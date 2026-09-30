# Email-safe brand assets

These PNGs are exported at **2× retina resolution** for crisp email rendering. Do **not** render them at their intrinsic pixel width.

Rendered widths in email HTML:

- DigiPixel: max 250 px (asset 500 px)
- PixlWrk: max 250 px (asset 500 px)
- Professional Structures: max 250 px (asset 500 px)
- My Simple Mortgage: max 250 px (asset 500 px)
- Matt Sidnell: max 220 px (asset 440 px)
- Matt Sidnell + My Simple Mortgage: max 250 px (asset 500 px)

Use an explicit `width` plus `height:auto`; use `*-light.png` on light backgrounds and `*-dark.png` on dark backgrounds.

Full-resolution masters remain under `/brands/`.


## Canonical email sizing

All email-specific PNG assets must be **250 px wide or smaller** intrinsically. Email HTML must also explicitly cap display width at 250 px or less and preserve aspect ratio.
