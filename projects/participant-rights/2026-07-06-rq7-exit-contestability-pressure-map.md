---
artifact_type: participant_rights_pressure_map
status: non_adopted_scaffold
created: 2026-07-06
research_question: RQ7 voice, exit, and retained value
claim_target: C5
governance_role: review_prep_only
constitutional: false
---

# RQ7 Exit And Contestability Pressure Map

Status: draft pressure map, not adopted participant-rights, identity-retention, appeal, reward, or contribution-log policy.

Purpose: pressure-test how exit, retained records, contestability, identity changes, and adverse-review residue interact before the repo grants participant rights or attaches reward meaning to contribution records.

This file does not grant rights, create an appeal path, create reward promises, create legal or financial claims, define identity-retention policy, change reviewer authority, revise governance, or decide how any real contribution should be handled. It is a bounded RQ7 research scaffold for later review.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ7.
- `ROADMAP.md`, especially Phase 1, Phase 3, and Phase 4.
- `CLAIMS.md`, especially C5.
- `LEGITIMACY-SCHEMA.md`, especially contestability, voice, exit with retained record, and bounded authority.
- `PROTOCOL-STACK.md`, especially Layers 6, 7, 8, and 9.
- `CONTRIBUTING.md`.
- `CONTRIBUTION-STANDARDS.md`, especially review states and the warning that scores are not automatic reward.
- `GOVERNANCE.md`, especially founder-led authority and public reason-giving.
- `GUARDRAILS.md`, especially reward, decentralization, AI, and overclaim language.
- `THREAT-MODEL.md`, especially reward gaming, legitimacy drift, founder theater, and governance capture.
- `templates/contribution-log-schema.md`, especially `loss_notes`.
- `projects/participant-rights/2026-07-03-rq7-voice-exit-retained-value-boundary-map.md`.
- `projects/first-contribution-workflow-dry-run/2026-07-05-t11-synthetic-adverse-decision-trace.md`.

## Boundary Under Pressure

The earlier RQ7 boundary map separates visibility, voice, contestability, exit with retained record, retained-value marker, dispute path, correction, and AI-use transparency. This map narrows the pressure to one difficult zone:

```text
participant exits or changes participation status
  while a contribution record, adverse review, dispute note, or loss note remains useful
```

The dangerous collapse is treating retention of a record as any of these stronger commitments:

- a right to reward,
- a right to governance standing,
- an adopted appeal path,
- an identity promise the repo has not reviewed,
- a duty to preserve every withdrawn artifact,
- or a power to rewrite historical rationale.

The opposite failure is also serious: exit becomes coercive if a contributor must keep participating to preserve accepted work, useful loss notes, or the ability to contest an adverse rationale.

## Synthetic Pressure Scenario

This scenario is non-real. It is a review fixture, not a contribution decision.

```text
Synthetic Contributor E submits a protocol-design contribution.
The review state becomes needs_revision.
The reviewer records useful loss_notes and a disputed classification point.
Before revision, the contributor exits participation and asks to change display identity.
Later, a future synthesis wants to cite the useful residue.
```

The scenario forces the repo to separate five questions:

1. What record remains visible?
2. What can the contributor still contest after exit?
3. What identity or pseudonym appears on retained material?
4. What useful residue can future synthesis cite?
5. What language prevents retained residue from becoming reward, ownership, or governance entitlement?

## Exit And Contestability Matrix

| pressure case | record to preserve | contestability question | identity or exit risk | over-promise risk | safe research note |
|---|---|---|---|---|---|
| Accepted contributor exits. | Accepted artifact link, contributor display identifier, review rationale, and later correction notes. | Can the contributor contest a later misdescription of the accepted work? | Exit may feel coercive if recognition disappears. | Retained record may be read as permanent reward or governance claim. | Test language that keeps attribution visible while saying no reward right is adopted. |
| `needs_revision` contributor exits before revision. | Submitted target, review state, rationale, loss notes, and revision route if useful. | Can the contributor dispute the reason for `needs_revision` without keeping a live proposal open forever? | Exit could erase useful residue or leave the contributor attached to an unfinished artifact. | Loss notes may be read as deferred acceptance. | Treat residue as review memory, not acceptance or entitlement. |
| `not_accepted` contributor disputes rationale and exits. | Original rationale, disputed point, reviewer response minimum, and loss notes if any. | Is the dispute preserved as a bounded point rather than a live appeal? | A public adverse note may outlive participation. | A contest marker may look like an adopted appeal right. | Separate dispute note, correction request, and governance appeal. |
| Contributor asks to change display identity. | Stable record identifier, current display label, and identity-change note if reviewed. | Can identity display be corrected without hiding historical rationale? | Public records can expose more continuity than intended. | Identity-update support may imply privacy guarantees the repo has not adopted. | Require later policy review before promising pseudonym continuity or erasure. |
| Contributor withdraws before review. | Possibly no durable record, or a minimal withdrawn stub if necessary for process integrity. | Is there anything to contest if no review occurred? | Preserving too much can violate withdrawal expectations. | A stub can imply review or rejection happened. | Decide later when withdrawal creates no record, a private note, or a public stub. |
| Contributor later classified as adversarial. | Prior accepted records, later risk note, and reason for any boundary change. | Can the contributor contest the later classification separately from old accepted work? | Retaliatory erasure and uncritical retention both harm legitimacy. | Historical acceptance can be mistaken for ongoing trust or future reward. | Keep prior record separate from later eligibility or sanction questions. |
| Contributor exits after governance dispute. | Accepted work, disputed governance point, and any public rationale. | Can governance disagreement be visible without granting veto or voting power? | Exit can become a loyalty test. | Voice may be mistaken for governance authority. | Preserve structured voice while keeping power transfer behind governance review. |
| Contributor asks for retained-value marker after exit. | Contribution record and any non-promissory future-relevance note if later adopted. | Can the request be reviewed without assigning value? | The contributor may rely on speculative future benefit. | Marker can become shadow token, payout claim, or governance weight. | Keep retained-value markers unadopted until reward and governance gates clear. |

## Minimum Record Fields To Study Later

A future review can test whether these fields are enough for exit and contestability without adopting policy now:

| field | purpose | boundary |
|---|---|---|
| `record_id` | Keeps the object stable when display identity, review state, or rationale changes. | Does not create a legal, financial, or governance claim. |
| `display_identity` | Names the visible contributor label used in the record. | Does not promise real-name, pseudonym, or erasure handling. |
| `review_state` | States whether the contribution is accepted, needs revision, not accepted, contested, or adversarial. | Does not decide any real contribution here. |
| `rationale` | Makes the review reason inspectable. | Does not make founder judgment final proof of legitimacy. |
| `loss_notes` | Preserves useful value narrowed, deferred, or not accepted as-is. | Does not imply reward, acceptance, ownership, or future claim. |
| `contestability_marker` | Names the specific point that could be disputed or corrected. | Does not create appeal policy or contributor veto power. |
| `exit_note` | Records that participation ended or paused if the contributor requests or the workflow later requires it. | Does not create retention, deletion, or ongoing-access promises. |
| `identity_change_note` | Separates display-label update from historical record alteration. | Does not adopt privacy or pseudonymity policy. |
| `future_use_boundary` | Says whether future synthesis may cite the retained record or residue. | Does not create reward readiness or governance standing. |

## Candidate Review Sequence

This is a later-review prompt, not an active workflow:

1. **Classify the object.** Is the item an accepted contribution, unfinished submission, adverse review, dispute note, correction request, identity request, or governance objection?
2. **Preserve the narrowest useful record.** Keep enough context for reconstruction without expanding the record into policy, reward, or surveillance.
3. **Separate display identity from record integrity.** A display-label change should not silently rewrite rationale, dates, review state, or contribution meaning.
4. **Name the contestable point.** Preserve what is disputed: class, evidence sufficiency, rationale, loss note, identity label, future-use boundary, reviewer conduct, or rule meaning.
5. **Identify the gate.** Rights, appeal, retention, deletion, reward, identity, sanction, and governance questions require later Joe/governance review.
6. **Use non-promissory language.** Retained records and loss notes preserve evidence and optionality; they do not promise payout, ownership, governance weight, or future acceptance.

## Failure Modes

| failure mode | early warning | possible mitigation to test |
|---|---|---|
| Exit coercion | Contributors believe leaving erases accepted value or useful residue. | Test retained-record language that survives exit without promising reward. |
| Record over-retention | Withdrawn or identity-sensitive material remains visible by default. | Separate no-record, minimal-stub, and public-record cases before policy adoption. |
| Appeal smuggling | Contestability language starts to function as adopted appeal rights. | Keep contest markers distinct from appeal or dispute-resolution policy. |
| Reward leakage | Retained-value or loss-note language sounds like payout debt. | Pair retained residue with explicit no-reward-currently-adopted language. |
| Identity overpromise | The repo implies pseudonym continuity, erasure, or privacy handling it cannot guarantee. | Flag identity handling as a later policy and governance question. |
| Founder shield | Founder-led review uses exit or identity complexity to avoid rationale. | Require rationale and bounded-authority notes even in synthetic review packets. |
| Historical rewrite | Correction or identity changes silently alter the original decision. | Prefer append-only correction notes until a policy says otherwise. |
| Adversarial pressure | Bad-faith actors use exit, grievance, or identity claims to exhaust review. | Define reviewability thresholds before rights or appeal policy is adopted. |

## Later Evidence Needed

RQ7 becomes more reviewable when the repo has:

- one synthetic or real exit case with an accepted record;
- one synthetic or real exit case after `needs_revision` or `not_accepted`;
- an identity-display change example that does not rewrite historical rationale;
- a contestability marker that distinguishes correction from appeal;
- a retained-record example paired with explicit no-reward-currently-adopted language;
- and a capture-risk review for grievance, identity, or retained-value gaming.

## Stop Conditions

Stop and require Joe/governance review before:

- editing `CONTRIBUTING.md`, `CONTRIBUTION-STANDARDS.md`, `GOVERNANCE.md`, `GUARDRAILS.md`, `CLAIMS.md`, `CONTRIBUTIONS-LOG.md`, public posture, issue templates, live review policy, contestability rules, identity policy, exit policy, or contribution-log policy based on this scaffold;
- adopting any participant right, exit right, retained-record commitment, identity-retention rule, appeal path, dispute rule, retained-value marker, reward meaning, governance power, reviewer authority, sanction, disclosure requirement, or deletion/erasure rule;
- treating loss notes, retained records, display identity, or contestability markers as legal, financial, token, ownership, governance, employment, or reward entitlement;
- changing C5 status or claiming RQ7 is solved;
- adding or changing a real contribution record;
- or publishing this scaffold as active participant-rights policy rather than draft research.
