# Cursor (cursor)

Cursor is an AI-powered code editor built on a fork of Visual Studio Code, designed to make developers extraordinarily productive by deeply integrating large language models into editing, navigation, refactoring, and chat. In addition to its consumer and team plans, Cursor exposes an Admin API for enterprise customers to programmatically manage their team.

This repository captures the APIs, developer tools, and machine-readable API artifacts for Cursor.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/apis.yml)

## Scope

- **Type:** Company
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- AI Editor
- Code Generation
- Coding Assistant
- Copilot
- Developer Tools
- LLM
- Productivity
- VSCode Fork

## Timestamps

- **Created:** 2026-01-02
- **Modified:** 2026-04-28

## APIs

### Cursor Admin API

The Cursor Admin API lets team and enterprise administrators programmatically manage members, billing groups, audit logs, daily usage data, spending, repository indexing blocklists, and per-user spend limits. Authentication uses HTTP Basic Authentication with the API key as the username.

- **Human URL:** [https://cursor.com/docs/account/teams/admin-api](https://cursor.com/docs/account/teams/admin-api)
- **Base URL:** `https://api.cursor.com`
- **OpenAPI:** [openapi/cursor-admin-api-openapi.yml](openapi/cursor-admin-api-openapi.yml)

## Common Properties

- [Website](https://cursor.com)
- [Documentation](https://cursor.com/docs)
- [Pricing](https://cursor.com/pricing)
- [Forum](https://forum.cursor.com)
- [Changelog](https://cursor.com/changelog)
- [JSON-LD Context](json-ld/cursor-context.jsonld)
- [Member Schema](json-schema/cursor-member-schema.json)
- [Daily Usage Schema](json-schema/cursor-daily-usage-schema.json)
- [Audit Event Schema](json-schema/cursor-audit-event-schema.json)
- [Vocabulary](vocabulary/cursor-vocabulary.yml)
- [Rules](rules/cursor-admin-api-rules.yml)
- [Capabilities](capabilities/cursor-admin-api-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
