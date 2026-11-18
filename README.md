# Money Ledger — phone app

An installable web app (PWA). Once installed it opens full screen with its own icon and works offline.
Your data is stored on the phone itself; nothing is sent anywhere.

## Put it online free with GitHub Pages (about 5 minutes)

1. Sign in at github.com and create a new **public** repository, e.g. `money-ledger`.
2. On the repo page click **Add file → Upload files**, drag in every file from this folder
   (index.html, sw.js, manifest.webmanifest and the .png icons), then **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**,
   pick branch **main** and folder **/ (root)**, then **Save**.
4. After a minute your app is live at `https://YOUR-USERNAME.github.io/money-ledger/`.

The repo only holds the app's code. Your financial data never goes into it.

## Install on your phone

- **iPhone (Safari):** open the link → Share → **Add to Home Screen**.
- **Android (Chrome):** open the link → ⋮ menu → **Install app** (or *Add to Home screen*).

## Moving data between the phone app and the Claude page

Settings → **Copy full backup** on one, then Settings → **Restore from backup** on the other.
Back up now and then: clearing Safari/Chrome website data would also clear the app's data.
