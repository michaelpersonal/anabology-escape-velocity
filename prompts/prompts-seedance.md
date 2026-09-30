# Seedance 2.5 — every clip prompt (ESCAPE VELOCITY)

Endpoint: **bytedance/seedance-2.5** through OpenRouter, 720p, 16:9, 4–8 s per clip, `generate_audio: true`.

**Inputs per clip:**

- `@Image1`: the Midjourney plate for the shot, graded in the video's print look.
- `@Audio1`, for sung shots: the exact window of the vocal it must lip-sync, cut from the song in a word gap. Motion clips get the full mix instead, for timing and energy.

**How lip-sync was checked:** Seedance copies the reference audio into its own soundtrack, and the mouth follows that soundtrack. So after each take, a script compared the clip's soundtrack with our vocal to find where the sync held. Where it drifted, the edit cut on the last eighth note before the drift and a **cover** clip (same prompt pattern, starting from that frame) took over. About 86% of sung seconds were verified in sync.

**Totals:** 47 storyboard clips (SD = sung or hero shots, SX = extra motion), 30 covers, 7 early tests; 91 submissions, 421 s generated, ≈ $97.28. The dollar figure is the local ledger's estimate; OpenRouter billing was the source of truth, at about $93.

## Storyboard clips and their covers

### SD01

song 0.00 s · 6 s · motion · plate `waymo-cu` · storyboard shots s001, s003

> The scene from @Image1, moving in time with @Audio1. Close-up. The woman from @Image1 sits still in the back seat of the moving car at night, eyes closed. A red light slides slowly across her face from left to right. At one second she opens her eyes and looks straight into the lens. At four seconds she turns her head slowly to the side window as a white light sweeps across the glass and her face. The car rocks slightly. Locked camera, very slow push in. No cuts. Her mouth stays closed, face expressionless.

### SD02

song 8.30 s · 4 s · motion · plate `waymo-arrive` · storyboard shots s006

> The white robotaxi from @Image1 has stopped at the head of the wet concrete catwalk inside the dark data hall with its rear door open; the woman from @Image2 steps out of the car and stands upright on the catwalk facing the camera, moving in time with @Audio1; the silhouetted front row holds up glowing laptops on both sides. Slow push in. No cuts.

### SD03

song 18.90 s · 6 s · motion · plate `hall-ms` · storyboard shots s011, s013

> The scene from @Image1, moving in time with @Audio1. Full-length shot: the woman from @Image1 walks straight toward the camera down the wet concrete catwalk with her whole body from head to boots in frame the entire time; the silhouetted front row holds up glowing laptops on both sides; fog. The camera stays wide and slowly pulls back to keep her whole figure in frame. No cuts.

### SD04

song 32.95 s · 4 s · motion · plate `hacker-house` · storyboard shots s019

> The scene from @Image1, moving in time with @Audio1. The woman from @Image1 walks toward the camera through the middle of the dim room between people asleep on beanbags, with a calm model's walk, glancing once at the shelves of small glowing computers. Nobody else moves. The camera moves back slowly. No cuts. Her mouth stays closed, face expressionless.

### SD05

song 56.16 s · 4 s · sung · plate `waymo-seat` · storyboard shots s031

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Our Waymo just drove into a firework. Are we on fire, dude?". Medium close-up of the woman from @Image1 sitting upright in the back seat of the car, facing the camera, saying the words flatly with no expression. Locked camera, no cuts, no head turns.

### SD06

song 62.14 s · 4 s · sung · plate `podcast` · storyboard shots s033

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Look six. Like, the singularity. How's the temperature? Mild.". Medium close-up of the woman from @Image1 seated behind a large broadcast microphone, speaking the words calmly toward the camera like a podcast guest. One hard top light, black background. Locked camera, very slow push in, no cuts.

### SD06-c1 (cover of SD06)

song 63.63 s · 4 s · sung · plate `podcast` · storyboard shots s033

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "singularity. How's the temperature? Mild. No grades, no tests.". Medium close-up of the woman from @Image1 seated behind a large broadcast microphone, speaking the words calmly toward the camera like a podcast guest. One hard top light, black background. Locked camera, very slow push in, no cuts.

### SD07

song 80.44 s · 5 s · sung · plate `hero-walk` · storyboard shots s045

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Eighteen months to escape the underclass. Lock in,". Full-length shot. The woman from @Image1 walks toward the camera down the middle of the huge hall, singing, with a confident model's walk; the flaps on the giant board behind her flicker in waves and bands of warm light cross the floor. Her skirt swings. The camera moves back at her walking speed so she ends at waist height. No cuts.

### SD08

song 84.10 s · 6 s · sung · plate `hero-cu` · storyboard shots s046, s048

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Lock in, baby, foot down on the gas. Feel the A G I, feel it". Close-up of the woman from @Image1 with her black bob, clay-orange streak and headset microphone, facing the camera, singing with her eyes closed, her head tilting back slightly on the long notes. Warm light from the side. Locked camera, very slight push in, no cuts, no head turns.

### SD09

song 89.52 s · 5 s · sung · plate `hero-profile` · storyboard shots s049

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "feel it coming fast. Escape velocity...". Medium close-up in profile of the woman from @Image1, looking up at the giant board above her and singing, her mouth opening wide on the long notes. Warm light falls on her face from above. The camera moves slowly around her by a few degrees. No cuts.

### SD09-c1 (cover of SD09)

song 91.49 s · 4 s · sung · plate `hero-profile` · storyboard shots s049

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Escape velocity...". Medium close-up in profile of the woman from @Image1, looking up at the giant board above her and singing, her mouth opening wide on the long notes. Warm light falls on her face from above. The camera moves slowly around her by a few degrees. No cuts.

### SD09-c2 (cover of SD09)

song 91.49 s · 4 s · sung · plate `hero-profile` · storyboard shots s049

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Escape velocity...". Medium close-up in profile of the woman from @Image1, looking up at the giant board above her and singing, her mouth opening wide on the long notes. Warm light falls on her face from above. The camera moves slowly around her by a few degrees. No cuts.

### SD09-c3 (cover of SD09)

song 91.49 s · 4 s · sung · plate `hero-profile` · storyboard shots s049

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Escape velocity...". Medium close-up in profile of the woman from @Image1, looking up at the giant board above her and singing, her mouth opening wide on the long notes. Warm light falls on her face from above. The camera moves slowly around her by a few degrees. No cuts.

### SD09-c4 (cover of SD09)

song 91.49 s · 4 s · sung · plate `hero-profile` · storyboard shots s049

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Escape velocity...". Medium close-up in profile of the woman from @Image1, looking up at the giant board above her and singing, her mouth opening wide on the long notes. Warm light falls on her face from above. The camera moves slowly around her by a few degrees. No cuts.

### SD09-ls1 (cover of SD09)

song 91.62 s · 1.92 s · sung

> 

### SD10

song 93.30 s · 5 s · motion · plate `hall-turn` · storyboard shots s050, s051

> The scene from @Image1, moving in time with @Audio1. Full-length shot. The woman from @Image1 stands completely still at the end of the walkway with her weight on one hip for two seconds, then turns sharply around on one heel so her short black hair swings out, the orange strand whips across her face and the tag on her belt flies out, and she stops facing the camera, still. Static camera. No cuts. Her mouth stays closed, face expressionless.

### SD11

song 100.81 s · 4 s · sung · plate `n-P33~2` · storyboard shots s053

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "WE'RE SO BACK!". Close-up of the woman from @Image1 with her black bob, clay-orange streak and headset microphone, facing the camera, singing with her mouth wide open and throwing her head back on the last word. Warm light from the side. Locked camera, no cuts.

### SD12

song 108.06 s · 4 s · sung · plate `flap-cu-b~1` · storyboard shots s056

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "WE'RE SO BACK! Look". Close-up of the woman from @Image1 looking up at the flickering board above her and singing, her face lit from above. Locked camera, no cuts, no head turns.

### SD13

song 127.55 s · 4 s · motion · plate `sheer-walk` · storyboard shots s065

> The scene from @Image1, moving in time with @Audio1. Full-length shot. The woman from @Image1 walks toward the camera on the grey concrete walkway at a slow, even pace; the sheer transparent shell over her outfit lifts and ripples as she walks. The camera moves back slowly. No cuts. Her mouth stays closed, face expressionless.

### SD14

song 131.04 s · 4 s · motion · plate `arena` · storyboard shots s067

> The scene from @Image1, moving in time with @Audio1. Wide shot. The woman from @Image1 walks at an even pace away from the camera through the torn opening in the far wall of the grid-painted room and out onto the real foggy street beyond, without slowing or looking back. Static camera. No cuts. Her mouth stays closed, face expressionless.

### SD15

song 138.41 s · 7 s · sung · plate `hoodie` · storyboard shots s071, s072

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Not A I. S I. It sounds much better. Trust us. Cashmere.". Medium shot of the woman from @Image1 in the pale hoodie, standing still and facing the camera, saying the words deadpan with one very small nod; near the end she lifts the hood up over her bob with both hands. Locked camera, no cuts.

### SD15-c1 (cover of SD15)

song 139.64 s · 6 s · sung · plate `hoodie` · storyboard shots s071, s072

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "I. It sounds much better. Trust us. Cashmere.". Medium shot of the woman from @Image1 in the pale hoodie, standing still and facing the camera, saying the words deadpan with one very small nod; near the end she lifts the hood up over her bob with both hands. Locked camera, no cuts.

### SD16

song 148.95 s · 5 s · sung · plate `golden-pool` · storyboard shots s074

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Lower me into the golden light.". Medium shot. The woman from @Image1 steps down into the shallow round pool of golden light and kneels upright in it, saying the words calmly toward the camera; rings of small lights pulse outward around her. The camera rises slowly. No cuts.

### SD16-c1 (cover of SD16)

song 147.78 s · 7 s · sung · plate `golden-pool` · storyboard shots s074

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "seats. Lower me into the golden light. You have six months". Medium shot. The woman from @Image1 steps down into the shallow round pool of golden light and kneels upright in it, saying the words calmly toward the camera; rings of small lights pulse outward around her. The camera rises slowly. No cuts.

### SD16-c2 (cover of SD16)

song 150.54 s · 4 s · sung · plate `golden-pool` · storyboard shots s074

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "into the golden light. You have six". Medium shot. The woman from @Image1 steps down into the shallow round pool of golden light and kneels upright in it, saying the words calmly toward the camera; rings of small lights pulse outward around her. The camera rises slowly. No cuts.

### SD17

song 159.98 s · 8 s · sung · plate `freeway-dawn` · storyboard shots s079, s081

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Six months to escape the underclass. They say hit the brakes, we say hit the gas. Feel the". Full-length shot. The woman from @Image1 walks toward the camera along the empty elevated freeway at dawn, singing, fog below the railings, the wind moving her hair and skirt. The camera moves back at her walking speed so she ends at medium shot. No cuts.

### SD17-c1 (cover of SD17)

song 161.01 s · 4 s · sung · plate `freeway-dawn` · storyboard shots s079, s081

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "months to escape the underclass. They say hit the". Full-length shot. The woman from @Image1 walks toward the camera along the empty elevated freeway at dawn, singing, fog below the railings, the wind moving her hair and skirt. The camera moves back at her walking speed so she ends at medium shot. No cuts.

### SD18

song 162.10 s · 4 s · sung · plate `wind-cu` · storyboard shots s080

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "escape the underclass. They say hit the brakes, we say". Close-up of the woman from @Image1 singing into strong wind with her eyes closed, her short hair and the orange strand blowing. Pale sky behind. Locked camera, no cuts, no head turns.

### SD19

song 167.26 s · 4 s · sung · plate `n-P58~2` · storyboard shots s083

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Feel the A G I, feel it coming fast.". Close-up of the woman from @Image1 singing into strong wind, eyes closed, tipping her head back on the long notes, her short hair and the orange strand blowing. The camera moves slowly around her by a few degrees. No cuts.

### SD20

song 174.39 s · 4 s · sung · plate `rail-mcu` · storyboard shots s086

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "WE'RE SO BACK! (It's so". Medium close-up of the woman from @Image1 at the overpass rail, turning to the camera and singing, holding the long last note with her mouth wide open, then laughing once. Pale sky and fog behind. Locked camera, no cuts.

### SD20-c1 (cover of SD20)

song 174.57 s · 4 s · sung · plate `rail-mcu` · storyboard shots s086

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "SO BACK! (It's so". Medium close-up of the woman from @Image1 at the overpass rail, turning to the camera and singing, holding the long last note with her mouth wide open, then laughing once. Pale sky and fog behind. Locked camera, no cuts.

### SD20-c2 (cover of SD20)

song 174.57 s · 4 s · sung · plate `rail-mcu` · storyboard shots s086

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "SO BACK! (It's so". Medium close-up of the woman from @Image1 at the overpass rail, turning to the camera and singing, holding the long last note with her mouth wide open, then laughing once. Pale sky and fog behind. Locked camera, no cuts.

### SD20-c3 (cover of SD20)

song 174.57 s · 4 s · sung · plate `rail-mcu` · storyboard shots s086

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "SO BACK! (It's so". Medium close-up of the woman from @Image1 at the overpass rail, turning to the camera and singing, holding the long last note with her mouth wide open, then laughing once. Pale sky and fog behind. Locked camera, no cuts.

### SD20-ls1 (cover of SD20)

song 174.68 s · 3.76 s · sung

> 

### SD21

song 180.23 s · 4 s · sung · plate `rail-mcu~1` · storyboard shots s088

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "WE'RE SO BACK!". Medium close-up of the woman from @Image1 at the overpass rail, singing straight into the lens with her eyes open. Pale sky and fog behind. Locked camera, very slight push in, no cuts.

### SD21-c1 (cover of SD21)

song 181.62 s · 4 s · sung · plate `rail-mcu~1` · storyboard shots s088

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "SO BACK! Escape velocity:". Medium close-up of the woman from @Image1 at the overpass rail, singing straight into the lens with her eyes open. Pale sky and fog behind. Locked camera, very slight push in, no cuts.

### SD22

song 190.40 s · 4 s · motion · plate `gantries~4` · storyboard shots s092

> The scene from @Image1, moving in time with @Audio1. Wide shot. The woman from @Image1 walks slowly down the middle lane of the empty foggy freeway under the huge signs, stops under the second sign and looks up at it. Fog drifts. Static camera. No cuts. Her mouth stays closed, face expressionless.

### SD23

song 209.94 s · 4 s · sung · plate `white-mcu` · storyboard shots s100

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Did we make it?". Medium close-up of the woman from @Image1 in white haze, turning her head to look straight into the lens and asking the words quietly. Locked camera, no cuts.

### SD23-c1 (cover of SD23)

song 209.21 s · 4 s · sung · plate `white-mcu` · storyboard shots s100

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Did we make it?". Medium close-up of the woman from @Image1 in white haze, turning her head to look straight into the lens and asking the words quietly. Locked camera, no cuts.

### SD23-c2 (cover of SD23)

song 209.21 s · 4 s · sung · plate `white-mcu` · storyboard shots s100

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Did we make it?". Medium close-up of the woman from @Image1 in white haze, turning her head to look straight into the lens and asking the words quietly. Locked camera, no cuts.

### SD23-c3 (cover of SD23)

song 209.21 s · 4 s · sung · plate `white-mcu` · storyboard shots s100

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Did we make it?". Medium close-up of the woman from @Image1 in white haze, turning her head to look straight into the lens and asking the words quietly. Locked camera, no cuts.

### SD24

song 217.00 s · 6 s · motion · plate `ramp-white` · storyboard shots s103, s104

> The scene from @Image1, moving in time with @Audio1. Full-length shot from behind. The woman from @Image1 walks slowly along the concrete ramp toward its end against the white sky, the wind rising and lifting her hair and pleated skirt, and stops two steps from the edge. The camera follows behind her, then stops. No cuts. Her mouth stays closed, face expressionless.

### SD25

song 222.78 s · 4 s · sung · plate `white-cu` · storyboard shots s105, s107

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Lock in. Lock in. Feel the A G I.". Close-up of the woman from @Image1 on a plain white background, chanting the words hard to the lens, eyes open. Locked camera, no cuts, no head turns.

### SD25-c1 (cover of SD25)

song 219.86 s · 6 s · sung · plate `white-cu` · storyboard shots s105, s107

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Lock in. Lock in. Feel the A". Close-up of the woman from @Image1 on a plain white background, chanting the words hard to the lens, eyes open. Locked camera, no cuts, no head turns.

### SD25-c2 (cover of SD25)

song 219.86 s · 6 s · sung · plate `white-cu` · storyboard shots s105, s107

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Lock in. Lock in. Feel the A". Close-up of the woman from @Image1 on a plain white background, chanting the words hard to the lens, eyes open. Locked camera, no cuts, no head turns.

### SD26

song 224.70 s · 4 s · motion · plate `ramp-white~1` · storyboard shots s108

> The scene from @Image1, moving in time with @Audio1. Full-length shot from behind. The woman from @Image1 runs fast down the concrete ramp toward the white sky, her pleated skirt and the straps of her harness whipping in the wind. The camera follows behind her at her speed. No cuts. Her mouth stays closed, face expressionless.

### SD27

song 228.61 s · 6 s · sung · plate `float-ms` · storyboard shots s111

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "in a datacenter. Lean proofs. Phages. Enzymes. Kidneys. Good boys.". Medium shot of the woman from @Image1 floating upright in bright white space, singing the words to the lens, her short hair and pleated skirt lifting in slow wind. Locked camera, no cuts.

### SD27-c1 (cover of SD27)

song 229.22 s · 4 s · sung · plate `float-ms` · storyboard shots s111

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "datacenter. Lean proofs. Phages. Enzymes. Kidneys.". Medium shot of the woman from @Image1 floating upright in bright white space, singing the words to the lens, her short hair and pleated skirt lifting in slow wind. Locked camera, no cuts.

### SD27-c2 (cover of SD27)

song 229.22 s · 4 s · sung · plate `float-ms` · storyboard shots s111

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "datacenter. Lean proofs. Phages. Enzymes. Kidneys.". Medium shot of the woman from @Image1 floating upright in bright white space, singing the words to the lens, her short hair and pleated skirt lifting in slow wind. Locked camera, no cuts.

### SD27-c3 (cover of SD27)

song 230.22 s · 4 s · sung · plate `float-ms` · storyboard shots s111

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Lean proofs. Phages. Enzymes. Kidneys. Good boys.". Medium shot of the woman from @Image1 floating upright in bright white space, singing the words to the lens, her short hair and pleated skirt lifting in slow wind. Locked camera, no cuts.

### SD28

song 239.56 s · 6 s · sung · plate `float-ms~1` · storyboard shots s116, s118

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "We're So Back region. Slash loop: make me happier. Slopacolypse? Not ours.". Medium shot of the woman from @Image1 floating upright in bright white space, singing the words to the lens, her hair and pleated skirt lifting in slow wind; she turns slowly by a quarter turn. Locked camera, no cuts.

### SD29

song 250.30 s · 5 s · sung · plate `white-cu~3` · storyboard shots s122, s123

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "WE'RE SO BACK! WE'RE SO BACK! Zero months, there is no underclass.". Close-up of the woman from @Image1 on a plain white background, singing hard to the lens with her mouth wide open, then softening her face on the last words. Locked camera, no cuts, no head turns.

### SD29-c1 (cover of SD29)

song 251.65 s · 4 s · sung · plate `white-cu~3` · storyboard shots s122, s123

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "SO BACK! Zero months, there is no underclass. One". Close-up of the woman from @Image1 on a plain white background, singing hard to the lens with her mouth wide open, then softening her face on the last words. Locked camera, no cuts, no head turns.

### SD30

song 253.46 s · 4 s · sung · plate `white-catwalk` · storyboard shots s124

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "there is no underclass. One year back for every". Full-length shot. The woman from @Image1 walks toward the camera along the white catwalk, singing, with a calm model's walk. Her soft shadow moves under her. The camera moves back slowly. No cuts.

### SD30-c1 (cover of SD30)

song 253.42 s · 4 s · sung · plate `white-catwalk` · storyboard shots s124

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "there is no underclass. One year back for every". Full-length shot. The woman from @Image1 walks toward the camera along the white catwalk, singing, with a calm model's walk. Her soft shadow moves under her. The camera moves back slowly. No cuts.

### SD31

song 255.22 s · 4 s · sung · plate `white-cu~4` · storyboard shots s125

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "One year back for every year that passed. Feel the". Close-up of the woman from @Image1 on a plain white background, singing with her eyes closed. Locked camera, very slight push in, no cuts, no head turns.

### SD31-c1 (cover of SD31)

song 254.22 s · 5 s · sung · plate `white-cu~4` · storyboard shots s125

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "underclass. One year back for every year that passed. Feel the". Close-up of the woman from @Image1 on a plain white background, singing with her eyes closed. Locked camera, very slight push in, no cuts, no head turns.

### SD32

song 260.62 s · 4 s · sung · plate `white-cu-b` · storyboard shots s127

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "feel it coming fast. Escape velocity...". Close-up of the woman from @Image1 on a plain white background, singing with her eyes closed, head tilting back on the long notes. Locked camera, no cuts.

### SD33

song 266.42 s · 5 s · sung · plate `white-cu-b~1` · storyboard shots s130, s131

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "It was never over! WE'RE SO BACK!". Close-up of the woman from @Image1 on a plain white background, singing with her eyes closed; on the very last note she opens her eyes and looks straight into the lens. Locked camera, no cuts, no head turns.

### SD33-c1 (cover of SD33)

song 269.87 s · 4 s · sung · plate `white-cu-b~1` · storyboard shots s130, s131

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "BACK!". Close-up of the woman from @Image1 on a plain white background, singing with her eyes closed; on the very last note she opens her eyes and looks straight into the lens. Locked camera, no cuts, no head turns.

### SD33-c2 (cover of SD33)

song 266.59 s · 4 s · sung · plate `white-cu-b~1` · storyboard shots s130, s131

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "It was never over! WE'RE SO BACK!". Close-up of the woman from @Image1 on a plain white background, singing with her eyes closed; on the very last note she opens her eyes and looks straight into the lens. Locked camera, no cuts, no head turns.

### SD34

song 283.00 s · 8 s · sung · plate `tag-to-lens~1` · storyboard shots s137, s138

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Do not iron. Do not nerf. Made in San Francisco.". Medium close-up of the woman from @Image1 holding a white garment tag up toward the lens between two fingers, saying the words deadpan to the camera; halfway through she turns the tag over. Locked camera, no cuts.

### SD34-c1 (cover of SD34)

song 287.21 s · 4 s · sung · plate `tag-to-lens~1` · storyboard shots s137, s138

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Made in San Francisco.". Medium close-up of the woman from @Image1 holding a white garment tag up toward the lens between two fingers, saying the words deadpan to the camera; halfway through she turns the tag over. Locked camera, no cuts.

### SD34-c2 (cover of SD34)

song 287.21 s · 4 s · sung · plate `tag-to-lens~1` · storyboard shots s137, s138

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Made in San Francisco.". Medium close-up of the woman from @Image1 holding a white garment tag up toward the lens between two fingers, saying the words deadpan to the camera; halfway through she turns the tag over. Locked camera, no cuts.

### SD35

song 290.20 s · 11 s · motion · plate `paper-board~1` · storyboard shots s139, s140

> The scene from @Image1, moving in time with @Audio1. Wide shot. The woman from @Image1 walks slowly away from the camera across the endless white floor beneath the small board on the wall; after a few steps she looks back over her shoulder once, then keeps walking until she is very small. Static camera. No cuts. Her mouth stays closed, face expressionless.

### SX01

song 50.89 s · 4 s · motion · plate `billboard-catwalk` · storyboard shots s028

> The scene from @Image1, moving in time with @Audio1. The woman from @Image1 stands on the narrow steel maintenance catwalk of a huge blank billboard above a fogged freeway at night; wind moves her hair and pleated skirt; she turns her head slowly toward the camera. Slow push in. No cuts.

### SX02

song 53.17 s · 4 s · motion · plate `n-P20~1` · storyboard shots s029

> The scene from @Image1, moving in time with @Audio1. The woman from @Image1 stands on the catwalk, makes one small stiff bow from the waist, then straightens and looks into the lens, deadpan. Locked camera. No cuts.

### SX03

song 54.99 s · 4 s · motion · plate `mission-fire` · storyboard shots s030

> The scene from @Image1, moving in time with @Audio1. A white robotaxi sits on a narrow city street at night in thick white smoke while red firework sparks burst around it; the woman from @Image1 leans on the car and turns to look into the camera. Slow push in. No cuts.

### SX04

song 65.93 s · 4 s · motion · plate `answer-sheet` · storyboard shots s035

> The scene from @Image1, moving in time with @Audio1. The woman from @Image1 tears a blank paper answer sheet in half with one sharp pull and lets the halves fall. Locked camera. No cuts.

### SX05

song 67.75 s · 4 s · motion · plate `moat` · storyboard shots s036

> The scene from @Image1, moving in time with @Audio1. The woman from @Image1 stands still on a stone plinth in the middle of a square moat of black water; slow ripples cross the water; the camera slowly orbits her. No cuts.

### SX06

song 110.42 s · 4 s · motion · plate `cage` · storyboard shots s057

> The scene from @Image1, moving in time with @Audio1. Pre-dawn in a vast grey concrete hall: the woman from @Image1 steps out of an open chrome cage and walks toward the camera. Slow push in. No cuts.

### SX07

song 120.38 s · 4 s · motion · plate `envelope-ms` · storyboard shots s062

> The scene from @Image1, moving in time with @Audio1. The woman from @Image1 tears open a paper envelope at chest height, pulls out one sheet and reads it, deadpan. Locked camera. No cuts.

### SX08

song 124.45 s · 4 s · motion · plate `leather-jacket` · storyboard shots s064

> The scene from @Image1, moving in time with @Audio1. The woman from @Image1 shrugs a black leather jacket onto her shoulders and then looks into the lens. Slow push in. No cuts.

### SX09

song 194.25 s · 4 s · motion · plate `gantry2-ms` · storyboard shots s093

> The scene from @Image1, moving in time with @Audio1. Under a huge split-flap sign on a steel gantry over an empty freeway in white fog, the woman from @Image1 looks up while the black flaps flutter. Low angle, slow tilt up. No cuts.

### SX10

song 201.00 s · 4 s · motion · plate `n-P63` · storyboard shots s095

> The scene from @Image1, moving in time with @Audio1. The woman from @Image1 stands dead centre on an empty freeway in white fog under three huge split-flap gantries; fog drifts past her; she does not move. Locked camera. No cuts.

### SX11

song 231.96 s · 4 s · motion · plate `dog-walk` · storyboard shots s112

> The scene from @Image1, moving in time with @Audio1. On a white paper floor the woman from @Image1 walks slowly across the frame while a small dog in a black harness trots beside her. Tracking shot. No cuts.

### SX12

song 271.41 s · 4 s · motion · plate `paper-board` · storyboard shots s132

> The scene from @Image1, moving in time with @Audio1. From behind, the woman from @Image1 walks away across an empty white paper floor toward a small black board on the white wall. Slow push. No cuts.

## Early tests (the lip-sync method was found here)

### test-sing-a

song 0.00 s · 5 s · motion

> @Image1 is the young woman with the black bob, the clay-orange streak and the headset microphone. She sings the vocal in @Audio1: her mouth lip-syncs exactly to @Audio1, every syllable and every held vowel in time, her jaw opening wide on the long notes. She sings: "Eighteen months to escape the underclass." Locked medium close-up, she faces the camera with her eyes half closed, no head turns, the camera does not move, the light stays the same.

### test-sing-b

song 0.00 s · 5 s · motion

> The young woman in the first frame with the black bob, the clay-orange streak and the headset microphone. She sings the vocal in @Audio1: her mouth lip-syncs exactly to @Audio1, every syllable and every held vowel in time, her jaw opening wide on the long notes. She sings: "Eighteen months to escape the underclass." Locked medium close-up, she faces the camera with her eyes half closed, no head turns, the camera does not move, the light stays the same.

### test-sing-cover

song 82.45 s · 5 s · sung

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "escape the underclass. Lock in, baby, foot down on the gas." Close-up of the woman from @Image1 with her black bob, clay-orange streak and headset microphone, facing the camera, eyes half closed. Locked camera, no cuts, no head turns.

### test-sing-ref

song 80.54 s · 5 s · sung

> @Image1 sings @Audio1. She lip-syncs to @Audio1 exactly, every word in time: "Eighteen months to escape the underclass." Close-up of the woman from @Image1 with her black bob, clay-orange streak and headset microphone, facing the camera, eyes half closed. Locked camera, no cuts, no head turns.

### test-sing

song 0.00 s · 5 s · motion

> She sings the words of the reference audio into her headset microphone, her lips moving exactly in time with the vocal, eyes closed, a slow small nod on each beat, her bob swaying slightly. The camera holds still with a very slow push in. The lighting stays the same.

### test-walk

song 18.96 s · 6 s · motion · plate `hall-ms`

> The scene from @Image1, moving in time with @Audio1. The woman from @Image1 walks straight toward the camera down the wet concrete catwalk with a steady model's walk, each step landing on the beat of @Audio1, her pleated skirt swinging and the white garment tag swaying. Her mouth stays closed, face expressionless. The crowd on both sides holds up glowing laptops. Slow push in. No cuts.

### test-waymo

song 0.00 s · 5 s · motion

> The young woman walks forward away from the open car door toward the camera with a calm, confident fashion-show walk, her pleated skirt swinging and her bob moving slightly with each step. The camera slowly pushes in. Light fog drifts across the wet concrete floor. The car stays still with its doors open. Her face stays the same.
