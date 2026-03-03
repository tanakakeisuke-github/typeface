# Glitch Type

Interactive typographic art piece. Letters made of particle circles, glitching between serif and sans-serif, reactive to touch.

## Demo

Open `index.html` in a browser, or host via GitHub Pages.

## How to use

- **Type A–Z / Space** — Characters appear as particle formations, morphing from the previous shape
- **Backspace** — Delete last character
- **Click & drag** — Particles scatter from cursor
- **Auto mode** — Autonomous animation with wandering disruption
- **Sound** — Web Audio synthesis synced to visual intensity (works best when opened directly, not in iframes)
- **Clear** — Reset all text

Max 48 characters. Auto line-wrap at 12 / 24 chars.

## Features

- Particle system: each letter sampled into circles
- Serif / sans-serif font glitching (Georgia, Palatino, Helvetica, Futura, etc.)
- RGB channel corruption on disturbed particles
- Horizontal row displacement (VRAM error aesthetic)
- Bit-depth reduction at high intensity
- Dead pixels and misaligned dots (permanent bugs)
- Scanline overlay
- Per-character type sound with pitch mapped to alphabet position
- Noise / drone / glitch blip audio layers

## Tech

Single HTML file. No dependencies, no build step.

- Canvas 2D for particle rendering + noise
- Web Audio API for sound synthesis
- Vanilla JavaScript (ES5 compatible)

## GitHub Pages

1. Push this repo
2. Settings > Pages > Source: main branch, root
3. Live at `https://<username>.github.io/<repo-name>/`

## License

MIT
