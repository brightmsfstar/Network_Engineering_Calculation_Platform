# Network Engineering Calculation Platform

This package contains the completed Phase 1 dashboard as a Progressive Web App.

## Included modules

- IPv4 Calculator
- IPv6 Calculator
- VLSM Auto-Allocation Engine
- Equal-size subnet mode
- CSV export
- PDF / Print reporting
- Multilingual support: English, French, German, Spanish, Italian, Portuguese, Dutch, Polish, Urdu, Mandarin, Cantonese, Arabic
- Android/iOS home-screen install support
- Offline cache through service worker

## Files

- `index.html` - main application
- `manifest.json` - PWA manifest
- `service-worker.js` - offline cache
- `icons/` - app icons for Android/iOS/PWA

## How to test locally

Option 1: open `index.html` directly in a browser.
This works as a web app, but PWA install/offline service worker may not activate from `file://`.

Option 2: run a local web server from this folder:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Android install

Open the app in Chrome or Edge. Use the browser menu and choose **Install app** or **Add to Home screen**.

## iPhone/iPad install

Open the app in Safari. Tap **Share**, then choose **Add to Home Screen**.

## Deployment

For full PWA installation and offline support, host this folder on HTTPS, for example GitHub Pages, Netlify, Vercel, or any HTTPS web server.
