---
artifact_type: workflow_dry_run
status: complete
created: 2026-07-01
test_target: T11 legitimacy trace workflow
governance_role: internal_test_record
constitutional: false
---

# Synthetic Contribution Trace

This dry run walks one synthetic contribution through the current contribution
workflow. It does not create a real contribution, does not edit
`CONTRIBUTIONS-LOG.md`, and does not accept, reject, or reward anyone's work.

## Source surfaces used

- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `templates/contribution-proposal.md`
- `templates/contribution-log-schema.md`
- `TESTS.md`

## Current schema alignment

This trace was created before the contribution-log schema gained an explicit
`loss_notes` field. It now reflects the current schema support without changing
the original synthetic review state or creating any live contribution record.

## Synthetic proposal

- **Title:** Prior-art comparison: Gitcoin quadratic funding vs legitimacy trace
- **Contributor:** Synthetic Contributor (agent-assisted: yes)
- **Contribution class:** research
- **Target file(s) / claim(s):** `CLAIMS.md`, `THREAT-MODEL.md`, RQ5 / T11
- **Summary:** Compares this repo's contribution-legitimacy stack to Gitcoin-style
  quadratic funding, with emphasis on where contribution value, contributor voice,
  and capture risk are or are not separable.
- **Prior art / sources:** Gitcoin / quadratic funding literature would be required
  in a real submission; omitted here because this is a synthetic workflow trace.
- **Value-rubric self-assessment:** clarity 2, rigor 1, relevance 3, novelty 1,
  legitimacy 2, capture-resistance 2, coordination-value 2.
- **Failure modes:** Could overstate novelty; could treat funding allocation as
  equivalent to legitimacy; could miss sybil/collusion attack literature.
- **Proposed review state on submit:** submitted

## Workflow trace

| Step | Expected workflow behavior | Synthetic result | Notes |
|---|---|---|---|
| 1. Submission | Proposal uses the public template and names class, target, evidence, value, and risks. | Pass. | The current template is sufficient for a first submission. |
| 2. Triage | Reviewer classifies the contribution using `CONTRIBUTION-STANDARDS.md`. | Research, possibly review-adjacent. | The class boundary is workable; mixed classes should be allowed but one primary class should be named. |
| 3. Relevance check | Reviewer asks whether the proposal addresses a live research question or claim. | Pass. | RQ5 / T11 needs exactly this kind of prior-art and attack-pressure comparison. |
| 4. Evidence check | Research contributions need source-backed comparison. | Needs revision. | The synthetic proposal names a source family but supplies no citations or mechanism-level comparison. |
| 5. Capture-risk check | Reviewer asks whether the contribution clarifies or obscures attack risk. | Needs revision. | A real version should explicitly separate sybil resistance, collusion, voice, reward, and legitimacy. |
| 6. Contestability | Contributor should be able to see why the review state was chosen. | Pass if rationale is recorded. | The current log schema supports rationale, but the review procedure should consistently state the decisive gap. |
| 7. Retained record | The project should retain enough information to reconstruct why the record is legitimate. | Pass for accepted/revised states if logged. | `CONTRIBUTIONS-LOG.md` can represent this, but a real first contribution should include a public rationale line. |
| 8. Loss notes | If work is not accepted as-is, the project should record what value was lost or deferred. | Schema-supported. | The current schema has explicit `loss_notes`; the remaining test is whether reviewers use it clearly in a real contribution trace. |

## Candidate log entry if this were real

This is an example only. It should not be copied into `CONTRIBUTIONS-LOG.md`
unless a real contribution exists.

```yaml
id: CONTRIB-000X
date: 2026-07-01
contributor: Synthetic Contributor (agent-assisted)
class: research
target: CLAIMS.md; THREAT-MODEL.md; RQ5/T11
review_state: needs_revision
rubric_scores:
  clarity: 2
  rigor: 1
  relevance: 3
  novelty: 1
  legitimacy: 2
  capture_resistance: 2
  coordination_value: 2
rationale: >
  Relevant to the first-contribution workflow and capture-resistance question,
  but not yet source-backed or mechanism-specific enough to enter the project
  record as research.
loss_notes: >
  The proposal preserves a useful comparison target for later prior-art work,
  but the unsourced and mechanism-light version defers any claim update,
  threat-model change, or accepted research record.
links: []
```

## Findings

1. **The first-contribution workflow is usable for a first pass.** The template,
   standards, review states, and log schema can carry a synthetic contribution
   from submission through a review state.
2. **The workflow still relies on founder/reviewer judgment, but not silently.**
   The standards give enough vocabulary to explain the judgment, especially when
   the decisive gap is evidence quality or capture-risk specificity.
3. **Loss notes are now schema-supported but still need real-use proof.** T11
   asks for explicit loss notes, and the current schema can carry them. The
   next evidence question is whether real reviews use the field to preserve
   deferred value without implying acceptance, reward, or future legal/financial
   claims.
4. **The right next real test is a real prior-art contribution.** A future
   Progress run should not build a larger governance system yet. It should run one
   real, bounded contribution through this same path and record the result.

## Boundary notes

- No real contributor is represented here.
- No real contribution was accepted or rejected.
- No live contribution log entry was changed.
- No claim status changed.
- No public governance standard changed.
- No reusable CapacityOS method was imported into this repo.
