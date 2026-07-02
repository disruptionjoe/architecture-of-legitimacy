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

- T10 synthetic log examples: [projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-log-examples.md](projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-log-examples.md). This pressure-tests three non-real log entries and does not mark T10 passed.
- T11 synthetic workflow trace: [projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md](projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md). This walks one non-real proposal through the current workflow and does not create a live contribution.

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
