RAKI'S STUDENT PLANNER — INSTALLABLE WEB APP FILES

This folder is prepared as a Progressive Web App (PWA). It needs to be hosted on an HTTPS website before Android Chrome can install it as an app. Opening index.html directly from Downloads will not enable the full install experience.

Files:
- index.html: the planner
- manifest.json: app name, appearance and icons
- service-worker.js: offline caching
- icon-192.png and icon-512.png: home-screen icons

After hosting on an HTTPS site:
1. Open the hosted site in Chrome on Android.
2. Tap Chrome's three-dot menu.
3. Choose "Install app" or "Add to Home screen" if shown.
4. Confirm. The planner should then have an icon on your home screen.

Your planner's task data is stored in browser local storage on that device. Use the in-app backup feature regularly.
