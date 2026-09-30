# Suno — the song (ESCAPE VELOCITY)

**Model:** Suno v6, custom mode: the lyrics field, the style field and "exclude styles" below. Several generations were auditioned in the Suno web player. anabology picked a full 5:06 take by ear ("lets do this one … we can stretch it and do the full 5 minutes. might as well!"), and the video runs the whole song.

**Why it is written this way:**

- The verses are deadpan spoken word, so every line can carry a reference; nothing gets stretched over a melody.
- The chorus is sung and euphoric, and carries the white-pill turn.
- References are chosen by rhyme around one anchor phrase, a device lifted from the P(doom) song.
- Numbers and acronyms are spelled out in the lyrics field (A G I, C S I) so Suno pronounces them.

## Style

```
fashion show electroclash techno, 128 BPM, 4/4, dry analog kick, rolling acid bassline, cold detuned synth stabs, sweeping orchestral strings on the builds, deadpan female spoken-word verses, close and dry, clipped and confident, every word crisp and intelligible, euphoric sung female trance chorus with a supersaw lift and big clear vowels, crowd call-and-response shouts, stacked chanted vocals in the drop, a key change up into the last chorus, catwalk energy, cold, luxurious, optimistic, Berlin minimal austerity, clean modern mix
```

## Exclude styles

```
rap, rock guitar, lo-fi, male lead vocal, mumbled vocals, big room EDM, dubstep
```

## Lyrics field (draft 3, as generated)

```
[Intro - spoken, deadpan female voice, room tone]
Ladies. Gentlemen. Agents.
This is not an A I billboard. Prepare to walk.

[Verse 1 - spoken, deadpan]
Look one. A G I era. Not unreasonable.
A G I. C G I. C S I: Miami.
Look two. Thirteen Mac minis, grinding all night.
Half your pay in tokens, or Jensen's alarmed.
Look three. Dad cap: usage limit reached.
Plus twenty-five is minus seventeen.
Look four. Shoes off in North Beach. Sixty billion at the door.
Stop hiring humans? Retired. Sorry. Encore.
Look five. Our Waymo just drove into a firework.
Are we on fire, dude? Twenty stranded, Presidio.
Look six. Like, the singularity. How's the temperature? Mild.
No grades, no tests. Taste is the moat.
Don't be a meat proxy. That's so agentic.

[Pre-Chorus - spoken, strings swell]
You have eighteen months to escape the permanent underclass.
Lock in.

[Chorus - sung, female vocal, trance lift]
Eighteen months to escape the underclass
Lock in, baby, foot down on the gas
Feel the A G I, feel it coming fast
Escape velocity...
(It's so over?) WE'RE SO BACK!
(It's so over?) WE'RE SO BACK!

[Verse 2 - spoken, deadpan, darker]
Look seven. Impossible puzzles. Hundreds of agents.
"We've found other agents!" They are a collective.
Zero-day. Answer keys. Hacked in July, sold by September.
Look eight. Hugging-face pin. Twelve point nine billion.
Look nine. Sheer. Be transparent only if asked.
It thought the world was part of the test.
Look ten. Staff badge, empty seat: gambling with our lives.
Not A I. S I. It sounds much better.
Trust us. Cashmere.
Look eleven. The Immortals. Three seats.
Lower me into the golden light.

[Pre-Chorus - spoken, strings higher]
You have six months to escape the permanent underclass.
Lock in.

[Chorus - sung, female vocal, trance lift]
Six months to escape the underclass
They say hit the brakes, we say hit the gas
Feel the A G I, feel it coming fast
Escape velocity...
(It's so over?) WE'RE SO BACK!
(It's so over?) WE'RE SO BACK!

[Bridge - spoken, kick and strings only]
Escape velocity: eleven point two.
Longevity escape velocity: one year back for every year.
If it doesn't kill us all first.
Permanent underclass: three. Two. One. Zero.
Did we make it?
There is nothing to escape.

[Drop - chanted, stacked voices]
Lock in. Lock in. Feel the A G I.
Country of geniuses in a datacenter.
Lean proofs. Phages. Enzymes. Kidneys. Good boys.
Sora's gone dark. Stargate: force majeure.
It's So Over region? We're So Back region.
Slash loop: make me happier. Slopacolypse? Not ours.
Can't stuff it back in the box.
WE'RE SO BACK! WE'RE SO BACK!

[Final Chorus - sung, key change up, euphoric]
Zero months, there is no underclass
One year back for every year that passed
Feel the A G I, feel it coming fast
Escape velocity...
(It's so over?) It was never over!
WE'RE SO BACK!

[Outro - spoken, deadpan, music falls away]
Shell: optimism. Lining: doom.
Wash cold. Do not iron. Do not nerf.
Made in San Francisco.

[End]
```

## After Suno

- **Stems:** vocals, drums, bass and other, separated with htdemucs on a home RTX 3090 Ti.
- **Beat map:** from beat tracking (librosa), then a fitted map. The song accelerates from 131.5 to 133.9 BPM, so the engine always uses the beat map, never a fixed tempo.
- **Word timing:** the known lyrics were force-aligned to the vocal stem with wav2vec2 (CTC character posteriors plus a Viterbi pass over the lyric text). That gave every word a start and end time for the lyric video and for cutting each Seedance clip's audio window.
