# Randall Ford Portfolio — Publish Ready V1.3

This release hardens the stacked hero-card composition across narrow mobile, tablet, split-column desktop, and wide desktop layouts.

## Hero-card changes
- Added responsive protected text zones for both the blue and white cards.
- Blue-card headline is positioned independently of the overlapping white card.
- White-card headline and orange ribbon remain in normal layout flow with dedicated spacing.
- Container-based breakpoints respond to the artwork width rather than only the browser width.
- No horizontal overflow at tested widths.

## Tested viewport widths
320, 360, 390, 430, 480, 600, 700, 768, 900, 980, 1024, 1280, 1440, and 1600 pixels.

The layout was checked for:
- Blue headline overlapping the white card
- White headline overlapping the orange ribbon
- Card content clipping outside the artwork frame
- Horizontal page overflow

## Publishing
Replace the current root `index.html` to apply this fix. The remaining site pages are unchanged but included for a complete package.
