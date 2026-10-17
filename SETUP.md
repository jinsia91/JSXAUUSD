# GoldDesk on GitHub Pages

Put GoldDesk online once, then open it on your phone, iPad or any computer, and add it to the home screen like an app.

## 1. Upload to GitHub (about 5 minutes, on your PC)

1. Sign in at github.com (create a free account if you don't have one).
2. Click **+** (top right) → **New repository**.
   - Repository name: `golddesk`
   - Choose **Public** (free GitHub Pages needs a public repository; your account number and balance are not in these files).
   - Click **Create repository**.
3. On the new repository page, click **uploading an existing file**.
4. Unzip `golddesk-app.zip` and drag **all the files inside it** (index.html, manifest.webmanifest, sw.js and the four .png icons) into the page. Leave out SETUP.md if you like.
5. Click **Commit changes**.
6. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main** and folder **/ (root)**, then **Save**.
7. Wait 1–2 minutes and refresh. The page shows your link, for example:
   `https://YOUR-GITHUB-NAME.github.io/golddesk/`

## 2. Install it as an app

**iPhone / iPad (Safari)**
1. Open the link in **Safari**.
2. Tap the **Share** button → **Add to Home Screen** → **Add**.
3. Open GoldDesk from the home screen. It runs full screen like an app.

**Android (Chrome)**
1. Open the link in **Chrome**.
2. Tap **⋮** → **Add to Home screen** (or **Install app**) → **Install**.

**PC (Chrome or Edge)**
- Open the link and click the install icon in the address bar, or keep using the page normally.

## 3. Your MT5 account

- **On phone and iPad:** trade and check balance, P/L, lots and open trades in the **MetaTrader 5 app**. GoldDesk on the phone shows charts, high-impact news, the gold call and the lot calculator.
- **On your PC:** open the GoldDesk link in Chrome or Edge, attach `GoldDesk_Exporter` in MT5 desktop and click **Connect MT5 file** as before. The account panel, the MT5 calendar countdown and the 5-minute playbook then run with your live CPT Markets data.

## 4. Updating later

When I send you a new version, open your `golddesk` repository on GitHub → **Add file → Upload files** → drag in the new `index.html` → **Commit changes**. Phones pick up the new version the next time the app is opened with internet.
