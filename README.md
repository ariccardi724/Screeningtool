# Free Vestibular & Dizziness Screening Kiosk
**Ivy Rehab Physical Therapy – Bala Cynwyd North** (inside AFC Fitness)

## Included Files
- `index.html` — Main kiosk entry point (GitHub Pages / Netlify / PWA)
- `screening-kiosk.html` — Identical standalone copy for direct linking
- `manifest.webmanifest` — Progressive Web App manifest (`fullscreen`, `landscape`)
- `sw.js` — Offline service worker (`vestibular-kiosk-v3`)
- `icon-192.png` & `icon-512.png` — PWA home-screen / app icons
- `.nojekyll` — Ensures GitHub Pages serves all static files directly without Jekyll processing

## Quick Setup
1. Upload all files in this batch to the root of your GitHub repository (or `/docs` if configured in **Settings → Pages**).
2. Open the live `https://` URL on your Android tablet in Chrome.
3. Tap **Install App** (or Chrome menu `⋮` → **Install app**) to add it to the Home Screen, tap **Fullscreen**, and use Android **App Pinning** to lock the tablet to the kiosk.
4. **Staff Access:** Tap the Ivy Rehab logo **5 times** (PIN `1234`) to view sign-ups, export CSV, or change the PIN.
