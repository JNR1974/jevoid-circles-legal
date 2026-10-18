# Jevoid Circles — legal pages for GitHub Pages

**DRAFT — prepared for private Git staging only. Do NOT publish or enable GitHub Pages yet.**

Static responsive website with `index.html`, `privacy.html`, `terms.html` and `style.css`. These draft documents are based on the current Jobs 01–03 features and planned Jevoid Circles safety/location features; **they are not legal advice or ready for public acceptance**.

## Suggested GitHub setup now

1. Create a new **private** GitHub repository named `jevoid-circles-legal` under your account.
2. Upload the files from this folder to its **root**, or push them with Git. Do not upload your Android repository or Firebase credentials.
3. **Leave Settings → Pages disabled** and keep the repository private until publication review. This draft has legal placeholders and is not suitable for public users.
4. Work on content privately while Job 04 continues. Use `PUBLISH_CHECKLIST.md` to finish all unresolved facts and legal operator/contact disclosures.

## Future publication (only after approval)

On GitHub Free, GitHub Pages normally requires a **public** repository. Once legal review and placeholders are finished, change this separate repository to public, then visit **Settings → Pages → Deploy from a branch → main / (root)**. On eligible paid plans, other repository visibility options may exist, but Pages websites are publicly accessible in every case.

For GitHub user `JNR1974` and repository `jevoid-circles-legal`, the *expected*, not-yet-live URLs are:

- `https://jnr1974.github.io/jevoid-circles-legal/privacy.html`
- `https://jnr1974.github.io/jevoid-circles-legal/terms.html`

Verify the real published URLs before adding them to the Android app. In the existing manual FirebaseOptions setup, the Android app reads only `POLICY_URL` and `TERMS_URL` from its ignored `firebase.debug.properties` (and later separately prepared release properties). A downloaded `google-services.json` does not configure these URLs.

## Cautions

- **Minimum identity is not anonymity:** Irish/EU GDPR generally requires the identity and contact information of the actual controller. A brand alone may not meet that obligation for a sole trader; confirm professional advice and a suitable business correspondence address.
- A separate inbox can minimize personal email exposure but must be monitored.
- A privacy policy is not a replacement for feature-specific consent or Android permission explanations.
- Publishing legally incomplete drafts, including `[PLACEHOLDER]` text, risks giving users incorrect information.
- Git commits and repository history remain accessible to others after a public release. Do not commit personal details that you would later want hidden from history; add them only when ready for disclosure.

References:
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://support.google.com/googleplay/android-developer/answer/18258653
- https://www.dataprotection.ie/en/organisations/know-your-obligations/transparency
