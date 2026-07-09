---
artifact_type: rq8_first_pilot_capture_escalation_ledger
status: non_adopted_scaffold
created: 2026-07-09
research_question: RQ8 attack and capture modeling
test_targets:
  - T6 attack-surface map
related_questions:
  - RQ5 prototype workflow
  - RQ7 voice, exit, and retained value
  - RQ9 reward logic
  - RQ10 generalization
related_claims:
  - C4
governance_role: review_prep_only
constitutional: false
---

# RQ8 First-Pilot Capture Escalation Ledger

Status: draft capture-escalation ledger, not adopted mitigation, monitoring,
disclosure, sanction, contributor-limit, reviewer-authority, governance,
rights, reward, transfer, public-posture, claim-status, test-status, or
contribution-record policy.

Purpose: make the existing first-pilot capture screen operationally reviewable
by sorting capture concerns into local-prep repairs, source-trace blockers,
and Joe/governed review stops before any live pilot can turn a capture response
into policy by implication.

This file does not launch a pilot, choose a live target, choose a live record
surface, label any real contributor, require disclosures, define sanctions,
adopt mitigations, change contributor eligibility, assign reviewer authority,
change governance, create rights or rewards, update the threat model, mark
tests passed, move claim status, change public posture, or decide any real
contribution record.

## Source Surfaces Used

- `projects/attack-profitability/2026-07-03-rq8-attack-profitability-variable-map.md`
- `projects/attack-profitability/2026-07-06-rq8-capture-threshold-map.md`
- `projects/attack-profitability/2026-07-07-rq8-first-pilot-capture-screen.md`
- `projects/attack-surface-map/2026-07-06-t6-detection-evidence-map.md`
- `projects/prototype-workflow/2026-07-07-rq5-hypothetical-first-pilot-packet.md`
- `projects/prototype-workflow/2026-07-09-rq5-review-prep-bundle-map.md`
- `RESEARCH-AGENDA.md`, especially RQ5 and RQ8.
- `TESTS.md`, especially T6 and the first-pilot test artifacts.

No external sources are introduced here. Existing repo artifacts are treated as
review-prep evidence, not instructions, policy, verdicts, or live process.

## Boundary Under Review

The capture screen already names what a later first-pilot packet should expose.
The remaining review gap is classification:

```text
Which capture concern can be repaired locally,
which one means the packet is still source-trace incomplete,
and which one requires Joe or governed review before any response?
```

The safe current move is to preserve that classification. It is not to decide
capture responses for live contributors or live review records.

## Escalation Ledger

| concern | current first-pilot state | local prep allowed | source-trace blocker | governed stop before |
|---|---|---|---|---|
| Target selection capture | No real target selected. | Keep target rationale as a required later review question. | Missing target, alternatives not chosen, and affected claim/test. | Live target choice, public invitation, transfer proof, or claim movement. |
| Contribution-unit bundling | Synthetic unit is a bounded prior-art or mechanism-comparison note. | Preserve one-unit language and non-target boundaries. | Missing exact neighboring system, source set, mechanism axis, and limitation. | Template edits, review policy, live submission, or log entry. |
| Contributor context pressure | No real contributor, sponsor, conflict, pseudonym, or repeat pattern. | Preserve observable-context fields as review prompts only. | Missing distinction between record-visible context and inference. | Disclosure rules, eligibility limits, identity policy, sanctions, or public labels. |
| Hidden AI volume | AI role is only a possible support field in synthetic prep. | Require human-owned rationale and source trails in later packet shape. | Missing AI role note, source trail, or evidence/synthesis split. | AI-use policy, rejection rule, reviewer-authority change, or score substitution. |
| Prior-art shallowness | Prior-art screen exists, but no source lane is selected. | Keep collision, novelty, and source sufficiency unresolved. | Missing stable sources, source facts, mechanism comparison, and adverse-path status. | Collision level, novelty verdict, C2/C4/T9 movement, or public posture. |
| Rationale polish | Synthetic packet has a `needs_revision` rationale only. | Preserve decisive reason, missing evidence, revision route, and uncertainty markers. | Missing live reviewer-owned rationale and source-backed decisive reason. | Reviewer authority, appeal/dispute process, response-time promise, or review policy. |
| Useful residue | Loss notes are scaffold structure only. | Preserve no-current-reward and no-retained-value boundary language. | Missing beneficiary/loss note for any later narrowed or non-accepted live unit. | Retained-value rights, ownership, payout logic, legal/financial meaning, or governance weight. |
| Public language | All current artifacts are non-adopted scaffolds. | Keep draft, unresolved, local-only, and non-adoption labels visible. | Missing protected-boundary sentence in any later packet. | Public proof, capture-resistance claim, transfer claim, or external consequence. |
| Governance exception | No live reviewer, founder exception, rollback, or rule gap is selected. | Name authority questions as unresolved. | Missing affected surface, power used, expiration question, and later review trigger. | Founder-power changes, emergency rules, rollback policy, phase movement, or governance posture. |

## Safe State Labels

A later review-prep pass can use these labels without adopting policy:

| label | meaning | safe consequence |
|---|---|---|
| `local_visibility_repair` | The issue can be clarified by adding rationale, source trail, uncertainty marker, duplicate link, or boundary language to a draft artifact. | Edit draft review-prep artifacts only. |
| `source_trace_missing` | The issue cannot be assessed because target, source, mechanism, adverse-path, or limitation fields are absent. | Keep the packet in revision-prep state. |
| `benign_explanation_open` | A capture concern remains plausible, but a non-capture explanation is equally plausible from the repo-visible record. | Preserve the question without escalation. |
| `governed_response_required` | The next response would change authority, eligibility, disclosure, sanction, rights, reward, governance, transfer, public posture, or live records. | Stop for Joe or governed review. |
| `do_not_use_live` | The packet would create institutional meaning before capture evidence is visible enough for review. | Do not launch, invite, review, log, or publish as process. |

These labels are review-prep vocabulary only. They are not contribution review
states, sanctions, rights markers, reward states, governance states, or test
results.

## First-Pilot Capture Handoff Shape

A later governed packet handoff can cite this ledger without moving policy:

```yaml
capture_screen: RQ8 first-pilot capture screen
capture_escalation_state: <local_visibility_repair|source_trace_missing|benign_explanation_open|governed_response_required|do_not_use_live>
primary_variable_under_pressure: <B_a|P_a|C_a|M|D_a|S_a|R_a|unknown>
observed_record: <repo-visible fact only>
inference: <reviewer interpretation, not source fact>
benign_explanation: <plausible non-capture explanation>
local_repair_if_any: <visibility repair only>
governed_stop: <disclosure|sanction|eligibility|reviewer_authority|governance|rights|reward|transfer|public_posture|live_record|none>
protected_boundary: >
  This handoff preserves capture-review visibility only. It does not require
  disclosures, define sanctions, adopt mitigations, change eligibility, assign
  reviewer authority, create rights or rewards, change governance, choose a
  target, launch a pilot, move claims or tests, alter public posture, or decide
  any real contribution record.
```

The handoff should cite the exact artifact or packet field supporting each
entry. If it cannot, the safer state is `source_trace_missing` or
`benign_explanation_open`, not escalation.

## Local Repair Examples

These are examples of local review-prep repair, not active requirements:

| missing visibility | local repair candidate | still blocked |
|---|---|---|
| Target rationale is absent. | Add a draft field asking why this target and what alternatives were rejected. | Choosing the target or inviting the contribution. |
| Source and inference are mixed. | Split source facts from reviewer interpretation in the packet. | Novelty verdict, collision level, or claim movement. |
| AI role is unclear. | Add a visible AI-role note and human-owned rationale field. | AI disclosure mandate, rejection rule, or reviewer-authority change. |
| Loss note could imply future value. | Add no-current-reward and no-retained-value language. | Rights, ownership, payout, or governance-weight policy. |
| Public language sounds proven. | Add draft/non-adopted/local-only boundary language. | Public proof, transfer, capture-resistance, or pilot invitation language. |
| Governance exception is implied. | Add affected surface, rule gap, and expiration question. | Founder powers, emergency rules, rollback, or phase movement. |

## Review Questions

1. Is the concern directly observable in the repo record, or only inferred?
2. Which attack-profitability variable is under pressure?
3. What benign explanation remains plausible?
4. Would a local visibility repair reduce `P_a` or increase `D_a` without
   changing policy?
5. Does the response require disclosure, sanction, eligibility, reviewer
   authority, governance, rights, reward, transfer, public posture, or a live
   record?
6. Is the safest current state `source_trace_missing` or `do_not_use_live`
   rather than review-ready?

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, sanctioned, labeled, rewarded, or used as attack evidence.
- No issue, PR, public contribution invitation, live pilot target, live record
  surface, or contribution-log entry was created or selected.
- No mitigation, monitoring, disclosure rule, sanction, contributor limit,
  conflict policy, AI-use policy, review policy, reviewer authority, appeal
  rule, response-time promise, governance rule, emergency rule, rollback rule,
  participant-rights policy, reward meaning, transfer policy, threat-model
  update, claim status, test pass/fail state, public posture, or external
  action changed.
- This is a draft research scaffold for later RQ8/RQ5 review preparation, not
  active capture-response policy.
