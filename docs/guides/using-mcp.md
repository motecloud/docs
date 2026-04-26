# Using MoteCloud With MCP

MoteCloud can be exposed to agents through MCP so they can prepare context, search memory, capture tasks, stream session observations, and persist durable findings.

This page describes the public integration model. Tenant-specific setup belongs in authenticated tenant documentation.

## Typical Tool Categories

A MoteCloud MCP integration usually includes tools for:

- Preparing relevant context for a task.
- Searching existing memory.
- Retrieving or expanding a memory item.
- Capturing a task or user request.
- Opening, appending to, and closing a working session.
- Ingesting validated durable knowledge.

## Recommended Agent Pattern

Before significant work, an agent should prepare context and open a working session. During the task, it should append concise observations after meaningful discoveries, decisions, errors, and validation results. At the end, it should close the session and persist any durable findings that will help future work.

## What To Avoid

Do not store secrets, credentials, private keys, access tokens, session cookies, tenant data, or speculative findings as durable public knowledge.

Do not use public documentation as a place for admin-only runbooks, private infrastructure details, or internal security evidence.

## Tenant Setup

Hosted tenant setup, credentials, and account-specific configuration are provided through authenticated product surfaces. Public docs should link users to tenant docs rather than publishing tenant-specific details here.
