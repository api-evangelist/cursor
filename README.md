# Cursor (cursor)

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

Cursor is an AI-first code editor by Anysphere, forked from VS Code, with deep AI integration: agentic edits, codebase chat, autocomplete, and tab-completion. Offers a hosted plan with model access and team management. Cursor exposes a public Admin API, Analytics API, AI Code Tracking API, Cloud Agents API, and a TypeScript SDK.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/apis.yml)

## Tags

- AI
- Developer Tools
- Code Editor
- Agent
- IDE
- Cloud Agents

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-19

## APIs

### Cursor Admin API

Programmatic access to team data: members, usage metrics, spending, repository blocklists, daily/filtered usage events. Available to Enterprise teams. Uses HTTP Basic auth with API key as username.

- **Human URL:** [https://cursor.com/docs/account/teams/admin-api](https://cursor.com/docs/account/teams/admin-api)
- **Base URL:** `https://api.cursor.com`

#### Tags

- Admin
- Teams
- Usage
- Billing

#### Properties

- [Documentation](https://cursor.com/docs/account/teams/admin-api)
- [A P I Index](https://cursor.com/docs/api)
- [Postman Collection](collections/cursor-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cursor-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cursor Analytics API

Usage insights, AI metrics, and model usage stats for Enterprise teams.

- **Human URL:** [https://cursor.com/docs/account/teams/analytics-api](https://cursor.com/docs/account/teams/analytics-api)
- **Base URL:** `https://api.cursor.com`

#### Tags

- Analytics
- Teams
- Metrics

#### Properties

- [Documentation](https://cursor.com/docs/account/teams/analytics-api)
- [Postman Collection](collections/cursor-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cursor-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cursor AI Code Tracking API

Track AI-generated code at the commit level for Enterprise teams.

- **Human URL:** [https://cursor.com/docs/api](https://cursor.com/docs/api)
- **Base URL:** `https://api.cursor.com`

#### Tags

- AI Tracking
- Commits
- Teams

#### Properties

- [Documentation](https://cursor.com/docs/api)
- [Postman Collection](collections/cursor-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cursor-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cursor Cloud Agents API

Create and manage AI coding agents in the cloud. Beta, available across all plans.

- **Human URL:** [https://cursor.com/docs/api](https://cursor.com/docs/api)
- **Base URL:** `https://api.cursor.com`

#### Tags

- Agents
- Cloud
- Beta

#### Properties

- [Documentation](https://cursor.com/docs/api)
- [Type Script S D K](https://cursor.com/docs/api)
- [Postman Collection](collections/cursor-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cursor-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/cursor)
- [LinkedIn](https://www.linkedin.com/company/cursorai)
- [Website](https://cursor.com/)
- [Documentation](https://cursor.com/docs)
- [Pricing](https://cursor.com/pricing)
- [Plans](plans/cursor-plans-pricing.yml)
- [Rate Limits](rate-limits/cursor-rate-limits.yml)
- [Fin Ops](finops/cursor-finops.yml)
- [L L Ms Txt](https://cursor.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
