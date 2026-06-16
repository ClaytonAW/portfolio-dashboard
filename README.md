# Portfolio Dashboard

A personal investment tracker with live exchange rates, AI news, and retirement projections.

## Deploy to GitHub Pages (5 minutes)

1. Go to **github.com** and sign in (or create a free account)
2. Click **New repository** → name it `portfolio-dashboard` → set to **Public** → click **Create repository**
3. Click **uploading an existing file** on the next screen
4. Drag and drop `index.html` into the upload box → click **Commit changes**
5. Go to **Settings → Pages** → under "Branch" select `main` → click **Save**
6. After ~60 seconds, your app will be live at:
   `https://YOUR-USERNAME.github.io/portfolio-dashboard`

Bookmark that URL on your phone and PC. On iPhone/Android you can tap **Share → Add to Home Screen** to make it feel like a native app.

## First-time setup

When you open the app, it will ask for your Anthropic API key.
- Get one at: https://console.anthropic.com/account/keys
- Your key is stored only in **your browser's localStorage** — it never leaves your device except to call Anthropic's API directly
- You'll need to enter it separately on each device (phone and PC) the first time

## Features

- **Dashboard** — net worth in GBP/USD/IDR/EUR, goal progress, retirement projection
- **Portfolio** — add/edit/remove positions, allocation donut charts, live price lookup
- **Assets** — cash accounts (multi-currency), crypto, property
- **News** — AI-powered market and holdings-specific news feed
- **Projection** — compound growth chart with adjustable contribution and return rate
- **Settings** — update API key, export/import data as JSON, clear data

## Data storage

All portfolio data saves in your browser's localStorage — it persists across sessions on the same device. Use **Settings → Export JSON** to back up your data, and **Import JSON** to restore it or transfer between devices.

## Updating your API key

Go to **Settings** tab in the app → paste new key → click Update.
