# Tetris 2026

A fully playable Tetris clone in a single HTML file. No frameworks, no build step, no dependencies — just open it in a browser and play.

## Why

Sometimes you just want to build something fun. This was a weekend project to see how far you can push a single file with vanilla JavaScript and CSS. Turns out: pretty far.

## Features

- Classic Tetris mechanics — rotation, wall kicks, soft/hard drop
- Ghost piece preview showing where your piece will land
- Line clear animations with scoring and level progression
- Next piece preview
- Pause/resume
- Responsive layout that works on desktop and mobile
- Animated gradient background that shifts as you level up

## Play It

```bash
open index.html
# or just double-click it
```

That's it. No `npm install`, no `docker compose`, no environment variables. Just a browser.

## Tech

- Vanilla JavaScript (ES6+)
- HTML5 Canvas for the game board
- CSS animations and gradients
- Web fonts (Inter)
- ~470 lines total

## Controls

| Key | Action |
|-----|--------|
| ← → | Move piece |
| ↑ | Rotate |
| ↓ | Soft drop |
| Space | Hard drop |
| P | Pause |

## Screenshot

The game features a dark theme with a purple/blue gradient background, glowing piece colors, and a clean minimal UI showing score, level, lines cleared, and next piece.

---

Built for fun, February 2026.
