# BOIRO Vulnerability Disclosure Policy

Last updated: 2026-10-14

BOIRO welcomes good-faith reports that help us protect our products, services, customers, and users. This policy explains how to report a vulnerability and which security-testing activities BOIRO currently authorizes.

## Reporting a vulnerability

Submit reports through [GitHub's private vulnerability reporting](https://github.com/Boiro-io/security/security/advisories).

Do not disclose vulnerabilities through public issues, discussions, pull requests, social media, or other public channels.

A useful report includes:

- the affected product, service, domain, or endpoint;
- a clear description of the vulnerability and its potential impact;
- reproducible steps or a minimal proof of concept;
- any prerequisites, test accounts, or configuration involved;
- relevant logs, screenshots, or request and response data with secrets and personal data removed;
- a preferred way for BOIRO to contact you.

## Authorized target

Active security testing is currently authorized only against:

- `app.boiro.io`

BOIRO considers good-faith security research against this target to be authorized when it is conducted in accordance with this policy. Activities that do not comply with this policy are not authorized.

## Out-of-scope targets

Unless BOIRO provides explicit written authorization, active security testing is not authorized against:

- `boiro.io`, `control.boiro.io`, or any other BOIRO-operated hostname;
- customer instances, customer subdomains, or customer custom domains;
- BOIRO repositories, employee accounts, infrastructure, or internal systems;
- third-party services, integrations, networks, or infrastructure.

Vulnerabilities discovered unintentionally on an out-of-scope target may still be reported. Stop testing that target, do not attempt to demonstrate additional impact, and privately report the information already observed.

## Testing rules

When testing the authorized target:

- use only accounts and data you own or have explicit permission to use;
- make a good-faith effort to avoid privacy violations, service disruption, and harm to BOIRO or its users;
- stop immediately and report the issue if you encounter personal, confidential, or customer data, or gain unintended access;
- access only the minimum information necessary to demonstrate the vulnerability;
- do not retain, download, copy, alter, delete, or publicly disclose other users' data;
- do not establish persistence, install backdoors, pivot to other systems, or attempt lateral movement;
- do not perform denial-of-service, load testing, high-volume automated scanning, spam, phishing, social engineering, or physical testing;
- do not test third-party services or integrations;
- do not use a vulnerability to access data or functionality beyond what is required for a minimal proof of concept;
- do not publicly disclose the vulnerability before BOIRO has had a reasonable opportunity to investigate, remediate, and coordinate disclosure.

If you are unsure whether an activity is permitted, submit a private report and request clarification before continuing.

## BOIRO's response

BOIRO will review the report, assess its impact and reproducibility, and coordinate next steps with the reporter. We may request additional information during the investigation and will communicate when remediation or coordinated disclosure is appropriate.

Submitting a report does not guarantee a monetary reward. Any recognition or reward is determined by BOIRO on a case-by-case basis.

This policy applies only to systems controlled by BOIRO. BOIRO cannot authorize testing of systems owned or operated by third parties.
