---
id: source.adr-0003-integral-non-transferable-value-model
pageType: source
title: ADR 0003 — Integral Non-Transferable Value Model vs Percentage-Based Paywall
date: "2026-05-06"
authors: Genesis
sourceType: architecture-decision-record
entityType: source
confidence: 1.0
updatedAt: "2026-05-06"
tags:
  - integral
  - ITC
  - economic-model
  - paywall
  - non-transferable
provenance:
  - source: source.github-regen-tribes
    path: docs/adr/0003-integral-non-transferable-value-model.md
    lines: "1-200"
    weight: 1.0
---

# ADR 0003 — Integral Non-Transferable Value Model vs Percentage-Based Paywall

**Status:** accepted  
**Date:** 2026-05-06  
**Domain:** exchange  
**Level:** system  
**GitHub:** https://github.com/regentribes/genesis-zero-bot/blob/main/docs/adr/0003-integral-non-transferable-value-model.md

## Decision

Adopt the ITC non-transferable value model over Oscar's percentage-based paywall.

## Core Models Compared

| Model | Key Property | Extractive? |
|-------|-------------|-------------|
| Oscar's paywall | % cut at exchange | Yes — transferable cut |
| ITC non-transferable | Event-sourced access value | No — non-transferable |
| Subscription | Fixed recurring fee | Yes — transferable |
| Donation | Voluntary contribution | No — but unpredictable |

## Key ITC Properties

- **Non-transferable** — "Access credits never transfer between members" (ITC spec 1.04)
- **Event-sourced** — Immutable append-only events, causal chain preserved
- **Governance-funded** — CDS/COS/FRS controls infrastructure funding, not extraction
- **Deterministic formula** — No human assigns or adjusts access values

## Rejected: Oscar's Paywall

Percentage extraction at exchange is structurally extractive. Creates regressive dynamics, transferable credits enable accumulation. Incompatible with gift economy principles.

## See Also

- [[concepts/adr-0000-oad-workflow-grammar|ADR 0000]]
- [[concepts/adr-0002-ame-metonymic-activation|ADR 0002]]
- Integral Specification ISPEC001 (spec only, not yet ingested into wiki)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By

- [[concepts/adr-0003-integral-non-transferable-value-model|ADR 0003 — Integral Non-Transferable Value Model vs Percentage-Based Paywall]]
<!-- openclaw:wiki:related:end -->
