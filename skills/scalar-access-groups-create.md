---
name: scalar-access-groups-create
description: Create a new access group and add members to it.
api: openapi/scalar-openapi.json
operations:
- postV1AccessGroups
- postV1AccessGroupsUidEmails
- getV1AccessGroupsSlug
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/scalar-openapi.json ; every operationId checked against the contract
---

# scalar-access-groups-create

Create a new access group and add members to it.

## Steps

1. 1. Use `postV1AccessGroups` with the request body fields required to define the access group.
2. 2. Use `postV1AccessGroupsUidEmails` with the `uid` path parameter of the created group and the request body containing email addresses to add.
3. 3. Optionally, retrieve the created group with `getV1AccessGroupsSlug` using the `slug` path parameter.

## Rules

- Authentication: Include a `Authorization: Bearer <token>` header (BearerAuth).
- Pagination: When listing groups, use `offset` and `size` query parameters.
- Idempotency: Not applicable; no idempotency keys are defined for these operations.
- Errors: The API does not specify custom error codes; standard HTTP error responses apply.
