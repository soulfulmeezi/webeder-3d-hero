# Webeder 3D Hero

Interactive 3D hero section for [Webeder](https://webeder.com/), built with Three.js.

## Live
https://soulfulmeezi.github.io/webeder-3d-hero/

## Features
- Golden key resting on a dark cinematic surface
- Holographic cyan key floating, slowly rotating and bobbing above it
- UnrealBloom post-processing glow
- Gold + cyan particle drift
- Mouse parallax camera shift
- Warm gold + cool blue volumetric-style lighting
- Transparent-friendly dark background for iframe overlay use
- Fully responsive, single self-contained HTML file, all deps via CDN

## 3D models
The scene auto-loads `models/golden-key.glb` and `models/holo-key.glb` when present, and falls back to high-quality procedural keys otherwise. To use Tripo3D exports, drop the two GLB files into a `models/` folder in this repo (same filenames) — no code changes needed.

## Embed
```html
<iframe src="https://soulfulmeezi.github.io/webeder-3d-hero/" style="width:100%;height:600px;border:0;display:block;" title="Webeder 3D Hero" loading="lazy"></iframe>
```
