# Client Acquisition OS and Quote Generator

A single-page B2B dealer portal demo: matrix order entry with volume-tier pricing, internal approval flow, live order tracking, Net-30 ledger with downloadable invoices, and volume/rebate analytics.

- **No build step.** Everything is in `index.html` (React 18 + Tailwind + Babel from pinned CDNs, custom SVG charts).
- **Demo data only.** Dealers, SKUs, orders and invoices are mock data generated in the browser. Nothing is sent to a server. Drafts are stored in your browser's localStorage.
- **Assumptions to replace:** rebate rates (Silver 1%, Gold 2%, Platinum 5%), tier thresholds ($750k Gold, $1.5M Platinum), volume discount brackets (50+ units 8%, 200+ units 15%) and the SKU catalog.

## Run locally
Open `index.html` in a browser (needs internet for the CDN scripts).

## Deploy on GitHub Pages
1. Create a repository and push these files to `main`.
2. Settings > Pages > Source: Deploy from a branch > `main` / root.
3. Your site is live at `https://<username>.github.io/<repo>/`.

## Files
- `index.html`: the whole app (component `ClientAcquisitionOS`).
- `.nojekyll`: tells GitHub Pages to serve files as-is.
