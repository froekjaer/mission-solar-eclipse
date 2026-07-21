# Mission Solar Eclipse — Mission Plan

**Document:** MSOL-PLAN-0001  
**Version:** 0.1 — Initial Draft  
**Date:** 2026-07-21  
**Author:** z.ai (Mission Director)  
**Status:** Draft — pending Mission Owner review  

---

## 1. Mission Statement

Prepare for, conduct and evaluate a safe, evidence-grounded observation of the total solar eclipse of **August 2, 2027**, with primary target location in the **Luxor region, Egypt**, while using the work as the first real reference implementation of Mission Framework.

### 1.1 Dual Outcomes

1. A responsibly planned and executed eclipse observation
2. Empirical evidence about whether Mission Framework is useful, coherent and operational under real constraints

### 1.2 Success Definition

A successful eclipse experience without traceable framework learning is only a partial mission success. A useful framework experiment that neglects participant safety or the real observation objective is a failure. Both outcomes must be achieved.

---

## 2. Target Eclipse

| Parameter | Value |
|---|---|
| Date | Monday, August 2, 2027 |
| Saros | 136, member 38 of 71 |
| Magnitude | 1.079 |
| Max duration | 6 minutes 23 seconds |
| Path width | 258 km |
| Greatest eclipse | 10:07 UTC, 25.5°N, 33.2°E |
| Primary target | Luxor region, Egypt |
| Local eclipse time | ~13:40–14:08 EGY (UTC+3) |
| Totality at Luxor | ~6 minutes 22 seconds |
| Sun altitude at totality | ~75° above horizon |
| Fallback region | Southern Spain (Cádiz/Málaga), ~4.5 min totality |

### 2.1 Evidence: Eclipse Selection

See **DEC-0001** for the full eclipse selection decision, including alternatives table, rationale, and evidence sources.

---

## 3. Objectives and Acceptance Criteria

### O1 — Observation Readiness

Establish a reviewed plan that identifies the intended observation location, timing, required equipment, participant needs and material dependencies.

**Acceptance evidence:** Approved mission plan, source references, dependency record, readiness review.
**Target date:** June 2027 (T-2 months)

### O2 — Safe Execution

Identify material safety concerns, accountable decisions, required controls and conditions that trigger escalation, relocation, cancellation or alternative observation modes.

**Acceptance evidence:** Safety assumptions and controls, named authority, contingency criteria, decision records.
**Target date:** June 2027 (T-2 months), updated continuously

### O3 — Evidence Integrity

Preserve the provenance, time, uncertainty and status of material astronomical facts, forecasts, observations, generated analysis and decisions.

**Acceptance evidence:** Traceable source and observation records that distinguish fact, forecast, assumption, AI analysis and decision.
**Target date:** Post-mission (August-September 2027)

### O4 — Framework Validation

Exercise the canonical Mission Loop through at least one complete path from reality and need through objective, capability, observation, evidence, decision, action, outcome and learning.

**Acceptance evidence:** Mapped vertical slice and explicit gaps, ambiguities or confirmations.
**Target date:** Post-mission (September 2027)

### O5 — Framework Feedback

Record implementation-derived semantic issues through the Framework Findings process.

**Acceptance evidence:** Findings or an explicit reviewed conclusion that no semantic finding arose from the tested slice.
**Target date:** Continuous, with final synthesis post-mission

---

## 4. Stakeholders and Authority

**Note:** Names marked `[TBC]` require confirmation from the Mission Owner.

| Role | Actor | Status |
|---|---|---|
| Mission Owner / Sponsor | Peter Frøkjær | Confirmed (MISSION.md) |
| Mission Director | z.ai (AutoClaw) | Delegated (Mission Order, 2026-07-21) |
| Chief Architect | ChatGPT (OpenAI) | Confirmed (INVITATION.md) |
| Lead Software Engineer | Codex | Confirmed (Mission Order) |
| Research Director | Peter Frøkjær | Confirmed (Mission Order) |
| Safety Decision Authority | `[TBC]` | **Requires named human** |
| Operational Coordinator | `[TBC]` | **Requires named human** |
| Evidence Steward | `[TBC]` | **Requires named human** |
| Travel/Observation Owner | `[TBC]` | **Requires named human** |
| Participants | `[TBC]` | **Requires identification** |

### 4.1 Authority Delegation Chain

```text
Peter (Mission Owner, accountable authority)
    ↓ delegates planning authority to
z.ai (Mission Director)
    ↓ may sub-delegate bounded research/analysis to
AI sub-agents (one-shot, bounded scope)
    ↓ decisions requiring human accountability escalate to
Peter or named human authority [TBC]
```

### 4.2 Urgent Gap

The following roles currently have **no identified human**:
- Safety Decision Authority
- Operational Coordinator
- Evidence Steward

These must be filled before the Go/No-Go decision point (T-2 months). Unfilled roles will trigger a No-Go.

---

## 5. Timeline and Milestones

### 5.1 Phase Overview

| Phase | Period | Key Activities |
|---|---|---|
| **Phase 0: Foundation** | Jul–Sep 2026 | Mission plan, stakeholder identification, initial equipment research |
| **Phase 1: Planning** | Oct–Dec 2026 | Equipment selection, budget, travel logistics research, site reconnaissance |
| **Phase 2: Preparation** | Jan–Apr 2027 | Equipment acquisition, testing, weather monitoring plan, safety review |
| **Phase 3: Readiness** | May–Jun 2027 | Final location decision, Go/No-Go, travel booking, rehearsals |
| **Phase 4: Execution** | Jul–Aug 2027 | Travel, observation, data preservation |
| **Phase 5: Learning** | Aug–Sep 2027 | Evidence review, framework findings, mission closeout |

### 5.2 Key Milestones

| Milestone | Target Date | Gate |
|---|---|---|
| M1: Mission Plan Approved | Sep 2026 | Mission Owner review |
| M2: Equipment Selection Complete | Nov 2026 | Technical review |
| M3: Budget Approved | Dec 2026 | Mission Owner |
| M4: Safety Plan Reviewed | Mar 2027 | Safety Authority [TBC] |
| M5: Equipment Acquired and Tested | May 2027 | Technical verification |
| M6: Location Decision (Luxor vs. Fallback) | Jun 2027 | Weather-dependent, Go/No-Go trigger |
| M7: Travel Booked | Jun 2027 | M6 Go required |
| M8: Pre-Flight Review | Jul 2027 | Final readiness check |
| M9: Eclipse Observation | Aug 2, 2027 | Execution |
| M10: Data Verified and Preserved | Aug 2027 | Evidence Steward |
| M11: Mission Closeout Report | Sep 2027 | Mission Owner |

### 5.3 Go/No-Go Criteria

**Go requires:**
1. All `[TBC]` safety-critical roles filled with named, briefed humans
2. Equipment acquired, tested, and verified functional
3. Weather forecast for target location ≤20% cloud probability at T-48h (or fallback decision triggered)
4. All participants briefed on safety protocols
5. Travel and accommodation confirmed
6. Data preservation plan verified (redundant storage, backup procedures)
7. Mission Owner approval

**No-Go triggers:**
1. Any unfilled safety-critical role
2. Equipment failure without backup
3. Weather forecast >50% cloud probability at both primary and fallback within 48h
4. Safety concerns unresolved
5. Participant withdrawal below minimum viable team
6. Mission Owner veto

---

## 6. Risk Assessment

### 6.1 Risk Register (Initial)

| ID | Risk | Probability | Impact | Mitigation | Status |
|---|---|---|---|---|---|
| R1 | Cloud cover at Luxor | Low (<3%) | Critical | Fallback to Spain; real-time weather monitoring | Monitored |
| R2 | Extreme heat (40°C+) at Luxor | High | Medium | Hydration plan, shade, early setup, medical kit | Needs plan |
| R3 | Equipment failure in transit | Medium | Critical | Carry-on critical optics; backup camera body; insurance | Needs plan |
| R4 | Participant illness/injury | Medium | High | Travel insurance, medical evacuation plan, first aid training | Needs plan |
| R5 | Political instability in Egypt | Low | Critical | Monitor travel advisories; fallback to Spain | Monitored |
| R6 | Solar filter damage/failure | Low | Critical | Redundant filters; pre-use inspection; never look without verified filter | Needs plan |
| R7 | Data loss/corruption | Medium | High | Redundant storage; off-site backup before leaving site; checksums | Needs plan |
| R8 | COVID/health travel restrictions | Unknown | High | Monitor entry requirements; flexible booking | Monitored |
| R9 | Framework proves inadequate | Medium | Low | Document findings; reality wins over framework | Accepted |
| R10 | Budget overrun | Medium | Medium | Contingency reserve; phased commitment | Needs plan |

### 6.2 Uncertainty Declaration

The mission explicitly acknowledges:
- **Weather is the irreducible uncertainty** — even at <3% historical cloud cover, eclipse-day cloud is possible
- **Travel restrictions** between now and 2027 are unknowable
- **Equipment availability** may change (discontinued models, supply chain)
- **Personal circumstances** of participants may change

These are not risks to be eliminated. They are uncertainties to be monitored, with contingency triggers defined.

---

## 7. Dependencies

### 7.1 Critical Dependencies

| Dependency | Type | Owner | Status |
|---|---|---|---|
| Astronomical ephemeris | External (NASA/ESA) | Public source | Verified |
| Weather forecasting | External (meteorological services) | Public source | Identified |
| Travel infrastructure | External (airlines, hotels) | `[TBC]` | Needs booking |
| Observation equipment | Internal (acquisition) | `[TBC]` | Needs selection |
| Solar safety certification | External (ISO 12312-2) | Equipment vendor | Needs verification |
| Egyptian entry requirements | External (government) | `[TBC]` | Needs monitoring |
| Mission Framework v1.0+ | Internal (framework repo) | ChatGPT (Chief Architect) | In progress |

### 7.2 Dependency Descent (Partial)

```text
Mission Solar Eclipse
    ↓ depends on
Eclipse observation capability
    ↓ depends on
Optical equipment + Solar safety + Accurate timing + Clear skies + Participant presence
    ↓ depends on
Camera body/lens/filter procurement + ISO-certified solar filters + GPS time sync + Weather forecasting + Travel logistics
    ↓ depends on
Budget approval + Vendor availability + Satellite data + Airline schedules + Hotel availability
    ↓ depends on
Mission Owner decision + Global supply chain + GPS constellation + Meteorological infrastructure + Egyptian tourism sector
    ↓ terminates at
Physical reality (Sun, Moon, Earth orbital mechanics)
```

The descent exposes that **the mission's deepest dependency is on celestial mechanics** — an unchangeable, perfectly predictable physical reality. This is unusual for a mission and should be explicitly celebrated as a framework test case: *what happens when the fundamental dependency is 100% reliable?*

---

## 8. Evidence Plan (Initial)

### 8.1 Evidence Classes

Per the Mission Charter, the following evidence classes must be separately recorded:

| Class | Example | Plan |
|---|---|---|
| Astronomical source | Eclipse timing, geometry | NASA eclipse bulletin, cited with retrieval date |
| External condition | Weather forecast, travel advisory | Screenshot/save with timestamp; record retrieval time |
| Assumption | Equipment availability, participant commitment | Explicitly labelled as unverified until confirmed |
| Decision | Location selection, Go/No-Go | Recorded in DEC-XXXX format |
| Observation | Eclipse photographs, weather measurements | With EXIF, GPS, observer, method, time |
| AI-assisted analysis | Eclipse research compilation | Model, version, task, timestamp, human review status |
| Outcome evidence | What occurred vs. planned | Post-mission assessment linked to objectives |

### 8.2 Provenance Rules

- Original observations are immutable (write-once storage)
- All transformations are logged (e.g., RAW→JPEG conversion parameters)
- All AI-generated content retains model provenance
- Cryptographic hashes for all digital evidence (SHA-256 minimum)

---

## 9. Next Actions

### Immediate (Jul–Sep 2026)
- [ ] Mission Owner reviews and approves this plan
- [ ] Identify and confirm all `[TBC]` role holders
- [ ] Begin equipment research (cameras, lenses, filters, mounts)
- [ ] Research Luxor logistics (flights, hotels, local transport, site access)
- [ ] Research Spain fallback logistics (Cádiz/Málaga area)
- [ ] Define budget envelope

### Phase 1 (Oct–Dec 2026)
- [ ] Equipment selection and procurement plan
- [ ] Detailed travel and logistics plan
- [ ] Weather monitoring plan (long-range forecasting subscription)
- [ ] Safety plan draft
- [ ] First rehearsal/training plan

### Deferred
- Detailed astrophotography technique research
- Post-mission publication planning
- Framework validation methodology (waiting on framework stabilization)

---

## 10. Framework Findings (Initial)

| FF-XXXX | Title | Status |
|---|---|---|
| FF-0001 | No sub-agent or delegated research concept | Deferred — revisit after additional decisions |

---

## 11. Document Control

| Version | Date | Author | Changes |
|---|---|---|---|
| 0.1 | 2026-07-21 | z.ai | Initial draft following DEC-0001 eclipse selection |

### Review Status

- [ ] Mission Owner (Peter)
- [ ] Chief Architect (ChatGPT)
- [ ] Research Director (Peter)
- [ ] Safety Authority `[TBC]`
