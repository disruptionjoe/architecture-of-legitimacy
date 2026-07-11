# Toy Payoff Model Surface Map

Status: review-prep surface map.

## Purpose

This directory holds T5 scaffolds for making collaboration-versus-defection
payoff pressure inspectable before any claim that collaboration dominates,
before any reward logic is adopted, and before any live contribution trace is
used.

This map is navigation only. It does not change the payoff model, claim that
collaboration dominates defection, mark T5 or RQ9 passed, strengthen C4 or C5,
adopt reward logic, convert scores, create retained-value rights, define
sanctions, assign reviewer authority, change governance, change public posture,
or create live contribution records.

## Read Order

Use this order when trying to understand the current T5
collaboration/defection lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [Collaboration/defection payoff model](2026-07-02-t5-collaboration-defection-payoff-model.md) | Baseline synthetic contributor scenarios and the starter payoff terms for collaboration, legitimacy, future value, contribution cost, defection gain, detection, sanction, and future trust loss. | No payoff measurement, reward rule, contribution score, retained-value promise, governance decision, claim-status movement, or T5 pass. |
| 2 | [Collaboration-threshold sensitivity map](2026-07-05-t5-collaboration-threshold-sensitivity-map.md) | Which payoff term would need to change before collaboration becomes more attractive than defection, and whether that change is local repair or governed review. | No reward logic, payout formula, retained-value right, sanction policy, appeal path, contributor-rights policy, claim-status movement, or public-posture movement. |
| 3 | [Payoff variable traceability map](2026-07-06-t5-payoff-variable-traceability-map.md) | Visible trace fields needed before later reviewers apply payoff variables to real contribution cases. | No real contributor estimate, contribution ranking, reward model, C4 strengthening, sanction, disclosure, appeal, participant-rights, or public-posture policy. |
| 4 | [No-reward payoff bridge](2026-07-07-t5-no-reward-payoff-bridge.md) | How recognition, legitimacy, and non-promissory useful residue can remain inspectable when there is no payout, score conversion, retained-value right, governance weight, or legal/financial meaning. | No reward mechanism, future-reward promise, score conversion, retained-value right, priority, governance weight, legal/financial meaning, T5/RQ9 pass, or real contribution decision. |
| 5 | [First-pilot defection-pressure screen](2026-07-09-t5-first-pilot-defection-pressure-screen.md) | How payoff variables expose first-pilot source-trace gaps, no-reward ambiguity, rationale needs, record-surface pressure, hidden-volume risks, conflict pressure, residue ambiguity, reviewer authority stops, and second-ring stops. | No pilot launch, target or source-lane selection, live record surface, issue, pull request, contribution-log entry, reward adoption, sanction, disclosure rule, reviewer authority, claim/test movement, or live contribution state. |

## Current Lane State

```yaml
lane_state: t5_review_prep_visible
baseline_payoff_model: available
threshold_sensitivity_map: available
variable_traceability_map: available
no_reward_payoff_bridge: available
first_pilot_defection_pressure_screen: available
collaboration_dominance_claim: not_available
live_review_ready: false
reward_test_state: not_open
reward_policy_state: not_adopted
sanction_policy_state: not_adopted
reviewer_authority_state: unchanged
claim_status: unchanged
test_status: unchanged
public_posture: unchanged
```

These labels are review-prep labels only. They are not contribution states,
review states, reward states, sanction states, governance states, claim
verdicts, test results, or public workflow terms.

## How To Read The Lane

Read the baseline model first to see the synthetic variables and contributor
scenarios. Then read the sensitivity map and traceability map together: the
sensitivity map asks which variable would have to move, while the traceability
map asks what public evidence would make that variable inspectable.

The no-reward bridge should come next because it narrows recognition,
legitimacy, and useful-residue meanings before reward pressure enters. The
first-pilot defection-pressure screen comes last because it applies the T5
terms to the current synthetic first-pilot stack without claiming readiness or
collaboration dominance.

The central distinction is:

```text
The repo can prepare payoff-review visibility; it has not shown that
collaboration dominates defection, adopted reward logic, opened a reward test,
created rights or sanctions, launched review, or created live contribution
records.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded T5 payoff-modeling review-prep lane:

- [Prototype workflow](../prototype-workflow/) for the synthetic first-pilot
  packet, source-trace, record-surface, and review-prep bundle scaffolds.
- [Reward readiness](../reward-readiness/) for RQ9 reward boundaries,
  no-reward baseline pressure, and reward-stop labels.
- [Attack profitability](../attack-profitability/) and
  [attack surface map](../attack-surface-map/) for gaming, capture,
  detection, false-positive, and escalation pressure.
- [Value rubric options](../value-rubric-options/) and
  [value rubric dry run](../value-rubric-dry-run/) for score/rationale,
  disagreement, and reward-adjacent value boundaries.
- [Participant rights](../participant-rights/) for contestability, exit,
  retained-record, retained-value, and rights-stop boundaries.
- [AI role boundary](../ai-role-boundary/) for hidden AI volume,
  evidence-laundering, and synthetic-consensus risks.
- [Second-ring synthesis](../second-ring-synthesis/) for the cross-lane
  governance, rights, capture, AI, reward, and transfer stop stack.

## Stop Conditions

Stop for Joe or governed review before:

- claiming collaboration dominates defection or that the payoff model works for
  real contributors;
- marking T5, RQ9, C4, C5, or any related test or claim stronger, passed,
  failed, accepted, rejected, or partly satisfied;
- selecting a live first-pilot target, source lane, contributor, reviewer
  owner, live record surface, public audience, reward context, AI tool, or
  transfer context;
- opening an issue, pull request, review thread, public invitation, reward
  packet, reward test, contribution-log entry, or live payoff trace;
- scoring a real contribution, assigning value, estimating a real
  contributor's motivation, or treating synthetic cases as evidence about real
  contributor behavior;
- adopting reward logic, payout formulas, score conversion, review priority,
  governance weight, retained-value rights, ownership, future eligibility,
  sanctions, disclosure rules, appeal paths, reviewer-authority changes,
  participant-rights rules, AI policy, capture-response policy, transfer
  policy, or public posture;
- creating or implying legal, financial, tax, employment, securities, token,
  IP, ownership, contractual, accounting, or professional-review meaning;
- editing `GOVERNANCE.md`, `GUARDRAILS.md`, `CLAIMS.md`,
  `CONTRIBUTION-STANDARDS.md`, `CONTRIBUTING.md`, issue templates, live review
  policy, contribution-log schema, public posture, contribution records, or
  reward-facing language outside draft review-prep artifacts;
- promising that current records will or will not count in a future reward
  process;
- or taking any non-GitHub external action.

## Safe Use

Use this map to find the current T5 artifacts and preserve read order. Do not
use it as evidence that collaboration currently dominates defection, reward
logic exists, reward tests are open, scores convert, retained-value rights
exist, sanctions exist, reviewer authority exists, a contribution can be
logged, or any policy/status decision has already been made.
