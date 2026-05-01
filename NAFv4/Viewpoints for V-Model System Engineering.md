
# Viewpoints for V-Model System Engineering

## Concept

* Existing Capability Analysis
  * C2, C1, A1
* Stakeholder Requirements
  * L2-L3, L2, L3, L4, L6
* System Requirements
  * L7, P2, P1
* High-level Design
  * P2 (revisit), P1 (revisit), P4, L4-P4
* Detailed Design
  * P3, P6, P1, P7
* Implementation Planning
  * Lr

## ArchiMate

```
[Plateau: Existing Capability]
   - C2 (Assessment)
   - C1 (Assessment)
   - A1 (Constraint)
        |
        | Influence
        v
[Plateau: Stakeholder Requirements]
   - L2 (Requirement)
   - L3 (Requirement)
   - L4 (Requirement)
   - L6 (Requirement)
        |
        | Realization
        v
[Plateau: System Requirements]
   - L7 (Requirement)
   - P1 (Node)
   - P2 (Node)
        |
        | Realization
        v
[Plateau: High-Level Design]
   - P4 (Tech Function)
   - L4→P4 (Realization)
        |
        | Realization
        v
[Plateau: Detailed Design]
   - P3 (Comm Network)
   - P6 (Tech Process)
   - P7 (Artifact)
        |
        | Realization
        v
[Plateau: Implementation Planning]
   - Lr (Work Package)
```
