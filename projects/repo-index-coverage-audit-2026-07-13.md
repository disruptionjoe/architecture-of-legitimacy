# Repo Index Coverage Audit - 2026-07-13

Status: navigation maintenance audit.

## Purpose

This audit records a narrow index-coverage check across tracked project
artifacts, local project README maps, `RESEARCH-AGENDA.md`, and `TESTS.md`.
It exists to help future maintenance runs decide whether index backfill is
worth doing deliberately.

This audit is not a claim-status change, test-status change, public-posture
change, governance change, source-selection decision, source-fact fill,
review launch, or instruction to backfill every omission in one run.

## Method

Mechanical checks used in this run:

- list tracked project markdown with `git ls-files 'projects/*.md'
  'projects/**/*.md'`;
- exclude local `README.md` files from repo-level coverage checks;
- check whether each tracked project path appears literally in
  `RESEARCH-AGENDA.md`;
- check whether each tracked project path appears literally in `TESTS.md`;
- check whether each project directory's local `README.md` mentions every
  sibling markdown artifact by filename.

The check is intentionally conservative. A missing literal path is an index
coverage signal, not proof that the underlying topic is absent from the repo or
that the artifact should be promoted.

## Findings

Local project README maps are complete by sibling filename mention. No local
directory map backfill is indicated by this check.

Repo-level index coverage is uneven:

| surface | mechanical omissions | interpretation |
|---|---:|---|
| `RESEARCH-AGENDA.md` | 29 | Several older test-support, C2, T9, T10/T11, and navigation artifacts are not literally indexed in the agenda, often because later synthesis artifacts carry the active review-prep thread. |
| `TESTS.md` | 17 | Several RQ option/boundary, readiness, portability-scoping, and navigation artifacts are not literally indexed in the test ledger, often because they are agenda or review-prep support rather than direct test passes. |

## `RESEARCH-AGENDA.md` Literal-Path Omissions

- `projects/attack-surface-map/2026-07-02-t6-attack-surface-map.md`
- `projects/contribution-taxonomy/2026-07-01-t1-contribution-taxonomy-fixture.md`
- `projects/coupled-stack-dependency/2026-07-03-c2-coupled-stack-dependency-map.md`
- `projects/coupled-stack-dependency/2026-07-03-c2-fixture-readiness-review.md`
- `projects/coupled-stack-dependency/2026-07-06-c2-evidence-packet-checklist.md`
- `projects/coupled-stack-dependency/2026-07-07-c2-validation-gap-closure-note.md`
- `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-log-examples.md`
- `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md`
- `projects/first-contribution-workflow-dry-run/2026-07-05-t11-synthetic-adverse-decision-trace.md`
- `projects/first-contribution-workflow-dry-run/2026-07-06-t10-log-schema-boundary-map.md`
- `projects/first-pilot-review-prep-read-order.md`
- `projects/first-workflow-simulation/2026-07-02-t3-newcomer-workflow-simulation.md`
- `projects/governance-package-portability/00-initial-scoping-note.md`
- `projects/governance-package-portability/01-governance-package-inventory.md`
- `projects/legitimacy-failure-table/2026-07-02-t4-legitimacy-failure-table.md`
- `projects/legitimacy-failure-table/2026-07-06-t4-response-routing-map.md`
- `projects/pilot-review-readiness/2026-07-10-first-pilot-answerability-map.md`
- `projects/pilot-review-readiness/2026-07-10-first-pilot-governed-review-packet-map.md`
- `projects/prior-art-collision-check/2026-07-02-t9-prior-art-collision-review-scaffold.md`
- `projects/prior-art-collision-check/2026-07-03-t9-first-source-packet-checklist.md`
- `projects/prior-art-collision-check/2026-07-05-t9-cross-packet-synthesis-scaffold.md`
- `projects/prior-art-collision-check/2026-07-05-t9-peer-review-adverse-path-trace-scaffold.md`
- `projects/prior-art-collision-check/2026-07-05-t9-peer-review-plos-one-process-path-trace.md`
- `projects/prior-art-collision-check/2026-07-05-t9-retained-record-value-clarification.md`
- `projects/prior-art-collision-check/2026-07-05-t9-wikipedia-adverse-path-trace-scaffold.md`
- `projects/toy-payoff-model/2026-07-02-t5-collaboration-defection-payoff-model.md`
- `projects/toy-payoff-model/2026-07-05-t5-collaboration-threshold-sensitivity-map.md`
- `projects/toy-payoff-model/2026-07-06-t5-payoff-variable-traceability-map.md`
- `projects/value-rubric-dry-run/2026-07-02-t2-value-rubric-dry-run.md`

## `TESTS.md` Literal-Path Omissions

- `projects/attack-profitability/2026-07-03-rq8-attack-profitability-variable-map.md`
- `projects/contribution-eligibility/2026-07-02-rq1-contribution-eligibility-options.md`
- `projects/contribution-eligibility/2026-07-06-rq1-disclosure-edge-case-matrix.md`
- `projects/contribution-taxonomy/2026-07-02-rq2-review-path-map.md`
- `projects/first-pilot-review-prep-read-order.md`
- `projects/founder-phase-constraint/2026-07-03-rq6-phase-transition-evidence-scaffold.md`
- `projects/generalization/2026-07-03-rq10-transfer-conditions-scaffold.md`
- `projects/governance-package-portability/00-initial-scoping-note.md`
- `projects/governance-package-portability/01-governance-package-inventory.md`
- `projects/governance-package-portability/02-portability-evidence-boundary.md`
- `projects/participant-rights/2026-07-03-rq7-voice-exit-retained-value-boundary-map.md`
- `projects/pilot-review-readiness/2026-07-10-first-pilot-answerability-map.md`
- `projects/pilot-review-readiness/2026-07-10-first-pilot-governed-review-packet-map.md`
- `projects/prototype-workflow/2026-07-02-rq5-prototype-workflow-synthesis.md`
- `projects/review-cadence-options/2026-07-02-rq4-review-cadence-options.md`
- `projects/reward-readiness/2026-07-03-rq9-reward-readiness-boundary-map.md`
- `projects/value-rubric-options/2026-07-02-rq3-value-rubric-options.md`

## Recommended Use

Use this audit before future index-maintenance work. A later run can backfill
specific entries when doing so reduces navigation friction, but it should keep
each entry concise and preserve the artifact's existing non-adopted or
review-prep status.

Do not treat the omission lists as a backlog that must be cleared before other
research work. Some omissions may be appropriate because newer synthesis
artifacts are the better navigation surface.

## Non-Conclusions

```yaml
local_readme_backfill_required: false
research_agenda_backfill_required: review_needed
tests_backfill_required: review_needed
claim_status: unchanged
test_status: not_marked_passed
governance_status: unchanged
public_posture: unchanged
source_selection: none
live_review_state: none
```
