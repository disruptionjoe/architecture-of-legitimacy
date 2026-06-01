# Claim Ledger

This ledger separates live research claims from motivation, analogy, and overclaim. The project should update this file whenever a claim becomes sharper, weaker, falsified, or promoted.

## Claim Status Key

- `core`: central to the project.
- `working`: plausible but underformalized.
- `testable`: can be studied with a bounded test now.
- `horizon`: motivating extension, not yet established.
- `guardrail`: an explicit non-claim.

## Current Claims

| id | claim | status | proof burden | current test path |
|---|---|---|---|---|
| C1 | A public open source or open research repo is a useful first proving ground for legitimate contribution allocation. | core, testable | Show that first contribution artifacts can be classified, reviewed, logged, and contested in public. | Build and run a first contribution workflow. |
| C2 | The minimal serious object is a coupled protocol stack, not a single ledger, token, rubric, or governance rule. | core, working | Show that isolated modules fail or become misleading without the others. | Dependency map and failure analysis. |
| C3 | Legitimacy is a first-class design variable in contribution allocation. | core, working | Define legitimacy operationally enough that design choices can be assessed against it. | Legitimacy schema and participant-feedback probes. |
| C4 | Collaboration may become more valuable than defection under the right protocol conditions. | working, testable | Define agents, payoffs, attack costs, benefits, and scaling assumptions. | Toy payoff model and attack-profitability equations. |
| C5 | Accepted contributors should retain some durable claim on the value they helped create. | working | Define what "claim" can mean before mature rewards exist. | Rights taxonomy and contribution-log design. |
| C6 | Founder-led beginnings can be legitimate if powers, limits, and transition milestones are explicit. | working | Avoid founder theater by specifying commitments and transition criteria. | Governance phase model. |
| C7 | AI can support judgment, critique, synthesis, and review, but cannot itself supply legitimacy. | guardrail, working | Bound AI to contestable and inspectable roles. | AI-use policy and review workflow. |
| C8 | Repo-scale success may generalize to broader collaborative institutions. | horizon | Show transfer conditions from one repo to many projects or public-goods settings. | Future comparative pilots. |
| C9 | Post-scarcity conditions make contribution legitimacy more important. | horizon | Clarify which scarcities remain and which value-allocation assumptions change. | Essay and literature review. |

## Claim Classes

### Core Claims

The project currently stands on `C1`, `C2`, and `C3`.

If these fail, the project should be substantially revised:

- if a repo is not a useful proving ground, the project needs a different first test surface;
- if the stack is not coupled, the project can narrow to one mechanism;
- if legitimacy cannot be operationalized, the project loses its central novelty.

### Testable Working Claims

`C4`, `C5`, and `C6` are the first formalization burden.

They should become models, rubrics, schemas, or experiments before the project makes stronger public claims.

### Horizon Claims

`C8` and `C9` are inspiration and orientation. They should not be presented as proven.

## Current Novelty Hypothesis

The strongest candidate novelty is treating legitimacy conditions, contribution accounting, reward rights, and governance transitions as one coupled design object inside a public proving ground.

The novelty is not:

- "contributors should be rewarded,"
- "DAOs can govern projects,"
- "AI can score work,"
- "open source needs better incentives."

Those are known neighboring ideas. This project is about the coupled architecture.

## Falsification And Demotion Conditions

A claim should be demoted if:

- it cannot be operationalized without circular definitions,
- its test path requires assuming the conclusion,
- prior art already contains the same claim with stronger formalization,
- the first repo workflow produces mostly noise and no useful contribution signal,
- participants experience the review process as illegitimate despite procedural compliance,
- or attack modeling shows that value accumulation makes capture strictly easier under the proposed rules.

