# Modern Toolkit for Excellence — Static Site

This repository hosts a small static website for the paper and media assets. It is designed to be published via GitHub Pages with no build step.

## Live Site
- Base URL: `https://esk000.github.io/Modern_Toolkit_for_Excellence/`
- Homepage: `https://esk000.github.io/Modern_Toolkit_for_Excellence/index.html`

## Contents
- `index.html` — Landing page linking to all assets
- `[Paper] Applying Reverse-Engineering and AI-Augmented Solutions for Modern Business Excellence.html`
- `[Paper] Applying Reverse-Engineering and AI-Augmented Solutions for Modern Business Excellence.pdf`
- `[Paper]Reverse Engineering and AI for Business Excellence.m4a`
- `Modern_Toolkit_for_Excellence.mp4`
- `.nojekyll` — Disables Jekyll processing so static files are served as-is

## Publish via GitHub Pages
You can deploy from either `gh-pages` or `main` (both contain only the site files).

1. Open `Settings → Pages` on GitHub.
2. Under “Build and deployment”, set:
   - Source: `Deploy from a branch`
   - Branch: `gh-pages` (recommended) or `main`
   - Folder: `/ (root)`
3. Save. Initial publish may take 1–3 minutes.

## Local Preview
- Run: `python3 -m http.server 8000`
- Open: `http://localhost:8000/index.html`

## Notes
- Filenames include spaces and brackets; use URL-encoded links when typing by hand.
- Large media uses `preload="none"` to avoid auto-fetch on page load.
- All files are under GitHub’s non-LFS 100 MB limit.

