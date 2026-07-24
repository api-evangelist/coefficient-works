# Coefficient Works

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
