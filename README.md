# Solv-IT Computer Solutions

Business website for Solv-IT Computer Solutions, with service and contact pages.

## Cloudflare deployment

- The site assets are served from `dist/`, which mirrors the public HTML, CSS, JavaScript, and image files.
- The Cloudflare Worker in `src/index.js` handles `/api/contact` and serves static assets.
- Configure the `EMAIL` send-email binding in `wrangler.jsonc` before deploying.
