# Serge Tun — Personal Website

A personal portfolio website for [Serge Tun](https://github.com/sergetun), built with pure HTML and CSS. Dark theme, full-viewport pages, smooth scroll snapping, and serif typography.

![HTML](https://img.shields.io/badge/HTML-5-E34F26) ![CSS](https://img.shields.io/badge/CSS-3-1572B6) ![No JS Framework](https://img.shields.io/badge/JS_Framework-None-lightgrey)

---

## Sections

| Section | Description |
|---------|-------------|
| **Home** | Full-screen quote display — rotatable inspirational quotes |
| **Work** | Professional experience and skills |
| **Photos** | Photography showcase |
| **About** | Bio — designer from Montréal, studied in DC, currently at KU Leuven in Belgium |

---

## Features

- **Full-viewport sections** — each page fills exactly one screen height (`100dvh` minus nav)
- **Scroll snap** — CSS `scroll-snap-type: both mandatory` for page-by-page navigation
- **Sticky navbar** — stays fixed at the top during scroll
- **Smooth scrolling** — `scroll-behavior: smooth` on anchor links
- **Dark theme** — black background with white text and blue-tinted borders
- **GFS Didot** — serif typeface loaded from Google Fonts
- **Zero dependencies** — no build tools, no JavaScript frameworks, no npm

---

## Project Structure

```
serge-tun-website/
├── src/
│   ├── index.html       # Page structure — nav, quote, work, photos, about
│   ├── styles.css       # Layout, nav, scroll snap, typography, page sizing
│   └── constants.css    # CSS custom properties (dark theme colors)
└── serv.sh              # Dev server — Python HTTP on port 8080
```

---

## Getting Started

```bash
./serv.sh
# → http://localhost:8080
```

Or manually:

```bash
cd src
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080) in your browser.

---

## Built By

| Name | GitHub |
|------|--------|
| Serge Tun | [@sergetun](https://github.com/sergetun) |
| Sivabalan Muthurajan | [@sivabalansm](https://github.com/sivabalansm) |
