---
artifact_type: adverse_review_contestability_boundary
status: draft_boundary_scaffold
created: 2026-07-06
research_target: RQ4 cadence and evaluation
governance_role: internal_research_scaffold
constitutional: false
---

# RQ4 Adverse-Review Contestability Boundary

Status: draft boundary scaffold.

Purpose: make adverse review outcomes and contested states more inspectable
before the project adopts any active dispute process, appeal rule, review
cadence, reviewer-authority model, response-time promise, rights policy, reward
meaning, or live contribution-log procedure.

This file is not a contribution policy, governance decision, appeal rule,
participant-rights grant, reviewer-authority change, claim-status decision,
reward rule, public-posture change, response-time promise, or live contribution
decision. It is a bounded research scaffold for testing what an adverse review
record would need to preserve so later contributors can understand and
challenge the decision without relying on private founder context.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ4.
- `ROADMAP.md`, especially Phase 1 and Phase 3.
- `CONTRIBUTING.md`.
- `CONTRIBUTION-STANDARDS.md`, especially Review States and Review Cadence.
- `templates/contribution-proposal.md`.
- `templates/contribution-log-schema.md`.
- `PROTOCOL-STACK.md`, especially Layers 3, 5, 6, and 7.
- `LEGITIMACY-SCHEMA.md`, especially visibility and contestability.
- `THREAT-MODEL.md`, especially cadence, review, and governance-capture risks.
- `projects/review-cadence-options/2026-07-02-rq4-review-cadence-options.md`.
- `projects/review-cadence-options/2026-07-05-rq4-cadence-timing-comparison.md`.
- `projects/first-contribution-workflow-dry-run/2026-07-05-t11-synthetic-adverse-decision-trace.md`.

## Boundary Under Review

The repo already names adverse and contested states:

- `needs_revision`;
- `not_accepted`;
- `contested`;
- `adversarial`.

The open RQ4 problem is not whether those labels exist. The problem is whether
the first public contribution workflow can preserve enough rationale, timing,
loss, and challenge information for an adverse state to remain legitimate.

An adverse outcome is safer when a future reader can answer:

1. What exactly was decided?
2. What was not decided?
3. Which evidence, rule, or boundary drove the state?
4. What useful value was preserved despite the adverse outcome?
5. What can be challenged without creating an automatic appeal right?
6. What requires Joe or later governance review rather than ordinary cadence?

## Synthetic Adverse Review Held Constant

- **Title:** Add contributor voting power after any accepted protocol-design
  contribution.
- **Contributor:** Synthetic Contributor F (agent-assisted: yes).
- **Contribution class:** protocol design, with governance and rights effects.
- **Target file(s) / question(s):** RQ4 cadence, RQ7 participant rights, RQ6
  governance transition, `CONTRIBUTION-STANDARDS.md` review states.
- **Summary:** Proposes that accepted protocol-design contributors immediately
  receive voting power over future cadence and review-state changes.
- **Evidence or reasoning:** The proposal argues that contributors need voice
  for contestability to be meaningful, but it provides no capture model,
  reviewer-selection rule, phase-transition evidence, or anti-cartel boundary.
- **Failure or risk:** Could convert a useful voice concern into premature
  governance transfer, reward-like influence, or contributor-cartel risk.
- **Loss or deferred value:** The proposal usefully exposes a tension between
  contestability and authority even if the voting-power mechanism is not
  reviewable as submitted.
- **Proposed review state on submit:** submitted.

This synthetic proposal is intentionally governance-sensitive so the boundary
can be tested without changing any live rule.

## Candidate Adverse-Review Trace

| trace field | minimum content | why it matters | stop boundary |
|---|---|---|---|
| `submitted_claim` | The exact requested change or proposition. | Prevents the review from answering a softened version of the proposal. | Do not rewrite the proposal into something acceptable without naming the narrowing. |
| `review_lane` | `protocol_design_review` with governance-sensitive stop. | Shows why ordinary maintenance or rolling triage is not enough. | Do not move governance transfer through cadence. |
| `review_state` | `not_accepted` as submitted, or `needs_revision` if narrowed. | Keeps adverse states distinct from silence or indefinite deferral. | Do not mark accepted value as active policy. |
| `decisive_reason` | Immediate voting power would transfer authority without phase evidence or capture controls. | Makes the adverse decision reconstructable. | Do not hide the real reason behind vague "not ready" language. |
| `evidence_gap` | Missing phase-transition criteria, reviewer-selection criteria, and attack analysis. | Names what would make a later version reviewable. | Do not require private founder context as the missing evidence. |
| `governance_boundary` | Contributor voice is a live concern; voting power is a protected governance move. | Separates useful problem statement from unsafe mechanism. | Joe or later governance review required before adopting power transfer. |
| `loss_notes` | Preserve the contestability-authority tension for RQ7/RQ6 review. | Keeps useful residue without implying acceptance, reward, or rights. | Do not create retained-value, legal, financial, or governance claims. |
| `contestability_note` | Contributor may challenge classification, evidence-gap framing, or whether a narrower voice artifact should be reviewed. | Names what can be disputed now. | Does not create appeal policy, reversal entitlement, or reviewer-election right. |
| `next_visible_state` | Deferred to later governance/rights review, or revised as a non-adopted voice-boundary scaffold. | Avoids ownerless adverse decisions. | Do not promise a date or external review capacity the repo has not adopted. |

## Contestability Boundary Matrix

| adverse issue | challengeable now | not challengeable through ordinary cadence | useful preserved residue |
|---|---|---|---|
| Wrong contribution class | The contributor can argue it should be `review`, `synthesis`, or `protocol design`. | The class dispute cannot grant governance power. | Classification rationale improves future triage. |
| Evidence gap disputed | The contributor can show phase-transition evidence or attack analysis exists. | A bare assertion that "voice requires votes" is not enough. | Missing-evidence list becomes a checklist for revision. |
| Useful value inside unsafe mechanism | The contributor can narrow to a voice or contestability artifact. | The unsafe voting-power mechanism remains out of scope. | The underlying legitimacy concern remains available for RQ7/RQ6. |
| Reviewer rationale too thin | The contributor can ask which boundary or source drove the adverse state. | Thin rationale does not imply acceptance by default. | Rationale minimums improve the review record. |
| Timing feels unfair | The contributor can challenge whether the item has a visible next state. | The repo has not promised response times or appeal windows. | Cadence research gains a test case for ownerless deferral. |
| Founder authority questioned | The contributor can identify the founder-context dependency. | Ordinary RQ4 review cannot transfer founder powers. | The concern routes to RQ6 phase-transition review. |
| AI-assisted review concern | The contributor can ask what the human reviewer checked directly. | Hidden model output is not an appeal forum. | Source-trace and human-rationale fields become more important. |

## Minimum Rationale Requirements

An adverse review note should be strong enough for a future contributor to
reconstruct the decision without the reviewer present. A later live procedure
should not adopt these fields until reviewed, but the scaffold suggests the
minimum evidence shape:

| field | minimum test |
|---|---|
| `state` | Is this `needs_revision`, `not_accepted`, `contested`, or `adversarial`? |
| `decisive_reason` | What one reason most explains the state? |
| `source_or_rule_basis` | Which source, template, rule, claim, test, or research question mattered? |
| `scope_of_decision` | What did the review decide, and what did it leave undecided? |
| `revision_route` | What narrower version, if any, would be reviewable? |
| `loss_notes` | What useful value was preserved without acceptance? |
| `contestability_note` | What can be challenged now? |
| `governance_boundary` | Which part requires Joe, governance review, or later policy work? |
| `timing_or_owner_note` | What is the next visible state without making a response-time promise? |

## Review Timing Implications

### Rolling Triage

Rolling triage can identify a governance-sensitive adverse path quickly, but it
should not decide the protected mechanism. A safe triage note says:

- this is protocol design with governance effects;
- ordinary cadence cannot adopt voting power;
- the useful concern is contestability and voice;
- later review needs phase-transition and capture evidence.

### Batch Review

Batch review is better for comparing governance-sensitive adverse items against
other cadence, rights, and transition proposals. It should still avoid making
contested states ownerless. The batch note needs a visible next state, even if
that state is "deferred until RQ6/RQ7 review."

### Pilot-Gated Review

Pilot-gated review can treat the adverse case as a synthetic test input. That
is safest against premature promises, but weakest for open attemptability. The
pilot should record whether a synthetic contributor could understand:

- the adverse state;
- the decisive reason;
- the revision route;
- the preserved loss note;
- and what can be challenged.

## Capture And Legitimacy Checks

Before any adverse-review or dispute path becomes real, reviewers should ask:

1. Does the path let contributors challenge decisions without granting automatic
   power to whoever contests most loudly?
2. Does the path preserve useful value without creating a reward promise,
   retained-value right, or governance claim?
3. Does the review state expose founder judgment instead of hiding it behind
   process language?
4. Does the cadence avoid both urgency pressure and ownerless delay?
5. Can bad-faith contributors exploit contestability to relitigate every
   decision or exhaust reviewers?
6. Can good-faith contributors understand what evidence would change the
   outcome?

## Later Review Questions

- Should `templates/contribution-proposal.md` or the reviewer-only section
  eventually include a `contestability_note` field?
- Should `templates/contribution-log-schema.md` eventually distinguish
  `contestability_note` from `loss_notes`?
- What is the smallest adverse-review note that remains legitimate to a
  newcomer?
- Which adverse states require public summary, and which can remain local to a
  contribution record?
- When does a challenge become a governance proposal rather than a review
  dispute?
- What evidence would justify a real appeal or dispute workflow in Phase 3 or
  Phase 4?

## Boundary Notes

- No real contributor is represented here.
- No real contribution was accepted, rejected, contested, scored, logged, or
  rewarded.
- No live contribution log entry was changed.
- No review cadence, appeal rule, dispute process, reviewer authority,
  response-time promise, governance policy, reward meaning, rights policy,
  claim status, test pass/fail state, or public posture changed.
- This scaffold is draft research evidence for later RQ4 review, not active
  workflow policy.
