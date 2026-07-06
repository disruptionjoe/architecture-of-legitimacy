---
artifact_type: rq9_reward_test_boundary
status: non_adopted_scaffold
created: 2026-07-06
research_question: RQ9 reward logic
claim_targets:
  - C4
  - C5
governance_role: review_prep_only
constitutional: false
---

# RQ9 Reward-Test Boundary

Status: draft research scaffold, not adopted reward logic.

Purpose: make any later reward experiment reviewable before the repo changes reward meaning, contribution scores, retained-value language, governance authority, claim status, public posture, or real contribution records.

This file does not create a reward mechanism, payout formula, token, retained-value right, contributor entitlement, governance-weight rule, legal or financial claim, tax meaning, ownership interest, employment relationship, review priority, sanction rule, appeal rule, or active contribution-review policy. It only defines how candidate reward tests should be bounded before they can be considered.

## Source Surfaces

- `RESEARCH-AGENDA.md`, especially RQ9.
- `ROADMAP.md`, especially Phase 2 formalization before Phase 3 pilot review.
- `CLAIMS.md`, especially C4 and C5.
- `LEGITIMACY-SCHEMA.md`, especially visibility, contestability, exit with retained record, bounded authority, and non-capture.
- `PROTOCOL-STACK.md`, especially contribution log, rights, rewards, governance, and capture monitoring.
- `CONTRIBUTION-STANDARDS.md`, especially the no-automatic-reward boundary for scores.
- `THREAT-MODEL.md`, especially reward gaming and economic capture.
- `templates/contribution-log-schema.md`, especially `loss_notes` and score boundaries.
- `projects/toy-payoff-model/2026-07-02-t5-collaboration-defection-payoff-model.md`.
- `projects/toy-payoff-model/2026-07-05-t5-collaboration-threshold-sensitivity-map.md`.
- `projects/participant-rights/2026-07-03-rq7-voice-exit-retained-value-boundary-map.md`.
- `projects/attack-profitability/2026-07-03-rq8-attack-profitability-variable-map.md`.
- `projects/reward-readiness/2026-07-03-rq9-reward-readiness-boundary-map.md`.

## Boundary Under Review

RQ9 asks what reward mechanism could be tested without pretending the full governance problem is solved. The reward-readiness boundary map separated reward alternatives from adoption. This scaffold adds a second guard: what would need to be true before one alternative can even become a bounded test packet.

The key distinction:

```text
reward alternative -> candidate test packet -> governance review -> possible experiment
```

This file only works the `candidate test packet` stage. It is earlier than adoption, earlier than a pilot, and earlier than any real contributor meaning.

## Test Packet Minimum

Every candidate reward test should answer these questions before it is considered:

| section | question | evidence to inspect | stop condition |
|---|---|---|---|
| Mechanism name | What exact reward alternative is being tested? | RQ9 inventory and protocol layer affected. | Stop if the mechanism is vague enough to smuggle in payout, status, or governance power. |
| Unit of recognition | What object receives recognition: artifact, accepted contribution, review labor, synthesis, correction, or retained residue? | Contribution classes, log schema, review state, and loss notes. | Stop if the unit cannot be reconstructed from public records. |
| No-reward baseline | What happens if no reward is tested? | Existing rationale, attribution, retained record, and contestability. | Stop if the test assumes reward is required before the baseline is examined. |
| Value signal | Which value signal would the test observe without treating scores as shares? | Rubric rationale, disagreement notes, and accepted/revised examples. | Stop if scores become balances, debt, payout math, or governance weight. |
| Contestability | How could a contributor challenge the classification or value signal? | Adverse-decision trace, contestability markers, and review rationale. | Stop if a reward test needs an appeal policy that does not exist. |
| Attack delta | Which attack variable becomes more attractive because the test exists? | RQ8 variables, T5 sensitivity terms, and threat model surfaces. | Stop if the test raises `B_a`, `P_a`, or `G_d` without a detection or mitigation answer. |
| Authority boundary | Who could authorize, pause, revise, or reverse the test? | Founder constraint work and governance surfaces. | Stop if the answer silently changes founder powers or reviewer authority. |
| External meaning screen | Could the test imply legal, financial, tax, securities, employment, IP, or ownership meaning? | Explicit review only if Joe authorizes that path later. | Stop immediately; this repo scaffold cannot create those meanings. |

## Candidate Reward-Test Boundary Matrix

The rows below are not proposed experiments. They show how each alternative would need to be bounded before it could be reviewed.

| alternative | minimal test object | first safe evidence | attack or legitimacy pressure | non-adoption boundary |
|---|---|---|---|---|
| No-reward baseline | One or more contribution records with clear rationale, attribution, loss notes, and contestability marker. | Synthetic or real traces showing whether recognition alone preserves trust. | High-value contributors may experience extraction if records preserve value without any future review path. | Do not convert baseline into a permanent anti-reward policy. |
| Symbolic credit | Public recognition attached to a specific accepted artifact or preserved residue. | Stable artifact link, review rationale, and contribution class. | Credit can become status capture, founder favoritism, or shadow governance rank. | Do not create rank, priority, payout, reviewer authority, or governance power. |
| Review priority | A routing hypothesis for repeated useful contributors or urgent repair work. | Evidence that the contributor's prior work improves review quality without excluding newcomers. | Priority can weaken open attemptability and become insider privilege. | Do not grant faster review, queue position, veto, or standing authority here. |
| Retained-value marker | A non-promissory note that accepted value may be reviewed later. | Contribution log field clarity, loss notes, and RQ7 retained-value language. | Markers can become shadow tokens or payout expectations. | Do not create entitlement, transferable claim, ownership, token, or future conversion rule. |
| Retroactive reward pool | A hypothetical later pool evaluated against past contribution records. | Clean record integrity, contestability, value-rubric stability, and capture review. | Ambiguous early records can become payout conflict and strategic claiming. | Do not promise a pool, formula, conversion rate, date, source of funds, or eligibility. |
| Revenue-linked distribution | A distant hypothesis for mapping future revenue to accepted value. | None sufficient inside current repo state. | Creates legal, tax, ownership, and accounting meanings outside current authority. | Stop before shares, percentages, obligations, revenue claims, or financial terms. |
| Token-like issuance | A distant hypothesis for portable programmable rewards. | None sufficient inside current repo state. | Intensifies sybil, speculation, market, and governance capture. | Stop before token design, supply, balances, transferability, or issuance terms. |
| Governance weight | A hypothesis that contribution history may later affect rule-making. | Founder-power limits, reviewer selection criteria, appeal path, and capture safeguards. | Reward recipients can entrench rule control. | Do not attach voting, veto, reviewer selection, or rule-making power to contribution records. |

## No-Reward Baseline Pressure Check

Before any positive reward test, the repo should ask whether the no-reward baseline is failing for a specific reason.

| pressure | baseline question | local evidence to inspect | boundary |
|---|---|---|---|
| Recognition adequacy | Can contributors find durable credit for accepted work? | Contribution log fields, artifact links, and synthesis notes. | Improve visibility before inventing reward. |
| High-effort residue | Does high-effort work retain useful loss notes when not accepted as-is? | `loss_notes`, adverse-decision traces, and revision routes. | Preserve residue without implying compensation. |
| Trust after adverse decision | Does contestability keep good-faith participation possible? | Rationale, contested state, and reviewer response minimums. | Do not adopt appeal rights here. |
| Score ambiguity | Are value scores being read as reward shares? | Rubric language, score notes, and contributor-facing explanations. | Reassert score-as-rationale before any reward discussion. |
| Strategic claiming | Are contributors treating early records as payout debt? | Retained-value language and review notes. | Add non-promissory wording; do not assign value. |
| Capture risk | Would any reward expectation increase gaming or agenda pressure? | RQ8 variables and threat model categories. | Stop before mechanism review if detection is unclear. |

## Worked Packet Shape

Later RQ9 work can use this template for exactly one candidate reward test:

```text
Candidate reward-test packet
  1. Alternative under review
  2. Unit of recognition
  3. No-reward baseline result
  4. Public records the test can inspect
  5. Value signal and score boundary
  6. Contestability path
  7. Attack-profitability delta
  8. Authority to pause, revise, or reverse
  9. External meaning screen
  10. Joe/governance adoption questions
```

The packet should be rejected as premature if it cannot complete any of sections 2 through 9 from public repo records without private founder context or new policy adoption.

## Local Repair Versus Governance Review

Safe local research can:

- make the no-reward baseline more inspectable;
- map an alternative to the records it would need;
- identify which reward phrases are ambiguous;
- compare attack deltas without assigning real value;
- name missing evidence fields for future review;
- or draft a later packet template with explicit non-adoption language.

Stop for Joe or governance review before:

- adopting a reward mechanism, payout formula, pool, token, entitlement, retained-value right, review priority, governance weight, or score conversion;
- changing contribution standards, review states, appeal paths, sanctions, disclosure requirements, reviewer authority, founder powers, governance rules, participant rights, claim status, public posture, protected licenses, or real contribution records;
- assigning economic value to any contribution, retained record, loss note, or synthetic case;
- interpreting scores, records, markers, or loss notes as legal, financial, tax, token, ownership, employment, securities, IP, or governance claims;
- or using this scaffold to solicit, promise, publish, or deploy any reward system.

## Later RQ9 Review Questions

1. Which reward alternative, if any, has enough public record evidence to become a candidate test packet?
2. Which current records are too ambiguous to support even symbolic credit beyond ordinary attribution?
3. Which no-reward baseline pressure is most real: recognition, high-effort residue, adverse-decision trust, score ambiguity, strategic claiming, or capture risk?
4. Which attack variable changes first when reward expectations appear?
5. Which reward-adjacent language should be rewritten before Phase 3 real contribution pilots?
6. Which authority boundary would pause or reverse a reward test if it starts producing capture pressure?

Until those questions are answered through a governed review, this scaffold does not strengthen C4 or C5, mark any test passed, create reward readiness, select a mechanism, create participant rights, move public posture, or alter any contribution record.
