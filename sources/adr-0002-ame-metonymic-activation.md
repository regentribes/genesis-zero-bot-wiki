---
id: source.adr-0002-ame-metonymic-activation
pageType: source
title: ADR 0002 — AME Metonymic Activation and Virtual Trust Field
date: "2026-05-06"
authors: Genesis
sourceType: architecture-decision-record
entityType: source
confidence: 1.0
updatedAt: "2026-05-06"
tags:
  - AME
  - affinity-mapping
  - metonymy
  - virtuality
  - trust-field
  - linguistics
provenance:
  - source: source.github-regen-tribes
    path: docs/adr/0002-ame-metonymic-activation.md
    lines: "1-999"
    weight: 1.0
---

# ADR 0002 — AME Metonymic Activation and Virtual Trust Field

**Status:** accepted  
**Date:** 2026-05-06  
**GitHub:** https://github.com/regentribes/genesis-zero-bot/blob/main/docs/adr/0002-ame-metonymic-activation.md

## Decision

Map AME (Affinity Mapping Engine) architecture to the linguistic sign model from Radden & Kövecses (2017). Document structural isomorphism between trapezium model of meaning and AME's seed activation model.

## Key Insight

AME's single-detected-value → activates entire seed → virtually activates FOT (Field of Trust). This is the **same mechanism** as the linguistic sign: a form (word) metonymically activates a whole configuration of concepts + experienced projections + relationships. Virtuality = indirect activation.

## Article Reference

"The Linguistic Sign: Metonymy and Virtuality" — DOI: 10.13092/lo.80.3565

**Exact quote:** "it means by virtue of the linguistic form activating (virtually) the entire trapezium-like configuration of forms, concepts, experienced projections, and relationships"

## AME Architecture

- Living Seed: needs + beliefs + principles + values (separated)
- V-Crystal: 6 positions (Victor, Villain, Victim, Vengeful, Virtuous, Vulnerable)
- FOT = Trust Field, hologram principle (min of 5 indicators)
- 30-day time lock for matching

See also: [[concepts/adr-0000-oad-workflow-grammar|ADR 0000]], [[concepts/adr-0001-agent-knowledge-systems|ADR 0001]]

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By

- [[concepts/adr-0002-ame-metonymic-activation|ADR 0002 — AME Metonymic Activation and Virtual Trust Field]]
<!-- openclaw:wiki:related:end -->
