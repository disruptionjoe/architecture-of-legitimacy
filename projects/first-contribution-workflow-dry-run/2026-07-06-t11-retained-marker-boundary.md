---
artifact_type: workflow_boundary_map
status: non_adopted_scaffold
created: 2026-07-06
test_target: T11 legitimacy trace workflow
related_questions:
  - RQ7 voice, exit, and retained value
  - RQ9 reward logic
governance_role: review_prep_only
constitutional: false
---

# T11 Retained-Marker Boundary

Status: draft workflow boundary, not adopted rights, retained-value, reward, or
contribution-log policy.

Purpose: make the retained-right marker part of T11 reviewable without changing
the contribution workflow, contribution-log schema, participant rights, reward
meaning, governance, claim status, public posture, or any live contribution
record.

## Boundary Under Review

T11 asks for one sample contribution to move through submission, validation,
contestability, log entry, retained-right marker, and explicit loss notes. The
repo already has synthetic workflow traces, a contribution-log schema boundary
map, RQ7 retained-value options, and RQ9 reward boundaries. The remaining risk
is that a future reviewer might collapse four different ideas:

1. **Retained record:** the contribution and review rationale remain visible.
2. **Retained recognition:** the record preserves attribution or visible credit.
3. **Retained-value marker:** the record preserves possible future relevance for
   a later review without promising anything.
4. **Reward or rights claim:** the record creates entitlement, payout,
   governance standing, ownership, or appeal rights.

This artifact works only on the boundary between 1, 2, and 3. It explicitly does
not adopt 4.

## Source Surfaces Used

- `TESTS.md`, especially T10 and T11.
- `CONTRIBUTIONS-LOG.md`.
- `templates/contribution-log-schema.md`.
- `CONTRIBUTION-STANDARDS.md`, especially the score and review-state boundary.
- `LEGITIMACY-SCHEMA.md`, especially contestability and exit with retained
  record.
- `PROTOCOL-STACK.md`, especially contribution log, rights, and rewards.
- `GUARDRAILS.md`, especially reward and decentralization overclaim boundaries.
- `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md`.
- `projects/first-contribution-workflow-dry-run/2026-07-05-t11-synthetic-adverse-decision-trace.md`.
- `projects/first-contribution-workflow-dry-run/2026-07-06-t10-log-schema-boundary-map.md`.
- `projects/participant-rights/2026-07-03-rq7-voice-exit-retained-value-boundary-map.md`.
- `projects/participant-rights/2026-07-06-rq7-exit-contestability-pressure-map.md`.
- `projects/reward-readiness/2026-07-06-rq9-reward-test-boundary.md`.

## Marker Vocabulary

| object | safe current meaning | must not imply |
|---|---|---|
| Retained record | The artifact, review state, rationale, and links remain inspectable. | Reward, ownership, governance standing, or permanent hosting promises. |
| Retained recognition | Attribution or visible credit remains attached to accepted work where appropriate. | Ranking, entitlement, payout, priority, or legal claim. |
| Loss-note residue | Useful value from revised, narrowed, or non-accepted work is preserved as review memory. | Acceptance, compensation, deferred approval, or future payout debt. |
| Non-promissory future-review marker | A note says the record may be relevant if a later rights or reward review is authorized. | Automatic eligibility, conversion formula, token, share, vote, veto, or appeal right. |
| Explicit no-reward boundary | The record states that no reward or retained-value right currently attaches. | A permanent anti-reward policy or a final decision about future reward design. |

## Workflow Placement Matrix

| workflow point | marker question | safe current handling | stop before |
|---|---|---|---|
| Submission | Did the contributor request reward, retained value, ownership, or future entitlement? | Treat it as a proposal claim to review, not as an attached right. | Accepting entitlement language into contribution policy or a live record. |
| Triage | Does the contribution touch reward, rights, governance, or log meaning? | Flag secondary effects and route the main contribution class separately from adoption questions. | Letting a harmless class label hide reward or rights effects. |
| Accepted record | What durable trace survives acceptance? | Preserve target, rationale, links, attribution, and score boundary. | Turning scores, attribution, or links into payout or governance weight. |
| Needs revision | What useful value is retained while revision remains open? | Use `loss_notes` to preserve residue and name what is not accepted yet. | Treating residue as deferred acceptance or reward debt. |
| Not accepted | What useful residue remains without accepting the claim? | Preserve a bounded loss note and the decisive rationale if the residue is useful. | Rewarding pressure, creating appeal policy, or changing claim status. |
| Contested | What exact marker or rationale is disputed? | Name the disputed point without promising a forum, timeline, or reversal. | Adopting appeal rights, reviewer authority changes, or dispute policy. |
| Future synthesis | Can later work cite the retained record or residue? | Cite the public artifact and preserve the non-promissory boundary. | Converting citation into contribution acceptance, reward eligibility, or governance standing. |

## Current Schema Note

The current log schema does not have a distinct `retained_right_marker` field.
That is a useful boundary, not a defect to patch during this run.

Until a governed schema change is authorized, marker language can be studied in
existing fields:

- `rationale` can explain why the contribution counted or did not count;
- `loss_notes` can preserve useful residue while naming promises not created;
- `links` can preserve the public trace needed for later review;
- `review_state` can say what has actually been decided.

Adding a distinct marker field, making it required, or attaching any reward,
rights, or governance meaning would require Joe/governance review.

## Candidate Non-Promissory Language

These snippets are review prompts, not live policy:

| case | candidate language to test | boundary preserved |
|---|---|---|
| Accepted contribution | "This record preserves attribution and review rationale. It does not create reward, ownership, governance weight, or future payout rights." | Recognition without reward. |
| Needs revision | "The loss note preserves useful residue for later synthesis. It does not accept the contribution as submitted or promise later compensation." | Residue without acceptance. |
| Not accepted | "The rejected portion is not part of the project record, but the named insight may remain useful as a future review lead." | Future relevance without entitlement. |
| Contested marker | "The disputed point is preserved for reconstructability. No appeal process, reviewer change, or reversal is adopted by this marker." | Contestability without appeal adoption. |
| Future reward review | "If a reward process is ever designed, this record may be evidence to inspect, but no reward process, eligibility rule, or conversion formula exists now." | Optionality without payout promise. |

## Failure Modes

| failure mode | early warning | safer response |
|---|---|---|
| Shadow entitlement | Contributors treat retained-marker language as debt or ownership. | Pair any marker with explicit no-reward and no-governance language. |
| Record erasure | Reviewers avoid preserving useful residue because it might imply reward. | Keep `loss_notes` non-promissory instead of deleting useful context. |
| Score conversion | Rubric scores become informal balances or ranks. | Re-state that scores support review discussion only. |
| Appeal smuggling | A contestability marker starts functioning as a promised appeal. | Name the disputed point but keep forum, timing, and authority unadopted. |
| Schema overreach | A new field is added before the repo knows what marker meaning is safe. | Study language in synthetic records first; leave schema changes gated. |
| Future-review ambiguity | Later synthesis cites residue as if it were accepted contribution value. | Cite the review state and boundary alongside the residue. |

## Later Evidence Needed

T11 becomes more reviewable when a later synthetic or real contribution can show:

- a public record with rationale, links, and review state;
- a retained record or residue note that a future contributor can reconstruct;
- a clear distinction between accepted value and useful but non-accepted residue;
- a contestability marker that does not become an appeal policy;
- explicit no-reward-currently-adopted language;
- and a stop condition for any reward, rights, governance, schema, or public
  posture movement.

## Boundary Notes

- No real contributor is represented here.
- No live `CONTRIB-*` record was added, changed, accepted, rejected, contested,
  sanctioned, scored, or rewarded.
- No contribution-log schema field was added, removed, renamed, or required.
- No retained-right marker, retained-value marker, participant right, reward
  logic, appeal path, governance rule, reviewer authority, claim status, test
  pass/fail state, public posture, legal meaning, financial meaning, ownership
  interest, or future payout promise was adopted.
