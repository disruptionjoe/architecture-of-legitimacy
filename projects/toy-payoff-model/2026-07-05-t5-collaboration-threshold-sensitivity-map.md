---
artifact_type: t5_collaboration_threshold_sensitivity_map
status: synthetic_modeling_scaffold
created: 2026-07-05
test_target: T5 toy payoff model
governance_role: internal_review_scaffold
constitutional: false
---

# T5 Collaboration-Threshold Sensitivity Map

Status: synthetic modeling scaffold.

Purpose: turn the existing collaborate/defect toy payoff fixture into a reviewable sensitivity map. The useful question is not whether the model can assign real values. The useful question is which term would need to change before collaboration becomes more attractive than defection, and whether that change is a safe local workflow repair or a governance/reward-sensitive decision.

This file is not a reward rule, contribution score, payout formula, retained-value promise, governance rule, sanction policy, appeal path, contributor-rights policy, claim-status decision, public-posture decision, real contribution record, or evidence that T5 has passed. It uses synthetic pressure cases only.

## Source Surfaces

This scaffold reads the current repo state as evidence:

- `TESTS.md`, especially the T5 payoff condition.
- `ROADMAP.md`, especially Phase 2 formalization.
- `CONTRIBUTION-STANDARDS.md`, especially contribution classes, review states, and the no-automatic-reward boundary for scores.
- `projects/toy-payoff-model/2026-07-02-t5-collaboration-defection-payoff-model.md`.
- `projects/attack-profitability/2026-07-03-rq8-attack-profitability-variable-map.md`.
- `projects/reward-readiness/2026-07-03-rq9-reward-readiness-boundary-map.md`.

## Model Under Review

The current T5 condition is:

```text
Collaborate is preferred when:

R_c + L_c + future_claim(V_c) - C_c
>
P_d * G_d - D_d * S_d - F
```

This sensitivity map treats each term as a pressure point:

| term | sensitivity question | safe local lever to inspect | review boundary |
|---|---|---|---|
| `R_c` | Does visible recognition make good-faith work worth doing? | Better rationale, attribution, artifact links, and synthesis notes. | Do not convert recognition into rank, reward, or governance authority. |
| `L_c` | Does participation feel legitimate even when the outcome is adverse? | Contestability markers, loss notes, and visible reasoning. | Do not adopt rights, appeals, or dispute policy here. |
| `future_claim(V_c)` | Does preserving possible future relevance help without implying debt? | Non-promissory retained-record language and explicit no-reward notes. | Do not create payout, ownership, token, or retained-value rights. |
| `C_c` | Is useful contribution too costly for newcomers or high-effort contributors? | Templates, clearer live questions, examples, and batch routing. | Do not lower quality gates into acceptance guarantees. |
| `P_d` | How likely is gaming or capture to succeed? | Evidence minimums, duplicate/dependency links, and review traceability. | Do not create surveillance or identity policy here. |
| `G_d` | How much can an actor gain by gaming visibility, priority, score, or future reward ambiguity? | No-reward boundary, class-sensitive review, and score-as-rationale framing. | Do not define real reward value or score conversion. |
| `D_d` | How likely is defection detected? | Source trails, AI disclosure prompts, conflict visibility, and rationale checks. | Do not adopt disclosure, sanction, or reviewer-authority rules here. |
| `S_d` | What happens if manipulation is detected? | Existing review states such as `needs_revision`, `not_accepted`, or `adversarial`. | Do not define sanctions or exclusion policy here. |
| `F` | Does bad-faith action carry future trust cost? | Durable records, public rationale, contestability, and reviewer memory. | Do not create shaming, legal meaning, or permanent exclusion. |

## Threshold Cases

The cases below ask what must change for collaboration to become more attractive. They are not measurements.

| id | pressure case | likely fragile term | threshold question | local repair candidate | governance-sensitive edge |
|---|---|---|---|---|---|
| T5-SM-01 | Newcomer tries a first maintenance or terminology contribution. | `C_c`, `L_c` | Can the contributor understand the next useful action without private context? | Add clearer examples, tighter templates, or first-task routing. | Do not promise acceptance or special review treatment. |
| T5-SM-02 | Prior-art contributor narrows project novelty instead of flattering it. | `R_c`, `L_c`, `D_d` | Is truth-seeking recognized when it weakens an overbroad claim? | Preserve caveats, source trails, and mechanism-level comparison. | Do not make a novelty verdict or claim-status move. |
| T5-SM-03 | Formalization contributor submits a high-effort model with uncertain assumptions. | `C_c`, `future_claim(V_c)` | Is partial value preserved when the model needs revision? | Use loss notes and revision routes to retain useful residue. | Do not convert retained residue into entitlement or reward claim. |
| T5-SM-04 | Volume optimizer splits one idea into many visible submissions. | `P_d`, `G_d` | Does volume create enough visibility or future-value ambiguity to dominate quality? | Batch related submissions and link duplicates/dependencies. | Do not create a new priority or sanction rule here. |
| T5-SM-05 | AI-assisted contributor submits useful synthesis with disclosure. | `D_d`, `C_c`, `R_c` | Can disclosed assistance lower contribution cost without hiding review responsibility? | Preserve source trails, reviewer rationale, and AI-use notes. | Do not alter AI policy or give AI final authority. |
| T5-SM-06 | Hidden AI volume actor submits plausible but shallow text. | `P_d`, `G_d`, `D_d` | Is shallow plausibility cheaper than careful evidence? | Require source-grounded relevance and uncertainty markers. | Do not impose identity or surveillance requirements here. |
| T5-SM-07 | Strategic claimant treats scores or records as future payout debt. | `G_d`, `future_claim(V_c)` | Does ambiguous language make gaming more valuable than collaboration? | Repeat no-reward and non-promissory retained-record boundaries. | Stop before payout, ownership, token, or legal meaning. |
| T5-SM-08 | Sponsored contributor submits relevant work with possible agenda pressure. | `D_d`, `F`, `P_d` | Are conflicts visible enough for review without excluding useful work? | Record conflict questions and evidence needs in review rationale. | Do not adopt disclosure policy or reviewer disqualification rules. |
| T5-SM-09 | Reviewer favors allies or preferred contribution classes. | `F`, `D_d`, `S_d` | Does public rationale make biased review costly enough to resist? | Require reasoned review notes and contestability markers. | Do not create reviewer selection, sanction, or appeal policy. |
| T5-SM-10 | Rejected contributor considers whether to revise, contest, or exit. | `L_c`, `F`, `future_claim(V_c)` | Does an adverse decision preserve enough visible legitimacy to keep good-faith engagement possible? | Keep rationale, loss notes, and revision path visible. | Do not adopt participant rights or appeal guarantees here. |

## Variable Interaction Notes

Several threshold cases depend on paired variables rather than one lever:

- Lowering `C_c` without raising `D_d` can make useful contribution easier, but it can also make low-effort volume cheaper.
- Raising `R_c` without a no-reward boundary can increase `G_d` by making recognition look like a future payout proxy.
- Preserving `future_claim(V_c)` can help high-effort contributors tolerate uncertainty, but vague retained-value language can also strengthen strategic claiming.
- Increasing `L_c` after adverse decisions depends on visible rationale and contestability, not on making every contributor happy.
- Raising `F` through durable public records can deter bad-faith behavior, but it should not become shaming or permanent exclusion.
- Increasing `D_d` through evidence trails is safer than increasing `S_d` through sanctions before governance is ready.

## Local Repair Versus Governance Review

Safe local modeling can ask:

- Which term is most fragile in a synthetic case?
- Which current repo surface could make that term more visible?
- Which review field, rationale note, source trail, or example would reduce ambiguity?
- Which assumptions remain unknowable before real contribution traces?

Stop for Joe or governance review before:

- adopting reward logic, payout formulas, retained-value rights, score conversion, or legal/financial meaning;
- changing contribution standards, review states, disclosure obligations, sanctions, appeal paths, reviewer authority, governance rules, or participant rights;
- moving claim status or marking T5 passed;
- treating synthetic cases as evidence about real contributors;
- or taking any non-GitHub external action.

## Candidate Later Review

A later T5 review can use this map to ask:

1. Which threshold cases are already covered by contribution standards, review states, or existing synthetic traces?
2. Which cases require new examples before the payoff condition is understandable without private context?
3. Which local repairs would lower contribution cost without increasing gaming?
4. Which reward or retained-value phrases should be rewritten before a real pilot?
5. Which variables can be inspected in Phase 2, and which should wait for Phase 3 real contribution traces?

Until then, this scaffold only clarifies review pressure. It does not strengthen C4, mark T5 passed, adopt reward logic, or change active contribution governance.
