# iam-automation-hub
   Python toolkit automating identity lifecycle workflows across Okta and Microsoft Entra ID via APIs and SCIM.
# IAM Automation Hub

A Python toolkit for automating identity lifecycle workflows across Okta and Microsoft Entra ID using their native APIs and SCIM 2.0.

## What This Project Does

Automates IAM operations that are typically handled manually through admin consoles or one-off scripts:

- User provisioning and deprovisioning across multiple identity providers
- Bulk group membership management
- Access review data extraction and reporting
- SCIM-based synchronization between Okta and Microsoft Entra ID
- Scheduled automation via GitHub Actions

## Planned Features

- [ ] Okta user lifecycle automation (Okta API)
- [ ] Microsoft Entra ID user and group management (Microsoft Graph API)
- [ ] SCIM 2.0 client for cross-IdP provisioning
- [ ] GitHub Actions workflows for scheduled jobs
- [ ] Structured audit logging and CSV/JSON reporting
- [ ] Configurable lifecycle policies (joiner, mover, leaver)

## Tech Stack

- **Language:** Python 3.11+
- **APIs:** Okta API, Microsoft Graph API, SCIM 2.0
- **Authentication:** OAuth 2.0 client credentials flow
- **Automation:** GitHub Actions
- **Testing:** pytest

## Project Status

🚧 **In active development** — Phase 1 build, targeting feature completeness by October 2026.

## About

Built as a portfolio project demonstrating practical IAM engineering skills.

Author: [Pratiksha Ramdas Kale](https://www.linkedin.com/in/pratikshakale/)
