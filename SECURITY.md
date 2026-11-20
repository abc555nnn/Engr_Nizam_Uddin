# Security Policy

## Overview

This repository contains the personal portfolio web application for **Nizam Uddin** (MSc in CSE — System Engineering, Ethical Hacker, CCNA, Cyber Defense & Log Analysis, IT Infrastructure, and Digital Forensics)[cite: 1, 2, 3, 5]. While this is a static/front-end portfolio project rather than a production enterprise platform, security and responsible disclosure are taken seriously.

## Supported Versions

Security updates and fixes are applied to the latest state of the default branch.

| Version / Branch | Supported          |
| ---------------- | ------------------ |
| `main` (latest)  | :white_check_mark: |
| Older snapshots  | :x:                |

## Scope

### In Scope
- Cross-Site Scripting (XSS) or DOM injection issues within portfolio rendering, search/filter tabs, modals, or inline editing functionality.
- Malicious or untrusted third-party script, font, or media embeds introduced into the repository.
- Accidental exposure of sensitive personal data, private credentials, tokens, or internal system details in source files or commit history.

### Out of Scope
- Denial-of-Service (DoS) or traffic/load testing against hosted demo URLs.
- Social engineering or phishing attempts targeting the repository owner or affiliated organizations.
- Vulnerabilities in third-party hosting providers (e.g., GitHub Pages, Vercel, Netlify, Site123)[cite: 4] or external certificate verification portals.
- Client-side browser storage behavior (such as local browser persistence for live inline edits) when used on an untrusted or shared device[cite: 1, 7].

## Reporting a Vulnerability

Please **do not** open a public GitHub Issue for security vulnerabilities or exposed sensitive information.

Instead, report potential issues privately:
1. Reach out directly via the contact options listed on the portfolio or LinkedIn profile for **Nizam Uddin**[cite: 4, 5].
2. Include a clear summary of the issue, affected files or views, steps to reproduce, and potential impact.

### What to Expect
- **Acknowledgment:** You can expect an initial response within **5 business days**.
- **Assessment & Remediation:** Validated issues involving code vulnerabilities or accidentally committed sensitive data will be reviewed and addressed as promptly as practical.
- **Disclosure:** Please allow a reasonable window to remediate the issue before sharing details publicly.

## Operational & Deployment Notes for Maintainers

- **Inline Editing & Browser Storage:** If live inline editing is enabled in the browser, edits are intended for personal customization—avoid entering sensitive credentials, tokens, or confidential notes into editable fields, and reset/export changes carefully before publishing.
- **Certificate & Project Links:** Ensure external credential links (such as Cisco Networking Academy or Securis360 verification URLs) and project showcase items point only to verified, safe destinations[cite: 2, 3, 8].
- **Secret Scanning:** Run secret checks before committing changes so API keys, private links, or personal documents are never pushed to version control.
