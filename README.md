# Pantry Log

A weekly grocery and pantry tracker that runs as an iPhone home-screen app. Sister app to Gym Log and Expense Log.

## What it does

- **Weekly grocery list** by calendar week (KW), grouped by category or by store
- **Receipt scanning** from a PDF (Rewe eBon, Lidl Plus), a photo, or pasted text. It reads items, prices, quantities, discounts and Pfand, matches them to the list, and learns receipt abbreviations over time.
- **Pantry stock** (Stocked / Low / Out) with best-before dates and a "use soon" list
- **Every-week staples** and "probably due" suggestions based on past purchases
- **Meal planning** by day, with ingredients added to the list in one tap
- **Price history** per item and store, with the cheapest store highlighted
- **Budget, protein, Pfand and flatmate cost-splitting** in Stats
- **Shopping mode** with big checkboxes that keeps the screen on

## Privacy

Everything is stored in the browser's local storage on your device. Receipts are read on the device; nothing is uploaded anywhere. Use **Stats → Copy backup** to save your data, and paste it back in to restore.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Name, icon and full-screen mode for the home screen |
| `sw.js` | Offline support; caches the app and the receipt readers |
| `icons/` | Home-screen icons |

## Install on iPhone

1. Open the GitHub Pages link in Safari.
2. Tap **Share → Add to Home Screen**.
3. Do your first photo scan on Wi-Fi. It downloads the German text reader (about 10 MB) once and caches it.
