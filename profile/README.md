# TrustYourWebsite

The rules for running a website in the EU keep piling up. GDPR. ePrivacy. Cookie consent. The European Accessibility Act. Image copyright. Meta tags that search engines actually read. Headers that keep your visitors safe.

Most of it is buried in legal PDFs or scattered across a hundred blog posts. Nobody has time to read all of it and still run a business.

TrustYourWebsite gives you a plain-English view of where your site stands. You paste a URL, we run 150+ technical checks, and you get a score out of 100 with the issues grouped by category. No jargon. No fear-mongering. Just what's there, what's missing and what to fix first.

Find it at **[trustyourwebsite.com](https://trustyourwebsite.com)**.

## Open-source tools

CLIs covering individual checks from the scanner. Free, MIT-licensed, zero or minimal runtime dependencies, CI-friendly.

| Tool | What it does |
|------|--------------|
| **[security-headers](https://trustyourwebsite.github.io/security-headers/)** | Grades HTTP security headers A+ to F — HSTS, CSP, X-Frame-Options, Permissions-Policy and more. Real CSP parser. &nbsp; [GitHub](https://github.com/trustyourwebsite/security-headers) · [npm](https://www.npmjs.com/package/@trustyourwebsite/security-headers) |
| **[cookie-consent-validator](https://trustyourwebsite.github.io/cookie-consent-validator/)** | Clicks "Reject All" on cookie banners and verifies tracking actually stops. Detects 11+ CMPs in 13 languages. &nbsp; [GitHub](https://github.com/trustyourwebsite/cookie-consent-validator) · [npm](https://www.npmjs.com/package/@trustyourwebsite/cookie-consent-validator) |
| **[dns-auth-check](https://trustyourwebsite.github.io/dns-auth-check/)** | Audits SPF, DKIM, DMARC, BIMI and MTA-STS. Recursive SPF lookup counting, automatic DKIM selector discovery. &nbsp; [GitHub](https://github.com/trustyourwebsite/dns-auth-check) · [npm](https://www.npmjs.com/package/@trustyourwebsite/dns-auth-check) |

More repos will land as we open-source parts of the scanner.

Hub page with install commands and previews: **[trustyourwebsite.github.io](https://trustyourwebsite.github.io/)**.

## Full scanner

The CLIs cover specific pieces. The managed service at **[trustyourwebsite.com](https://trustyourwebsite.com)** runs every check against every page of your site and gives you one prioritised fix-it report — security headers, cookie consent, GDPR policy text, email DNS auth, TLS, accessibility (WCAG 2.2 / EAA), image copyright, broken links, meta tags and structured data.

## Not legal advice

Everything we publish is technical analysis. A scanner can't replace a lawyer and we won't pretend otherwise. If you have a live claim against you, talk to a lawyer.

---

Questions, bugs or ideas: open an issue on the relevant repo.
