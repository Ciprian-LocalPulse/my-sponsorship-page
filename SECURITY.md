# Security Policy

My Sponsorship Page is maintained as a public-facing sponsorship, trust, and supporter-conversion repository. This policy defines how security concerns should be reported, what is in scope for public review, and which sponsor, commercial, or implementation details must remain private.

## Public Edition Security Scope

This repository represents the Public Edition of the sponsorship page. Public materials may include sponsor messaging, public trust positioning, static page materials, governance files, and safe evaluation materials.

This repository must not disclose or request disclosure of:

- private sponsor records, donor information, transaction details, invoices, or payment metadata
- private sponsor tier fulfillment details, private benefits delivery, or supporter account information
- payment provider configuration, webhooks, API keys, tokens, secrets, credentials, or environment variables
- private analytics, conversion data, campaign performance data, or supporter segmentation
- private commercial discussions, partnership terms, acquisition materials, pricing strategy, or negotiation details
- unreleased brand assets, private messaging drafts, private sponsor communications, or internal launch materials
- private prompts, internal playbooks, operational runbooks, or commercial implementation details

## Supported Scope

Security reports are welcome for issues affecting public repository materials, including:

- accidental exposure of secrets or sensitive data
- unsafe public documentation that could enable misuse
- vulnerable public demo code, if present
- browser security concerns in public code, including unsafe script injection, unsafe external links, unsafe forms, or unsafe asset loading
- dependency, supply-chain, or build configuration concerns, if such files are later added
- misleading sponsorship, support, or trust-language issues that could create user or sponsor risk
- repository configuration issues that affect integrity, trust, or disclosure handling

## Out of Scope

The following are generally out of scope unless they expose sensitive data or create direct user risk:

- generic best-practice requests without a specific security impact
- social engineering, phishing, or physical security testing
- denial-of-service testing or traffic flooding
- scanning infrastructure not owned or explicitly authorized by the maintainer
- automated reports with no exploitability explanation
- third-party platform issues outside this repository owner's control
- requests for private sponsor records, payment details, analytics, conversion strategy, tier fulfillment workflows, or private commercial terms
- subjective design, brand, sponsor tier, or messaging preferences with no security impact

## Reporting Process

Please report security issues privately and with minimal sensitive detail.

Preferred process:

1. Use GitHub private vulnerability reporting if it is enabled for this repository.
2. If private vulnerability reporting is unavailable, contact the maintainer through the public GitHub profile or the commercial contact path listed in SUPPORT.md.
3. Do not open a public issue containing secrets, exploit details, sponsor information, donor records, payment details, private commercial details, or implementation-sensitive information.
4. Include a concise description, affected file or area, reproduction notes where safe, and recommended remediation.

## Response Timeline

The maintainer will make a reasonable effort to follow this timeline:

- Acknowledgement: within 5 business days
- Initial triage: within 10 business days
- Remediation decision: based on severity, exploitability, and public safety impact
- Public disclosure: only after remediation or explicit maintainer approval

This repository is maintained as a public sponsorship and governance surface. Response times may vary for non-critical documentation findings.

## Safe Harbor

Good-faith research is welcome when it is defensive, limited, and respectful of the boundaries above. The maintainer will not pursue action against researchers who:

- act in good faith and avoid privacy violations
- do not access, modify, delete, or exfiltrate data
- do not disrupt services or third-party systems
- avoid public disclosure before coordination
- stop testing and report promptly after identifying a potential issue

Safe harbor does not apply to unauthorized access, credential misuse, data theft, extortion, payment abuse, donor-data exposure, scraping private sponsor data, or attempts to obtain private commercial materials.

## Public Disclosure

Public disclosure should be coordinated with the maintainer. Reports may be acknowledged in release notes or changelog entries when doing so does not reveal sensitive security information.

## Responsible Use

My Sponsorship Page is intended for lawful sponsorship discovery, public trust positioning, supporter conversion, and commercial inquiry routing. Reports, issues, pull requests, or discussions that enable credential misuse, payment abuse, donor-data exposure, phishing, impersonation, or private material extraction may be closed or removed.