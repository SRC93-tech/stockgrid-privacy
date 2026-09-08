# StockGrid Web Presence & Production Landing Pages

This directory contains the production web presence, legal compliance pages, and auth redirect pages for **StockGrid** (hosted on GitHub Pages and linked in app stores and Supabase Auth).

## 📂 Web Pages Catalog

| File | Purpose | Description |
| :--- | :--- | :--- |
| **[`index.html`](index.html)** | **Official Product Landing Page** | High-impact hero, animated 4-bar Grid Weave™ logo, interactive phone mockup (Summary, Valuation, Size Matrix), quick actions, live multi-device audit feed, and feature matrix. |
| **[`privacy.html`](privacy.html)** | **Privacy Policy** | Legally compliant policy covering Postgres RLS tenant isolation, camera permissions (barcode scanning only), secure local storage, zero data selling, and device revocation rights. |
| **[`terms.html`](terms.html)** | **Terms of Service** | Multi-device software license, master PIN administration, data ownership, and service availability terms. |
| **[`confirmed.html`](confirmed.html)** | **Email Verified Page** | Supabase Auth redirect landing page confirming successful email verification. |
| **[`reset-password.html`](reset-password.html)** | **Password Reset Page** | Supabase Auth password reset form with live access-token parsing and password update handler. |

---

## 🔗 Interlinking Map
- **`index.html`** links to `privacy.html`, `terms.html`, and downloads.
- **`privacy.html`** & **`terms.html`** link back to `index.html` and cross-link each other.
- **`confirmed.html`** & **`reset-password.html`** link back to `index.html`.

---

## 🚀 Local Preview Server
Run the local HTTP server anytime:
```bash
python -m http.server 8088
```
Then access: `http://localhost:8088/preview/index.html`
