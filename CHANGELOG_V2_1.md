# AFM-G 2.1 — Feedback fixes

- Research thumbnails use object-fit: contain; no decorative circles/squares over scientific images.
- Research detail images preserve their full frame and original aspect ratio.
- People portraits enlarged. Existing Le Dinh Anh profile integrated into People page, with old URL redirected.
- Publications have separate Journal and Conference sections; filters search both. International and domestic journals remain together in Journals.
- Original image/data assets retained.

Test locally: `python -m http.server 8000` then visit `http://localhost:8000`.
