# Priyanshi Enterprises — Website

A single-page, mobile-responsive website for **Priyanshi Enterprises**, an RO water purifier sales, repair & service business based in Kabra Nagar, Nanded, Maharashtra.

**Live site:** https://purwa-g.github.io/Priyanshi-enterprises/

## About

Priyanshi Enterprises has been selling, installing and servicing RO/UV/UF water purifiers in Nanded for 10+ years, rated 5.0★ on JustDial. This site was built to give the business a simple, fast-loading online presence that customers can call, WhatsApp, or visit directly from.

## Features

- Single-page layout — hero, services, 8-stage purification explainer, product range with pricing, installation gallery, shop photos, and a contact section with an embedded map
- Fully responsive (mobile, tablet, desktop) with a sticky call/WhatsApp bar on mobile
- One-tap Call and WhatsApp buttons throughout
- Scroll-reveal animations and a purity-themed progress indicator (desktop)
- No build step or framework — plain HTML, CSS and vanilla JavaScript

## Tech Stack

- HTML5 / CSS3 (custom properties, CSS Grid & Flexbox)
- Vanilla JavaScript (IntersectionObserver for scroll reveals)
- Google Fonts (Manrope, Inter)
- Google Maps embed (no API key required)

## Project Structure

```
├── index.html          # entire site — markup, styles, and scripts
├── shop-*.jpg           # shop storefront & interior photos
├── product-*.jpg         # product studio photos
├── install-*.jpg         # installation photos
└── README.md
```

All images are referenced directly by filename in `index.html` and must stay in the same folder as `index.html` for them to load correctly.

## Deployment

Currently deployed via **GitHub Pages**:

1. Push changes to the `main` branch
2. GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root) auto-publishes within ~1 minute
3. Live at: https://purwa-g.github.io/Priyanshi-enterprises/

## Updating Content

- **Phone/WhatsApp number:** search for `9112878899` in `index.html` and replace all instances (`tel:` and `wa.me` links)
- **Prices:** search for `p-price` in `index.html` — each product card has its price next to this class
- **Address/hours:** found in the Contact section near the bottom of `index.html`
- **Photos:** replace the relevant `.jpg` file (keep the same filename) or add a new image and reference it in the HTML

## Contact

**Priyanshi Enterprises**
Matoshree Complex, Near Morya Tower, Kabra Nagar Ring Road, Nanded – 431602, Maharashtra
📞 +91 91128 78899
