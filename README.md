# Polymarket Edge Finder — Patched GitHub Pages Package

This package is meant to replace the earlier scanner build if that build showed a scan failure.

## What changed

- Safer parsing for `clobTokenIds` and `outcomes`
- Batch midpoint and price fetching
- More fault-tolerant scanning
- New cache version so GitHub Pages / iPhone PWA should update more cleanly

## Upload steps

1. Replace the files in your GitHub repo root with the files from this package.
2. Commit the changes.
3. Open your GitHub Pages URL in Safari.
4. Hard refresh once.
5. If you previously added the app to Home Screen and it still looks old, remove it and add it again.

## Files

- `index.html`
- `manifest.json`
- `service-worker.js`
- `icon-192.png`
- `icon-512.png`
- `.nojekyll`

