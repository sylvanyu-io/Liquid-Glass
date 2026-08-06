# Liquid Glass

Two standalone experiments in refractive liquid-glass rendering.

- **SVG / DOM filter** keeps displacement maps, masks, tint, chroma offsets, and the filter graph visible in the DOM.
- **Canvas / WebGL shader** implements the lens as a Three.js fullscreen pass with a Kawase blur pyramid.

## Run locally

```bash
npm install
npm run dev
```

## Included

- Adjustable lens dimensions, corner radius, refraction, chroma, tint, and blur
- SVG filter implementation with generated displacement maps
- Three.js shader implementation with multi-stage Kawase blur
- Shared reference image and responsive controls

This repository is the standalone demo extracted from [sylvanyu.io](https://sylvanyu.io/).
