# CLASH — Rock Paper Scissors

A neon-noir arcade-style Rock Paper Scissors game built as a single-page web app.

## Features

- **Best of 5** — First to 3 wins takes the match, with pip indicators tracking progress
- **Sound effects** — Synthesized audio via Web Audio API (no external files needed)
- **Confetti** — 1200-particle canvas celebration on match victory
- **Animated reveals** — Bouncy pop-in animations for choice cards
- **Visual feedback** — Screen flash and shake on wins/losses, win streak counter
- **Victory/Defeat overlay** — Match-end screen with score summary and replay button
- **Always Win mode** — Secret toggle in the upper-left corner

## Running

Serve the project with any static HTTP server:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

## Design

Designed by **Niki Nelson** ([@nikicreates](https://github.com/nikicreates))

## Tech

Pure HTML, CSS, and JavaScript — no dependencies, no build step. Fonts loaded from Google Fonts (Bebas Neue, Space Mono).
