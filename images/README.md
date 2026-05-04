# 🖼️ Images for The Headline Salon site

This folder holds **24 placeholder images** that the live site already references. Just **drop your real photos in over the placeholders, keeping the same file names**, and everything will work — no code changes needed.

---

## How to use

1. Open any folder below.
2. Replace each `.jpg` placeholder with your real photo.
3. **Keep the same file name** (e.g. `polaroid-1.jpg`, `01-hair-extensions.jpg`).
4. Refresh the site — your photo appears.

> 💡 If your file is `.png` or `.webp`, you'll need to either:
> - convert it to `.jpg` and use the same name, **or**
> - update the file extension in `index.html` (search & replace).

---

## Folder structure & specs

### `hero/` — 4 polaroid photos (main hero stack)
**Format: 4:5 portrait · ~800 × 1000 px · ~85% JPG quality**

These are the photos that swipe inside the polaroid frames at the top of the page.

| File | What it should show |
|---|---|
| `polaroid-1.jpg` | Glassy blowout / signature look |
| `polaroid-2.jpg` | Color / balayage |
| `polaroid-3.jpg` | Hair extensions |
| `polaroid-4.jpg` | Bridal up-do |

### `services/` — 6 service photos (accordion images)
**Format: 16:9 horizontal · ~1200 × 675 px**

Shown when a guest taps a service to expand it.

| File | Service |
|---|---|
| `01-hair-extensions.jpg` | Hair Extensions / weaving |
| `02-color-correction.jpg` | Color & Correction |
| `03-brazilian-blowout.jpg` | Brazilian Blowout |
| `04-bridal-updo.jpg` | Up-do's & Bridal |
| `05-cut-style.jpg` | Cut & Style |
| `06-olaplex.jpg` | Olaplex Treatment |

### `about/` — 1 studio interior shot
**Format: 4:5 portrait · ~1000 × 1250 px**

| File | What it should show |
|---|---|
| `studio.jpg` | Inside of the studio — chairs, mirrors, atmosphere |

### `gallery/` — 5 gallery photos
**Format: 4:5 portrait · ~1000 × 1250 px**

The asymmetric grid in the "Recent work" section.

| File | Suggested content |
|---|---|
| `1.jpg` | Color / balayage |
| `2.jpg` | Extensions |
| `3.jpg` | Cut / layers |
| `4.jpg` | Bridal / up-do |
| `5.jpg` | Blowout / glassy |

### `before-after/` — 4 transformations × 2 photos = 8 files
**Format: 4:5 portrait · ~1000 × 1250 px**

⚠️ **Important:** The "before" and "after" of each pair must be **the same crop / framing** — otherwise the slider misaligns when you drag the handle.

| Pair | Before | After |
|---|---|---|
| 1 — Color | `1-color-before.jpg` | `1-color-after.jpg` |
| 2 — Blowout | `2-blowout-before.jpg` | `2-blowout-after.jpg` |
| 3 — Extensions | `3-extensions-before.jpg` | `3-extensions-after.jpg` |
| 4 — Bridal | `4-bridal-before.jpg` | `4-bridal-after.jpg` |

---

## Quick tips

- **JPG, not PNG** — JPG is ~5× smaller for photos. Use [squoosh.app](https://squoosh.app) for free in-browser compression.
- **Keep widths around 1000–1400 px** — anything bigger just slows the page down without looking better on retina screens.
- **Strip EXIF metadata** if your photos contain location / device info you don't want public — squoosh.app does this automatically.
- **The two photos in a before/after pair MUST be the same crop** — same camera angle, same zoom, same framing. Otherwise the slider warps.

---

If anything's unclear or you want to add / remove a slot, just message me — happy to adjust.
