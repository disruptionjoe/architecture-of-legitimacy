# Value Rubric Dry Run Surface Map

Status: navigation surface map.

## Purpose

This directory contains non-adopted T2 scaffolds for pressure-testing whether
the current value rubric surfaces useful disagreement across synthetic
contribution examples before any active rubric, score, review, reward, or
policy meaning changes.

This map is navigation only. It does not adopt rubric policy, score meanings,
score aggregation, review policy, reviewer authority, contribution standards,
contribution templates, issue templates, contribution-log schema, reward logic,
retained-value meaning, governance rules, claim status, test status, public
posture, or live contribution records.

## Read Order

Use this order when trying to understand the current T2 value-rubric dry-run
lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [T2 value rubric dry run](2026-07-02-t2-value-rubric-dry-run.md) | Synthetic contribution samples, provisional score vectors, and the first pass at whether the seven dimensions expose useful tradeoffs. | No active score meaning, aggregation rule, review state, reward meaning, claim/test movement, or real contribution decision. |
| 2 | [T2 reviewer-disagreement map](2026-07-07-t2-reviewer-disagreement-map.md) | Disagreement labels for evidence gaps, dimension boundaries, class sensitivity, governance stops, reward leakage, and taste conflict. | No score revision, reviewer authority, reward entitlement, governance permission, contribution-standard edit, T2 pass, or live record. |

## Current Lane State

```yaml
lane_state: synthetic_value_rubric_review_prep_visible
dry_run_fixture: available
reviewer_disagreement_map: available
active_rubric_policy_state: unchanged
score_meaning_state: discussion_only
score_aggregation_state: not_adopted
reviewer_authority_state: unchanged
reward_meaning_state: absent
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

Read the dry-run fixture first to see the synthetic samples, provisional score
vectors, and boundary observations. The useful result is not identical scoring;
the useful result is whether disagreement exposes evidence gaps, dimension
ambiguity, class-sensitive prompts, governance stops, reward leakage, or
arbitrary taste.

Then read the reviewer-disagreement map to classify why reviewers might diverge
on the same sample. It turns score disagreement into inspection prompts for a
later T2/RQ3 review without changing score meanings or deciding whether any
real contribution is valuable, accepted, rewarded, or policy-relevant.

The central distinction is:

```text
The repo can prepare value-rubric disagreement visibility; it has not
authorized active score meanings, score aggregation, reviewer authority,
reward logic, governance movement, claim/test movement, public-posture
movement, contribution standards, or live contribution records.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded T2 synthetic dry-run lane:

- [Value rubric options](../value-rubric-options/) for RQ3 rubric options,
  dimension failure modes, first-pilot value screens, and disagreement ledgers.
- [Contribution taxonomy](../contribution-taxonomy/) for RQ2/T1 class,
  evidence-minimum, ambiguity, and review-path scaffolds.
- [Review cadence options](../review-cadence-options/) for RQ4 rationale,
  contestability, timing, and reviewer-capacity scaffolds.
- [Prototype workflow](../prototype-workflow/) for RQ5 packet, source-trace,
  record-surface, revision, and review-prep bundle scaffolds.
- [Reward readiness](../reward-readiness/) for RQ9 no-reward baseline,
  reward-boundary, and first-pilot reward-stop scaffolds.

## Stop Conditions

Stop for Joe or governed review before:

- changing active rubric dimensions, score meanings, score aggregation,
  contribution standards, review states, reviewer authority, contribution
  templates, issue templates, contribution-log schema, governance files,
  guardrails, claims, test-status surfaces, or public-facing posture surfaces;
- assigning scores, ranks, accepted/revised/rejected states, value verdicts,
  reward meaning, retained-value rights, governance weight, legal/financial
  meaning, claim-status movement, test-status movement, public language, or
  contribution-record meaning;
- selecting a real first-pilot target, source lane, contribution unit,
  contributor, reviewer owner, live record surface, public audience, reward
  context, or transfer context;
- treating synthetic samples, suggested score vectors, disagreement labels, AI
  output, or private founder context as source evidence, review authority,
  reward entitlement, participant right, governance authority, or live record;
- opening an issue, pull request, review thread, public invitation, score
  ledger, contribution-log entry, or non-GitHub external action;
- storing private, confidential, regulated, proprietary, or unsafe material in
  the public repo.

## Safe Use

Use this map to find the current T2 value-rubric dry-run artifacts and preserve
read order. Do not use it as evidence that active score meanings exist,
reviewer authority exists, rewards exist, rights exist, a contribution can be
logged, T2 has passed, a pilot is live, or any policy/status decision has
already been made.
