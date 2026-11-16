SECOND BRAIN — INSTALLATION

WHAT'S INCLUDED
- Responsive personal knowledge app for MacBook and iPhone
- Notes with categories, tags, editing and pinning
- Projects and status tracking
- Daily journal
- Local keyword-based knowledge search
- Knowledge graph visualization
- JSON export/import backup
- PWA manifest and offline service worker

IMPORTANT LIMITATIONS
This version stores data in the browser's local storage. It does NOT automatically synchronize data between your Mac and iPhone, does not include a generative AI model, and does not run background automations. Those require a secure hosted sync/backend and AI service or local model. The app is fully usable without them.

FASTEST WAY TO USE ON MAC
1. Unzip the package.
2. Open index.html in Safari or Chrome.
3. Your data is saved in that browser on that Mac.
For PWA installation/offline support, serve it over HTTPS.

INSTALL ON IPHONE 15 AND MACBOOK NEO
A PWA must be hosted at an HTTPS address for reliable Add to Home Screen and service-worker support.
Free option:
1. Create a GitHub account and a new public repository (for example second-brain-app).
2. Upload the contents of this folder to the repository root.
3. In repository Settings → Pages, deploy from the main branch and root folder.
4. Open the resulting GitHub Pages HTTPS URL in Safari on your iPhone.
5. Tap Share → Add to Home Screen.
6. On MacBook Neo, open the same URL in Safari and use File → Add to Dock if available.
Keep the repository free of personal notes; this repository should contain only the app code.

MOVE DATA BETWEEN DEVICES
Settings → Export backup on one device, then Settings → Import backup on the other. Import replaces local data on that device. Export a backup before importing.

PRIVACY
Do not store passwords, payment-card data, government ID numbers, or highly sensitive information. Local browser storage can be cleared by browser cleanup. Export regular backups.
