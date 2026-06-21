# Freya Studio Cafe & Bakery — website mockup

A cozy one-page site built as a **free mockup** to send to the owner (Freida Rivera).
Single file: `index.html` (HTML + Tailwind via CDN — no build needed; just open in a browser).
Bakery-focused: warm elegant theme (cream / blush-rose / caramel), Fraunces + Poppins, with a
**Cake Pre-Order** section and a **Private Events** section as the standout features.

## ✅ What's already wired (from research — please confirm)
- Name: **Freya Studio Cafe & Bakery**, owner **Freida Rivera**, Lipa City
- Phone / WhatsApp: **+63 923 088 3180** (the cake form opens a pre-filled WhatsApp message)
- Facebook: facebook.com/FreyaStudioCafe · Instagram: @freyastudiocafe
- Google Map points at **Marauoy, Lipa City**

## 🔧 Swap these once Freida shares assets
- **Photos** — every image is **Unsplash stock** (clearly not hers). Replace the
  `src="https://images.unsplash.com/..."` links (hero, about, menu items, gallery, events) with her
  real photos. Best source: her Instagram (@freyastudiocafe). Drop files in `images/` and point to them.
- **Menu** — the 6 items + ₱ prices are **samples**. Replace with her real cakes/pastries/drinks + prices.
- **Exact address** — currently "Marauoy, Lipa City (confirm exact address)". Update text + the map `q=` query.
- **Hours** — currently "10:00 AM – 9:00 PM (confirm)".
- **est. year** — set to 2024 in the About stamp; change if different.
- **Cake order routing** — the form opens **WhatsApp**. If she prefers Messenger, swap the
  `https://wa.me/639230883180?text=...` line in the script for an `m.me/FreyaStudioCafe` link.
- **Logo** — currently a text logo "Freya Studio" + an "F" mark. Swap for her real logo if she has one
  (drop `images/logo.png` and replace the `<span>F</span>` blocks).

## What's intentionally generic (safe placeholders)
- Reviews/testimonials were left out (add real ones once she has them).
- Tagline lines in the hero typewriter — tweak to her brand voice.

## Deploy (free, no per-deploy cost)
Push to GitHub → import on **Vercel** → auto-deploys (e.g., `freya-studio.vercel.app`).
Footer credit "Website by Marco Belen" links to the portfolio — remove if the client prefers.
