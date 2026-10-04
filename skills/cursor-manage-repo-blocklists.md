---
name: cursor-manage-repo-blocklists
description: Manage repository blocklists by retrieving, adding/updating, or removing entries.
api: openapi/cursor-repo-blocklists-api-openapi.yml
operations:
- getRepoBlocklists
- upsertRepoBlocklists
- deleteRepoBlocklist
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/cursor-repo-blocklists-api-openapi.yml ; every operationId checked against the contract
---

# cursor-manage-repo-blocklists

Manage repository blocklists by retrieving, adding/updating, or removing entries.

## Steps

1. 1. `getRepoBlocklists` – no required fields; uses BasicAuth header.
2. 2. `upsertRepoBlocklists` – request body with repo blocklist data; uses BasicAuth header.
3. 3. `deleteRepoBlocklist` – path parameter `repoId`; uses BasicAuth header.

## Rules

- Authentication: Include a BasicAuth header with valid credentials on each request.
- Idempotency: The `upsertRepoBlocklists` operation is idempotent; repeated calls with the same data produce the same result.
- Errors: The API returns standard HTTP error codes; no specific error details are documented.
