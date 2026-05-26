# AR Test Offline Use

This folder now has no internet dependency for local use.

## Recommended

1. Double-click `start-local-server.command`.
2. Open `http://localhost:8080` in Chrome.
3. Allow camera access.
4. Point the camera at `QRcode Trigger.png` displayed on another screen or printed.

Browsers often block camera access when opening `index.html` directly as a `file://` file. Serving the same folder from `localhost` works offline and counts as a secure local context.

## Files

- `index.html`: offline-capable page that uses local scripts in `vendor/`.
- `index.self-contained.html`: archive copy with the scripts, marker, and video embedded into one HTML file.
- `assets/asset.mp4`: AR video content.
- `assets/marker.patt`: marker pattern.
- `vendor/`: local copies of A-Frame, AR.js, and gesture helper scripts.
