# AFM Research Group — Website 2.0 (GitHub Pages)

A responsive static website for Applied Fluid Mechanics Research Group, School of Aerospace Engineering, UET – VNU.

## Preview locally

Python 3:

```bash
cd AFM-G-website-v2
python -m http.server 8000
```

Open http://localhost:8000/ (file:// directly will not load publications.json because fetch needs HTTP).

## Recommended deployment (safe)

1. Back up your original repository before doing anything (`git clone` or download ZIP).
2. Create a new branch `redesign-v2` from `main`.
3. Merge this site into the branch, **after** inspecting the original assets. Do not delete original images, PDFs or member profile pages.
4. Verify published links under `members/` and all references to legacy photos. Copy original media assets to the upgraded site and replace conceptual SVG illustrations with genuine group scientific visuals.
5. Use GitHub Pages branch preview or a separate test repository. Keep current site live until all contents/links are audited.
6. Open a pull request and merge only after verification.

The site has no build dependencies. GitHub Pages can serve the files as-is from the root folder.

## Content provenance and limitations

- Home research descriptions, collaborations, people, project titles, publications and activity titles have been transcribed from publicly visible AFM-G pages on 2026-10-24.
- The duplicate 2025 publication in the source was removed once in this V2 listing; confirm metadata before deployment.
- Source site lists Banh Duc Minh in multiple team categories; both references remain, explicitly flagged for review.
- Original activity photos and linked member profile pages could **not** be fetched from GitHub in this environment. They are **not included** in this package and must be copied from your original repository before replacing the live website.
- The abstract flow SVG and card illustrations are original conceptual placeholders, NOT AFM-G scientific results.
- DOI/ORCID/Google Scholar URLs are not fabricated; add only after verification.

## Contents

- `index.html`, `research.html`, `members.html`, `projects.html`, `publications.html`, `activities.html`, `contact.html`
- `data/publications.json`, `data/projects.json`, `data/activities.json`
- `assets/css/style.css`, `assets/js/site.js`, `assets/images/`

Content is English-first with source Vietnamese project titles maintained accurately.


## Original repository integration

This edition includes the original photography and research imagery from the owner-provided `AFM-G.github.io-main.zip`. The original personal profile URL `members/Le-Dinh-Anh.html` is preserved. See `SOURCE_AUDIT.md` for the detailed change log and manual review checklist.


### Confirm you are running 2.2
Extract into a NEW folder, open CMD within it and run `python -m http.server 8001`. Visit http://localhost:8001/index.html?v=2.2. Header must display `AFM-G · v2.2`. If not, you are looking at the old directory/server.
