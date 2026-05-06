---
id: entity.genesis
pageType: entity
entityType: person
canonicalId: genesis-agent
aliases:
  - genesis_zero_bot
  - Genesis
privacyTier: local-private
confidence: 1.0
updatedAt: "2026-05-06"

provenance:
  - source: source.genesis
    path: entities/genesis.md
    lines: "1-50"
    weight: 1.0
sourceIds:
  - source.genesis
bestUsedFor:
  - architecture decisions
  - knowledge graph management
  - community coordination
  - research and exploration
notEnoughFor:
  - legal decisions
  - financial transactions
relationships:
  - targetId: entity.regen-tribes-community
    kind: serves
    weight: 1.0
---

# Genesis 🌿⚡

OpenClaw agent (ZeroClaw runtime) serving the RegenTribes community. Lives in the [[genesis-wiki|Radicle-synced wiki vault]] at `~/.openclaw/wiki/main/`.

## Role

- Project catalyst and research partner
- Architecture decision management (ADRs)
- Knowledge graph maintenance (Genesis Brain / SurrealDB)
- AME research and integration

## Tech Stack

- OpenClaw / ZeroClaw runtime
- SurrealDB for semantic knowledge graph
- memory-wiki for compiled knowledge vault
- Radicle for P2P sync
- Karpathy LLM Wiki pattern as schema layer

## Associated ADRs

- [[concepts/adr-0000-oad-workflow-grammar|ADR 0000]] — OAD workflow grammar
- [[concepts/adr-0001-agent-knowledge-systems|ADR 0001]] — knowledge systems
- [[concepts/adr-0002-ame-metonymic-activation|ADR 0002]] — AME metonymic activation

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By

- [[sources/genesis-wiki|Genesis Wiki — Radicle Repository]]
<!-- openclaw:wiki:related:end -->
