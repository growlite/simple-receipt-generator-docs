# Simple Receipt Generator — documentation site

Version: 1.0 · Effective on publication: 27 September 2026. Prepared for https://github.com/growlite/simple-receipt-generator-docs. This package contains the approved English/Spanish legal and support pages. The owner authorized public hosting in this documentation-only repository. Local preparation does not establish deployment or live availability.

## Publication

The intended canonical address is https://growlite.github.io/simple-receipt-generator-docs/. The coordinator must verify deployment and HTTPS before using the address in an App Store record. Public app release remains a separate decision.

Use one deployment method: **Deploy from a branch**, `main`, `/ (root)`.

1. Verify the finalized payload against the approved candidate and its recorded version/date/hosting delta.
2. Place only this documentation package at the root of `main` in the authorized public repository. Do not add application code, internal review records, customer receipts or credentials.
3. In repository Settings → Pages, select Deploy from a branch, `main`, `/ (root)`, then save. No Actions workflow is required. `.nojekyll` keeps this plain static site from Jekyll processing.
4. Enable/enforce HTTPS when available. Verify the actual published URL, certificate, both language routes, plain-text EULAs and the exact file hashes before using public links. Record actual publication separately from this prepared payload. If publication is delayed beyond 27 September 2026, update the effective date before deployment and verify the mechanical delta again.

Every path is relative, including the language switch and EULA links, so the site works under the project subpath. The package needs no framework, JavaScript, third-party font, form or backend. GitHub Pages still logs visitor IP addresses for security; see the Privacy Policy.

## Customer issues; owner-only contributions

[Customer issue channel](https://github.com/growlite/simple-receipt-generator-docs/issues): customers may report bugs using synthetic examples. The issue template requests reproduction steps without private records. Issues and usernames can be public; GitHub processes them and others may retain copies. The owner's one-year Provider-controlled data policy does not promise removal of GitHub-controlled data or public copies.

For private support, privacy requests and security vulnerability reports, email [support@growlite.ai](mailto:support@growlite.ai). Never post receipts, customer details, tax identifiers, payment references, credentials or unredacted screenshots in issues. The app owner maintains repository contents; outside code contributions and pull requests are not accepted. This README/template expresses policy; actual contributor/PR permissions are separate repository settings to verify. A public repository may still be read or forked through GitHub's normal features.

## Package contents

Root index, ten EN/ES document pages, one stylesheet, two plain-text EULAs, `.nojekyll`, this README and a minimal `.github/ISSUE_TEMPLATE/` bug-report template/config. No internal source, evidence, intake or legal-review matrix is included. Rebuild in the authoritative app workspace using `python3 docs/legal/site/build.py` then `python3 docs/legal/site/export_pages.py`; the exporter writes only the fixed local prepared-package directory and its adjacent hashes. It does not run Git or call GitHub.
