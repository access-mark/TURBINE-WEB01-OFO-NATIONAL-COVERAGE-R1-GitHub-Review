# TURBINE BusinessOS V4-R8-Z1 | Zoom Accessibility Review

Source: R8 review repository, commit `3ae31049b29f0f764b004fe464527b32e88747ac`.
This is a non-production, isolated review build. Do not overwrite the original R8 repository.

Changes to R8 behaviour:
- Keep the original floating Guide button on spacious desktop viewports.
- On effective widths of 1120 CSS pixels or less, or viewport heights of 650 CSS pixels or less, move that same Guide button into the header as an accessible compact action.
- When compact, open the Guide panel below the header with bounded height and internal scrolling; preserve keyboard/escape/focus behaviour.
- On very short/narrow screens, stack the homepage hero so the headline and CTA take precedence over the screenshot.
- Hide secondary announcement text on narrow screens, preserving the main tagline.
- Do not alter the logo source image, approved header top padding, product screenshot images or public SEO gate.

Deployment: Upload this ZIP's root contents (99 files) into a NEW GitHub repository called
`TURBINE-BusinessOS-V4-R8-Z1-Zoom-Accessibility-Review` and enable Pages from main/root.

`noindex, follow` is intentional. Forms and automated trial access are not production-ready.

This build is locally tested with equivalent CSS viewport sizes corresponding to 100%, 150% and 200% zoom. Native zoom and live-host visual acceptance remain pending.
