---
artifact_type: prior_art_collision_review_scaffold
status: synthetic_test_fixture
created: 2026-07-02
test_target: T9 prior-art collision check
governance_role: internal_test_record
constitutional: false
---

# T9 Prior-Art Collision Review Scaffold

Status: synthetic test fixture.

Purpose: prepare a disciplined first T9 prior-art collision review without
pretending that the comparison has already been performed.

This file is not a literature review, novelty verdict, claim-status decision,
governance decision, public-posture change, live contribution decision, or
evidence that T9 has passed. It is a bounded scaffold for comparing the repo's
coupled-stack claim to neighboring systems once source packets are attached.

## Source Surfaces Used

- `README.md`
- `CLAIMS.md`, especially C2 and C3
- `RESEARCH-AGENDA.md`
- `ROADMAP.md`
- `TESTS.md`
- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `LEGITIMACY-SCHEMA.md`
- `PROTOCOL-STACK.md`
- `THREAT-MODEL.md`

## Boundary Under Test

T9 asks whether the project's current novelty hypothesis survives comparison
with neighboring systems.

The hypothesis under test is not that every module is new. The live question is
whether this repo is studying a coupled object that binds contribution
accounting, legitimacy conditions, reward or retained-value rights, governance
transition, and capture monitoring inside one visible public proving ground.

For this scaffold, every comparison starts in this state:

```text
collision_result: unresolved
source_status: source_packet_required
claim_status_change: none
```

## Use Pattern

For each neighboring system, a later reviewer should attach a source packet
before making any collision claim.

Minimum source packet:

- one stable primary source or official description;
- one source that explains how the system works in practice, when available;
- a mechanism-level note for each relevant comparison axis;
- at least one limitation, uncertainty, or failure mode of the comparison;
- and a short statement separating source evidence from reviewer inference.

The useful result is not defending novelty. The useful result is narrowing,
strengthening, or demoting the coupled-stack claim with visible evidence.

## Comparison Axes

Use these axes before deciding whether a neighboring system collides with the
repo's current object.

| axis | review question | local surface |
|---|---|---|
| contribution_unit | What counts as a contribution, and can non-code or non-monetary work be represented? | `CONTRIBUTION-STANDARDS.md`, `PROTOCOL-STACK.md` |
| validation_path | Who decides whether work counts, and what rationale is visible? | `CONTRIBUTING.md`, `PROTOCOL-STACK.md` |
| value_logic | How is value assessed before reward or governance consequences attach? | `CONTRIBUTION-STANDARDS.md`, `TESTS.md` |
| legitimacy_conditions | Are visibility, contestability, voice, exit, adaptive rule change, bounded authority, and non-capture named? | `LEGITIMACY-SCHEMA.md` |
| record_trace | Can a future participant reconstruct the path from raw evidence to accepted record? | `CONTRIBUTIONS-LOG.md`, `PROTOCOL-STACK.md` |
| retained_value | Does accepted work create persistent recognition, rights, claims, or future reward eligibility? | `PROTOCOL-STACK.md`, `CLAIMS.md` |
| reward_timing | Does the system reward immediately, retroactively, symbolically, or not yet? | `RESEARCH-AGENDA.md`, `ROADMAP.md` |
| governance_transition | Are founder, maintainer, reviewer, voter, or participant powers named and transferred over time? | `GOVERNANCE.md`, `PROTOCOL-STACK.md` |
| capture_model | Does the system model gaming, capture, sybil behavior, cartel formation, or epistemic attack? | `THREAT-MODEL.md` |
| coupled_design | Are the above modules designed as one object, or as separate mechanisms loosely connected later? | `CLAIMS.md`, `README.md` |

## Candidate Neighboring Systems

These are candidates for a first T9 review packet, not conclusions about
similarity or difference.

| id | neighboring system or practice | why it is adjacent | first collision question | required source packet | collision status |
|---|---|---|---|---|---|
| T9-PA-01 | Gitcoin-style public-goods funding and quadratic funding | Allocates funds to public goods and must handle contribution value, sybil risk, and community legitimacy. | Does funding legitimacy rely on a coupled contribution-record workflow, or primarily on donation/voting mechanics? | Official program/mechanism docs; source explaining sybil/collusion controls; source on matching or allocation rules. | unresolved |
| T9-PA-02 | Optimism-style retroactive public-goods funding | Retroactively allocates value after work is visible and must justify impact judgments. | Does retroactive allocation preserve a contestable trace from contribution evidence to rights or reward, or mainly score impact after the fact? | Official retro-funding docs; round design or badgeholder process source; critique or limits source. | unresolved |
| T9-PA-03 | Wikipedia contribution, edit, and dispute processes | Public contribution, review, reputation, moderation, and dispute handling are visible at large scale. | Does the system bind contribution accounting to retained value and governance transition, or mostly govern knowledge production? | Policy/process source; edit/dispute or arbitration source; source on contributor rights or governance. | unresolved |
| T9-PA-04 | Academic peer review | Validates research contributions through reviewer judgment, citation, reputation, and publication decisions. | Does peer review provide legitimacy conditions and contribution accounting without solving reward rights or governance transition? | Journal or conference process source; source on reviewer authority/appeal; critique or reform source. | unresolved |
| T9-PA-05 | Open-source maintainer governance and BDFL models | Maintainers classify, accept, reject, and merge contributions while retaining project direction authority. | Does explicit maintainer authority plus contribution history already cover the founder-led legitimacy problem? | Project governance example; contribution review source; source on maintainer authority or transition. | unresolved |
| T9-PA-06 | DAO token-voting governance | Uses tokens or membership rules to allocate decision power and sometimes rewards. | Does token governance solve legitimacy, or does it shift the problem into wealth, turnout, delegation, and capture? | Governance docs; voting/delegation source; capture or plutocracy-risk source. | unresolved |
| T9-PA-07 | Commons-governance design principles | Studies institutional durability, participant boundaries, monitoring, sanctions, conflict resolution, and nested governance. | Does commons governance already provide the stronger formal object this repo is rediscovering? | Primary theory source; applied case source; limitation or transfer-risk source. | unresolved |
| T9-PA-08 | Participatory budgeting | Lets participants allocate public resources through deliberation, proposals, and voting. | Does the process connect contribution records and retained value, or focus on resource allocation decisions? | Program/process source; evaluation source; source on participation limits or capture. | unresolved |
| T9-PA-09 | Cooperative ownership and patronage allocation | Connects participation, ownership, governance, and surplus distribution. | Does cooperative practice already integrate contribution, legitimacy, reward rights, and governance transition in the target way? | Cooperative governance source; patronage or surplus allocation source; source on member exit/rights. | unresolved |
| T9-PA-10 | Reputation systems and prediction-market-adjacent mechanisms | Use forecasts, ratings, or reputation signals to aggregate judgment and allocate attention or value. | Does signal aggregation provide legitimacy, or does legitimacy still require contestable authority and retained-record design? | Mechanism source; governance or market-design source; failure-mode source. | unresolved |

## Collision Levels For Later Review

Use these levels only after source packets are attached.

| level | meaning | allowed consequence |
|---|---|---|
| no_collision_found | The neighbor shares labels or isolated mechanisms but does not contain the coupled object. | Preserve claim status; note mechanism differences. |
| module_overlap | The neighbor covers one or more modules better than this repo. | Narrow local novelty and import questions for future work. |
| coupled_overlap | The neighbor integrates several modules in a way that materially overlaps the current hypothesis. | Flag C2/C3 novelty for Joe/reviewer review; do not silently change claim status. |
| stronger_formalization | The neighbor contains the same object with better evidence, theory, or implementation. | Route a claim-demotion or reframing proposal; do not decide inside the fixture. |
| ambiguous | Evidence is incomplete, mixed, or too label-level. | Mark source packet incomplete and require mechanism-level comparison. |

## First Review Packet Template

```yaml
neighboring_system: ""
source_packet:
  primary_source: ""
  practice_source: ""
  critique_or_limit_source: ""
mechanism_notes:
  contribution_unit: ""
  validation_path: ""
  value_logic: ""
  legitimacy_conditions: ""
  record_trace: ""
  retained_value: ""
  reward_timing: ""
  governance_transition: ""
  capture_model: ""
  coupled_design: ""
source_vs_inference:
  directly_supported_by_sources:
    - ""
  reviewer_inferences:
    - ""
limitations:
  - ""
candidate_collision_level: ambiguous
claim_status_change_requested: false
follow_up_questions:
  - ""
```

## Red Flags For T9 Review

- A comparison uses familiar labels such as "governance," "DAO," "commons,"
  or "public goods" without mechanism-level detail.
- A source-backed overlap is treated as a defeat rather than a useful narrowing
  of the local claim.
- A novelty-preserving argument ignores an adjacent system's stronger evidence.
- A review confuses reward allocation with contribution legitimacy.
- A review treats votes, scores, citations, tokens, or AI summaries as
  legitimacy without checking visibility, contestability, exit, and capture.
- A claim-status change is smuggled into a test artifact without explicit
  review.

## Pass Criteria For A Later T9 Review

T9 can move toward a stronger result when:

- 10 neighboring systems have source packets;
- each comparison uses the same mechanism axes;
- each comparison separates source evidence from reviewer inference;
- at least one limitation or failure mode is named for each comparison;
- collision levels are assigned without private founder context;
- and any proposed claim narrowing, demotion, or strengthening is routed through
  review rather than decided inside the artifact.

This scaffold does not mark T9 passed. It gives the repo a repeatable structure
for discovering whether prior art narrows, strengthens, or defeats the current
coupled-stack novelty hypothesis.

## Boundary Notes

- No source packet has been completed here.
- No prior-art collision verdict has been made.
- No novelty claim has been accepted, rejected, narrowed, or strengthened.
- No claim status changed.
- No governance rule changed.
- No public posture changed.
- No T9 pass/fail state changed.
- No real contribution was submitted, accepted, revised, rejected, contested, or
  rewarded.
- No reward, retained-value, legal, or financial promise is created.
