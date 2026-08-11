# Security Policy

## Supported Versions

This repository contains the source code for the QubiSafe website hosted at:

`https://qubisafe.github.io/`

Security fixes are applied to the latest version of the website and the default branch of this repository.

| Version                  | Supported |
| ------------------------ | --------- |
| Latest / default branch  | ✅         |
| Older commits / versions | ❌         |

## Reporting a Vulnerability

QubiSafe takes the security of its website, source code, and users seriously. We appreciate responsible security research and encourage security researchers to report vulnerabilities privately.

### Preferred Reporting Method

Please use **GitHub's Private Vulnerability Reporting** feature for this repository, if available.

Security vulnerabilities should **not** be disclosed through public GitHub issues, pull requests, discussions, or other public channels.

GitHub's private vulnerability reporting and repository security advisories are designed to allow maintainers and researchers to privately investigate and resolve security issues before public disclosure.

### If Private Reporting Is Unavailable

Please contact the QubiSafe maintainers privately through an appropriate contact method associated with the project.

When reporting a vulnerability, please do not publicly disclose sensitive details before the issue has been reviewed and, where appropriate, remediated.

## What to Include

Please provide as much of the following information as possible:

* A clear description of the vulnerability
* The affected URL, page, file, component, or functionality
* The affected branch, commit, or version, if known
* Steps required to reproduce the vulnerability
* The potential security impact
* Proof-of-concept information, where appropriate
* Screenshots or logs that help demonstrate the issue
* A suggested mitigation or fix, if known

Please do **not** include real credentials, private keys, API tokens, passwords, personal information, or other sensitive data in your report.

## Do Not Publicly Disclose Vulnerabilities

Please do not create a public issue or pull request containing:

* Exploit code or detailed exploitation instructions
* API keys, access tokens, passwords, or private keys
* Authentication credentials
* Personally identifiable or confidential information
* Sensitive configuration
* Information that could enable attacks against QubiSafe or its users

If you discover a secret accidentally committed to the repository, report it privately and treat the secret as compromised. Exposed credentials should be revoked or rotated as soon as possible. GitHub recommends never hardcoding secrets and using appropriate secret-management mechanisms instead.

## Scope

This security policy covers security vulnerabilities affecting:

* The QubiSafe GitHub Pages website
* Source code contained in this repository
* HTML, CSS, JavaScript, and other client-side code
* GitHub Pages deployment configuration
* GitHub Actions or other repository automation, where applicable
* Third-party dependencies included in the project
* Security-sensitive repository configuration
* Accidental exposure of credentials or other sensitive information through this repository

## Out of Scope

The following are generally outside the scope of this policy:

* Vulnerabilities in GitHub's own infrastructure or GitHub.com
* Vulnerabilities in unrelated third-party services
* Denial-of-service attacks against GitHub or third-party infrastructure
* Social engineering or phishing attacks against QubiSafe personnel or contributors
* Physical attacks against users or infrastructure
* Spam, content issues, or cosmetic website bugs without a security impact
* Issues that require a compromised account or device unless they demonstrate an additional vulnerability in QubiSafe

Security issues in third-party services should be reported to the respective service provider.

## Responsible Testing

Security testing should be performed responsibly and only to the extent necessary to demonstrate the vulnerability.

Researchers should:

* Avoid accessing, modifying, or deleting data belonging to other users.
* Avoid disrupting website availability.
* Avoid automated activity that could negatively affect the service.
* Avoid social engineering or attacks against QubiSafe personnel.
* Stop testing once sufficient evidence has been obtained to demonstrate the vulnerability.
* Avoid accessing or retaining sensitive information that is not necessary to demonstrate the issue.

## Response Process

After receiving a security report, the QubiSafe maintainers will make reasonable efforts to:

1. Acknowledge receipt of the report.
2. Review and validate the reported vulnerability.
3. Assess its severity and potential impact.
4. Work on an appropriate fix or mitigation.
5. Deploy the fix when reasonably possible.
6. Notify affected users or publish a security advisory when appropriate.

The exact response time may vary depending on the severity and complexity of the vulnerability.

## Disclosure

QubiSafe supports coordinated vulnerability disclosure.

Researchers are requested to allow reasonable time for investigation and remediation before publicly disclosing a vulnerability.

Once an issue has been addressed, QubiSafe may publish relevant security information, including the vulnerability's impact, affected versions, remediation, and appropriate researcher credit.

Researchers who responsibly report valid security vulnerabilities may be acknowledged publicly, unless they prefer to remain anonymous.

## Security of Secrets

Contributors must never commit the following to this repository:

* Passwords
* API keys
* Access tokens
* Private keys
* Authentication credentials
* Database credentials
* Other secrets or sensitive configuration

Secrets should be stored using appropriate secret-management mechanisms rather than being hardcoded into source files. GitHub provides secret-management and secret-scanning capabilities to help prevent accidental exposure.

If a secret is accidentally committed:

1. Treat it as compromised immediately.
2. Revoke or rotate the secret.
3. Notify the QubiSafe maintainers privately.
4. Remove the secret from the repository and, where necessary, its history.
5. Investigate whether the exposed credential was accessed or misused.

Removing a secret from the latest commit alone does not necessarily make it safe; credentials should be revoked or rotated first.

## Acknowledgements

QubiSafe appreciates security researchers and contributors who responsibly report vulnerabilities and help improve the security and reliability of the project.

Thank you for helping keep QubiSafe and its users safe.
