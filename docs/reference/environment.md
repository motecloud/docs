# Environment Reference

This page describes public configuration principles for MoteCloud integrations.

It does not publish private deployment settings, internal environment variables, production credentials, local development secrets, or tenant-specific values.

## Public Configuration Principles

- Keep credentials out of source control.
- Use tenant-specific setup instructions from authenticated documentation.
- Use placeholders in public examples.
- Separate public docs configuration from admin operations configuration.
- Rotate credentials through the hosted product or approved operational process.

## Example Placeholder Style

Public examples should use placeholder names such as:

```text
MOTECLOUD_BASE_URL=https://example.motecloud.io
MOTECLOUD_TENANT_ID=example-tenant
MOTECLOUD_ACCESS_TOKEN=replace-with-your-token
```

These placeholders are illustrative only.

## What Not To Publish

Do not publish real access tokens, private keys, signed credentials, production tenant identifiers, private endpoint URLs, billing provider secrets, local development override values, or internal service topology.