# Stable Evershine — Website

Static, single-page site (no build step). Everything runs from plain files.

## Files
- `index.html` — the entire site
- `support.js` — runtime the page loads
- `assets/` — images, logo, hero video, MahaRERA QR

## Deploy to GitHub Pages
1. Create a new GitHub repo and upload **all** files, keeping this folder structure (`index.html` at the repo root, `assets/` beside it).
2. Repo **Settings → Pages** → Source: `Deploy from a branch` → Branch: `main` / root → **Save**.
3. Your site goes live at `https://<username>.github.io/<repo-name>/` in ~1 minute.

## Local preview
Open `index.html` in a browser, or run any static server (e.g. `npx serve`) from this folder.

## Notes
- Update the domain in the `<link rel="canonical">` and Open Graph / `og:url` tags in `index.html` once you know the final URL.
- The 3D location map (MapLibre GL) and the page-header particle background (three.js) load from public CDNs — an internet connection is required for those two features.
