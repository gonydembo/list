# SuperList PWA — Deploy & Install Guide

## What's in this folder
```
superlist-pwa/
├── index.html          # The complete app (single file)
├── sw.js               # Service worker (offline support)
├── manifest.json       # PWA manifest (install capability)
├── icon-192.png        # App icon 192x192
├── icon-512.png        # App icon 512x512
├── apple-touch-icon.png # iOS home screen icon
└── README.md           # This file
```

## Free Deployment Options (pick one)

### Option A: Netlify (easiest — drag & drop)
1. Go to https://app.netlify.com/drop
2. Drag the entire `superlist-pwa` folder onto the page
3. Done! You get a URL like `https://random-name.netlify.app`
4. Optionally set a custom name in Site Settings

### Option B: Vercel
1. Install: `npm install -g vercel`
2. Run: `cd superlist-pwa && vercel`
3. Follow prompts — you get a URL like `https://superlist.vercel.app`

### Option C: GitHub Pages (free forever)
1. Create a GitHub repo named `superlist`
2. Push all files to the `main` branch
3. Go to Settings → Pages → Source: main branch
4. Your app is at `https://yourusername.github.io/superlist`

### Option D: Cloudflare Pages
1. Go to https://pages.cloudflare.com
2. Connect your GitHub repo or upload directly
3. Free, fast, with custom domain support

---

## Install on iPhone

1. Open the deployed URL in **Safari** (must be Safari!)
2. Tap the **Share button** (square with arrow at bottom)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **"Add"**
5. The app appears on your home screen with the SuperList icon
6. Opens full screen — no browser bars!

## Install on Android

1. Open the deployed URL in **Chrome**
2. You'll see an automatic **"Install SuperList"** banner at the bottom
3. Tap **"Install"**
4. Or tap ⋮ menu → **"Install app"** / **"Add to Home Screen"**
5. The app appears in your app drawer like a real app

---

## Features
- ✅ Works offline after first load
- ✅ Full screen (no browser bars)
- ✅ App icon on home screen
- ✅ Data persists in localStorage
- ✅ Camera barcode scanning
- ✅ Image upload for products
- ✅ Hebrew + English bilingual
- ✅ All fields editable
- ✅ Custom products
- ✅ Nutrition info
- ✅ Share list
- ✅ Grouped by category

## Cost: $0
No developer accounts needed. No app store fees. Free hosting.
