---
artifact_type: rq9_no_reward_baseline_inspection
status: non_adopted_scaffold
created: 2026-07-07
research_question: RQ9 reward logic
claim_targets:
  - C4
  - C5
governance_role: review_prep_only
constitutional: false
---

# RQ9 No-Reward Baseline Inspection

Status: draft research scaffold, not adopted reward logic.

Purpose: make the no-reward baseline inspectable before the repo considers any
reward mechanism, payout formula, score conversion, retained-value right,
governance weight, review priority, legal/financial meaning, public posture, or
real contribution record change.

This file does not create a reward mechanism, promise future reward, define
eligibility, adopt a no-reward policy, grant participant rights, assign value to
any contribution, create legal or financial meaning, change claim status, change
test status, or decide any real contribution record. It only names what a later
review would need to inspect before moving from "records and recognition only"
to any reward-test packet.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ7 and RQ9.
- `TESTS.md`, especially T5, T6, T10, and T11.
- `CLAIMS.md`, especially C4 and C5.
- `LEGITIMACY-SCHEMA.md`, especially visibility, contestability, exit with
  retained record, bounded authority, and non-capture.
- `PROTOCOL-STACK.md`, especially contribution log, rights, rewards,
  governance, and capture monitoring.
- `CONTRIBUTION-STANDARDS.md`, especially score boundaries and review states.
- `THREAT-MODEL.md`, especially reward gaming and economic capture.
- `templates/contribution-log-schema.md`, especially `loss_notes`.
- `projects/reward-readiness/2026-07-03-rq9-reward-readiness-boundary-map.md`.
- `projects/reward-readiness/2026-07-06-rq9-reward-test-boundary.md`.
- `projects/participant-rights/2026-07-06-rq7-exit-contestability-pressure-map.md`.
- `projects/first-contribution-workflow-dry-run/2026-07-05-t11-synthetic-adverse-decision-trace.md`.
- `projects/first-contribution-workflow-dry-run/2026-07-06-t11-retained-marker-boundary.md`.
- `projects/second-ring-synthesis/2026-07-07-second-ring-dependency-map.md`.

## Boundary Under Inspection

The no-reward baseline is the control condition for early contribution review.
It asks whether the repo can preserve enough visible record value before any
reward mechanism is tested.

The baseline is not:

- a permanent decision against rewards;
- a promise that contribution records will later convert into reward;
- a claim that recognition alone is legitimate;
- a contributor-rights policy;
- or a legal, financial, ownership, governance, employment, token, or tax
  position.

The baseline is only inspectable if later readers can reconstruct what was
submitted, what was accepted or not accepted, what useful residue remained, why
the review state was chosen, and which promises were explicitly not created.

## Baseline Objects

| object | current safe meaning | reward-readiness question | stop condition |
|---|---|---|---|
| Visible record | Artifact, target, review state, links, and rationale remain inspectable. | Can a contributor or reviewer reconstruct the value without private founder memory? | Stop if reconstruction requires private assurances or unwritten judgment. |
| Recognition | The record attributes work or useful residue where appropriate. | Does attribution preserve credit without becoming rank, priority, payout, or governance standing? | Stop if recognition becomes status hierarchy or shadow allocation. |
| Review rationale | The record explains why the contribution counted, needed revision, or was not accepted. | Is the rationale specific enough to be contestable and reusable? | Stop if the rationale is a conclusory founder judgment. |
| Loss notes | Useful narrowed, deferred, or non-accepted value remains visible. | Can residue be preserved without implying deferred acceptance or compensation? | Stop if loss notes read as payout debt or future entitlement. |
| Contestability marker | A disputed point can be identified without adopting appeal policy. | Does the marker help reconstruction without promising forum, timeline, or reversal? | Stop if it becomes an appeal right or reviewer-authority change. |
| No-reward boundary | The record states that no reward or retained-value right currently attaches. | Is the boundary clear without becoming a permanent anti-reward claim? | Stop if the language forecloses later review or promises conversion. |

## Current Evidence To Inspect

| evidence surface | what it currently shows | what it does not yet show |
|---|---|---|
| Synthetic contribution trace | A non-real accepted-path workflow can carry proposal, review, log, and rationale fields. | A real contributor's trust response or reward expectation. |
| Synthetic adverse-decision trace | A non-real `not_accepted` path can preserve rationale, revision route, loss notes, and contestability marker. | A live appeal, contributor exit, or post-review dispute outcome. |
| T11 retained-marker boundary | Retained record, retained recognition, loss-note residue, and future-review marker can be separated in language. | An adopted marker field, rights policy, or reward policy. |
| RQ7 exit and contestability pressure map | Exit, identity, dispute, retained record, and useful residue can be pressure-tested before rights adoption. | A live participant-rights rule or identity-handling policy. |
| RQ9 reward-test boundary | Candidate reward tests can be screened for unit, baseline, contestability, attack delta, authority, and external meaning. | A selected mechanism, value assignment, payout formula, or governance review result. |
| Second-ring dependency map | Reward logic depends on records, rights boundaries, attack delta, and authority to pause or reverse. | Any permission to move reward, rights, governance, or transfer policy. |

## Baseline Pressure Screen

A later RQ9 review should inspect the no-reward baseline before comparing
positive reward alternatives.

| pressure | inspectable question | current local signal | possible local repair before reward design |
|---|---|---|---|
| Recognition sufficiency | Can contributors find durable credit or useful residue from public records? | Synthetic traces and log examples preserve links, rationale, and loss notes. | Improve record visibility, index links, or rationale specificity before adding reward language. |
| High-effort residue | Does useful work survive when the submission is narrowed or not accepted? | The adverse-decision trace and retained-marker boundary preserve residue without acceptance. | Make loss notes clearer; do not compensate, accept, or promise future value here. |
| Contestability | Can a disputed point be named without adopting an appeal system? | T11 and RQ7 artifacts distinguish contest markers from appeal rights. | Improve marker specificity and reviewer-response prompts before rights adoption. |
| Score ambiguity | Are value scores being read as shares, balances, or future payout math? | Current standards warn that scores are not automatic rewards. | Reassert score-as-rationale language before any reward-test packet. |
| Exit pressure | Would a contributor have to keep participating to preserve accepted value or residue? | RQ7 maps exit and identity-change cases, but no policy is adopted. | Study record-retention language without promising erasure, privacy, reward, or governance standing. |
| Strategic claiming | Would retained records attract speculative reward claims? | RQ9 and T11 warn against retained markers becoming debt or shadow tokens. | Pair any retained-record example with explicit no-current-reward language. |
| Capture risk | Would even discussing reward increase gaming, founder pressure, or status competition? | Threat and RQ8 scaffolds name reward gaming and escalation hazards. | Require attack-delta review before choosing any reward alternative. |

## Candidate Baseline Inspection Packet

Before a later review moves from baseline inspection to reward-test design, it
should fill a packet like this from public repo records:

```text
No-reward baseline inspection packet
  1. Contribution or synthetic trace under review
  2. Visible record fields
  3. Recognition and attribution state
  4. Review rationale
  5. Loss-note or useful-residue handling
  6. Contestability marker
  7. No-current-reward boundary language
  8. Exit or identity-retention pressure
  9. Score-to-reward ambiguity check
  10. Attack or strategic-claiming pressure
  11. Evidence still missing before reward-test design
```

The packet should be rejected as premature if it cannot answer sections 2
through 10 without private founder context, new policy adoption, or external
legal/financial interpretation.

## Local Repair Versus Governance Review

Safe local research can:

- improve visibility of existing synthetic records;
- create clearer non-promissory no-reward wording for synthetic examples;
- separate attribution, loss notes, contestability, and future-review markers;
- name where current records still depend on private judgment;
- map score-to-reward ambiguity without changing score meanings;
- or identify which reward-test packet fields are still missing.

Stop for Joe or governance review before:

- adopting reward logic, a payout formula, token-like issuance, retained-value
  right, review priority, score conversion, governance weight, appeal path,
  sanction, disclosure requirement, or participant right;
- editing live contribution standards, governance rules, issue templates,
  contribution-log policy, public posture, claims, or real contribution records;
- assigning economic value, future eligibility, ownership, legal/financial
  meaning, or governance standing to any record;
- promising that current records will or will not count in a future reward
  process;
- or using this scaffold to solicit, publish, deploy, or externally test a
  reward system.

## Later Review Questions

1. Which baseline pressure is visible first: recognition sufficiency,
   high-effort residue, contestability, score ambiguity, exit pressure,
   strategic claiming, or capture risk?
2. Which current synthetic trace would make the best first no-reward baseline
   packet?
3. Which field needs clearer language before any reward-test packet can be
   reviewed: rationale, loss notes, contestability, no-reward boundary, or score
   boundary?
4. What evidence would show that recognition-only participation is extractive
   rather than merely incomplete?
5. Which attack variable changes as soon as future rewards become plausible?
6. What authority would pause a reward test if baseline inspection shows
   strategic claiming or contributor confusion?

Until those questions are answered through a governed review, this scaffold
does not strengthen C4 or C5, mark T5, T6, T10, T11, or RQ9 passed, create
reward readiness, choose a reward mechanism, create participant rights, move
public posture, or alter any contribution record.
