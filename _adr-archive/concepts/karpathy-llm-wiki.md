---
id: concept.karpathy-llm-wiki
pageType: concept
entityType: concept
title: Karpathy LLM Wiki Pattern
status: active
date: "2026-05-06"
authors: Andrej Karpathy
domain: information
level: system
confidence: 1.0
updatedAt: "2026-05-06"
tags:
  - knowledge-base
  - wiki
  - LLM
  - pattern
  - karpathy
sourceIds:
  - source.karpathy-llm-wiki
claims:
  - id: claim.karpathy.pattern.two-stages
    text: "LLM Wiki ingest should be two-stage: analysis (LLM reads source → structured findings) then generation (LLM takes findings → wiki pages)"
    status: supported
    confidence: 1.0
    evidence:
      - kind: external-url
        sourceId: source.karpathy-llm-wiki
relatedConcepts:
  - concept.memory-wiki
  - concept.ame-metonymic-activation
  - concept.living-seed-pattern
---

# Karpathy LLM Wiki Pattern

Original proposal by Andrej Karpathy (2024): https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f

## Core Idea

Instead of RAG (retrieve-and-answer from raw documents on every query), the LLM incrementally builds and maintains a **persistent wiki** — a structured, interlinked collection of markdown files that sits between you and the raw sources.

**The key difference:** knowledge is compiled once and kept current, not re-derived on every query.

## Three Layers

1. **Raw sources** — immutable source documents (articles, papers, data)
2. **Wiki** — LLM-generated markdown files with YAML frontmatter and wikilinks
3. **Schema** — configuration that tells the LLM how the wiki is structured

## Three Operations

| Operation | What happens |
|-----------|-------------|
| **Ingest** | LLM reads source → creates/updates wiki pages → updates index + log |
| **Query** | Search relevant pages → LLM synthesizes answer with citations |
| **Lint** | Check for orphan pages, broken links, contradictions, stale content |

## Special Files

- **index.md** — content catalog, updated on every ingest, LLM reads it first
- **log.md** — append-only chronological record of all operations

## Implementations

- **memory-wiki** (OpenClaw) — agent-native, Radicle sync, compiled digests
- **geronimo-iia/llm-wiki** — Rust, 23 MCP tools, no LLM inside
- **nashsu/llm_wiki** — Electron desktop app, two-step ingest, 4-signal knowledge graph
- **atomicmemory/llm-wiki-compiler** — npm CLI, two-phase pipeline, SHA256 cache

## Relevance to RegenTribes

Genesis uses memory-wiki which implements this pattern. The wiki vault at `rad:zYhRVEu5Zh85vcwvmxkZHJNQxn6X` is the live instance.

Source: [Karpathy's Original Gist](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)

## Related
<!-- openclaw:wiki:related:start -->
- No related pages yet.
<!-- openclaw:wiki:related:end -->
