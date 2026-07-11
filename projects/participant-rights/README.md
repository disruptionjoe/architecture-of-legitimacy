# Participant Rights

Status: review-prep surface map.

## Purpose

This directory holds non-adopted RQ7 scaffolds for making voice, exit,
identity, contestability, retained-record, retained-value, no-current-rights,
and no-current-reward questions inspectable before any live first-pilot record
or public contribution surface can create participant-rights policy by
implication.

This map is navigation only. It does not grant participant rights, define exit
or identity policy, create appeal or dispute rights, promise retained records,
create reward or retained-value meaning, change governance, assign reviewer
authority, change public posture, move claim status, mark tests passed, or
create live contribution records.

## Read Order

Use this order when trying to understand the current RQ7 participant-rights
lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [Voice, exit, and retained-value boundary map](2026-07-03-rq7-voice-exit-retained-value-boundary-map.md) | Baseline RQ7 pressure around visibility, exit, residue, future use, and retained-value language. | No rights, exit policy, reward policy, retained-value claim, governance movement, public-posture movement, or C5 movement. |
| 2 | [Exit and contestability pressure map](2026-07-06-rq7-exit-contestability-pressure-map.md) | Separating exit, contestability, correction, attribution, and continued-record pressures from adopted process. | No appeal path, dispute process, identity policy, retention promise, reviewer authority, or contribution-log policy. |
| 3 | [First-pilot rights boundary](2026-07-07-rq7-first-pilot-rights-boundary.md) | Applying RQ7 pressure to the synthetic RQ5 first-pilot packet fields. | No pilot launch, live target, contributor right, retained-value right, reward logic, review policy, public posture, or real contribution record. |
| 4 | [First-pilot rights-stop ledger](2026-07-09-rq7-first-pilot-rights-stop-ledger.md) | Classifying rights prompts into local trace repair, missing policy/evidence, governed stops, public/live-use blocks, and do-not-use-live states. | No participant-rights policy, identity/exit/appeal/reward/governance movement, live log entry, claim/test movement, or public-process adoption. |

## Current Lane State

```yaml
lane_state: rq7_participant_rights_review_prep_visible
voice_exit_boundary: available
exit_contestability_pressure_map: available
first_pilot_rights_boundary: available
first_pilot_rights_stop_ledger: available
live_review_ready: false
participant_rights_policy_state: not_adopted
identity_policy_state: not_adopted
exit_policy_state: not_adopted
appeal_or_dispute_policy_state: not_adopted
retained_record_policy_state: not_adopted
reward_policy_state: not_adopted
claim_status: unchanged
test_status: unchanged
public_posture: unchanged
```

These labels are review-prep labels only. They are not participant-rights
states, appeal states, reward states, identity states, governance states,
reviewer-authority assignments, sanctions, contribution states, claim verdicts,
or test results.

## How To Read The Lane

Read the baseline boundary map first to see which participant-facing meanings
RQ7 is trying not to create accidentally. Then read the exit and
contestability pressure map to see why withdrawal, correction, rationale, and
dispute language can become policy by implication. Read the first-pilot rights
boundary before the rights-stop ledger, because the ledger turns those field
pressures into stop labels for later governed review.

The central distinction is:

```text
The repo can prepare participant-rights visibility; it has not authorized
participant-rights policy, identity policy, exit policy, retained-record
commitments, appeal/dispute process, reward meaning, or live contribution
records.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded RQ7 participant-rights review-prep lane:

- [Prototype workflow](../prototype-workflow/) for the synthetic RQ5 packet,
  source-trace, revision, and review-prep stack.
- [First contribution workflow dry run](../first-contribution-workflow-dry-run/)
  for retained-marker and log-readiness boundaries.
- [Reward readiness](../reward-readiness/) for no-reward, score-conversion,
  retained-value, and reward-stop boundaries.
- [Attack profitability](../attack-profitability/) and
  [attack surface map](../attack-surface-map/) for capture, gaming,
  false-positive, and escalation boundaries.
- [AI role boundary](../ai-role-boundary/) for AI-assisted review trace,
  rationale ownership, and hidden-authority boundaries.
- [Founder phase constraint](../founder-phase-constraint/) for governance,
  founder-power, phase-transition, emergency, and rollback stop boundaries.
- [Second-ring synthesis](../second-ring-synthesis/) for the cross-lane
  governance, rights, capture, AI, reward, and transfer stop stack.

## Stop Conditions

Stop for Joe or governed review before:

- selecting a live first-pilot target, source lane, contributor, reviewer
  owner, live record surface, public audience, or transfer context;
- logging or editing any real `CONTRIB-*` entry;
- adopting participant rights, exit rights, identity rights, privacy rights,
  appeal rights, dispute rights, retained-record commitments, retained-value
  rights, reward claims, governance rights, ownership interests, or legal or
  financial meaning;
- adopting identity, exit, withdrawal, retention, deletion, erasure, appeal,
  dispute, reward, reviewer-authority, AI-use, capture-response, governance,
  or contribution-log policy;
- changing `GOVERNANCE.md`, `GUARDRAILS.md`, `CLAIMS.md`,
  `CONTRIBUTION-STANDARDS.md`, `CONTRIBUTING.md`, issue templates, live review
  policy, contribution records, claim status, test status, public posture, or
  transfer posture;
- assigning sanctions, labels, accepted/rejected states, score conversions,
  reward eligibility, governance weight, response-time promises, or binding
  reversal meaning;
- treating synthetic scaffolds as evidence about a real contributor;
- or taking any non-GitHub external action.

## Safe Use

Use this map to find the current RQ7 artifacts and preserve read order. Do not
use it as evidence that participant rights exist, appeal or dispute process
exists, identity or exit policy exists, rewards exist, a live contribution can
be logged, or any rights, governance, claim, test, public-posture, legal,
financial, or external decision has already been made.
