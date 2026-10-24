# Brain Append

> **Tri-Platform Agent Skill** for Claude Desktop / Code, Grok CLI, and Google Antigravity / Gemini.  
> Append Dated Notes & Progress to Existing Second Brain Memories — Directly appends dated progress notes, research logs, and task updates to existing Second Brain memories without overwriting original content.

---

## Overview

`brain-append` provides standardized capabilities across conversational AI platforms:
- Targeted memory appending by unique memory ID (/brain-append <id> <text>).
- Automated timestamping and delimiter formatting for appended sections.
- User-authorization conveyance on direct slash command execution.
- Tri-platform NTFS junctions connecting Claude, Grok, and Antigravity.
- Standard documentation suite: SKILL.md, HOW_TO_USE.txt, IMPLEMENTATION_PLAN.md, and README.md.

---

## Tri-Platform Architecture

Zero duplicate code across platforms. Canonical source resides in `.agents`:
- **Canonical Source**: `C:\Users\<you>\.agents\skills\brain-append`
- **Claude**: `C:\Users\<you>\.claude\skills\brain-append` (NTFS Junction)
- **Grok**: `C:\Users\<you>\.grok\skills\brain-append` (NTFS Junction)
- **Antigravity**: `C:\Users\<you>\.gemini\config\skills\brain-append` (NTFS Junction)

---

## Documentation Suite

- [`HOW_TO_USE.txt`](HOW_TO_USE.txt): Standardized user guide and prompt templates.
- [`IMPLEMENTATION_PLAN.md`](IMPLEMENTATION_PLAN.md): Feature checklist and roadmap.
- [`App Changes Tracker.html`](App%20Changes%20Tracker.html): Interactive visual version log.
- [`SKILL.md`](SKILL.md): Agent system instructions and triggers.
