# Scalar

Scalar is an open-source API platform built around the OpenAPI standard. It provides interactive API documentation (API References), an offline-first API client, a centralized API registry for managing OpenAPI documents and Spectral rules, and automated SDK generation for TypeScript, Python, Go, PHP, Java, and Ruby. Used by teams at SmartBear, Microsoft ASP.NET, and 30+ framework ecosystems. 14.9k GitHub stars, MIT licensed.

**URL:** [https://scalar.com/](https://scalar.com/)
**GitHub:** [https://github.com/scalar/scalar](https://github.com/scalar/scalar)

**Type:** Company (API Platform)
**Tags:** API Client, API Documentation, API References, Code Generation, Developer Tools, OpenAPI, Registry, SDKs, Swagger

## Products / APIs

### Scalar API References
Modern, interactive API documentation rendered from OpenAPI and Swagger specifications. Features multiple themes, dark mode, mobile responsiveness, built-in search, and an embedded API client. Supports OpenAPI 3.0 and 3.1, $ref resolution, and 30+ framework integrations.

- **Getting Started:** [https://scalar.com/products/api-references/getting-started](https://scalar.com/products/api-references/getting-started)
- **Documentation:** [https://guides.scalar.com/scalar/scalar-api-references/getting-started](https://guides.scalar.com/scalar/scalar-api-references/getting-started)
- **npm:** [@scalar/api-reference](https://www.npmjs.com/package/@scalar/api-reference)

### Scalar API Client
Fully open-source, offline-first REST API client built on the OpenAPI standard. Supports collections, environments, pre/post-response scripting, test results, and collection runners. Available for macOS, Windows, Linux, and browser.

- **Getting Started:** [https://scalar.com/products/api-client/getting-started](https://scalar.com/products/api-client/getting-started)
- **Web App:** [https://client.scalar.com/](https://client.scalar.com/)

### Scalar Docs
Documentation platform for creating and publishing developer documentation synchronized with APIs and code. Supports WYSIWYG editing, Markdown/MDX from repositories, OpenAPI-generated references, and Git Sync with CI/CD integration.

- **Getting Started:** [https://scalar.com/products/docs/getting-started](https://scalar.com/products/docs/getting-started)
- **Portal:** [https://docs.scalar.com/](https://docs.scalar.com/)

### Scalar Registry
Centralized management and versioning of OpenAPI Documents, JSON Schemas, and Spectral Rules with deep Git integration. Single source of truth for API definitions with CLI and GitHub Actions support.

- **Getting Started:** [https://scalar.com/products/registry/getting-started](https://scalar.com/products/registry/getting-started)
- **Documentation:** [https://guides.scalar.com/scalar/scalar-registry/getting-started](https://guides.scalar.com/scalar/scalar-registry/getting-started)

### Scalar SDKs
Automated type-safe client library generation from OpenAPI specifications for TypeScript, Python, Go, PHP, Java, and Ruby. Includes automated GitHub workflows, code samples, full OpenAPI auth support, and webhook support. $100/month per language.

- **Getting Started:** [https://scalar.com/products/sdks/getting-started](https://scalar.com/products/sdks/getting-started)
- **Pricing:** [https://guides.scalar.com/scalar/pricing](https://guides.scalar.com/scalar/pricing)

### Scalar CLI
Command-line interface for managing OpenAPI files, generating documentation, running mock servers, validating specs, and publishing to the Scalar Registry.

- **Documentation:** [https://guides.scalar.com/scalar/scalar-cli/getting-started](https://guides.scalar.com/scalar/scalar-cli/getting-started)
- **npm:** [@scalar/cli](https://www.npmjs.com/package/@scalar/cli)

## Artifacts

### Spectral Rules
- [Scalar Rules](rules/scalar-rules.yml) — Spectral ruleset enforcing OpenAPI conventions: Title Case summaries, operationId presence, kebab-case paths, response definitions, and schema descriptions.

### JSON Schema
- [OpenAPI Document Schema](json-schema/scalar-openapi-document-schema.json) — Schema for an OpenAPI document managed in the Scalar Registry, including documentation and SDK generation configuration.

### JSON Structure
- [OpenAPI Document Structure](json-structure/scalar-openapi-document-structure.json) — Structural documentation for Scalar Registry OpenAPI document entries.

### JSON-LD Context
- [Scalar Context](json-ld/scalar-context.jsonld) — Linked data context for the Scalar API platform vocabulary.

### Vocabulary
- [Scalar Vocabulary](vocabulary/scalar-vocabulary.yml) — Domain vocabulary covering API Registry, API Reference, SDK Generation, Spectral, Collections, Mock Server, and more.

### Examples
- [Registry Publish Example](examples/scalar-registry-publish-example.json) — Publishing an OpenAPI document to the Scalar Registry via CLI.
- [API Reference Config Example](examples/scalar-api-reference-config-example.json) — Embedding Scalar API References in an HTML page.
- [SDK Generation Workflow](examples/scalar-sdk-generation-example.json) — GitHub Actions workflow for automated TypeScript SDK generation.

## Common Resources

- [Scalar Documentation](https://guides.scalar.com/scalar/introduction)
- [Scalar Pricing](https://guides.scalar.com/scalar/pricing)
- [Scalar Dashboard](https://dashboard.scalar.com/)
- [Scalar Blog](https://scalar.com/blog)
- [Scalar Discord](https://discord.gg/scalar)
- [Scalar Changelog](https://github.com/scalar/scalar/releases)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
