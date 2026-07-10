# Design QA

- Source visual truth:
  - `qa/source-grove.png`
  - `qa/source-founders.png`
  - `qa/source-evergreen.png`
- Implementation screenshots:
  - `qa/grove-desktop.png`
  - `qa/founders-desktop.png`
  - `qa/evergreen-desktop.png`
  - `qa/grove-mobile.png`
  - `qa/founders-mobile.png`
  - `qa/evergreen-mobile.png`
- Comparison evidence: `qa/comparison.png` and `qa/comparison-evergreen.png`
- Viewports: 1440 × 1024 desktop; 390 × 844 mobile
- State: default landing-page state at the top of each direction

## Findings

No actionable P0, P1, or P2 findings remain.

- Fonts and typography: Spectral/Mulish and Instrument Serif/Instrument Sans match the intended editorial and founder-led directions. Headline scale, line height, emphasis, and wrapping preserve the hierarchy of each source without clipping at desktop or mobile widths.
- Spacing and layout rhythm: Hero proportions, qualification rails, section transitions, and CTA placement follow the source concepts. Mobile layouts reflow to one column with no horizontal overflow and keep the primary action visible in the first screen.
- Colors and visual tokens: Cream, evergreen, clay, and restrained gold tokens match the source palettes and retain readable foreground/background contrast.
- Image quality and asset fidelity: Existing Eighteen Grove photography is used at natural aspect ratios with intentional crops. The exact generated hero scenes were replaced with existing project photography in the same art direction; this is an intentional asset substitution, not unresolved design drift.
- Copy and content: Approved positioning, EBITDA target, sector criteria, confidentiality language, contact details, and disclaimer are preserved. No portfolio, returns, testimonial, or track-record claims were added.

## Interaction and browser checks

- Selector-page cards navigate to their matching direction.
- The primary “Start a confidential conversation” CTA scrolls to the contact section.
- Header navigation and criteria links use valid in-page anchors.
- Mail links use `mailto:info@eighteengrove.com`.
- All rendered images loaded successfully.
- Browser console errors checked: none.

## Focused comparison evidence

Focused comparison was performed on the hero, header, CTA group, qualification rail, and first section transition because those are the defining fidelity surfaces in the three selected concepts. The long-form sections reuse the same verified component system and approved content.

## Comparison history

1. Initial capture found two P2 issues: default `figure` margins inset the hero imagery, and selector-page anchors inherited browser-default link styling. Both were corrected in `site.css` and `index.html`.
2. Mobile capture found one P2 issue: the Founders CTA group shrink-wrapped instead of using the available mobile width. The mobile Founders action group was set to full width.
3. Post-fix desktop and mobile captures showed no remaining P0/P1/P2 issues, no horizontal overflow, no broken images, and no console errors.

## Follow-up polish

- P3: Replace the existing forest and field photographs with final licensed Eighteen Grove photography once a direction is selected.

final result: passed
