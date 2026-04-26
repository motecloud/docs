# Error Guide

This page describes common public error categories and how to respond to them.

## Authentication Error

The request is missing valid authentication or uses credentials that are no longer accepted.

Check the hosted tenant documentation for the correct setup path. Do not paste credentials into public issues.

## Authorization Error

The authenticated user or integration does not have permission for the requested scope.

Confirm tenant membership, role, and requested operation.

## Missing Tenant Context

The request does not identify an active tenant or workspace context.

Use the hosted product flow to select or configure the correct tenant.

## Invalid Request

The request body is missing required information or includes invalid fields.

Review the public guide for the workflow you are using and check that examples use placeholders rather than real sensitive values.

## Rate Limit Or Quota

The request exceeded an allowed rate or quota.

Retry with backoff where appropriate and review tenant plan or usage guidance in authenticated documentation.

## Temporary Service Unavailable

The service may be temporarily unavailable.

Check the public status page and retry later. If the issue persists, use the support path.