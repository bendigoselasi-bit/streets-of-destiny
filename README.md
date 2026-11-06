# STREETS OF DESTINY

An original browser-based 3D open-world narrative game prototype set in a fictional modern African city inspired by Accra.

## Current prototype

- Three.js 3D scene with a fictional neighbourhood street
- Third-person placeholder character
- Keyboard movement and mouse-drag camera look
- Basic mission marker and HUD
- Static-site deployment structure

## Run locally

This is a static browser project. Because it uses JavaScript modules, serve it over HTTP rather than opening index.html directly.

For example, with Python installed:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

An internet connection is required for the Three.js CDN import.

## Deploy on Render

Create a Render **Static Site** connected to this repository.

- Branch: `main`
- Build command: leave blank
- Publish directory: `.`
- Root directory: leave blank

## Controls

- WASD or arrow keys: move
- Mouse drag: rotate camera

## Roadmap

1. Replace placeholder character and buildings with original high-quality GLB assets.
2. Add interaction and mission systems.
3. Add vehicles, pedestrians, and traffic.
4. Add district streaming, save data, audio, and performance optimization.

All characters, locations, stories, and assets are original.