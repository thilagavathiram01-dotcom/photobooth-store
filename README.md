# Photobooth Store CDN

Static asset store for the Photobooth app, deployed on Cloudflare Pages.

## Deploy
Connect this repository to Cloudflare Pages:
- Build command: (none)
- Build output directory: `/`

Or deploy with Wrangler:
```
npx wrangler pages deploy .
```

## Endpoints
- `/frames.json`
- `/lenses.json`
- `/frames/<id>.png`
- `/lenses/thumbs/<thumbAsset>.png`
- `/assets/...`
