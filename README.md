# notesapplocal

**Sakura Notes 桜** — a clean, Japanese-themed notes app.
Live: https://notesapplocal.netlify.app/

## 🌸 Design

- Washi-paper background, sumi-ink text, vermillion (shu-iro) & sakura accents
- Japanese serif typography, hanko-style 桜 seal, sakura branch art
- Gently falling sakura petals (respects reduced-motion)
- Light (washi paper) & dark (indigo night) themes

## ✨ Offline / PWA support

The app is a **Progressive Web App (PWA)** — it saves locally on your device and opens **without internet**:

- 📝 All notes are stored in your browser's `localStorage` (on your device, private).
- 📦 A **service worker** (`sw.js`) caches the whole app, so it opens even with no internet.
- 📲 You can **install** it: browser menu → *Install app* / *Add to Home Screen*.

Tip: open the site once with internet — after that it works fully offline.
