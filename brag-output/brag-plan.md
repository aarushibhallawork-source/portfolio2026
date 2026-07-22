# Brag Plan: Aarushi Bhalla — Portfolio (the one you can play)

## What is this app?
A product designer's single-page portfolio that's secretly a pixel-art platformer:
you control a caped pixel Aarushi, run and jump through a purple valley, and punch
open mystery boxes to reveal what fuels her day — then see the real products she's shipped.

## The angle
**"Most portfolios you scroll. This one you play."** The video leans into the twist:
it looks like a clean designer portfolio, but it's a Mario-style minigame starring the
designer. The joke and the flex are the same thing — she didn't just design a portfolio,
she built a playable one. It ends on the site's own deadpan credit line:
"Made with Claude Code, Designed with Figma. No templates were harmed."

## Hook (first 2-3 seconds)
Pixel Aarushi standing in a sunflower field under a lilac castle sky. Big display type
slams in: **"Most portfolios you scroll."** — then she jumps (arm-up sprite) and the line
flips to **"This one you play."** The pixel world IS the hook; show it immediately.

## Key moments (the middle)
- The **"A Day in my Life"** game tab + control hint "← → and the space bar" — establishes
  it's really playable.
- **Punching a "?" box** → it pops and an aura toast reads "Strawberry Matcha · +100 aura points" (coin SFX).
- **Three mystery boxes revealed one-by-one** — Strawberry Matcha ("the fuel that gets me
  through 4 pm changes"), Macbook Pro ("where every idea actually gets built"), Badminton
  Racket ("how I unwind after a long day of work"). Each with its own collect sound.
- **Level complete → real work:** the 3-star "A Day in my Life" popup dissolves into the
  actual case studies (Medtronic — "An AI workflow builder for National Healthcare policy
  makers in Rwanda"; SAVii loan-recovery audit) with real stats (10+ pain points, 15% ↓ drop-offs).

## Outro / punchline
Footer headline **"That was the work. Now's the reaching out part."** then the credit line
lands on the deep-plum card: **"Made with Claude Code, Designed with Figma. No templates were
harmed."** End card: the pixel avatar + "Aarushi Bhalla | Product Designer".

## User flow worth showing
Entry (land in the pixel valley) → key action (run, jump, punch mystery boxes to collect
matcha/macbook/badminton) → result ("A Day in my Life" level-complete popup, then the real
shipped work). The centerpiece is the game being *played*, not described.

## Tone
- Preset: default
- Creative direction: a portfolio that's secretly a pixel platformer — playful retro-game
  launch trailer, warm and postable.
- Interpretation: comfortable 5-scene pacing with room to breathe; energetic but legible;
  the humor comes from the site's real absurd charm (a playable resume), never forced.

## Format: landscape — 1920x1080
## Duration: 20s

## Visual identity (from the project)
- Background: `#160F17` (deep plum-black)
- Accent: `#ce93c5` (mauve); pill/box tints `rgba(216,183,211,·)`
- Text: `#ffffff`
- Display font: Clash Display (Semibold for headlines)
- Body font: General Sans
- Strongest visual element: the pixel-art valley (`bg-valley.png`) with the caped character
  sprites (`character-new.png`, `jump-ascend.png`, `jump-descend.png`), mauve "?" boxes
  (`box.png`), collectible icons (`matcha.png`, `macbook.png`, `badminton.png`), and the
  3-star popup (`star.png`). Use the REAL project assets — they are the product.

## Share copy (draft)
My portfolio is secretly a pixel platformer. Play as me, punch open some matcha, and see
what I actually shipped. 🎮

## Audio direction
- Role: warm upbeat bed with playful arcade accents.
- Music: `happy-beats-business-moves-vol-1` (bundled), ~120 BPM, positive/energetic.
- Music treatment: start ~0.0s under the hook, keep it low behind text, small lift on the
  box-collect sequence, gentle fade on the outro credit line so the punchline reads clean.
- Music cue guidance: preset read (120.19 BPM). Target strong beats for the sequential box
  reveals; beat grid ~0.5s apart across the whole window (3.0s–24.5s). Use the beat grid
  windows in Scene 3 but hold each collected item to the reading floor (~0.8s), snapping to
  every other beat rather than every beat.
- Audio-reactive treatment: subtle — a small glow/pop on each box collect; no waveform bars.
- SFX posture: moderate, motion-matched — arcade coin/collect on each "?" box (casino/ui),
  a soft jump/land thud on the hop, a light UI tick on the level-complete stars, one soft
  whoosh on the game→work transition.
- Audio-coupled moments: box punch + collect (coin), three-item reveal (coin per item on
  beat), star pop on the popup, credit-line settle.
- Restraint rule: no more than one coin per collected item; the outro credit line lands in
  near-silence so it reads as the deadpan punchline.

## Music cue guidance
- Track: `happy-beats-business-moves-vol-1-by-ende-dot-app.mp3`, ~120 BPM.
- Strong-cue targets: land the hook flip (~3.0s), and the three box collects near strong
  beats in the 16–20s region if timing allows — otherwise use the local beat grid.
- Beat-grid window for the 3-box sequential reveal: snap items to every-other-beat
  (~1.0s apart) so each caption holds its ~0.8s reading floor.
- Restraint note: keep coins single and clean; fade music under the final credit line.

## Storyboard

### Scene 1 — Hook: "you play" — 3s
Pixel valley (`bg-valley.png`, lilac sky + castle) with pixel Aarushi standing in the
sunflowers (`character-new.png`). Display type slams in: "Most portfolios you scroll." (hold
~1.0s), she hops (swap to `jump-ascend.png`), line flips to "This one you play." (hold ~1.0s).
Sequential/interaction: yes — a single simulated jump (sprite swap on the up-beat).
Audio intent: warm downbeat that says "fun, game, go".
Audio-coupled idea: soft jump whoosh on the hop.
Music: upbeat bed enters.
Transition mood: clean → Scene 2

### Scene 2 — It's really playable — 4s
The "A Day in my Life" game tab sits top-right on the frame; control hint pill shows
"← ▢ →  control me using the arrow keys and the space bar". Aarushi runs right and jumps
into a mauve "?" box (`box.png`) — it pops, an aura toast slides in top-right: "Strawberry
Matcha · +100 aura points".
Sequential/interaction: yes — simulate run → jump → box punch → toast.
Audio intent: playful; the punch feels satisfying.
Audio-coupled idea: coin/collect SFX exactly on the box punch; light land thud.
Music: bed continues, small lift.
Transition mood: clean wipe → Scene 3

### Scene 3 — A Day in my Life (the collectibles) — 5s
Three collectible cards arrive one-by-one on the deep-plum panel, each an icon + name +
line: Strawberry Matcha ("the fuel that gets me through 4 pm changes"), Macbook Pro ("where
every idea actually gets built"), Badminton Racket ("how I unwind after a long day of work").
Sequential/interaction: yes — 3 items reveal on every-other-beat (~1.0s apart), each held
~0.8s+ so its caption reads; the full set holds together at the end of the scene.
Audio intent: three satisfying arrivals building a little rhythm.
Audio-coupled idea: one clean coin per item, on the beat.
Music: bed with the collect rhythm riding on top.
Transition mood: soft → Scene 4

### Scene 4 — Level complete → real work — 4.5s
The "A Day in my Life" popup flashes 3 gold stars (`star.png`) + "Level complete" feel, then
dissolves into the actual case-study cards: Medtronic ("An AI workflow builder for National
Healthcare policy makers in Rwanda") and SAVii (loan-recovery audit), with a stat strip
"10+ pain points · 15% ↓ drop-offs · Prioritized roadmap". The beat: the game was fun, the
work is real.
Sequential/interaction: yes — stars pop in (tick), then the two project cards slide up.
Audio intent: a confident turn from play to substance.
Audio-coupled idea: soft UI ticks on the stars; one whoosh on the game→work dissolve.
Music: bed holds, slight forward push.
Transition mood: dramatic-but-clean dissolve → Scene 5

### Scene 5 — Outro / punchline — 3.5s
Footer headline "That was the work. Now's the reaching out part." (Clash Display Semibold),
then the credit card lands: "Made with Claude Code, Designed with Figma. No templates were
harmed." End card: pixel avatar (`avatar.png`) + "Aarushi Bhalla | Product Designer".
Sequential/interaction: none — let the punchline breathe.
Audio intent: music fades under the credit line so the deadpan lands.
Audio-coupled idea: none on the credit line (near-silence); tiny settle on the end card.
Music: gentle fade-out.
Transition mood: soft hold → end.

**Music mood for this video:** upbeat (playful, postable, ~120 BPM).
**Audio summary:** a warm upbeat bed carries a playful arcade layer — jump whoosh, three
clean box-collect coins on the beat, a couple of soft UI ticks — then fades under the
deadpan credit line so the punchline reads in near-silence.
