# Project Structure and Naming

## Folder structure

```text
YYYY-MM-DD_project-slug/
├── 01_ADMIN/          brief, schedule, releases, feedback, manifest
├── 02_MEDIA/          originals (read-only), proxies, selects
├── 03_AUDIO/          production audio, music, SFX, mix
├── 04_PROJECT_FILES/  editor, color, motion, autosaves
├── 05_GFX/            logos, images, source graphics, fonts licenses
├── 06_EXPORTS/        review, master, platform versions
├── 07_REVIEW/         notes, approvals, references
└── 08_ARCHIVE/        final package and project snapshot
```

## Naming convention

Use `PROJECT_YYYYMMDD_DESCRIPTION_v01.ext`. Example: `ACME_20260830_IG-Reel-9x16_v03.mp4`. Increment the two-digit version for every exported review or delivery; use `MASTER` only after approval, e.g. `ACME_20260830_MASTER_16x9_v01.mov`.

Avoid spaces, ambiguous names, and `final-final`. Use lowercase project slugs in folders; keep filenames short enough to survive different systems. Every exported version must be listed in the delivery manifest.
