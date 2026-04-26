# MCP Tools Reference

This page describes public MCP tool categories for MoteCloud integrations.

Tool names and availability can vary by hosted configuration and tenant permissions. Tenant-specific setup belongs in authenticated documentation.

## Context Tools

Context tools prepare relevant memories for a task. They help agents start with the right background instead of rediscovering known project facts.

## Search And Retrieval Tools

Search and retrieval tools find memory items and fetch specific records. Expansion tools can discover related context through memory relationships.

## Task Capture Tools

Task capture tools record the start of a meaningful user request or unit of work.

## Session Tools

Session tools open a working session, append observations, flush intermediate state, and close the session with a summary.

## Ingestion Tools

Ingestion tools persist validated durable knowledge. They should be used carefully and should not store secrets, raw tenant data, speculative claims, or public-inappropriate material.

## Restricted Tools

Admin-only maintenance tools, internal diagnostics, billing internals, security operations, and local development utilities should not be documented as public MCP tools.