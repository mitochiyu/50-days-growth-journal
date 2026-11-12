# 50 DAYS — The Last Chapter of 2026

A responsive Korean personal growth journal for 2026-11-12 through 2026-12-31.

## Deploy with GitHub Pages
1. Create a public repository named `50-days-growth-journal`.
2. Upload `index.html`, `manifest.json`, and `sw.js` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site.

## Data
Daily entries are stored in the browser's localStorage. Photos are stored as compressed-size-limited data URLs (1.5 MB per image) in the same local data object. Export JSON regularly. Clearing browser data or switching devices can remove access to local records; keep backups.

## Notes
Browser notifications are best-effort while the page is open. This static site does not include a server-side scheduler or cross-device sync.
