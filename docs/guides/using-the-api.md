# Using The API

MoteCloud API integrations should follow the same memory lifecycle used by agent integrations: prepare, work, capture, validate, and close.

This page is a public integration guide. Authenticated tenant-specific setup and credentials belong in hosted tenant documentation.

## Integration Flow

1. Identify the tenant or workspace context through the hosted product flow.
2. Prepare relevant context for the task.
3. Create or capture a task event when work begins.
4. Append meaningful observations during the task.
5. Ingest durable findings only after validation.
6. Close or summarize the session.

## Request Design

Good requests are explicit about task intent and scope. They should include enough description for retrieval to find relevant memory, while avoiding secrets or unnecessary personal data.

## Response Handling

Clients should treat prepared context as guidance, not as an unconditional source of truth. When context contains caveats, old information, or contradictions, the client or agent should reason carefully and validate before acting.

## Authentication

Use the authentication method provided by the hosted product or tenant setup. Do not publish tokens, credentials, signed requests, private tenant identifiers, or local development credentials in public docs, examples, issues, or benchmark artifacts.

## Public Reference Status

This repository currently provides a curated public API overview. A generated API specification should be published only after it is reviewed and sanitized for public scope.