# Coefficient Works

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

Coefficient Works, Inc. (operating as Coefficient) is a San Mateo, California no-code data platform that connects live business data to Google Sheets and Microsoft Excel. Founded in 2019 by Navneet Loiwal and Tommy Tsai, the company provides point-and-click connectors to 60+ business systems including Salesforce, HubSpot, NetSuite, QuickBooks, Snowflake, MySQL, Stripe, Looker, Tableau and Google Ads, with scheduled two-way sync, spreadsheet-native alerting through Slack and email, live web dashboards, and an AI assistant that builds pivot tables, formulas, charts and data-cleaning steps from natural language. Coefficient is a consumer of other providers' APIs rather than a producer: as of this enrichment pass it publishes no public developer API, no OpenAPI or AsyncAPI description, no client SDKs, and no developer portal, and its "Connect Any API" feature is a consumer-side HTTP client (GET/POST, bearer token / API key / basic auth, cursor, offset and page-number pagination) that writes third-party API responses into a sheet. The one programmatic surface Coefficient serves is an inbound webhook trigger URL, issued per import on the Pro and Enterprise plans, that an external system calls to force an immediate refresh — capped at 12 calls per hour with a five-minute minimum interval. Coefficient states it is SOC 2 compliant and provides the audit report on request. Distribution is through the Google Workspace Marketplace and Microsoft AppSource. The company is backed by Battery Ventures, Foundation Capital and S28 Capital.

**Areas:** Company · Spreadsheets · Google Sheets · Microsoft Excel · Data Integration · No-Code · Business Intelligence · Reporting · Revenue Operations · Software-as-a-Service

## Coefficient Works on APIs.io

Everything profiled for Coefficient Works is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/coefficient-works/](https://apis.io/providers/coefficient-works/)** — or go straight to one of the APIs or properties below.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Coefficient Works Webhooks](https://apis.io/asyncapis/coefficient-works/coefficient-works-webhooks/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Coefficient Works Domain Security](https://apis.io/security/coefficient-works/coefficient-works-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Coefficient Works Plans Pricing](https://apis.io/plans/coefficient-works/coefficient-works-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Coefficient Works Rate Limits](https://apis.io/rate-limits/coefficient-works/coefficient-works-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://coefficient.io/)
- [Documentation](https://help.coefficient.io/hc/en-us)
- [Getting started](https://coefficient.io/get-started)
- [Pricing](https://coefficient.io/pricing)
- [Sign up](https://coefficient.io/get-started)
- [Support](https://help.coefficient.io/hc/en-us)
- [Blog](https://coefficient.io/blog)
- [Compliance](https://coefficient.io/data-security)
- [Terms of service](https://coefficient.io/terms)
- [Privacy policy](https://coefficient.io/privacy-policy)
- [GitHub](https://github.com/coeff)

## API Evangelist rating

**Kin Score 45.4** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 55.4 |
| Contract quality | 39.0 |
| Contract governance | 18.2 |
| Operational transparency | 31.6 |
| Developer ergonomics | 28.6 |
| Access clarity | 84.2 |

**Agent readiness 19.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 23.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/coefficient-works/](https://apis.io/providers/coefficient-works/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Coefficient Works: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/coefficient-works/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
