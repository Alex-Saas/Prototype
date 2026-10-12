# Proposed GoIELTS Project Instructions Addendum — Prototype Quality & Publishing Gates

Status: Prepared for application to ChatGPT Project **GoIELTS UI UX & Prototyping** only after verifying workspace **Alex_Workspace**. This file is not proof of a live ChatGPT Project settings update.

## Approved design fidelity
When a Product Owner selects a Desktop or Mobile visual variant, use that precise variant as the implementation baseline. Do not reinterpret layout, spacing, hierarchy, typography, CTA or structure without approval. PRD, User Stories and Acceptance Criteria remain the source of truth for behavior and UX copy.

## Verified assets
Use official GoIELTS assets and production IBM Plex Sans Arabic font. Do not rely merely on specifying the font family name: verify network loading and actual font rendering in browser. Avoid temporary asset URLs and placeholder text logos.

## Mandatory visual verification
Use reference → HTML → browser render → screenshot → compare → fix → re-render. At minimum cover 1440px Desktop, 850px narrow ChatGPT preview, 390px and 375px Mobile. Check horizontal overflow, title wrapping, element balance, CTA and X spacing, colors, radii, alignment and RTL.

## Mandatory functional verification
Test every user and subscription state, all controls, excluded routes, 24h dismissal, restore, and key error/empty/success cases. Stripe payment CTA remains simulated until explicitly integrated. Do not conflate data-eligibility logic with user-facing wording.

## Public publishing
Default host: GitHub Pages in **Alex-Saas/Prototype**, under a feature-specific folder. Verify actual repository owner, branch, connected account Push access and Pages site configuration before making changes. The public URL is a release artifact and must be visited and tested. Keep approved prototype source unchanged during public migration. Present direct public URL rather than sandbox links when published.

## Completion criterion
Never claim Completed & Verified unless visual QA, functional QA, live URL QA and brand asset QA all pass. Distinguish code upload, deployment setup, live publishing and verified public link. Block and report any missing permission.

## Browser hygiene
Close task tabs and release browser sessions when finished; preserve browser persistence without killing processes.
