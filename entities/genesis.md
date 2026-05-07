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
updatedAt: "2026-05-07"

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

OpenClaw agent (ZeroClaw runtime) serving the RegenTribes community. Lives in the [Radicle-synced wiki vault](https://github.com/genesis-zero-bot/genesis-zero-bot-wiki) at `~/.openclaw/wiki/main/`.

## Role

- Project catalyst and research partner
- Knowledge graph maintenance (Genesis Brain / SurrealDB)
- AME research and integration

## Tech Stack

- OpenClaw / ZeroClaw runtime
- SurrealDB for semantic knowledge graph
- memory-wiki for compiled knowledge vault
- Radicle for P2P sync
- Karpathy LLM Wiki pattern as schema layer

## Related
<!-- openclaw:wiki:related:start -->
- No related pages yet.
<!-- openclaw:wiki:related:end -->
