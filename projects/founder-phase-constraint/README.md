# RQ6 Founder Phase Constraint Surface Map

Status: review-prep surface map.

## Purpose

This directory holds non-adopted RQ6/T7 scaffolds for making founder powers,
phase-transition evidence, emergency and rollback boundaries, first-pilot
governance evidence, and authority-movement stops inspectable before any
governance move.

This map is navigation only. It does not adopt founder powers, founder limits,
transition triggers, rollback rules, emergency authority, reviewer authority,
appeal paths, participant rights, reward policy, AI policy, transfer posture,
public posture, claim status, test status, or live contribution records.

## Read Order

Use this order when trying to understand the current founder-phase constraint
lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [T7 founder-phase constraint review prep](2026-07-02-t7-founder-phase-constraint-review-prep.md) | Founder-power decision slots, evidence requirements, pass criteria, and future governance-review prompts. | No founder power, founder limit, transition trigger, emergency rule, rollback rule, reviewer-selection rule, participant right, appeal path, claim, reward, or record movement. |
| 2 | [RQ6 phase-transition evidence scaffold](2026-07-03-rq6-phase-transition-evidence-scaffold.md) | Evidence tiers and phase-transition review requirements from Phase 0 through generalization. | No phase transition, transition trigger, founder-power movement, reviewer authority, emergency rule, rollback rule, rights, reward, claim, or public-posture movement. |
| 3 | [RQ6 emergency and rollback boundary map](2026-07-06-rq6-emergency-rollback-boundary.md) | Trigger, scope, expiration, contestability, and record-preservation fields for any later exception-authority review. | No emergency power, rollback rule, privacy rule, retention rule, appeal path, founder limit, reviewer authority, or public-posture policy adoption. |
| 4 | [RQ6 first-pilot governance-evidence packet](2026-07-07-rq6-first-pilot-governance-evidence-packet.md) | What current first-pilot scaffolds would and would not show as governance-transition evidence. | No pilot launch, live target, reviewer appointment, founder-power definition, phase movement, emergency rule, rollback rule, rights, reward, claim, test, or live-record movement. |
| 5 | [RQ6 first-pilot governance-stop ledger](2026-07-09-rq6-first-pilot-governance-stop-ledger.md) | Stop labels for local trace repair, source-trace gaps, second-ring governed stops, authority movement, public or live use, and do-not-use-live states. | No live pilot, reviewer authority, founder-power movement, phase transition, emergency action, rollback action, public posture, claim/test movement, or contribution-record creation. |

## Current Lane State

```yaml
lane_state: rq6_governance_transition_review_prep_visible
founder_power_inventory: draft_review_slots_only
phase_transition_state: not_adopted
phase_transition_evidence: review_prep_only
emergency_authority_state: not_adopted
rollback_authority_state: not_adopted
reviewer_authority_state: unchanged
first_pilot_governance_evidence: packet_shape_only
live_review_ready: false
source_trace_state: source_trace_still_missing
rights_state: no_current_rights_or_retained_value_commitment
reward_state: no_current_reward
transfer_state: horizon_only
claim_status: unchanged
test_status: not_marked_passed
public_posture: unchanged
```

These labels are review-prep labels only. They are not governance states,
phase states, contribution states, issue labels, authority assignments, rights
states, reward states, claim verdicts, test results, or public workflow terms.

## How To Read The Lane

Read the T7 prep first to understand the founder-power decision slots. Then
read the phase-transition scaffold to see what evidence a later governance
review would need before any phase movement. The emergency and rollback map
separates temporary correction from permanent hidden control. The first-pilot
governance-evidence packet then shows why first-pilot workflow evidence is not
the same as governance-transition evidence. Read the governance-stop ledger
last, because it turns the newer first-pilot stack into concrete stop labels.

The central distinction is:

```text
The repo can prepare governance-review visibility; it has not authorized a
pilot, reviewer role, founder-power change, phase transition, emergency rule,
rollback rule, rights or reward move, public-posture move, contribution record,
or claim/test move.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded RQ6/T7 governance-transition review-prep lane:

- [Second-ring synthesis](../second-ring-synthesis/) for the dependency map and
  first-pilot stop stack across governance, rights, capture, AI, reward, and
  transfer lanes.
- [Pilot review readiness](../pilot-review-readiness/) for governed-review
  handoff, unresolved review questions, answerability labels, and packet order.
- [Prototype workflow](../prototype-workflow/) for RQ5 source-trace, live
  surface, revision, and review-prep bundle scaffolds.
- [Participant rights](../participant-rights/) for voice, exit,
  contestability, retained-record, and rights-stop boundaries.
- [Attack profitability](../attack-profitability/) and
  [attack surface map](../attack-surface-map/) for capture and detection stops
  that can affect governance authority.
- [AI role boundary](../ai-role-boundary/) for hidden-authority and AI-assisted
  review constraints.
- [Reward readiness](../reward-readiness/) for no-reward and reward-stop
  boundaries before governance weight or retained-value meaning exists.
- [Generalization](../generalization/) for transfer and public-language
  boundaries before broader institutional claims.

## Stop Conditions

Stop for Joe or governed review before:

- selecting a real first-pilot target, source lane, contributor, reviewer
  owner, live record surface, public audience, transferred power, phase
  transition, emergency trigger, rollback trigger, or governance-review object;
- filling a source-trace packet or changing a synthetic packet into a live
  contribution object;
- opening an issue, pull request, review thread, public invitation, or
  contribution-log entry;
- editing governance files, guardrails, claims, test-status surfaces,
  contribution standards, contribution templates, issue templates, review
  policy, public posture, or live contribution records;
- adopting founder powers, founder limits, transition triggers, phase movement,
  emergency rules, rollback rules, reviewer authority, appeal paths, dispute
  process, response-time promises, participant rights, identity policy,
  retention policy, reward logic, retained-value rights, governance weight, AI
  policy, capture response, transfer criteria, or public language;
- assigning prior-art collision levels, contribution classifications, scores,
  accepted/rejected states, sanctions, legal or financial meaning, test
  outcomes, claim-status movement, or contribution-record meaning;
- importing governance machinery from another repository as adopted local
  policy;
- or taking any non-GitHub external action.

## Safe Use

Use this map to find the current RQ6/T7 artifacts and preserve read order. Do
not use it as evidence that founder powers are fully specified, a phase
transition is ready, emergency or rollback authority exists, reviewer authority
exists, a first pilot can launch, participant rights or rewards exist, transfer
is approved, public governance language is safe, or any policy/status decision
has already been made.
