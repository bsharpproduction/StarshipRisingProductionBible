# STARSHIP RISING
## Motion Graphics Production Bible
### For an AI agent · Version 1.0 · 2026-09-27

This file is the single source of truth. Follow it in order. Do not invent a second visual system. If a choice is not specified, use the **Default Stack** in §0.

---

## 0. Mission

Build a lyric-synced motion piece that feels like a Wong Kar-wai night shot of a Blade Runner launch site. Cold and intimate. Industrial and tender. The machine is trying to pray.

**Working title:** STARSHIP RISING  
**Format master:** 1920×1080, 24 fps (step-print friendly). Also export 3840×2160.  
**Safe crop:** keep hero subjects and type inside a 9:16 center column so a vertical cut works.  
**Assumed runtime:** 03:10 (hold last frame + static decay after 2:57).  
**Tempo lock:** 87 BPM (range of the record: 80–95).  
**Beat:** 0.6897 s · **half-bar:** 1.379 s · **bar:** 2.759 s.

### Default Stack (apply to every shot unless overridden)

1. Plate from `assets/plates/` as the base.
2. Very slow Ken Burns (scale 100→108 or 108→100 over the full cue).
3. Cool filter LUT: teal shadows, amber practicals, 10–15% saturation crush on midtones.
4. Overlay `assets/overlays/ov_grain_scratch.jpg` at 25–40% Overlay or Soft Light.
5. Overlay `assets/overlays/ov_static_scanlines.jpg` at 8–18% Screen, peaked on chorus word "static" and on outro.
6. Anamorphic horizontal flare on any bright point source.
7. Chromatic aberration 2–6 px on frame edges only.
8. Underexpose the composite −0.4 to −0.8 stops. Never look like a catalog render.
9. No logos. No NASA/SpaceX marks. No readable HUD chrome. No faces.

### What this is not

Not a launch documentary.  
Not glossy 8K product viz.  
Not lyric-video karaoke with a stock rocket.  
Not centered heroic poster frames.

---

## 1. Emotional contract

| Voice in the mix | Picture does this |
|---|---|
| Raspy male lead, strained falsetto | Type is imperfect, slightly late, sometimes too large. Cuts land on breath, not just downbeats. |
| Ethereal female wordless vocal | No lyrics. Picture becomes smear, fog, pale cyan light. Step-print. |
| Glitchy electronic texture | Datamosh, scanline tear, 2–6 frame hold, channel split. |
| Spacious reverb | Hold the last frame of a phrase 4–8 extra frames. Let type decay instead of hard-out. |
| Cold + intimate | Close textures (steel, glass, clocks) cut against distant vehicles. Never a medium "explainer" shot. |

**Narrative in one line:** We packed our grief into stainless steel and launched it at a sky that is singing back through static.

**Three-act picture:**  
- Act I (0:00–0:55) Earth, wet, heavy, framed through glass and fence.  
- Act II (0:55–2:30) Ascent, separation, clocks failing.  
- Act III (2:30–end) Leaving as a feeling, not a destination. Do not look down.

---

## 2. Wong Kar-wai composition rules (non-negotiable)

Use at least **two** of these in every shot.

**W1 · Off-center.** Subject lives on a vertical third. Dead-center is reserved for the two "Don't look down" cards and for one breath-hold at 2:40.

**W2 · Frame through obstruction.** 25–45% of the frame is a dirty foreground: rain glass, chainlink, car pillar, bulkhead, cable, doorway. Foreground is soft. Subject is mid-distance.

**W3 · Isolation geometry.** Doorways, windows, tower lattice, viewports. The vehicle or the line of type sits inside a smaller rectangle.

**W4 · Angle is a feeling.** Prefer low (awe, weight) or high (vertigo, memory). Neutral eye-level only for clocks and type-only cards.

**W5 · Step-print / smudge-motion.** On female vocalizing, on "memory", on "static", on "leaving": shoot-feel of 12 fps printed to 24. Repeat frames in 2s. Motion becomes ribbon.

**W6 · Hands-and-objects thinking.** When there is no person, the steel, the clock hand, the rain bead, the bellows *is* the close-up. Desire and fear live in texture.

**W7 · Color is motivated.** Every colored light has a source in the plate (sodium lamp, instrument, engine, CRT, neon tube). Do not dump a rainbow grade with no source.

**W8 · No fill.** Keep one side of the frame hungry and dark. Lifted colorful blacks, not milky grey.

Christopher Doyle shorthand for prompts: *single practical, underexposed 1–2 stops, obstruction in the near field, wet, grain, not cleaned.*

---

## 3. World: Blade Runner × Starship × analog indie

**Place:** a Gulf-coast night that could be Boca Chica if memory were a synth. Wet flats, chainlink, sodium, fog, stacked stainless tanks, a needle on the horizon.

**Vehicle language:**
- Stainless skin with condensation. Reflections are the poetry.
- Heat as amber smear, not crisp exhaust plumes.
- Booster fall is a broken vow — body falling through empty teal air toward black water.
- Interior is analog: clocks, tungsten cage light, CRT, tactile switches. Not glass-cockpit sci-fi.

**Indie / anti-render finish (always on):**
- 35mm grain. Fine + coarse mixed.
- Hairline scratches and gate weave (1 px).
- Slight misregistration of R/B channels on cuts.
- Occasional 1-frame flash of inverted luminance on hard consonants.
- Compression blocks only as a *chosen* glitch, not as an accident of export.
- Avoid: octane sheen, perfect fillets, stock HUD, lens dirt packs that look like YouTube presets.

**Cool filter:**
- Shadows → `#0B1C22` / `#12343C`
- Midtones shift −12 toward cyan
- Highlights split: steel stays `#C9D4D6`, lamps stay `#E8A45A`
- A thin magenta edge on speculars (`#C45B8A` at 8% opacity)

---

## 4. Color system

Master swatches (use these hexes in grades, type, and glows):

| Name | Hex | Role |
|---|---|---|
| Void Teal | `#070D10` | True black substitute |
| Harbor Shadow | `#0B1C22` | Field, letterboxing |
| Doyle Emerald | `#12343C` | Lifted shadow |
| Sodium Wet | `#E8A45A` | Practical lamps, engine heat |
| Steel Gleam | `#C9D4D6` | Metal highlight, primary type |
| Fog Cyan | `#7EC8C6` | Female vocal, distant gleam |
| Static Magenta | `#C45B8A` | Glitch, "voices in the static" |
| Oxblood | `#4A1C28` | Memory, broken vow |
| Paper White | `#E7E2D6` | Soft type on dark, never pure #FFF |
| Signal Amber | `#F0C27B` | Small UI ticks, clock faces |

**Section tints**
- Intro / verse 1: Harbor + Sodium, low contrast.
- Pre-chorus: add Oxblood in the shadows.
- Chorus: open the sky, add Fog Cyan and a sliver of Static Magenta in the upper frame.
- Verse 2 / booster: Oxblood + Sodium heat vs teal sea.
- Bridge: Fog Cyan + Steel, almost no amber.
- Outro: Static Magenta eats the cyan until only grain remains.

Reference still: `assets/reference/00_palette_table.jpg`

---

## 5. Typography system

Type is a second instrument, not a caption. Size is emotion.

### Families (use these roles; substitute closest available)

| Role | Primary | Fallback | When |
|---|---|---|---|
| BODY / industrial | Condensed grotesque (Oswald, Druk Condensed, Haettenschweiler, Bebas Neue) | DIN Condensed | Verses, facts of the world |
| NERVE / intimate | Italic serif (Instrument Serif Italic, Editorial New Italic, Freight Display Italic) | Playfair Display Italic | Pre-chorus, "beautiful", "cold and beautiful" |
| TELEMETRY | Monospace (IBM Plex Mono, Fragment Mono, Space Mono) | Courier Prime | Times, "static", outro |
| GHOST | Wide tracking, thin grotesque or serif small-caps | — | Female vocalizing moments (rarely used; prefer no type) |

Physical mood: `assets/reference/01_type_physical.jpg`

### Scale ladder (1080p). Jump between rungs. Do not ease through every size.

| Rung | Size | Tracking | Use |
|---|---|---|---|
| whisper | 18–28 px | +80 to +140 | Ghost words, "isn't there" |
| speak | 36–48 px | +20 | Default verse |
| strain | 64–82 px | 0 to −20 | End of a verse line |
| cry | 110–160 px | −40 | One word only: *rising*, *static*, *home*, *leaving*, *down* |
| wall | 220–320 px | −60 | Single word fills frame. Max twice in the film: **STATIC** and **DOWN** |

Color of type:
- Default: Paper White at 88–94% opacity.
- On steel plates: Steel Gleam.
- On "static" / outro: Fog Cyan with a 4 px Static Magenta duplicate offset +3x / 0y (channel split).
- Never 100% pure white. Never drop shadow chrome. A 1 px dark halo is allowed if plate is busy.

Placement:
- Avoid lower-third karaoke. Prefer upper-left third, mid-right third, or stacked ragged left inside a window/doorway already in the plate.
- Type may be cut by the foreground obstruction. That is correct.
- Maximum 2 lines on screen. 3 only if the third line is whisper-rung and fading.

### Type animation language

Name these in the timeline as they are written here.

**T-LATE** — word arrives 2–5 frames after the sung syllable. Vulnerability. Default for the male lead.

**T-HOLD** — hold the last word of the line through 4–8 frames of the next plate.

**T-DECAY** — opacity 100→0 with a 2 px vertical smear (directional blur) over 10–16 frames. Reverb analog.

**T-STEP** — type updates on 12 fps (hold 2 frames). Use on pre-chorus.

**T-SPLIT** — duplicate layer, R channel +4 px, B channel −4 px, 6–10 frames. Use on "static", "shaking", "broken".

**T-SCALEHIT** — one word jumps two rungs on the stressed syllable then falls one rung. Use once per chorus on *rising* and on *home*.

**T-RAIN** — glyphs jitter 1 px, random opacity 80–100, like drops. Use on shore / glass plates.

**T-MONO** — letters type on at 18–22 ms per character, telemetry feel. Use on outro and on "clocks forget to wind".

**T-NONE** — no type. Female vocalizing, intro, most instrumental air.

Do not bounce, do not elastic-ease like app UI, do not kinetic-type every word. Stillness is the luxury.

---

## 6. Motion principles

1. **Camera speed is grief-speed.** Max 8% scale change per cue. Pan only to follow a reflection or a falling booster.
2. **Cuts are on consonants or on silence**, not on every bar line. Prefer L-cuts: picture changes while the last sung word is still decaying.
3. **Step-print recipe:** for any 24 fps clip that needs smudge, hold each frame twice and drop every other original (or interpret as 12 fps). Mix with 24 fps sharp frames on the word that must sting.
4. **Parallax:** foreground obstruction moves 1.4× the plate. Tiny. If it looks like a 3D postcard, reduce it.
5. **Engine / heat:** never a sharp plume. Long-shutter ribbon. Grain should eat the brightest core.
6. **Glitch budget:**  
   - Verse: 0–1 events per line.  
   - Pre: 1 event.  
   - Chorus "static" line: dense, 4–8 frames.  
   - Outro: glitch becomes the picture.
7. **Breathing machine (bridge):** opacity or scale pulse at 87 BPM on plate `13_machine_breathing.jpg`, amplitude ≤2%.
8. **Do not look down (outro):** the camera *does* look down, slowly, against the lyric. That contradiction is the ending.

---

## 7. Motif library

Reuse these. Do not add a new motif without retiring an old one.

| Motif | Meaning | Where it lives |
|---|---|---|
| Rain on glass / steel | Prayer, packing silence | 03, 04, 12 |
| Chainlink / fence | The life we cannot keep | 04, 05 |
| Sodium on wet ground | Earth memory | 03, 05, 06 |
| Stainless reflection | The metal skin, the self we built | 04, 07, 10 |
| CRT / scanlines | Voices that are not there | 08, overlays |
| Clocks wrong or still | Time letting go | 11 |
| Earth through dirty glass | Not the end — the start of leaving | 12 |
| Bellows / ribbed machine | The machine that dreams of breathing | 13 |
| Tower lattice well | Vertigo, don't look down | 14 |
| Magenta-teal sky | A sky we've never known | 09 |
| Falling booster | Broken vow | 10 |

---

## 8. Asset index

All paths relative to this folder.

### Plates (base footage)

| File | Emotion | Primary cues |
|---|---|---|
| `assets/plates/02_intro_smudge.jpg` | Wordless, distant | 0:00–0:19, fades in outro |
| `assets/plates/03_texas_shore_gleam.jpg` | Gleam, waiting | 0:19–0:29 |
| `assets/plates/04_metal_skin_prayer.jpg` | Tender industrial | 0:29–0:39 |
| `assets/plates/05_packed_silence_yard.jpg` | Beginning as a lie we need | 0:39–0:46 |
| `assets/plates/06_ground_shaking.jpg` | Memory as vibration | 0:46–0:55 |
| `assets/plates/07_starship_rising.jpg` | Ascent | 0:55–1:00, 1:50–1:55 |
| `assets/plates/08_voices_in_static.jpg` | Beautiful and ruined | 1:00–1:10, 1:55–2:05 |
| `assets/plates/09_sky_never_known.jpg` | Homesick for the future | 1:10–1:26, 2:05–2:30 |
| `assets/plates/10_booster_falls.jpg` | Broken vow | 1:26–1:35 |
| `assets/plates/11_clocks_forget.jpg` | Weightless time | 1:35–1:50 |
| `assets/plates/12_leaving_earth.jpg` | Not an ending | 2:30–2:40 |
| `assets/plates/13_machine_breathing.jpg` | Cold / beautiful | 2:40–2:49 |
| `assets/plates/14_dont_look_down.jpg` | Vertigo | 2:49–end |

### Overlays

| File | Blend | Opacity |
|---|---|---|
| `assets/overlays/ov_grain_scratch.jpg` | Overlay / Soft Light | 25–40% always |
| `assets/overlays/ov_static_scanlines.jpg` | Screen / Add | 8% default, 35–55% on "static" and outro |

### Reference (do not use as hero plates)

| File | Use |
|---|---|
| `assets/reference/00_palette_table.jpg` | Grade target |
| `assets/reference/01_type_physical.jpg` | Type texture / bump map for letters if needed |

If a generative model is used to extend a plate into motion, **lock to the still**. Prompt: *continue this exact frame as analog 35mm, slow drift, no new objects, no people, no logos, cool teal grade, grain.*

Machine cue sheet: `AGENT_CUES.json`

---

## 9. Lyric-synced shot list

Times are start of the cue. Hold each cue until the next start. Picture may pre-lap 4–8 frames.

### 0:00–0:19 · INTRO
**Lyric:** (none — ethereal female vocalizing, distant, wordless)  
**Plate:** `02_intro_smudge.jpg`  
**Comp:** W2 + W5. Lights already smeared; increase smear with the vocal.  
**Type:** T-NONE.  
**Motion:** scale 104→100. Grain 35%. Static overlay 6%.  
**Camera:** locked, slight gate weave.  
**Grade:** darkest of the film. Fog Cyan only in the smear.  
**Do:** let 3–4 seconds be almost empty.  
**Don't:** preview the rocket.

### 0:19–0:29 · V1a
**Lyric:** There's a gleam on the Texas shore  
**Plate:** `03_texas_shore_gleam.jpg`  
**Comp:** W1 + W2. Gleam is the distant vehicle + the wet reflection, not a sparkle sticker.  
**Type:** BODY speak-rung, ragged left in the open right third, under the horizon. T-LATE + T-RAIN.  
Emphasis word **gleam** → strain-rung for 8 frames.  
**Motion:** drift right 2%.  
**Don't:** add a caption "Texas".

### 0:29–0:34 · V1b
**Lyric:** A stainless prayer we can't ignore  
**Plate:** `04_metal_skin_prayer.jpg`  
**Comp:** W6 extreme texture. Chainlink stays in foreground.  
**Type:** NERVE italic for **prayer** only; rest BODY. Place type in a fence diamond if it fits. T-HOLD.  
**Motion:** macro drift across beads of water.  
**Grade:** Fog Cyan + Sodium split on the steel.

### 0:34–0:39 · V1c
**Lyric:** We packed the silence in a metal skin  
**Plate:** hold `04`, match-dissolve 12 frames into `05_packed_silence_yard.jpg` at 0:36.  
**Type:** BODY. **silence** whisper-rung, **metal skin** speak-rung. T-DECAY on "silence".  
**Motion:** the yard plate is seen through the same fence logic — keep a dark left bar (car pillar).

### 0:39–0:46 · V1d
**Lyric:** And told ourselves this is where we begin  
**Plate:** `05_packed_silence_yard.jpg`  
**Comp:** W2 + W3.  
**Type:** the whole line speak-rung, then **begin** drops to whisper as if we do not believe it. T-LATE.  
**Motion:** almost still.

### 0:46–0:51 · PRE a
**Lyric:** The ground is shaking like a memory  
**Plate:** `06_ground_shaking.jpg`  
**Comp:** W4 low + W5.  
**Type:** BODY strain-rung. T-SPLIT on **shaking**. T-STEP on the line.  
**Motion:** 2–3 px camera shake, 12 fps cadence, decaying. Dust already in plate — do not add stock debris.  
**Grade:** Sodium lifts; Oxblood creeps into the lower third.

### 0:51–0:55 · PRE b
**Lyric:** Of everything we couldn't keep  
**Plate:** hold `06`, flash 4 frames of `03` as a memory insert on "keep".  
**Type:** NERVE italic, speak-rung, lower right. T-DECAY through the downbeat of the chorus.  
**Do:** the insert is the only flashback in the film. Once.

### 0:55–1:00 · CH1 a
**Lyric:** Starship rising through the thinning air  
**Plate:** `07_starship_rising.jpg`  
**Comp:** W1. Vehicle on a diagonal.  
**Type:** **Starship** BODY speak; **rising** T-SCALEHIT to cry-rung; rest speak. Place type in the empty lower-left sky, not on the flame.  
**Motion:** very slow push in. Flame smear only.  
**Glitch:** 4 frames of scanline at the top edge already in the plate — keep it.

### 1:00–1:07 · CH1 b
**Lyric:** I hear them singing from a place that isn't there  
**Plate:** dissolve to `08_voices_in_static.jpg`  
**Comp:** W3 doorway.  
**Type:** whisper-rung for the whole line except **isn't there** in TELEMETRY. T-LATE.  
**Motion:** CRT snow increases with the vocal stack. Static overlay → 22%.  
**Don't:** show a choir. The "them" is the smear on the wall and the broken CRT.

### 1:07–1:10 · CH1 c
**Lyric:** Beautiful voices in the static  
**Plate:** `08` with static overlay 45–55%.  
**Type:** **Beautiful** NERVE italic strain-rung; **STATIC** wall-rung TELEMETRY, T-SPLIT, 8 frames only then drop to cry-rung.  
**This is one of two wall-type moments.**

### 1:10–1:26 · CH1 d + air
**Lyric:** Calling us home to a sky we've never known  
Then instrumental air until 1:26.  
**Plate:** `09_sky_never_known.jpg`  
**Comp:** W2 + W3 viewport.  
**Type:** **home** T-SCALEHIT cry-rung; **sky we've never known** whisper, wide tracking, sits on the lower sash of the window. T-HOLD into the air.  
At 1:16 type off. Picture only. Slow push through the glass. Female vocal = increase Fog Cyan, T-NONE.

### 1:26–1:30 · V2 a
**Lyric:** The booster falls like a broken vow  
**Plate:** `10_booster_falls.jpg`  
**Comp:** W1. Booster occupies the right third. Left is empty sea — that emptiness is the vow.  
**Type:** BODY speak; **broken vow** NERVE italic. Place on the empty water, left. T-LATE.  
**Motion:** booster drifts down 6% of frame height over the cue.  
**Grade:** Sodium on the fire, Doyle Emerald on the sea.

### 1:30–1:35 · V2 b
**Lyric:** Back into the heat we left behind  
**Plate:** hold `10`, 8-frame insert of `06` heat on "heat".  
**Type:** T-DECAY.  
**Motion:** continue the fall. Do not cut to an explosion.

### 1:35–1:37 · V2 c
**Lyric:** While we climb into the quiet  
**Plate:** `11_clocks_forget.jpg`  
**Comp:** W3 bulkhead window.  
**Type:** whisper. T-MONO on **quiet**.

### 1:37–1:41 · V2 d
**Lyric:** Where the clocks forget to wind  
**Plate:** `11`  
**Type:** TELEMETRY speak-rung over the clock cluster. T-MONO. One clock hand can be a separate rotating layer, slowing to a stop on "forget".  
**Motion:** almost none. Listen to the mix — this is the quietest picture.

### 1:41–1:44 · PRE2 a
**Lyric:** No more gravity to hold the name  
**Plate:** `11` push toward the Earth window.  
**Type:** BODY; **name** fades first (identity leaving). T-STEP.

### 1:44–1:50 · PRE2 b
**Lyric:** No more weight to keep us the same  
**Plate:** match to a gentle drift of `07` starting at 1:47 (pre-lap chorus).  
**Type:** NERVE italic. T-DECAY across the chorus downbeat.

### 1:50–1:55 · CH2 a
**Lyric:** Starship rising through the thinning air  
**Plate:** `07_starship_rising.jpg` again, tighter crop (scale 112 start).  
**Type:** same as CH1 a but 10% smaller — we have heard this prayer. T-HOLD shorter.

### 1:55–2:02 · CH2 b
**Lyric:** I hear them singing from a place that isn't there  
**Plate:** `08`  
**Type:** even later (T-LATE + 3 extra frames). Whisper.

### 2:02–2:05 · CH2 c
**Lyric:** Beautiful voices in the static  
**Plate:** `08` + static 50%. Brief 3-frame cut of `09`.  
**Type:** do **not** repeat the wall-rung STATIC. Use cry-rung only. The first chorus already shouted.

### 2:05–2:30 · CH2 d + long air
**Lyric:** Calling us home to a sky we've never known  
Then a long instrumental / vocalizing bed.  
**Plate:** `09` until 2:18, then slow 24-frame dissolve to `12_leaving_earth.jpg` holding without type.  
**Type:** **home** speak, not cry. After 2:10, T-NONE.  
**Motion:** 2:18–2:30 is the widest, stillest picture in the film. Let the female vocal own it. Step-print the clouds.

### 2:30–2:35 · BR a
**Lyric:** This is not the end of Earth  
**Plate:** `12_leaving_earth.jpg`  
**Comp:** W2 window. Earth is dirty and particular, not a stock Blue Marble.  
**Type:** BODY speak, centered in the glass, small on purpose. T-LATE.  
**Don't:** add continents as graphics.

### 2:35–2:40 · BR b
**Lyric:** This is just the start of leaving  
**Plate:** hold `12`  
**Type:** **leaving** T-SCALEHIT to cry-rung, then T-DECAY. NERVE italic.

### 2:40–2:44 · BR c
**Lyric:** Cold and beautiful  
**Plate:** `13_machine_breathing.jpg`  
**Comp:** W6. Dead-center allowed.  
**Type:** NERVE italic, two words stacked, speak-rung, Paper White. Almost no motion on the type.  
**Motion:** breathing pulse at 87 BPM, 2% scale.

### 2:44–2:49 · BR d
**Lyric:** The machine that dreams of breathing  
**Plate:** hold `13`, open aperture feel (slightly brighter core).  
**Type:** TELEMETRY whisper under the bellows. T-MONO.  
**Glitch:** 2-frame T-SPLIT on **dreams**.

### 2:49–2:57 · OUT a
**Lyric:** Don't look down  
**Plate:** `14_dont_look_down.jpg`  
**Comp:** W4 high / well.  
**Type:** **Don't look down** BODY strain-rung, then the second hit coming.

### 2:57–end · OUT b
**Lyric:** Don't look down  
(female vocalizing fading into static)  
**Plate:** `14` push into the well. From 3:02 cross to `02_intro_smudge.jpg` eaten by `ov_static_scanlines.jpg` at 60%+.  
**Type:** second **DOWN** is the other wall-rung moment. Hold. Then T-DECAY into static. Last readable word should be gone before the vocal is gone.  
**Motion:** camera does the forbidden thing — eases toward the fire at the bottom.  
**End card:** 1.5 s of near-black Harbor Shadow + grain. No title unless asked.

---

## 10. Layer architecture (agent implementation)

Build every cue as this stack, bottom to top:

```
[0] PLATE          still or gen-video locked to still
[1] PLATE_MOVE     transform (Ken Burns / fall / pulse)
[2] GRADE          teal/amber cool filter, −0.4 to −0.8 EV
[3] FLARE          anamorphic, only if a point source exists
[4] TYPE           max 2 layers (fill + split-duplicate)
[5] OBSTRUCTION    extra glass/fence if the plate needs more W2
[6] GRAIN          ov_grain_scratch  25–40% Overlay
[7] STATIC         ov_static_scanlines  variable Screen
[8] ABERRATION     edge-only
[9] LETTERBOX      optional 2.35 crop at 8% opacity bars (chorus + bridge only)
```

Export ProRes 422 HQ or high-bitrate H.264. Do not upload-and-recompress twice.

### Generative video extension (if used)

Prompt skeleton:

```
Analog 35mm film continuation of this exact still.
Wong Kar-wai framing, obstruction in foreground, underexposed,
cool teal shadows, amber practical lights, wet surfaces,
slow drift only, step-print motion smear, heavy grain,
chromatic aberration, indie music video, not CGI, not NASA footage,
no people, no faces, no logos, no readable signage, no HUD.
```

Negative: `sharp octane render, stock rocket launch, lyric karaoke bar, clean UI, centered poster, daylight, crowd, brand marks`

Duration per gen clip: match the cue length + 8 frames handles.

---

## 11. Sound-picture lock notes

You may not have stems. Use the mix as follows:

- When the raspy lead is dry and close → type is large and late.
- When reverb tail is long → T-DECAY matches the tail, not the grid.
- When glitch percussion hits → 1–2 frame T-SPLIT or scanline.
- When female vocal is solo → T-NONE, smear, Fog Cyan.
- If BPM drifts toward 80, stretch holds. If toward 95, shorten T-HOLD, never speed the Ken Burns into a music-video slam.

---

## 12. Do / Don't

**Do**
- Leave air. This song is 80–95 BPM and spacious. Picture should feel colder than the vocal.
- Crop plates. They are masters, not compositions. Reframe every cue.
- Let type be cut off by glass and fence.
- Repeat plates. Repetition is the chorus.
- Prefer one beautiful mistake (misregistered channel, late word) over a clean render.

**Don't**
- Don't show a high-res Starship hero turntable.
- Don't use comic-sans-kinetic type packs.
- Don't put every line in the lower third.
- Don't add astronaut faces, flags, mission patches, or company marks.
- Don't cut on every bar.
- Don't make Earth a shiny marble.
- Don't explain the lyrics with icons (no little house for "home").
- Don't add a title card unless requested.

---

## 13. QC checklist (run before delivery)

- [ ] No shot is dead-center except 2:40 and the DOWN card.
- [ ] Every shot has grain + cool filter.
- [ ] Type never pure white, never more than two lines.
- [ ] STATIC wall-type happens once. DOWN wall-type happens once.
- [ ] Female-vocal passages have no lyrics on screen.
- [ ] Booster falls right-third; sea on the left stays empty.
- [ ] No logo, no HUD, no face.
- [ ] 24 fps. Step-print is intentional, not dropped frames from export.
- [ ] Vertical-safe: hero + type readable in the center 1080×1920 crop.
- [ ] Last 2 seconds are static and almost black.

---

## 14. Prompt blocks for still regeneration

If a plate must be remade, keep the look locked:

**Universal look block**
```
photographed like a 1990s Wong Kar-wai film still crossed with Blade Runner night
and an analog indie music video. 16:9. Off-center. Frame through dirty glass or fence.
Single practical light source. Teal-emerald shadows, amber sodium, cool filter,
crushed blacks that still hold color, 35mm grain, anamorphic flare,
chromatic aberration, slight VHS tear at the edge, underexposed,
not glossy CGI, not NASA documentary, no people, no logos, no readable text.
```

---

## 15. File map

```
starship-rising-motion-bible/
├── MOTION_GRAPHICS_BIBLE.md      ← this file
├── AGENT_CUES.json               ← machine-readable cue list
└── assets/
    ├── plates/                   ← hero stills, numbered in story order
    ├── overlays/                 ← grain + static
    └── reference/                ← palette + physical type
```

End of bible.
)
