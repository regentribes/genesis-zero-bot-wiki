---
id: source.adr-0000-oad-workflow-grammar
pageType: source
title: ADR 0000 — Integral OAD Workflow Grammar Over Full Integral Stack
date: "2026-05-06"
authors: Genesis
sourceType: architecture-decision-record
entityType: source
confidence: 1.0
updatedAt: "2026-05-06"
tags:
  - integral
  - OAD
  - workflow-grammar
  - architecture
provenance:
  - source: source.github-regen-tribes
    path: docs/adr/0000-oad-workflow-grammar-over-full-integral-stack.md
    lines: "1-999"
    weight: 1.0
---

# ADR 0000 — Integral OAD Workflow Grammar Over Full Integral Stack

**Status:** accepted  
**Date:** 2026-05-06  
**RID:** rad:zYhRVEu5Zh85vcwvmxkZHJNQxn6X  
**GitHub:** https://github.com/regentribes/genesis-zero-bot/blob/main/docs/adr/0000-oad-workflow-grammar-over-full-integral-stack.md

## Decision

Adopt OAD's **workflow grammar** — the structural process — without adopting the full Integral stack. Defer the material coefficient engine and ITC to Phase 2.

## Key Points

- M1 (intake) → M2 (collaborative workspace) → M3–M7 (analysis) → M8 (optimization) → M9 (certification) → M10 (knowledge commons)
- Maps to existing tools: git for M2, SurrealDB for M10
- Blocking constraints: no material coefficient database, no COS/ITC/FRS, no constitutional governance, scale mismatch
- Phase-gated path: Phase 1 (now), Phase 2 (3–6 months), Phase 3 (6–12 months)

## Rejected Options

- **Bonfires.ai**: subscription cost, no offline P2P mode
- **llm_wiki**: desktop-only, not agent-integratable

## Adopted

OAD workflow grammar only (M1/M2 → M9/M10 loop)

See also: [[concepts/adr-0001-agent-knowledge-systems|ADR 0001]], [[concepts/adr-0002-ame-metonymic-activation|ADR 0002]]

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By

- [[concepts/adr-0000-oad-workflow-grammar|ADR 0000 — Integral OAD Workflow Grammar]]
<!-- openclaw:wiki:related:end -->
