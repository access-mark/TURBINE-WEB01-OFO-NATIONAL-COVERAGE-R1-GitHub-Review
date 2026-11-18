# WEB-01 V4-R7 | Narrative and Occupation Inclusion Review

Date: 17 November 2026  
Workstream: WEB-01 / public website  
Classification: Controlled development review candidate  
Approval: NOT production release accepted

## What changed

- Established heading -> explanatory copy -> practical evidence -> next action as the default narrative pattern across the site; retains the approved V4 design.
- Repositioned 42 action links below the five supporting cards.
- Removed the redundant homepage chooser paragraph and unnecessary sentence on Your Business.
- Corrected the active-section navigation behavior (forward and backward, including anchor offset).
- Highlighted TURBINE Guide and connected-customer-journey actions.
- Removed the redundant Trial Access self-link callout.
- Expanded the searchable occupation directory from **780 to 1,770 distinct titles** across **18 work areas**. This includes waitress/waiter, waiter alternatives, barista, frontline retail, care, trades, office, transport, education, science and other work.
- Improved search matching, alternative job names, common local spellings, typo suggestions and recovery from unfamiliar titles. Unknown titles link into a business-first journey and preserve the visitor's search words without claiming specialist product functions.
- Preserved all 29 original long-form curated occupation story pages. No SEO doorway pages were generated for the expanded entries.
- Preserved all ten original PNG assets byte-for-byte, including logo transparency and spacing.

## Qualification evidence

- 72 HTML pages assessed (including the 404 page).
- 1,008 in-memory Chromium layout cases across 7 viewports and light/dark themes; 0 detected overflow, clipped-content or broken-image cases.
- 37/37 functional checks passed, including the exact title **Waitress** and an unknown title with a non-dead-end recovery journey.
- No JavaScript page exceptions detected.
- No broken local links or anchors, duplicate HTML ids or missing principal metadata in the audited source.
- CSS: 0 `!important` declarations.
- Preview robots `noindex, follow`: **72/72** pages, intentionally retained.

## Taxonomy integrity and limits

The searchable titles are **a custom TURBINE catalogue**, informed by coverage standards such as South Africa's OFO 2021 and the ILO ISCO-08. The official OFO master spreadsheet was not imported or exhaustively reconciled in this environment. Do not represent this dataset as the official OFO taxonomy, as having every possible occupation, or as validating regulated workflows.

References:  
- South African MICT SETA OFO source: https://mict.org.za/what-we-do/sector-skills-planning/organising-framework-for-occupations/  
- ILO ISCO-08: https://isco.ilo.org/

## Outstanding production gates

1. Confirm permanent production domain and refresh canonical, structured data, sitemaps and OG/Twitter URLs for that domain.
2. Remove noindex only after founder authorisation for public indexing.
3. Connect and qualify approved enquiry delivery, analytics, consent and search performance monitoring.
4. Independently test public GitHub Pages rendering, native 200% browser zoom, physical mobile, screen readers, and performance.
5. Independently reconcile product claims with governed production technical qualification.
6. Reconcile custom occupation catalog against the authoritative OFO XLS and review a continuing alias-gap test plan; no list can be permanently exhaustive.

Do not overwrite the existing V4-R6 repository. For this test package, use GitHub repository `TURBINE-BusinessOS-V4-R7-Inclusive-Journey-Review` so preview URLs agree. All new work remains a review candidate until explicitly accepted.
