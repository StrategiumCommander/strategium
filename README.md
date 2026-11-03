# Strategium v4.22 — installable PWA

## Publish today (GitHub Pages)
1. Create a new GitHub repository (public for free Pages).
2. Upload **all five app files** from this folder to the repository root (index.html, manifest.webmanifest, service-worker.js, icon-192.png, icon-512.png).
3. Go to Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save.
4. Visit the HTTPS Pages URL shown there. It may take a few minutes to appear.

Alternative: Cloudflare Pages Direct Upload, uploading these files as a folder or ZIP.

## Install
- Android Chrome: site menu → Install app / Add to Home screen.
- iOS Safari: Share → Add to Home Screen → Add.
- Desktop Chrome or Edge: install icon in address bar or browser menu.

The first load requires internet; afterward the app shell is cached for offline use. Imported rosters remain **local to each browser/device**, not synced. Keep copies of original roster and stratagem files. Updating the service-worker cache version is necessary for new deployments.

This is an unofficial fan-made utility and is not affiliated with Games Workshop.
