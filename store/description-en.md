# Gear Turn — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io, 145 chars)

Link metal gears from the power source to every fan! Mesh, ratio and jam
your way through 25 handcrafted levels. A free single-file HTML5 puzzle.

## Details

- Genre: Puzzle / Casual / Mechanics
- Controls: Mouse / Touch (drag gears from the tray into dashed slots; drag
  placed gears again to move or remove them). Keyboard: Esc = menu, R = reset.
- Goal: build a drive chain from the lightning-bolt power gear to every teal
  fan. Finish with moves ≤ PAR for 3 stars.
- Mechanics: meshing gears counter-rotate; 8-tooth gears drive 16-tooth gears
  at half speed (2:1 ratio); odd gear loops JAM the machine and must be
  undone; two power sources clash if their networks touch.
- 25 handcrafted levels: single chains → branches → fixed axles → jam traps
  and snares → ratio showcases → two-source networks.
- Features: move counter + star rating, level unlocking, progress/stars/mute
  saved in localStorage, powered-chain glow, wind particles, procedural metal
  graphics, fully synthesized sound (no audio files), single-file HTML5 (no
  external assets), works offline once loaded.
- Tech: Vanilla JavaScript, Canvas, WebAudio. No frameworks, no tracking, no
  external links in gameplay.

## Tags

gears, puzzle, logic, mechanics, machinery, casual, single-file, physics

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales to fit, portrait-friendly, touch + mouse)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## GameDistribution
- Upload gear-turn-gd.zip (contains only index.html; the GD SDK loader is
  embedded and activates automatically on gamedistribution domains)

## itch.io
- Upload zip (rename to gear-turn-itch.zip), mark "This file is playable in
  browser", entry file: index.html, viewport 480×640, kind: html
- Pricing: $0 (donations optional)
