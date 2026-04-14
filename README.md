# PredictX — Deploy to Vercel

## Your folder should look like this:
```
predictx/
├── index.html      ← paste game code inside this
├── vercel.json     ← already done
├── manifest.json   ← already done
├── sw.js           ← already done
```

---

## STEP 1 — Fill in index.html

Open index.html. Find this comment:
  <!-- PASTE YOUR FULL GAME HTML HERE -->

Replace it with everything between <style> and </script>
from the last game widget Claude built for you.

---

## STEP 2 — Create a GitHub repo (free)

1. Go to https://github.com/new
2. Name it: predictx
3. Set to Public
4. Click "Create repository"
5. Upload all 4 files by dragging them in

---

## STEP 3 — Deploy on Vercel (free)

1. Go to https://vercel.com
2. Sign up with your GitHub account
3. Click "Add New Project"
4. Select your predictx repo
5. Click Deploy — no settings to change
6. Done. Vercel gives you a URL like:
   https://predictx.vercel.app

Takes about 60 seconds.

---

## STEP 4 — Custom domain (optional, ~$10/year)

In Vercel dashboard:
Settings → Domains → Add your domain
e.g. predictx.io or getpredictx.com

---

## STEP 5 — Share it

Send this link to people:
- Telegram crypto groups
- X (Twitter)
- WhatsApp
- Reddit crypto communities

---

## PWA UPGRADE (later — adds "Install App" button on mobile)

When you're ready to make it installable as an app:

1. Create icon-192.png and icon-512.png
   (your logo, square, transparent background)
2. Put them in the predictx/ folder
3. Upload to GitHub
4. Vercel auto-deploys

Users on iPhone: tap Share → Add to Home Screen
Users on Android: browser shows "Install App" banner automatically

---

## WHAT'S LIVE vs WHAT'S MOCK

LIVE (works right now):
✅ Full game engine
✅ Candlestick chart
✅ Round system (synthetic price)
✅ Leaderboard
✅ Mobile optimised
✅ Streaks + social feed

MOCK (needs backend later):
⏳ Balance resets on page refresh
⏳ Leaderboard resets on page refresh
⏳ No real money deposits
⏳ No cross-device sessions

All of the above get fixed when we wire the Next.js backend.
Do that AFTER you have real users playing.
