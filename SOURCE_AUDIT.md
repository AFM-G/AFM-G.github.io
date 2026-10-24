# AFM-G source integration audit

Source: uploaded `AFM-G.github.io-main.zip` (original GitHub repository snapshot).

- Original `assets/images/` preserved including original research visuals, event photos, and portrait.
- Original `members/Le-Dinh-Anh.html` retained at the old URL.
- Existing core HTML URLs retained.
- Original event photo groupings mapped into expandable albums under News & Events.
- No new members, projects, awards, or publications invented during source integration.
- `lang.json` and `assets/js/lang.js` archived; original bilingual functionality should be independently reviewed before enabling.
- Site is ready for local preview but should be reviewed before replacing live GitHub Pages.

## Manual review checklist

1. Verify publication titles, dates, DOI links against sources.
2. Check labels/captions of scientific images: source file names do not establish a publication-level attribution.
3. Verify members statuses and duplicate role classifications.
4. Confirm responsive browser appearance and the relative paths of the preserved legacy profile.
- Legacy member profile uses preserved `assets/css/legacy-style.css` to maintain its original styling.
