# Retrieval And Graphs

MoteCloud uses retrieval and relationships to help agents find useful context.

This page describes the public product concept. It does not document private ranking formulas, internal thresholds, benchmark-tuned parameters, or proprietary implementation details.

## Retrieval

Retrieval finds memory items that are likely to matter for a task. A useful retrieval system can consider meaning, metadata, recency, scope, and task fit.

The goal is not to return everything. The goal is to return enough relevant context for an agent to make better decisions inside a limited context window.

## Graph Relationships

Memory items become more useful when they are connected. Relationships can show that one item supports, updates, depends on, or contradicts another.

Graph expansion helps an agent recover nearby context that may not match the exact wording of the task.

## Contradictions

Contradictions are useful when handled carefully. If two memories conflict, an agent should see enough context to notice the conflict and avoid blindly following stale or disputed information.

## Public Boundary

Public docs can explain retrieval and graph concepts. They should not publish internal scoring weights, proprietary ranking logic, private benchmark tuning, tenant data, or operator-only diagnostic details.