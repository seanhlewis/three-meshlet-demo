# three-meshlet-demo

Live WebGPU demo site for the Three.js meshlet renderer project.

This repository is meant to run directly on GitHub Pages as a static site.

## GitHub Pages setup

1. Open repository settings for `seanhlewis/three-meshlet-demo`.
2. Go to **Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`.
5. Save.

After Pages finishes deploying, the site URL is:

- https://seanhlewis.github.io/three-meshlet-demo/

## Local preview

```bash
python -m http.server 8787
```

Then open:

- http://127.0.0.1:8787/

## Repo layout

- `index.html` - main demo app
- `build/` - bundled Three.js WebGPU files used by the demo
- `jsm/` - controls, loaders, inspector, meshopt, draco decoder assets
- `models/` - demo GLTF and GLB assets
