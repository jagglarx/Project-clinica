# DENTAL CLINICa Product Requirements Document

## Original problem statement
- Build a complete DENTAL CLINICa homepage as a visual-system adaptation inspired by the Oralic editorial UI rhythm, using the provided verified clinic details, exact logo, and suitable uploaded clinic photos.

## Architecture decisions
- React single-page experience in the starter frontend.
- Static verified content is kept in the page content model; no backend API is required for this homepage.
- External actions use the provided WhatsApp, phone, and Google Maps destinations.
- Responsive CSS implements editorial dark/light section pacing, mobile navigation, accordions, and sticky mobile actions.

## User personas
- Prospective dental patients in Jamia Nagar, Okhla and nearby New Delhi areas.
- Existing patients looking for directions, contact details, or a booking channel.
- Clinic staff who need a premium, editable content foundation without unverified claims.

## Core requirements (static)
- Full homepage from utility strip through footer.
- Premium Oralic-inspired layout rhythm without copied content or assets.
- Exact verified rating, review count, address, phone, WhatsApp, Plus Code and practical CTAs.
- Responsive desktop and mobile experience with interaction test IDs.
- Unverified team, service, review and journal content clearly framed as placeholders/general information.

## What has been implemented (2026-08-15)
- Replaced the starter screen with utility strip, sticky header, dark image hero, about, metrics, editorial statement, philosophy, care accordion, service cards, comparison, Google trust, gallery, team placeholders, contact, FAQ, journal, final CTA, footer and mobile action bar.
- Integrated the uploaded DENTAL CLINICa logo and three uploaded clinic photos.
- Added functional WhatsApp, phone, Maps/directions, anchor navigation, mobile menu, service accordion and FAQ accordion.
- Verified production build and desktop/mobile preview rendering.

## Prioritized backlog
- P0: Clinic confirmation of doctor profiles, official service list, hours, approved testimonials and approved gallery captions.
- P1: Replace general service copy with clinic-approved content and add approved Google review excerpts.
- P1: Add a CMS or content editor for clinic staff.
- P2: Add appointment request form and analytics after booking workflow is confirmed.

## Remaining next tasks
- Confirm and publish official treatments, hours, doctor/team profiles and clinic-approved imagery.
- Add privacy/terms destinations and any clinic-approved social links.
