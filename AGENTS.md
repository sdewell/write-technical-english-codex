# AGENTS.md — write-technical-english-codex

> **Purpose:** Codex's entry point for write-technical-english-codex. **Use:** Codex reads this first; it points at CLAUDE.md for the repo's conventions and holds Codex-only items (sandbox specifics, Codex tooling). Codex reviews and owns this file.

The repo's conventions and gotchas are in [CLAUDE.md](CLAUDE.md); read it
first.

## Codex-only

The installable package is
[`.agents/skills/write-technical-english`](.agents/skills/write-technical-english/):
`SKILL.md`, `references/`, and `agents/openai.yaml` (Codex interface
metadata). `agents/openai.yaml` sets `allow_implicit_invocation: false`, so
the skill never fires on ordinary conversation — install and invoke it with
`$write-technical-english` per the README. Changing that flag changes
behavior for every installation; treat it as a packaging decision, not a
routine edit.
