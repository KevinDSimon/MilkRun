<img src="icon-192.png" width="96" height="96" alt="Milk Run icon">

# Milk Run

A pumping session timer for Spectra S1/S2 pumps. Pick a 15, 20, 25 or 30 minute session and it walks through each step (letdown or expression mode, cycle speed, vacuum range), dings when it's time to change settings, and logs ounces per side.

Session plans follow the PumpingMamas Spectra cheat sheet.

## Use it

Open the GitHub Pages URL in Safari on an iPhone, then Share → Add to Home Screen. It runs full-screen and works offline after the first load.

The log is stored on the phone only. Use Export CSV in the app to back it up.

## Files

- `index.html` is the whole app
- `manifest.webmanifest`, `icon.svg` and the `icon-*.png` files give it its home screen name, icon and favicon
- `sw.js` caches the app for offline use. Change `CACHE` in it when you publish an update so phones pick up the new version.
