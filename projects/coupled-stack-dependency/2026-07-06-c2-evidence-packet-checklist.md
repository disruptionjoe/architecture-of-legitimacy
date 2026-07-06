# C2 Evidence Packet Checklist

Date: 2026-07-06

Status: non-adopted review-prep artifact.

Purpose: answer the C2 fixture-readiness review question about which existing artifacts should be read together as the first evidence packet for the coupled-stack claim.

This checklist does not change C2 status, mark any test passed or failed, adopt a proof packet, add or remove protocol layers, change governance or reward policy, make a prior-art or novelty verdict, change public posture, or decide any real contribution.

## Source Surfaces

- `CLAIMS.md` for the C2 proof burden.
- `PROTOCOL-STACK.md` for the provisional layer sequence.
- `LEGITIMACY-SCHEMA.md` for legitimacy conditions.
- `THREAT-MODEL.md` for capture classes.
- `CONTRIBUTION-STANDARDS.md` for contribution classes, review states, and rubric dimensions.
- `TESTS.md` for current bounded test artifacts.
- `projects/coupled-stack-dependency/2026-07-03-c2-coupled-stack-dependency-map.md` for the dependency rows.
- `projects/coupled-stack-dependency/2026-07-03-c2-fixture-readiness-review.md` for fixture coverage and remaining review questions.

## Review Question

For C2, the immediate review question is not whether every layer has a separate fixture. It is whether the existing artifacts already show that evaluating one module in isolation hides legitimacy, record, reward, governance, or capture risk that only appears when the stack is read together.

The first C2 evidence packet should therefore group artifacts by what coupling risk they expose, not by the date they were created.

## Packet Checklist

| packet | read together | coupling question | what would count as a useful answer |
|---|---|---|---|
| Proof burden frame | `CLAIMS.md`, `PROTOCOL-STACK.md`, `projects/coupled-stack-dependency/2026-07-03-c2-coupled-stack-dependency-map.md` | What does C2 require beyond a list of useful modules? | A reviewer can name which dependencies are legitimacy-critical, merely convenient, or still ambiguous. |
| Trace preservation | `projects/first-workflow-simulation/2026-07-02-t3-newcomer-workflow-simulation.md`, `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md`, `projects/first-contribution-workflow-dry-run/2026-07-05-t11-synthetic-adverse-decision-trace.md`, `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-log-examples.md` | Can the workflow preserve the path from submitted evidence to accepted, revised, or rejected record without private founder context? | The reviewer can reconstruct target, rationale, review state, loss notes, contestability marker, and log implications from public artifacts. |
| Review usability | `projects/contribution-eligibility/2026-07-06-rq1-disclosure-edge-case-matrix.md`, `projects/contribution-taxonomy/2026-07-06-rq2-boundary-case-fixture.md`, `projects/value-rubric-options/2026-07-06-rq3-dimension-failure-map.md`, `projects/review-cadence-options/2026-07-06-rq4-adverse-review-contestability-boundary.md`, `projects/prototype-workflow/2026-07-06-rq5-workflow-handoff-gap-map.md` | Do eligibility, taxonomy, rubric, cadence, and workflow handoffs need each other for a reviewer to make a visible decision? | The reviewer can identify which ambiguities are local workflow repairs and which require governance or policy review. |
| Legitimacy failure pressure | `projects/legitimacy-failure-table/2026-07-02-t4-legitimacy-failure-table.md`, `projects/legitimacy-failure-table/2026-07-06-t4-response-routing-map.md`, `LEGITIMACY-SCHEMA.md` | Do legitimacy failures point to one module or to cross-layer repair? | The reviewer can separate failures caused by missing visibility, contestability, voice, exit, adaptive rules, bounded authority, and non-capture. |
| Capture and payoff pressure | `projects/attack-surface-map/2026-07-02-t6-attack-surface-map.md`, `projects/attack-profitability/2026-07-03-rq8-attack-profitability-variable-map.md`, `projects/attack-profitability/2026-07-06-rq8-capture-threshold-map.md`, `projects/toy-payoff-model/2026-07-05-t5-collaboration-threshold-sensitivity-map.md`, `THREAT-MODEL.md` | Which protocol choices change attack profitability or collaboration incentives only when read across layers? | The reviewer can name which variables belong to intake, validation, rubrics, logs, rights, rewards, governance, or monitoring. |
| High-authority gates | `projects/founder-phase-constraint/2026-07-06-rq6-emergency-rollback-boundary.md`, `projects/participant-rights/2026-07-06-rq7-exit-contestability-pressure-map.md`, `projects/reward-readiness/2026-07-06-rq9-reward-test-boundary.md`, `projects/generalization/2026-07-06-rq10-transfer-failure-boundary.md` | Which C2 implications must remain review-gated because they approach rights, rewards, governance transfer, or generalization? | The reviewer can keep C2 analysis from silently adopting powers, rights, reward meaning, portability, or public commitments. |
| AI and review authority | `projects/ai-role-boundary/2026-07-02-t8-ai-role-boundary-fixture.md`, `projects/ai-role-boundary/2026-07-03-c7-ai-assisted-review-trace-checklist.md`, `projects/ai-role-boundary/2026-07-06-c7-t8-ai-authority-failure-map.md` | Does AI assistance remain inspectable support rather than hidden legitimacy authority? | The reviewer can distinguish synthesis support from final judgment, citation laundering, synthetic consensus, and rubric substitution. |
| Fixture sufficiency | `projects/coupled-stack-dependency/2026-07-03-c2-fixture-readiness-review.md`, `TESTS.md` | Is another C2 fixture actually needed before review? | The reviewer can say which gaps are already covered, which are review questions, and which would need a later synthetic fixture. |

## Review Sequence

1. Start with the proof burden frame. Do not treat C2 as proven just because the repo has many related artifacts.
2. Read the trace-preservation packet next. If a future reader cannot reconstruct a synthetic decision, the stack is not yet doing the core record-preserving work.
3. Read review usability and legitimacy failure pressure together. This shows whether failures are local workflow gaps or cross-layer legitimacy problems.
4. Read capture and payoff pressure before reward or governance gates. This prevents early success from being mistaken for later robustness.
5. Read the high-authority gates last. These artifacts are brakes, not adoption surfaces.
6. Use the fixture-sufficiency packet to decide whether a later C2 run needs a new synthetic fixture or only a narrower review memo.

## Ready For Human Review When

A later C2 review packet is more useful if it can answer these without private context:

- Which dependency rows are necessary for legitimacy rather than merely helpful?
- Which isolated-layer failures are already shown by existing artifacts?
- Which failure still lacks a synthetic probe?
- Which C2 implications are gated because they would change rights, rewards, governance, public posture, or claim status?
- Which evidence would demote or narrow C2 instead of strengthening it?

This readiness signal is not acceptance. It only says the packet is organized enough for a reviewer to evaluate.

## Not Covered

This checklist does not provide:

- real contributor experience;
- source-backed prior-art collision verdicts;
- evidence that any test has passed;
- empirical attack or collaboration data;
- an adopted governance transition model;
- adopted rights or reward terms;
- or a public claim that the coupled stack has been validated.

## Non-Adoption Boundary

Do not use this checklist to:

- change C2 status;
- mark any test passed or failed;
- add or remove protocol layers;
- adopt a reward, rights, governance, appeal, sanction, disclosure, AI-review, or contribution policy;
- make a prior-art or novelty verdict;
- strengthen public posture;
- choose a pilot;
- or decide any real contribution.
