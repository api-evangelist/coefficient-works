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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Coefficient Works, Inc. (operating as **Coefficient**) is a San Mateo, California no-code data platform that connects live business data to Google Sheets and Microsoft Excel. Founded in 2019 by Navneet Loiwal and Tommy Tsai, it provides point-and-click connectors to 60+ business systems (Salesforce, HubSpot, NetSuite, QuickBooks, Snowflake, MySQL, Stripe, Looker, Tableau, Google Ads), scheduled two-way sync, Slack/email alerting, live web dashboards, and an AI assistant for spreadsheet work.

- Website: https://coefficient.io/
- Help Center: https://help.coefficient.io/hc/en-us
- Pricing: https://coefficient.io/pricing
- Data Security: https://coefficient.io/data-security

## API posture

Coefficient is an **API consumer, not an API producer**. As of the 2026-07-20 enrichment pass it publishes:

- no public developer API, developer portal, or API reference
- no OpenAPI, AsyncAPI, or GraphQL description
- no first-party client SDKs on npm, PyPI, or other registries
- no MCP server, CLI, webhooks, changelog, or status page
- no `/.well-known/` discovery documents (security.txt, openid-configuration, oauth-authorization-server, api-catalog, ai-plugin.json all returned 404)
- no named security certifications (the Data Security page cites AWS hosting, end-to-end credential encryption, routine pen testing, and Google/Microsoft marketplace vendor compliance, but no SOC 2 / ISO 27001 / HIPAA claim)

It does publish a machine-readable `/llms.txt`, captured verbatim in `llms/`.

Distribution is via the Google Workspace Marketplace, Microsoft AppSource, and the Atlassian Marketplace.

Backed by: Battery Ventures, Foundation Capital, S28 Capital.
