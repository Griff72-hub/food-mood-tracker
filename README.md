# Food & Mood Tracker

A small iPhone-friendly progressive web app. Entries are stored in the browser using localStorage.

## Quick test
Open `index.html` in a browser. Most features work immediately.

## Install on an iPhone
The app must be hosted over HTTPS for offline installation. Upload all three app files to a static host, open the resulting address in Safari, tap Share, then Add to Home Screen.

## Files
- `index.html`: complete app
- `manifest.webmanifest`: install metadata
- `sw.js`: offline cache

## Privacy
Entries remain in that browser profile unless exported. Clearing Safari website data may delete them, so use Export data regularly.
