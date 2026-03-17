# CDS — Collaborative Decision System

The Collaborative Decision System is Integral's governance engine. It is the 
channel through which problems are raised, proposals are deliberated, decisions 
are made, and those decisions are dispatched to the rest of the system for action.

CDS is the first system to be built. It governs the development process itself 
as the contributor community grows — before it governs a node, it governs the 
project. This makes it the highest-priority repository in the organization.

## Role in the Architecture

- Receives issues and proposals from participants and from other systems
- Structures deliberation through a defined governance pipeline
- Synthesizes consensus without majority voting
- Records every decision in a tamper-evident, append-only ledger
- Dispatches decision packets to OAD, COS, ITC, and FRS for implementation
- Receives governance feedback from FRS to assess whether decisions are working

CDS does not produce goods, track labor, or monitor ecological conditions. 
It produces legitimate, recorded, actionable decisions — and closes the loop 
by evaluating whether those decisions had their intended effects.

## Current Status

**Phase 1 — Specification and governance setup.**

No implementation has begun. The minimum viable module set for CDS is defined 
in the [development guide](https://github.com/integralcollective/integral-devguide). 
The white paper's formal CDS specification serves as the primary technical reference.

Active work in this repository begins when the contributor community is ready 
to ratify the minimum viable module set and begin Phase 2 development.

## Minimum Viable Modules

The following modules are proposed for the initial build:

- **Module 1** — Issue Capture & Signal Intake
- **Module 2** — Issue Structuring & Framing *(manually assisted)*
- **Module 6** — Weighted Consensus Mechanism *(simplified)*
- **Module 7** — Decision Recording, Versioning & Accountability
- **Module 8** — Implementation Dispatch Interface *(simplified)*

Full module descriptions, deferral reasoning, and implementation guidance 
are in Section 3.1 of the development guide.

## References

- [Integral Development Guide](https://github.com/integralcollective/integral-devguide)
- [Integral White Paper](https://github.com/integralcollective/integral-whitepaper)
- [Interface Specifications](https://github.com/integralcollective/integral-specifications)

---

*Part of the [Integral project](https://integralcollective.io).*
