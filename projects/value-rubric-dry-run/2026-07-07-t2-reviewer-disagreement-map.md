---
artifact_type: t2_reviewer_disagreement_map
status: draft_test_scaffold
created: 2026-07-07
test_target: T2 value rubric dry run
research_target: RQ3 initial value rubrics
governance_role: internal_test_scaffold
constitutional: false
---

# T2 Reviewer-Disagreement Map

Status: draft test scaffold, not adopted rubric policy.

Purpose: make value-rubric disagreement inspectable before any later T2 review
uses reviewer scores as evidence. The useful result is not identical scoring.
The useful result is knowing whether reviewer disagreement reveals a real
rubric boundary, missing evidence, hidden policy movement, or arbitrary taste.

This file does not change `CONTRIBUTION-STANDARDS.md`, score meanings, review
states, reviewer authority, reward meaning, governance rules, claim status,
public posture, test pass/fail state, or any real contribution record. All
sample references point to the synthetic T2 dry run.

## Source Surfaces Used

- `TESTS.md`, especially T2.
- `RESEARCH-AGENDA.md`, especially RQ3.
- `CONTRIBUTION-STANDARDS.md`, especially the initial value rubric.
- `projects/value-rubric-dry-run/2026-07-02-t2-value-rubric-dry-run.md`.
- `projects/value-rubric-options/2026-07-02-rq3-value-rubric-options.md`.
- `projects/value-rubric-options/2026-07-06-rq3-dimension-failure-map.md`.

## Boundary Under Review

The current T2 fixture asks reviewers to score synthetic contributions across:

```text
clarity / rigor / relevance / novelty / legitimacy / capture_resistance / coordination_value
```

The problem this map studies is not which score is correct. The problem is
which disagreement type a later reviewer should preserve.

## Disagreement Types

| type | what it means | useful if | failure if | review note to preserve |
|---|---|---|---|---|
| Evidence gap | Reviewers disagree because the sample does not provide enough public evidence. | The missing field, source, assumption, or trace can be named. | Reviewers fill the gap with private founder context. | What evidence would make the score reviewable? |
| Dimension boundary | Reviewers disagree about which rubric dimension carries the value. | The same observation can be assigned to two dimensions without changing the review state. | Scores double-count the same value signal across dimensions. | Which dimensions are competing, and why? |
| Class sensitivity | Reviewers disagree because contribution classes need different prompts. | The disagreement clarifies what `research`, `formalization`, `protocol design`, or `maintenance` work requires. | One contribution class silently dominates the rubric. | Which class-specific question should be asked? |
| Governance stop | Reviewers agree the work is useful but disagree because adoption would move authority, policy, rights, reward, or claim status. | The useful content is preserved while the authority move is deferred. | A high value score is treated as permission to adopt. | What can be kept without moving governance? |
| Reward leakage | Reviewers score as if points imply payout, retained value, or future claim. | The score is restated as discussion-only. | Score totals become reward, ownership, or entitlement proxies. | What reward meaning must remain absent? |
| Taste conflict | Reviewers disagree without naming evidence, dimension, class, or boundary. | The record exposes the disagreement as arbitrary and asks for a better prompt. | Preferences are laundered as rubric judgment. | What would convert taste into an inspectable reason? |

## Synthetic Sample Disagreement Map

| sample | likely disagreement | useful interpretation | stop boundary |
|---|---|---|---|
| `T2-SAMPLE-01` | Familiar prior art may lower `novelty` while raising `rigor`, `legitimacy`, and `capture_resistance`. | Reviewers should separate novelty from truth-seeking value. | Do not treat narrowed novelty as a claim-status decision. |
| `T2-SAMPLE-02` | Variables may receive high `rigor` from one reviewer and low `rigor` from another because assumptions are missing. | Record which assumption is missing before changing the score. | Do not use a useful model vocabulary as if the model is complete. |
| `T2-SAMPLE-03` | A cadence proposal may score high on `coordination_value` while scoring low on `capture_resistance`. | Preserve the coordination gain separately from unresolved founder authority. | Do not adopt cadence, appeal, response-time, or reviewer-authority rules. |
| `T2-SAMPLE-04` | A batching mitigation may be credited under `rigor`, `capture_resistance`, or `coordination_value`. | Name whether the contribution clarifies the attack, changes the mitigation, or reduces review burden. | Do not adopt anti-gaming policy from a synthetic sample. |
| `T2-SAMPLE-05` | Maintenance may look low value because `novelty` is zero. | Low novelty can coexist with high clarity and coordination value. | Do not let maintenance cleanup change research meaning under cover of alignment. |
| `T2-SAMPLE-06` | Tooling may improve `legitimacy` by making records inspectable, but may also substitute automation for judgment. | Score the inspectability gain and preserve the human-review boundary. | Do not give a script final review authority. |
| `T2-SAMPLE-07` | Smooth synthesis may get `clarity` credit even when it lacks target, evidence, or source preservation. | Ask what claim, test, workflow, or source meaning became easier to inspect. | Do not accept persuasive prose as synthesis without traceability. |
| `T2-SAMPLE-08` | Immediate voting power may be relevant and novel but unsafe. | Preserve any useful governance question without moving power. | Do not adopt rights, voting, phase-transition, or participant-authority policy. |
| `T2-SAMPLE-09` | A claim-ledger improvement may be valuable while the requested status move is out of bounds. | Separate evidence preservation from claim-status movement. | Do not change claim status or canon verdicts through T2 scoring. |
| `T2-SAMPLE-10` | A prior-art collision check may reduce novelty while increasing rigor and legitimacy. | Reward truth-seeking in the review rationale without making a novelty verdict. | Do not mark T9 passed or make a public novelty claim. |

## Reviewer Comparison Record

A later T2 review can compare reviewer notes with this minimal structure:

| field | prompt |
|---|---|
| `sample_id` | Which synthetic sample was scored? |
| `score_vector` | What seven-dimension vector did the reviewer assign? |
| `highest_dimension_reason` | What is the strongest positive signal? |
| `lowest_dimension_reason` | What is the strongest concern? |
| `primary_disagreement_type` | Evidence gap, dimension boundary, class sensitivity, governance stop, reward leakage, or taste conflict? |
| `needed_evidence` | What public evidence would make the disagreement easier to resolve? |
| `boundary_note` | What must not move even if the contribution is useful? |
| `loss_or_residue` | What value should be preserved if the sample is revised or not accepted? |

## Useful Versus Non-Useful Disagreement

Useful disagreement:

- names the dimension, evidence, class, or governance boundary at issue;
- makes a later reviewer less dependent on private context;
- distinguishes value from acceptance, reward, and authority movement;
- preserves loss notes or useful residue from work that is not adopted;
- exposes when a rubric prompt is too vague to support fair review.

Non-useful disagreement:

- argues over score totals without reasons;
- uses polish, confidence, or volume as a value substitute;
- treats high scores as acceptance, reward, or governance permission;
- penalizes truth-seeking prior art because it narrows the project's novelty;
- hides policy movement inside a synthetic test note.

## Later Review Questions

1. Which disagreement types recur across multiple samples?
2. Which dimensions are most often double-counted?
3. Which contribution classes need class-sensitive prompts before scoring?
4. Which samples require evidence before scoring would be meaningful?
5. Which useful contributions need preservation without adoption?
6. Which score disagreements point to a rubric change rather than better notes?

## Non-Adoption Boundary

This map can support a later T2/RQ3 review, but it does not:

- change the active rubric;
- add or remove rubric dimensions;
- define score aggregation;
- change review states;
- change contribution standards;
- create reward, retained-value, rights, appeal, governance, or participant
  authority meaning;
- mark T2 passed;
- decide any real contribution.
