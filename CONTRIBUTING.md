# Contributing to Site-Images

Thank you for contributing images to The Back Room forums! Please follow the guidelines below to keep the repository organized and consistent.

## Folder Guide

Place your image in the correct folder:

| Folder | What goes here |
|---|---|
| `avatars/` | Profile avatars (square images, recommended 128×128 px or larger) |
| `banners/` | Forum and section banners (recommended 1200×300 px) |
| `backgrounds/` | Full-page or section backgrounds (recommended 1920×1080 px or larger) |
| `icons/` | Small UI icons and logo marks (recommended 64×64 px, SVG preferred) |
| `emotes/` | Forum emoji and reaction images (recommended 32×32 px to 128×128 px) |
| `misc/` | Any image that doesn't fit the categories above |

## Naming Conventions

- Use **lowercase letters** only.
- Separate words with **hyphens** (`-`), not spaces or underscores.
- Be **descriptive** — the filename should reflect the content.
- Include a version suffix when replacing an existing image (e.g., `logo-v2.png`).

**Good examples:**
```
avatars/default-avatar.png
banners/general-discussion.jpg
icons/logo-small.svg
emotes/wave.gif
```

**Bad examples:**
```
avatars/Avatar 1.PNG      ← spaces and uppercase
banners/banner.jpg        ← not descriptive
icons/ICON_FINAL_v3.png   ← uppercase and underscores
```

## File Size Guidelines

| Category | Recommended max file size |
|---|---|
| Avatars | 256 KB |
| Banners | 1 MB |
| Backgrounds | 2 MB |
| Icons | 100 KB |
| Emotes | 256 KB |
| Misc | 2 MB |

Compress images before submitting. Tools such as [Squoosh](https://squoosh.app/) or [TinyPNG](https://tinypng.com/) are free and easy to use.

## Submission Process

1. **Fork** this repository.
2. Add your image(s) to the appropriate folder(s) following the guidelines above.
3. Open a **Pull Request** with a brief description of what you are adding and why.
4. A maintainer will review and merge your PR.

## Acceptable Formats

| Format | Extension | Notes |
|---|---|---|
| PNG | `.png` | Preferred for icons, emotes, and images requiring transparency |
| JPEG | `.jpg`, `.jpeg` | Preferred for photographs and large backgrounds |
| GIF | `.gif` | Accepted for animated emotes and avatars |
| WebP | `.webp` | Recommended for optimized file sizes across all categories |
| SVG | `.svg` | Accepted for `icons/` only |

Do **not** commit source/editing files such as `.psd`, `.ai`, `.xcf`, or `.afphoto`.

## Questions

Open an issue or ask in the forums if you are unsure where an image belongs.
