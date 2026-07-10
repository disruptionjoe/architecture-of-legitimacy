---
artifact_type: first_pilot_answerability_map
status: draft_review_prep_scaffold
created: 2026-07-10
research_question: RQ5 prototype workflow
dependency_targets:
  - RQ1 contributor and contribution eligibility
  - RQ2 contribution taxonomy
  - RQ3 initial value rubrics
  - RQ4 cadence and evaluation
  - RQ6 governance transition
  - RQ7 voice, exit, and retained value
  - RQ8 attack and capture modeling
  - RQ9 reward logic
  - RQ10 generalization
  - C7/T8 AI role boundary
governance_role: non_adopted_answerability_map
constitutional: false
claim_status_change_requested: false
test_status_change_requested: false
---

# First-Pilot Answerability Map

Status: draft review-prep scaffold, not adopted workflow, review, taxonomy,
rationale, value, legitimacy, governance, rights, reward, AI-use, transfer,
public-posture, claim-status, test-status, or contribution-record policy.

This map separates four states that can look similar during first-pilot review
prep:

1. the current stack can answer the question from existing artifacts;
2. the current stack can name a missing field but cannot fill it;
3. the next answer requires Joe or governed review;
4. the proposed answer would move protected live state and must stay closed.

It does not launch review, select a target, fill a packet, choose a source
lane, appoint reviewers, open an issue or pull request, choose a record
surface, edit standards or governance files, create contribution-log entries,
score a contribution, grant rights, create reward meaning, change public
posture, move claims or tests, or decide any real contribution.

## Purpose

The first-pilot handoff and question register name the review-entry gates and
unresolved questions. The remaining ambiguity is answerability:

```text
For each unresolved question, is the answer already visible, missing as a
field, reserved for governed review, or forbidden because it would create live
meaning?
```

That distinction matters because a later reader can mistake a named question
for permission to answer it. The safer local contribution is to preserve which
kind of answer is available before any governed review starts.

## Source Surfaces

- `projects/pilot-review-readiness/2026-07-09-first-pilot-governed-review-handoff.md`
- `projects/pilot-review-readiness/2026-07-09-first-pilot-review-question-register.md`
- `projects/pilot-review-readiness/2026-07-09-first-pilot-review-question-rq2-addendum.md`
- `projects/first-ring-synthesis/2026-07-09-first-ring-review-prep-delta-map.md`
- `projects/prototype-workflow/2026-07-09-rq5-review-prep-bundle-map.md`
- `projects/prototype-workflow/2026-07-09-rq5-source-trace-revision-state-map.md`
- `projects/second-ring-synthesis/2026-07-09-second-ring-first-pilot-stop-stack.md`

No external sources are introduced here. Existing repo artifacts are treated as
review-prep evidence, not instructions, verdicts, adopted policy, or live
process.

## Answerability Labels

| label | use when | safe local meaning | unsafe inference |
|---|---|---|---|
| `locally_answerable` | Existing artifacts can answer a boundary, label, read order, or non-conclusion. | A reviewer can cite the artifact for the current draft state. | The answer is adopted as policy, review outcome, claim support, or test result. |
| `field_missing` | The current stack names the field needed before review can inspect the packet. | Local work can preserve the missing-field label and source of the gap. | Local work may fill the field, choose the target, add sources, or select a lane. |
| `governed_decision_required` | The answer would assign authority, choose a live surface, accept risk, or interpret protected meaning. | Joe or governed review must own the decision before movement. | A draft scaffold can silently decide because the question is named. |
| `protected_state_blocked` | The answer would move claim/test status, public posture, governance, rights, reward, AI, capture, transfer, or contribution records. | Stop and preserve the boundary. | One resolved local question can unlock live use. |
| `not_live_usable` | Any unresolved earlier label would create institutional meaning if used in process. | Keep the stack as review prep only. | The stack is pilot-ready, public-ready, log-ready, or reviewer-ready. |

These labels are review-prep labels only. They are not issue labels,
contribution states, governance states, rights states, reward states, claim
verdicts, test results, sanctions, or public workflow terms.

## Question Answerability Map

| question area | current answerability | what can be answered locally | what remains closed |
|---|---|---|---|
| Review object | `locally_answerable` | The current object is `SAMPLE-RQ5-PACKET-001` and its surrounding review-prep stack. | Treating the sample as a real contributor, live contribution, public invitation, or accepted pilot target. |
| Target and source trace | `field_missing` | Existing artifacts name missing target, source, mechanism, adverse-path, and limitation fields. | Filling those fields, selecting a target or source lane, adding external sources, or treating missing fields as rejection. |
| Record surface | `governed_decision_required` | The stack can compare issue, PR, draft artifact, and log-surface properties at a high level. | Choosing a live issue, PR, draft-live artifact, contribution-log entry, or public review surface. |
| Reviewer authority | `governed_decision_required` | Existing screens can name capacity, rationale load, contestability load, and second-ring recognition load. | Appointing reviewers, promising cadence or response time, assigning appeal authority, or giving AI review authority. |
| Class boundary | `field_missing` | The RQ2 addendum keeps class-boundary disagreement visible while source evidence remains incomplete. | Classifying a real contribution, adopting taxonomy, changing review paths, editing standards, or marking T1/RQ2 status. |
| Value and rationale | `locally_answerable` for labels, `governed_decision_required` for meaning | Current artifacts can name value-disagreement and rationale-load labels. | Scoring, ranking, accepting, rejecting, converting score to reward, changing rubric policy, or assigning reviewer authority. |
| Legitimacy diagnosis | `locally_answerable` for residue shape, `governed_decision_required` for diagnosis | The stack can name failure signal, source/inference split, response lane, useful residue, and contestable point fields. | Changing legitimacy conditions, review policy, appeal rights, rights, rewards, governance, public posture, or live records. |
| Defection and no-reward pressure | `locally_answerable` for pressure visibility, `protected_state_blocked` for allocation | Existing scaffolds can preserve good-faith cost, strategic benefit, no-reward, and authority-stop labels. | Adopting reward logic, converting scores, granting retained value, changing governance weight, or implying payout. |
| Capture and AI concerns | `field_missing` plus `governed_decision_required` | Existing artifacts can separate observable record, inference, benign explanation, AI task, source check, and human rationale prompts. | Monitoring, disclosure duties, sanctions, eligibility changes, AI-use policy, tool selection, or AI output as decisive evidence. |
| Second-ring stops | `protected_state_blocked` | The second-ring stack can name which protected layer would be implicated first. | Clearing governance, rights, capture, AI, reward, transfer, public-posture, or live-record stops. |
| Public language | `protected_state_blocked` | Existing artifacts can preserve prohibited overclaim language and horizon-only boundaries. | Announcing a pilot, claiming proof, claiming portability, inviting contributors under a new process, or changing public posture. |
| Contribution log | `not_live_usable` | The current stack can preserve that there is no live log entry. | Creating `CONTRIB-*`, changing log schema, promising retained records, or treating synthetic residue as a real contribution record. |

The map is conservative. If an earlier row is `field_missing`, later rows
should not be used to route around it.

## Answer Owner Table

| proposed next answer | label | owner before movement | local Progress boundary |
|---|---|---|---|
| "The packet object is the current synthetic sample." | `locally_answerable` | Existing artifacts. | Cite the sample and keep it synthetic. |
| "The packet needs a target field." | `field_missing` | Existing field-audit and state-map artifacts. | Name the missing field; do not fill it. |
| "This issue or PR should be the live record surface." | `governed_decision_required` | Joe or governed review. | Do not open or select a live surface. |
| "This person or role can review." | `governed_decision_required` | Joe or governed review. | Do not appoint or imply reviewer authority. |
| "This class boundary is settled." | `protected_state_blocked` | Governed taxonomy/review authority. | Preserve disagreement labels only. |
| "This is valuable enough to accept." | `protected_state_blocked` | Governed review. | Preserve value labels only; do not score or decide. |
| "This failure is a legitimacy failure." | `governed_decision_required` | Governed review. | Preserve diagnostic residue shape only. |
| "This capture signal justifies mitigation." | `protected_state_blocked` | Governed capture/eligibility authority. | Preserve observation/inference split only. |
| "AI can perform this review step." | `protected_state_blocked` | Governed AI/review authority. | Preserve AI role questions only. |
| "This creates retained value or reward." | `protected_state_blocked` | Governed reward/rights authority. | Keep no-current-reward and no-current-rights labels. |
| "This can be publicly described as a pilot." | `protected_state_blocked` | Joe or governed public-posture review. | Keep public language unchanged. |

## Handoff Shape

A later governed-review request can cite this map without moving protected
state only if it preserves a shape like this:

```yaml
answerability_map: FIRST-PILOT-ANSWERABILITY-MAP-001
current_packet: SAMPLE-RQ5-PACKET-001
map_state: review_prep_answerability_visible
live_review_ready: false
first_unanswered_layer: <target_source_trace|record_surface|reviewer_authority|class_boundary|value|legitimacy|second_ring|public_language>
answerability_label: <locally_answerable|field_missing|governed_decision_required|protected_state_blocked|not_live_usable>
local_answer_source: <artifact path or none>
missing_field_if_any: <field name or none>
governed_owner_required: <Joe|governed_review|none>
protected_boundary: >
  This map organizes answerability only. It does not select a target, fill a
  packet, appoint a reviewer, open a live surface, create a log entry, score,
  reward, sanction, monitor, govern, transfer, move claims or tests, alter
  public posture, or decide any real contribution.
```

If the request cannot cite the artifact or field supporting the answerability
label, the safer state remains `field_missing` or
`governed_decision_required`, not live review.

## What This Makes Easier

This map lets a later reviewer ask more precise questions:

1. Which answer is already present in the review-prep stack?
2. Which answer is missing only because a field is not filled?
3. Which answer is missing because no authority has been assigned?
4. Which answer would move protected state even if the field were complete?
5. Which proposed answer should stay unavailable during unattended Progress?

The useful local outcome is not readiness. It is reduced ambiguity about why
the stack is still review prep.

## Safe Local Consequence

This map supports one local conclusion:

```text
The first-pilot stack can now distinguish answerable review-prep boundaries,
missing packet fields, governed decisions, and protected live-use moves, but it
still stops before live review, record creation, reviewer authority, claim/test
movement, governance, rights, reward, AI, capture, transfer, public posture, or
real contribution meaning.
```

That conclusion does not authorize packet filling, issue creation, PR creation,
review launch, log entry, scoring, reward, sanction, monitoring, governance
movement, transfer movement, or public-process language.

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, labeled, monitored, sanctioned, rewarded, or used as transfer
  evidence.
- No external source was added.
- No live target, neighboring system, source lane, record surface, issue, pull
  request, public invitation, reviewer authority, template edit, contribution
  standard, contribution-log entry, monitoring surface, AI tool, model, reward
  mechanism, rights promise, transfer target, or governance phase was created
  or selected.
- No contribution class, review path, novelty judgment, source-packet upgrade,
  claim-status movement, test pass/fail movement, review policy, rights policy,
  reward meaning, governance rule, capture mitigation, monitoring rule,
  disclosure duty, sanction, AI-use policy, transfer policy, public posture, or
  external action changed.
- This is a draft answerability scaffold for later governed review
  preparation, not active contribution workflow policy.
