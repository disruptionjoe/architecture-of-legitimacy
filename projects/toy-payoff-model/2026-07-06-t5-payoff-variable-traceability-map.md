---
artifact_type: t5_payoff_variable_traceability_map
status: synthetic_modeling_scaffold
created: 2026-07-06
test_target: T5 toy payoff model
claim_target: C4
governance_role: internal_review_scaffold
constitutional: false
---

# T5 Payoff Variable Traceability Map

Status: synthetic modeling scaffold.

Purpose: make the T5 collaboration/defection payoff model less speculative by naming what visible trace would be needed before a later reviewer uses each variable in a real contribution case.

This file is not a reward rule, contribution score, payout formula, retained-value promise, governance rule, sanction policy, appeal path, disclosure rule, contributor-rights policy, claim-status decision, public-posture decision, real contribution record, or evidence that T5 has passed.

## Source Surfaces

This scaffold reads the current repo state as evidence:

- `TESTS.md`, especially the T5 payoff condition.
- `CLAIMS.md`, especially the C4 proof burden.
- `PROTOCOL-STACK.md`, especially contribution validation, value rubrics, contribution log, rights, rewards, governance, and capture monitoring.
- `CONTRIBUTION-STANDARDS.md`, especially contribution classes, review states, and the no-automatic-reward boundary for scores.
- `projects/toy-payoff-model/2026-07-02-t5-collaboration-defection-payoff-model.md`.
- `projects/toy-payoff-model/2026-07-05-t5-collaboration-threshold-sensitivity-map.md`.
- `projects/attack-surface-map/2026-07-02-t6-attack-surface-map.md`.
- `projects/attack-profitability/2026-07-03-rq8-attack-profitability-variable-map.md`.
- `projects/prototype-workflow/2026-07-06-rq5-workflow-handoff-gap-map.md`.

## Boundary Under Review

The current T5 condition is useful only if future reviewers can see why a variable was assigned or discussed. Otherwise the model can become private intuition with symbols.

```text
Collaborate is preferred when:

R_c + L_c + future_claim(V_c) - C_c
>
P_d * G_d - D_d * S_d - F
```

This map asks what the repo would need to preserve before using those terms in a real trace. It does not estimate any real contributor, assign values, rank contributions, adopt a reward model, or change C4.

## Variable Traceability Table

| term | trace question | visible evidence to preserve | weak trace warning | review boundary |
|---|---|---|---|---|
| `R_c` | What recognition or review value did collaboration create now? | Review rationale, artifact link, contribution class, value notes, and any synthesis pointer. | Recognition is asserted as "valuable" without saying what changed in repo knowledge. | Do not convert recognition into rank, reward, priority, governance weight, or entitlement. |
| `L_c` | What legitimacy benefit remains for the contributor and later readers? | Public rationale, contestable decision point, bounded-authority note, and visible review state. | The contributor must trust hidden founder judgment or private context. | Do not adopt rights, appeals, response-time promises, or dispute policy here. |
| `future_claim(V_c)` | What future relevance is preserved without creating debt? | Non-promissory retained-record or loss note that says what may matter later and what promise is not created. | Language sounds like payout, ownership, token credit, legal claim, or automatic future acceptance. | Stop before reward, retained-value rights, legal meaning, or financial meaning. |
| `C_c` | What did useful collaboration cost the contributor? | Submission complexity, required evidence, revision burden, source-gathering burden, and whether public docs were enough. | The contribution depended on private guidance or unnecessary process friction. | Do not lower quality gates into acceptance guarantees or special treatment. |
| `P_d` | How likely would gaming, capture, or extraction have succeeded under the visible process? | Evidence minimums applied, duplicate/dependency links, source trails, AI-use notes, conflict prompts, and review timing. | A bad trace cannot show where manipulation would have been caught. | Do not create surveillance, identity rules, disclosure obligations, or reviewer powers here. |
| `G_d` | What could an actor gain by defecting in this surface? | Visibility benefit, priority benefit, score ambiguity, reward ambiguity, agenda control, or governance leverage named in the review. | The trace leaves extractable benefit implicit, especially around scores and future value. | Do not define real reward value, score conversion, payout, priority, or governance meaning. |
| `D_d` | What observable signal would expose defection? | Missing sources, shallow mechanism comparison, undisclosed AI dependence, duplicate submissions, conflict signal, or rationale mismatch. | Detection depends on reviewer intuition rather than an inspectable signal. | Do not adopt disclosure, sanction, identity, or surveillance policy here. |
| `S_d` | What formal review response exists if manipulation is detected? | Existing review state such as `needs_revision`, `not_accepted`, or `adversarial`, plus rationale. | The response is either punitive without evidence or toothless without a state. | Do not define sanctions, exclusion, removal, or punishment policy here. |
| `F` | What future trust, access, or reputation cost would bad-faith action create? | Durable record, public rationale, contestability marker, and connection to future review memory. | The record either erases bad-faith evidence or creates permanent stigma without process. | Do not create shaming, legal meaning, permanent exclusion, or participant-rights rules. |

## Minimum Trace Packet For A Later T5 Review

A later review should not use the payoff model against a real contribution unless the trace can answer these questions from public repo evidence:

1. What contribution class and review state were assigned?
2. What artifact, claim, test, or protocol layer did the contribution affect?
3. What public evidence or reasoning supported the review?
4. What value was recognized now, if any?
5. What value was preserved as a non-promissory future note, if any?
6. What was explicitly not promised by the record?
7. What contribution cost or friction was visible?
8. What gaming or capture path was relevant to the case?
9. What observable signal would detect that path?
10. What review state or rationale would respond to the signal?
11. What contestable point or correction route remained visible?
12. Which variables remained unknowable before more real traces exist?

If those answers are missing, the correct result is usually "T5 trace not ready," not a stronger C4 claim.

## Synthetic Case Coverage

The existing T5 synthetic cases already expose several likely trace gaps:

| pressure family | strongest variable need | traceability implication |
|---|---|---|
| Newcomer and maintenance work | `C_c`, `R_c`, `L_c` | Public docs must show what was attempted, why it was useful, and whether private founder context was needed. |
| Prior-art and research narrowing | `R_c`, `D_d`, `P_d` | Review notes must reward truth-seeking and preserve mechanism-level source comparison. |
| Formalization and synthesis | `C_c`, `future_claim(V_c)`, `F` | High-effort partial value needs loss notes without implying reward or future acceptance. |
| Volume optimization and hidden AI | `P_d`, `G_d`, `D_d` | Duplicate links, source trails, AI-use disclosure, and shallow-evidence warnings must be visible. |
| Strategic claiming | `G_d`, `future_claim(V_c)` | Scores, retained records, and loss notes need explicit no-reward and non-promissory language. |
| Adverse or contested decisions | `L_c`, `F`, `S_d` | Rationale, review state, and contestable point must survive the adverse outcome. |
| Sponsored or conflicted work | `D_d`, `F`, `P_d` | The trace needs conflict visibility without silently adopting disclosure or disqualification policy. |
| Reviewer bias | `D_d`, `F`, `S_d` | Public rationale and contestability should make biased review inspectable before sanctions or new authority exist. |

## Local Repair Versus Review Stop

Safe local modeling can improve:

- trace fields a reviewer should preserve,
- wording that separates recognition from reward,
- examples of visible evidence for a variable,
- links between existing synthetic traces and payoff terms,
- and questions that keep unknown variables explicit.

Stop for Joe or governance review before:

- adopting reward logic, payout formulas, retained-value rights, score conversion, priority, governance weight, or legal/financial meaning;
- changing contribution standards, review states, disclosure obligations, sanctions, appeal paths, reviewer authority, governance rules, participant rights, or public posture;
- marking T5 passed or strengthening C4;
- treating synthetic cases as evidence about real contributors;
- or using the model to decide a real contribution.

## Candidate Later Review

A later T5 review can use this map to ask:

1. Which variables are traceable in current synthetic examples?
2. Which variables need a first real contribution trace before they can be evaluated?
3. Which trace gaps are local workflow problems rather than governance or reward questions?
4. Which wording risks converting recognition or retained records into reward expectations?
5. Which variables should remain deliberately unestimated until Phase 3 pilot evidence exists?

Until then, this scaffold only prepares traceability criteria. It does not change the payoff model, adopt policy, strengthen C4, or make T5 pass.
