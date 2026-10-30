# MONOLITH — Cinematic Villa Experience

A single-page architectural film experience featuring scroll-controlled video scrubbing and a real-time Three.js scene.

## Hosting
This repository is prepared for GitHub Pages with GitHub Actions.

One-time activation:
1. Open **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **GitHub Actions**.
3. The included workflow deploys on every push to `main`.

After the first successful run, the site URL is:
https://abuahmad2003sudan-del.github.io/Basira3-Pro/

## Media
The villa film is served from the account's hosted media URL, while the HTML, styling and interaction code are versioned in this repository.

## Notes
- Scroll progress is mapped to the HTML video element's `currentTime`.
- The 3D scene is rendered with Three.js.
- This is a static site; it does not need a Node server or database.
