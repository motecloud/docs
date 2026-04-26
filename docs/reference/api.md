# API Reference Overview

This page is a curated public overview of MoteCloud API concepts.

It is not a complete generated API specification. Generated specifications should be published only after review for public scope.

## Public API Categories

Public-facing API documentation can cover:

- Context preparation.
- Memory search and retrieval.
- Task capture.
- Session open, append, flush, and close flows.
- Durable memory ingestion for validated findings.
- Public status and documentation surfaces.

## Restricted API Categories

Public documentation should not expose admin-only routes, internal diagnostics, private billing internals, tenant-specific operations, security evidence, or local development-only endpoints.

## Request Guidance

Requests should be scoped to the task and should avoid secrets or unnecessary sensitive data. Use placeholder values in public examples.

## Response Guidance

Clients should handle empty results, conflicting memories, authorization errors, rate limits, and temporary service unavailability.

## Future Specification

A public OpenAPI or similar specification can be added when it is generated from a sanitized public surface and reviewed before publication.