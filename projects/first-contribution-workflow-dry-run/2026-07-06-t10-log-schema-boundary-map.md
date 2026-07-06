---
artifact_type: workflow_dry_run
status: complete
created: 2026-07-06
test_target: T10 contribution log prototype
governance_role: internal_test_record
constitutional: false
---

# T10 Contribution Log Schema Boundary Map

This boundary map pressure-tests the current contribution-log schema before it
is used for more real records. It does not edit `CONTRIBUTIONS-LOG.md`, does not
change the schema in `templates/contribution-log-schema.md`, does not mark T10
passed, and does not accept, revise, reject, contest, sanction, reward, score,
or promise anything to a real contributor.

## Purpose

The existing T10 synthetic log examples show that the log can represent
accepted, needs-revision, and not-accepted synthetic entries. The next useful
check is narrower: identify where a reviewer could accidentally create hidden
policy, reward meaning, attribution ambiguity, or contestability gaps by filling
the current fields too casually.

This map treats the schema as review-prep. It separates what the current fields
can safely carry from what would require Joe review, governance work, or a later
schema change.

## Source Surfaces Used

- `CONTRIBUTIONS-LOG.md`
- `templates/contribution-log-schema.md`
- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `TESTS.md`
- `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-log-examples.md`
- `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md`
- `projects/first-contribution-workflow-dry-run/2026-07-05-t11-synthetic-adverse-decision-trace.md`

## Boundary Summary

| field area | safe current use | boundary risk | review question |
|---|---|---|---|
| `id` | Use `CONTRIB-NNNN` only for real entries and `SAMPLE-*` for synthetic tests. | Synthetic records copied into live namespace could imply a real contribution decision. | Is this a real contribution with a governed review, or a fixture? |
| `date` | Record the review or log date plainly. | Date could be read as acceptance date, submission date, or future entitlement date. | Which event does the date represent? |
| `contributor` | Name the contributor or pseudonym, and label agent assistance. | Too much identity detail can create privacy or disclosure policy by accident. | What identity detail is review-relevant and consented? |
| `class` | Use the provisional contribution classes from `CONTRIBUTION-STANDARDS.md`. | Mixed classes can hide governance or reward effects behind a harmless label. | What is the primary class, and what secondary effects need review? |
| `target` | Name files, claims, tests, or research questions affected. | Broad targets can silently pull protected surfaces into a routine review. | Does the target touch claims, governance, policy, reward, rights, or public posture? |
| `review_state` | Use current states as descriptive review outcomes. | `accepted`, `contested`, or `adversarial` could be mistaken for rights, sanctions, or appeal policy. | What does this state decide, and what does it not decide? |
| `rubric_scores` | Use scores as discussion aids only. | Scores can be mistaken for reward, rank, status, or payout conversion. | Is the score explicitly separated from reward and governance weight? |
| `rationale` | Explain the decisive reason for the state. | Generic rationale can make reviewer authority opaque. | Could a future contributor reconstruct the decision without private context? |
| `loss_notes` | Preserve useful deferred value without implying acceptance or reward. | Future-claim language can become a hidden promise. | What value is preserved, and what promise is explicitly not made? |
| `links` | Point to issue, PR, source, or review artifacts. | Missing or unstable links break contestability and later synthesis. | Can a reviewer inspect the source evidence and decision trail? |

## Boundary Scenarios

### SAMPLE-T10-B1: Mixed-class governance effect

```yaml
id: SAMPLE-T10-B1
date: 2026-07-06
contributor: Synthetic Contributor E
class: maintenance
target: CONTRIBUTION-STANDARDS.md; review cadence
review_state: needs_revision
rubric_scores:
  clarity: 2
  rigor: 1
  relevance: 2
  novelty: 1
  legitimacy: 2
  capture_resistance: 1
  coordination_value: 2
rationale: >
  The submission is framed as maintenance but would alter review cadence and
  reviewer expectations. It should be treated as protocol design before any
  standards change is considered.
loss_notes: >
  The cleanup language may still improve contributor usability, but the
  governance-effect portion is deferred until cadence and reviewer-authority
  implications are separated.
links:
  - synthetic example only; no issue or PR
```

Boundary lesson: `class` cannot be the only governance filter. A maintenance
label should not allow a change to review cadence, reviewer authority, or policy
meaning without the right review path.

### SAMPLE-T10-B2: Score-to-reward confusion

```yaml
id: SAMPLE-T10-B2
date: 2026-07-06
contributor: Synthetic Contributor F
class: formalization
target: TESTS.md T5; TESTS.md T10
review_state: accepted
rubric_scores:
  clarity: 3
  rigor: 2
  relevance: 3
  novelty: 2
  legitimacy: 2
  capture_resistance: 2
  coordination_value: 3
rationale: >
  The contribution clarifies variable meanings in the toy payoff model and
  improves later review consistency.
loss_notes: >
  No reward, retained-value right, governance weight, payout, or future legal or
  financial claim is created by the score. Any later reward review would need a
  separate governed process.
links:
  - synthetic example only; no issue or PR
```

Boundary lesson: high scores can support review reasoning, but they must not be
treated as automatic reward logic, ranking, legal claim, or governance weight.

### SAMPLE-T10-B3: Contestability without appeal adoption

```yaml
id: SAMPLE-T10-B3
date: 2026-07-06
contributor: Synthetic Contributor G (agent-assisted)
class: research
target: RQ9; prior-art comparison
review_state: contested
rubric_scores:
  clarity: 2
  rigor: 1
  relevance: 3
  novelty: 2
  legitimacy: 2
  capture_resistance: 1
  coordination_value: 2
rationale: >
  The review found the comparison relevant but undersourced. The contributor
  disputes whether the named examples require full source packets before the
  project can preserve them as research leads.
loss_notes: >
  The disputed examples are preserved as leads only. This does not accept the
  research, adopt a reward path, create an appeal right, or decide future
  contribution status.
links:
  - synthetic example only; no issue or PR
```

Boundary lesson: `contested` can record that a decision is challenged, but this
schema field does not by itself adopt an appeal process, rights policy, sanction
policy, or reviewer-selection rule.

### SAMPLE-T10-B4: Linkless record risk

```yaml
id: SAMPLE-T10-B4
date: 2026-07-06
contributor: Synthetic Contributor H
class: review
target: CLAIMS.md C3; TESTS.md T4
review_state: needs_revision
rubric_scores:
  clarity: 2
  rigor: 2
  relevance: 3
  novelty: 1
  legitimacy: 2
  capture_resistance: 2
  coordination_value: 2
rationale: >
  The critique may expose a legitimacy failure mode, but the supporting note is
  not linked, making later reconstruction too dependent on private memory.
loss_notes: >
  The possible failure mode should be preserved as a review lead, but it should
  not change C3, T4, or the threat model until the source trail is inspectable.
links:
  - missing in synthetic example by design
```

Boundary lesson: `links` is not decorative. For live records, missing evidence
or review links weaken contestability, later synthesis, and the legitimacy trace.

## Field-Level Review Prompts

Before a live entry is added, a reviewer should be able to answer:

1. Is this a real contribution record or a synthetic fixture?
2. Does the entry touch a protected surface, such as claims, governance, reward,
   rights, public posture, contribution policy, or reviewer authority?
3. Does the `class` field match the real effect of the contribution, including
   secondary effects?
4. Does `review_state` describe only the current review outcome, without
   implying appeal rights, sanctions, rewards, or governance powers?
5. Are rubric scores explicitly separated from payout, rank, entitlement, and
   governance weight?
6. Does `rationale` name the decisive reason for the state?
7. Do `loss_notes` preserve useful deferred value without making a promise?
8. Do `links` let a future contributor inspect the evidence and review trail?

## Findings

1. **The schema can carry the first prototype, but the fields need discipline.**
   The current fields can represent attribution, review state, rationale, loss
   notes, and links, but weak entries would still create opacity.
2. **The highest-risk fields are `review_state`, `rubric_scores`, and
   `loss_notes`.** Each can accidentally imply rights, rewards, sanctions,
   entitlement, or future-claim meaning if boundaries are not explicit.
3. **`class` needs an effect check.** A contribution can be submitted as
   maintenance while actually changing protocol design, governance, or reward
   expectations.
4. **T10 should not be treated as passed yet.** The schema has synthetic
   pressure tests, but a real first contribution still needs a governed review
   trail before the project can claim the log prototype works in practice.

## Boundary Notes

- No real contributor is represented here.
- No live `CONTRIB-*` record was added, changed, accepted, rejected, contested,
  sanctioned, scored, or rewarded.
- No contribution-log schema field was added, removed, renamed, or required.
- No contribution standard, governance rule, appeal process, reward meaning,
  rights policy, reviewer authority, test pass/fail state, claim status, or
  public posture changed.
