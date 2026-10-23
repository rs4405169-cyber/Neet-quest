# NEET QUEST — Android PWA

A dark, neon study RPG. The app runs in a browser and stores its data locally on your device.

## Quick test on a computer
Open `index.html` directly to test most features. Service-worker/offline/PWA installation features require a local web server or HTTPS hosting.

## Publish free with GitHub Pages (beginner steps)
1. Create/sign in to a GitHub account and create a **public** repository named `neet-quest`.
2. Upload every file and folder from this ZIP (keep the `icons` folder).
3. Open repository **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish. Open the provided `https://...github.io/neet-quest/` URL on your Android phone in Chrome.
6. Visit the page once while online. In Chrome, tap **⋮ → Add to Home screen** (or **Install app**, if shown). Confirm.

## How the game works
- Quest XP is awarded once per quest per active date. Physics/Chemistry/Biology trials unlock after 100 questions in that subject.
- MCQ counts reset when you create a new day; historical day records remain.
- Full Night Freedom costs 200 XP and unlocks after claiming Mock Test Boss Fight that day.
- A missed planned study day resets currently unspent XP to zero; redeemed rewards and their history remain.
- The day-close action is irreversible for that date. App confirmations are self-reported, not verified.
- Level progress uses total XP ever earned, while the spendable balance is unspent XP.

## Backups and privacy
Use **Daily Log → Export JSON backup** regularly. Import replaces current local data after confirmation. Clearing Chrome/site data can erase your saved data. Data is not automatically synced across devices. Keep backup files private.

## Notes
This project is a static PWA and does not have an online account or server. Browser storage is the source of truth. The app has not been published or installed for you; you must host it and add it to your home screen using the steps above.
