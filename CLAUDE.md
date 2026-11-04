# Milk Run

A static home-screen web app for iPhone. Published with GitHub Pages from the `main` branch, root folder.

- Live: https://kevindsimon.github.io/MilkRun/
- Repo: https://github.com/KevinDSimon/MilkRun

## Files
All files stay at the top level (no subfolders): `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `icon-180.png`, `icon-192.png`, `icon-512.png`, `README.md`.

## Publishing an update
1. Edit the app files.
2. Bump the `CACHE` name in `sw.js` (`pump-v5` → `pump-v6`, and so on). Without this, phones that already installed the app keep the old version.
3. Commit and push to `main`.
4. Wait for the Pages build to finish: `gh api repos/KevinDSimon/MilkRun/pages/builds/latest --jq .status` should say `built`.

## Important
- Deleting the app from the home screen erases the log stored on the phone. Export the CSV first.
- The repo must stay public, because GitHub Pages on a free account requires it.
