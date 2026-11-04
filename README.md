# Gear Turn

A free single-file HTML5 gear-linkage puzzle. Drag metal gears into slots to
build a drive chain from the power source (lightning bolt) to every teal fan.
Meshing gears counter-rotate and an 8-tooth gear drives a 16-tooth gear at
half speed. Beware: an odd loop of gears fights itself and JAMS the machine.

**Play:** https://shuangyueliao.github.io/gear-turn/

## Features

- 25 handcrafted levels: single chains, branches, fixed-axle structures,
  jam traps, decoy slots, gear-ratio showcases and two-source speed clashes
- Real transmission simulation: distance-based meshing (tolerance < 20% of
  tooth pitch), direction alternation, teeth-ratio speeds (8T/16T = 2:1),
  odd-cycle jam detection, multi-source speed-conflict detection
- Drag & drop with slot snapping; placed gears can be re-dragged or returned
  to the tray; move counter with PAR-based 3-star rating
- Progress, stars and mute setting saved in localStorage
- Procedural metal gear graphics (canvas), fully synthesized sound
  (WebAudio): placement clicks, ratio-pitched hum, ratchet ticks, jam
  grinding, win arpeggio
- Mouse + touch input, responsive canvas, portrait-friendly
- Zero external assets, zero analytics, zero external links in gameplay

## Controls

- Drag gears from the tray into dashed slots (mouse or touch)
- Drag a placed gear again to move it back to the tray or into another slot
- Keyboard: `Esc` menu, `R` reset level

## Tech

Vanilla JavaScript + Canvas + WebAudio in one `index.html` (~43 KB).
Portal SDKs (CrazyGames / GameDistribution) load only on their own domains.

## Run locally

```bash
python3 -m http.server 8890
# open http://localhost:8890/
```

## License

MIT
