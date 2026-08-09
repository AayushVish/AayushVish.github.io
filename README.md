# Aayush Vishwakarma — Portfolio

Static portfolio built from the Figma file. Case study pages render the **exported Figma artwork** (not HTML recreations), with site navigation on top so the site matches the design.

## Run locally

Open `index.html` in a browser, or use any simple local static server:

```bash
python3 -m http.server 8080
```

## GitHub Pages

Deployed from the `main` branch root at `https://AayushVish.github.io`.

## Assets

All images live in `assets/` (optimized local copies of the Figma exports). Do not point the site at temporary `figma.com/api/mcp/asset/...` URLs — those expire.

If you update the Figma file, re-export the home previews and full case-study frames, replace the matching files under `assets/`, and keep the same filenames.
