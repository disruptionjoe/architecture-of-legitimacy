---
artifact_type: cadence_timing_comparison
status: draft_comparison
created: 2026-07-05
research_target: RQ4 cadence and evaluation
governance_role: internal_research_scaffold
constitutional: false
---

# RQ4 Cadence Timing Comparison

Status: draft comparison scaffold.

Purpose: compare how different review timing shapes affect the same synthetic
substantive contribution before the project adopts any active cadence rule.

This file is not a contribution policy, review-cadence decision, appeal rule,
reviewer-authority change, claim-status decision, reward rule, public-posture
change, response-time promise, or live contribution decision. It is a bounded
research scaffold for testing timing effects against rationale visibility, loss
notes, and contested-state handling.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ4.
- `ROADMAP.md`, especially Phase 1 and Phase 3.
- `CONTRIBUTING.md`.
- `CONTRIBUTION-STANDARDS.md`, especially Review Cadence.
- `projects/review-cadence-options/2026-07-02-rq4-review-cadence-options.md`.
- `projects/prototype-workflow/2026-07-02-rq5-prototype-workflow-synthesis.md`.
- `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md`.
- `projects/first-contribution-workflow-dry-run/2026-07-05-t11-synthetic-adverse-decision-trace.md`.
- `projects/coupled-stack-dependency/2026-07-03-c2-fixture-readiness-review.md`.

## Synthetic Contribution Held Constant

- **Title:** Add a visible next-review-window field to first-response triage.
- **Contributor:** Synthetic Contributor E (agent-assisted: yes).
- **Contribution class:** protocol design, with review and synthesis effects.
- **Target file(s) / question(s):** RQ4 review cadence, RQ5 prototype workflow,
  `CONTRIBUTION-STANDARDS.md` review cadence.
- **Summary:** Proposes that first-response triage for substantive contributions
  should name the next expected review window so a contributor can distinguish
  acknowledgement from acceptance and know when a real review may occur.
- **Evidence or reasoning:** Local RQ4 and RQ5 scaffolds already flag the risk
  that fast triage may be mistaken for a decision, while delayed batch review may
  make contested states feel ownerless.
- **Failure or risk:** Could become an implied response-time promise, overburden
  founder-led review, or smuggle cadence policy into ordinary contribution
  handling before a real pilot.
- **Loss or deferred value:** Even if the field is not adopted, the proposal
  names a useful trace problem: contributors need visible timing state, not only
  a final review state.
- **Proposed review state on submit:** submitted.

## Timing Comparison

| cadence shape | first visible state | likely substantive state | rationale visibility | loss-note handling | contestability visibility | primary timing risk |
|---|---|---|---|---|---|---|
| Rolling triage plus weekly batch | `triaged` quickly, with class and next batch window. | `needs_revision` or deferred after batch review. | Strong if triage says "not a decision" and batch review records the decisive reason. | Preserve the value of the timing-state idea without adopting the field. | Contributor can contest whether the item was placed in the right lane or batch. | Fast acknowledgement may be mistaken for acceptance or a response-time promise. |
| Continuous maintenance, twice-monthly substantive review | No fast substantive decision; maintenance-only items can move continuously. | Deferred to the next substantive window. | Strong only if the deferral note names why this is substantive protocol design. | Preserve the coordination value while explaining why policy movement waits. | Contributor can contest classification, but may wait too long for a disposition. | Delay may make contestability formal but practically weak. |
| Pilot-gated cadence before real external review | Logged as a synthetic or invited pilot item, not a public cadence commitment. | Use as pilot evidence rather than adopting the field. | Strong if the pilot records load, timing, and rationale sufficiency. | Preserve the trace problem as evidence for choosing a later cadence. | Contestability remains a test object, not a live appeal path. | The project may appear open while still withholding a usable public expectation. |

## Review Trace Under Each Shape

### Rolling Triage Plus Weekly Batch

1. Triage can happen quickly because it only classifies the proposal as
   protocol design with review effects.
2. The triage note must say it is not acceptance, not policy adoption, not an
   appeal rule, and not a response-time promise.
3. The weekly batch review can decide whether the idea belongs in a later
   cadence proposal, a pilot checklist, or `needs_revision`.
4. If narrowed, loss notes should preserve the useful distinction between
   acknowledgement timing and final decision timing.
5. If contested, the contributor can challenge lane placement or the batch
   deferral without claiming an appeal right.

### Continuous Maintenance, Twice-Monthly Substantive Review

1. The proposal should not move through continuous maintenance because it changes
   the meaning of review timing.
2. A deferral note should name the substantive review lane and the reason for
   batching.
3. The later review can compare this proposal with other cadence, rationale, or
   workflow suggestions.
4. Loss notes should preserve the idea's coordination value if the field itself
   is rejected as too promissory.
5. The weak point is contributor experience: a long wait can make a visible
   state less legitimate unless the open state has an owner.

### Pilot-Gated Cadence

1. Treat the proposal as a synthetic pilot input rather than a live contribution.
2. Record how long triage and review took, what rationale was enough, and where
   hidden founder context still appeared.
3. Use the pilot to compare Option A and Option B from the RQ4 scaffold without
   telling real contributors that either option is active.
4. Preserve loss notes about the timing-state problem even if the pilot does not
   adopt the field.
5. The weak point is open attemptability: pilot-gating protects against
   overpromise, but it can also delay the first real external contribution.

## Findings

1. **First-response visibility matters, but it is not the same as speed.** A
   quick triage state is useful only if it clearly says what has and has not
   been decided.
2. **Batching improves substantive comparison but needs an owner.** Batch review
   reduces urgency pressure, but an ownerless deferred state weakens
   contestability.
3. **Pilot-gating is safest against overpromise but weakest for openness.** It
   can protect the repo from premature cadence commitments while making the
   public contribution path feel less real.
4. **The same proposal needs different loss notes under different cadence
   shapes.** A fast lane preserves deferred policy value; a slow lane preserves
   contributor-orientation value; a pilot lane preserves evidence for later
   cadence selection.
5. **A later real cadence decision should test fields before adopting them.**
   The candidate field is not adopted here; it is a prompt for future review of
   whether first-response records need a visible next-review-window marker.

## Later Review Questions

- What is the shortest first-response note that prevents triage from looking
  like acceptance?
- Should a deferred substantive review name a date, a window, or only an owner?
- Which contribution classes can safely receive rolling decisions?
- When does a timing expectation become a public promise the repo cannot keep?
- Should contested states require a next review window before any real
  external contribution is invited?

## Boundary Notes

- No real contributor is represented here.
- No real contribution was accepted, rejected, contested, scored, logged, or
  rewarded.
- No live contribution log entry was changed.
- No review cadence, appeal rule, reviewer authority, response-time promise,
  governance policy, reward meaning, rights policy, claim status, test
  pass/fail state, or public posture changed.
- This comparison is draft research evidence for later RQ4 review, not active
  workflow policy.
