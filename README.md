# 🧚 Fairy Food Feast

A magical browser-based PWA where you help a fairy catch ingredients to cook up yummy recipes.
Made with love for Eva 💖

## Play

👉 **[Play online](https://rd4704.github.io/fairy-food-feast/)**

Or "Add to Home Screen" on iPad/iPhone to install it as a fullscreen app — works offline once installed.

## Run locally

```bash
python3 -m http.server 8765
# then open http://localhost:8765
```

## Tech

- HTML5 Canvas 2D
- Web Audio API (procedural sounds, no audio files)
- Vanilla JS, single-file game logic
- PWA: manifest + service worker for offline play
- No build step, no dependencies

## Deploy

Pushing to `main` automatically publishes via GitHub Pages
(see [.github/workflows/deploy.yml](.github/workflows/deploy.yml)).
