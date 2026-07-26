# FOUNDATION — Your First Design Laptop

An interactive field guide for young designers choosing their first laptop (India edition, 2026).
By **Tajinder J Singh**.

**Live site:** `https://<your-username>.github.io/<repo-name>/`

---

## Publish this as a website (GitHub Pages) — 5 minutes

### Option A — Upload in the browser (no tools needed)
1. Go to **github.com/new** and create a repository — e.g. `foundation-laptop-guide`. Set it **Public**. Don't add a README (this repo already has one). Click **Create repository**.
2. On the repo page, click **Add file → Upload files**.
3. Drag in **`index.html`**, this **`README.md`**, and the **`images/`** folder. Click **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**, **Branch: `main`**, folder **`/ (root)`**. Save.
5. Wait ~1 minute, then refresh — your live URL appears at the top of the Pages settings. Done.

### Option B — Command line (if you use git)
```bash
git init
git add .
git commit -m "FOUNDATION laptop guide — edition 01"
git branch -M main
git remote add origin https://github.com/<your-username>/foundation-laptop-guide.git
git push -u origin main
```
Then enable Pages: **Settings → Pages → Deploy from a branch → main → / (root)**.

---

## Expanding it later (it's built to grow)

- **Add real product photos:** drop images into `images/` using these names, and they appear automatically —
  `review-air-hero.jpg`, `thumb-air.jpg`, `thumb-zenbook.jpg`, `thumb-yoga.jpg`, `thumb-pro.jpg`,
  `thumb-aspire.jpg`, `thumb-air15.jpg`, `thumb-airm2.jpg`, `thumb-vivobook.jpg`.
- **Add more laptops:** open `index.html`, find the `var laptops = [ ... ]` list, and copy a block. Give it an
  `id`, `name`, `price`, `text`, `chips`, and `cats` (e.g. `['windows','oled','budget']`). It joins the filter
  and comparison automatically.
- **Add filter categories:** edit the `var filters = [ ... ]` list.
- **Change the author photo:** replace `images/author-portrait.jpg` (the page also has one embedded as a fallback).

## Files
- `index.html` — the whole site (self-contained; animations via anime.js + Motion One from CDN).
- `images/` — product photos and author portrait (add your own here).
- `FOUNDATION_First_Proof_2026.pdf` — the print/PDF edition (optional to include).

---
© 2026 Tajinder J Singh · A FOUNDATION publication · Prices indicative (₹), verify before buying.
