# Game Zone 🎮

A collection of 3D mini-games built with Three.js. One tap to play — mobile friendly.

## Games

| Game | Description |
|------|-------------|
| 🗼 [Stack Tower 3D](stack-tower-3d/) | Drop the sliding blocks and build the tallest tower. Speed increases every level. |
| 🛺 [Rickshaw Run 3D](rickshaw-run-3d/) | Desi Flappy-style flyer — tap to keep the rickshaw flying through the pipes. |
| ⚡ [Reaction King 3D](reaction-king-3d/) | Wait for green, tap as fast as you can. 5 rounds, average score, best saved. |

## Run locally

No build step needed — just serve the folder and open `index.html`:

```bash
cd game-zone
python3 -m http.server 8000
# open http://localhost:8000
```

## Tech

- Three.js (CDN) for 3D rendering
- Plain HTML/CSS/JS — no frameworks, no build tools
- Best scores saved in `localStorage`
- Tiny WebAudio synth sounds — no audio files needed
