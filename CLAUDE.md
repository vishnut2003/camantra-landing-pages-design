# CLAUDE.md

This file provides guidance to Claude Code when working in this repository.

## Project Purpose

This is a **design presentation project** for the client **CA Mantra**. It contains landing page design mockups/prototypes that will be shown to the client for **approval only**.

**This is NOT a production project.** Nothing here will be deployed as the final product. Once the client approves a design direction, the approved design will be rebuilt properly in a separate production project.

## What This Means for Development

- **Prioritize visual polish and speed of iteration** over code quality, architecture, or maintainability.
- **Static HTML/CSS/JS is preferred** — no build tools, frameworks, or bundlers unless absolutely necessary. Each design should open directly in a browser (or via a simple local server).
- **Placeholder content is fine** — use realistic dummy text, stock-style imagery, and placeholder contact details where real client content is unavailable.
- **No backend, no forms that actually submit, no analytics, no SEO work** — forms and buttons only need to *look* functional.
- **Multiple design variants are expected.** Keep each design self-contained so variants can be compared side by side.

## Project Structure

Each landing page design lives in its own folder:

```
design-1/          # First design concept
  index.html
design-2/          # Second design concept
  index.html
...
index.html         # (optional) Gallery/index page linking to all designs for easy client review
```

- Keep each design **fully self-contained** (its own CSS/JS/assets inside its folder) so designs can be shared or deleted independently.
- CDN links (Google Fonts, icon libraries, Tailwind CDN) are acceptable since this is for preview only.

## Client Context

- **Client:** CA Mantra — a Chartered Accountancy (CA) services brand.
- **Audience for these pages:** the client reviewing designs, not end users.
- **Tone of designs:** professional, trustworthy, finance/accounting industry appropriate.

## Conventions

- Make every design **responsive** — the client may review on mobile.
- Name design folders descriptively when possible (e.g., `design-1-modern-dark`, `design-2-classic-blue`).
- If a designs gallery `index.html` exists at the root, add new designs to it.
- Do not spend time on tests, linting, CI, or deployment configuration.
