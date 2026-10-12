# GoIELTS Prototype — Release QA Gate

## Ownership and scope
- [ ] Confirm intended GitHub organization / repository and connected plugin write permission before any write.
- [ ] Confirm active ChatGPT workspace **Alex_Workspace** before modifying Project settings or instructions.
- [ ] Record approved source version, layout references, and no-change areas.
- [ ] Do not publish sensitive files, authentication tokens, or private account data.

## Pixel-aware review
- [ ] Preserve the approved Desktop and Mobile visual references: alignment, layout, order, spacing, type, logo, colors, radii and CTA.
- [ ] Use official verified GoIELTS assets and production **IBM Plex Sans Arabic** typography; verify actual font load in browser.
- [ ] Render and inspect desktop 1440px, narrow ChatGPT preview 850px, mobile 390px and 375px.
- [ ] Compare browser screenshots with approved references, fix deviations, re-render.
- [ ] Check horizontal overflow, clipping, overlap between dismiss and CTA, and long Arabic copy.

## Functional
- [ ] Exercise every subscription state and learner-copy variant.
- [ ] Check click/tap, dismissal, 24-hour persistence, restore, excluded routes.
- [ ] State clearly that Stripe action is a simulation, not a real payment.
- [ ] Verify any tested routes, UI copy and feature rules against approved PRD.

## Public publishing
- [ ] Commit approved source into **Alex-Saas/Prototype** (not personal account).
- [ ] Publish via GitHub Pages from the verified branch and folder.
- [ ] Open public URL, confirm HTTP 200 and correct title.
- [ ] Validate font loading, screenshots, desktop/mobile, interaction and console errors on live public URL.
- [ ] Update prototype gallery without rewriting approved prototype.
- [ ] Only claim Completed & Verified after completing visual, functional and public-URL checks.

## Browser hygiene
- [ ] Check for unfinished form or upload.
- [ ] Close task-created tabs and release Playwright/Browser V2 lease.
