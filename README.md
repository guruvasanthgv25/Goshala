# Lokah Samasta Sukhino Bhavantu Goshala — Website

Padhur Village, Kallakurichi District, Tamil Nadu.

## Publish free on GitHub Pages
1. Sign in at github.com → **New repository** → name it e.g. `goshala` → Public → Create.
2. Click **uploading an existing file** and drag in everything from this folder:
   `index.html`, `README.md`, the photos and qrcode.js (all files sit at the top level, no folders).
   Do not upload the original `.heic` photos. Then click **Commit changes**.
3. Go to **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
4. After 1–2 minutes the site is live at `https://<your-username>.github.io/goshala/`.

## Easy edits (all in index.html)
- **Prices**: search for `var FEED` near the bottom. Change the monthly amount `m:` and the table recalculates by itself.
  If you change prices, also update the Daily / Monthly / Yearly plan amounts and the "Total" row.
- **UPI ID**: search for `sakthikumark4151-1@okicici` (it appears in a few places).
- **Receipt WhatsApp number**: `var WA = "919443376536"`.
- **Photos**: replace the .jpg files and keep the same names (gallery-01.jpg … gallery-12.jpg, parents.jpg, hero.jpg).

`qrcode.js` is the MIT-licensed qrcode-generator library by Kazuhiko Arase. It draws the UPI QR codes.
