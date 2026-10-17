# BusBuddy App Prototype

This folder contains an installable-web-app (PWA) version of the BusBuddy HTML prototype.

## Important
- This is still a prototype. Bus positions, route map, and bus status are simulated.
- It does not connect to STOPR, school-bus GPS, or send reliable background bus alerts.
- Install support generally requires the app to be served from `https://` (or `localhost`); opening `index.html` directly as a file will show the prototype but usually will not enable installation/offline caching.

## Easiest way to try it
1. Open `index.html` to preview the design.
2. To install it as an app, publish this folder to a static HTTPS host (for example, a static site host) and open the resulting website in Chrome or Edge.
3. Use the browser's Install app option. On iPhone/iPad, open it in Safari and use Share → Add to Home Screen.

## Files
- `index.html` — BusBuddy interface
- `manifest.webmanifest` — app name, display settings, and icon
- `service-worker.js` — basic app-shell caching for supported browsers
- `busbuddy-icon.svg` — app icon
