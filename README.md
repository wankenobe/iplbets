# IPL Family Bets — Real-time PWA

All 3 phones sync instantly. Anyone can place bets from their own phone.

## Files needed
- `index.html` — the entire app
- `manifest.json` — PWA config
- `sw.js` — offline support
- `icon-192.png` + `icon-512.png` — app icons (make on canva.com)

---

## Step 1 — Firebase (free, ~5 min)

1. Go to **console.firebase.google.com** (sign in with Google)
2. Click **Add project** → name it anything → Continue
3. Click the **</>** Web icon → register app → copy the `firebaseConfig` object
4. In left menu: **Build → Realtime Database → Create database → Start in test mode**
5. Done — keep the config object ready

---

## Step 2 — Host on GitHub Pages (free)

1. Go to **github.com** → New repository → name: `ipl-bets` → Public
2. Upload: `index.html`, `manifest.json`, `sw.js`, and your two icon PNGs
3. Go to **Settings → Pages → Deploy from main branch → Save**
4. Your URL: `https://YOUR-USERNAME.github.io/ipl-bets`

---

## Step 3 — First launch (one person only)

1. Open the URL → paste your Firebase config → tap **Connect & Play**
2. Enter all 3 player names + starting balance → tap **Start Game**
3. Done! Share the URL with your brothers

---

## Step 4 — Install on phones

**Android (Chrome):** Open URL → ⋮ menu → "Add to Home Screen"

**iPhone (Safari):** Open URL in Safari → Share button → "Add to Home Screen"

---

## How to play

- Each person opens the app and taps their name under "I am:"
- Tap any odds button to place a bet (max ₹1,000/match)
- Each player can bet once per match
- Anyone can tap "Declare Winner" after a match ends
- All balances update instantly on all phones
