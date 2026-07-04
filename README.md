# FarmCore brand assets

Public logo assets for embedding anywhere a public image URL is needed (e.g. the
Cloudflare Access login page Logo URL field). Temporary identity, hand off to a brand
designer post-funding.

**Locked rules:** mark = solid "Holstein spot"; wordmark = Manrope, **Farm SemiBold (600) +
Core ExtraBold (800)**; colors **ink `#141414` / paper `#ffffff`**, black & white only.

## Use these (canonical, correct weights)
- `svg/` — scalable, preferred. Variants: `farmcore-lockup`, `farmcore-lockup-reverse`,
  `farmcore-wordmark`, `farmcore-wordmark-reverse`, `farmcore-mark`, `farmcore-mark-reverse`,
  `farmcore-appicon`.
- `png/` — transparent rasters at multiple sizes (e.g. `farmcore-lockup-256.png`,
  `farmcore-mark-512.png`, `farmcore-appicon-1024.png`).

`-reverse` = white, for dark backgrounds (`#101820` / `#141414`).

## CDN
`https://cdn.jsdelivr.net/gh/FarmCoreInc/brand-assets@main/svg/farmcore-lockup.svg`
(swap the path for any file under `svg/` or `png/`).

## Notes
- Root `farmcore-lockup.svg` / `farmcore-lockup.png` are the **padded** lockup wired into the
  Cloudflare Access login page (that card adds no clear space of its own). The `svg/`+`png/`
  set is tightly cropped per logo convention (add your own clear space ≈ the mark's width).
- Older `farmcore-logo.png` is kept only for the earlier login-page URL; prefer `svg/`.
