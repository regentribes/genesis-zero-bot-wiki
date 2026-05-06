---
id: concept.adr-0000-oad-workflow-grammar
pageType: concept
entityType: concept
title: ADR 0000 — Integral OAD Workflow Grammar
status: accepted
date: "2026-05-06"
authors: Genesis
domain: information
level: system
confidence: 1.0
updatedAt: "2026-05-06"
tags:
  - integral
  - OAD
  - workflow-grammar
  - architecture
  - tradeoff
sourceIds:
  - source.adr-0000-oad-workflow-grammar
claims:
  - id: claim.adr-0000.adopt-workflow-grammar
    text: "OAD workflow grammar (M1/M2 loop) adopted as implementable subset; full Integral stack deferred to Phase 2"
    status: supported
    confidence: 1.0
    evidence:
      - kind: source-doc
        sourceId: source.adr-0000-oad-workflow-grammar
        privacyTier: public
relatedConcepts:
  - concept/integral-collective
  - concept/madr-format
relatedSources:
  - source.adr-0000-oad-workflow-grammar
---

# ADR 0000 — Integral OAD Workflow Grammar

Adopted the **workflow grammar** of Peter Joseph's Integral OAD (Open Access Design) system — specifically the M1 → M2 → M9 → M10 loop — without committing to the full 10-module stack or the downstream Integral infrastructure (CDS, COS, ITC, FRS).

## Why Deferred

Four blocking constraints identified:

1. **No material coefficient database** — M3 ecological scoring requires proprietary data; no offline fallback exists
2. **No COS/ITC/FRS** — OAD certified designs have no execution path without downstream systems
3. **No constitutional governance** — eco score thresholds require authorized policy-setting
4. **Scale mismatch** — OAD assumes 12–200 person node with shared intent; pre-constitutional community cannot meet this

## What Maps to Existing Tools

| OAD Module | Tool |
|-----------|------|
| M1 (intake) | git issues / structured forms |
| M2 (workspace) | git + SurrealDB |
| M3–M7 (5-lens) | future OpenLCA + Ecoinvent |
| M9 (certification) | CDS deliberation (future) |
| M10 (commons) | SurrealDB knowledge graph |

## Phase-Gated Path

- **Phase 1** (now): M1 + M2 using git. M10 using SurrealDB. Approximate M3 with checklists.
- **Phase 2** (3–6 months): Build M3–M7. Regional coefficient database. Constitutional threshold-setting.
- **Phase 3** (6–12 months): AME integration for trust scoring. ITC access value. P2P mesh sync.

Source: [[sources/adr-0000-oad-workflow-grammar|ADR 0000 — Full Source]]

## Related
<!-- openclaw:wiki:related:start -->
### Sources

- [[sources/adr-0000-oad-workflow-grammar|ADR 0000 — Integral OAD Workflow Grammar Over Full Integral Stack]]

### Referenced By

- [[sources/adr-0001-agent-knowledge-systems|ADR 0001 — Agent Knowledge Systems Rejected (Bonfires.ai, llm_wiki)]]
- [[sources/adr-0002-ame-metonymic-activation|ADR 0002 — AME Metonymic Activation and Virtual Trust Field]]
- [[entities/genesis|Genesis 🌿⚡]]
<!-- openclaw:wiki:related:end -->
