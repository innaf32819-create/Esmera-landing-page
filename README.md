# Esmera Landing (Canvas version) — GitHub Pages

This package mirrors your latest canvas HTML exactly.

## Deploy from branch (simplest)
1. Upload all files to repo root on `main`.
2. Settings → Pages → Source: **Deploy from branch** → Branch: `main` / **/** (root).
3. Save. Your site will publish.

## Deploy via GitHub Actions (optional)
1. Keep `.github/workflows/pages.yml` from this package.
2. Settings → Pages → Source: **GitHub Actions**.
3. Push any commit → check the Actions tab.

Notes:
- `.nojekyll` is included (must stay in repo root).
- Video is at `assets/videos/hero.mp4` (already compressed if I had your file).
- Images are placeholders; replace with your real assets as needed.
