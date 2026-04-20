# JewelVault — Jewelry Inventory Management System

A complete, self-contained jewelry inventory website for your business.
No server required. Works on any web hosting or domain.

---

## Files included

```
jewelvault/
├── index.html              ← Dashboard (homepage)
├── css/
│   └── style.css           ← All styles
├── js/
│   ├── data.js             ← Data layer (localStorage)
│   └── app.js              ← Dashboard logic
└── pages/
    ├── inventory.html      ← Full inventory table
    ├── add-product.html    ← Add new product with media upload
    ├── catalogue.html      ← Visual product catalogue grid
    ├── pricing.html        ← Pricing manager & bulk updates
    ├── media.html          ← Image & video gallery
    └── reports.html        ← Analytics & CSV export
```

---

## How to deploy to your domain

### Option 1 — cPanel / File Manager (most common hosting)
1. Log in to your hosting cPanel
2. Open **File Manager**
3. Navigate to **public_html** folder
4. Upload the entire **jewelvault** folder by zipping it first
5. Extract it inside public_html
6. Visit: `https://yourdomain.com/jewelvault/`

### Option 2 — FTP (FileZilla, etc.)
1. Connect via FTP to your domain
2. Navigate to `public_html/` or `www/`
3. Upload the `jewelvault/` folder
4. Visit: `https://yourdomain.com/jewelvault/`

### Option 3 — Set as root site
1. Upload all files directly into `public_html/` (not in a subfolder)
2. Visit: `https://yourdomain.com/`

### Option 4 — Netlify / Vercel (free hosting)
1. Go to netlify.com → New site → Deploy manually
2. Drag and drop the `jewelvault/` folder
3. Get a free URL instantly (or connect your domain)

---

## Features

| Page | What it does |
|------|-------------|
| Dashboard | Stats, stock alerts, category chart, recent activity |
| Inventory | Full table, search, filter, sort, edit, delete, CSV export |
| Add Product | Complete form with image & video drag-and-drop upload |
| Catalogue | Beautiful card grid with product detail popup |
| Pricing | Individual & bulk price updates, margin tracking |
| Media | Gallery of all product images & videos with lightbox |
| Reports | Analytics, top products, alerts, full CSV export |

---

## Data storage

All data is stored in your browser's **localStorage**.
- Data persists across browser sessions on the same device
- To share data across devices/team, you would need a backend database
- Export CSV regularly as backup

---

## Customization

- Change company name: Search for "JewelVault" in all HTML files and replace
- Change colors: Edit `css/style.css` — look for `--gold`, `--dark`, etc.
- Add new categories: Search for the category list in each HTML file

---

## Browser support
Works in all modern browsers: Chrome, Firefox, Safari, Edge.
