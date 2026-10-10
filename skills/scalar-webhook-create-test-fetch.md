---
name: scalar-webhook-create-test-fetch
description: Create a webhook, send a test payload, and retrieve its delivery records.
api: openapi/scalar-openapi.json
operations:
- postV1Webhooks
- postV1WebhooksUidTest
- getV1WebhooksUidDeliveries
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/scalar-openapi.json ; every operationId checked against the contract
---

# scalar-webhook-create-test-fetch

Create a webhook, send a test payload, and retrieve its delivery records.

## Steps

1. 1. Call `postV1Webhooks` with the required request body fields (as defined in the API contract) and include the Bearer authentication header.
2. 2. Call `postV1WebhooksUidTest` with the `uid` path parameter of the created webhook and include the Bearer authentication header.
3. 3. Call `getV1WebhooksUidDeliveries` with the same `uid` path parameter, include the Bearer authentication header, and use the `offset` and `size` query parameters for pagination.

## Rules

- Authentication: Provide a Bearer token in the `Authorization` header for all requests.
- Pagination: The `getV1WebhooksUidDeliveries` operation supports `offset` and `size` query parameters.
- Idempotency: Not applicable; no idempotency keys are defined for these operations.
- Errors: The API does not specify custom error codes; standard HTTP error responses apply.
