# sage-social-media

Public media host for **SAGE** (Instagram [@sageopti](https://instagram.com/sageopti)), the visibility division of PurelyLogic.

## Why this repo exists

Instagram's Content Publishing API does not accept a file upload. You give it a **public HTTPS URL** and Instagram's servers fetch the media themselves. This repo is that URL.

Every image or video posted to @sageopti by the automation is committed here first, then served from `raw.githubusercontent.com`:

```
https://raw.githubusercontent.com/Hadgimoto/sage-social-media/main/assets/2026/09/2026-09-16-example.jpg
```

## Layout

```
assets/YYYY/MM/YYYY-MM-DD-name.ext
```

## How files get here

They are pushed by `host-media.mjs` in the SAGE-SOCIAL toolkit, which commits the file and prints its public URL.

## Rules

- **Everything here is public and permanent.** Only finished, post-ready assets.
- No client data, no drafts, no internal screenshots, no credentials.
- Images: JPEG, 8 MB max, aspect ratio between 4:5 and 1.91:1.
- Video: MP4/MOV, H.264 + AAC, 300 MB max, 3 s to 15 min.

## Licence

All assets are © PurelyLogic LLC. Public hosting is a technical requirement of the Instagram API, not a grant of reuse rights.
