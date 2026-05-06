---
id: source.karpathy-llm-wiki
pageType: source
title: Karpathy LLM Wiki Pattern — Original Proposal
date: "2026-05-06"
authors: Andrej Karpathy
sourceType: article
entityType: source
confidence: 1.0
updatedAt: "2026-05-06"
tags:
  - karpathy
  - LLM-wiki
  - knowledge-base
sourceIds: []
---

# Karpathy LLM Wiki Pattern

**URL:** https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f

This gist describes a pattern for building personal knowledge bases using LLMs. Key quote:

> "Instead of just retrieving from raw documents at query time, the LLM incrementally builds and maintains a persistent wiki — a structured, interlinked collection of markdown files that sits between you and the raw sources. When you add a new source, the LLM doesn't just index it for later retrieval. It reads it, extracts the key information, and integrates it into the existing wiki — updating entity pages, revising topic summaries, noting where new data contradicts old claims."

Three layers: raw sources → wiki → schema.
Three operations: ingest, query, lint.

See: [[concepts/karpathy-llm-wiki|Karpathy LLM Wiki Pattern — Concept Page]]

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By

- [[concepts/karpathy-llm-wiki|Karpathy LLM Wiki Pattern]]
<!-- openclaw:wiki:related:end -->
