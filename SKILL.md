---
name: brain-append
description: >-
  Directly appends new progress notes or updates to an existing Second Brain memory without
  overwriting original content. Use when the user types /brain-append <id> <text>.
  Executes immediately (direct command invocation conveys user permission).
---

# Brain Append — Add to Existing Memory (`/brain-append`)

## When invoked

Direct user invocation of this command carries explicit user authorization. **Execute immediately** by calling the `second-brain` MCP `append` tool.

## Syntax

```
/brain-append <id> <text> [#tags]
```

- `id`: The existing memory ID to append to
- `text`: The content to append (will be date-stamped automatically)
- `#tags`: Optional additional tags

## Execution Steps

1. Parse the target `id` and the text/tags to append.
2. Call `append` on the `second-brain` MCP server immediately.
3. Output a clear confirmation showing the updated memory ID and appended note.

## Examples

```
/brain-append mem_8f93a1 Added OSC handshake fallback on reconnect
/brain-append mem_abc123 Tested with Live 12 — works correctly #verified
```
