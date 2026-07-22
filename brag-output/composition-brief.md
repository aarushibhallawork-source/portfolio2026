# Hyperframes Composition Brief: Aarushi Bhalla — Portfolio (the one you can play)

## Objective
Create a short launch-style brag video: a designer's portfolio that's secretly a playable
pixel platformer starring the designer. Playful, postable, ~20s.

## Output
- Composition directory: `brag-output/composition/`
- Rendered video: `brag-output/brag.mp4`
- Format: landscape — 1920x1080
- Duration: 20 seconds (5 scenes)

## Source Material
- Project root: `/Users/aarushibhalla/Desktop/Portfolio 2026`
- Primary files read: `index.html` (full site), whole session context.
- Product name: Aarushi Bhalla — Product Designer (portfolio)
- Tagline / strongest claim: "Most portfolios you scroll. This one you play."
- Key UI / visual moment to recreate: the pixel-art platformer — a caped pixel Aarushi in a
  lilac valley with a castle, punching mauve "?" mystery boxes; the "A Day in my Life"
  collectibles; the level-complete stars; then the real case-study cards; then the footer.
- REAL project assets are in `brag-output/composition/assets/img/` — USE THESE (they are the
  product): `bg-valley.png` (valley/castle background), `character-new.png` (standing),
  `jump-ascend.png` (arm-up jump), `jump-descend.png` (falling), `box.png` (mauve "?" box),
  `matcha.png`, `macbook.png`, `badminton.png` (collectibles), `star.png` (gold star),
  `platform-1.png` (grass platform), `avatar.png` (pixel avatar for the end card).
  All pixel art: render with `image-rendering: pixelated`.
- Copy that must appear verbatim:
  - "Most portfolios you scroll." / "This one you play."
  - "A Day in my Life"
  - "control me using the arrow keys and the space bar"
  - "Strawberry Matcha" — "the fuel that gets me through 4 pm changes"
  - "Macbook Pro" — "where every idea actually gets built"
  - "Badminton Racket" — "how I unwind after a long day of work"
  - "An AI workflow builder for National Healthcare policy makers in Rwanda"
  - "Auditing a fragmented app-to-offline Loan Recovery flow for lower dropoffs"
  - "That was the work. Now's the reaching out part."
  - "Made with Claude Code, Designed with Figma. No templates were harmed."
  - "Aarushi Bhalla | Product Designer"

## Creative Direction
- Tone preset: default
- Creative direction: playful retro-game launch trailer for a portfolio that's secretly a game.
- Interpretation: comfortable 5-scene pacing; energetic but legible; warmth over slickness;
  humor comes from the site's real charm (a playable resume), never forced.
- Angle: It looks like a clean designer portfolio, but it's a Mario-style minigame starring
  the designer. The flex and the joke are the same thing — she built a playable portfolio.
  It ends on the site's own deadpan credit line.
- Hook: pixel Aarushi in the sunflower field; "Most portfolios you scroll." slams in, she
  jumps, it flips to "This one you play."
- Outro / punchline: footer headline, then the credit line "…No templates were harmed.",
  then the end card with the pixel avatar.
- Avoid: generic SaaS language, abstract filler visuals, redesigning the brand, non-pixel
  fonts on the game scenes.

## Visual Identity
- Background: `#160F17` (deep plum-black) — the stage ground / #root background (opaque, to
  avoid white-flash seams).
- Text: `#ffffff`
- Accent: `#ce93c5` (mauve); pill/box tints `rgba(216,183,211,0.3)` fill, border `#d8b7d3`.
- Display font: Clash Display (load via Fontshare like the site:
  `https://api.fontshare.com/v2/css?f[]=clash-display@400,500,600&f[]=general-sans@400,500,600&display=swap`).
  Semibold for headlines. Fallback: system sans if the font fails.
- Body font: General Sans.
- Visual references: the pixel valley + caped character + mauve "?" boxes are the signature.
  Cards use `border-radius: 20px`, 1px accent borders, deep-plum translucent fills — match
  the site's card look.

## Storyboard
Use `brag-output/brag-plan.md` as the creative contract. Scene summary:
1. Hook "you play" — 3s — pixel valley + standing→jump sprite; "Most portfolios you scroll." → "This one you play."
2. It's really playable — 4s — "A Day in my Life" game tab + control-hint pill; run→jump→punch a "?" box → aura toast "Strawberry Matcha · +100 aura points".
3. A Day in my Life (collectibles) — 5s — 3 cards one-by-one (matcha/macbook/badminton) with their captions; hold the full set.
4. Level complete → real work — 4.5s — 3 gold stars pop, dissolve into the Medtronic + SAVii case-study cards with a stat strip "10+ pain points · 15% ↓ drop-offs · Prioritized roadmap".
5. Outro / punchline — 3.5s — footer headline + credit line + end card (avatar + "Aarushi Bhalla | Product Designer").

## Audio
- Audio role: warm upbeat bed with playful arcade accents.
- Audio arc: bed enters under the hook; small lift and collect-rhythm through the box scenes;
  fades under the final credit line so the deadpan punchline reads in near-silence.
- Music: `assets/music/happy-beats-business-moves-vol-1-by-ende-dot-app.mp3` (~120 BPM).
- Music treatment: start ~0.0s, low behind text (~0.3–0.4), slight lift in Scene 3, fade-out
  across Scene 5 so the credit line lands clean.
- Music cue guidance: bundled preset at `assets/music/happy-beats-business-moves-vol-1-by-ende-dot-app.music-cues.json`
  (120.19 BPM; strong beats ~16–24s, beat grid ~0.5s apart from 3.0s). Beat-lock 1–2 major
  moments (the hook flip; the game→work dissolve). Snap the 3 collectible reveals to
  every-other-beat (~1.0s apart) so each caption holds its ~0.8s reading floor.
- Audio-reactive treatment: subtle — a small glow/pop on each box collect and a gentle
  presence lift on the hero title; no waveform/EQ bars.
- Audio-coupled moments:
  - Scene 1 — soft jump whoosh on the hop.
  - Scene 2 — box punch → collect SFX; light land thud.
  - Scene 3 — one clean collect SFX per item, on the beat (3 total).
  - Scene 4 — soft UI ticks on the 3 stars; one whoosh on the game→work dissolve.
  - Scene 5 — near-silence on the credit line; tiny settle on the end card.
- SFX selection guidance: use `brag-output/sfx-analysis.md` (copied from the skill). Pick a
  bright, short "collect/confirm" cue for the boxes (e.g. an `interface/` select/bong or a
  clean casino chip cue) — keep it single per item; a soft `impact/` footstep or drop for the
  land; light `ui/` clicks/switches for the stars. Prefer low high-frequency-risk files for
  the repeated collect sound.
- Exact SFX choice: choose filenames, timestamps, density, and volume against the implemented
  animation. Copy selected SFX into `brag-output/composition/assets/sfx/`.
- Audio files: music already in `assets/music/`; copy any selected SFX into `assets/sfx/`.

## Hyperframes Instructions
Load the composition-building Hyperframes domain skills — `hyperframes-core`,
`hyperframes-animation`, `hyperframes-creative`, `hyperframes-keyframes`, `hyperframes-cli`.
This is a /brag build: do NOT enter the `hyperframes` entry-point intent interview or the
generic promo/launch workflow. Prefer native Hyperframes conventions.

Requirements:
- Show the real pixel-game assets (they are the product's signature UI).
- Keep all text readable in the final render (reading-time floor: short label ~0.8s settled,
  sentence ~0.3s/word).
- Keep total duration 15–25s (target 20s).
- Include the music + SFX layer.
- Beat-lock 1–2 major tweens to strong cues (±0.15s), mark `// beat-locked`.
- Snap the 3 sequential collectibles to consecutive beats (±0.10s), mark `// beat-grid`,
  but hold each caption to its reading floor (every-other-beat).
- Wire at least one subtle audio-reactive element (hero glow / card presence), or document
  extraction failure and skip — do not block the render.
- `#root` background must be opaque `#160F17` (white-flash seam guard).
- Run `npx hyperframes check` before render — it is the single gate. Then render high quality
  to `brag-output/brag.mp4`.
