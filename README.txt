NEET 235 LECTURE TRACKER — APP BUNDLE

This is an installable Progressive Web App (PWA) bundle, configured to open in standalone app mode after installation. It is not an APK.

FILES
- index.html: tracker app
- manifest.webmanifest: app name, icon and standalone display settings
- service-worker.js: offline caching
- icon-192.png / icon-512.png: app icons

IMPORTANT ANDROID INSTALLATION NOTE
Android requires the app to be served from a secure HTTPS website (or localhost) for installation and offline service-worker support. Opening index.html directly from Downloads will let you use the tracker, but will not enable app installation or offline caching. After hosting these files at an HTTPS address:
1. Open the HTTPS address in Chrome on Android.
2. Open Chrome menu (⋮).
3. Tap "Install app" or "Add to Home screen" (label varies).
4. Launch "NEET Tracker" from the home screen. It opens without the normal browser toolbar.
5. Keep using the same installed app/browser profile. Export a backup from inside the app occasionally.

The app saves checkmarks locally on that device/browser. It does not sync automatically between devices.
