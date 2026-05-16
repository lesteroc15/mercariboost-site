# MercariBoost — Marketing Site

Static HTML for the MercariBoost docs site. Hosts the privacy policy and terms of service required by the Chrome Web Store listing.

Live: <https://lesteroc15.github.io/mercariboost-site/>

## Files

- `index.html` — landing page
- `privacy.html` — privacy policy (mirrors `docs/PRIVACY.md` in the extension repo)
- `terms.html` — terms of service (mirrors `docs/TERMS.md` in the extension repo)
- `styles.css` — shared styling

## Updating

Source of truth for the policy text lives in the extension repo at `docs/PRIVACY.md` and `docs/TERMS.md`. When those change, re-mirror the body content into the HTML files here. Keep the meta dates in sync.

## Deployment

GitHub Pages serves this repo on every push to `main`. No build step.
