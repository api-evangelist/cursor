---
name: cursor-spend-management
description: Manage team spend by setting a user spend limit and retrieving spending data.
api: openapi/cursor-spend-api-openapi.yml
operations:
- setUserSpendLimit
- getSpend
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/cursor-spend-api-openapi.yml ; every operationId checked against the contract
---

# cursor-spend-management

Manage team spend by setting a user spend limit and retrieving spending data.

## Steps

1. 1. Call `setUserSpendLimit` with the required body fields for the user and limit.
2. 2. Call `getSpend` with any required request body parameters to retrieve current spending data.

## Rules

- Auth: Include BasicAuth credentials in the request.
- No rate limit is defined; exhaustion returns no specific HTTP status.
