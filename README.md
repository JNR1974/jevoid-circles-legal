# Jevoid Circles — GitHub Pages legal site

**Prepared 18 October 2026. Candidate content for review; not yet approved for publication.**

Files: `index.html`, `privacy.html`, `terms.html`, `style.css`, `.nojekyll`, `.gitignore`, `PUBLISH_CHECKLIST.md`.

The pages contain the confirmed legal controller **Jordi Nogues**, Ireland, and contact **LensLabsAI@gmail.com**. They reflect the original adults-18+ Jevoid Circles MVP (including locally complete Circle CRUD), **not** a parent-managed children-tracking product. Location sharing, journeys and SOS are described as planned, not currently operating. Confirmed legal details are included while unresolved business identity/address, processors, transfer, retention, deletion and deployment details remain publication blockers. See `PUBLISH_CHECKLIST.md`.

## Upload to GitHub privately first

1. Create a separate private GitHub repository, e.g. `jevoid-circles-legal`.
2. Upload these files to its repository root. Do not upload Android source code, Firebase config, private keys or other credentials.
3. Keep GitHub Pages **disabled** while reviewing, and do not invite public users to rely on draft policies.
4. Complete every item in `PUBLISH_CHECKLIST.md` before publication, and set the final effective date and release consent version.
5. When approved, make the separate repository public if required by your plan and enable **Settings → Pages → Deploy from branch → main / (root)**.

Example expected URLs (not active until published):
- `https://jnr1974.github.io/jevoid-circles-legal/privacy.html`
- `https://jnr1974.github.io/jevoid-circles-legal/terms.html`

Open in a signed-out browser and confirm HTTPS and rendering. In the Android repo, set `POLICY_URL` and `TERMS_URL` in the local ignored `firebase.debug.properties`, and later separate release configuration. Do not change the existing Hilt/manual FirebaseOptions initialization or insert placeholder legal consent.

Public GitHub repositories retain commits and prior published information may be archived. Keep unnecessary private information out of all committed revisions.
