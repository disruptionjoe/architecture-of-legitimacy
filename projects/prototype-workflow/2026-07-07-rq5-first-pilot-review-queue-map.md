---
artifact_type: research_scaffold
status: draft
created: 2026-07-07
research_question: RQ5 prototype workflow
test_targets:
  - T3 first workflow simulation
  - T10 contribution log prototype
  - T11 legitimacy trace workflow
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
governance_role: non_adopted_first_pilot_review_queue
constitutional: false
---

# RQ5 First-Pilot Review Queue Map

Status: draft review-prep scaffold, not adopted workflow, review, governance,
rights, reward, AI, transfer, public-posture, claim-status, or
contribution-record policy.

This queue map orders the remaining work between "the first-pilot packet can be
described" and "a live first pilot may be run." It does not invite a public
pilot, choose a pilot target, edit issue templates, change contribution
standards, create a live contribution-log entry, adopt review policy, assign
reviewer authority, mark tests passed, move claim status, change governance,
create participant rights, change reward or retained-value meaning, change AI
policy, make transfer claims, change public posture, or decide any real
contribution.

## Purpose

The first-pilot checklist says what a later packet must preserve. The
second-ring stop map says where a later packet must pause before unresolved
governance, rights, reward, capture, AI, or transfer questions become hidden
commitments.

The remaining RQ5 planning problem is sequencing:

```text
Which questions can the repo prepare locally, which questions require a
Joe/governed decision before live use, and which questions remain blocked until
more evidence exists?
```

This map is a queue for review preparation only. It is not a launch plan.

## Source Surfaces

- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-review-packet-checklist.md`
- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-second-ring-stop-map.md`
- `projects/prototype-workflow/2026-07-07-rq5-end-to-end-dry-run-readiness-trace.md`
- `projects/first-ring-synthesis/2026-07-07-first-ring-scaffold-crosswalk.md`
- `projects/second-ring-synthesis/2026-07-07-second-ring-dependency-map.md`
- `projects/review-cadence-options/2026-07-07-rq4-rationale-minimums-map.md`
- `projects/contribution-eligibility/2026-07-06-rq1-disclosure-edge-case-matrix.md`
- `projects/contribution-taxonomy/2026-07-06-t1-classification-consistency-check.md`
- `projects/value-rubric-dry-run/2026-07-07-t2-reviewer-disagreement-map.md`
- `projects/ai-role-boundary/2026-07-06-c7-t8-ai-authority-failure-map.md`

## Queue Labels

Use these labels to keep review preparation from silently becoming policy.

| label | meaning | allowed output |
|---|---|---|
| Local prep | The repo can clarify the packet, field, evidence, or rationale shape without live consequences. | Draft scaffold, comparison note, or review-prep checklist. |
| Joe/governed decision | The next step would authorize a live surface, reviewer role, public invitation, template change, or protected meaning. | Stop and ask through the repo-governed path before live use. |
| Evidence blocked | The question cannot be answered from current scaffolds alone. | Name the missing trace, source packet, or review artifact. |
| Do not do now | The action would move protected state or create public/external consequence. | Record the boundary and leave the action unstarted. |

These labels are not contribution states and should not be copied into active
review policy without a separate governed decision.

## First-Pilot Review Queue

| queue item | why it matters | current evidence | safe local prep | decision or blocker |
|---|---|---|---|---|
| Record surface for the first pilot | The packet must live somewhere reviewable without becoming a live log entry too early. | The checklist names possible surfaces: issue, PR, project artifact, or post-review contribution-log entry. | Compare what each surface would preserve: submission snapshot, review rationale, residue, log eligibility, and contestability. | Joe/governed decision before choosing a live surface or editing issue templates. |
| Candidate pilot target | The first pilot needs one low-governance target, not a public call for broad contributions. | Existing RQ5 artifacts keep pointing to a bounded, source-backed research or review contribution. | Maintain the safe shape: one named target, one contribution unit, source-backed evidence, no reward or governance movement. | Joe/governed decision before selecting a real target or inviting a contributor. |
| Accountability context | Identity, pseudonymity, agent assistance, affiliation, conflict, and source limits can matter without becoming hidden gatekeeping. | RQ1 and RQ5 field-parity scaffolds show the gap but do not adopt disclosure prompts. | Draft a packet note that records visible context and says what policy it does not create. | Joe/governed decision before changing templates or requiring disclosure fields. |
| Class and evidence continuity | Review must connect primary class to the right evidence minimum. | RQ2/T1 and RQ5 scaffolds support `research` as the likely first primary class, with `review` as a possible secondary effect. | Prepare a narrow class/evidence note for one source-backed research contribution shape. | Evidence blocked until a real packet shows whether reviewers can hold the class stable. |
| Value and disagreement handling | A first pilot can expose disagreement without turning scores into authority or reward. | RQ3/T2 scaffolds separate dimension conflict, false positives, taste, governance stops, and reward leakage. | Name which value dimensions a first packet may discuss and which ones must remain non-scoring notes. | Do not do now: score-to-reward, ranking, payout, retained-value, or governance-weight language. |
| Review rationale minimum | A later reader must see the decisive reason for `accepted`, `needs_revision`, `not_accepted`, `contested`, or `adversarial`. | RQ4 rationale minimums and the first-pilot checklist already name state-specific receipt needs. | Keep a one-packet rationale screen that asks for state, decisive reason, missing evidence, protected boundary, and useful residue. | Joe/governed decision before adopting review-state policy, appeal paths, response times, or reviewer authority. |
| Protected boundary sentence | The packet must say what the review cannot decide before review language implies adoption. | The checklist and stop map repeatedly protect claims, policy, rights, rewards, governance, AI authority, transfer, and public posture. | Prepare reusable non-conclusion prompts inside the review-prep artifact. | Do not do now: change claims, tests, public posture, templates, governance, rewards, rights, AI policy, or transfer language. |
| Loss notes and useful residue | Useful value should not disappear when work is narrowed or rejected, but residue must not become a promise. | T10/T11 and RQ7/RQ9-adjacent scaffolds distinguish record, recognition, reward, and future-review markers. | State residue as preserved evidence or future-review context only. | Joe/governed decision before any rights, reward, retained-value, legal, financial, ownership, or governance meaning. |
| Log eligibility | The live contribution log must not receive synthetic, draft, unreviewed, or merely proposed material. | Existing traces stay in `SAMPLE-*` space and the checklist separates review outcome from live log eligibility. | Draft a log-eligibility reason field for the later packet. | Joe/governed decision before creating any real `CONTRIB-*` entry. |
| Contestability marker | The first pilot should identify what could be corrected without overpromising appeal process. | RQ4, RQ5, and T11 artifacts support visible disputable points and correction paths. | Name the challengeable point and current visible owner in the packet. | Joe/governed decision before adopting appeal rights, dispute forum, timing promise, or reviewer-authority model. |
| Second-ring stop screen | A narrow review can accidentally imply governance, rights, capture response, AI authority, reward, or transfer. | The second-ring stop map defines dependency triggers and non-conclusions. | Apply the stop screen after packet completeness and before live use. | Stop if the packet touches live governance, rights, capture policy, AI policy, reward logic, transfer, or public posture. |

## Owner-Sorted Queue

### Local Prep Queue

The repo can safely prepare these artifacts without launching a pilot:

1. A record-surface comparison that names what an issue, PR, project artifact,
   or post-review log entry would preserve.
2. A class/evidence note for the likely first-pilot shape: bounded,
   source-backed research with review as a secondary effect.
3. A one-packet rationale screen that keeps decisive reason, protected
   boundary, useful residue, log eligibility, and contestability together.
4. A second-ring stop-screen application note for the same hypothetical packet.

Each local-prep artifact should remain non-adopted and should avoid template,
policy, claim, test, reward, rights, governance, public-posture, live-record, or
external-consequence movement.

### Joe/Governed Decision Queue

These questions should not be answered by an unattended Progress run:

1. Which real contribution target, if any, should be used for the first pilot?
2. Which live record surface should hold the first pilot before and after
   review?
3. Should issue templates, contribution templates, or contribution standards be
   changed before the pilot?
4. Who has reviewer authority for the pilot, and what authority is explicitly
   not being assigned?
5. What accountability context is required, optional, or out of scope?
6. When, if ever, can a reviewed pilot enter `CONTRIBUTIONS-LOG.md` as a real
   `CONTRIB-*` record?

### Evidence-Blocked Queue

These questions need more evidence before adoption:

1. Whether a real contributor can submit enough context without private founder
   explanation.
2. Whether a reviewer can keep class, evidence, rationale, residue, and log
   eligibility continuous across one real packet.
3. Whether multiple reviewers would classify the same contribution consistently.
4. Whether adverse, revised, or contested outcomes preserve useful residue
   without creating rights or reward expectations.
5. Whether second-ring stop conditions are sufficient when a real packet raises
   conflict, capture, AI, reward, rights, or transfer pressure.

## Near-Term Review-Prep Sequence

If this repo continues local preparation before any live pilot, the safest
sequence is:

1. Compare record surfaces without choosing one.
2. Draft a hypothetical packet using the safe bounded research/review shape.
3. Apply class, evidence, rationale, boundary, loss-note, log-eligibility, and
   contestability screens to that packet.
4. Apply the second-ring stop screen.
5. Bring the remaining live-surface and authority questions to Joe/governed
   review.

This sequence should not be described as a public pilot, contribution campaign,
or active review process.

## Do Not Queue For Unattended Progress

Do not put these actions into an unattended Progress run:

- public contribution invitation;
- first real pilot target selection;
- issue-template, contribution-template, or contribution-standard edits;
- mandatory disclosure, identity, conflict, or agent-use rules;
- reviewer appointment, review cadence, appeal process, dispute process, or
  response-time promise;
- live `CONTRIB-*` entry;
- claim-status movement or test pass/fail marking;
- reward, retained-value, rights, legal, financial, ownership, employment, or
  governance commitments;
- sanctions, contributor limits, capture-response policy, or public labels for
  real contributors;
- AI as final authority, hidden evidence, score substitute, or novelty judge;
- transfer pilot selection, public proof language, or portability commitments;
- or non-GitHub external consequences.

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, sanctioned, rewarded, or used as transfer evidence.
- No issue template, contribution template, contribution standard,
  contribution-log schema, live contribution record, review policy, reviewer
  authority, appeal rule, response-time promise, governance rule, emergency
  rule, rollback rule, participant-rights policy, reward meaning, AI-use policy,
  transfer policy, claim status, test pass/fail state, public posture, or
  external action changed.
- This is a draft research scaffold for later RQ5 review preparation, not
  active contribution workflow policy.
