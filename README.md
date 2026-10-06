# Subrat Padhi — Engineering Portfolio

A responsive engineering portfolio focused on embedded systems, IoT, software, databases, and hardware/software integration.

## Current structure

- `index.html` — current portfolio application
- `assets/images/` — profile and general images
- `assets/projects/` — project photos, diagrams, demos
- `assets/certificates/` — certificate images/PDFs
- `docs/` — project notes and future documentation

## Run locally

No build system is required for the current version.

1. Open `index.html` directly in a browser, or
2. Run a local server from this folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Before publishing

Replace the placeholder email, GitHub, and LinkedIn links in `index.html` with the real profiles. Add project media under `assets/` as it becomes available.

## Future architecture

The visual prototype is intentionally kept dependency-free for now. Once the content and visual direction are finalized, this can be migrated to a component-based React/Vite structure without changing the portfolio's information architecture.

## Publishing options

The folder can be placed in a GitHub repository and later deployed through GitHub Pages, Netlify, Vercel, or another static hosting provider.
