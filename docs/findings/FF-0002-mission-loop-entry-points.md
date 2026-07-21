# Framework Finding — FF-0002

**Identifier:** FF-0002  
**Source:** DEC-0002 (Mallorca pivot), Mission Owner directive  
**Status:** Proposed  
**Submitted:** 2026-07-21  
**Confidence:** High  

## Title

**Canonical Mission Loop assumes linear planning but missions are often enacted before planned**

## Canonical Reference

- GLOSSARY.md — Mission Loop, Mission definition
- README.md — "The Mission Cycle" diagram

## Context

The canonical Mission Loop is:

```text
Reality → Need/Opportunity/Obligation → Mission → Objective → Capability/Action → ...
```

This implies a linear progression from need through mission definition through planning. But DEC-0002 exposed a different pattern:

Peter (Mission Owner) committed real resources (flights, hotel, car) before the Mission Director (z.ai) began planning. The mission was *enacted* before it was *planned*. The execution order was:

```text
Reality (eclipse opportunity + personal constraints)
    ↓
Owner decision (book flights, hotel, car)
    ↓
Directive to Director (baseline v0.1)
    ↓
Director planning (this document)
    ↓
Mission Loop (observation, evidence, learning)
```

## Observation

The canonical loop is not wrong — all the elements are present. But it describes an idealized sequence (need recognized → mission defined → planned → executed) that doesn't capture the common real-world pattern where mission resources are committed in parallel with or prior to formal planning.

This is not a framework defect per se — it's a question of what the Loop models. Is it:

1. A *design-time* model of what a well-formed mission looks like (normative)?
2. A *run-time* model of how missions actually unfold (descriptive)?
3. Both — with views for different contexts?

The Glossary doesn't say.

## Interpretation

The Mallorca mission is *more* framework-compliant, not less, because the Owner committed resources to reality before the framework was involved. This is precisely "reality before models" — the Reality Principle in its strongest form.

But the Loop diagram doesn't show this. It shows a clean waterfall. A mission that starts with an owner booking flights doesn't fit the diagram, even though it perfectly fits the principles.

### Proposed clarification

The Mission Loop should be explicitly annotated as **normative** (this is what a well-structured mission should enable) with an acknowledgment that real missions may enter the loop at different points:

- **Need-driven:** The classic path — need recognized → mission formed
- **Opportunity-driven:** Eclipse date known → owner commits → planning follows (Mallorca pattern)
- **Obligation-driven:** External requirement → mission formed to comply
- **Recovery-driven:** Failure detected → recovery mission formed

All four should connect to the same Mission Loop once the mission exists.

## Evidence

- DEC-0002 (Mallorca pivot with owner pre-commitment)
- DEC-0001 (original Luxor planning — need-driven approach)
- Mission baseline v0.1 directive (2026-07-21, 17:18 CEST)

## Consequence

Without clarification, future reference missions that follow the opportunity-driven pattern may be incorrectly assessed as "non-compliant" with the Mission Loop, when they are in fact demonstrating the Reality Principle in its purest form.

## Proposed Disposition

**Accept — Clarify.** Add annotation to the canonical Mission Loop in GLOSSARY.md acknowledging multiple entry points while preserving the normative structure. No change to existing concepts — only clarification of the Loop's scope.

### Specific suggestion for GLOSSARY.md

Add this note to the Canonical Mission Loop section:

> **Entry points.** The loop is normative — it describes the elements a well-structured mission should contain. Real missions may form through different triggers: an identified need (classic path), a recognized opportunity (e.g., a predictable celestial event), an external obligation, or a recovery from failure. Once formed, a mission should connect to the full loop, but the trigger event determines where mission formation begins.
>
> **Resource commitment.** In practice, accountable authorities may commit resources before formal planning is complete. This is not a deviation from the framework — it is the Reality Principle in operation. The framework's role is to make the committed mission traceable, not to require that planning precede commitment.

## Review Criteria

1. ✅ Observation is traceable to a real mission event (DEC-0002)
2. ✅ Issue concerns canonical meaning (Mission Loop interpretation)
3. ✅ Existing definition is ambiguous (normative vs. descriptive not stated)
4. ✅ Proposed change improves explanatory value without breaking existing concepts
5. ✅ Change is clarification only — no semantic distortion risk
6. ✅ Sufficient evidence (real mission with committed resources)
7. ❓ Affected documents: GLOSSARY.md (Mission Loop section), README.md (Mission Cycle diagram)

---

## Disposition

**Status:** Proposed  
**Requires:** Mission Framework maintainer review (ChatGPT, Chief Architect)
