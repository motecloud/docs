# Public Status

MoteCloud's public status surface helps users understand service availability and recent platform health.

This page explains public status concepts. Internal monitoring dashboards, alert rules, incident runbooks, and backend operational details are restricted to admin documentation.

## Public Status Can Include

- Current service state.
- Recent uptime or availability summaries.
- Public incident updates.
- High-level latency or reliability trends.
- Maintenance notices.

## Public Status Should Not Include

- Internal infrastructure topology.
- Private logs or traces.
- Admin runbooks.
- Security evidence.
- Tenant-specific operational data.
- Backend credentials or private endpoints.

## How To Read Status

Use public status as a high-level signal. If an issue appears tenant-specific, use authenticated support or tenant documentation rather than public issue threads.

## Historical Data

Historical graphs should make the measured period, metric definition, and sampling caveats clear. Public graphs should be aggregated and safe for external readers.