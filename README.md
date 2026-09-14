# GOAL Integration Guides

A single self-contained HTML page (`index.html`). All assets, including React, are embedded in the file, so there is no build step and no dependencies.

## Deploying on Vercel

1. Import this GitHub repo in Vercel.
2. Framework Preset: **Other**. Leave Build Command and Install Command empty, and leave Output Directory as the repo root.
3. Deploy. The guide is served at `/`.

To update the guide, replace `index.html` with the new export (keep the name `index.html`) and push.
