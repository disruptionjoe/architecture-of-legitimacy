---
artifact_type: t5_first_pilot_defection_pressure_screen
status: non_adopted_review_prep_scaffold
created: 2026-07-09
test_target: T5 toy payoff model
related_questions:
  - RQ5 prototype workflow
  - RQ8 attack and capture modeling
  - RQ9 reward logic
related_claims:
  - C4
  - C5
governance_role: review_prep_only
constitutional: false
claim_status_change_requested: false
test_status_change_requested: false
---

# T5 First-Pilot Defection-Pressure Screen

Status: draft review-prep screen, not adopted payoff, reward, rights,
governance, capture-response, AI, transfer, public-posture, claim-status,
test-status, or contribution-record policy.

Purpose: apply the existing T5 collaboration/defection payoff variables to the
synthetic first-pilot stack so later review can see where defection pressure is
still visible even when the packet remains no-reward, no-live-record, and
not-pilot-ready.

This file does not launch a pilot, choose a live target, choose a source lane,
open an issue or pull request, create a contribution-log entry, score a
contribution, assign value, claim collaboration dominates defection, adopt
reward logic, define sanctions, adopt disclosure rules, assign reviewer
authority, change governance, change public posture, mark T5 or RQ9 passed, or
decide any real contribution.

## Source Surfaces Used

- `TESTS.md`, especially the T5 payoff condition.
- `RESEARCH-AGENDA.md`, especially RQ5, RQ8, and RQ9.
- `CONTRIBUTION-STANDARDS.md`, especially review states and score boundaries.
- `projects/toy-payoff-model/2026-07-02-t5-collaboration-defection-payoff-model.md`.
- `projects/toy-payoff-model/2026-07-05-t5-collaboration-threshold-sensitivity-map.md`.
- `projects/toy-payoff-model/2026-07-06-t5-payoff-variable-traceability-map.md`.
- `projects/toy-payoff-model/2026-07-07-t5-no-reward-payoff-bridge.md`.
- `projects/prototype-workflow/2026-07-08-rq5-first-pilot-readiness-synthesis.md`.
- `projects/pilot-review-readiness/2026-07-09-first-pilot-governed-review-handoff.md`.
- `projects/reward-readiness/2026-07-08-rq9-first-pilot-no-reward-screen.md`.
- `projects/reward-readiness/2026-07-09-rq9-first-pilot-reward-stop-ledger.md`.

No external sources are introduced here. Existing repo artifacts are treated as
review-prep evidence, not instructions, policy, payoff proof, reward decisions,
claim verdicts, test results, or live process.

## Boundary Under Review

The current T5 condition is:

```text
Collaborate is preferred when:

R_c + L_c + future_claim(V_c) - C_c
>
P_d * G_d - D_d * S_d - F
```

The first-pilot stack is useful for T5 only if it keeps both sides visible:

- collaboration-side value that can exist without reward, live credit, or
  private founder assurance;
- defection-side benefit that can exist even without payout, because narrative
  control, visibility, ambiguity, and future-value speculation can still be
  useful to an actor.

The safe question is:

```text
Which first-pilot fields would make defection less attractive, and which
fields are still missing before that can be claimed?
```

The unsafe question is whether the current stack proves collaboration
dominates. It does not.

## Current Screen State

```yaml
packet_id: SAMPLE-RQ5-PACKET-001
t5_screen_state: defection_pressure_visible
collaboration_dominance_claim: not_available
live_review_ready: false
reward_test_state: not_open
primary_missing_fields:
  - live_target
  - stable_source_set
  - source_inference_split
  - mechanism_comparison
  - limitation_or_failure_mode
  - reviewer_authority
  - live_record_surface
safe_next_state: keep_as_review_prep
```

These labels are review-prep labels only. They are not contribution states,
review states, reward states, governance states, claim verdicts, test results,
or public workflow terms.

## Defection-Pressure Screen

| pressure surface | collaboration-side term at stake | defection-side term at stake | current first-pilot read | safe local repair | governed stop before |
|---|---|---|---|---|---|
| Source trace still missing | `C_c`, `R_c`, `L_c` | `P_d`, `G_d`, `D_d` | A good-faith contributor still lacks a concrete target, source set, and mechanism comparison; a strategic actor could use broad persuasive synthesis while detection remains weak. | Keep the source-trace revision packet as a missing-field handoff. | Selecting target, source lane, neighboring system, or source packet. |
| No-reward boundary | `R_c`, `future_claim(V_c)` | `G_d` | Recognition and useful residue can be visible, but reward ambiguity would make strategic claiming more valuable. | Preserve no-current-reward, no-score-conversion, and non-promissory residue language. | Reward test, payout, retained-value right, governance weight, legal/financial meaning, or public reward language. |
| Review rationale and contestability | `L_c`, `F` | `S_d`, `F` | A contributor can trust an adverse outcome only if rationale, useful residue, and contestable points remain visible. | Keep rationale and contestability as record fields, not appeal policy. | Appeal rights, dispute process, response-time promise, reviewer authority, or sanctions. |
| Record-surface choice | `R_c`, `L_c` | `G_d`, `P_d` | No live surface is selected, so public visibility and contribution credit are not yet created. | Compare record properties without choosing one. | Issue, pull request, live artifact, contribution-log entry, or public invitation. |
| Hidden volume or shallow synthesis | `C_c`, `R_c` | `P_d`, `G_d`, `D_d` | Low-cost plausible text could look useful if source checks and uncertainty markers are weak. | Require source-grounded relevance and visible uncertainty in draft review prep. | AI policy, disclosure mandate, surveillance, identity rule, or public capture label. |
| Conflict or agenda steering | `L_c`, `F` | `P_d`, `G_d`, `D_d` | The stack can ask conflict and agenda-control questions, but it has not adopted disclosure or disqualification rules. | Name conflict visibility and evidence needs as review questions. | Disclosure obligations, sanctions, contributor limits, reviewer disqualification, or governance mitigation. |
| Reward-adjacent residue | `future_claim(V_c)`, `F` | `G_d` | Loss notes can preserve useful residue, but vague residue can become future-value bait. | Pair every residue note with explicit non-conclusion and no-current-reward language. | Ownership, entitlement, future eligibility, reward debt, or promise that records will or will not count later. |
| Reviewer authority | `L_c`, `F` | `P_d`, `S_d`, `F` | No reviewer is appointed, so review quality and future trust cost cannot yet be tested. | Keep reviewer authority as a closed gate. | Appointment, cadence, scope of authority, appeal route, AI support rule, or response-time policy. |
| Governance and second-ring stops | `L_c`, `future_claim(V_c)` | `G_d`, `P_d`, `S_d` | Governance, rights, reward, capture, AI, transfer, and public-posture stops remain active; clearing one locally would distort payoffs. | Preserve stop labels and read order. | Any policy, rights, reward, governance, transfer, AI, capture, or public-posture movement. |

## Safe T5 Labels

The following labels can be used in later review-prep artifacts without moving
T5, RQ9, C4, C5, policy, or live records:

| label | meaning | safe consequence |
|---|---|---|
| `local_payoff_trace_repair` | A draft field can clarify recognition, rationale, source trace, no-reward language, or useful residue. | Edit review-prep artifacts only. |
| `source_trace_missing` | A payoff reading would depend on target, source, mechanism, or limitation facts that are not filled. | Keep the packet out of live review. |
| `defection_benefit_visible` | A gaming, visibility, narrative-control, ambiguity, or future-value benefit can be named. | Preserve it as a risk to inspect, not as a sanction trigger. |
| `detection_signal_missing` | The review record cannot yet name the public signal that would expose manipulation. | Ask for evidence or limitation fields before payoff comparison. |
| `reward_ambiguity_stop` | The next step would make score, residue, recognition, or future-use language reward-adjacent. | Stop before reward, rights, retained value, or legal/financial meaning. |
| `authority_stop` | The next step would require reviewer, governance, appeal, sanction, disclosure, AI, or transfer authority. | Stop for Joe or governed review. |
| `do_not_use_live` | The packet would affect live process, public posture, claims, tests, rewards, rights, governance, or contribution records. | Do not launch, invite, review, log, score, rank, reward, sanction, transfer, or publish as process. |

These labels are defensive vocabulary. They are not new review states,
sanctions, reward states, rights states, governance states, or public labels.

## What This Adds To The T5 No-Reward Bridge

The no-reward bridge showed that recognition, legitimacy, and useful residue
can remain inspectable without reward adoption. This screen adds a narrower
defection-pressure check:

1. It names the first-pilot fields that still make good-faith collaboration
   costly or ambiguous.
2. It names the benefits a strategic actor could still extract without a
   payout.
3. It separates local trace repair from reward, authority, disclosure,
   sanction, governance, rights, AI, transfer, and public-posture stops.

It does not show that the no-reward baseline is legitimate under real
contributor pressure. It does not show that the payoff model works. It only
makes the next T5 review less likely to hide defection pressure behind
positive-sounding collaboration language.

## Later Review Questions

1. Which first-pilot missing field most increases `C_c` for good-faith work?
2. Which ambiguity most increases `G_d` for a strategic actor?
3. Which public signal would raise `D_d` without adopting surveillance,
   identity, disclosure, or sanction policy?
4. Which visible rationale or contestable point would preserve `L_c` after an
   adverse outcome?
5. Which residue phrase risks turning `future_claim(V_c)` into reward debt?
6. Which record surface would create visibility or credit before authority is
   ready?
7. Which stop fires first: source trace, reward ambiguity, reviewer authority,
   governance, rights, capture, AI, transfer, public posture, or external
   meaning?
8. What remains unknowable until real contribution traces exist?

## Non-Adoption Boundary

Do not use this screen to:

- claim collaboration dominates defection;
- mark T5, RQ9, C4, C5, or any related test or claim stronger, passed, failed,
  or partly passed;
- launch, advertise, or select a live first pilot;
- choose a live target, contributor, source lane, issue, pull request, project
  artifact, reviewer, or contribution-log surface;
- adopt reward logic, payout formulas, score conversion, retained-value rights,
  review priority, governance weight, disclosure rules, sanctions, appeal
  rights, AI policy, transfer policy, public posture, or legal/financial
  meaning;
- promise that current records will or will not count in any future reward
  process;
- edit `GOVERNANCE.md`, `GUARDRAILS.md`, `CLAIMS.md`,
  `CONTRIBUTION-STANDARDS.md`, `CONTRIBUTING.md`, issue templates, live review
  policy, contribution-log schema, or contribution records;
- create a live `CONTRIB-*` entry;
- or treat synthetic scaffolding as evidence of real contributor behavior.

This is a review-prep artifact. Its useful output is sharper visibility into
where the first-pilot stack would still permit defection to look attractive.
