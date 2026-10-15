# Website verification — October 15, 2026

Repository: eaglevisiondigital/straightedge2 only.
Source: straightedge2-website-build-verified (1).zip.

## Verified
- All 12 approved asset SHA-256 hashes match ASSET_MANIFEST.json; both reference PNGs are preserved unchanged.
- Netlify Git deployment linked to straightedge2 main, publish directory `.`, no build command. Forms detection enabled.
- Hosted preview: https://deploy-preview-1--straightedge-property-services.netlify.app/
- Chromium tested at 1440, 1024, 768, 390, and 320 CSS pixels. No horizontal overflow, broken anchor targets, or unloaded inline images at any width.
- Hero and property-care background photographs visually loaded.
- Mobile menu opens, closes after navigation, and updates aria-expanded. Service card selects the matching estimate service.
- No browser console warnings or errors observed on the tested preview.
- Synthetic estimate submitted on the production Netlify site; redirected to /thank-you. Netlify verified-submissions UI displays every submitted field and marker SE2-20261015-1405. Submission count increased from 0 to 1. No real customer information used.
- Corrected tablet hero overflow, estimate success URL, and desktop hero proportions/service gutters.

## Visual comparison limits
Compared against reference/approved-homepage.png. Preserved the supplied black/red/white design, hero, eight-card service grid, care panel, benefits row, footer, and package section order. The package itself differs from the raster mockup in photograph framing/content detail, Unicode icons, font/script rendering, and the additional work teaser and estimate form before the footer. These source-package differences remain; this is not a pixel-identical reproduction. Approved photography/logo files were not modified to force a match.

## Scope of verification
Screenshots for all five widths and synthetic form capture are saved locally in qa/. Email-notification delivery was not tested. Browser verification covers Chromium only. Production recheck follows merge of the preview branch.
