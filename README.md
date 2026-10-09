# StockGrid

<p align="center">
  <img src="favicon-192x192.png" alt="StockGrid logo" width="96" height="96" />
</p>

<p align="center">
  <strong>Inventory, visual catalog and stock ledger for garment manufacturers, wholesalers and retailers.</strong><br/>
  <a href="https://stockgrid.co.in">stockgrid.co.in</a> ·
  <a href="https://play.google.com/store/apps/details?id=com.stockgrid.android">Get it on Google Play</a>
</p>

This repository is the source of the **stockgrid.co.in** website. The StockGrid app itself is closed source.

---

## About StockGrid

StockGrid is an Android app that runs a garment business's catalog and stock from the phone, shared by the owner and staff. Every firm's data is kept separate on the server, and every stock movement is recorded in a ledger that is corrected, never erased.

### Features

- **Visual catalog** - every design with photos per colour, size-wise prices and categories; share catalogs and size availability with buyers on WhatsApp.
- **Size and colour stock** - track stock per size and colour for each design, with low-stock alerts.
- **Stock ledger** - every purchase, sale, return and adjustment is recorded with who, when and why; mistakes are corrected with a new entry, never by deleting history.
- **Fast photoshoot entry** - add a whole new collection at once: split the shoot into designs, then tag and price them in bulk.
- **Barcodes and labels** - scan barcodes and QR codes with the phone camera (including batch scanning) and print labels.
- **Reports** - sales performance, staff activity, stock insights (low stock, out of stock, slow and fast movers) and stock valuation, with CSV export.
- **Staff and security** - staff accounts with PINs, a device registry with remote removal, and a Master PIN that keeps prices and valuation owner-only.
- **Encrypted backup** - optional Google Drive backup, encrypted on the phone before upload.
- **Your data, your call** - download your data, or delete your firm from inside the app (7-day cooling-off).

Free 14-day trial, then a subscription through Google Play.

---

## Website pages

| Page | URL |
| :--- | :--- |
| Home | [stockgrid.co.in](https://stockgrid.co.in) |
| Download | [stockgrid.co.in/download](https://stockgrid.co.in/download/) |
| Privacy Policy | [stockgrid.co.in/privacy](https://stockgrid.co.in/privacy/) |
| Terms of Service | [stockgrid.co.in/terms](https://stockgrid.co.in/terms/) |
| Delete your account | [stockgrid.co.in/delete-account](https://stockgrid.co.in/delete-account/) |
| Email confirmed (app sign-up link) | `confirmed.html` |
| Reset password (app reset link) | `reset-password.html` |

`confirmed.html` and `reset-password.html` are opened from the app's sign-up and password-reset emails - don't rename or move them. Each `privacy/`, `terms/` and `delete-account/` folder holds a copy of the matching `.html` page so both URL styles work; edit both.

Hosted on GitHub Pages with the custom domain in `CNAME`. Preview locally with `python -m http.server 8088` and open http://localhost:8088.

---

## Proprietary software

StockGrid is closed-source commercial software. All rights reserved. This repository contains only the public website - no app source code.

© 2026 StockGrid (SRC93 Tech) · Contact: src93.appsupport@gmail.com
