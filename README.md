# RH Scoreboard

Personal tracking dashboard for the 10-year plan. Two tabs:

- **Weekly** — check off slow-carb days, in-bed-by-alarm nights, training in 15-min increments (Zone 1–3 ≥120 min incl. tennis · 2× Zone 4/5 · strength ≥120 min), the $455 brokerage + $92 HYSA transfers, and the Whoop sleep average. Scores the week against 7 targets. Sleep target auto-adjusts by phase (≥6:15 → ≥6:30 Nov 2026 → ≥6:45 Jul 2027). Also holds the one-time financial setup to-do list.
- **Quarterly** — account balances (computes personal + household net worth against the $4.3M/2028 → $10M/2039 milestones (flat growth during the 2029–2034 college squeeze is planned, not failure)), Squadra 10 results, bodyfat, Cooper test, fasting glucose, CEO-time %.

## Put it on GitHub (5 minutes)

1. Go to github.com → New repository → name it `scoreboard`, set it **Public**, create.
2. Add file → Upload files → drop `index.html` in → Commit.
3. Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
4. In ~1 minute your dashboard is live at `https://<your-username>.github.io/scoreboard/`.
5. **On your phone (this is the intended home):** open the URL in Safari → Share → **Add to Home Screen**. It installs as a standalone app — full screen, its own icon, no browser chrome. All tap targets are sized for thumbs; workouts log in 15-minute taps.

## Privacy

The page itself contains no personal data — it's an empty scoreboard, so a public repo is fine. Your entries are stored in your browser's localStorage on each device and are never uploaded. Two consequences:

- Phone and laptop each keep their own data. Pick one device as the system of record (phone, realistically).
- localStorage can be wiped by clearing browser data. **Export a JSON backup after every quarterly entry** (button at the bottom of the Quarterly tab) and drop it in this folder.
