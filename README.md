# Checkr

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Checkr is a technology-driven background check platform for employment screening. Its REST API lets employers, staffing firms, and platform partners run compliant background checks programmatically - creating candidates, sending invitations, ordering packages, and retrieving reports composed of individual screenings (SSN trace, county/state/national/federal criminal searches, sex offender registry, motor vehicle records, education and employment verifications, and more). The API also covers adverse action workflows, continuous checks and subscriptions, node/hierarchy and geo account structure, Form I-9, documents, and webhooks for event-driven report status updates. Authentication is HTTP Basic auth with a secret API key, with OAuth for Checkr Partner integrations.

**Areas:** Background Checks · Employment Screening · Compliance · Human Resources · Identity Verification · Criminal Records · Recruiting

## Checkr on APIs.io

Everything profiled for Checkr is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/checkr/](https://apis.io/providers/checkr/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [Checkr Account API](https://apis.io/apis/checkr/checkr-account-api/) — Account and user metadata.
- [Checkr Adverse Actions API](https://apis.io/apis/checkr/checkr-adverse-actions-api/) — FCRA adverse action workflows against a report.
- [Checkr Candidates API](https://apis.io/apis/checkr/checkr-candidates-api/) — Candidate records that background checks are run against.
- [Checkr Continuous Checks API](https://apis.io/apis/checkr/checkr-continuous-checks-api/) — Ongoing monitoring for new records.
- [Checkr Documents API](https://apis.io/apis/checkr/checkr-documents-api/) — Files attached to a candidate.
- [Checkr Geos API](https://apis.io/apis/checkr/checkr-geos-api/) — State/locale definitions scoping pricing and compliance.
- [Checkr Invitations API](https://apis.io/apis/checkr/checkr-invitations-api/) — Hosted invitations for candidates to submit their own information.
- [Checkr Nodes and Hierarchy API](https://apis.io/apis/checkr/checkr-nodes-and-hierarchy-api/) — Tree of nodes modeling account/organization structure.
- [Checkr Packages API](https://apis.io/apis/checkr/checkr-packages-api/) — Bundles of screenings and the programs that group them.
- [Checkr Reports API](https://apis.io/apis/checkr/checkr-reports-api/) — The container aggregating a candidate's screenings and result.
- [Checkr Screenings API](https://apis.io/apis/checkr/checkr-screenings-api/) — Individual screening components nested under a report.
- [Checkr Subscriptions API](https://apis.io/apis/checkr/checkr-subscriptions-api/) — Recurring re-runs of a package for a candidate.
- [Checkr Verifications API](https://apis.io/apis/checkr/checkr-verifications-api/) — Education and employment verification screenings.
- [Checkr Webhooks API](https://apis.io/apis/checkr/checkr-webhooks-api/) — Event notification subscriptions.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [checkr](https://apis.io/servers/checkr/checkr/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Checkr Agentic Access](https://apis.io/agentic-access/checkr/checkr-agentic-access/)

#### Collections (15)

Postman and Open Collection request collections.

- [Checkr API](https://apis.io/collections/checkr/open-checkr/)
- [Checkr Account API](https://apis.io/collections/checkr/open-checkr-account-api/)
- [Checkr Account Adverse Actions API](https://apis.io/collections/checkr/open-checkr-adverse-actions-api/)
- [Checkr Account Candidates API](https://apis.io/collections/checkr/open-checkr-candidates-api/)
- [Checkr Account Continuous Checks API](https://apis.io/collections/checkr/open-checkr-continuous-checks-api/)
- [Checkr Account Documents API](https://apis.io/collections/checkr/open-checkr-documents-api/)
- [Checkr Account Geos API](https://apis.io/collections/checkr/open-checkr-geos-api/)
- [Checkr Account Invitations API](https://apis.io/collections/checkr/open-checkr-invitations-api/)
- [Checkr Account Nodes and Hierarchy API](https://apis.io/collections/checkr/open-checkr-nodes-and-hierarchy-api/)
- [Checkr Account Packages API](https://apis.io/collections/checkr/open-checkr-packages-api/)
- [Checkr Account Reports API](https://apis.io/collections/checkr/open-checkr-reports-api/)
- [Checkr Account Screenings API](https://apis.io/collections/checkr/open-checkr-screenings-api/)
- [Checkr Account Subscriptions API](https://apis.io/collections/checkr/open-checkr-subscriptions-api/)
- [Checkr Account Verifications API](https://apis.io/collections/checkr/open-checkr-verifications-api/)
- [Checkr Account Webhooks API](https://apis.io/collections/checkr/open-checkr-webhooks-api/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Checkr Authentication](https://apis.io/security/checkr/checkr-authentication/)
- [Checkr Domain Security](https://apis.io/security/checkr/checkr-domain-security/)
- [Checkr Trust Center](https://apis.io/security/checkr/checkr-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Checkr Plans Pricing](https://apis.io/plans/checkr/checkr-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Checkr Rate Limits](https://apis.io/rate-limits/checkr/checkr-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Checkr Finops](https://apis.io/finops/checkr/checkr-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://checkr.com)
- [Documentation](https://docs.checkr.com/)
- [Blog](https://checkr.com/blog)
- [GitHub](https://github.com/checkr)

## API Evangelist rating

**Kin Score 30.2** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 55.2 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 32.1 |
| Access clarity | 15.8 |

**Agent readiness 48.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Employment & Payroll

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/checkr/](https://apis.io/providers/checkr/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Checkr: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/checkr/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
