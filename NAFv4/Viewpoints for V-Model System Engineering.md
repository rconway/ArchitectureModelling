
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
[Plateau: Concept of Operations]
   - L2-L3 (Representation)   «Logical Concept Viewpoint»
        |
        | Influence / Refines
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
   - P4 (Technology Function)
   - L4-P4 (Representation)   «Activity-to-Function Mapping»
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

# A4 - Methodology Used

<img width="734" height="530" alt="image" src="https://github.com/user-attachments/assets/f907a532-db89-4ab2-814f-add26f1365f3" />
