# C2 Fixture-Readiness Review

Date: 2026-07-03

Status: non-adopted review-prep artifact.

Purpose: answer the immediate review question left by the C2 coupled-stack dependency map: which isolated-layer failures already have enough fixture or scaffold coverage, and which would need a later synthetic fixture before real contribution review or claim-status movement.

This artifact does not create a fixture, require a fixture, change C2 status, mark any test passed or failed, adopt policy, make a prior-art or novelty judgment, or decide any real contribution.

## Source Surfaces

- `CLAIMS.md` for the C2 proof burden.
- `TESTS.md` for current test paths and linked artifacts.
- `PROTOCOL-STACK.md` for the provisional layer sequence.
- `THREAT-MODEL.md` for capture and attack concerns.
- `projects/coupled-stack-dependency/2026-07-03-c2-coupled-stack-dependency-map.md` for the dependency rows and open fixture question.
- Existing synthetic fixtures and review scaffolds linked from `TESTS.md` and `RESEARCH-AGENDA.md`.

## Review Answer

C2 should not automatically produce a new fixture for every dependency row.

The existing fixture set already covers many first-order isolated-layer failures. A later C2 fixture should be added only when all three conditions hold:

1. the isolated-layer failure cannot be inspected through an existing fixture or scaffold;
2. the missing probe affects C2's proof burden rather than only a lower-level design preference;
3. the fixture can be synthetic and reversible, without adopting governance, reward, rights, claim-status, source-packet, or contribution decisions.

## Fixture Coverage Map

| C2 dependency-map row | existing coverage | readiness disposition | possible later fixture only if needed |
|---|---|---|---|
| Eligibility | T1 taxonomy fixture, T3 newcomer workflow simulation, RQ1 eligibility options, T8 AI role boundary. | Covered enough for review-prep. Reuse existing artifacts before adding a new C2 fixture. | Multi-state eligibility sample comparing accepted, needs-revision, not-accepted, and adversarial attempts across contribution classes. |
| Contribution taxonomy | T1 taxonomy fixture, RQ2 review-path map, T2 value-rubric dry run. | Covered enough for current C2 review. The next useful move is reviewer comparison, not another taxonomy fixture. | Mixed-class submission exercise if future reviewers cannot choose primary class without private context. |
| Validation | T3 workflow simulation, T10 log examples, T11 legitimacy trace, RQ5 prototype workflow synthesis. | Partially covered. Current artifacts show normal and non-real review paths, but the adverse-decision path is still thin. | Synthetic adverse-decision trace with explicit rationale, revision route, loss notes, and contestability marker. |
| Value rubric | T2 value-rubric dry run, T4 legitimacy failure table, RQ3 rubric options. | Covered enough for first review. Add probes inside rubric review before creating a separate C2 fixture. | Rubric-gaming probe only if reviewers cannot distinguish useful disagreement from score theater. |
| Cadence | RQ4 review-cadence options, T3 workflow simulation, T11 trace. | Partially covered. Options exist, but no artifact compares timing effects on the same substantive contribution. | Same contribution run through rolling triage versus batch review, preserving rationale and contested-state visibility. |
| Contribution log | T10 synthetic log examples, T11 trace, contribution-log schema, RQ5 synthesis. | Covered enough for current C2 review. Existing artifacts already test whether future readers can reconstruct a synthetic decision. | Disputed or revised log-entry trace if a future contested-state review exposes reconstruction gaps. |
| Rights | RQ7 rights boundary map, T11 retained-right marker, contribution-log schema. | Review-prep coverage only. Do not create rights fixtures until rights questions remain explicitly non-adopted and bounded. | Synthetic exit or dispute scenario that separates retained record, retained value, appeal, and voice without adopting rights policy. |
| Rewards | T5 payoff model, T6 attack-surface map, RQ8 attack-profitability map, RQ9 reward-readiness map. | Coverage is intentionally gated. C2 should not create reward fixtures before reward readiness review. | No near-term C2 fixture. Later reward probes need explicit reward-readiness scope and Joe/governance review if they approach policy. |
| Governance | T7 founder-phase constraint review prep, RQ4 cadence options, RQ7 rights map, RQ9 reward-readiness map. | Coverage is review-prep only. Governance fixtures risk implying transfer decisions and should stay deferred. | Power-transfer scenario only after governance review defines the power, evidence requirement, and non-adoption boundary. |
| Capture monitoring | T6 attack-surface map, T5 payoff model, RQ8 attack-profitability variable map, THREAT-MODEL. | Covered enough for first modeling review. The next move is variable calibration or source-backed attack comparison, not a new C2 fixture. | Cross-layer capture scenario only if existing attack artifacts cannot show which layer changes attack profitability. |

## Near-Term Recommendation

The only near-term C2 fixture candidate worth holding open is the synthetic adverse-decision trace under Validation.

Reason: C2's proof burden is strongest when the repo can show that a contribution can be rejected, revised, or narrowed while preserving the legitimacy trace. Existing artifacts show submission, review, log examples, loss notes, and prior-art packet readiness, but they do not yet fully test a contested or adverse decision with explicit rationale and revision path.

This is not a decision to build that fixture now. It is a readiness note for a later Progress run or human review.

## Defer Or Avoid

- Do not create reward, rights, governance-transfer, sanctions, disclosure, or external-pilot fixtures as C2 shortcuts.
- Do not make C2 depend on fixture volume. C2 needs evidence that coupling matters, not a fixture for every layer label.
- Do not treat a synthetic fixture as evidence about real contributor experience.
- Do not use this review to change the C2 claim status, current test matrix, public posture, contribution standards, reward policy, or governance rules.

## Review Questions

1. Is the adverse-decision trace the smallest missing probe for C2, or should the first real prior-art pilot supply that evidence instead?
2. Which existing fixtures should be read together as the first C2 evidence packet?
3. What would show that C2 is over-coupled and should be narrowed to fewer required dependencies?
4. Which dependency rows are convenience links rather than legitimacy-critical couplings?
5. What evidence would justify moving from review-prep artifacts to a C2 status review?
