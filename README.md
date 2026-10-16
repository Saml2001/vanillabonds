# vanillabonds.com — v6

Single-page marketing site for VanillaBonds, a Munich startup, plus the
platform demo. Static HTML/CSS/JS, no build step, deployed via GitHub Pages.

- `index.html` — the site (one page; light theme)
- `platform.html` — the two-sided platform demo (company view: upload, answer, confirm as CFO; investor views: anchors see everything first, co-investors only deals whose anchors have committed). Built from `../seb-mvp/index.html` by `../seb-mvp/build_platform.py`; edit the source or the script, not this file
- `demo.html` — guided walkthrough (dark theme via `data-theme="demo"`; all data fictitious/illustrative)
- `issuers.html` / `investors.html` / `pricing.html` — redirect stubs for retired URLs
- `assets/css/tokens.css` — every colour/size/duration token (`--vb-*`); re-skin by editing this file only
- `assets/css/site.css` / `demo.css` — components per theme; no hardcoded values
- `assets/fonts/` — self-hosted Source Sans 3 (OFL) + IBM Plex Mono (OFL); no external requests
- `assets/video/` — hero (muted loop) + pitch video, encoded from local sources

Branch lineage: `main` = v1 archive · `v2`/`v3` = previous builds · `v6` = this build.
