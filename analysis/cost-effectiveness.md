# Cost & Effectiveness Analysis of Security Controls

## Overview

This analysis evaluates security controls proposed within the broader
AI Incident Response project from both a cost and defensive-effectiveness
perspective.

The goal was to examine not only whether a security control could
interrupt the attack chain, but also whether its implementation would
be practical relative to the defensive value it provides.

---

## Analysis Perspective

The controls were evaluated across two environments:

### Lab-Side Controls

Controls that could be implemented closer to the environment where
AI/ML workloads, models, datasets, or experimental systems are operated.

### Victim-Side Controls

Controls that could help organizations detect or contain malicious
activity after interaction with potentially compromised AI/ML
artifacts or infrastructure.

---

## Evaluation Criteria

The analysis considered several dimensions:

| Dimension | Purpose |
|---|---|
| Cost | Relative implementation and operational cost |
| Effectiveness | Expected defensive impact |
| Detection Value | Ability to expose malicious behavior |
| Containment Value | Ability to limit further compromise |
| Deployment Complexity | Practical difficulty of implementation |
| Attack-Chain Position | Stage at which the control can intervene |

---

## Cost vs. Defensive Value

A security control should not be evaluated only by whether it is
technically capable of stopping an attack.

Its practical value also depends on:

- implementation requirements,
- operational overhead,
- deployment complexity,
- attack-chain coverage,
- and the amount of containment burden it can eliminate.

This creates an important trade-off:

> **How much defensive value does a control provide relative to the
> cost and complexity required to deploy it?**

---

## My Contribution

My primary contribution to the team project focused on evaluating
security controls from a **cost and effectiveness perspective**.

I examined proposed controls across both lab-side and victim-side
environments and considered how implementation cost, operational
complexity, and defensive effectiveness affected their practical value.

This analysis contributed to the broader **Kill-Point Matrix**, which
mapped defensive controls to potential interruption points across the
attack chain.

---

## Key Takeaway

The analysis highlights that strong incident response is not simply
about deploying the largest possible number of security controls.

The placement of controls across the attack chain, their ability to
detect or contain malicious activity, and the operational cost of
deployment all influence their real defensive value.

---

## Related Project

This analysis was conducted as part of the team research project:

**The Containment Burden Sits on the Wrong Side of the Boundary &
AI Escape Detection Harness**

Published through Apart Research.
