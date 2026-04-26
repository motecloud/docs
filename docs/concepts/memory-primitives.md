# Memory Primitives

MoteCloud stores memory as structured units of useful information.

The public vocabulary below describes the model without exposing private implementation details or internal scoring behavior.

## Memory Item

A memory item is a compact piece of information that may help a future task. It can describe a fact, procedure, user preference, project convention, working observation, or validated decision.

Good memory items are specific, reusable, and tied to enough context that an agent can understand why they matter.

## Metadata

Metadata describes how a memory item should be interpreted. It can include source, scope, category, confidence, freshness, or task relevance.

Metadata helps retrieval systems distinguish durable knowledge from temporary notes and public information from tenant- or admin-scoped information.

## Scope

Scope controls where memory should be used.

Common public-facing scopes include:

- Public knowledge: safe to expose in public documentation or examples.
- Tenant knowledge: available to authenticated users in a tenant context.
- Operator knowledge: restricted to administrators and operational workflows.

Public documentation should describe scopes, but it should not publish restricted memory content.

## Session

A session captures work as it unfolds. Agents can append discoveries, decisions, validation results, and errors during a task. At the end, the session can be summarized so future work has continuity.

## Durable Finding

A durable finding is a memory item that has been validated and is likely to help future tasks. Durable findings should be concise and practical.

## Relationship

Relationships connect memory items. A relationship can show that two items are related, that one item supports another, or that one item contradicts another.

Relationships help agents recover context that would be hard to find through isolated keyword matching.