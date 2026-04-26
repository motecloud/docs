# Context Priming

Context priming is the process of preparing useful memory before an agent begins work.

An agent usually has a limited context window. If it starts from an empty prompt, it may rediscover decisions, repeat mistakes, or miss project-specific constraints. Context priming gives the agent a compact set of relevant memories so it can begin with better orientation.

## What A Prepared Context Should Do

A good context block should:

- Match the current task.
- Prefer verified and durable facts over noisy scratch notes.
- Include relevant constraints, conventions, and prior decisions.
- Respect public, tenant, and admin boundaries.
- Stay compact enough to leave room for the actual task.

## Working Memory And Durable Memory

Working memory captures observations during a task. Durable memory stores findings that are likely to be useful later.

Not every observation should become durable. Good durable memories are validated, reusable, and specific enough to guide a future task.

## Agent Workflow

A typical agent workflow looks like this:

1. Prepare context for the task.
2. Capture the task as a working-memory event.
3. Append concise observations after meaningful discoveries or decisions.
4. Persist validated durable findings when they will help future work.
5. Close the session with a short summary.

## Why It Matters

Context priming helps agents work with continuity. It improves handoffs, reduces repeated discovery, and gives long-running projects a memory layer that is more structured than a chat transcript.
