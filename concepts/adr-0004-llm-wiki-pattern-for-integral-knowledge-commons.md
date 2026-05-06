---
id: concept.adr-0004-llm-wiki-pattern-for-integral-knowledge-commons
pageType: concept
entityType: concept
title: ADR 0004 — LLM Wiki Pattern for Integral Knowledge Commons (M10)
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
  - source.adr-0004-llm-wiki-pattern-for-integral-knowledge-commons
claims:
  - id: claim.adr-0004.decision
    text: "LLM Wiki (Karpathy compile-once-query-forever pattern) adopted as M10 knowledge commons layer for Integral stack, over stateless RAG or raw document stores"
    status: supported
    confidence: 1.0
    evidence:
      - kind: source-doc
        sourceId: source.adr-0004-llm-wiki-pattern-for-integral-knowledge-commons
        privacyTier: public
relatedConcepts:
  - concept/adr-0000-oad-workflow-grammar
  - concept/karpathy-llm-wiki
  - concept/adr-0005-rag-agent-memory
relatedSources:
  - source.adr-0004-llm-wiki-pattern-for-integral-knowledge-commons
---
# ADR 0004 — LLM Wiki Pattern for Integral Knowledge Commons (M10)

**Status:** proposed  
**Date:** 2026-05-06  
**ADR:** [[source.0004-llm-wiki-pattern-for-integral-knowledge-commons|Full Document]]  
**GitHub:** https://github.com/regentribes/genesis-zero-bot/blob/main/docs/adr/0004-llm-wiki-pattern-for-integral-knowledge-commons.md

## Key Decision

LLM Wiki (Karpathy compile-once-query-forever pattern) adopted as M10 knowledge commons layer for Integral stack, over stateless RAG or raw document stores

## See Also

- [[adr-0000-oad-workflow-grammar|ADR 0000 — OAD Workflow Grammar]]
- [[karpathy-llm-wiki|Karpathy LLM Wiki Pattern]]
- [[concept.adr-0005-rag-agent-memory-for-integral-stack|ADR 0005 — RAG and Agent Memory]]

## Related

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By

- [[concepts/adr-0003-integral-non-transferable-value-model|ADR 0003 — Integral Non-Transferable Value Model vs Percentage-Based Paywall]]
- [[concepts/adr-0005-rag-agent-memory-for-integral-stack|ADR 0005 — RAG and Agent Memory in the Integral Stack]]
- [[concepts/adr-0006-data-quality-governance-layer|ADR 0006 — Data Quality and Governance for Knowledge Layer]]
<!-- openclaw:wiki:related:end -->
