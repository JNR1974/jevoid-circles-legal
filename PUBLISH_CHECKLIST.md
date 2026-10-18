# Jevoid Circles — before public GitHub Pages publication

**Status: finalized content candidate, NOT legal sign-off or publication-ready.**

## Confirmed for draft
- Data controller / sole trader: **Jordi Nogues**, Ireland.
- Service: **Jevoid Circles**.
- Public support and privacy contact: **LensLabsAI@gmail.com** (verify monitored inbox).
- First-release audience per original PRD: **adults 18+**; under-18/child-tracking functionality is excluded for now.
- Current development state: live Firebase authentication and App Check debug exchange validated; Job 04 Circle CRUD and role control locally/emulator validated, NOT deployed live.
- Opt-in temporary location sharing, journeys and SOS are **planned**, not live.

## Must resolve before publishing
- [ ] Confirm whether Irish sole-trader/business and EU consumer rules require a business/trading address and any additional contact/registration information; provide a suitable lawful business correspondence address if required (avoid adding home address without considering alternatives). Check with an Irish solicitor/privacy professional.
- [ ] Verify final inventory of data categories, Firebase/Google processors and processing locations, transfers and safeguards; confirm GDPR lawful bases and retention periods for data, security logs, backup and deletion.
- [ ] Validate account-deletion functionality and public deletion instructions against **deployed** backend (not only emulator), as applicable for Google Play.
- [ ] Confirm deployed Circle access controls/other actual functionality; update Privacy/Terms before location, invitation, SOS or billing goes live.
- [ ] Verify age 18+ enforcement in app AND backend, plus appropriate Google Play audience declarations.
- [ ] Review exact legal/consent effective date and version synchronization (development backend historically uses 2026-10-17); update app, server and documents together. Never fabricate user consent.
- [ ] Obtain qualified Irish/EU legal review, including GDPR transparency, ePrivacy, consumer/e-commerce disclosure obligations and safety-service wording.
- [ ] On approval, update the draft banner and noindex policy appropriately, mark actual effective date, and verify pages render and links work on mobile.
- [ ] Confirm repository and Git history contain no secrets or unpublished personal details; public repositories preserve commit history.
- [ ] Publish GitHub Pages ONLY after checklist passes; verify unauthenticated HTTPS links, then configure POLICY_URL and TERMS_URL in ignored Firebase properties.

No live Firebase deployment, billing change or public publication is included in this package.
