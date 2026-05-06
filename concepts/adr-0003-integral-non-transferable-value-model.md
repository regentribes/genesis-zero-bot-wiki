---
id: concept.adr-0003-integral-non-transferable-value-model
pageType: concept
entityType: concept
title: ADR 0003 — Integral Non-Transferable Value Model vs Percentage-Based Paywall
status: accepted
date: "2026-05-06"
authors: Genesis
domain: exchange
level: system
confidence: 1.0
updatedAt: "2026-05-06"
tags:
  - integral
  - ITC
  - economic-model
  - paywall
  - non-transferable
  - value
sourceIds:
  - source.adr-0003-integral-non-transferable-value-model
claims:
  - id: claim.adr-0003.ITC-adopted-over-paywall
    text: "ITC non-transferable value model adopted over Oscar's percentage-based paywall for regenerative community economics"
    status: supported
    confidence: 1.0
    evidence:
      - kind: source-doc
        sourceId: source.adr-0003-integral-non-transferable-value-model
        privacyTier: public
  - id: claim.adr-0003.non-transferable-access-credits
    text: "ITC model requires access credits to be non-transferable between members — prevents accumulation and winner-take-all dynamics"
    status: supported
    confidence: 1.0
    evidence:
      - kind: source-doc
        sourceId: source.adr-0003-integral-non-transferable-value-model
        privacyTier: public
  - id: claim.adr-0003.governance-funded-infrastructure
    text: "ITC infrastructure funding through CDS/COS/FRS governance rather than transaction extraction"
    status: supported
    confidence: 1.0
    evidence:
      - kind: source-doc
        sourceId: source.adr-0003-integral-non-transferable-value-model
        privacyTier: public
relatedConcepts:
  - concept.integral-collective
  - concept.ITC-ledger
  - concept.oad-workflow
  - concept.fot-field-of-trust
relatedSources:
  - source.adr-0003-integral-non-transferable-value-model
  - source.Integral_Specification_ISPEC001
---

# ADR 0003 — Integral Non-Transferable Value Model vs Percentage-Based Paywall

Adopted the ITC non-transferable value model (event-sourced, governance-funded) over Oscar's percentage-based paywall for regenerative community economics.

## Why Not Oscar's Paywall

| Problem | Mechanism |
|---------|-----------|
| Regressive extraction | % cut means high-usage members pay more proportionally |
| Transferable credits | Enable accumulation → winner-take-all dynamics |
| Volume-dependent revenue | Infrastructure funding tied to transaction volume |
| Structurally extractive | Regardless of stated intent, % extraction is extractive |

## Why ITC Non-Transferable

| Property | Effect |
|----------|--------|
| Non-transferable credits | Prevents accumulation and wealth concentration |
| Event-sourced ledger | Immutable audit trail, no hidden adjustments |
| Governance-funded | CDS/COS/FRS controls funding, not market extraction |
| Deterministic formula | No human assignment or manipulation possible |

## Phase Status

- **Decision:** locked now (ADR 0003)
- **Implementation:** deferred to Phase 2 (when COS/ITC/FRS available)

Source: [[sources/adr-0003-integral-non-transferable-value-model|ADR 0003 — Full Source]]

## Related
<!-- openclaw:wiki:related:start -->
### Sources

- [[sources/adr-0003-integral-non-transferable-value-model|ADR 0003 — Integral Non-Transferable Value Model vs Percentage-Based Paywall]]
<!-- openclaw:wiki:related:end -->
