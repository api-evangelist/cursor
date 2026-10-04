---
name: cursor-remove-team-member
description: Remove a specific member from a team after retrieving the list of current team members.
api: openapi/cursor-members-api-openapi.yml
operations:
- getTeamMembers
- removeTeamMember
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/cursor-members-api-openapi.yml ; every operationId checked against the contract
---

# cursor-remove-team-member

Remove a specific member from a team after retrieving the list of current team members.

## Steps

1. 1. Retrieve the list of team members using the `getTeamMembers` operation. No request body or special headers are required beyond authentication.
2. 2. Identify the member to remove and call the `removeTeamMember` operation. Provide the required member identifier in the request payload (field name not specified in the documentation).

## Rules

- Authentication: Include a BasicAuth header as defined by the API.
- Idempotency: Not specified; treat each `removeTeamMember` call as a single action.
