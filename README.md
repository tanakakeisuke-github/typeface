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
- **Music** — Upload your own audio file to drive particle movement, color, and glitch intensity in real-time (bass = particle burst, mids = wave motion, highs = color shift, beat detection = font glitch)
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
- Music-reactive mode: FFT frequency analysis drives particle physics, color, and glitch effects
  - Beat detection with bass/mid/high frequency band separation
    - Audio file upload with playback controls and progress bar

## Tech

Single HTML file. No dependencies, no build step.

- Canvas 2D for particle rendering + noise
- Web Audio API for sound synthesis + AnalyserNode for music-reactive FFT
- Vanilla JavaScript (ES5 compatible)

## GitHub Pages

1. Push this repo
2. Settings > Pages > Source: main branch, root
3. Live at `https://<username>.github.io/<repo-name>/`

## License

MIT
