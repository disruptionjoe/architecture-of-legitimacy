# RQ8 Attack Profitability Surface Map

Status: review-prep surface map.

## Purpose

This directory holds non-adopted RQ8 scaffolds for making attack profitability,
capture thresholds, first-pilot capture visibility, and capture-escalation
stops inspectable before any capture response becomes policy.

This map is navigation only. It does not adopt mitigations, monitoring,
disclosure rules, sanctions, contributor limits, reviewer authority, governance
rules, rights, rewards, transfer posture, public posture, claim status, test
status, or live contribution records.

## Read Order

Use this order when trying to understand the current RQ8 capture-modeling lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [RQ8 attack-profitability variable map](2026-07-03-rq8-attack-profitability-variable-map.md) | Shared variable vocabulary for attacker benefit, success probability, cost, mitigation friction, detection, sanction, and reputation cost. | No threat-model update, mitigation adoption, reward decision, governance rule, rights policy, claim movement, public-posture movement, or test result. |
| 2 | [RQ8 capture threshold map](2026-07-06-rq8-capture-threshold-map.md) | Boundary between local workflow repair and escalation into policy, rights, rewards, sanctions, disclosure, reviewer authority, governance, or public posture. | No mitigation, disclosure, sanction, eligibility, appeal, reward, rights, founder-power, governance, or public-claim adoption. |
| 3 | [RQ8 first-pilot capture screen](2026-07-07-rq8-first-pilot-capture-screen.md) | Capture observability prompts for the synthetic first-pilot packet before any live pilot, target, record surface, or contributor context exists. | No pilot launch, target choice, live record, disclosure requirement, sanction, reviewer authority, governance, rights, reward, threat-model update, claim movement, or test movement. |
| 4 | [RQ8 first-pilot capture escalation ledger](2026-07-09-rq8-first-pilot-capture-escalation-ledger.md) | Labels for local visibility repair, source-trace gaps, benign explanations, governed-response stops, and do-not-use-live states. | No live response, contributor label, mitigation, monitoring, disclosure, sanction, contributor limit, transfer, public posture, claim/test status, or contribution-record movement. |

## Current Lane State

```yaml
lane_state: rq8_capture_modeling_review_prep_visible
variable_map: available
threshold_map: available
first_pilot_capture_screen: available
capture_escalation_ledger: available
live_review_ready: false
source_trace_state: source_trace_still_missing
mitigation_policy_state: not_adopted
monitoring_policy_state: not_adopted
disclosure_rule_state: not_adopted
sanction_policy_state: not_adopted
contributor_limit_state: not_adopted
reviewer_authority_state: unchanged
claim_status: unchanged
test_status: not_marked_passed
public_posture: unchanged
```

These labels are review-prep labels only. They are not contribution states,
issue labels, policy states, sanctions, reviewer-authority assignments, rights
markers, reward states, governance states, transfer states, claim verdicts, or
test results.

## How To Read The Lane

Read the variable map first to get the attack-profitability vocabulary. Then
read the threshold map to separate local workflow repair from governed policy
movement. The first-pilot capture screen applies those boundaries to the
synthetic first-pilot packet. The escalation ledger then sorts remaining
capture concerns into local repair, source-trace, benign-explanation, governed
response, and do-not-use-live states.

The central distinction is:

```text
The repo can prepare capture-review visibility; it has not authorized capture
response policy, monitoring, disclosure mandates, sanctions, contributor
limits, reviewer authority, rights, rewards, governance movement, transfer
movement, public-posture movement, contribution records, or claim/test movement.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded RQ8 capture-modeling review-prep lane:

- [Attack surface map](../attack-surface-map/) for T6 attack scenarios,
  detection evidence, and false-positive screens.
- [Prototype workflow](../prototype-workflow/) for the synthetic first-pilot
  packet, source-trace, record-surface, and review-prep bundle scaffolds.
- [AI role boundary](../ai-role-boundary/) for hidden-authority, AI-volume, and
  AI-assisted review trace boundaries.
- [Participant rights](../participant-rights/) for voice, exit,
  contestability, retained-record, and rights-stop boundaries.
- [Reward readiness](../reward-readiness/) for no-reward baseline and
  reward-stop boundaries.
- [Second-ring synthesis](../second-ring-synthesis/) for the cross-lane
  governance, rights, capture, AI, reward, and transfer stop stack.

## Stop Conditions

Stop for Joe or governed review before:

- selecting a real first-pilot target, source lane, contribution unit,
  contributor, reviewer owner, live record surface, public audience, or
  transfer context;
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
  labels, test outcomes, claim-status movement, legal/financial meaning, or
  contribution-record meaning;
- or taking any non-GitHub external action.

## Safe Use

Use this map to find the current RQ8 attack-profitability artifacts and preserve
read order. Do not use it as evidence that a live capture-response procedure
exists, monitoring exists, disclosure rules exist, sanctions exist, contributor
limits exist, reviewer authority exists, rights or rewards exist, a contribution
can be logged, or any policy/status decision has already been made.
