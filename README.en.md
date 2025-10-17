# Soonnetmall New Page

[中文](README.md) | English

Overview

- Static single‑page site built with plain HTML + CSS. No bundlers, frameworks, or backend required.
- Main files: `soonnetmall-information.html` (markup), `newpage-style.css` (styles), images under `photo/`.

Sections

- Navigation: brand logo, cart/login links.
- Hero: headline with tags and three search pills (AI face recognition, bib search, HD download) and CTAs.
- Ribbon (Highlights): three feature cards with an AI badge and tip bubble.
- Steps: three-step flow with illustration and CTA.
- Dark Gallery: 5 polaroid-style cards. Desktop shows a wide strip; mobile uses a responsive layout (3-2) and prevents overflow.
- Bottom CTAs: two marketing boxes (Photographer sign-up, Join member) with copy and images.
- FAQ: collapsible Q&A list.
- Footer: links and copyright.

Structure

- `soonnetmall-information.html` — main page (HTML)
- `newpage-style.css` — stylesheet (CSS)
- `photo/` — images and assets

Getting Started

- Open `soonnetmall-information.html` directly in your browser.
- Recommended: VS Code + Live Server for instant reload.

Editing Notes

- Brand colors and basics live in CSS `:root` variables.
- Responsive rules mainly under `@media (max-width: 960px)` and `@media (max-width: 600px)`.
- Replace images by dropping files into `photo/` and updating `src` and `alt` in HTML.
- SEO: update `<title>`, meta description and Open Graph tags in the HTML `<head>`.

Deploy (GitHub Pages)

1. Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main`, Folder: `/ (root)` → Save
4. Wait for Pages to publish

Browser Support

- Modern browsers (Chrome/Edge/Firefox/Safari latest). IE is not supported.

Preview

<div align="center">

<img src="photo/polaroids-1.jpg" alt="Preview 1" width="360" />
<img src="photo/polaroids-6.jpg" alt="Preview 2" width="360" />

</div>

