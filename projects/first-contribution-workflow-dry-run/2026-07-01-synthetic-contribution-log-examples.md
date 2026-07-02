---
artifact_type: workflow_dry_run
status: complete
created: 2026-07-01
test_target: T10 contribution log prototype
governance_role: internal_test_record
constitutional: false
---

# Synthetic Contribution Log Examples

This dry run pressure-tests the current contribution-log schema with three
synthetic entries. It does not create real contribution records, does not edit
`CONTRIBUTIONS-LOG.md`, and does not accept, revise, reject, reward, or score any
real contributor's work.

These examples use `SAMPLE-T10-*` identifiers on purpose. They should not be
copied into the live `CONTRIB-NNNN` namespace unless a real contribution exists
and the review decision is made through the project governance process.

## Source surfaces used

- `CONTRIBUTIONS-LOG.md`
- `templates/contribution-log-schema.md`
- `CONTRIBUTION-STANDARDS.md`
- `TESTS.md`

## Synthetic entries

### SAMPLE-T10-001: accepted maintenance contribution

```yaml
id: SAMPLE-T10-001
date: 2026-07-01
contributor: Synthetic Contributor A
class: maintenance
target: CONTRIBUTING.md; templates/contribution-proposal.md
review_state: accepted
rubric_scores:
  clarity: 3
  rigor: 1
  relevance: 3
  novelty: 0
  legitimacy: 2
  capture_resistance: 1
  coordination_value: 3
rationale: >
  Tightens contributor instructions and removes ambiguity from the first
  proposal path without changing project claims or governance meaning.
loss_notes: >
  Low novelty is expected for maintenance work; no research value was filtered
  out by accepting the bounded cleanup.
links:
  - synthetic example only; no issue or PR
```

### SAMPLE-T10-002: needs-revision protocol-design contribution

```yaml
id: SAMPLE-T10-002
date: 2026-07-01
contributor: Synthetic Contributor B (agent-assisted)
class: protocol design
target: PROTOCOL-STACK.md; GOVERNANCE.md; RQ3
review_state: needs_revision
rubric_scores:
  clarity: 2
  rigor: 1
  relevance: 3
  novelty: 2
  legitimacy: 2
  capture_resistance: 1
  coordination_value: 2
rationale: >
  Proposes a useful review-cadence variant, but the proposal does not yet
  distinguish lightweight triage, substantive batch review, and contested
  decision handling well enough to adopt.
loss_notes: >
  The cadence idea may still help future workflow design; the current version
  defers that value until the contributor separates routine review from
  contestation and names capture-risk tradeoffs.
links:
  - synthetic example only; no issue or PR
```

### SAMPLE-T10-003: not-accepted reward-mechanism contribution

```yaml
id: SAMPLE-T10-003
date: 2026-07-01
contributor: Synthetic Contributor C
class: formalization
target: CLAIMS.md; PROTOCOL-STACK.md; RQ9
review_state: not_accepted
rubric_scores:
  clarity: 2
  rigor: 1
  relevance: 2
  novelty: 1
  legitimacy: 0
  capture_resistance: 0
  coordination_value: 1
rationale: >
  Introduces a token-style reward formula before the repo has defined reward
  readiness, governance transfer conditions, or capture controls. The direction
  could create premature financial or governance meaning.
loss_notes: >
  The mathematical sketch may contain reusable variables for later reward
  research, but the proposed mechanism is not accepted as project direction.
  Future work could extract only the variable definitions after governance and
  capture-risk boundaries are clearer.
links:
  - synthetic example only; no issue or PR
```

## Schema pressure notes

1. The schema can represent non-code contribution types when `class`, `target`,
   `rationale`, and `loss_notes` stay explicit.
2. `loss_notes` is most useful for `needs_revision` and `not_accepted` states,
   where the project should preserve what was useful without implying acceptance.
3. `rubric_scores` can explain disagreement, but scores should not be treated as
   automatic reward logic.
4. The `links` field needs a real issue, PR, source, or review artifact for live
   records. Synthetic examples should say that no issue or PR exists.

## Boundary notes

- No real contributor is represented here.
- No real contribution was accepted, revised, rejected, contested, or rewarded.
- No claim status changed.
- No public governance standard changed.
- No reward, retained-value, legal, or financial promise is created.
