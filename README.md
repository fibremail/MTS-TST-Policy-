Fibremail sub domain MTA-STS

Overview

This repository hosts the MTA-STS policy for the Fibremail sub domain.

It allows supporting mail servers to verify that SMTP connections to the Fibremail mail infrastructure must use valid TLS and trusted certificates.

---

Purpose

This repository provides:

- Version control for the MTA-STS policy.
- A simple deployment source.
- Easy rollback if policy changes are required.
- Documentation of policy revisions over time.

The policy is intentionally kept small and straightforward.

---

Deployment

This repository is deployed to the "mta-sts.sl.fibremail.com" subdomain.

Changes should only be made after confirming that the mail infrastructure supports the intended policy mode (for example, "testing" or "enforce").

---

Related Standards

This repository forms part of the Fibremail email security infrastructure alongside:

- TLS Reporting (TLS-RPT)
- DNSSEC
- SPF
- DKIM
- DMARC
- OpenPGP Web Key Directory (WKD)

---

License

Infrastructure project for the Fibremail domain.