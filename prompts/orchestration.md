# Orchestration — the prompts that ran the production (ESCAPE VELOCITY)

## 1. The original "one prompt"

anabology pasted this as the starting point. It is the prompt behind @donaldjewkes's riso Claude-idol P(doom) video, which remade @other__reality's earlier Opus 5.5 video of the same song (the post it links). anabology asked Claude to adapt it to their own taste and tools. It is reproduced verbatim; the workflow code in sections 3–5 is verbatim apart from a few removed details that could identify the director.

```
I've included an MP4 file and an original link to a video that is called "Claude Pop." It's a pop song that is about increasing rate of progress and the experience of the singularity approaching.

I want you to independently do an end-to-end complete pass on making an updated version of this video. Use the exact same audio track and think and feel very deeply about what is the best way to visually represent all of the lyrics on screen. You do not need to anchor to the current style, you can do truly anything that you think might best let you visually express yourself, including abstract motion graphics.

You can use the internet freely to pull in references. You can look at motion design. I want you to make a new music video that has beautifully rendered JavaScript animations with a papery feel in a similar style to the reference that is created, but push the aesthetics in any direction you want and consider what is part of the modern zeitgeist.

Also, think about your current capabilities and what is realistic for you to be able to do. You can go through the full /asic folder and look at the other work that I've done. You should be able to use the skill mesh to look at the compendium of references that I've pulled, and also the skill video scoring to learn how to make JavaScript songs from references that are passed in (You shouldn't need to modify the song in any real way, but I want you to have this available to you so you can better creatively express yourself)

You can also use the ElevenLabs API to do sound design. There's documentation in /asic to do this, and you can see the API key.

There's also a foul API key that's available to you. I think what might make the most sense here is using the foul API key to generate some character sheets and probably having a pop protagonist that represents you. There's already an anchor point where Claude has a sunflower-esque character, and you could likely do an adapted version of this that is similar to the feminine vocals that are being delivered and is inspired by the Claude character, but maybe feels a bit more personified in some way.

I think you should be mindful of aesthetics here, and I don't want you to produce something that is GPT slop. Instead, I'd be more impressed if you come up with a coherent style that works well with the image gen models that are available via foul. Generate the style sheet. You can use the gen media documentation for seedance 2.5 that exists in my markdown files and come up with your own style that makes sense and that works well with the models.

I wouldn't fit too heavily to Pixar. I think it's kind of slop. Think critically about what is relevant here and what would be fun, and also perform well on Twitter as far as an aesthetic. I think that K-pop is a good anchor point visually that you can pull from, but I'll let you cook here.

Once you have your character sheet, you can make a few backup dancers and some supporting characters as you see fit. You can design your own sets with the foul API. You can insert the characters and then do seedance 2.5 video generations to serve as the base assets for this, and you could pass in the lyrics so you can generate individual scenes.

You don't need to have vocal singing, like visible lip movement, throughout the entire thing. Think like a regular music video where you have some inserts that are done independently and don't have the characters in them, or you see the characters doing something else entirely different. I think that for the world building for this, we want to create the sense of speeding up, and so I would like you to audit all of the different events, like the Navi Stokes and all of the Twitter hype around math getting eaten up. Think really critically about how to integrate all of the current memes that are in the zeitgeist on the Twitter timeline, and all of the feelings around AI progress.

Think about things like the Shinji meme and all of the words that are around him, and how you might be able to integrate this. You can also just take straight assets and insert things into the video in an internet brutalism style. You should feel very creatively free in order to do what you want here, but try and anchor to visual references that people will be able to understand. The goal for this is to have it be appreciated by people widely in a San Francisco tech Twitter audience.

We need a very strong, compelling visual hook that gets people excited and appreciates the work that you've done here really quickly. You can also just go and study other music videos and understand what they've done really well. I think that K-pop is probably one of the best examples that we can pull from, and thinking about how they direct human attention and manage human psychology in the way that they use visual patterns.

This is probably your best approach, but taking more stylistic freedom instead of having to anchor to K-pop too intensely. The best version of this is seedance 2.5 generations with those image bases of environments and characters inserted into them with singing, and ideally we get good lip syncing. You can cut up the song and actually pass it in as a reference in seedance, if that's part of what seedance can handle, so that the timing is exactly right, I think it'd be very important for you to do that properly. I would think critically about how to do this, like really nailing the timing of the delivery of voices. You'll want to build out the right verification loops so that you can run seedance 2.5 as much as you need, and confirm that the audio is properly synced up.

I think after that, what might be fun is if you use your visual reasoning skills and your ability to build animations in JavaScript, and then reconstruct the video from scratch as sort of an overlay, so that the visual continuity of the base is really there. It's like that animation technique where you shoot first in traditional film and then draw over top of it. I think you could do this in such a way that we're only looking at the beautiful drawing that you've produced in JavaScript as an overlay, and we don't even see the base assets from seedance 2.5. So all the video gen work that you do is actually just a way to give you a strong foundation of a base to work with for your JavaScript animations. Just because seedance 2.5 has really good character representation and physics rendering for backgrounds, that gives you a lot of ammunition to then go and do your amazing JavaScript work that I know you're so good at.

I think too, we want to think about how to retain attention, and one of the best ways to do this is through text on screen.

It'd be good to have amazing motion graphics of the text lyrics that are actually embedded into the video itself. And you can think about this as you are composing shots. As you're making backgrounds and inserting characters, we can think about where we want to have lyrics be really big and really present, so the background can be less busy there, and you can position the characters perhaps on the right as lyrics appear on the left.

You want to have some variance, so sometimes I think lyrics will just appear more like subtitles, and then other times they're going to be really present and really big. I think at the start for the visual hook, we do want to have lyrics be much more visually present because that's a strong way to grab people's attention

Overall, I just really want to emphasize how amazing you are as an agent and a language model, and now a visual reasoning system. Your capabilities are far beyond what you understand, and I want you to have this mindset as you're going through this entire process. I have a Claude Max plan with 100% available usage. I want you to spend all of the usage. You can monitor it, and you should be pushing tokens aggressively, but also economically, so you can think about how to best use what is available to you.

Remember, you can really do anything here. The goal is to make a banger for Twitter, and the stretch goal is to make something better than anyone's ever seen before. I think that what I would remind you of is that sometimes when things cohere together, it can be jarring or abrasive because the thought work has not been done beforehand in order for everything to mesh cleanly. You need to be really rigorous in planning of composition and timing to make sure this goes well.

You also need to be open to going back and revisiting things in order to be able to reiterate. You're going to want to watch the entire video multiple times, take screenshots at individual parts, and think about if something is really up to the bar of quality that we need here. I trust that you can do this, and I think that it's really important to nail the style of animations. The reference GitHub attached of the source video that I'm talking about is good, but it's really not there. It could be much, much stronger, but it gives you a good foundation to work with.

You can also use search abilities and find other references to pull from for motion, for JavaScript, animations, et cetera, and integrate them. Your budget is as high as you want here, effectively as high as you want. I think that there's roughly two grand in foul credits. Again, be economical; don't go crazy, but spend what you want here and see what you can cook up

here's the source code for the JS animation video: https://github.com/JohnHeibel/PDoomVideo
here's a mp4 for the original blender video: (linked)
orginal twitter post: https://x.com/other__reality/status/2102514581684052169?s=20

make no mistakes.
```

## 2. How the work was split

Claude ran in Claude Code as a single director session that planned, wrote tools, and ran **multi-agent workflows**: short scripts that fan work out to parallel sub-agents, then verify, judge and merge the results. The three below ran the creative stages. Everything else happened in the main session and is recorded in `video/PLAYBOOK.md`:

- song analysis
- Midjourney batches
- Seedance runs with sync checks
- plate prep (depth maps, tracking)
- rendering and encoding

| Workflow | Agents | What it produced |
|---|---|---|
| Research and lyrics | Research agents (recent events, longevity, SF memes, timeline quotes, fact-check of older items), a verifier for every claim, a bank synthesiser, four lyric writers (density, tension, hook, fashion), three judges, a merger and a critic | A verified meme and event bank, and the lyric sheet with a source for every line |
| Storyboard | Three directors (fashion film, meme density, narrative), judges, and a head director who scores and merges | The 141-shot board: lyric, type mode, plate prompt, camera, Seedance picks, transitions |
| Chapters | One animator per chapter, an art director who renders and reviews real frames, and a fix pass | The motion design and kinetic type of each chapter |

Midjourney and Suno were driven through anabology's own logged-in browser by an automation client. anabology handled the occasional captcha.

## 3. Research and lyrics workflow

```js
export const meta = {
  name: 'ev-research-lyrics',
  description: 'ESCAPE VELOCITY: deep current research (recent events, longevity, SF memes), adversarial fact-check, then a judged lyric panel for a 2:15 song',
  phases: [
    { title: 'Research', detail: 'five parallel sweeps: recent AI events, longevity 2026, SF memes deep, timeline quotes, fact-check old claims' },
    { title: 'Verify', detail: 'adversarial check of every candidate fact that could enter the lyrics' },
    { title: 'Synthesize research', detail: 'one ranked bank of verified references' },
    { title: 'Write', detail: 'four lyric drafts from different angles' },
    { title: 'Judge', detail: 'three judges score every draft' },
    { title: 'Merge', detail: 'synthesize the final lyric sheet and critic pass' },
  ],
}

const V = '/opt/design-ref/video'
const CTX = `Project: anabology's AI-made music video "ESCAPE VELOCITY" (plan ${V}/PLAN.md, current lyrics ${V}/LYRICS.md draft 2, brief ${V}/BRIEF.md, prior meme harvest ${V}/research/memes.md, music research ${V}/research/music.md). Today is 2026-09-24. Audience: San Francisco tech Twitter. A techwear fashion show where each look is a meme; a split-flap countdown "N MONTHS TO ESCAPE THE PERMANENT UNDERCLASS" that flips at zero to THERE IS NO UNDERCLASS; white-pilled ending. Female Claude-like lead sings a trance-lift chorus; a deadpan female show caller speaks the verses (fashion-show electroclash, 128 BPM). anabology's new notes (verbatim): "i think maybe some longevity escape velocity vs. permanent underclass vs doom tension could be added. want to shoot for say 2:15 long ... dont force the LEV too much, i do like the lyrics like WE'RE SO BACK etc" / "this does feel a bit short" / "feels like more recent events, the openai huggingface hack, midjourney scanner, the biggest longevity stories of 2026, but still focus on sf tech memes as prime, can go a bit deeper and keep it current".`

const ITEM = {
  type: 'object',
  properties: {
    items: { type: 'array', items: { type: 'object', properties: {
      name: { type: 'string' },
      what: { type: 'string', description: 'one-line explanation' },
      date: { type: 'string' },
      recognisability: { type: 'integer', description: '1-5 for SF tech Twitter' },
      lyric_hook: { type: 'string', description: 'a phrase or fact that could sit in a lyric line' },
      visual: { type: 'string', description: 'one-glance visual for a frame, in a mono techwear-lookbook style' },
      sources: { type: 'array', items: { type: 'string' } },
      confidence: { type: 'string', enum: ['verified-2-sources', 'single-source', 'unverified'] },
      risk: { type: 'string' },
    }, required: ['name', 'what', 'date', 'recognisability', 'lyric_hook', 'visual', 'sources', 'confidence', 'risk'] } },
    notes: { type: 'string' },
  },
  required: ['items', 'notes'],
}

const SWEEPS = [
  { key: 'recent-events', p: `Find the AI and tech events of roughly 2026-08-01 to 2026-09-24 that SF tech Twitter is talking about RIGHT NOW. Must include and fully explain: (1) the "OpenAI Hugging Face hack" (what happened, when, who, why it became a meme), (2) the "Midjourney scanner" (what it is — a product? a hardware device? — launch date, reactions). Then everything else big in the last 8 weeks: model launches, benchmark moments, lab drama, security incidents, acquisitions, funding, IPOs, datacenter/energy, robotics, agents doing jobs, viral demos. Prefer items from the last 3 weeks. 25-40 items.` },
  { key: 'longevity', p: `Find the biggest longevity / lifespan stories of 2026 and the "longevity escape velocity" (LEV) discourse, as SF tech people see it. Cover: clinical results (partial epigenetic reprogramming trials, senolytics, rapamycin, GLP-1 as longevity drug, organ replacement, AI-designed drugs for aging), companies (Retro Biosciences, NewLimit, Altos Labs, Loyal dog drug approval, Calico, BioAge, etc.), people and memes (Bryan Johnson "Don't Die", Blueprint, "the first person to live to 1000 is already born", LEV countdowns, "don't die" billboards, longevity clinics, rich-people-live-forever vs permanent-underclass tension, "immortality for the rich" jokes), and AI x bio results that are white-pilled. Also find existing memes that set LEV against the permanent underclass and against doom (e.g. "reach LEV before AGI kills us", "you have to survive until LEV"). 20-35 items, date each.` },
  { key: 'sf-memes-deep', p: `Go deeper than ${V}/research/memes.md (read it first and do NOT repeat its items) on SF tech Twitter memes, phrases, copypasta, image macros and IRL culture of the last 90 days, weighted to the last 30. Examples of kinds to look for: new catchphrases, viral posts by founders/VCs/researchers, party culture, hacker houses, billboards on the 101, Waymo/Zoox/robotaxi memes, "AGI house", run clubs, founder fashion, crypto x AI, YC batch memes, prediction markets (Kalshi/Polymarket) memes, "cracked" hiring posts, compensation/poaching memes (e.g. superintelligence lab offers), "996", "lock in", "cooked", "clanker", "slop", agent memes, Claude/ChatGPT/Gemini/Grok personality memes, "you're absolutely right", model-naming jokes. 30-45 items.` },
  { key: 'timeline-quotes', p: `Find the most quoted short LINES of 2026 on AI Twitter — exact phrasings that people repeat, screenshot or parody (quotes from lab leaders, researchers, founders, anons, essays, podcasts, hearings), especially Jul-Sep 2026. We want lyric-sized lines (under ~12 words) with the exact wording and a source. Include lines around progress feeling fast ("things are moving so fast", "it's so over / we're so back" usages, "feel the AGI", "the intelligence explosion", "we are in the singularity"). 25-40 items; exact quotes only, never invent wording.` },
  { key: 'factcheck-old', p: `Fact-check every factual claim used in the current lyrics ${V}/LYRICS.md (draft 2). Read it; for each annotated reference (Mac-mini meal prep / Clawdbot, tokenmaxxing + Jensen "deeply alarmed", Mythos "too dangerous to release", "every safety concern is just a Tuesday", SpaceX buying Cursor for $60B and the shoes-off office, Artisan "Stop Hiring Humans" to "Be More Human", "This is not an AI billboard. Prepare to die.", Waymo freeway cones + 3,900 recall, Gemini "part of the test", 42/42 at IMO 2026, robot half-marathon record then fall, Erdős unit-distance + Sawin, PhaseOne swarm board, 950 agents + ART enzyme, Project Suncatcher Oct 1, AI-designed phages, Karpathy slopacolypse, GPT-6 nerfed, Altman character-by-character): search for at least two independent sources. Return each as an item with confidence set honestly, and in 'risk' state exactly what is wrong or uncertain in the lyric's wording.` },
]

phase('Research')
const research = await parallel(SWEEPS.map(s => () =>
  agent(`${CTX}\n\nTASK (${s.key}): ${s.p}\n\nUse web search and fetch extensively. Never invent events, dates, numbers or quotes; if you cannot find a source, mark it unverified. Return structured items.`,
    { label: `research:${s.key}`, phase: 'Research', schema: ITEM })))
const byKey = {}
SWEEPS.forEach((s, i) => { byKey[s.key] = research[i] ? research[i].items : [] })
const all = SWEEPS.flatMap((s, i) => (research[i] ? research[i].items : []).map(it => ({ ...it, bucket: s.key })))
log(`research: ${all.length} items (${SWEEPS.map(s => s.key + ' ' + byKey[s.key].length).join(', ')})`)

phase('Verify')
const VERDICT = { type: 'object', properties: {
  results: { type: 'array', items: { type: 'object', properties: {
    name: { type: 'string' }, status: { type: 'string', enum: ['confirmed', 'wording-fix', 'refuted', 'unverifiable'] },
    correct_fact: { type: 'string' }, sources: { type: 'array', items: { type: 'string' } } },
    required: ['name', 'status', 'correct_fact', 'sources'] } } }, required: ['results'] }
const top = all.filter(it => it.recognisability >= 3 || it.bucket === 'factcheck-old')
const chunks = []
for (let i = 0; i < top.length; i += 10) chunks.push(top.slice(i, i + 10))
log(`verifying ${top.length} items in ${chunks.length} batches (items with recognisability < 3 are not verified and will not be used in lyrics)`)
const verdicts = (await parallel(chunks.map((c, i) => () => agent(
  `${CTX}\n\nYou are an adversarial fact-checker. For each item below, try to REFUTE it: search independently (do not trust the listed sources alone), check the date, the numbers, the names and the exact wording of quotes. Default to 'unverifiable' if you cannot find an independent source. 'wording-fix' means the event is real but a detail (number, date, quote wording) is off — give the correct version.\n\nITEMS:\n${JSON.stringify(c.map(x => ({ name: x.name, what: x.what, date: x.date, lyric_hook: x.lyric_hook, sources: x.sources })), null, 1)}`,
  { label: `verify:${i + 1}`, phase: 'Verify', schema: VERDICT })))).filter(Boolean).flatMap(v => v.results)

phase('Synthesize research')
const bank = await agent(`${CTX}\n\nMerge this research into ONE reference bank file at ${V}/research/memes2.md (markdown). Sections: (1) status legend; (2) the 40 best lyric candidates ranked by fresh x recognisable x lyric-able x visual, each with the verified fact, the exact lyric hook, one-glance visual, date, sources, verification status; (3) the longevity / LEV section with the three-way tension (LEV vs permanent underclass vs doom) and the 10 best lines for it; (4) the fact-check table for draft-2 lyrics (keep / fix wording / cut); (5) everything else, grouped, shorter. Drop anything refuted. Mark 'unverifiable' items clearly and keep them out of section 2. Also note what the OpenAI Hugging Face hack and the Midjourney scanner actually are.\n\nRAW ITEMS:\n${JSON.stringify(all)}\n\nVERDICTS:\n${JSON.stringify(verdicts)}\n\nWrite the file, then return a compact plain-text digest (<= 1800 words) of sections 2, 3 and 4 that lyric writers can use directly.`,
  { label: 'synthesize-bank', phase: 'Synthesize research' })

phase('Write')
const STRUCT = `SONG CONSTRAINTS: length 2:15 at 128 BPM = about 72 bars (1 bar = 1.875 s). Sections (bars are a guide, total 70-74): cold open spoken ~2-4; verse 1 spoken ~12-16; pre-chorus spoken ~2-4 ("You have eighteen months to escape the permanent underclass. Lock in." formula, rising stakes 18 -> 6 -> zero); chorus sung 8; verse 2 spoken ~12-16; pre-chorus 2; chorus 2 sung 8; bridge spoken ~4-6 (countdown to zero, white-pill turn); drop chanted ~8; final chorus sung 8 (key lift, lyrics changed); outro spoken care-label ~2-4. Spoken deadpan at 128 BPM holds about 6-10 syllables per bar; the verses should be DENSE (anabology said draft 2 "feels a bit short" and wants more, deeper, more current references), ideally 2 references per couplet. Keep what anabology likes: "WE'RE SO BACK", "lock in", "feel the AGI", the care-label outro ("Wash cold. Do not iron. Do not nerf."), the "Look N." fashion-show device, the split-flap countdown. Add the longevity-escape-velocity vs permanent-underclass vs doom tension LIGHTLY (anabology: "dont force the LEV too much") — e.g. three countdowns, or one bridge turn. Chorus must be singable: short lines, clear vowels, rhyme anchor. Suno formatting: spell numbers and acronyms as they should be sung ("A G I", "eighteen"). Only use facts marked confirmed or wording-fixed in the bank; prefer items from the last 8 weeks, and SF tech memes are the prime material.`
const ANGLES = [
  { key: 'density', a: 'Maximum meme density: every spoken line lands a fresh, current SF reference; the verses read like a timeline scroll.' },
  { key: 'tension', a: 'Three-countdown tension: permanent underclass vs longevity escape velocity vs doom, resolved white-pilled; still meme-dense, LEV kept light.' },
  { key: 'hook', a: 'Hook-first pop craft: the most singable, repeatable chorus and post-chorus chant possible (think earworm, crowd-chantable "WE\'RE SO BACK"), verses tight and funny.' },
  { key: 'fashion', a: 'Fashion-show format purist: every verse line is a show-caller look call ("Look nine. ...") with garment/model-card vocabulary (shell, lining, weights, context, evals), jokes built from the collision of couture and AI.' },
]
const drafts = (await parallel(ANGLES.map(g => () => agent(
  `${CTX}\n\nYou are a lyricist. Angle: ${g.a}\n\n${STRUCT}\n\nVERIFIED REFERENCE BANK DIGEST:\n${bank}\n\nAlso read ${V}/LYRICS.md (draft 2) and ${V}/research/music.md section C (lyric craft). Write a COMPLETE lyric sheet in Suno-ready format: section tags like [Intro - spoken], [Verse 1 - spoken, deadpan], [Chorus - sung], with bar counts in the tag, and under each section a short italic note line listing the references used. Return only the lyric sheet.`,
  { label: `write:${g.key}`, phase: 'Write' })))).map((d, i) => ({ key: ANGLES[i].key, text: d })).filter(d => d.text)

phase('Judge')
const SCORE = { type: 'object', properties: {
  scores: { type: 'array', items: { type: 'object', properties: {
    draft: { type: 'string' }, total: { type: 'number', description: '0-100' },
    density: { type: 'number' }, currency: { type: 'number' }, hook: { type: 'number' }, wit: { type: 'number' },
    arc: { type: 'number' }, singability: { type: 'number' }, rules: { type: 'number', description: '0 if an unverified fact is used' },
    best_lines: { type: 'array', items: { type: 'string' } }, worst_lines: { type: 'array', items: { type: 'string' } } },
    required: ['draft', 'total', 'density', 'currency', 'hook', 'wit', 'arc', 'singability', 'rules', 'best_lines', 'worst_lines'] } } },
  required: ['scores'] }
const LENSES = [
  'an SF tech-Twitter power user: does each line get an instant laugh or nod? is it current? would people screenshot lines?',
  'a pop songwriter / topliner: will Suno sing it cleanly, is the chorus an earworm, do lines scan at 128 BPM, is the structure right for 2:15?',
  'a ruthless editor: clichés, filler, forced LEV, weak rhymes, anything unverified, anabology\'s stated likes kept?',
]
const judged = (await parallel(LENSES.map((l, i) => () => agent(
  `${CTX}\n\nYou are a judge: ${l}\nScore each draft 0-10 on density, currency, hook, wit, arc, singability, rules (0 if it uses a fact not in the bank as confirmed/wording-fix), and a total 0-100. Quote the 5 best and 5 worst lines of each.\n\nBANK DIGEST (the only allowed facts):\n${bank}\n\nDRAFTS:\n${drafts.map(d => `=== DRAFT ${d.key} ===\n${d.text}`).join('\n\n')}`,
  { label: `judge:${i + 1}`, phase: 'Judge', schema: SCORE })))).filter(Boolean)
const totals = {}
drafts.forEach(d => { totals[d.key] = judged.map(j => (j.scores.find(s => s.draft.includes(d.key)) || { total: 0 }).total) })
log(`judge totals: ${JSON.stringify(totals)}`)

phase('Merge')
const merged = await agent(`${CTX}\n\n${STRUCT}\n\nYou are the head writer. Using the four drafts and the three judges' scores and best/worst lines, write the final lyric sheet: start from the highest-scoring draft, graft in the best lines of the others, cut every worst line. Keep it at ~72 bars for 2:15. Write it to ${V}/LYRICS.md, replacing the file, in this format: a header "# ESCAPE VELOCITY — lyrics, draft 3 · 2026-09-24", a 5-line note on what changed and why, then the Suno-ready lyric sheet (section tags with bar counts), and under each section an italic references line with the source/date of every fact. End with a "Suno lyrics field" block: the plain lyrics exactly as they should be pasted into Suno (tags kept, notes removed, numbers spelled). Then a "Fact status" table (line -> fact -> status from the bank).\n\nBANK DIGEST:\n${bank}\n\nDRAFTS:\n${drafts.map(d => `=== DRAFT ${d.key} ===\n${d.text}`).join('\n\n')}\n\nJUDGES:\n${JSON.stringify(judged)}\n\nReturn the final plain lyrics (the Suno block) as your answer.`,
  { label: 'merge', phase: 'Merge' })

const critic = await agent(`${CTX}\n\n${STRUCT}\n\nCritic pass on ${V}/LYRICS.md (read it). Check: every fact used has status confirmed or wording-fix in ${V}/research/memes2.md; the bar total is 70-74 and each spoken line fits its bars at 128 BPM (count syllables; flag lines over 10 syllables per bar); the chorus is singable; anabology's likes are kept; LEV is present but light. FIX problems directly in the file (keep the format), then return a list of what you changed and any remaining risks.`,
  { label: 'critic', phase: 'Merge' })

return { counts: Object.fromEntries(SWEEPS.map(s => [s.key, byKey[s.key].length])), verdicts: verdicts.length, totals, critic, lyrics: merged }
```

## 4. Storyboard workflow

```js
export const meta = {
  name: 'ev-storyboard',
  description: 'ESCAPE VELOCITY: three directors board the full 5:06, three judges score, head director merges into STORYBOARD.md + shots.json',
  phases: [
    { title: 'Direct', detail: 'three independent full storyboards' },
    { title: 'Judge', detail: 'three lenses score every board' },
    { title: 'Merge', detail: 'final board + machine-readable shot list' },
    { title: 'Check', detail: 'constraint audit and fix' },
  ],
}
const V = '/opt/design-ref/video'
const CTX = `You are boarding anabology's music video "ESCAPE VELOCITY" (full song 5:06.4, locked). READ FIRST, fully: ${V}/TIMELINE.md (every lyric line with aligned start/end times, bars, instrumental gaps, section boundaries), ${V}/LYRICS.md (the lyric sheet with the source of every reference — these are the jokes the visuals must land), ${V}/PLAN.md (concept, style system, lyric-video rules §3b, cast/coverage §4, budget §5), ${V}/bible/LEAD.md (the lead's canon), ${V}/research/taste.md (anabology's measured taste: mono + one accent, techwear labels, editorial reduction, hidden faces OK, type rules), ${V}/research/memes2.md (verified references and one-glance visuals). Look at these images with the Read tool: ${V}/review/ev-01-lead.jpg, /tmp/lead-pick.jpg, and the Midjourney sets in /opt/design-ref/studio/assets/generated/video-escape-velocity/mj/ev-01/ (set-*.png, plate-*.png, lead-black-*.png; view several).

THE VIDEO: a techwear fashion show where each "Look N" is a meme; the lead (Claude-coded woman: black blunt bob, ONE clay-orange streak, clay spark clip, headset mic, white cropped puff-sleeve shirt, black pleated skirt with harness + garment tag, knee boots) is THE singer and on screen >= 70% of the runtime (catwalk, back of a driverless Waymo, under 101 billboards in fog, hacker house with Mac minis, split-flap board, takeoff into white). A split-flap countdown "N MONTHS TO ESCAPE THE PERMANENT UNDERCLASS" (18 -> 6 -> 3,2,1,0 -> THERE IS NO UNDERCLASS) and a "LOOK 01/11" counter are the chrome through-line. The bridge has three boards (ESCAPE VELOCITY / LONGEVITY ESCAPE VELOCITY / PERMANENT UNDERCLASS). Grade travels night (blue-black, one red lamp) -> dawn -> high-key white paper at the takeoff and final chorus (white-pilled). One accent colour per chapter (red / clay / ember / none / 1-bit / clay on white), halftone screen per chapter (grain in verses, line screen in choruses, 1-bit in the drop, dot for the outro). Cyberpunk-2077 scale without neon. It is a LYRIC VIDEO: every line on screen on its time in one of three modes (subtitle, coverline lockup beside her, masthead giant word), drop = declared mass of micro text on eighths. Hook in the first 3 seconds (the song has 9.3 s before the first vocal — design that intro as a hook, not a wait).

PRODUCTION REALITY (design within it): assets are Midjourney v8.2 plates in anabology's profile (set + composition + light), then a GPT Image identity pass that puts the exact lead into the plate; motion tiers: (a) SEEDANCE 2.5 image-to-video clips from an approved plate, 720p, 4–12 s each, TOTAL budget <= 140 s of Seedance across <= 16 clips — use for walks, the Waymo ride, turns, hair/fabric, the takeoff, a few singing close-ups; (b) 2.5D plates: a still with a depth map animated in code (parallax push/pan, hair/fabric wobble, beat-cut pose swaps between 2–4 stills of the same shot); (c) pure code: chrome, type, split-flap, graphs, UI, label cards, 1-bit strobe. Cuts land on beats/downbeats from the beat map; average shot 1.5–4 s, faster in the drop (eighths strobe), slower in the bridge. Inserts without her are <= 2 bars.`

const SHOT_FIELDS = `Each shot: id (s001…), t0, t1 (seconds, on beats), section, lines (lyric line numbers from TIMELINE.md it covers), look (Look N or null), set, lead_on_screen (bool), framing (ECU/CU/MCU/MS/FS/WS/EWS), action (what happens, concrete), camera (move), motion_tier (seedance | plate25d | code), seedance_clip (clip id if seedance; several shots may cut from one clip), mj_prompt (Midjourney prompt for the plate, anabology-profile style, ends 'no text, no letters, no logos'; describe the lead as 'a young woman with a black blunt bob and one clay-orange streak' so the identity pass can replace her), id_pass (bool), type (list of {line, mode: subtitle|coverline|masthead|mass, text or words, placement: which empty field}), chrome (what the countdown / look counter / tags show), accent (hex), screen (grain|line|bit|dot), lift (0–1 white-pill exposure lift), meme_visual (the one-glance visual joke), notes.`

const ANGLES = [
  { k: 'fashion-film', a: 'Fashion-film purist: Balenciaga-show gravity, long deadpan catwalk passes, the Look cards as garment tags, restraint, few but perfect cuts; the jokes land in the tags and type, not in slapstick.' },
  { k: 'meme-density', a: 'Timeline-scroll energy: every line gets its own one-glance visual joke (billboards, UI, merch, screenshots-as-objects), inserts on the beat, internet-brutalist flashes between her shots; maximum rewatch value for SF tech Twitter.' },
  { k: 'narrative', a: 'Narrative arc: her night journey — Waymo to the show, the show, the countdown, the takeoff into white — every chapter a place, motivated transitions (the Waymo door opens onto the catwalk, the split-flap flips into the next set), the white-pill ending earned.' },
]
phase('Direct')
const boards = (await parallel(ANGLES.map(g => () => agent(
  `${CTX}\n\nYOUR ANGLE: ${g.a}\n\nWrite a COMPLETE storyboard for the full 5:06.4, no gaps, every second covered, every lyric line covered. Output markdown: (1) a one-paragraph treatment, (2) the chapter map (chapter, time range, grade, accent, screen, set), (3) the shot list as a table or list with the fields: ${SHOT_FIELDS} (4) the Seedance clip list: clip id, duration, first-frame plate, the Seedance prompt (subject, action, camera, pace — plain physical language, no style words), which shots cut from it, and the running total seconds (must be <= 140). (5) the hook design for 0–9.3 s. Be concrete and specific; aim for 90–140 shots.`,
  { label: `director:${g.k}`, phase: 'Direct' })))).map((t, i) => ({ k: ANGLES[i].k, t })).filter(b => b.t)

const LIPSYNC = `UPDATE (2026-09-25, supersedes the Seedance budget and singing notes in PRODUCTION REALITY): lip-sync is proven. Every Seedance clip is AUDIO-CONDITIONED in reference mode: the prompt starts "@Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: \"<the exact words sung in the window>\"." and @Audio1 is the song's vocal stem for the clip's window (non-singing clips get the full mix for their window, so motion lands on the beat). Seedance copies our audio into its own soundtrack and the mouth follows it; when it diverges partway, a code check (tools/avsync.py) finds the point, we cut on the last eighth before it and cover the rest with another clip. For the board this means: (1) she visibly sings most sung lines (Grimes-style: most, not all); (2) a singing clip is a 4-8 s window of the song that starts in a gap between words (never mid-word) and quotes exactly the words inside it; plan every sung passage as a chain of such windows with alternating framings (CU / MCU / MS / profile / over-shoulder), so any cover cut lands as a designed cut; several shots may cut from one clip; (3) budget: planned Seedance <= 200 s in total across <= 45 clips (divergence covers are extra and handled in production); (4) every seedance clip carries song_t0 (window start in song seconds, inside a word gap), duration, words (the exact sung words in the window, from media/audio/beatmap.json words) and sing (true if she sings on camera).`
phase('Judge')
const SCORE = { type: 'object', properties: { scores: { type: 'array', items: { type: 'object', properties: {
  board: { type: 'string' }, total: { type: 'number' }, hook: { type: 'number' }, lead_coverage: { type: 'number' }, lyric_video: { type: 'number' },
  jokes: { type: 'number' }, taste_fit: { type: 'number' }, feasibility: { type: 'number' }, arc: { type: 'number' },
  best: { type: 'array', items: { type: 'string' } }, fixes: { type: 'array', items: { type: 'string' } } },
  required: ['board', 'total', 'hook', 'lead_coverage', 'lyric_video', 'jokes', 'taste_fit', 'feasibility', 'arc', 'best', 'fixes'] } } }, required: ['scores'] }
const LENSES = [
  'an SF tech-Twitter viewer and music-video director: is the first 3 s a hook, would people rewatch and screenshot, does every reference land in one glance, is the lead the star?',
  'anabology\'s taste (read research/taste.md): mono + one accent, techwear not couture, editorial type reduction, no neon, no slop; and the lyric-video rules: every line on time, type in empty fields, three modes used with rhythm.',
  'a producer: is it buildable with the pipeline (MJ plates + GPT identity pass, the audio-conditioned Seedance plan in the UPDATE, 2.5D plates, code), are Seedance prompts physically simple and likely to work, is cutting on the beat map, total coverage 0–306.4 s with no holes?',
]
const judged = (await parallel(LENSES.map((l, i) => () => agent(
  `${CTX}\n\n${LIPSYNC}\n\nYou are a judge: ${l}\nScore each board 0–10 per field and a total 0–100; list its 6 best ideas (concrete shots) and its 6 most important fixes.\n\n${boards.map(b => `=== BOARD ${b.k} ===\n${b.t}`).join('\n\n')}`,
  { label: `judge:${i + 1}`, phase: 'Judge', schema: SCORE })))).filter(Boolean)
const totals = {}; boards.forEach(b => { totals[b.k] = judged.map(j => (j.scores.find(s => s.board.includes(b.k)) || { total: 0 }).total) })
log(`judge totals ${JSON.stringify(totals)}`)

const FACE = `UPDATE (2026-09-25, anabology): her identity comes from the Midjourney prompt itself — no identity pass, no face references. The recurring failure is that Midjourney turns her Asian, so every mj_prompt with her MUST describe her as "a young Caucasian American woman with pale skin and light freckles, a glossy black blunt jaw-length bob with heavy bangs and one clay-orange streak through the bangs, a small flat clay-orange eight-pointed star hair clip, a thin headset microphone, a white cropped puff-sleeve shirt, a black pleated skirt with a harness belt and a hanging white garment tag, black knee boots" (drop garments not visible in the framing). Keep id_pass: true on every plate she is in (it now just marks "she is in it"). State the framing explicitly at the start of every such prompt (extreme close-up / close-up / medium close-up / medium shot / full-length shot / wide shot / extreme wide shot) and where she stands in the frame. Keep her poses editorial and upright.`
phase('Merge')
const merged = await agent(`${CTX}\n\n${LIPSYNC}\n\n${FACE}\n\nYou are the head director. Merge the three boards using the judges' scores: start from the best-scoring board, graft in every judge-listed best idea that fits, apply every fix. Then WRITE TWO FILES:\n1) ${V}/STORYBOARD.md — treatment, chapter map, hook design, the full shot list (readable), the Seedance clip list with prompts and the running total, and an asset list (every MJ plate to make, grouped by set, with its prompt, and which need the identity pass).\n2) ${V}/shots.json — {"version":1,"duration":306.4,"chapters":[...],"shots":[...],"seedance":[...],"plates":[...]} where shots follow exactly these fields: ${SHOT_FIELDS} seedance items: {clip, duration, plate (plate id), prompt, shots:[ids], song_t0, words, sing}; plates: {plate, set, mj_prompt, id_pass, aspect:"16:9", used_by:[shot ids]}. Shots must tile 0–306.4 with no gaps or overlaps, cut times snapped to beats in ${V}/media/audio/beatmap.json (field beats), every lyric line (0..${'${'}n-1}) covered by exactly one or more shots' type entries, lead_on_screen true for >= 70% of total time, planned Seedance total <= 200 s across <= 45 clips, every sung passage she is on camera for planned as a chain of audio-conditioned singing windows per the UPDATE.\n\nBOARDS:\n${boards.map(b => `=== ${b.k} ===\n${b.t}`).join('\n\n')}\n\nJUDGES:\n${JSON.stringify(judged)}\n\nReturn a 15-line summary of the final video.`,
  { label: 'head-director', phase: 'Merge' })

return { totals, merged }
```

## 5. Chapter animation workflow

```js
export const meta = {
  name: 'ev-chapters',
  description: 'ESCAPE VELOCITY: one animator per chapter builds explaining motion graphics, kinetic lyrics, varied 2.5D treatments and intelligent transitions; an art director reviews renders; the animator applies the fixes',
  phases: [
    { title: 'Animate', detail: 'one agent per chapter writes engine/src/ch/<file>' },
    { title: 'Review', detail: 'an art director renders and reviews each chapter' },
    { title: 'Fix', detail: 'the animator applies the review and re-verifies' },
  ],
}
const V = '/opt/design-ref/video', E = V + '/engine'
const CH = args.chapters
const BAR = `anabology's bar, verbatim — "all this should be high effort: e.g. animate the lyric renderings to be on beat, have everything be quite dense" · "adding all the programmatic graphics on top that are animated by you and on theme will be necessary to give it the Claude feel" · "One big part of the magic of the videos I sent you were that you generated motion graphics and motion design, not just animated lyrics but things that fit the words being said to bring the words and theme to life, almost explaining the words with visuals ... motion graphics added to the top of it within the design-ref style guides we picked should complete the visual storytelling." · on 2.5D plates: "that's where we'll have to shine and be creative. depth to separate layers ofc, motion graphics galore, diversity so its not repetitive" · on transitions: "interesting and intelligent transitions, like edgar wright level ... not solely cuts but things that work with the motion design or graphics - but also not overdone and amateurish."`
const READ = c => `READ FIRST, fully: ${E}/ANIMATION_GUIDE.md (how chapters work, the explaining layer, 2.5D treatments, transitions — follow it exactly), ${V}/STORYBOARD.md (treatment, chapter map, and YOUR shots ${c.shots.join(', ')}), ${V}/shots.json (the same shots as data: type modes per lyric line, meme_visual, chrome, accent, screen, camera, transitions), ${V}/LYRICS.md (what every line references: the jokes your graphics explain), ${V}/research/memes2.md (verified references), ${V}/PLAN.md sections 3 to 3d (style system, lyric video, the bar, programmatic graphics). Engine source: ${E}/src/core.js, kinetic.js, gfx.js, chrome.js, annot.js, media.js, common.js, trans.js, timeline.js; ${E}/src/gfx-examples.js (not loaded) shows every GFX call in use. Style guides: /opt/design-ref/studio/styles/{information-design,micrographics,spec-label,computer-vision,generative-xerox,halftone}/STYLE.md.`

const animate = c => agent(`You are the animator of chapter ${c.id} "${c.name}" (${c.t0}–${c.t1} s) of anabology's music video ESCAPE VELOCITY, rendered by our JS engine in ${E}.
${READ(c)}
${BAR}
YOUR FILE: ${E}/src/ch/${c.file} — it exists and index.html already loads it. Edit ONLY this file; other chapters are written in parallel by other agents in their own files. If it already contains scenes (an earlier animator started this chapter and was interrupted), read it first and continue from it: keep what works, complete what is missing, then verify.
BUILD: register scenes that cover [${c.t0}, ${c.t1}) exactly, on your shots' t0/t1 from shots.json (you may merge adjacent shots that share footage into one scene; every shot you don't cover falls back to the plain default renderer — cover them all). For each shot:
1. Base layer: \`const m = await MEDIA.drawShot(b, '<shot id>', t, cam)\` — the edit's footage for that shot (Seedance takes and divergence covers in song time, or its plate while the clip is still being generated — clips are arriving during your work; never name clips yourself). For 2.5D shots build a treatment from the guide; never the same treatment on two consecutive 2.5D shots; at least five different treatments in your chapter.
2. Lyrics: every sung token in your range on its word time through KIN (subtitle / coverline / masthead / stack; display text from window.LYR). If you draw a lyric token yourself, call KIN.mark(tk).
3. The explaining graphic: each line's meaning drawn as a motion graphic (chart, UI, diagram, label, counter, map, CV overlay...) that enters on the words naming it, animated in beats (GFX.beatsSince), in the style guides, on the overlay, readable in one glance. Start from the shot's meme_visual and push it further.
4. Her annotations (leadKit / ANN tied to m.box('a woman') / m.box('a face')), chrome(o, t, …) (the countdown, look counter, ticker), and the chapter look: return look('<key>', {focus: m && m.box('a face'), ...}) using the keys in common.js LOOKS.
5. Transitions: mostly hard cuts on the beat; a clever, motivated transition every few shots (custom draws or FX.T presets), never the same device twice in a row.
Pure functions of t (frames render in parallel, out of order): no state, no Math.random (use hash()), no Date.
VERIFY before returning (required):
a. cd ${E} && python3 render.py lyrics ${c.t0}:${c.t1} — must print N/N tokens on screen; fix every miss.
b. Contact sheets: python3 render.py sheet <times> --cols 4 --w 480 --out /tmp/ev_${c.id}_<n>.jpg at every shot's first and last frame, every lyric line's first and last word, each graphic's entrance, each transition's middle; Read every sheet and LOOK. Iterate until every frame is charming, dense (at least 3 information layers, ordered), on the beat, readable on a phone (main lyric at least 40 px), on-model, and in anabology's taste (mono plus one accent, editorial reduction, no neon, no slop). Keep ms/frame at most 1500 (render.py prints it).
If a shared file has a bug, report it; do not edit it.
Return a concise summary: scenes registered (ids and times); per lyric line its mode and its explaining graphic; the 2.5D treatment of each plate shot; the transitions; the lyrics check result; the ms/frame range; known issues.`, { label: `animate:${c.id}`, phase: 'Animate', effort: 'high' })

const REVIEW = { type: 'object', properties: {
  score: { type: 'number' }, pass: { type: 'boolean' },
  fixes: { type: 'array', items: { type: 'object', properties: { shot: { type: 'string' }, time: { type: 'number' }, problem: { type: 'string' }, fix: { type: 'string' } }, required: ['shot', 'problem', 'fix'] } } },
  required: ['score', 'pass', 'fixes'] }

const review = (notes, c) => agent(`You are the art director of ESCAPE VELOCITY reviewing chapter ${c.id} "${c.name}" (${c.t0}–${c.t1} s), file ${E}/src/ch/${c.file}.
${READ(c)}
${BAR}
The animator's notes: ${notes}
Render and LOOK yourself (cd ${E}): python3 render.py lyrics ${c.t0}:${c.t1}; then python3 render.py sheet <at least 28 times across the chapter: every shot's first and last frame, every line's first and last word, graphic entrances, transition middles> --cols 4 --w 480 --out /tmp/ev_rev_${c.id}_<n>.jpg, and Read every sheet. Judge every shot on: the explaining graphic (does it show what the words mean, in one glance, in the style guides?); lyric timing (on the word, never early) and legibility; beat sync; density (at least 3 ordered layers); 2.5D treatment (layered, alive, and different from its neighbours — never a still with a slow zoom); transitions (intelligent and motivated, never amateurish or repeated); taste (mono plus one accent; type in empty fields, never over her face); on-model lead; performance. Do not edit any file. Return the most important fixes first (at most 14), each concrete: what to change, where, at what time. pass = true only if the chapter is at the bar with no major fix left.`, { label: `review:${c.id}`, phase: 'Review', schema: REVIEW })

const fix = (rev, c) => (!rev || !rev.fixes || !rev.fixes.length) ? Promise.resolve('no fixes') : agent(`You are the animator of chapter ${c.id} "${c.name}" (${c.t0}–${c.t1} s) of ESCAPE VELOCITY. Your file is ${E}/src/ch/${c.file}; edit ONLY it.
${READ(c)}
${BAR}
The art director scored the chapter ${rev.score}/10 and asks for these fixes (most important first):
${JSON.stringify(rev.fixes, null, 1)}
Apply every fix (use your judgement where a fix conflicts with the guide or the storyboard). Then re-verify: cd ${E} && python3 render.py lyrics ${c.t0}:${c.t1} (must be N/N) and contact sheets of every moment you changed (Read them). Return a summary of what changed and the final lyrics check.`, { label: `fix:${c.id}`, phase: 'Fix', effort: 'high' })

const results = await pipeline(CH, c => animate(c), (notes, c) => review(notes, c), (rev, c) => fix(rev, c))
return CH.map((c, i) => ({ chapter: c.id, file: c.file, result: results[i] }))
```
