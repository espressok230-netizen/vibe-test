# AGENTS.md

## Cursor Cloud specific instructions

This repo is a single self-contained static page: `index.html` (a Korean slide deck) with all CSS and JS inline. There is no build system, package manager, dependencies, tests, or lint config.

- Run (dev): serve the folder with any static server, e.g. `python3 -m http.server 8000` from the repo root, then open `http://localhost:8000/`. There is nothing to build.
- No install step is required (no dependencies).
- The deck is scroll-based (slides use `IntersectionObserver` for the active-slide indicator); navigate by scrolling.
