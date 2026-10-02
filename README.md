# AI/ML Incident Response & Security Control Analysis

> An AI security case study examining where attacks against AI/ML
> infrastructure can be detected, interrupted, and contained across
> the attack chain.

## Project Overview

This repository presents my analysis and contribution to the team research
project:

**The Containment Burden Sits on the Wrong Side of the Boundary &
AI Escape Detection Harness**

The project investigates a real-world AI/ML security incident from an
incident-response perspective, focusing on how defensive controls can
detect, interrupt, or contain malicious activity at different stages of
the attack chain.

The broader research includes an incident reconstruction, a **26-control
Kill-Point Matrix**, containment analysis, and a detection proof of concept.

---

## Research Question

> Where should containment responsibility sit when potentially malicious
> AI/ML activity crosses the boundary between a lab environment and a
> downstream victim environment?

The analysis considers not only **which security controls are available**,
but also **when they can intervene**, **what defensive effect they provide**,
and **how much implementation effort they require**.

---

## Analysis

### 1. Attack Chain Analysis

Reconstruction of the attack sequence and identification of potential
detection and containment opportunities.

➡️ [View Attack Chain Analysis](analysis/attack-chain.md)

### 2. Security Control Analysis

Analysis of **26 proposed security controls** across lab-side,
external-sandbox, and victim-side environments.

Controls are evaluated according to their primary defensive effect:

**Block • Detect • Reduce**

➡️ [View Security Control Analysis](analysis/security-controls.md)

### 3. Cost, Timing & Effectiveness

Comparison of defensive controls based on:

- implementation effort,
- intervention timing,
- defensive effect,
- attack-chain position,
- and containment value.

➡️ [View Cost & Effectiveness Analysis](analysis/cost-effectiveness.md)

---

## Key Visualization

![Control Timing and Cost Analysis](assets/diagrams/control-timing-cost.png)

A central observation of the broader analysis is that implementation
cost alone does not explain the difference between the two sides of the
boundary.

**Intervention timing is critical.**

Controls positioned earlier in the attack chain can potentially interrupt
malicious activity before the containment burden reaches the downstream
environment.

---

## My Contribution

My primary contribution to the team project focused on the
**cost and effectiveness analysis of proposed security controls**.

I evaluated controls across lab-side and victim-side environments,
considering factors such as:

- implementation effort,
- operational complexity,
- defensive effectiveness,
- intervention timing,
- attack-chain coverage,
- and containment value.

This work contributed to the project's broader **Kill-Point Matrix** and
the analysis of how containment responsibilities are distributed across
the AI/ML security boundary.

This repository is a **personal portfolio representation of my analysis
and contribution** to the broader team research project. The complete
research and technical implementation were collaborative efforts.

---

## Security Concepts

`AI Security` `Incident Response` `Attack Chain Analysis`
`Detection Engineering` `Containment` `Security Controls`
`Risk Analysis` `Kill-Point Analysis`

---

## Repository Structure

    ai-security-incident-response/
    │
    ├── README.md
    │
    ├── analysis/
    │   ├── attack-chain.md
    │   ├── security-controls.md
    │   └── cost-effectiveness.md
    │
    └── assets/
        └── diagrams/
            ├── control-timing-cost.png
            ├── security-controls-owner-cost.png
            └── security-controls-owner-effect.png

---

## Broader Team Research

This repository focuses on my analytical contribution and portfolio
documentation.

For the complete team research, incident reconstruction, Kill-Point Matrix,
and detection proof of concept, see the original project resources:

- **Apart Research Publication:**  
  [The Containment Burden Sits on the Wrong Side of the Boundary &
  AI Escape Detection Harness](https://apartresearch.com/project/the-containment-burden-sits-on-the-wrong-side-of-the-boundary-ai-escape-detection-harness-7luf)

- **Original Detection Harness Repository:**  
  [AI Escape Detection PoC](https://github.com/V3nG4mxV1p3r/ai-escape-detection-poc)

---

##  Collaboration & Attribution

The original research was developed collaboratively as part of an
AI Incident Response Sprint.

This repository does **not** represent the entire team project as individual
work. It documents my contribution and presents selected analyses from the
broader collaborative research for portfolio purposes.
