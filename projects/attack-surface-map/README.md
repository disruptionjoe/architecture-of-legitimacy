# T6 Attack Surface Map

Status: review-prep surface map.

## Purpose

This directory holds non-adopted T6/RQ8 scaffolds for making attack scenarios,
detection evidence, false-positive hazards, and first-pilot capture-response
stops inspectable before any monitoring, disclosure, sanction, eligibility,
reviewer-authority, governance, rights, reward, AI-use, transfer, or public
posture rule is adopted.

This map is navigation only. It does not update the threat model, adopt
mitigations, require disclosure, define sanctions, change reviewer authority,
decide contributor eligibility, change governance, create rights or rewards,
move claim status, mark T6 passed, alter public posture, or create live
contribution records.

## Read Order

Use this order when trying to understand the current T6 attack-surface lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [T6 attack-surface map](2026-07-02-t6-attack-surface-map.md) | Concrete attack scenarios across economic, epistemic, governance, and cross-class capture surfaces. | No threat-model update, governance rule, reward rule, claim-status movement, public-posture movement, or T6 pass result. |
| 2 | [T6 detection evidence map](2026-07-06-t6-detection-evidence-map.md) | Separating observable record, inference, missing evidence, false-positive hazard, and local repair from escalation. | No monitoring, disclosure, sanction, contributor-limit, conflict, AI-use, reviewer-authority, appeal, emergency, rollback, rights, reward, transfer, public-label, or governance policy. |
| 3 | [T6 first-pilot detection false-positive screen](2026-07-09-t6-first-pilot-detection-false-positive-screen.md) | Forcing first-pilot capture and AI concerns through benign-explanation and local-trace-repair checks before escalation. | No pilot launch, target choice, live record, real contributor label, disclosure requirement, sanction, reviewer authority, governance, rights, reward, AI policy, transfer, claim/test status, or live contribution record. |

## Current Lane State

```yaml
lane_state: t6_attack_surface_review_prep_visible
attack_scenario_matrix: available
detection_evidence_contract: available
first_pilot_false_positive_screen: available
live_review_ready: false
monitoring_policy_state: not_adopted
disclosure_rule_state: not_adopted
sanction_policy_state: not_adopted
contributor_limit_state: not_adopted
reviewer_authority_state: unchanged
claim_status: unchanged
test_status: not_marked_passed
public_posture: unchanged
```

These labels are review-prep labels only. They are not contributor labels,
policy states, sanctions, reviewer-authority assignments, rights markers,
reward states, governance states, transfer states, claim verdicts, test
results, or public workflow terms.

## How To Read The Lane

Read the attack-surface map first to see the candidate attack scenarios and
which protocol layer each scenario pressures. Then read the detection evidence
map to separate direct observation from inference and escalation. Read the
first-pilot false-positive screen last, because it applies that distinction to
the synthetic first-pilot review-prep stack.

The central distinction is:

```text
The repo can prepare attack and capture review visibility; it has not
authorized monitoring, disclosure, sanctions, eligibility limits, reviewer
authority, rights, rewards, governance movement, transfer movement, public
posture movement, contribution records, or claim/test movement.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded T6/RQ8 attack-surface review-prep lane:

- [Attack profitability](../attack-profitability/) for capture variables,
  thresholds, first-pilot capture screens, and escalation labels.
- [AI role boundary](../ai-role-boundary/) for hidden-authority and AI-assisted
  review trace boundaries.
- [Pilot review readiness](../pilot-review-readiness/) for governed-review
  handoff, unresolved review questions, answerability labels, and packet order.
- [Second-ring synthesis](../second-ring-synthesis/) for the cross-lane
  governance, rights, capture, AI, reward, and transfer stop stack.
- [Founder phase constraint](../founder-phase-constraint/) for founder-power,
  phase-transition, emergency, rollback, and governance-stop boundaries.
- [Participant rights](../participant-rights/) and
  [reward readiness](../reward-readiness/) for rights, exit, recognition,
  retained-record, no-reward, and reward-stop boundaries.

## Stop Conditions

Stop for Joe or governed review before:

- selecting a real first-pilot target, source lane, contributor, reviewer
  owner, live record surface, public audience, or transfer context;
- filling a live source-trace packet or changing a synthetic packet into a live
  contribution object;
- opening an issue, pull request, review thread, public invitation, or
  contribution-log entry;
- editing the threat model, claims, tests, contribution standards,
  contribution templates, review policy, governance files, guardrails,
  participant-rights language, reward language, transfer posture, or
  public-facing posture surfaces;
- adopting monitoring, mitigation, disclosure, sanction, contributor-limit,
  conflict, AI-use, reviewer-authority, appeal, emergency, rollback,
  participant-rights, reward, transfer, public-label, or governance policy;
- treating synthetic capture scenarios as evidence about any real contributor;
- assigning contribution classifications, accepted/rejected states, sanctions,
  labels, test outcomes, claim-status movement, legal or financial meaning, or
  contribution-record meaning;
- or taking any non-GitHub external action.

## Safe Use

Use this map to find the current T6/RQ8 attack-surface artifacts and preserve
read order. Do not use it as evidence that live monitoring exists, disclosure
rules exist, sanctions exist, contributor limits exist, reviewer authority
exists, rights or rewards exist, a live contribution can be logged, or any
policy/status decision has already been made.
