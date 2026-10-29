# Monthly Period Tracker — installable app

Created by Nafisha Tamanna Nice.

This folder is a complete Progressive Web App (PWA). Upload the whole folder
to any free static host, open the link on your phone, and install it.

## Files
- `index.html` – the app
- `manifest.webmanifest` – app name, colours and icons
- `sw.js` – lets the app work offline
- `*.png` – app icons

## Option 1: Netlify Drop (easiest, no account needed to try)
1. Unzip this file.
2. Open https://app.netlify.com/drop on a computer.
3. Drag the `period-tracker-app` folder onto the page.
4. Netlify gives you a link like `https://something.netlify.app`.
   Create a free account if you want to keep the link permanently.

## Option 2: GitHub Pages
1. Create a new public repository on GitHub.
2. Upload all files from this folder .
3. Go to Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After a minute your app is at `https://<username>.github.io/<repo>/`.

## Install on a phone
- Android (Chrome): open the link → Settings tab → "Install app",
  or ⋮ menu → "Install app" / "Add to Home screen".
- iPhone (Safari): open the link → Share button → "Add to Home Screen".

## Notes
- The app must be opened over https (both hosts above do this) for install and offline mode to work.
- Data is saved on each phone only. Use Settings → Backup & restore to move it.
- To publish an update, replace `index.html` and change `VERSION` in `sw.js` (for example `mpt-v2`).
