# TURBINE BusinessOS WEB-01 V4-R8 — Fluid Viewport Review

## Purpose
A controlled responsive repair based on V4-R7. Preserve the authorised V4 visual identity, logo files and header breathing room, narrative, 72 HTML pages, occupation directory and preview restrictions.

## Fluid layout rules
- Page gutters, section vertical rhythm, text and card spacing use bounded CSS `clamp()` tokens.
- Content gains width up to a controlled 1700px maximum on ultrawide screens; paragraphs retain readable line lengths.
- Components reflow into fewer columns at meaningful breakpoints instead of shrinking legibility.
- Phone and landscape layouts preserve buttons, navigation, images and fixed guide accessibility.
- Ultra-narrow 280-319px windows have an explicit headline/CTA fallback.
- Original PNG assets are not altered or cropped; 8px approved top-header spacing is retained.
- `noindex` remains enabled and forms stay preview-only.

## Non-negotiable release gates
Live 200% native browser zoom, device/browser matrix, real enquiry delivery, final production domain/canonicals and product-claim qualification remain separate approval gates. Offline simulated reflow/zoom is not proof of live-device acceptance.
