# Tests

This file turns the project's claims into bounded checks.

The first tests are not final proof. They are small passes that should clarify what is worth building, what is too broad, and what fails early.

## Test Matrix

| id | test | claim target | first bounded pass | success signal | failure signal |
|---|---|---|---|---|---|
| T1 | Contribution taxonomy pass | C1, C2 | Define 6-10 contribution classes with examples. | Contributors can classify sample work consistently. | Most samples require private context or collapse into one vague category. |
| T2 | Value rubric dry run | C3 | Score 10 hypothetical contributions across proposed dimensions. | Rubric surfaces useful disagreements. | Rubric produces arbitrary or popularity-like scoring. |
| T3 | First workflow simulation | C1 | Walk one sample contribution from proposal to log entry. | A newcomer can follow the steps. | The process depends on founder intuition at every step. |
| T4 | Legitimacy failure table | C3 | Define at least 10 legitimacy failure modes. | Failures map to design responses. | "Legitimacy" remains too vague to diagnose anything. |
| T5 | Toy payoff model | C4 | Define collaborate/defect payoffs for simple contributor types. | Model identifies conditions where collaboration dominates. | Collaboration dominance requires unrealistic assumptions. |
| T6 | Attack-surface map | C2, C4 | Map economic, epistemic, and governance attacks. | Attack classes imply concrete mitigations. | Capture resistance remains slogan-level. |
| T7 | Founder phase constraint | C6 | Specify founder powers, limits, and transition triggers. | Founder-led phase becomes visible and bounded. | Decentralization remains a promise without constraints. |
| T8 | AI role boundary | C7 | Define allowed and disallowed AI uses in review. | AI supports synthesis without final authority. | AI becomes an opaque legitimacy substitute. |
| T9 | Prior-art collision check | C2, C3 | Compare the coupled-stack claim to 10 neighboring systems. | Novelty is narrowed or strengthened. | Existing prior art already contains the same object. |
| T10 | Contribution log prototype | C5 | Create a log schema and populate three examples. | Records attribution, validation, and future-claim notes. | The log cannot represent non-code contribution well. |
| T11 | S7 legitimacy trace workflow | C2, C3, C7 | Run one sample contribution through submission, validation, contestability, log entry, retained-right marker, and explicit loss notes. | Future contributors can reconstruct why the record is legitimate without private founder context. | The accepted record depends on opaque authority, hidden AI judgment, or unrecorded loss. |

## Test Artifacts

- T1 contribution taxonomy fixture: [projects/contribution-taxonomy/2026-07-01-t1-contribution-taxonomy-fixture.md](projects/contribution-taxonomy/2026-07-01-t1-contribution-taxonomy-fixture.md). This pressure-tests current contribution classes with synthetic sample submissions and does not mark T1 passed.
- T2 value rubric dry run: [projects/value-rubric-dry-run/2026-07-02-t2-value-rubric-dry-run.md](projects/value-rubric-dry-run/2026-07-02-t2-value-rubric-dry-run.md). This pressure-tests the current seven-dimension rubric with synthetic contributions and does not mark T2 passed.
- T3 newcomer workflow simulation: [projects/first-workflow-simulation/2026-07-02-t3-newcomer-workflow-simulation.md](projects/first-workflow-simulation/2026-07-02-t3-newcomer-workflow-simulation.md). This pressure-tests whether a first-time synthetic contributor can move from public proposal format to log-ready review outcome and does not mark T3 passed.
- T4 legitimacy failure table: [projects/legitimacy-failure-table/2026-07-02-t4-legitimacy-failure-table.md](projects/legitimacy-failure-table/2026-07-02-t4-legitimacy-failure-table.md). This pressure-tests current legitimacy conditions with synthetic failure modes and does not mark T4 passed.
- T5 collaborate/defect payoff model: [projects/toy-payoff-model/2026-07-02-t5-collaboration-defection-payoff-model.md](projects/toy-payoff-model/2026-07-02-t5-collaboration-defection-payoff-model.md). This pressure-tests the starter toy payoff model with synthetic contributor scenarios and does not mark T5 passed.
- T6 attack-surface map: [projects/attack-surface-map/2026-07-02-t6-attack-surface-map.md](projects/attack-surface-map/2026-07-02-t6-attack-surface-map.md). This pressure-tests economic, epistemic, and governance attack scenarios against protocol surfaces and does not mark T6 passed.
- T7 founder-phase constraint review prep: [projects/founder-phase-constraint/2026-07-02-t7-founder-phase-constraint-review-prep.md](projects/founder-phase-constraint/2026-07-02-t7-founder-phase-constraint-review-prep.md). This identifies governance decision slots and evidence requirements for later review and does not mark T7 passed or adopt founder powers, limits, transition triggers, emergency rules, or governance policy.
- T8 AI role boundary fixture: [projects/ai-role-boundary/2026-07-02-t8-ai-role-boundary-fixture.md](projects/ai-role-boundary/2026-07-02-t8-ai-role-boundary-fixture.md). This pressure-tests allowed AI support, conditional assistance, disallowed authority, and adversarial AI patterns in review without changing AI policy or marking T8 passed.
- T9 prior-art collision review scaffold: [projects/prior-art-collision-check/2026-07-02-t9-prior-art-collision-review-scaffold.md](projects/prior-art-collision-check/2026-07-02-t9-prior-art-collision-review-scaffold.md). This prepares a 10-system mechanism-comparison scaffold for future source-backed prior-art review and does not mark T9 passed or make a novelty verdict.
- T9 first source-packet checklist: [projects/prior-art-collision-check/2026-07-03-t9-first-source-packet-checklist.md](projects/prior-art-collision-check/2026-07-03-t9-first-source-packet-checklist.md). This prepares the first real prior-art packet for readiness review before any collision level, novelty judgment, claim-status change, or contribution decision.
- T10 synthetic log examples: [projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-log-examples.md](projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-log-examples.md). This pressure-tests three non-real log entries and does not mark T10 passed.
- T11 synthetic workflow trace: [projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md](projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md). This walks one non-real proposal through the current workflow, now reflects explicit `loss_notes` schema support, and does not create a live contribution.

## Supporting Research Artifacts

- C2 coupled-stack dependency map: [projects/coupled-stack-dependency/2026-07-03-c2-coupled-stack-dependency-map.md](projects/coupled-stack-dependency/2026-07-03-c2-coupled-stack-dependency-map.md). This maps local protocol-layer dependencies and isolated-layer failure modes without changing C2 status, marking test pass/fail state, adopting policy, making a prior-art verdict, or deciding any real contribution.
- C2 fixture-readiness review: [projects/coupled-stack-dependency/2026-07-03-c2-fixture-readiness-review.md](projects/coupled-stack-dependency/2026-07-03-c2-fixture-readiness-review.md). This reviews which C2 isolated-layer failures are already covered by existing fixtures and which would need later synthetic review without creating a fixture, changing C2 status, marking test pass/fail state, adopting policy, making a prior-art verdict, or deciding any real contribution.
- C7/T8 AI-assisted review trace checklist: [projects/ai-role-boundary/2026-07-03-c7-ai-assisted-review-trace-checklist.md](projects/ai-role-boundary/2026-07-03-c7-ai-assisted-review-trace-checklist.md). This prepares a review trace checklist for AI-assisted contribution review without changing AI policy, contribution policy, governance, claim status, public posture, reward or rights meaning, T8 pass/fail state, or real contribution records.

## Toy Payoff Model Starter

This is a placeholder model to refine.

Let a contributor choose `collaborate` or `defect`.

Variables:

- `V_c`: value created by collaboration.
- `R_c`: reward or retained claim from accepted collaboration.
- `L_c`: legitimacy benefit from participating in a trusted system.
- `C_c`: cost of collaborating.
- `G_d`: gain from defection, gaming, capture, or extraction.
- `P_d`: probability of successful defection.
- `S_d`: sanction or exclusion cost if defection is detected.
- `D_d`: detection probability.
- `F`: future value lost by damaging reputation or claim rights.

Simple condition:

```text
Collaborate is preferred when:

R_c + L_c + future_claim(V_c) - C_c
>
P_d * G_d - D_d * S_d - F
```

Research tasks:

- define contributor types,
- define what counts as defection,
- estimate which variables the protocol stack can affect,
- identify where legitimacy changes payoffs,
- identify where rewards intensify attacks.

## Attack-Profitability Starter

Let an attacker choose whether to capture a decision, rubric, governance process, or reward path.

Variables:

- `B_a`: benefit from successful attack.
- `C_a`: attack cost.
- `P_a`: probability of attack success.
- `D_a`: probability of detection.
- `S_a`: sanction if detected.
- `R_a`: reputational or future-access cost.
- `M`: mitigation cost imposed by protocol design.

Basic attack profitability:

```text
Attack is attractive when:

P_a * B_a > C_a + M + D_a * S_a + R_a
```

The project should study how protocol choices change `P_a`, `B_a`, `C_a`, `M`, and `D_a`.

## Single-Pass Agent Tasks

Good first agent tasks:

- produce 10 candidate contribution classes and examples,
- draft three alternative value rubrics,
- compare this project to Gitcoin, Optimism retro funding, Wikipedia, peer review, and DAO governance,
- create a first threat model table,
- turn the toy payoff model into a clearer variable glossary,
- draft the first contribution log schema,
- propose a founder-led phase with explicit constraints.
