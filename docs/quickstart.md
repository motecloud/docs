# Quickstart

This quickstart explains the public path for getting oriented with MoteCloud.

## 1. Understand The Model

MoteCloud gives agents a memory workflow:

1. Prepare context for the task.
2. Capture the task or user request.
3. Append meaningful observations during the work.
4. Persist validated findings that should survive across sessions.
5. Close the working session with a compact summary.

This workflow keeps memory useful without turning every temporary detail into durable knowledge.

## 2. Choose An Integration Path

MoteCloud can be used through hosted product surfaces and integration layers such as MCP. Public docs in this repository focus on concepts and safe integration guidance.

Authenticated tenant-specific details belong in the hosted tenant documentation at `/account/docs` after sign-in.

## 3. Start With Public Guides

Recommended order:

1. Read the [overview](overview.md).
2. Read [memory primitives](concepts/memory-primitives.md).
3. Read [context priming](concepts/context-priming.md).
4. Read [agent memory](concepts/agent-memory.md).
5. Read [using MoteCloud with MCP](guides/using-mcp.md) or [using the API](guides/using-the-api.md).
6. Review [privacy and documentation boundaries](concepts/privacy-and-boundaries.md).
7. Review [benchmark overview](benchmarks/overview.md) if you are evaluating behavior.

## Public Reference

Use the curated reference pages for public integration concepts:

- [API reference overview](reference/api.md)
- [MCP tools reference](reference/mcp-tools.md)
- [Environment reference](reference/environment.md)
- [Error guide](reference/errors.md)

## 4. Keep Boundaries Clear

Do not place secrets, private repository links, tenant identifiers, admin runbooks, internal strategy, or security evidence in public documentation, issues, examples, or benchmark submissions.

## 5. Get Help

Use public documentation issues for docs feedback. Use the hosted product support path for account-specific questions. Use private security reporting for vulnerabilities.
