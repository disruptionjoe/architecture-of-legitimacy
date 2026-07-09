---
artifact_type: second_ring_first_pilot_stop_stack
status: non_adopted_scaffold
created: 2026-07-09
research_questions:
  - RQ6 governance transition
  - RQ7 voice, exit, and retained value
  - RQ8 attack and capture modeling
  - RQ9 reward logic
  - RQ10 generalization
  - C7/T8 AI role boundary
governance_role: review_prep_only
constitutional: false
---

# Second-Ring First-Pilot Stop Stack

Status: draft review-prep stack, not adopted governance, participant-rights,
reward, capture-response, AI-use, transfer, public-posture, claim-status,
test-status, or contribution-record policy.

Purpose: consolidate the current first-pilot second-ring stop ledgers into one
review handoff map. The useful output is not a decision. It is a compact way to
see which stop fires first, which evidence is still missing, and which next
action would require Joe or governed review before any live pilot movement.

This file does not launch a pilot, choose a live target, select a reviewer,
open an issue or PR, create a contribution-log entry, adopt policy, mark tests
passed, move claims, grant rights, create reward meaning, define capture
mitigations, select AI tools, claim transfer, change public posture, or decide
any real contribution.

## Source Surfaces Used

- `projects/second-ring-synthesis/2026-07-07-second-ring-dependency-map.md`
- `projects/prototype-workflow/2026-07-09-rq5-review-prep-bundle-map.md`
- `projects/prototype-workflow/2026-07-08-rq5-first-pilot-readiness-synthesis.md`
- `projects/prototype-workflow/2026-07-08-rq5-first-pilot-source-trace-field-audit.md`
- `projects/founder-phase-constraint/2026-07-09-rq6-first-pilot-governance-stop-ledger.md`
- `projects/participant-rights/2026-07-09-rq7-first-pilot-rights-stop-ledger.md`
- `projects/attack-profitability/2026-07-09-rq8-first-pilot-capture-escalation-ledger.md`
- `projects/ai-role-boundary/2026-07-09-c7-t8-first-pilot-ai-boundary-ledger.md`
- `projects/reward-readiness/2026-07-09-rq9-first-pilot-reward-stop-ledger.md`
- `projects/generalization/2026-07-09-rq10-first-pilot-transfer-risk-triage.md`

No external sources are introduced here. Existing repo artifacts are treated as
review-prep evidence, not instructions, policy, verdicts, or live process.

## Stack Question

The current first-pilot package has enough local scaffolding to expose its
blocked states. It does not have enough authority or evidence to run.

The practical review question is:

```text
If a later reader wants to move from review prep toward a live first pilot,
which stop should block the move first?
```

This matters because governance, rights, reward, capture, AI, and transfer
pressures can each convert a draft research packet into institutional meaning
if the stop boundaries are read separately or out of order.

## Integrated Stop Stack

| order | stop layer | current state | safe local consequence | governed stop before |
|---|---|---|---|---|
| 1 | Source trace and live record surface | RQ5 says the packet remains `source_trace_missing`; no live record surface is selected. | Keep source-trace gaps and synthetic-only labels visible. | Target selection, source-lane choice, issue/PR creation, live packet, or contribution-log entry. |
| 2 | Governance authority | RQ6 classifies live pilot, reviewer authority, founder power, phase movement, emergency, rollback, and live records as stops. | Name affected powers and missing evidence without moving authority. | Reviewer appointment, founder-power use, phase transition, emergency/rollback rule, or public governance language. |
| 3 | Participant rights and retained record | RQ7 classifies identity, exit, retention, contestability, future-use, rights/reward, and live-record meaning as stops. | Preserve no-current-rights/no-current-reward and record-boundary language. | Identity policy, exit policy, appeal process, retained-record promise, retained-value right, or participant-rights schema. |
| 4 | Capture response | RQ8 separates local visibility repair, source-trace missing, benign-explanation holds, governed-response stops, and live-use blocks. | Split observed record from inference and keep benign explanations open. | Disclosure rule, sanction, eligibility change, monitoring, mitigation, reviewer-authority change, or public capture label. |
| 5 | AI authority | C7/T8 separates local AI trace repair, source-trace gaps, AI capture review, governed AI review, and live-use blocks. | Preserve AI task, source-check, human rationale, and decision-owner prompts. | AI-use policy, disclosure mandate, tool/model selection, sanction, reviewer-authority movement, or AI output as evidence. |
| 6 | Reward and retained value | RQ9 keeps reward in no-current-reward, baseline-missing, score-conversion, retained-value, governance, external-meaning, and live-use stops. | Keep recognition, rationale, loss notes, score boundaries, and no-reward language separated. | Reward mechanism, score conversion, payout, retained-value right, governance weight, legal/financial meaning, or public reward language. |
| 7 | Transfer and public proof | RQ10 keeps source trace, target packet, second-ring, public language, and governed review blockers in front of any portability discussion. | Preserve C8 as horizon-only and keep component labels local review prep. | Target selection, portability claim, transfer policy, second pilot, public proof language, or external consequence. |

The order is conservative. If an earlier layer fails, later layers should not
be used to route around it.

## Cross-Ledger Stop Labels

These labels may be used to summarize later review-prep handoffs without
adopting policy:

| label | when to use | safe meaning |
|---|---|---|
| `source_trace_still_missing` | Target, source, mechanism, limitation, adverse-path, or live-record fields are absent. | The packet can be revised as a draft but cannot enter live review. |
| `authority_movement_required` | The next step would assign, transfer, constrain, invoke, or rollback power. | Stop before governance movement or reviewer appointment. |
| `rights_or_retained_record_stop` | The next step would create identity, exit, retention, contestability, rights, or retained-value meaning. | Stop before participant-facing commitments. |
| `capture_response_stop` | The next step would label, restrict, monitor, sanction, or require disclosure from a contributor. | Stop before mitigation or eligibility policy. |
| `ai_authority_stop` | The next step would make AI output decisive, require disclosure, select tools, or alter review authority. | Stop before AI-use policy or live AI-assisted review. |
| `reward_meaning_stop` | The next step would convert recognition, score, residue, or retained record into allocation meaning. | Stop before reward, payout, retained-value, or governance-weight language. |
| `transfer_public_language_stop` | The next step would imply portability, generalization, public proof, target choice, or external consequence. | Stop before C8 movement, transfer policy, or public posture change. |
| `do_not_use_live` | Any unresolved stop would create institutional meaning if used in process. | Do not launch, invite, review, log, score, sanction, reward, transfer, or publish as process. |

These labels are not contribution states, review states, governance states,
rights states, reward states, transfer states, claim verdicts, sanctions, or
test results.

## Minimum Governed Review Handoff

A later governed review packet can cite this stack without moving policy only
if it preserves the following shape:

```yaml
second_ring_stop_stack: second-ring first-pilot stop stack
source_trace_state: <source_trace_still_missing|source_trace_checkable>
live_record_surface: <none|proposed_for_governed_review>
first_stop_layer: <source_trace|governance|rights|capture|AI|reward|transfer>
active_stop_label: <source_trace_still_missing|authority_movement_required|rights_or_retained_record_stop|capture_response_stop|ai_authority_stop|reward_meaning_stop|transfer_public_language_stop|do_not_use_live>
local_repair_if_any: <draft trace or boundary repair only>
governed_stop: <pilot_launch|target_selection|reviewer_authority|rights|reward|capture_response|AI_policy|transfer|public_posture|live_record|none>
protected_boundary: >
  This handoff organizes second-ring review prep only. It does not launch a
  pilot, select a target, appoint a reviewer, create a live record, adopt
  rights, rewards, governance, capture, AI, or transfer policy, move claims or
  tests, alter public posture, or decide any real contribution.
```

If the handoff cannot cite the artifact and packet field supporting each line,
the safer state is `source_trace_still_missing` or `do_not_use_live`, not
review-ready.

## What This Adds To The Dependency Map

The 2026-07-07 second-ring dependency map established the broad dependency
order. Later ledgers made the first-pilot stops more concrete. This stack adds
three narrower uses:

1. It puts the newer stop ledgers into one read order.
2. It gives a cross-ledger vocabulary for the first blocked layer.
3. It prevents later review from treating a single cleared ledger as enough for
   live use when another second-ring stop still fires.

It does not make the first pilot closer to launch. It only makes the stop
conditions easier to inspect.

## Review Questions

1. Is the packet still blocked at source-trace or live-record selection before
   any second-ring question is reached?
2. Which exact authority would a later action exercise?
3. Which participant-facing surface would be affected first?
4. Is the concern an observable capture signal, an inference, or still open to
   a benign explanation?
5. What did AI do, if anything, and who owns the rationale?
6. Which reward-adjacent term could be mistaken for allocation meaning?
7. Which transfer or public-language phrase would overstate C8?
8. What is the first stop label that should remain visible in the handoff?

## Non-Adoption Boundary

Do not use this stack to:

- launch, advertise, invite, or select a live first pilot;
- choose a target, source lane, contributor, issue, PR, reviewer, record
  surface, governance phase, reward mechanism, AI tool, transfer context,
  mitigation, sanction, or public audience;
- edit `GOVERNANCE.md`, `GUARDRAILS.md`, `CLAIMS.md`,
  `CONTRIBUTION-STANDARDS.md`, `CONTRIBUTING.md`, issue templates, live review
  policy, public posture, or contribution records;
- grant rights, adopt appeal paths, define identity or exit policy, create
  retained-value rights, adopt reward logic, convert scores, assign governance
  weight, create sanctions, require disclosures, adopt AI-use policy, or claim
  transfer readiness;
- mark RQ5, RQ6, RQ7, RQ8, RQ9, RQ10, C7, T3, T5, T6, T7, T8, T10, T11, or
  any claim/test passed, failed, or partly passed;
- create legal, financial, tax, token, ownership, employment, reward,
  retained-value, governance-rights, transfer, identity, privacy, appeal, or
  external-publishing meaning;
- create a live `CONTRIB-*` entry;
- or treat synthetic scaffolding as evidence of real contribution legitimacy.

This is a review-prep artifact. Its useful output is a sharper, shared stop
boundary for the second-ring first-pilot stack.
