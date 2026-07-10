# Design QA

- Source visual truth: `qa/springdale-reference.png` (the reference named by Dylan)
- User-rejected state: `qa/founders-before.png`
- Revised implementation: `qa/founders-after.png`
- Mobile implementation: `qa/founders-mobile-after.png`
- Side-by-side evidence: `qa/founders-comparison-v2.png`
- Viewports: 1440 × 1024 desktop and 390 × 844 mobile
- State: top of Option 2, default navigation state

## Findings

No actionable P0, P1, or P2 issues remain.

- Fonts and typography: Option 2 now uses a large, high-contrast editorial headline over real photography, preserving Eighteen Grove’s serif identity while adopting Springdale’s bold image-led hierarchy. Desktop and mobile wrapping are readable and unclipped.
- Spacing and layout rhythm: The previous oversized empty canvas was replaced with a full-bleed 720px hero, bottom-weighted content, immediate CTAs, and a compact qualification rail. The mobile hero and rail meet without a dead gap and produce no horizontal overflow.
- Colors and visual tokens: The white header, deep grove overlay, warm cream emphasis, and high-contrast actions retain Eighteen Grove’s palette while differentiating Option 2 from Grove and Evergreen.
- Image quality and asset fidelity: The existing Eighteen Grove oak-field photograph is used at full resolution with an intentional crop. The official horizontal green lockup remains in the header. No generated placeholders, handcrafted SVGs, or CSS-drawn assets were introduced.
- Copy and content: All three options now include every current site requirement from Dylan’s July 10 email: entrepreneurial private equity, the official logo, no personal name, `info@eighteengrove.com`, the Miami address, $1M–$10M target EBITDA, four investment sectors, Partnership as the foundational principle, all requested positioning phrases, and the three focus areas. Guides remain removed.

## Email gap audit

The earlier build was inconsistent on two requested commitments:

1. “We partner with exceptional operators to build enduring platforms.”
2. “We keep management and build value over time.”

Both are now explicit in Grove, Founders, and Evergreen. The verbose three-row Approach section was also replaced in every option with one concise partnership statement, reflecting Dylan’s “less is more” guidance and his note that the detailed Approach content was probably unnecessary.

## Interaction and browser checks

- Option 2 primary CTA scrolls to the contact section.
- Header links and criteria links resolve to valid in-page sections.
- All three pages load the correct official logo lockup and contain no broken images.
- Desktop and mobile layouts have no horizontal overflow.
- Browser console errors checked: none.

## Comparison history

1. Initial evidence confirmed the user’s P1 concern: Option 2 used an oversized empty white hero and a narrow photo strip, unlike the bold, full-bleed Springdale reference.
2. Option 2 was rebuilt as an image-led hero with content over photography, immediate conversion actions, and an integrated qualification rail.
3. First mobile capture found a P2 dead band below the hero because the grid remained taller than the image. The mobile grid height was aligned to the image height.
4. Post-fix captures show no remaining P0/P1/P2 issues.

## Follow-up polish

- P3: Replace the current oak-field image with final licensed Eighteen Grove photography if Dylan selects Option 2.

final result: passed
