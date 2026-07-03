# Checkr (checkr)

Checkr is a technology-driven background check platform for employment screening. Its REST API lets employers, staffing firms, and platform partners run compliant background checks programmatically - creating candidates, sending invitations, ordering packages, and retrieving reports composed of individual screenings (SSN trace, county/state/national/federal criminal searches, sex offender registry, motor vehicle records, and education/employment verifications). The API also covers adverse action workflows, subscriptions and continuous checks, node/hierarchy and geo account structure, documents, Form I-9, and webhooks for event-driven report status updates. Authentication is HTTP Basic auth with a secret API key; Checkr Partner integrations use OAuth.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/checkr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/checkr/refs/heads/main/apis.yml)

**Base URL:** `https://api.checkr.com/v1`

## Tags

- Background Checks
- Employment Screening
- Compliance
- HR Tech
- Identity Verification
- Criminal Records

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Checkr Candidates API

Create, list, retrieve, and update the candidate records that background checks are run against, and request PII removal. Candidates hold the personal information (name, DOB, SSN, addresses, driver license, work authorization) used to order reports and screenings.

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

### Checkr Invitations API

Send candidates a hosted invitation to submit their own information and consent, then create, list, retrieve, and cancel those invitations. Invitations order a package once the candidate completes the flow, removing the need to collect PII directly.

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

### Checkr Reports API

Create, retrieve, update/upgrade, complete, and review reports - the top-level container for a candidate's background check that aggregates individual screenings, addresses, documents, an ETA, and an overall assessment result (clear/consider).

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

### Checkr Screenings API

Retrieve the individual screening components nested under a report - SSN trace, county/state/national/federal criminal searches, sex offender registry search, global watchlist, and motor vehicle report - each with its own status and records.

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

### Checkr Verifications API

List and retrieve education and employment verification screenings for a report, plus manage the supporting candidate-provided schools, employers, driver licenses, and professional licenses used to verify history.

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

### Checkr Packages API

List and retrieve the packages (bundles of screenings such as Basic+, Essential, and Professional) and programs configured on your account that determine which screenings a report includes and what it costs.

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

### Checkr Documents API

Upload, list, and retrieve documents attached to a candidate - driver license images, motor vehicle records, and other supporting files required to process or dispute a screening.

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

### Checkr Adverse Actions API

Create, list, retrieve, and cancel FCRA-compliant adverse action workflows against a report, including the pre-adverse and post-adverse notice timing required when a hiring decision is based on a background check.

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

### Checkr Subscriptions API

Create, list, retrieve, update, and cancel subscriptions that automatically re-run a package for a candidate on a recurring schedule (for example annual re-screening).

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

### Checkr Continuous Checks API

Create, list, retrieve, update, and cancel continuous checks that monitor a candidate on an ongoing basis and surface new criminal or MVR records as they appear, rather than as a one-time point-in-time report.

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

### Checkr Nodes and Hierarchy API

Model your organization as a tree of nodes (locations, departments, franchises) via the hierarchy and nodes endpoints, so reports and billing can be segmented and access controlled across a large account.

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

### Checkr Geos API

Create, list, retrieve, update, and delete geos - the state/locale definitions that scope package pricing and localized compliance requirements so reports follow the rules of the candidate's work location.

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

### Checkr Webhooks API

Register and manage webhook subscriptions that Checkr POSTs event notifications to (report.completed, candidate.created, invitation.completed, and more) over HTTPS or Amazon SNS, giving event-driven updates on long-running screening workflows.

- **Human URL:** [https://docs.checkr.com/](https://docs.checkr.com/)
- **Base URL:** `https://api.checkr.com/v1`

## Authentication

Checkr uses HTTP Basic auth: pass your **secret API key** as the username with an empty password. Publishable keys are used only with Checkr's client-side JS API. Checkr Partner integrations authenticate on behalf of customer accounts using **OAuth**.

## Rate Limits

The API allows **1200 requests per minute** across all endpoints, with `X-Ratelimit-Limit`, `X-Ratelimit-Remaining`, and `X-Ratelimit-Reset` response headers. Exceeding it returns HTTP 429. POST requests support an `Idempotency-Key` header. List endpoints paginate with `page` and `per_page` (default 25).

## Common Properties

- [GitHub Organization](https://github.com/checkr)
- [LinkedIn](https://www.linkedin.com/company/checkr)
- [Website](https://checkr.com)
- [Documentation](https://docs.checkr.com/)
- [Plans](plans/checkr-plans-pricing.yml)
- [Rate Limits](rate-limits/checkr-rate-limits.yml)
- [Fin Ops](finops/checkr-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
