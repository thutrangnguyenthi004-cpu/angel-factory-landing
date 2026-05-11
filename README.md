# Angel Factory · Beauty Tax-Free Album

Long-form sales letter landing page for Angel Factory — 50 AI-rendered photos from 20 selfies, $99.

## Live

- Production: deployed via Netlify (see site URL in Netlify dashboard)
- Entry point: `index.html`

## Local preview

```bash
cd "$(dirname "$0")"
python3 -m http.server 8765
# open http://localhost:8765/
```

## Files

- `index.html` — main landing page (entry point)
- `Landing Page.html` — same content, alternate filename
- `summer.css` — landing page styles
- `styles.css` — shared styles
- `assets/` — images, videos, QR
- `Angel Factory - Beauty Tax-Free Album.html` — album view (alt template)
- `Angel Factory - Summer Album.html` — summer album view (alt template)
- `Landing Page v1.html`, `Landing Page v2.html` — earlier versions

## Deploy

Connected to Netlify via GitHub. Pushing to `main` auto-deploys.
