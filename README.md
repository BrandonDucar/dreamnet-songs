# DreamNet Songs

Song drops, metadata, receipts, and live pages for DreamStar, ZABAL Gamez, Droid OS, and related creator experiments.

## Current Drops

- `Better Call Zaal` - ZABAL builder anthem generated in Suno and staged as a public song page.

## Repo Pattern

Each song should include:

- `index.html` - public landing page
- `assets/*-cover.svg` or cover image
- `metadata.json` - machine-readable song metadata
- `lyrics.md` - lyrics or working lyric sheet
- `poidh-checklist.md` - ZABAL/POIDH submission helper when relevant
- `receipt.json` - proof and source links

Audio exports are intentionally ignored by default because finished masters can get large. Add them intentionally when ready for release.

## Deployment

This repo is a static site and can be deployed to Cloudflare Pages:

```bash
wrangler pages deploy . --project-name dreamnet-songs
```

