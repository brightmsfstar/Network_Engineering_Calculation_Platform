# Network Engineering Calculation Platform

Multilingual IPv4, IPv6 and VLSM calculation dashboard with PDF and CSV reporting support.

## Files

- `index.html` - main PWA app
- `manifest.json` - PWA manifest
- `service-worker.js` - offline support
- `icons/` - app icons

## GitHub Pages

Upload the contents of this folder to your repository root:

- index.html
- manifest.json
- service-worker.js
- README.md
- icons/

Then enable GitHub Pages from `main` branch and `/ (root)`.

## Fix included

This version fixes the issue where JavaScript text appeared on the dashboard. The service worker registration is now placed before the real closing body tag, not inside the print-report HTML template.
