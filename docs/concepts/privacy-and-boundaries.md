# Privacy And Documentation Boundaries

MoteCloud documentation is split by audience and sensitivity.

The goal is simple: public users should get useful product and integration information, authenticated tenants should get their own operational guidance, and administrators should get restricted runbooks and monitoring material without leaking those details to the public web.

## Public Documentation

Public documentation can include:

- Product overview and concepts.
- Public quickstarts and integration guides.
- Public API and MCP usage guidance.
- Public benchmark methodology and published results.
- Public changelog entries.
- Responsible disclosure process.

Public documentation must not include tenant data, private repository links, admin runbooks, internal security evidence, credentials, private benchmark artifacts, internal deployment procedures, or unpublished strategy.

## Tenant Documentation

Tenant documentation is for authenticated users. It can explain tenant-scoped onboarding, usage patterns, account workflows, and tenant-specific product guidance.

Tenant docs should not include admin-only runbooks, internal monitoring details, private credentials, or other tenants' information.

## Admin Documentation

Admin documentation is for operators. It can include runbooks, restricted monitoring explanations, incident procedures, and internal operational references.

Admin documentation is not mirrored into this public repository.

## Repository Link Policy

Public documentation should only link to public repositories in the `motecloud` GitHub organization. Links to private source repositories or internal file paths should be removed or replaced with curated public documentation.

## Benchmark Boundary

Benchmark methodology and published results can be public. Internal tuning notes, unreleased datasets, private artifact paths, proprietary scoring thresholds, and tenant-specific evaluation data should remain private.
