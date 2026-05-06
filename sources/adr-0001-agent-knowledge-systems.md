---
id: source.adr-0001-agent-knowledge-systems
pageType: source
title: ADR 0001 — Agent Knowledge Systems Rejected (Bonfires.ai, llm_wiki)
date: "2026-05-06"
authors: Genesis
sourceType: architecture-decision-record
entityType: source
confidence: 1.0
updatedAt: "2026-05-06"
tags:
  - knowledge-base
  - wiki
  - bonfires
  - llm-wiki
  - architecture
provenance:
  - source: source.github-regen-tribes
    path: docs/adr/0001-agent-knowledge-systems-rejected.md
    lines: "1-999"
    weight: 1.0
---

# ADR 0001 — Agent Knowledge Systems Rejected

**Status:** accepted  
**Date:** 2026-05-06  
**GitHub:** https://github.com/regentribes/genesis-zero-bot/blob/main/docs/adr/0001-agent-knowledge-systems-rejected.md

## Decision

Reject Bonfires.ai and llm_wiki. Adopt OpenClaw's `memory-wiki` plugin with Radicle P2P sync.

## Bonfires.ai — Rejected

- Subscription barrier
- No offline P2P mode
- Proprietary knowledge graph
- Overlaps with genesis-brain (SurrealDB)

## llm_wiki — Rejected

- Desktop-only (Electron app)
- No server/API mode
- No P2P sync
- Karpathy pattern right, implementation wrong

## Adopted

- **memory-wiki** (OpenClaw bundled) — agent-native, Obsidian-compatible
- **Radicle** — P2P sync via git-radicle protocol

See also: [[concepts/adr-0000-oad-workflow-grammar|ADR 0000]], [[concepts/adr-0002-ame-metonymic-activation|ADR 0002]]

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By

- [[concepts/adr-0001-agent-knowledge-systems|ADR 0001 — Agent Knowledge Systems Rejected]]
<!-- openclaw:wiki:related:end -->
