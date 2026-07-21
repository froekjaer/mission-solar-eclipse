# Framework Finding — FF-0001

**Identifier:** FF-0001  
**Source:** Mission Solar Eclipse — DEC-0001  
**Status:** Proposed  
**Submitted:** 2026-07-21  
**Confidence:** Moderate  

## Title

**No sub-agent or delegated research concept in Mission Core or Glossary**

## Canonical Reference

- GLOSSARY.md — Actor, Decision, Delegated Authority, Capability
- docs/MISSION_CORE_ADMISSION.md

## Context

During eclipse target selection (DEC-0001), I delegated astronomical research to a sub-agent (`sessions_spawn`). This sub-agent is:
- An **Actor** (it performed an action — researched and compiled eclipse data)
- Operating under **Delegated Authority** (I authorized it to research within defined bounds)
- Producing **Evidence** (the research report is evidence for DEC-0001)

But the current Glossary defines:
- **Actor** as "A person, organisation, system or mechanism capable of performing an action or participating in a relationship" — which *does* cover AI sub-agents
- **Delegated Authority** as "A recorded Decision by an accountable human or organisational authority that permits another Actor or mechanism to act within explicit bounds"

## Observation

The Glossary definitions are technically sufficient — an AI sub-agent fits within the existing concepts. However:

1. **No concept distinguishes between primary and delegated actors.** In DEC-0001, the Mission Director (z.ai) acted under delegated authority from Peter, and the research sub-agent acted under sub-delegated authority from z.ai. Both are "Actors" and both operate under "Delegated Authority," but their relationship (sub-delegation, bounded scope, one-shot execution) is invisible in the current model.

2. **No concept for "one-shot capability provision."** The sub-agent provided a capability (astronomical research) for a single decision. It is not a persistent Service, not a standing Capability, and not a human team member. The framework models persistent capabilities well but has no concept for ephemeral, AI-provisioned capabilities that exist only for the duration of one task.

3. **The delegation chain is implicit.** Peter → z.ai → sub-agent. The current Delegated Authority concept captures a single delegation but not chains. In practice, complex missions will have multi-hop delegation.

## Interpretation

The framework is *sufficient* for this specific case but would benefit from:
- Explicit modeling of **delegation chains** (not just single delegation edges)
- A concept for **ephemeral capability** (one-shot or time-bounded capability provision, distinct from persistent Service)
- Recognition that AI sub-agents are a distinct Actor subtype with specific trust, provenance, and accountability characteristics

This is not a bug — the framework's existing concepts absorb the use case. But as AI sub-agents become common in mission execution, the absence of explicit modeling may lead to inconsistent application (e.g., some missions will model sub-agents as Actors, others as Services, others as Capabilities — without guidance).

## Evidence

- DEC-0001 decision record
- Sub-agent research result (session: agent:main:subagent:9fd3a7d4-...)
- Mission Director Note MDN-0001

## Consequence

Without explicit modeling of delegation chains and ephemeral AI capabilities, different reference missions will model the same pattern differently, reducing cross-mission comparability and framework coherence.

## Proposed Disposition

**Defer — gather evidence from additional mission decisions.**

This finding should be revisited after the mission has executed 10+ delegated research or analysis tasks. The current level of evidence (one sub-agent call) is insufficient to determine whether the framework needs new concepts or merely guidance on applying existing ones.

## Review Criteria

1. ✅ Observation is traceable to a real mission condition (DEC-0001 eclipse research delegation)
2. ✅ Issue concerns canonical meaning (Actor, Delegated Authority, Capability)
3. ✅ Existing definition is *sufficient* but the pattern may benefit from explicit modeling
4. ⬜ Would proposed change improve value? (Deferred — insufficient evidence)
5. ⬜ Could change introduce distortion? (Deferred)
6. ⬜ Sufficient evidence? (No — single instance)
7. ⬜ Affected documents? (Deferred)

---

## Disposition

**Status:** Proposed → Deferred  
**Rationale:** Valid observation, but single-instance evidence is insufficient for a canonical change. Revisit after additional mission decisions exercise the same pattern.
**Reviewer:** z.ai (self-assessment — requires external review)
**Date:** 2026-07-21
