---
artifact_type: first_pilot_reviewer_capacity_screen
status: draft_review_prep_scaffold
created: 2026-07-09
research_target: RQ4 cadence and evaluation
depends_on:
  - RQ5 prototype workflow
  - first-pilot governed-review handoff
  - RQ4 rationale minimums
governance_role: non_adopted_first_pilot_reviewer_capacity_screen
constitutional: false
---

# RQ4 First-Pilot Reviewer-Capacity Screen

Status: draft review-prep scaffold, not adopted review, cadence,
reviewer-authority, appeal, dispute, response-time, contribution-log,
public-posture, claim-status, test-status, or contribution-record policy.

This screen applies existing RQ4 cadence and rationale scaffolds to the
first-pilot governed-review handoff. It does not launch a pilot, select a
target, fill a source packet, appoint reviewers, assign reviewer authority,
promise response times, open an issue or PR, choose a live record surface, edit
templates or standards, create a live contribution-log entry, mark tests
passed, move claims, create rights or rewards, change governance, change public
posture, or decide any real contribution.

## Purpose

The governed-review handoff says reviewer authority is not assigned. The RQ4
question is narrower than reviewer appointment:

```text
What reviewer-capacity evidence would a first-pilot review need before a live
review window can be named without creating hidden authority or response-time
promises?
```

This file keeps capacity screening separate from cadence adoption. A review can
be locally well-scaffolded and still unsafe to launch if review ownership,
available attention, contestability handling, and synthesis load are unnamed.

## Source Surfaces

- `projects/review-cadence-options/2026-07-02-rq4-review-cadence-options.md`
- `projects/review-cadence-options/2026-07-07-rq4-rationale-minimums-map.md`
- `projects/review-cadence-options/2026-07-08-rq4-first-pilot-rationale-screen.md`
- `projects/pilot-review-readiness/2026-07-09-first-pilot-governed-review-handoff.md`
- `projects/prototype-workflow/2026-07-09-rq5-review-prep-bundle-map.md`
- `CONTRIBUTION-STANDARDS.md`
- `templates/contribution-log-schema.md`

No external sources are introduced here. Existing repo artifacts are treated as
review-prep evidence, not instructions, verdicts, adopted policy, or live
process.

## Capacity Boundary Under Review

The current first-pilot stack has enough local scaffolding to ask for governed
review, but it does not yet show that any reviewer can hold the full review
burden. The burden includes:

- source-trace inspection;
- class and evidence review;
- rationale writing;
- useful-residue and loss-note preservation;
- contestability note drafting;
- protected-boundary enforcement;
- second-ring stop recognition;
- and later synthesis without policy drift.

Capacity means more than time available. A reviewer must have a bounded
authority shape, a visible non-decision boundary, and enough bandwidth to write
the rationale that makes the review reconstructable.

## Reviewer-Capacity Screen

| screen | current first-pilot state | capacity evidence needed before live review | protected boundary |
|---|---|---|---|
| Review owner | `none_assigned` in the handoff. | A named review owner or owner role, plus what that owner may not decide. | Do not appoint a reviewer or assign authority here. |
| Attention budget | No review window exists. | A conservative estimate of time needed for source trace, rationale, and boundary checks. | Do not promise response time or create a queue. |
| Evidence bandwidth | Source-trace fields remain missing. | Confidence that the reviewer can separate source facts, contributor inference, reviewer inference, and limitations. | Do not fill sources or select a target. |
| Rationale bandwidth | RQ4 rationale fields exist as scaffolds only. | Evidence that `decisive_reason`, `scope_of_decision`, `useful_residue`, and `contestability_note` can be written without private context. | Do not adopt rationale fields as live policy. |
| Contestability load | Contestability is visible but not an appeal path. | A way to record what can be challenged without creating reversal entitlement or dispute forum. | Do not create appeal rights or dispute process. |
| Second-ring recognition | Stop stack and handoff keep protected stops active. | Evidence that the reviewer can identify when governance, rights, reward, capture, AI, transfer, or public posture stops fire. | Do not clear any stop. |
| Synthesis load | Monthly or later synthesis is not assigned. | A later place to preserve unresolved issues without changing policy or claim status. | Do not create synthesis cadence or claim movement. |

If any screen lacks evidence, the safe state remains:

```text
reviewer_capacity_not_yet_live_ready
```

That label is review-prep language only. It is not a contribution state, issue
label, public workflow term, governance state, test outcome, claim verdict, or
response-time commitment.

## Capacity Failure Modes

1. **Available-time fallacy.** A reviewer has time to read the packet but not
   enough time to write a reconstructable rationale.
2. **Authority leakage.** Naming a capacity owner is treated as reviewer
   appointment or policy authority.
3. **Fast-triage overreach.** A quick completeness screen looks like acceptance,
   rejection, or priority.
4. **Contestability overload.** Every objection becomes an appeal path before
   the repo has adopted appeal rights.
5. **Second-ring blindness.** The reviewer can judge source trace but misses
   rights, reward, governance, capture, AI, transfer, or public-posture stops.
6. **Synthesis drift.** A later summary turns unresolved review lessons into
   policy, claim movement, or public posture.
7. **Founder-context dependency.** Missing evidence is handled through private
   memory instead of public source or packet fields.

## Safe Review Window Language

A later governed review might need a review-window phrase. This scaffold keeps
safe and unsafe meanings separate.

| phrase | safe meaning | misuse risk |
|---|---|---|
| `capacity_screen_needed` | Review prep cannot move until ownership and rationale load are inspected. | Becomes an indefinite private blocker. |
| `capacity_screen_passed_for_governed_review` | A governed reviewer may discuss whether live review can be launched. | Sounds like live review is authorized. |
| `reviewer_capacity_not_yet_live_ready` | The packet stack remains local review prep. | Sounds like a negative judgment on contribution value. |
| `governed_review_window_required` | Joe or governed review must decide owner, authority, and timing. | Becomes a public response-time promise. |

For the current stack, the safest label is:

```text
reviewer_capacity_not_yet_live_ready
```

## Safe Handoff Addition

If a later handoff cites this screen, it can add a conservative field without
creating live process:

```yaml
reviewer_capacity_state: reviewer_capacity_not_yet_live_ready
review_owner: none_assigned
review_window: none_promised
reviewer_authority: none_assigned
capacity_blockers:
  - source_trace_missing
  - review_owner_not_named
  - rationale_load_not_estimated
  - contestability_owner_not_named
protected_boundary: >
  Capacity screening organizes review-prep questions only. It does not appoint
  reviewers, assign authority, promise timing, open a live review surface, edit
  standards, create appeal rights, move claims or tests, change public posture,
  or decide any real contribution.
```

The field should cite evidence rather than rely on private founder memory,
reviewer memory, AI summary, or unstated authority.

## Later Review Questions

1. What is the minimum reviewer time needed to inspect one source-backed
   first-pilot packet and write a reconstructable rationale?
2. Which part of review can be triaged quickly without looking like acceptance
   or rejection?
3. Who, if anyone, may own `contestability_note` before appeal rights exist?
4. Which second-ring stop is most likely to be missed by an under-capacity
   reviewer?
5. Where should unresolved capacity findings be synthesized without changing
   policy, claims, tests, or public posture?
6. What evidence would justify moving from `reviewer_capacity_not_yet_live_ready`
   to a governed discussion of a live review window?

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, sanctioned, rewarded, or used as transfer evidence.
- No review owner, reviewer role, review authority, response-time promise,
  appeal rule, dispute process, review cadence, issue, PR, live target, live
  record surface, or public invitation was created or selected.
- No issue template, contribution template, contribution standard,
  contribution-log schema, live contribution record, review policy, governance
  rule, participant-rights policy, reward meaning, AI-use policy, transfer
  policy, claim status, test pass/fail state, public posture, or external
  action changed.
- This is a draft research scaffold for later RQ4/RQ5 review preparation, not
  active contribution workflow policy.
