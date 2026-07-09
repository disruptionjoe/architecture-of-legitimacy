---
artifact_type: research_scaffold
status: draft_review_prep_ledger
created: 2026-07-09
research_question: RQ3 initial value rubrics
test_targets:
  - T2 value rubric dry run
  - RQ5 prototype workflow
governance_role: non_adopted_first_pilot_value_disagreement_ledger
constitutional: false
---

# RQ3 First-Pilot Value-Disagreement Ledger

Status: draft review-prep ledger, not adopted rubric policy, score policy,
review policy, reward policy, governance policy, claim-status movement,
test-status movement, public-posture change, reviewer-authority assignment, or
contribution-record policy.

This ledger extends the RQ3 first-pilot value screen by sorting likely value
disagreements into stop labels a later governed reviewer can inspect. It does
not score a contribution, rank contributors, choose a rubric option, change
score meanings, convert scores into reward, change `CONTRIBUTION-STANDARDS.md`,
mark T2 or RQ5 passed, launch review, create a live record, or decide any real
contribution.

## Purpose

The first-pilot value screen established that the current synthetic packet is
not scoreable while source trace, target, mechanism comparison, limitation, and
review-authority facts are missing.

This file asks the next narrower question:

```text
If reviewers disagree about first-pilot value, what should the record preserve
before anyone argues about scores?
```

The useful output is a ledger of disagreement states. The ledger makes value
discussion safer by keeping evidence repair, dimension ambiguity, governance
pressure, reward leakage, and arbitrary taste separate.

## Source Surfaces

- `CONTRIBUTION-STANDARDS.md`
- `projects/value-rubric-options/2026-07-08-rq3-first-pilot-value-screen.md`
- `projects/value-rubric-options/2026-07-06-rq3-dimension-failure-map.md`
- `projects/value-rubric-dry-run/2026-07-07-t2-reviewer-disagreement-map.md`
- `projects/prototype-workflow/2026-07-09-rq5-review-prep-bundle-map.md`
- `projects/pilot-review-readiness/2026-07-09-first-pilot-governed-review-handoff.md`

## Ledger Labels

These labels are review-prep labels only. They are not live review states.

| label | when to use | useful local output | protected boundary |
|---|---|---|---|
| `source_trace_missing` | A value claim depends on target, source, mechanism, adverse-path, or limitation facts that are not present. | Name the missing field before discussing value. | Do not infer value from private context or polished prose. |
| `dimension_boundary_open` | The same signal could belong to two or more rubric dimensions. | Name the competing dimensions and the reason they compete. | Do not double-count the signal or change score meanings. |
| `class_prompt_unsettled` | The packet may need a class-specific prompt before the seven-dimension rubric is useful. | Preserve the contribution class question separately from value. | Do not rewrite taxonomy, contribution standards, or review paths. |
| `governed_meaning_risk` | A useful value rationale would imply authority, rights, governance, reward, or public posture if adopted. | Preserve the useful observation with an explicit deferral note. | Do not let value language adopt policy or move authority. |
| `reward_leakage_risk` | Score, value, or recognition language starts implying payout, ownership, retained value, or future claim. | Restate the value note as discussion-only and no-current-reward. | Do not create financial, legal, retained-value, or governance-weight meaning. |
| `taste_conflict_unresolved` | Reviewers disagree without naming evidence, dimension, class, or boundary. | Ask what evidence or prompt would make the reason inspectable. | Do not launder preference, confidence, or style as rubric judgment. |
| `value_discussion_ready` | Missing evidence and protected boundaries are named well enough for non-scoring discussion. | Allow a prose value note, still without scores or live review effect. | Do not convert readiness into acceptance, scoring, ranking, or record creation. |

## First-Pilot Application

The current synthetic first-pilot stack should enter the ledger conservatively:

| review area | current label | why | next safe local question |
|---|---|---|---|
| Target and source trace | `source_trace_missing` | The packet does not yet select a live target, source lane, neighboring system, or limitation statement. | Which missing source-trace field blocks value discussion first? |
| Rigor versus relevance | `dimension_boundary_open` | The same evidence minimum could support rigor, relevance, or both. | Does the record show a stronger claim, a clearer target, or only a better checklist? |
| Novelty | `source_trace_missing` | Novelty cannot be discussed without a neighboring system and mechanism comparison. | Which prior-art lane would make novelty reviewable later? |
| Legitimacy | `governed_meaning_risk` | Contestability and rationale fields are useful, but adoption would imply process authority. | What can be preserved as inspectability without creating appeal or reviewer authority? |
| Capture resistance | `dimension_boundary_open` | Source-trace, AI-volume, conflict, and public-posture concerns may overlap with legitimacy and governance stops. | Which risk is observable in the record, and which remains inference? |
| Coordination value | `taste_conflict_unresolved` | More scaffolding may help review, but it may also add review load. | What future reviewer action becomes easier enough to justify the extra structure? |
| Reward adjacency | `reward_leakage_risk` | Value discussion can be mistaken for reward readiness. | What no-reward boundary must sit beside the value note? |

## Reviewer Comparison Shape

A later governed review can use this shape as a comparison record before any
score vector is allowed:

```yaml
value_disagreement_id: <stable local id>
packet_under_review: <synthetic or live packet id>
rubric_dimensions_discussed:
  - clarity
  - rigor
  - relevance
primary_ledger_label: source_trace_missing
secondary_ledger_labels:
  - dimension_boundary_open
missing_public_evidence:
  - <source, target, mechanism, limitation, or record field>
competing_dimensions:
  - <dimension A>
  - <dimension B>
value_preserved_without_adoption: <one sentence>
protected_boundary: >
  This comparison does not score, rank, reward, accept, log, govern, change
  claims, change tests, assign authority, or create contribution-record
  meaning.
next_authorization_needed: <human/governed review, source-trace revision, or no action>
```

This shape is not a live template, issue form, contribution-log schema, review
state, rubric policy, or contribution standard.

## Good And Bad Ledger Outcomes

Useful ledger outcome:

- identifies the strongest missing evidence before score discussion;
- distinguishes dimension disagreement from class disagreement;
- names reward leakage before any value language hardens;
- preserves useful residue without accepting or logging a contribution;
- leaves a later reviewer less dependent on private founder context.

Bad ledger outcome:

- argues about totals before public evidence exists;
- rewards polish, confidence, volume, or AI-generated synthesis;
- treats "valuable" as "accepted", "rewardable", or "governance-ready";
- hides claim, test, policy, public-posture, or live-record movement inside a
  value note;
- creates a mandatory process step from a draft scaffold.

## What This Prepares

This ledger prepares a later RQ3/T2 discussion by making these boundaries
explicit:

1. evidence repair before value disagreement;
2. dimension boundary before score totals;
3. class prompt before rubric generalization;
4. useful residue before acceptance;
5. no-reward boundary before recognition;
6. governed meaning stop before authority movement;
7. synthetic prep label before live review state.

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, ranked, logged, sanctioned, rewarded, or used as governance evidence.
- No score vector, score aggregation rule, rubric option, contribution
  standard, review policy, reviewer authority, appeal rule, response-time
  promise, rights policy, reward logic, retained-value meaning, governance
  rule, claim status, test pass/fail state, public posture, issue template,
  contribution template, contribution-log schema, or live contribution record
  changed.
- This is a draft RQ3/T2 review-prep scaffold for the synthetic RQ5
  first-pilot packet, not active contribution workflow policy.
