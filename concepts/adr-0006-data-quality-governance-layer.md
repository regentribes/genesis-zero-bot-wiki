---
id: concept.adr-0006-data-quality-governance-layer
pageType: concept
entityType: concept
title: ADR 0006 — Data Quality and Governance for Knowledge Layer
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
  - source.0006-data-quality-governance-layer
claims:
  - id: claim.adr-0006.decision
    text: "Four governance requirements (provenance, freshness, contradiction detection, ingest gates) apply across all three knowledge patterns: LLM Wiki, RAG, Agent Memory"
    status: supported
    confidence: 1.0
    evidence:
      - kind: source-doc
        sourceId: source.0006-data-quality-governance-layer
        privacyTier: public
relatedConcepts:
  - concept.adr-0004-llm-wiki-pattern-for-integral-knowledge-commons
  - concept.adr-0005-rag-agent-memory-for-integral-stack
relatedSources:
  - source.0006-data-quality-governance-layer
---

# ADR 0006 — Data Quality and Governance for Knowledge Layer

**Status:** proposed  
**Date:** 2026-05-06  
**Full document:** [[0006-data-quality-governance-layer|0006-data-quality-governance-layer|GitHub]]  
**Source:** [[sources/0006-data-quality-governance-layer|Source page]]

## Key Decision

Four governance requirements (provenance, freshness, contradiction detection, ingest gates) apply across all three knowledge patterns: LLM Wiki, RAG, Agent Memory

## References

- [[sources/0006-data-quality-governance-layer|Source page in wiki vault]]
- [GitHub](https://github.com/regentribes/genesis-zero-bot/blob/main/docs/adr/0006-data-quality-governance-layer.md)

## Related
<!-- openclaw:wiki:related:start -->
### Sources

- [[sources/0006-data-quality-governance-layer|ADR 0006 — Data Quality and Governance for Knowledge Layer]]

### Referenced By

- [[sources/0006-data-quality-governance-layer|ADR 0006 — Data Quality and Governance for Knowledge Layer]]
<!-- openclaw:wiki:related:end -->
