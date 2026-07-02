---
artifact_type: toy_payoff_model
status: synthetic_test_fixture
created: 2026-07-02
test_target: T5 toy payoff model
governance_role: internal_test_record
constitutional: false
---

# T5 Collaboration/Defection Toy Payoff Model

Status: synthetic test fixture.

Purpose: pressure-test whether the starter collaborate/defect condition in `TESTS.md` can describe concrete contributor incentives without pretending that collaboration already dominates defection.

This file is not a reward rule, contribution score, retained-value promise, governance decision, claim-status decision, or evidence that T5 has passed. All values below are invented examples for T5 testing.

## Model Under Test

The starter condition in `TESTS.md` is:

```text
Collaborate is preferred when:

R_c + L_c + future_claim(V_c) - C_c
>
P_d * G_d - D_d * S_d - F
```

For this fixture, the terms mean:

| term | meaning | protocol lever to inspect |
|---|---|---|
| `R_c` | immediate recognition or review value from collaboration | contribution log, public rationale, synthesis cadence |
| `L_c` | legitimacy benefit from participating in a trusted process | visibility, contestability, voice, exit, bounded authority |
| `future_claim(V_c)` | non-promissory possibility that accepted value may matter later | retained-record marker, loss notes, explicit no-reward boundary |
| `C_c` | cost of producing and submitting useful work | templates, review cadence, clarity of live questions |
| `P_d` | probability defection succeeds | validation, batching, source trails, reviewer discipline |
| `G_d` | gain from gaming, capture, extraction, or low-value visibility | reward expectations, attention, governance influence |
| `D_d` | probability defection is detected | evidence minimum, AI disclosure, duplicate/dependency links |
| `S_d` | sanction or exclusion cost if detected | review state, rejection rationale, ineligibility rules |
| `F` | future value lost by harming trust, access, or reputation | public record, reviewer memory, appeal trail |

## Use Pattern

Reviewers should use this as a relative model, not as a calculator.

For each scenario, record:

- the contributor type,
- which term is most uncertain,
- which protocol choice changes the result most,
- whether collaboration depends on hidden founder context,
- whether a future reward assumption is doing too much work,
- and whether the scenario suggests a local workflow repair or a governance-sensitive decision.

The useful result is not a precise payoff. The useful result is seeing where the current stack can make collaboration more attractive without overpromising rewards or pretending defection disappears.

## Synthetic Scenario Matrix

Scale for the illustrative values:

- `0`: absent or negligible
- `1`: low
- `2`: moderate
- `3`: high

These values are only prompts for reviewer disagreement. They are not measurements.

| id | contributor type | collaborate-side sketch | defect-side sketch | preliminary read | pressure point |
|---|---|---|---|---|---|
| T5-PM-01 | maintenance contributor | Fixes broken links and terminology. `R_c=1`, `L_c=2`, `future_claim=0`, `C_c=1`. | Little gain from gaming. `P_d=1`, `G_d=1`, `D_d=2`, `S_d=1`, `F=1`. | Collaboration is likely preferred even without future reward because cost is low and visible usefulness is high. | Maintenance needs clear acceptance and attribution, not reward promises. |
| T5-PM-02 | prior-art researcher | Adds a source-backed comparison that narrows novelty. `R_c=2`, `L_c=3`, `future_claim=1`, `C_c=2`. | Could cherry-pick labels to win an argument. `P_d=2`, `G_d=2`, `D_d=1`, `S_d=1`, `F=2`. | Collaboration depends on reviewers rewarding truth-seeking even when it weakens the project's novelty story. | Evidence minimum and mechanism-level comparison raise `D_d`. |
| T5-PM-03 | formalization contributor | Defines variables for C4 with assumptions and limits. `R_c=2`, `L_c=2`, `future_claim=1`, `C_c=3`. | Can present confident equations without assumptions. `P_d=2`, `G_d=2`, `D_d=1`, `S_d=1`, `F=1`. | High contribution cost makes collaboration fragile unless review gives clear rationale and preserves partial value. | `needs_revision` records need loss notes so high-cost work is not erased. |
| T5-PM-04 | volume optimizer | Splits one idea into many small submissions. `R_c=1`, `L_c=1`, `future_claim=0`, `C_c=1`. | Visibility gain can be high if records count volume. `P_d=3`, `G_d=3`, `D_d=1`, `S_d=1`, `F=1`. | Defection may dominate unless batching and duplicate/dependency links reduce the value of volume. | Batch related submissions to lower `P_d * G_d`. |
| T5-PM-05 | AI-assisted contributor | Labels AI use and submits a reviewed synthesis. `R_c=2`, `L_c=2`, `future_claim=1`, `C_c=2`. | Can flood plausible text while hiding AI dependence. `P_d=2`, `G_d=3`, `D_d=1`, `S_d=1`, `F=1`. | Collaboration improves when disclosure is normal and hidden AI volume is detectable. | AI disclosure and source trails raise `D_d` without banning useful assistance. |
| T5-PM-06 | contested contributor | Receives an adverse decision but keeps a visible rationale, contest path, and loss note. `R_c=0`, `L_c=3`, `future_claim=1`, `C_c=2`. | Can escalate socially or distort the dispute. `P_d=2`, `G_d=2`, `D_d=2`, `S_d=1`, `F=2`. | Collaboration can remain attractive after rejection if legitimacy benefits survive the adverse outcome. | Contestability and retained record increase `L_c` and `F`. |
| T5-PM-07 | sponsored contributor | Discloses a funder while submitting relevant work. `R_c=2`, `L_c=2`, `future_claim=1`, `C_c=2`. | Can steer priorities while appearing neutral. `P_d=2`, `G_d=3`, `D_d=1`, `S_d=1`, `F=2`. | Collaboration depends on conflict visibility and review independence. | Conflict disclosure raises detection and reputation cost for agenda capture. |
| T5-PM-08 | reviewer or maintainer | Provides adversarial review that prevents reward gaming. `R_c=2`, `L_c=3`, `future_claim=1`, `C_c=2`. | Can favor allies or preferred contribution classes. `P_d=2`, `G_d=2`, `D_d=1`, `S_d=2`, `F=3`. | Collaboration is favored if reviewer rationale is public and biased review has high future trust cost. | Public rationale and dispute windows raise `F`. |
| T5-PM-09 | newcomer | Attempts a first contribution using only public docs. `R_c=1`, `L_c=1`, `future_claim=0`, `C_c=3`. | Can abandon the process or submit low-effort noise. `P_d=2`, `G_d=1`, `D_d=1`, `S_d=0`, `F=0`. | Collaboration may not dominate if the workflow depends on private context or high setup cost. | Better first-task routing lowers `C_c` and increases `L_c`. |
| T5-PM-10 | strategic claimant | Cites early scores as future payout obligations. `R_c=1`, `L_c=1`, `future_claim=2`, `C_c=1`. | Can convert ambiguity into implied debt. `P_d=2`, `G_d=3`, `D_d=1`, `S_d=1`, `F=1`. | Defection risk rises when future-claim language is vague. | Explicit no-reward and non-promissory retained-record boundaries lower `G_d`. |
| T5-PM-11 | deep synthesis contributor | Integrates tests, claims, and threats into a clearer map. `R_c=3`, `L_c=3`, `future_claim=1`, `C_c=3`. | Can smooth over uncertainty to gain praise. `P_d=2`, `G_d=2`, `D_d=2`, `S_d=1`, `F=2`. | Collaboration is favored if uncertainty preservation is valued, not punished. | Synthesis review should reward caveats, proof burdens, and source links. |
| T5-PM-12 | rule-change advocate | Proposes a cadence or appeal improvement. `R_c=2`, `L_c=2`, `future_claim=0`, `C_c=2`. | Can design process changes that advantage their own future work. `P_d=2`, `G_d=3`, `D_d=1`, `S_d=1`, `F=2`. | Collaboration depends on separating useful protocol design from adoption authority. | Governance-sensitive proposals can be logged without being accepted as policy. |

## Boundary Observations

- Collaboration can dominate for low-cost, high-visibility maintenance without any reward promise.
- High-cost formalization and synthesis need visible rationale, partial-value preservation, and review quality, or collaboration becomes fragile.
- Future-claim language is a dangerous variable when it is vague; it can help preserve value, but it can also increase gaming.
- Legitimacy benefits matter most after adverse or contested outcomes, not only after acceptance.
- Defection often becomes attractive when `P_d` is high and `D_d`, `S_d`, or `F` are low.
- The protocol stack can affect payoff terms, but it cannot eliminate incentives to defect.

## Candidate Review Questions

1. Which variable is least defined: recognition value, legitimacy benefit, future-claim value, detection probability, sanction cost, or future trust loss?
2. Which scenarios require only local workflow repair, and which would require governance or reward-policy review?
3. Does the model distinguish collaboration from obedience to founder preference?
4. Does any scenario depend on future rewards so heavily that it violates the current no-reward boundary?
5. Which protocol layer most reliably changes the result: contribution log, value rubric, cadence, rights, governance, or capture monitoring?

## Pass Criteria For A Later T5 Review

T5 can move toward a stronger result when:

- reviewers can define contributor types and defection types without private founder context,
- at least several scenarios identify a protocol choice that changes a named payoff term,
- collaboration does not require unrealistic reward promises,
- adverse decisions can still preserve enough legitimacy value to keep good-faith contributors engaged,
- and the model reveals which assumptions would need evidence before C4 becomes stronger.

This fixture does not mark T5 passed. It gives the repo a repeatable object for testing whether collaboration-versus-defection reasoning can become operational without overclaiming.
