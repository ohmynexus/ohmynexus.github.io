# RAW ABYSS — Sound Archive starter

Standalone page at `/raw-abyss/`; the current site root is unchanged.

## Configure catalog
1. Put audio assets you are authorized to distribute in `raw-abyss/assets/audio/`.
2. Register each song in `raw-abyss/index.html` under `TRACKS`:
```js
{ title:"Song title", artist:"Band", genre:"Metalcore", src:"assets/audio/song.mp3" },
```
Genres: `Hardcore`, `Metalcore`, `Deathcore`, or `Mixed`.
Keep file names/case exact. No audio is included yet; the catalog is intentionally empty.

## Public audio caution
Repository-hosted assets are public and downloadable. This player does not prevent extraction. Verify distribution rights and current GitHub repository file-size/usage policies before adding tracks. For bigger collections, consider dedicated object storage/CDN.

## Status
- Draft implementation added on `feature/raw-abyss-music-archive`
- Root page not replaced
- No audio uploaded
- No deployment/publication performed
- Review and approval required before merge/deploy
