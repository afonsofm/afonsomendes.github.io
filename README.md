# Afonso Mendes — Portfolio

Single-page personal portfolio covering my background in Telecommunications & Informatics Engineering, professional experience, projects, awards, education and extracurricular activities.

**Live:**
- 🌐 [afonsomendes.vercel.app](https://afonsomendes.vercel.app)
- 🌐 [afonsofm.github.io/afonsomendes.github.io](https://afonsofm.github.io/afonsomendes.github.io/)

Both URLs serve the same site and are updated automatically on every push to `main`.

## Sections

- **About** — skills overview (programming, networks, telecom, tools, languages, soft skills)
- **Experience** — professional and internship history
- **Projects** — featured projects with images and tags
- **Awards & Distinctions** — honors and recognitions, with photo galleries
- **Education** — academic background
- **Activities & Volunteering** — extracurricular involvement
- **Contact** — ways to get in touch

## Features

- **Bilingual (EN / PT)** — language toggle, defaults to English, choice remembered across visits
- **Light / dark theme** — toggle with saved preference
- Fully responsive layout (desktop and mobile)
- Smooth-scroll navigation with active-section highlighting
- Fade-in animations on scroll
- Image lightbox for project and award galleries
- Automatic duration labels for date ranges (e.g. "Sep 2025 — Jan 2026 · 5 months")
- Optimized, lazy-loaded images (multiple sizes in `images/opt/`)
- SEO and social previews: Open Graph / Twitter tags, JSON-LD structured data, sitemap and robots.txt

## Tech Stack

Plain **HTML, CSS and vanilla JavaScript**: no frameworks, no build step. Fonts via Google Fonts (DM Serif Display, Plus Jakarta Sans).

## Project Structure

```
index.html                  # entire site (markup, styles, scripts)
images/                     # photos and screenshots, in per-project subfolders
images/opt/                 # resized/optimized versions used by the page
CV_AfonsoMendes_ENG.pdf     # downloadable CV
robots.txt, sitemap.xml     # SEO
```

## Running Locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server
```

Then visit `http://localhost:8000`.

## Deployment

The site is deployed to two hosts from the `main` branch. Neither needs a build step:

| Host | URL | How |
|------|-----|-----|
| **Vercel** | https://afonsomendes.vercel.app | Git integration (project `afonsomendes`), static preset |
| **GitHub Pages** | https://afonsofm.github.io/afonsomendes.github.io/ | Served directly from `main` |

All asset paths are relative, so the same files work at the root (Vercel) and under the `/afonsomendes.github.io/` subpath (GitHub Pages). Canonical and Open Graph URLs point to the GitHub Pages address.

## Contact

- Email: [afonsomendes.tech@gmail.com](mailto:afonsomendes.tech@gmail.com)
- LinkedIn: [afonso-figueira-mendes](https://linkedin.com/in/afonso-figueira-mendes)
