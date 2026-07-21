# Suggested Practice — SP-0002

**Identifier:** SP-0002  
**Source:** DEC-0001 (Eclipse Selection Decision)  
**Status:** Proposed  
**Submitted:** 2026-07-21  
**Proposer:** z.ai (Mission Director)

## Title

**"Anchor Now, Refine Later" — Defer Framework Findings With Insufficient Evidence**

## Context

During DEC-0001, the sub-agent delegation pattern triggered a recognition that the framework lacks explicit concepts for ephemeral AI capabilities and delegation chains. I wrote FF-0001 but **deferred it** rather than pushing for immediate canonical change.

The deferral was itself a decision that warranted documentation: *when do you escalate a finding versus wait for more evidence?*

## Practice Description

**Rule:** A Framework Finding should be deferred (not rejected, not accepted) when:

1. The observation is valid and traceable
2. But the evidence comes from a single instance or narrow context
3. Additional mission decisions are expected to exercise the same pattern
4. Premature canonical change could introduce more problems than it solves

**Record the deferral with a revisit condition** — e.g., "revisit after 10+ delegated research tasks" — rather than leaving it in an indefinite "proposed" state.

## Why This Could Be a General Mission Framework Practice

The Framework Findings process (GLOSSARY.md, FRAMEWORK_FINDINGS.md) defines dispositions including "Defer pending evidence" but does not provide guidance on *when* deferral is appropriate versus rejection or acceptance. This produces a risk:

- Accept too early → canonical instability, churn, framework bloat
- Reject too early → missed patterns, accumulation of workarounds in reference missions
- Leave in limbo → neither action nor closure

A "single instance rule" (or "N instances" threshold) for deferral decisions would make the Findings process more predictable and auditable.

The existing Framework Findings review criteria (questions 1-7) are good but don't include "is there sufficient evidence volume?" as an explicit gate. This practice fills that gap procedurally rather than changing the criteria.

## Validation Status

- [ ] Used for 3+ Framework Findings (tracking)
- [ ] Compared against established deferral practices in standards bodies (ISO, W3C, IETF)
- [ ] Assessed for Framework Findings submission (meta-finding: the Findings process itself may need a "sufficient evidence" gate)
- [ ] Adopted or rejected by Mission Framework

## Related

- FF-0001 (first application of "defer with revisit condition")
- docs/FRAMEWORK_FINDINGS.md — Dispositions, Review criteria
- docs/MISSION_CORE_ADMISSION.md — Admission criteria requiring cross-domain evidence
