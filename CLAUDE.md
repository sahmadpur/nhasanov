# CLAUDE.md — Novruz Hasanov Portfolio

## Project Overview
Personal portfolio website for Novruz H. Hasanov, built as a single-page Bootstrap 5 site.
Inspired by the [Start Bootstrap "Personal" theme](https://startbootstrap.com/previews/personal).

## Repository
- GitHub: https://github.com/sahmadpur/nhasanov.git
- Live site: (to be configured via GitHub Pages)

## Stack
- **HTML5** — single `index.html` file (one-page layout)
- **Bootstrap 5** — via CDN, responsive grid and components
- **Font Awesome 6** — icons via CDN
- **Google Fonts** — Inter / DM Sans
- **Vanilla CSS** — custom styles in `<style>` block or `css/style.css`

## Site Structure (One-Page Sections)
| Section | ID | Notes |
|---|---|---|
| Hero | `#home` | Photo, tagline, CTA buttons |
| About | `#about` | Bio, social links |
| Experience | `#experience` | Timeline of work history |
| Education | `#education` | Degrees |
| Skills | `#skills` | Technical & language skills |
| Contact | `#contact` | Email, phone, LinkedIn |

## Candidate Info
- **Name:** Novruz H. Hasanov
- **Location:** Baku, Azerbaijan
- **Email:** nhasanov2016@ada.edu.az
- **Phone:** (+99450) 2310856
- **LinkedIn:** linkedin.com/in/novruzhasanov
- **Current Role:** Ecosystem Analytics / Senior Data Analyst @ Pasha Holding LLC (Apr 2025–Present)

## Design Tokens
- Primary gradient: `#4f46e5` → `#a855f7` (blue-purple, matching template)
- Accent: `#6366f1`
- Text dark: `#1e1b4b`
- Section bg alternating: `#ffffff` / `#f8f7ff`
- Font: Inter (Google Fonts)

## Guidelines
- Keep all content in a **single `index.html`** — no separate pages
- Nav links use smooth scroll (`scroll-behavior: smooth`)
- Responsive: mobile-first using Bootstrap breakpoints
- Do not add jQuery — Bootstrap 5 JS bundle is sufficient
- Placeholder photo: use a professional avatar SVG until a real photo is provided

## Updating Content
All candidate content is in `index.html`. Search for section comments like `<!-- HERO -->`, `<!-- EXPERIENCE -->`, etc. to locate and update content quickly.
