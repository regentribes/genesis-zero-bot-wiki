---
id: concept.adr-0005-rag-agent-memory-for-integral-stack
pageType: concept
entityType: concept
title: ADR 0005 — RAG and Agent Memory in the Integral Stack
status: proposed
date: 2026-05-06
authors: Genesis
domain: information
level: system
confidence: 1.0
updatedAt: 2026-05-06
tags:
  - adr
  - architecture
sourceIds:
  - source.adr-0005-rag-agent-memory-for-integral-stack
claims:
  - id: claim.adr-0005.decision
    text: "Three-pattern assignment: Agent Memory for AME/ITC member context, RAG for CDS deliberation records, LLM Wiki for M10 domain synthesis"
    status: supported
    confidence: 1.0
    evidence:
      - kind: source-doc
        sourceId: source.adr-0005-rag-agent-memory-for-integral-stack
        privacyTier: public
relatedConcepts:
  - concept/adr-0004-llm-wiki-pattern
  - concept/adr-0000-oad-workflow-grammar
  - concept/adr-0006-data-quality-governance
relatedSources:
  - source.adr-0005-rag-agent-memory-for-integral-stack
---
# ADR 0005 — RAG and Agent Memory in the Integral Stack

**Status:** proposed  
**Date:** 2026-05-06  
**ADR:** [[source.0005-rag-agent-memory-for-integral-stack|Full Document]]  
**GitHub:** https://github.com/regentribes/genesis-zero-bot/blob/main/docs/adr/0005-rag-agent-memory-for-integral-stack.md

## Key Decision

Three-pattern assignment: Agent Memory for AME/ITC member context, RAG for CDS deliberation records, LLM Wiki for M10 domain synthesis

## See Also

- [[concept.adr-0004-llm-wiki-pattern-for-integral-knowledge-commons|ADR 0004 — LLM Wiki Pattern]]
- [[adr-0000-oad-workflow-grammar|ADR 0000 — OAD Workflow Grammar]]
- [[concept.adr-0006-data-quality-governance-layer|ADR 0006 — Data Quality Governance]]

## Related

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By

- [[concepts/adr-0003-integral-non-transferable-value-model|ADR 0003 — Integral Non-Transferable Value Model vs Percentage-Based Paywall]]
- [[concepts/adr-0004-llm-wiki-pattern-for-integral-knowledge-commons|ADR 0004 — LLM Wiki Pattern for Integral Knowledge Commons (M10)]]
- [[concepts/adr-0006-data-quality-governance-layer|ADR 0006 — Data Quality and Governance for Knowledge Layer]]
<!-- openclaw:wiki:related:end -->
