TUE–FRI CHECKLIST PWA

FILES
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

IMPORTANT
For Chrome to offer "Install app" / "Add to Home screen" as a real app,
these files must be served over HTTPS (or localhost). Opening index.html
directly as file:// will not activate the service worker.

QUICK HOSTING
Upload the entire folder contents to any static HTTPS host such as:
- Vercel
- GitHub Pages
- Netlify
- Cloudflare Pages

After it is online:
1. Open the HTTPS address in Chrome on your phone.
2. Tap the three-dot menu.
3. Choose "Add to Home screen" or "Install app".
4. The checklist should then open standalone and remain usable offline after
   the first successful load.

Checklist progress is stored locally on that browser/device and is not sent anywhere.
