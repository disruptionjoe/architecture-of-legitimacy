# Value Rubric Options Surface Map

Status: navigation surface map.

## Purpose

This directory contains non-adopted RQ3/T2 scaffolds for making early value
rubric options, dimension failure modes, first-pilot value screens, and value
disagreement labels inspectable before any active rubric or review policy
changes.

This map is navigation only. It does not adopt rubric policy, score policy,
score aggregation, review policy, reviewer authority, reward logic,
retained-value meaning, governance rules, claim status, test status, public
posture, contribution standards, issue templates, contribution-log schema, or
live contribution records.

## Read Order

Use this order when trying to understand the current value-rubric options lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [RQ3 initial value-rubric options scaffold](2026-07-02-rq3-value-rubric-options.md) | Candidate rubric shapes, value/reviewability separation, failure modes, and later adoption questions. | No rubric option, score meaning, reviewer authority, reward, governance, claim, public-posture, or contribution decision. |
| 2 | [RQ3 value-rubric dimension failure map](2026-07-06-rq3-dimension-failure-map.md) | Dimension-by-dimension false positives, collapse risks, repair questions, and T2 dry-run prompts. | No dimension adoption, score aggregation, contribution-standard, reward, governance, claim, test, or real-contribution movement. |
| 3 | [RQ3 first-pilot value screen](2026-07-08-rq3-first-pilot-value-screen.md) | Non-scoring screen for what value information a synthetic first-pilot packet can preserve before score, reward, ranking, or policy meaning. | No score, rank, reward, reviewer authority, first-pilot launch, T2/RQ5 pass, template, policy, or live-record movement. |
| 4 | [RQ3 first-pilot value-disagreement ledger](2026-07-09-rq3-first-pilot-value-disagreement-ledger.md) | Review-prep labels for source-trace gaps, dimension ambiguity, class prompts, governed-meaning risk, reward leakage, and taste conflict. | No live review state, score, rank, reward, acceptance, contribution record, governance, claim, test, or public-posture movement. |

## Current Lane State

```yaml
lane_state: value_rubric_review_prep_visible
options_scaffold: available
dimension_failure_map: available
first_pilot_value_screen: available
first_pilot_value_disagreement_ledger: available
active_rubric_policy_state: unchanged
score_meaning_state: not_adopted
score_aggregation_state: not_adopted
reviewer_authority_state: unchanged
reward_meaning_state: not_adopted
claim_status: unchanged
test_status: not_marked_passed
public_posture: unchanged
live_review_ready: false
```

These labels are review-prep labels only. They are not contribution states,
issue labels, score states, reward states, reviewer-authority assignments,
governance states, claim verdicts, test results, public-posture labels, or
contribution-record meanings.

## How To Read The Lane

Read the options scaffold first to understand the candidate rubric shapes and
the distinction between reviewability, value judgment, acceptance, reward, and
governance authority. Then read the dimension failure map to see how the seven
provisional dimensions can produce false positives or collapse into each other.

The first-pilot value screen applies those distinctions to the synthetic RQ5
packet without scoring it. The value-disagreement ledger should come last
because it turns the screen into review-prep labels a later governed review can
preserve before any score discussion or live use.

The central distinction is:

```text
The repo can prepare value-rubric review visibility; it has not authorized
rubric adoption, score meanings, score aggregation, reviewer authority, reward
logic, governance movement, claim/test movement, public-posture movement,
contribution standards, or live contribution records.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded RQ3/T2 value-rubric review-prep lane:

- [Value rubric dry run](../value-rubric-dry-run/) for T2 synthetic scoring
  examples and reviewer-disagreement mapping.
- [Contribution taxonomy](../contribution-taxonomy/) for RQ2/T1 class,
  evidence-minimum, ambiguity, and review-path scaffolds.
- [Prototype workflow](../prototype-workflow/) for RQ5 packet, source-trace,
  record-surface, revision, and review-prep bundle scaffolds.
- [Pilot review readiness](../pilot-review-readiness/) for governed-review
  handoff, question-register, answerability, and packet-map surfaces.
- [Reward readiness](../reward-readiness/) for RQ9 no-reward baseline,
  reward-boundary, and first-pilot reward-stop scaffolds.

## Stop Conditions

Stop for Joe or governed review before:

- changing active rubric dimensions, score meanings, score aggregation,
  contribution standards, review states, reviewer authority, issue templates,
  contribution templates, contribution-log schema, governance files, guardrails,
  claims, test-status surfaces, or public-facing posture surfaces;
- assigning scores, ranks, accepted/revised/rejected states, value verdicts,
  reward meaning, retained-value rights, governance weight, legal/financial
  meaning, claim-status movement, test-status movement, public language, or
  contribution-record meaning;
- selecting a real first-pilot target, source lane, contribution unit,
  contributor, reviewer owner, live record surface, public audience, reward
  context, or transfer context;
- treating synthetic packet notes, review-prep labels, score discussion, AI
  output, or private founder context as source evidence, review authority,
  reward entitlement, participant right, governance authority, or live record;
- opening an issue, pull request, review thread, public invitation, score
  ledger, contribution-log entry, or non-GitHub external action;
- storing private, confidential, regulated, proprietary, or unsafe material in
  the public repo.

## Safe Use

Use this map to find the current RQ3/T2 value-rubric options artifacts and
preserve read order. Do not use it as evidence that an active rubric policy
exists, score meanings exist, reviewer authority exists, rewards exist, rights
exist, a contribution can be logged, a pilot is live, or any policy/status
decision has already been made.
