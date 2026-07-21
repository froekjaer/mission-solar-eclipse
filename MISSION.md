# Mission Solar Eclipse — Mission Charter

**Status:** Initial reference mission baseline  
**Programme baseline:** Foundation Release v1.0

## Mission statement

Prepare for, conduct and evaluate a safe, evidence-grounded observation of a total solar eclipse, while using the work as the first real reference implementation of Mission Framework.

The mission has two inseparable outcomes:

1. a responsibly planned and executed eclipse observation; and
2. empirical evidence about whether Mission Framework is useful, coherent and operational under real constraints.

A successful eclipse experience without traceable framework learning is only a partial mission success. A useful framework experiment that neglects participant safety or the real observation objective is also a failure.

## Mission boundary

The initial reference implementation covers the smallest end-to-end slice needed to test the framework:

- define the observation purpose and participants
- identify astronomical, geographic, travel, safety and operational constraints
- define assessable objectives and acceptance criteria
- establish accountable roles and decision authority
- identify required capabilities, resources and dependencies
- record material assumptions, risks and contingency triggers
- preserve sources, observations, decisions and evidence
- execute or simulate key decision points
- assess outcomes and learning
- raise Framework Findings where implementation challenges canonical semantics

Detailed tourism planning, comprehensive astrophotography research and broad travel content are outside the initial slice unless they materially affect mission objectives, safety, evidence or contingency decisions.

## Initial objectives

### O1 — Observation readiness

Establish a reviewed plan that identifies the intended observation location or location-selection process, timing, required equipment, participant needs and material dependencies.

**Initial acceptance evidence:** approved mission plan, source references, dependency record and readiness review.

### O2 — Safe execution

Identify material safety concerns, accountable decisions, required controls and conditions that trigger escalation, relocation, cancellation or alternative observation modes.

**Initial acceptance evidence:** safety assumptions and controls, named authority, contingency criteria and decision records.

### O3 — Evidence integrity

Preserve the provenance, time, uncertainty and status of material astronomical facts, forecasts, observations, generated analysis and decisions.

**Initial acceptance evidence:** traceable source and observation records that distinguish fact, forecast, assumption, AI analysis and decision.

### O4 — Framework validation

Exercise the canonical Mission Loop through at least one complete path from reality and need through objective, capability, observation, evidence, decision, action, outcome and learning.

**Initial acceptance evidence:** mapped vertical slice and explicit gaps, ambiguities or confirmations.

### O5 — Framework feedback

Record implementation-derived semantic issues through the Framework Findings process.

**Initial acceptance evidence:** findings or an explicit reviewed conclusion that no semantic finding arose from the tested slice.

## Stakeholders and authority

The mission must identify, before consequential planning is treated as approved:

- mission sponsor or accountable mission authority
- operational coordinator
- participants and their relevant needs
- safety decision authority
- evidence or documentation steward
- owners of material travel, equipment and observation decisions

Names may be added when confirmed. Unknown ownership must remain explicitly unresolved and must not be replaced by an assumed AI or generic "team" authority.

## Core evidence classes

The mission records at least these classes separately:

| Class | Example | Required distinction |
|---|---|---|
| Astronomical source | eclipse timing or geometry | sourced calculation, not local observation |
| External condition | weather or transport forecast | time-sensitive forecast with retrieval time |
| Assumption | expected mobility or equipment availability | unverified planning premise |
| Decision | selected location or fallback trigger | accountable authority, basis and time |
| Observation | measured or directly recorded condition | observer or sensor, method and time |
| AI-assisted analysis | synthesis, comparison or suggestion | model provenance and human review status |
| Outcome evidence | what occurred and whether criteria were met | retrospective assessment linked to objectives |

## Reality and contingency rule

**Reality wins.** A preferred location, plan, forecast or model must yield when credible evidence shows that it is unsafe, unavailable or unlikely to meet the mission objective. If evidence is insufficient, the uncertainty must remain visible and be handled through an explicit decision or contingency threshold.

## Initial vertical slice

The first implementation should test a bounded decision such as location readiness or a weather-dependent fallback:

```text
Astronomical and geographic reality
        ↓
Observation opportunity and participant need
        ↓
Mission objective and acceptance criteria
        ↓
Location-selection capability and dependencies
        ↓
Forecasts, sources, assumptions and observations
        ↓
Evidence assessment
        ↓
Accountable go / relocate / fallback decision
        ↓
Action
        ↓
Observed outcome
        ↓
Learning and Framework Findings
```

The exact decision may be refined, but the slice must remain small enough to complete and review before broader mission documentation expands.

## Relationship to canonical semantics

Normative definitions remain in [Mission Framework](https://github.com/froekjaer/mission-framework), especially its canonical glossary. This charter applies those concepts to the eclipse mission.

Where this document needs a local interpretation that may conflict with canonical meaning, the interpretation must be labelled and linked to a [Framework Finding](https://github.com/froekjaer/mission-framework/blob/main/docs/FRAMEWORK_FINDINGS.md).

## Completion and learning

The mission is not complete merely because the eclipse date passes. Closure requires:

- assessment against objectives and acceptance criteria
- preservation of material decisions and outcome evidence
- review of failed assumptions and unused contingencies
- recorded participant and operational learning
- disposition or handoff of Framework Findings
- identification of reusable and non-reusable mission artefacts
