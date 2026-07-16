# Design QA

## Current review set

- Direction 1: Grove
- Direction 2: Daylight
- The rejected Founders and Evergreen directions are not included in the chooser.

## Source-of-truth audit

- Dylan's June 26 and July 10 email notes were read together and reconciled.
- The persistent requirement comparison is in `review-checklist.md`.
- Both directions retain the official logo, exact contact details, $1M–$10M EBITDA target, four sectors, Partnership principle, requested positioning language, and three operating focus areas.
- Dylan's personal name and Guides remain excluded.
- No team, portfolio, performance, or track-record claims were invented.

## Improvement audit

- Ten documented improvements were completed in Grove.
- Ten documented improvements were completed in Daylight.
- Grove remains the warmer, rooted, stewardship-led direction.
- Daylight remains the brighter, open, Miami-led direction.
- Both use semantic investment-profile markup, clearer investment-criteria hierarchy, optimized images, share metadata, reduced-motion support, and a linked physical address.

## Browser audit

- Desktop at 1280px: no horizontal overflow, failed images, or dead placeholder links in either direction.
- Mobile at 390px: both layouts collapse cleanly, profile and criteria cards reflow as intended, and neither direction has horizontal overflow.
- Both headers remain accessible while scrolling, and anchor offsets account for their height.
- Both pages contain exactly four `dt`/`dd` profile pairs.
- The Daylight EBITDA target stays on one line at desktop size.
- The chooser still exposes exactly the two intended review directions.

## Content checks

- The exact hero promise remains visually intact in both directions.
- Ownership-transition, value-added partner, and right-next-steward language is present in both.
- All requested sector, focus-area, partnership, stewardship, contact, and target-profile language is present in both.

## Live deployment audit

- GitHub Pages served the current versioned stylesheets for both directions.
- Both live pages loaded without failed images or horizontal overflow at desktop size.
- The live chooser contains exactly two cards: Grove and Daylight.

Final result: passed locally and on the live GitHub Pages preview.
