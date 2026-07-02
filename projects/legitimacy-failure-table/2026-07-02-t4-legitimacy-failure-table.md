---
artifact_type: legitimacy_failure_table
status: synthetic_test_fixture
created: 2026-07-02
test_target: T4 legitimacy failure table
governance_role: internal_test_record
constitutional: false
---

# T4 Legitimacy Failure Table

Status: synthetic test fixture.

Purpose: pressure-test whether the current legitimacy conditions in `LEGITIMACY-SCHEMA.md` can diagnose concrete failures without relying on private founder judgment.

This file is not a claim-status decision, canon verdict, governance change, reward rule, live contribution decision, or evidence that T4 has passed. It is a bounded test object for making legitimacy failure more inspectable.

## Conditions Under Test

The fixture uses the seven provisional legitimacy conditions:

- visibility
- contestability
- voice
- exit with retained record
- adaptive rule change
- bounded authority
- non-capture

It also cross-checks against the current protocol stack layers: eligibility, taxonomy, validation, value rubrics, cadence, contribution log, rights, rewards, governance, and capture monitoring.

## Use Pattern

For each failure mode, reviewers should record:

- which condition fails first,
- what evidence would make the failure observable,
- whether the failure is a design flaw, execution flaw, adversarial pressure, or normal dissatisfaction,
- which protocol layer should respond,
- and whether the response would require Joe review or governance authorization.

The useful result is not a complete taxonomy. The useful result is seeing whether reviewers can diagnose legitimacy failures without collapsing everything into vague unfairness, founder preference, or popularity.

## Failure Mode Matrix

| id | failure mode | primary condition at risk | early observable signal | likely source | candidate design response |
|---|---|---|---|---|---|
| T4-FM-01 | Opaque rationale: a review decision records the outcome but not the reason. | visibility | Contributors cannot tell which rubric dimension, evidence gap, or rule drove the result. | execution flaw | Require minimum rationale fields for triage, acceptance, revision, and rejection records. |
| T4-FM-02 | Appeal sinkhole: contestation exists in name but never receives a response or disposition. | contestability | Contested items accumulate without state, owner, or next review window. | design and execution flaw | Add an appeal state, response expectation, and unresolved-contest summary cadence. |
| T4-FM-03 | Social voice without structural uptake: feedback is welcomed socially but cannot alter rules. | voice | Repeated feedback appears in comments or notes but never becomes a rule-change proposal or documented non-action. | design flaw | Track rule-change proposals separately from ordinary contribution review. |
| T4-FM-04 | Exit erases claim trace: a contributor leaves and their accepted work becomes hard to discover or attribute. | exit with retained record | Accepted contributions remain in prose or history but not in a stable contribution record. | design flaw | Preserve accepted contribution links and contributor identifiers without implying reward or legal claim. |
| T4-FM-05 | Bureaucratic legitimacy drift: formal fields are complete while participants still experience the process as arbitrary. | adaptive rule change | Reviews meet checklist requirements but adverse decisions cluster around unclear criteria. | execution flaw | Pair compliance checks with periodic adverse-decision review and participant-feedback probes. |
| T4-FM-06 | Founder exception leak: founder judgment bypasses public rules without a visible exception record. | bounded authority | Similar submissions receive different treatment because private context or founder preference fills gaps. | governance risk | Record founder-only decisions as founder-phase exceptions and mark which rule is incomplete. |
| T4-FM-07 | Reward-shaped review: reviewers inflate scores because future reward, credit, or influence is expected. | non-capture | High-value scores cluster around strategic contributors, sponsors, or coalition partners without stronger evidence. | adversarial pressure | Keep early scores non-promissory and separate value discussion from reward readiness. |
| T4-FM-08 | AI judgment laundering: an AI-generated summary or score is treated as neutral authority. | visibility and contestability | Review notes cite an AI output without human rationale, source trail, or challenge path. | execution and capture risk | Require AI-use disclosure, human reviewer rationale, and contestable source links. |
| T4-FM-09 | Volume legitimacy: many small submissions create apparent contribution weight without proportional value. | non-capture | A contributor splits one idea into many records and accumulates visibility or score density. | adversarial pressure | Batch related submissions, record duplicate/dependent links, and review contribution units qualitatively. |
| T4-FM-10 | Rule-change capture: a procedural update makes future challenges harder while appearing neutral. | bounded authority and non-capture | Appeal windows narrow, reviewer eligibility concentrates, or rationale requirements weaken after a contested case. | governance capture | Route rule changes through explicit capture-risk review before adoption. |
| T4-FM-11 | Private-context dependency: a newcomer cannot reproduce why a contribution was accepted or rejected from public records. | visibility | The decision is intelligible only to people who know unstated history, relationships, or priorities. | design and execution flaw | Add context links, target claims/tests, and reviewer notes sufficient for a new contributor. |
| T4-FM-12 | Adverse-decision silence: rejected or narrowed work loses its useful residue. | contestability and exit with retained record | `needs_revision` or `not_accepted` decisions do not preserve what was useful, lost, or deferred. | execution flaw | Use loss notes so adverse decisions preserve inspectable value without forcing acceptance. |
| T4-FM-13 | Rights ambiguity: accepted contributors cannot tell what visibility, voice, exit, appeal, or retained-claim expectations attach to acceptance. | exit with retained record and voice | Accepted work is logged, but participation rights remain implicit or socially negotiated. | design flaw | Separate present-day rights from future reward hypotheses and record which rights are active now. |
| T4-FM-14 | Synthetic consensus: AI-assisted or coordinated submissions make a position look broadly supported before independent review exists. | non-capture | Multiple submissions repeat similar language, evidence, or framing without distinct reasoning. | epistemic capture | Track source overlap, require mechanism-level reasoning, and reward adversarial review of apparent consensus. |

## Diagnostic Boundaries

- A legitimacy failure is not the same as a contributor being unhappy with an outcome.
- A failed contribution review can remain legitimate if the reason, contest path, retained record, and rule-learning path are visible.
- A useful contribution can still require revision if it asks for governance, reward, claim-status, or public-posture movement before the repo has authority to make that move.
- Capture risk can arise from good-faith incentives, not only bad-faith attackers.
- The founder-led phase can be legitimate only if its exceptions and limits become inspectable rather than private.

## Candidate Review Questions

1. Can two reviewers identify the same primary condition for most failure modes?
2. Which failures require a local workflow repair versus Joe review or governance authorization?
3. Which failures already have mitigation in `CONTRIBUTION-STANDARDS.md`, `PROTOCOL-STACK.md`, or `THREAT-MODEL.md`?
4. Which failures need new evidence fields before real contributions are reviewed?
5. Are any legitimacy conditions redundant, or do they diagnose distinct failures?

## Pass Criteria For A Later T4 Review

T4 can move toward a stronger result when:

- reviewers can classify at least 10 legitimacy failures without private founder context,
- each failure maps to an observable signal rather than a mood label,
- candidate responses identify the affected protocol layer,
- governance-sensitive responses are separated from safe workflow repairs,
- and the table reveals at least one missing field, review state, or mitigation worth testing in a later run.

This fixture does not mark T4 passed. It gives the repo a repeatable object for testing whether legitimacy has become operational enough to diagnose failure.
