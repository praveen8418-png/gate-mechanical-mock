GATE Mechanical Mock Test PWA
==============================

Files:
- index.html: your supplied portal, with PWA metadata and service-worker registration added
- manifest.json: install name, display settings, and icons
- service-worker.js: caches the app shell for repeat/offline opening
- icon-192.png and icon-512.png: app icons

Free deployment:
1. Create a GitHub account if you do not already have one.
2. Create a public repository, for example gate-mechanical-mock.
3. Upload ALL files in this folder to the repository root.
4. Open repository Settings -> Pages.
5. Select Deploy from a branch, choose main and /(root), then Save.
6. Wait for the published URL. Open it in Chrome on Android.
7. Chrome menu (three dots) -> Install app / Add to Home screen.

Notes:
- PWA installation needs HTTPS; GitHub Pages provides HTTPS.
- Question records are stored in this browser's IndexedDB, not shared across devices/users.
- MathJax is loaded from a CDN in the original file, so equations may not typeset offline unless MathJax files are also hosted locally.
- Keep JSON backups of your question bank. Browser data can be cleared by the device/browser.
- Test all exam features after deployment. This package adds PWA support but does not guarantee that every existing portal function is bug-free.
