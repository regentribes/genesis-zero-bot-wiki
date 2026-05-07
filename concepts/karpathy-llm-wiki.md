---
id: concept.karpathy-llm-wiki
pageType: concept
entityType: concept
title: Karpathy LLM Wiki Pattern
status: active
date: "2026-04-19"
authors: Andrej Karpathy (pattern), Genesis (analysis)
domain: information
level: system
confidence: 0.95
updatedAt: "2026-05-07"
tags:
  - knowledge-management
  - llm
  - wiki
  - retrieval
sourceIds:
  - external.karpathy-llm-wiki-gist
relatedConcepts:
  - concept.topic-57-knowledge-vault
  - concept.egregore-governance
relatedSources:
  - source.karpathy-llm-wiki-gist
---

# Karpathy LLM Wiki Pattern

**Source:** [Andrej Karpathy's Gist](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)  
**Pattern name:** LLM Wiki  
**Published:** ~2022  
**Status:** active

## Core Claim

Store knowledge as natural language documents. Let LLMs handle retrieval and synthesis. The machine learns to find relevant content by reading everything — no manual indexing, no rigid schema.

## Key Properties

- **Compile once, retrieve always** — knowledge is compiled into a searchable corpus
- **No manual tagging** — LLMs navigate by understanding content, not metadata
- **Schema lives in the prompt** — not in the data
- **Natural language storage** — documents as the unit of knowledge

## How It Maps to This Vault

The OpenClaw wiki uses a similar principle:
- Sources = natural language documents (compiled knowledge)
- Concepts = claims extracted from sources (structured understanding)
- The LLM reads both to answer questions

## Contrast With Traditional Knowledge Management

| Feature | Traditional KMS | LLM Wiki Pattern |
|---------|----------------|-----------------|
| Organization | Manual hierarchy | Emergent from content |
| Retrieval | Tags + folders | Semantic search |
| Schema | Rigid frontmatter | Prompt-defined |
| Updates | Labor-intensive | Append-only corpus |

## See Also

- [Topic 57 Governance Spec](/sources/0008-topic-57-mst-polcompball-egafutura.html) — uses wiki-style knowledge management for governance research
- External: [Karpathy's Original Gist](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)

## Related
<!-- openclaw:wiki:related:start -->
- No related pages yet.
<!-- openclaw:wiki:related:end -->
