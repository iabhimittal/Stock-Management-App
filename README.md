# OM SAI TRADERS — Shop Management App

A complete, offline-first shop management web app for **OM SAI TRADERS** .  
Built as a single HTML file — no server, no database, no installation required.

## Features

- **Billing** — Create GST/non-GST bills with item autocomplete, discounts, and payment tracking (Cash / UPI / Credit)
- **Inventory** — Track stock levels, get low-stock alerts, adjust stock manually with + / − controls
- **Stock Movements** — Auto-deducts stock on sale, auto-adds on purchase; full audit log
- **Purchases** — Log supplier purchases and received items with optional payment recording
- **Customers** — Customer ledger with credit balance tracking and bill history
- **Reminders** — "To Collect", "To Pay", and "Connect" (re-engage inactive customers) categories
- **Sales Report** — Period filter (Today / 7 Days / This Month / Custom), payment breakdown, top products chart
- **Print Bills** — Opens a print-ready invoice in a new window

## How to Use

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
2. All data is saved automatically in the browser's `localStorage`
3. No internet connection required after the first load

## Hosting on GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set Source to `main` branch, root folder `/`
4. Your app will be live at `https://<your-username>.github.io/<repo-name>/`

## Data Backup

All data lives in your browser's localStorage. To back it up:
- Open the app → More → (future: Export feature)
- Or open DevTools → Application → Local Storage → copy the `ost_*` keys

## Tech Stack

- Vanilla HTML + CSS + JavaScript (zero dependencies, zero build step)
- localStorage for persistence
- Single file — everything inline

## License

Private — OM SAI TRADERS internal use.
