# weight-challenge

Static single-page app tracking weight-loss challenge progress. Data lives in [daten.js](daten.js); the page ([index.html](index.html)) is a self-contained bundle (no build step, no dependencies to install).

## Deploy on Vercel

1. Push this repo to GitHub (already connected to `origin`).
2. In Vercel, "Add New Project" → import this repository.
3. Framework preset: **Other** (static site, no build command needed).
4. Deploy.

## Local preview

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.
