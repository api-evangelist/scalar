---
name: scalar-payment-start-flow
description: Initiate a payment, process it via Stripe, and start billing for the transaction.
api: openapi/scalar-openapi.json
operations:
- postPaymentStart
- postStripe
- postPaymentBillingStart
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/scalar-openapi.json ; every operationId checked against the contract
---

# scalar-payment-start-flow

Initiate a payment, process it via Stripe, and start billing for the transaction.

## Steps

1. 1. Call `postPaymentStart` with the required request body fields and include the `Authorization: Bearer <token>` header.
2. 2. Call `postStripe` with the Stripe payment details in the request body and include the `Authorization: Bearer <token>` header.
3. 3. Call `postPaymentBillingStart` with billing information in the request body and include the `Authorization: Bearer <token>` header.

## Rules

- All requests must include an `Authorization: Bearer <token>` header (BearerAuth).
- No pagination is required for these operations.
- There is no rate limit; on exhaustion the API returns no specific HTTP status.
