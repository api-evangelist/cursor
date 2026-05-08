# Cursor (cursor)

Cursor is an AI-first code editor by Anysphere, forked from VS Code, with deep AI integration: agentic edits, codebase chat, autocomplete, and tab-completion. Offers hosted plans with model access and team management. Cursor exposes a public Admin API, Analytics API, AI Code Tracking API, Cloud Agents API, and a TypeScript SDK.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=cursor-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, Developer Tools, Code Editor, Agent, IDE, Cloud Agents

## APIs
- **Admin API** — Team members, usage, spending, repository blocklists. Enterprise teams. Base URL `https://api.cursor.com`. Basic auth with `crsr_*` API key. [Docs](https://cursor.com/docs/account/teams/admin-api)
- **Analytics API** — Usage insights, model usage. Enterprise. [Docs](https://cursor.com/docs/account/teams/analytics-api)
- **AI Code Tracking API** — Track AI-generated code at commit level. Enterprise.
- **Cloud Agents API** — Create/manage AI coding agents. Beta, all plans. TypeScript SDK available.

### Plans (May 2026)
- **Hobby** — Free, no card, limited agent + tab completions.
- **Pro** — $20/mo: extended agent, frontier models, MCPs, skills, hooks, cloud agents.
- **Pro+** — $60/mo: 3x usage on OpenAI/Claude/Gemini.
- **Ultra** — $200/mo: 20x usage, priority feature access.
- **Teams** — $40/user/mo: shared resources, central billing, usage analytics, SSO, RBAC.
- **Enterprise** — Custom: pooled usage, invoice/PO billing, SCIM, audit logs, priority.

### Rate Limits
- Per-team, per-minute: most endpoints 20-100 RPM; some up to 250 RPM (e.g. user spend limit).

## Plans, Rate Limits, FinOps
- [Plans](plans/cursor-plans-pricing.yml)
- [RateLimits](rate-limits/cursor-rate-limits.yml)
- [FinOps](finops/cursor-finops.yml)

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://cursor.com/)
- [Documentation](https://cursor.com/docs)
- [Pricing](https://cursor.com/pricing)

## Notes
- No public OpenAPI spec was discovered at the time of profiling; surfaces are documented page-by-page on cursor.com/docs/api.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
