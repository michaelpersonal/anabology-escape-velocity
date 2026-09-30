# How ESCAPE VELOCITY was made

**ESCAPE VELOCITY** is a 5:06 lyric music video. It's a techwear fashion show where each "Look N" is a Silicon Valley meme, walked by an AI model who is also a fashion model. A split-flap board counts down "18 MONTHS TO ESCAPE THE PERMANENT UNDERCLASS" until it flips to "THERE IS NO UNDERCLASS" and the catwalk lifts off.

It was made in about 19 hours of wall-clock time, from the first message to the final colour master:

- **anabology** directed and made every taste call, in about 50 messages.
- **Claude** (Anthropic's model, running in Claude Code) was the production team: research, lyrics, storyboard, prompts, the edit, and every frame of motion design.
- **Tools:** Midjourney made the images, Suno the song, and Seedance 2.5 the moving shots. A custom JavaScript engine drew everything else on top, on the beat.

<!-- zip-only -->This folder holds the full record: every Midjourney and Seedance prompt, the Suno fields, anabology's direction, and the agent prompts that ran the production.<!-- /zip-only -->

![24 frames from the final video, one every 12.8 seconds.](frames-final.jpg)

---

## The spark

It started from **"I'm Upping My P(doom)"**, a riso anime-idol Claude video by @donaldjewkes, made from a single long Claude prompt that remade @other__reality's earlier Opus 5.5 video of the same song. anabology shared that prompt<!-- zip-only --> (it's in [orchestration.md](orchestration.md))<!-- /zip-only --> and asked for their own version in their own taste:

> "i want to make my own video, different style, more aligned with teh taste i have logged and ranked and expressed in this design-ref project … using my midjourney profile for a lot of the design and inspo … a different style of song, not claude-pop but somehting.. more algined with the midjourney high fashion, techno xerox dithered white-pilled cyperpunk 2077 dystopic future aesthetic … but same lyrical cleverness and density."

*design-ref* is anabology's design workshop. It holds their logged and ranked taste (which images and layouts they like, measured), style guides, and a video pipeline that Claude built and extended during this project.

## The stack

| Role | Tool | How it was used |
|---|---|---|
| Director | anabology | Taste, concept picks, the song pick, and short notes at every checkpoint |
| Production team | Claude (Claude Code) | Planning; multi-agent workflows for research, lyrics, storyboard and animation; every script, prompt and frame |
| Art department | **Midjourney v8.2** with `--raw --hd` and anabology's personal profile | 188 prompts, 636 images, 130 plates. Driven through anabology's own logged-in browser by an automation client |
| Song | **Suno v6** | Custom lyrics, style and exclude fields. anabology picked the take by ear |
| Moving shots | **Seedance 2.5** (via OpenRouter) | 47 clips plus 30 continuation clips. Each is conditioned on the Midjourney plate **and** the exact slice of the song, so she lip-syncs the real vocal |
| GPU box | a home RTX 3090 Ti | Stems (htdemucs), beat map, word-level forced alignment (wav2vec2), depth maps for 2.5D, object and face tracking (Grounding DINO), LatentSync as a lip-sync fallback, exemplar-based video colourization |
| Motion design and edit | a custom JS engine | Headless Chromium: canvas plus a WebGL print pass. Every frame is a pure function of time. It draws 2.5D depth parallax, kinetic lyrics on each word's time, and all the explaining graphics |

## How it was made, step by step

1. **Research and lyrics** (multi-agent).
   - Research agents harvested the San Francisco tech timeline: the live memes, the recent events, and the longevity stories. Every item was fact-checked by a separate verifier agent.
   - Four lyric writers then worked from different angles: density, tension, hook and fashion. Judges scored them, a merger combined them, and a critic pass followed.
   - The verses are deadpan spoken word, so every line can carry a reference. The chorus is a euphoric trance lift ("(It's so over?) WE'RE SO BACK!").
2. **The song.** A Suno v6 style prompt ("fashion show electroclash techno, 128 BPM … deadpan female spoken-word verses … euphoric sung female trance chorus with a supersaw lift…"). anabology picked a full 5:06 take: "lets do this one … we can stretch it and do the full 5 minutes. might as well!"<!-- zip-only --> See [prompts-suno.md](prompts-suno.md).<!-- /zip-only -->
3. **Listening to it.** On the GPU box: stems, a beat map (the song accelerates from 131.5 to 133.9 BPM), and a start and end time for every word. Everything afterwards is placed on that grid.
4. **Her.** The lead was defined as a written canon: a black blunt jaw-length bob, one clay-orange streak, an eight-pointed clay spark hair clip, a headset microphone, a white cropped puff-sleeve shirt, a black pleated coated-nylon skirt with a harness belt and a garment tag, and knee boots.
   - Midjourney v8.2 has no `--oref`, so identity was tried three ways: GPT-image identity passes, face-sheet image prompts, and plain prompt text.
   - Identity passes drifted from the Midjourney look.
   - Face sheets over-conditioned: a close-up-sized head on a distant figure.
   - **What worked:** the canon written into every prompt, plus an explicit descriptor ("a young Caucasian American woman with pale skin and light freckles"). Without it, Midjourney drifted her ethnicity from shot to shot.

   ![The first Midjourney batch was a casting call: three hair directions (platinum, black, clay-orange), each as a turnaround, a data-hall catwalk shot and a face sheet. The black bob with one clay-orange streak became the lead: the silhouette reads at thumbnail size, and the clay colour stays a small accent.](lead-casting-ev01.jpg)
5. **Storyboard** (multi-agent).
   - Three director agents boarded the song independently: fashion film, meme density and narrative. Judges scored them, and a head director merged the best into one board: 141 shots across 9 chapters.
   - Every shot carries its lyric, a type mode (subtitle, coverline, masthead or strobe), its plate prompt, its camera, and whether it gets a Seedance clip.
   - anabology reviewed a storyboard PDF and approved it ("looks good, i approve"). They added notes, such as: two clips must never start from the same frame, and repetitive 2.5D panels become pure motion design.
6. **Midjourney plates.** 188 prompts in 15 batches; 159 ran to completion, four images each (636 images).
   - Every prompt is a concrete scene, usually with a declared empty area for type. It ends in the video's family of style words:
     - the palette and light: "blue-black and steel blue, one small red status lamp as the only warm light"
     - the grain: "fine silver grain"
     - the finish: "cinematic 35mm film still"
     - always: "no text, no letters, no logos"
   - Nearly all ran with `--ar 16:9 --v 8.2 --raw --hd` and anabology's personal profile. A few were image-weighted face-sheet tests (`--iw 0.5`), and one early `--oref` test was rejected by v8.2.
   - A typical plate prompt: `a vast low datacenter on a black plain at night, steam plumes rising from its roof, a row of loading bays lit white, one red aviation lamp, a small white robotaxi turning into the nearest bay, a passenger silhouette in its rear window, the top half empty night sky, blue-black #0f1216 and steel blue, one small red lamp as the only warm note, fine silver-gelatin grain, cinematic stillness, no text, no letters, no logos`
   - Picks became either a 2.5D shot (animated in code over a depth map) or a Seedance start image.<!-- zip-only --> See [prompts-midjourney.md](prompts-midjourney.md).<!-- /zip-only -->
7. **Seedance 2.5, with the song inside the prompt.**
   - Each clip gets the plate as `@Image1` and the exact window of the vocal as `@Audio1`. The prompt quotes the words sung in that window: `@Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "…"`.
   - anabology spotted the key fact: "its perfectly synced while in seedance, but the audio changes when it desyncs." Seedance copies the reference audio into its own soundtrack, and the mouth follows that soundtrack.
   - So a script compares the clip's soundtrack with the real vocal to find the point where it drifts. The edit cuts on the last eighth note before it, and a continuation clip starting from that frame covers the rest.
   - About 86% of sung seconds were verified in sync, with LatentSync as the fallback.
   - Cost: about $93 for 91 submissions and 421 seconds of 720p.<!-- zip-only --> See [prompts-seedance.md](prompts-seedance.md).<!-- /zip-only -->

   ![The sync check on one of the first test clips. Top: the vocal Seedance was given, with each word's aligned time. Middle: the soundtrack Seedance returned, which the mouth follows. Below: how closely they match over time, and the timing offset. This clip stays in sync to the end; where the match drops under the threshold, the edit cuts and a continuation clip takes over.](lipsync-check.png)
8. **Motion design** (multi-agent).
   - One animator agent per chapter wrote that chapter's code. An art-director agent rendered it and reviewed real frames. The animator then applied the fixes.
   - What's on screen:
     - every word, on its aligned time
     - the split-flap countdown
     - look cards set as model cards and garment tags
     - computer-vision boxes tracked to her
     - 2.5D parallax from depth maps
     - graphics that explain each joke
   - anabology's bar: "motion graphics and motion design, not just animated lyrics but things that fit the words being said … almost explaining the words with visuals."
9. **v1 to v2.** anabology on v1: "way too.. gray … loses the Midjourney magic." The print pass became a colour halftone.
   - Seedance clips made from monochrome start frames had come back grey. They were recoloured with exemplar-based video colourization (Deep Exemplar, CVPR 2019), using each shot's own Midjourney image as the colour exemplar.
   - The lesson: keep generation inputs in colour, and apply the look in post.
10. **Render.** 7,354 frames at 1920×1080, rendered in about 63 minutes on a 4-core machine, then encoded as a CRF 16 master.

## What worked, in short

- **Midjourney as the art department, with a profile as the taste.** A personal profile plus `--raw` and one consistent family of style words kept 130 plates in one world. Character identity lived in the prompt text, not in reference images.
- **Seedance with the audio in the loop.** Image plus audio reference, the exact sung words quoted, and sync *measured* rather than eyeballed. Where sync drifts, cut and continue from the frame.
- **Code on top of video.** Generated footage is the plate; the meaning (lyrics on the beat, explaining graphics, a through-line device) is drawn in code, so it's exact and on the beat.
- **Agents in parallel, one human with taste.** Research, lyrics, storyboards and animation fanned out across agents with judges and reviewers. anabology spent their attention on a handful of decisive notes.

## Numbers

| | |
|---|---|
| Song | 5:06.4 · Suno v6 · 131.5 → 133.9 BPM |
| Edit | 141 shots · 9 chapters · lyric video (every word on its time) |
| Midjourney | 188 prompts · 636 images · 130 plates used · v8.2 `--raw --hd` with anabology's profile |
| Seedance 2.5 | 47 clips + 30 continuation clips · 91 submissions · 421 s at 720p · ≈ $93 |
| Claude | Opus 5.5 (1M context) · 1.4B tokens · ≈ $626 at API prices, run on a Claude Max subscription |
| Render | 7,354 frames at 1080p · ~63 min · CRF 16 master |
| Time | ~19 h from the first message to the v2 master · about 50 messages from anabology |

<!-- pagebreak -->

## What it cost in Claude tokens

Measured afterwards from Claude Code's own records: the per-turn cost totals, which include every subagent and workflow, and the per-call usage in the session transcript.

- **About $626 at API list prices, and 1.4 billion tokens**, from the first message until the next project began ($604 by the final master). anabology ran it on a Claude Max subscription, so this is what the same work would cost on the API, not what was paid.
- **By model:** Opus 5.5 with 1M context $607; Haiku 4.5, Claude Code's helper for web search, $14; Fable 5.1, used for the first 25 minutes, $5.

| Where | Cost | Share |
|---|---|---|
| Animation: an animator, an art director and a fixer agent per chapter, plus a first attempt that was restarted (40 agent runs, 3,145 tool calls) | $301 | 48% |
| The main session: planning, every Midjourney, Suno, Seedance, GPU and render script, and the edit | $185 | 30% |
| Storyboard: 3 director agents, 3 judges and a head director | $95 | 15% |
| Research and lyrics: a 31-agent workflow plus web search | $44 | 7% |

- **Why so many tokens:** every API call re-reads the whole conversation from the prompt cache, and 96% of all tokens were those re-reads. The main session's context sat around 565k tokens across 1,028 calls; the animation agents ended at about 350k each. By type, Opus cost $270 in cache reads, $190 in cache writes and $147 in output, including thinking.
- **Images were a small share:** the main session looked at 138 images (Midjourney grids, reference frames, contact sheets and 15 browser screenshots). Re-reading them from cache on later calls cost about $22, under 4% of the total. The agents' transcripts weren't kept, so their image share can't be measured.
- **Thinking effort:** research and lyrics ran at the default effort; from the storyboard on, max. The chapter animators and fixers were set to high.

<!-- zip-only -->

## Files in this folder

- [how-escape-velocity-was-made.pdf](how-escape-velocity-was-made.pdf): this write-up as a PDF.
- [direction-log.md](direction-log.md): anabology's direction, verbatim and in order (lightly redacted).
- [orchestration.md](orchestration.md): the original "one prompt", and the prompts given to the research, storyboard and animation agents.
- [prompts-midjourney.md](prompts-midjourney.md): all 188 Midjourney prompts, by batch.
- [prompts-seedance.md](prompts-seedance.md): every Seedance prompt, including the continuation clips and the early lip-sync tests.
- [prompts-suno.md](prompts-suno.md): the Suno style, exclusions and lyrics.
- [frames-final.jpg](frames-final.jpg), [lead-casting-ev01.jpg](lead-casting-ev01.jpg), [lipsync-check.png](lipsync-check.png): the pictures above.

<!-- /zip-only -->
