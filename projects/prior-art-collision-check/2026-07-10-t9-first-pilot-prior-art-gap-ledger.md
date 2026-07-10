---
artifact_type: first_pilot_prior_art_gap_ledger
status: draft_review_prep_ledger
created: 2026-07-10
test_target: T9 prior-art collision check
related_research_question: RQ5 prototype workflow
governance_role: non_adopted_internal_review_artifact
constitutional: false
collision_result: unresolved
source_lane_selected: false
claim_status_change_requested: false
---

# T9 First-Pilot Prior-Art Gap Ledger

Status: draft review-prep ledger, not a prior-art verdict, novelty judgment,
source-packet upgrade, pilot launch, claim-status change, test-status change,
public-posture change, contribution-record action, or policy adoption.

This ledger turns the first-pilot prior-art screen into explicit gap labels for
later governed review. It does not add external sources, select a live source
lane, assign collision levels, make a novelty verdict, mark T9 or RQ5 passed,
choose a live first-pilot target, edit templates or standards, create records,
adopt review policy, move governance, create rights or rewards, change AI or
transfer posture, or decide any real contribution.

## Purpose

The T9 first-pilot screen already says a source-backed prior-art or
mechanism-comparison note is plausible as review prep, but not ready for live
review. The useful next local step is to preserve exactly which gaps must stay
visible before any reviewer treats the packet as a prior-art contribution.

This ledger asks:

```text
Which T9 gaps would still block a first-pilot prior-art packet from review,
and what protected meaning must not be inferred while each gap remains open?
```

The answer is gap tracking only. It does not choose the lane, fill the packet,
upgrade a source packet, or authorize review.

## Source Surfaces

- `projects/prior-art-collision-check/2026-07-08-t9-first-pilot-prior-art-screen.md`
- `projects/prior-art-collision-check/2026-07-07-t9-adverse-path-evidence-queue.md`
- `projects/prior-art-collision-check/2026-07-07-t9-second-wave-cross-packet-synthesis.md`
- `projects/prototype-workflow/2026-07-08-rq5-first-pilot-source-trace-gate.md`
- `projects/prototype-workflow/2026-07-08-rq5-first-pilot-source-trace-field-audit.md`

No new external source is introduced here. Existing repo artifacts are treated
as review-prep evidence, not instructions, policy, or verdicts.

## Gap Labels

| label | meaning |
|---|---|
| `source_lane_unselected` | No neighboring system, case, PR, edit, manuscript path, funding application, or governance action has been chosen. |
| `source_trace_missing` | Stable source references and directly sourced facts are not present in a live packet. |
| `adverse_path_missing` | The packet does not yet state accepted-path-only, adverse-path, under-valued-path, or mixed-path evidence. |
| `mechanism_scope_unbounded` | The comparison axes are not narrowed to one or two mechanisms. |
| `source_inference_split_missing` | Source facts, contributor inference, and reviewer inference are not visibly separated. |
| `collision_boundary_required` | The packet needs a clear no-verdict boundary before any T9 review language is read. |
| `live_use_blocked` | The gap blocks live review, issue, PR, contribution-log, public invitation, or policy movement. |

These labels are not contribution states, source-packet statuses, test results,
or public workflow labels.

## Gap Ledger

| gap | current local evidence | later review need | protected non-inference |
|---|---|---|---|
| Targeted local surface | The synthetic first-pilot packet points toward RQ5/T9 review preparation. | Name one test, research question, claim-adjacent scaffold, or project artifact. | Broad project relevance is not a review target. |
| Source lane | The T9 screen lists funding, knowledge-validation, maintainer-governance, commons, retained-record, and capture-translation options. | Choose one inspectable lane through Joe or governed review. | No lane is selected, exhausted, or preferred for live use. |
| Contribution unit | The current shape is "one source-backed prior-art or mechanism-comparison note." | State the exact note, correction, comparison, or critique under review. | A literature bundle is not one reviewed contribution. |
| Stable source references | Existing T9 packets contain prepared sources, but the first-pilot packet has no live source set. | Put stable source references in the packet itself. | Reviewer memory, search, or private founder context is not evidence. |
| Direct source facts | Existing screens require source facts, but the packet does not supply them. | Separate directly sourced facts from contributor summary. | Inference, AI wording, or reviewer synthesis cannot become source fact. |
| Contributor and reviewer inference | The source-trace gate says inference must be marked, but no live review exists. | Mark contributor interpretation and any reviewer comparison separately. | Interpretation does not settle novelty, overlap, or evidence. |
| Adverse-path status | The adverse-path queue names candidate losing, delayed, rejected, reverted, disputed, and under-rewarded paths. | Declare accepted-path-only, adverse-path, under-valued-path, or mixed-path evidence. | Success-path evidence cannot imply contestability, retained value, loss-note quality, or rights. |
| Mechanism axes | Existing synthesis names validation, allocation, voice, contestability, record, reward timing, governance, capture, and coupling axes. | Choose one or two axes. | A narrow comparison cannot support broad novelty or collision claims. |
| Similarity and difference pressure | The current screen says both are needed before comparison. | Name what looks similar enough to reduce overclaim and different enough to require review. | Similarity is not `module_overlap`; difference is not novelty strength. |
| Missing evidence | The packet has no selected target, source lane, source facts, adverse-path status, or limitation. | Name the exact missing source or trace before review. | Missing evidence is a revision need, not rejection, acceptance, or score. |
| Record and recognition | T9 retained-record work separates record, recognition, reward, rights, and future eligibility. | State what survives as record versus recognition, reward, right, or later eligibility. | Retained record does not create retained-value policy, rights, rewards, or future eligibility. |
| Collision boundary | T9 artifacts keep collision result unresolved. | Add a boundary sentence saying the packet assigns no collision level or novelty verdict. | No `module_overlap`, `coupled_overlap`, novelty failure, novelty strength, or T9 pass/fail state is created. |
| Public and live-use boundary | The RQ5 source-trace gate and T9 screen keep live use blocked. | Keep public language, issue/PR creation, live review, and log eligibility behind governed review. | Draft review prep is not public invitation, pilot readiness, or contribution-record meaning. |

## Current Review-Prep Readout

```yaml
prior_art_gap_state:
  - source_lane_unselected
  - source_trace_missing
  - adverse_path_missing
  - mechanism_scope_unbounded
  - source_inference_split_missing
  - collision_boundary_required
safe_next_state: governed_source_trace_selection
unsafe_next_state: live_prior_art_review
collision_result: unresolved
test_status: unchanged
```

The useful result is sharper blocking language. A later reviewer can see which
fields must be filled before T9 review begins, while this repo still avoids
choosing a live target or implying a novelty conclusion.

## Boundary Notes

- No new external sources were added.
- No source packet was edited or upgraded.
- No source lane, target, case, issue, PR, contributor, reviewer, or live
  record surface was selected.
- No prior-art collision level or novelty verdict was assigned.
- No claim status, test pass/fail state, review policy, reviewer authority,
  contribution standard, governance rule, rights policy, reward meaning, AI
  policy, transfer policy, public posture, or contribution record changed.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, sanctioned, rewarded, or used as transfer evidence.
