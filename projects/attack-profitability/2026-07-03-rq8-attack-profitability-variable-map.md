---
artifact_type: rq8_attack_profitability_variable_map
status: research_scaffold
created: 2026-07-03
research_question: RQ8 attack and capture modeling
governance_role: internal_modeling_scaffold
constitutional: false
---

# RQ8 Attack-Profitability Variable Map

Status: research scaffold.

Purpose: make RQ8 reviewable by connecting the current threat classes, protocol layers, T6 attack scenarios, and C4 proof burden to a shared attack-profitability vocabulary.

This file is not a threat-model update, mitigation adoption, reward-readiness decision, governance rule, rights policy, claim-status change, public-posture change, or evidence that any test has passed. It prepares questions a later review can answer.

## Source Surfaces

This scaffold reads the current repo state as evidence:

- `THREAT-MODEL.md` asks for attack-profitability equations for major threat classes.
- `PROTOCOL-STACK.md` places capture monitoring after governance and reward layers, while warning that reward and governance mechanisms can intensify gaming.
- `CLAIMS.md` gives C4 the proof burden to define agents, payoffs, attack costs, benefits, and scaling assumptions.
- `TESTS.md` names attack-profitability variables: `B_a`, `C_a`, `P_a`, `D_a`, `S_a`, `R_a`, and `M`.
- `projects/attack-surface-map/2026-07-02-t6-attack-surface-map.md` gives synthetic attacks and candidate levers without marking T6 passed.

## Variable Glossary

| variable | working meaning | first evidence to look for | governance boundary |
|---|---|---|---|
| `B_a` | Benefit an attacker expects from a successful attack. | What value, visibility, authority, reward expectation, or agenda control the attack would capture. | Do not define real reward value or retained claims here. |
| `P_a` | Probability the attack succeeds under current process. | Where validation, cadence, review, source trails, or log fields would fail to catch the attack. | Do not adopt new reviewer powers or appeal rules here. |
| `C_a` | Direct cost of attempting the attack. | Time, coordination, reputation risk before detection, contributor effort, or required artifacts. | Do not impose new participation barriers here. |
| `M` | Mitigation cost imposed by protocol design. | Extra fields, batching, rationale requirements, disclosure prompts, review windows, or traceability steps. | Do not promote a mitigation to policy here. |
| `D_a` | Probability the attack is detected. | Observable signals, duplicate links, conflict patterns, AI-use traces, missing sources, or suspicious rule changes. | Do not create surveillance, identity, or disclosure policy here. |
| `S_a` | Formal sanction if detected. | Rejection, revision request, ineligibility, removal from review, or explicit adverse note. | Do not define sanctions here. |
| `R_a` | Reputation or future-access cost if detected. | Public rationale, durable record, reviewer memory, contributor trust, or loss of future influence. | Do not create public shaming or participant-rights rules here. |

## Threat-Class Crosswalk

| threat class | likely first variable to model | useful second variable | reason to start there |
|---|---|---|---|
| Economic capture | `B_a` | `D_a` | Economic attacks usually become attractive when value or influence is legible before conflicts, sponsorship, or volume patterns are visible. |
| Epistemic capture | `P_a` | `C_a` | Epistemic attacks work when shallow plausibility can pass review cheaply. Better evidence minimums should change success probability before sanctions matter. |
| Governance capture | `R_a` | `M` | Governance capture often hides in procedural normality. Durable records, rationale, and pre-decision capture checks can make quiet rule capture costlier. |
| Cross-class capture | `B_a` | `P_a` | Rights, exit, contribution logs, rewards, and founder authority can combine value extraction with procedural advantage. |

## T6 Scenario Variable Map

| T6 scenario group | primary attacked layer | variable most exposed | modeling note |
|---|---|---|---|
| Low-value volume and duplicate submissions | contribution intake | `P_a * B_a` | The model should ask whether volume creates visibility, priority, or future-claim benefit before quality review can sort it. |
| Rubric or definition capture | value rubrics | `B_a` | The model should name who benefits when a scoring dimension changes, without adopting a new rubric. |
| Future payout or retained-value ambiguity | rewards and rights | `B_a` | The model should keep present recognition separate from future reward hypotheses. |
| Sponsored or affiliated review pressure | reviewer selection | `D_a + R_a` | The model should ask what conflict signals are visible without deciding disclosure policy. |
| Shallow prior-art collision | prior-art review | `P_a` | The model should distinguish label-level similarity from mechanism-level collision. |
| Smooth synthesis that removes caveats | synthesis | `D_a` | The model should treat lost uncertainty markers as a detection failure. |
| Hidden AI volume or synthetic consensus | AI support and validation | `C_a + D_a` | The model should ask which source trails make hidden volume more expensive or detectable. |
| Appeal sinkholes and adverse record loss | cadence, log, and contestability | `R_a` | The model should ask whether procedural delay or hidden loss notes reduce reputational cost for capture. |
| Founder entrenchment and rule-change timing | governance | `M + D_a` | The model should ask what pre-decision capture check is needed before powers or rules move. |

## First Modeling Questions

1. For each T6 scenario, what is the smallest concrete benefit an attacker could extract without a mature reward system?
2. Which attacks become much more attractive only after rewards, governance powers, reviewer authority, or retained-value markers are adopted?
3. Which protocol layer can most cheaply reduce `P_a` or increase `D_a` without making first contributions too hard?
4. Which mitigations only improve visibility or rationale, and which would cross into governance, rights, reward, sanction, or disclosure policy?
5. Which scenarios require modeling participant exit or adverse-decision legitimacy before estimating attack profitability?
6. Which variables are currently impossible to estimate without real contribution traces?

## Candidate Equation Shape

The existing starter can become a scenario-specific inequality:

```text
Attack attractive when:

P_a(surface, process_state) * B_a(value_at_risk)
>
C_a(attacker_effort) + M(protocol_friction) + D_a(observable_signal) * S_a(response_cost) + R_a(future_trust_loss)
```

The useful next step is not numeric precision. The useful next step is identifying which term a protocol choice is supposed to change, and whether that choice is local workflow repair or governance-sensitive policy.

## Review Boundaries

Safe to do in a later bounded review:

- map one T6 scenario to all variables,
- compare two local workflow repairs by which variable they affect,
- identify a missing evidence field as a proposal,
- mark which variables remain unknowable before real contribution traces.

Stop and require Joe or governance review before:

- adopting a mitigation as policy,
- changing contributor eligibility, appeal, disclosure, sanction, rights, reward, retained-value, reviewer-authority, or governance rules,
- changing claim status or public posture,
- treating a synthetic attack scenario as evidence about a real contributor,
- or assigning economic value to a retained claim.

## Open Output For RQ8

RQ8 can become sharper when this scaffold produces:

- one worked attack-profitability example per threat class,
- a list of variables the current protocol stack can affect without policy adoption,
- a list of variables that require governance or reward review,
- and a separation between pre-reward capture risk and post-reward capture risk.

Until then, this file is only a boundary map for modeling work. It does not strengthen the repo's public claims.
