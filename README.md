# Sreehari Rajan | Personal Website

This repository contains the published static portfolio website for Sreehari Rajan, a Cloud and Microservices Engineer focused on Java, Spring Boot, and agentic AI developer tooling.

The site highlights:

- microservices and cloud architecture work
- case studies and engineering impact
- technical leadership and platform thinking
- links to resume, LinkedIn, GitHub, and YouTube
- responsive dark-mode portfolio design

## Live site

- https://sreehariraajan.in

## Project structure

- `index.html` — main portfolio page
- `404.html` — custom not-found page
- `Sreehari-Rajan-Resume.pdf` — downloadable resume
- `images/` — marketing and image assets
- `_astro/` — generated CSS and frontend assets
- `robots.txt`, `sitemap-*.xml`, `site.webmanifest` — SEO and PWA metadata

## Local preview

Because this is a static site, you can preview it locally with any basic web server.

### Option 1: Python

```bash
cd "c:\Users\Sreehari Rajan\OneDrive\Documents\Personal website"
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

### Option 2: Node.js

```bash
npx serve .
```

## Editing content

Most of the portfolio copy and layout live in `index.html`. If you want to update:

- headline and bio
- project case studies
- CTAs and contact links
- resume file path or metadata
- SEO tags and social share data

then edit the relevant sections in `index.html` and replace static assets where necessary.

## Deployment

This repository is intended for static hosting. Upload the project files to your hosting provider or CDN and ensure the following files remain at the root:

- `index.html`
- `404.html`
- `Sreehari-Rajan-Resume.pdf`
- `robots.txt`
- `site.webmanifest`
- `sitemap-0.xml`
- `sitemap-index.xml`

## Contact

- LinkedIn: https://www.linkedin.com/in/sreehariraajan/
- GitHub: https://github.com/sreehariraajan
- YouTube: https://www.youtube.com/@sreehariraajan
- Email: sreeharirajan@gmail.com

## Notes

This site is a polished personal portfolio and is best treated as a static marketing site rather than a full application build. If you are making content changes, keep the design responsive and preserve the existing metadata for SEO and social previews.
