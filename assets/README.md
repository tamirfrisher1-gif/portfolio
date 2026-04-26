# assets/

Brand assets for the site.

## Files

- `headshot.jpg` — hero portrait (LinkedIn photo). Used in the hero portrait of `index.html` and `portable-profile.html`, and as the og:image / twitter:image.
- `headshot.svg` — fallback monogram (TF in gold on navy). Not currently used; kept as a backup.
- `favicon.svg` — small "T" favicon used in the browser tab.

## Swapping the headshot

To replace the photo:

1. Save your new image as `assets/headshot.jpg` (square crop, ~600×600 minimum, centered on the face).
2. Hard-refresh the site (Ctrl + F5) to bypass the browser cache. The HTML already points at this file, so no markup changes are needed.
