# Agent Memory

Agent memory gives AI systems continuity across tasks without relying on a single long transcript.

MoteCloud's public agent-memory model is built around preparing context, recording working observations, and preserving validated knowledge.

## Recommended Lifecycle

1. Prepare relevant context for the task.
2. Capture the task or user request.
3. Append concise observations as the agent works.
4. Persist validated findings that should help future work.
5. Close the session with a compact summary.

This lifecycle keeps memory intentional. It avoids treating every temporary thought as durable knowledge.

## What Agents Should Capture

Agents should capture information that changes future behavior:

- Verified project conventions.
- User preferences that are safe to remember.
- Commands or workflows that were validated.
- Important decisions and their rationale.
- Failures that reveal a reusable lesson.

## What Agents Should Avoid Capturing

Agents should not store secrets, credentials, private keys, raw customer data, speculative claims, or information outside the current user's authorized scope.

Agents should also avoid saving noisy scratch work when a short summary would be more useful.

## Why Session Closure Matters

Closing a session gives future work a compact handoff. It helps separate temporary exploration from durable findings and gives later agents a clear path into what happened.