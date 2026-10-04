# Snakes & Ladders — Sawda Mobile App

This package converts the supplied single-file HTML game into an installable
mobile web app (PWA). The original board/game is preserved; only PWA metadata
and offline support were added.

## Android
1. Put this folder on a web host using HTTPS (or use any local web server).
2. Open the URL in Chrome on Android.
3. Choose "Add to Home screen" / "Install app".
4. Launch it from the phone home screen. It opens as a standalone app.

## iPhone/iPad
1. Open the HTTPS URL in Safari.
2. Tap Share.
3. Choose "Add to Home Screen".
4. Launch from the home screen.

The game can cache itself for offline use after the first successful load.

Note: This package is an installable PWA rather than a signed .apk/.ipa.
