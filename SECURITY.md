# Security Policy

CORE teaches security responsibly. We welcome reports of security issues in this repository and feedback about unsafe content.

## Reporting a Vulnerability
If you discover a security vulnerability in the site, build pipeline, or repository configuration:

1. Do **not** open a public issue with sensitive details.
2. Use GitHub **Security Advisories** if available (Security tab → "Report a vulnerability").
3. If advisories are not available, open a GitHub issue with the title:
   **[Security] Private report request**
   and keep technical details minimal until maintainers respond.

## Responsible Security Content Rules
We do not accept content that enables real-world harm, including:
- Weaponized exploit chains against real targets
- Malware deployment instructions
- Evasion, persistence, or stealth focused on bypassing security controls
- Credential theft instructions beyond basic defensive awareness
- “Do this to hack X” content

Allowed (and encouraged):
- Defensive security fundamentals
- Safe demonstrations in isolated labs (local VMs, CTFs, intentionally vulnerable apps)
- Threat modeling, detection, mitigation, hardening
- Red-team topics framed for learning, ethics, and defense

## Handling Sensitive Information
Do not commit:
- API keys, tokens, passwords
- Private IPs, personal data, or identifying details
- Proprietary/confidential content

If sensitive info is accidentally committed, report it immediately so it can be removed and rotated.

## Supported Versions
CORE is continuously updated. Only the `main` branch and published site are considered supported.
