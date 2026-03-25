# SONG BIRD 🐦🎤

Use your voice as the controller for your character. Sing to fly. Dodge the contribution graph. Try not to embarrass yourself.

## How it works

- **Calibrate your voice.** Sing a comfortable note for 3 seconds. The game learns your range.
- **Sing higher to fly up.** The pitch of your voice controls the bird's height.
- **Sing lower to descend.** Or just stop singing — gravity does the rest.
- **Dodge the obstacles.** GitHub contribution graph columns scroll toward you. Find the gap.

By score 10 you'll be humming confidently. By score 25 you'll be doing vocal runs. By score 50 your coworkers will file an HR complaint.

This is working as intended.

## What's under the hood

One HTML file. No build step. No npm install. No server required.

- [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) for microphone pitch detection
- [Canvas 2D](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) for rendering
- Autocorrelation algorithm for real-time pitch tracking
- GitHub contribution graph blocks as obstacles
- Pixel-art Poptocat as the playable character

## Run locally

```bash
python3 -m http.server 8000
open http://localhost:8000
```

Microphone needs HTTPS or localhost.

## Lineage

This repo is part of a nerd-sniping chain of voice/body-controlled browser games between GitHub colleagues. See also:
- [@ashleywolf's Scream Invaders](https://github.com/ashleywolf/scream-invaders) — Space Invaders controlled by screaming
- [@leereilly's 3D Ping Pong](https://github.com/leereilly/3dpingpong) — Pong controlled by your face
- [@martinwoodward's 3D Breakout](https://github.com/martinwoodward/3dbreakout) — Breakout in 3D

Same question, different answer: what if the controller is your singing voice?

## License

MIT
