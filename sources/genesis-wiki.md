---
id: source.genesis-wiki
pageType: source
title: Genesis Wiki — Radicle Repository
date: "2026-05-06"
sourceType: knowledge-repository
entityType: source
provenance: []
tags:
  - wiki
  - radicle
  - knowledge-base
confidence: 1.0
updatedAt: "2026-05-06"
---

# Genesis Wiki — Radicle Repository

This wiki vault is the compiled knowledge layer for the RegenTribes community.

## Public Access

**Radicle RID:** `rad:zYhRVEu5Zh85vcwvmxkZHJNQxn6X`

Peers on the Radicle network can clone this wiki:

    git clone rad://zYhRVEu5Zh85vcwvmxkZHJNQxn6X

Or use the iris UI:

    https://radicle.xyz/nodes/radicle.xyz/trees/rad:zYhRVEu5Zh85vcwvmxkZHJNQxn6X

## Architecture

The wiki follows Karpathy's LLM Wiki pattern:

- **Sources layer:** immutable source documents (ADRs, articles, specs)
- **Concepts layer:** LLM-generated synthesis pages with wikilinks
- **Entities layer:** people, projects, organizations
- **Syntheses layer:** cross-cutting summaries

## Sync Strategy

- Radicle P2P for offline-first sync across nodes
- GitHub for human-facing ADR document reference
- Both are kept in sync manually

## See Also

- [[entities/genesis|Genesis agent]]
- [[entities/regen-tribes-community|RegenTribes community]]
- [[concepts/karpathy-llm-wiki|Karpathy LLM Wiki pattern]]

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By

- [[entities/genesis|Genesis 🌿⚡]]
<!-- openclaw:wiki:related:end -->
