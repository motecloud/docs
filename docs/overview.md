# MoteCloud Overview

MoteCloud is memory infrastructure for agents and AI systems.

Modern agents need more than a prompt window. They need to remember durable facts, recover the right context at the right moment, preserve working-session observations, and respect boundaries between public knowledge, tenant-specific knowledge, and operator-only knowledge.

MoteCloud provides a structured memory layer for that work.

## What MoteCloud Helps With

- Durable memory for agent workflows.
- Context preparation before an agent starts a task.
- Working-session capture while an agent is exploring, coding, researching, or assisting a user.
- Public, tenant, and admin documentation boundaries.
- Retrieval patterns that combine semantic relevance with structured metadata and relationships.
- Benchmark publication surfaces for public evaluation material.

## Core Ideas

A memory item stores a useful observation, fact, procedure, or note. Metadata describes where it came from, why it matters, and how it should be used. Relationships connect related information so a future task can recover more than one isolated note.

Context priming prepares a compact, ranked set of relevant memories for a task. Agents use that context to avoid rediscovering known facts and to make better decisions inside a limited context window.

Working sessions capture short-lived observations as a task unfolds. Durable findings can be promoted when they are validated and likely to help future work.

## Documentation Surfaces

MoteCloud separates documentation into three broad scopes:

- Public docs for product concepts, public guides, benchmark methodology, and safe references.
- Tenant docs for authenticated users working inside a tenant.
- Admin docs for operators, monitoring, runbooks, and restricted operational material.

See [Privacy and documentation boundaries](concepts/privacy-and-boundaries.md) for the full public explanation.
