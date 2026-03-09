# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static affiliate marketing site at **techwalkthroughs.com** — hand-written HTML/CSS with no framework, build system, or JavaScript. Deployed via GitHub Pages (CNAME configured). Focuses on software comparisons and reviews (marketing/CRM, cybersecurity, AI coding tools) monetized through recurring affiliate commissions.

## Development

There is no build step, package manager, or test suite. To preview locally:

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

Deployment happens automatically via GitHub Pages on push to `main`.

## Architecture

### Content Structure
- **Hub pages:** `/[category]/index.html` — category landing with comparison table linking to articles
- **Article pages:** `/[category]/[keyword-slug-2026]/index.html` — full comparison/review articles
- **Utility pages:** `/methodology/`, `/disclosure/`, `/about/`

Every HTML page follows: `<skip-link> → <header> → <nav> → <main> → <footer>`. Articles additionally have breadcrumbs, a methodology trust line, comparison tables, verdict boxes, and CTA buttons.

### Single Stylesheet
`/assets/styles.css` — CSS variables for theming (colors, spacing, typography with `clamp()`), mobile-first responsive design, BEM-ish class naming (`.comparison-table`, `.verdict-box`, `.article-ctas`, `.btn`, `.btn-secondary`).

### Affiliate Links
- **Placeholder format:** `https://[product-url]?ref=techwalkthroughs` with `rel="nofollow"`
- Search for `?ref=techwalkthroughs` to find all placeholder affiliate URLs needing replacement

### SEO
Every page has: unique `<title>`, `<meta description>`, Open Graph tags, `<link rel="canonical">`, single `<h1>`, proper heading hierarchy. Sitemap at `/sitemap.xml`.

## Continuity Workflow

When the user says **"continue"** or similar:
1. Read `PROGRESS.md` — use "Next up" as the task list
2. After completing work, update PROGRESS.md (move task to "Last completed", adjust "Next up")
3. If PROGRESS.md is empty, fall back to `ACTION_ITEMS.md` and `CONTENT_ROADMAP.md`

## Key Reference Files

| File | Purpose |
|------|---------|
| `PROGRESS.md` | Current task tracker (last completed / next up) |
| `ACTION_ITEMS.md` | Affiliate program signup checklist and URL replacement guide |
| `CONTENT_ROADMAP.md` | Phase 1/2/3 content plan, SEO strategy, content templates |
| `AUDIT.md` | Technical audit |
| `UI_AUDIT.md` | Design audit |

## Conventions

- **File paths** use lowercase kebab-case with year suffix: `best-crm-small-business-2026/`
- **New articles** should follow the existing comparison template structure (intro → evaluation criteria → top picks → comparison table → verdict box → CTAs → disclosure)
- **All affiliate CTAs** get `rel="nofollow"` and the placeholder `?ref=techwalkthroughs` param until real affiliate links are available
- **Accessibility:** maintain skip links, ARIA labels, focus states, and `prefers-reduced-motion` support
