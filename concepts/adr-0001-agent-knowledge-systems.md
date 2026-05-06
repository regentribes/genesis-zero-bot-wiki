---
id: concept.adr-0001-agent-knowledge-systems
pageType: concept
entityType: concept
title: ADR 0001 — Agent Knowledge Systems Rejected
status: accepted
date: "2026-05-06"
authors: Genesis
domain: information
level: system
confidence: 1.0
updatedAt: "2026-05-06"
tags:
  - knowledge-base
  - wiki
  - bonfires
  - llm-wiki
  - memory-wiki
  - radicle
  - architecture
  - tradeoff
sourceIds:
  - source.adr-0001-agent-knowledge-systems
claims:
  - id: claim.adr-0001.rejected-bonfires-llmwiki
    text: "Bonfires.ai and llm_wiki both rejected as unsuitable for offline-first P2P agent-resident knowledge management"
    status: supported
    confidence: 1.0
    evidence:
      - kind: source-doc
        sourceId: source.adr-0001-agent-knowledge-systems
        privacyTier: public
relatedConcepts:
  - concept/memory-wiki
  - concept/karpathy-llm-wiki
  - concept/radicle-p2p
  - concept/surreal-db
---

# ADR 0001 — Agent Knowledge Systems Rejected

Rejected two candidate tools for LLM wiki / knowledge base management. Adopted OpenClaw's bundled `memory-wiki` plugin with Radicle P2P sync.

## Rejected: Bonfires.ai

- Subscription cost — incompatible with budget-constrained community
- No offline P2P mode — server-hosted, assumes live internet
- Proprietary knowledge graph — cannot export for P2P sync
- Overlaps with existing `genesis-brain` (SurrealDB semantic graph)

## Rejected: llm_wiki

- Desktop-only (Electron) — no server/API mode
- Requires manual app running — not headless-agent integrable
- No P2P sync mechanism
- Karpathy LLM Wiki pattern is the **right idea, wrong implementation for agents**

## Adopted: memory-wiki + Radicle

| Property | Bonfires | llm_wiki | memory-wiki |
|----------|----------|----------|-------------|
| Offline-first | no | yes | yes |
| Agent-integratable | no | no | yes |
| P2P sync | no | no | yes (Radicle) |
| Obsidian-compatible | no | yes | yes |
| Structured claims | no | no | yes |

Source: ADR 0001 — Full Source

## Related

## Related
<!-- openclaw:wiki:related:start -->
### Sources

- [[sources/adr-0001-agent-knowledge-systems|ADR 0001 — Agent Knowledge Systems Rejected (Bonfires.ai, llm_wiki)]]

### Referenced By

- [[sources/adr-0000-oad-workflow-grammar|ADR 0000 — Integral OAD Workflow Grammar Over Full Integral Stack]]
- [[sources/adr-0002-ame-metonymic-activation|ADR 0002 — AME Metonymic Activation and Virtual Trust Field]]
- [[entities/genesis|Genesis 🌿⚡]]
<!-- openclaw:wiki:related:end -->
