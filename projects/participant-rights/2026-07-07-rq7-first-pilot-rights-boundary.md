---
artifact_type: participant_rights_first_pilot_boundary
status: non_adopted_scaffold
created: 2026-07-07
research_question: RQ7 voice, exit, and retained value
related_tests:
  - T11 legitimacy trace workflow
related_questions:
  - RQ5 prototype workflow
  - RQ9 reward logic
claim_target: C5
governance_role: review_prep_only
constitutional: false
---

# RQ7 First-Pilot Rights Boundary

Status: draft first-pilot boundary map, not adopted participant-rights,
identity, appeal, dispute, retained-value, reward, governance, review, or
contribution-log policy.

Purpose: apply the existing RQ7 participant-rights scaffolds to the synthetic
RQ5 first-pilot packet before any live pilot can turn record visibility,
contestability, exit, loss notes, or future-use language into rights by
implication.

This file does not launch a pilot, choose a live target, choose a live record
surface, grant participant rights, create an appeal or dispute path, define
identity policy, create retained-value rights, adopt reward logic, assign
reviewer authority, change governance, change public posture, change claim or
test status, or decide any real contribution record. It is a bounded RQ7
review-prep scaffold.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ5 and RQ7.
- `TESTS.md`, especially T10 and T11.
- `CLAIMS.md`, especially C5.
- `CONTRIBUTION-STANDARDS.md`, especially review states, scores, and the
  current non-reward boundary.
- `GOVERNANCE.md`, especially founder-led public reason-giving.
- `GUARDRAILS.md`, especially reward, decentralization, and AI overclaim
  boundaries.
- `projects/participant-rights/2026-07-03-rq7-voice-exit-retained-value-boundary-map.md`.
- `projects/participant-rights/2026-07-06-rq7-exit-contestability-pressure-map.md`.
- `projects/first-contribution-workflow-dry-run/2026-07-06-t11-retained-marker-boundary.md`.
- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-review-queue-map.md`.
- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-second-ring-stop-map.md`.
- `projects/prototype-workflow/2026-07-07-rq5-hypothetical-first-pilot-packet.md`.
- `projects/reward-readiness/2026-07-07-rq9-no-reward-baseline-inspection.md`.
- `projects/second-ring-synthesis/2026-07-07-second-ring-dependency-map.md`.

## Boundary Under Review

The hypothetical first-pilot packet already preserves submission, evidence,
rationale, loss-note, log-eligibility, contestability, and second-ring stop
screens. RQ7 adds a narrower risk:

```text
the packet may need to expose contributor-facing rights questions
without granting participant rights or creating policy by implication
```

That matters because even a synthetic packet can make later live use feel
"already decided" if it treats any of these as settled:

- contributor visibility;
- continued record visibility after exit;
- identity or pseudonym handling;
- loss-note preservation;
- contestability after adverse review;
- future-use or retained-value language;
- correction and annotation;
- or no-current-reward wording.

The safe current move is not to adopt a rights schema. It is to name which
rights questions a first-pilot packet must keep visible, which questions it
cannot answer, and which actions require Joe/governed review before live use.

## First-Pilot Rights Exposure Matrix

| packet surface | RQ7 pressure exposed | safe current handling | stop before |
|---|---|---|---|
| Contributor display identity | A real contributor may need a visible label without the repo promising identity continuity, privacy, or erasure. | Record the display label as packet metadata in a later live packet; keep identity policy unresolved. | Pseudonym, identity-change, privacy, deletion, or erasure commitments. |
| Contributor exit or withdrawal | A contributor might leave before revision, after acceptance, or after an adverse review. | Preserve only the narrowest useful record needed for reconstruction in synthetic review-prep. | Exit rights, withdrawal policy, record-retention promises, or deletion rules. |
| Review state and rationale | `accepted`, `needs_revision`, `not_accepted`, `contested`, or `adversarial` states affect how a participant can understand the decision. | Require visible rationale in the packet shape while keeping review authority and appeal policy unadopted. | Live review policy, reviewer authority, response-time promises, or appeal/dispute process. |
| Loss notes and useful residue | Useful narrowed or rejected work may need to survive without becoming future value. | Treat loss notes as reconstruction aids and evidence for later review, not as accepted contribution value. | Retained-value rights, reward promises, deferred acceptance, or future payout eligibility. |
| Contestability marker | A participant may need to name a disputed point without creating an appeal court. | Preserve the disputed point and current visible owner in the packet; no forum, timing, or reversal is promised. | Appeal rights, dispute forum, reviewer reassignment, binding reversal, or governance escalation. |
| Log eligibility | A later live review must decide whether a contribution can enter `CONTRIBUTIONS-LOG.md`. | Keep synthetic packets out of the live log and require a post-review eligibility reason for any future live packet. | Real `CONTRIB-*` entries, log schema changes, or contribution-record policy changes. |
| Future-use boundary | A retained record or residue may help later synthesis. | State future use as possible evidence to inspect, not as reward, ownership, governance standing, or accepted value. | Score conversion, token/share language, governance weight, or legal/financial meaning. |
| No-current-rights and no-current-reward language | The packet needs to avoid both overpromising rights and foreclosing later review. | Use explicit "not adopted now" language rather than permanent anti-rights or anti-reward claims. | Permanent rights/reward posture, public posture changes, or C5 movement. |

## Synthetic Packet Read

Apply the matrix to `SAMPLE-RQ5-PACKET-001` from the hypothetical first-pilot
packet.

| packet element | current synthetic state | RQ7 read | live-use blocker |
|---|---|---|---|
| Contributor | `SAMPLE_CONTRIBUTOR`; no real person. | No identity or exit policy is tested yet. | A real packet must decide what display identity is visible and what it does not promise. |
| Review state | `synthetic_needs_revision`. | The state can expose rationale and loss-note requirements without reviewing a real contribution. | A live `needs_revision` record needs a visible revision route and contestability marker. |
| Useful residue | Packet shape is useful, but target and sources are missing. | Residue can be preserved as scaffold structure only. | A live residue note must avoid deferred acceptance or retained-value meaning. |
| Contestable point | Whether a bounded source-backed research/review contribution is the safest first-pilot shape. | Contestability exists as a review-prep question, not a participant right. | A real contributor dispute needs a bounded point, response owner, and no-appeal boundary. |
| Log eligibility | Not eligible for `CONTRIBUTIONS-LOG.md`. | Correct for synthetic work; no live contributor or contribution exists. | A real packet cannot enter the log until review state, rationale, and boundaries are decided. |
| Second-ring stop | RQ7 stop is invoked by rights, identity, residue, contestability, and retained-value pressure. | Stop screen is clear enough for review-prep. | Joe/governed review before live rights, appeal, retention, identity, or reward meaning. |

This read shows the next local preparation need: a live first-pilot packet must
carry rights-boundary fields even when the contribution itself is low-governance
and source-backed. Otherwise, a simple review can still create rights, reward,
or governance implications by omission.

## Minimum Rights Boundary Fields For A Later Packet

These fields are review prompts, not active template requirements:

| field | question it preserves | boundary it must state |
|---|---|---|
| `display_identity_note` | What contributor label is visible in this packet? | No identity, privacy, pseudonymity, or erasure policy is adopted by the note. |
| `exit_or_withdrawal_note` | Has participation ended, paused, or withdrawn in a way relevant to the record? | No exit right, withdrawal rule, or retention/deletion promise is adopted. |
| `rationale_visibility` | Can a participant reconstruct the decisive review reason? | Visible rationale does not make founder judgment final proof of legitimacy. |
| `loss_note_boundary` | What useful residue remains, if any? | Residue is not acceptance, compensation, reward debt, or retained-value entitlement. |
| `contestable_point` | What exact point could be corrected or disputed? | The point is not an appeal right, dispute process, response-time promise, or veto. |
| `future_use_boundary` | May later synthesis inspect this record or residue? | Future use is evidence review only, not score conversion, payout, ownership, or governance weight. |
| `no_current_rights_reward_boundary` | Which rights and reward meanings are explicitly not created now? | The boundary is not a permanent anti-rights or anti-reward decision. |

A later governed template change may accept, reject, rename, or replace these
fields. Until then, they should stay in research scaffolds and synthetic packet
review only.

## Rights-Specific Stop Screen

Before a later first-pilot packet is used live, stop for Joe/governed review if
the packet requires any of these moves:

| trigger | why it stops |
|---|---|
| A contributor asks for anonymity, pseudonym continuity, identity change, erasure, or display-name correction. | The repo has not adopted identity or retention policy. |
| A contributor exits or withdraws and the record may remain public. | The repo has not adopted exit, withdrawal, deletion, or retained-record rules. |
| A reviewer wants to preserve useful residue from unaccepted work. | Loss notes can become deferred acceptance, reward debt, or future-value claims. |
| A contributor disputes rationale, class, evidence sufficiency, score, loss note, future-use note, or reviewer conduct. | Contestability is not yet an adopted appeal or dispute process. |
| A packet mentions retained value, future reward review, score conversion, ownership, governance standing, or legal/financial meaning. | C5/RQ7 and RQ9 gates remain review-prep only. |
| A packet would enter `CONTRIBUTIONS-LOG.md` as a real record. | Live contribution records require post-review eligibility and governed handling. |

## Local Prep Still Safe

Safe local research work can continue by:

- testing non-promissory wording in synthetic packets;
- comparing field names for clarity without changing live templates;
- adding more synthetic adverse, exit, or contested examples;
- checking whether loss notes remain understandable without reward language;
- mapping identity-display ambiguity as a research problem;
- or connecting RQ7 fields to RQ8 capture and RQ9 no-reward screens.

Unsafe unattended work includes:

- changing contribution instructions, issue templates, contribution-log schema,
  live review policy, governance rules, public posture, or claim status;
- granting participant rights, exit rights, identity rights, retained-value
  rights, appeal paths, dispute processes, reviewer authority, sanctions,
  disclosure requirements, reward meaning, or governance standing;
- logging a real contribution;
- or using this scaffold to invite a public pilot.

## Later Review Questions

1. Which rights-boundary field is actually necessary for the first live packet:
   display identity, exit/withdrawal, rationale, loss notes, contestability,
   future use, or no-current-rights/no-reward language?
2. Can a contributor understand `loss_notes` as useful residue without hearing
   reward, debt, or deferred acceptance?
3. What is the smallest contestability marker that preserves reconstructability
   without becoming an appeal policy?
4. What identity or withdrawal scenario is safe to test synthetically before
   any live public contribution?
5. What language preserves future review optionality without creating C5
   movement?
6. Which RQ8 capture risks appear once rights-boundary fields become visible in
   a live packet?

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, sanctioned, rewarded, or used as evidence for rights.
- No issue, PR, public contribution invitation, live pilot target, or live
  record surface was created or selected.
- No issue template, contribution template, contribution standard,
  contribution-log schema, contribution record, review policy, reviewer
  authority, appeal rule, dispute path, response-time promise, governance rule,
  participant-rights policy, identity policy, exit policy, retained-value
  meaning, reward meaning, AI-use policy, transfer policy, claim status, test
  pass/fail state, public posture, legal meaning, financial meaning, ownership
  interest, or external action changed.
- This is a draft research scaffold for later RQ7/RQ5 review preparation, not
  active participant-rights policy.
