---
artifact_type: t5_no_reward_payoff_bridge
status: synthetic_modeling_scaffold
created: 2026-07-07
test_target: T5 toy payoff model
research_targets:
  - RQ9 reward logic
claim_targets:
  - C4
  - C5
governance_role: review_prep_only
constitutional: false
---

# T5 No-Reward Payoff Bridge

Status: synthetic modeling scaffold, not adopted reward logic.

Purpose: connect the T5 collaboration/defection payoff variables to the RQ9
no-reward baseline so later review can see what remains inspectable when the
system has visible records, rationale, loss notes, and contestability markers
but no payout, score conversion, retained-value right, governance weight,
review priority, legal/financial meaning, or public reward posture.

This file does not change the payoff model, adopt reward logic, assign value to
any contribution, define a payout formula, create retained-value rights,
convert scores, change contribution standards, change review states, change
governance, change claim status, change public posture, mark T5 or RQ9 passed,
or decide any real contribution record.

## Source Surfaces Used

- `TESTS.md`, especially T5, T10, T11, and the RQ9 supporting artifacts.
- `RESEARCH-AGENDA.md`, especially RQ9 reward logic.
- `CONTRIBUTION-STANDARDS.md`, especially score boundaries and review states.
- `projects/toy-payoff-model/2026-07-02-t5-collaboration-defection-payoff-model.md`.
- `projects/toy-payoff-model/2026-07-05-t5-collaboration-threshold-sensitivity-map.md`.
- `projects/toy-payoff-model/2026-07-06-t5-payoff-variable-traceability-map.md`.
- `projects/reward-readiness/2026-07-07-rq9-no-reward-baseline-inspection.md`.
- `projects/prototype-workflow/2026-07-07-rq5-hypothetical-first-pilot-packet.md`.

## Boundary Under Review

The current T5 condition is:

```text
Collaborate is preferred when:

R_c + L_c + future_claim(V_c) - C_c
>
P_d * G_d - D_d * S_d - F
```

The no-reward baseline does not make the collaboration side empty. It narrows
what the collaboration side is allowed to mean.

Under this baseline, `R_c` can mean current recognition and review value,
`L_c` can mean visible legitimacy from a traceable process, and
`future_claim(V_c)` can mean only non-promissory preserved residue for later
review. It cannot mean payout, ownership, token credit, score conversion,
governance standing, priority, legal/financial claim, or automatic future
acceptance.

The bridge question is:

```text
Can a later reviewer inspect collaboration incentives without importing reward
meaning into the record?
```

## No-Reward Term Reading

| term | no-reward reading | visible evidence needed | failure mode | stop boundary |
|---|---|---|---|---|
| `R_c` | Current recognition or review value from a visible record. | Attribution, artifact link, review rationale, contribution class, and useful-residue note. | Recognition becomes a shadow balance, rank, payout proxy, or governance signal. | Do not convert recognition into reward, priority, retained value, or authority. |
| `L_c` | Legitimacy benefit from being reviewed through an inspectable process. | Public rationale, review state, contestable point, bounded-authority note, and source trail. | Contributor must trust private founder judgment or hidden reviewer discretion. | Do not adopt rights, appeal rules, response-time promises, or reviewer authority here. |
| `future_claim(V_c)` | Non-promissory preservation that something may be useful to review later. | Loss notes, retained-record language, explicit no-current-reward boundary, and unresolved-evidence note. | Residue reads like debt, entitlement, ownership, payout eligibility, or automatic future acceptance. | Stop before retained-value rights, score conversion, payout, legal meaning, or financial meaning. |
| `C_c` | Cost of producing useful work under public docs and evidence requirements. | Submission burden, required sources, revision route, and private-context dependency check. | Contribution cost is hidden, so non-reward participation becomes extractive. | Do not lower quality gates into acceptance guarantees or special treatment. |
| `P_d` | Chance that gaming, capture, or extraction succeeds despite no reward. | Evidence minimums, duplicate/dependency links, AI-use notes, conflict prompts, and review timing. | No-reward status is treated as enough protection against manipulation. | Do not create surveillance, identity rules, or disclosure obligations here. |
| `G_d` | Benefit from gaming visibility, priority, narrative control, score ambiguity, or future-reward ambiguity. | Which benefit the actor could extract from the visible record. | The record leaves speculative future value undefined enough to attract strategic claiming. | Do not define real reward value, priority, governance weight, or public reward posture. |
| `D_d` | Chance that manipulation is detected from public evidence. | Missing sources, shallow comparison, hidden AI dependence, duplicate pattern, conflict signal, or rationale mismatch. | Detection depends on private intuition rather than an inspectable signal. | Do not adopt sanctions, disclosure rules, identity rules, or reviewer powers here. |
| `S_d` | Existing review response if manipulation is visible. | Current review states such as `needs_revision`, `not_accepted`, or `adversarial`, plus rationale. | The response either punishes without process or cannot name why the record failed. | Do not define sanctions, exclusion policy, or punishment here. |
| `F` | Future trust or access cost created by a durable, reasoned record. | Public rationale, contestability marker, future review memory, and correction path. | The record erases bad-faith evidence or creates permanent stigma without process. | Do not create shaming, legal meaning, permanent exclusion, or participant-rights policy. |

## Baseline Pressure Bridge

| no-reward pressure | payoff variables exposed | inspectable local question | safe local repair | blocked next action |
|---|---|---|---|---|
| Recognition sufficiency | `R_c`, `L_c`, `C_c` | Does the record make useful work visible enough without implying payment? | Improve rationale specificity, artifact links, and contribution-class notes. | Do not create rank, points, payout, or priority meaning. |
| High-effort residue | `C_c`, `future_claim(V_c)`, `F` | Can partial value survive a revision or rejection without becoming deferred compensation? | Use loss notes and non-promissory retained-record language. | Do not create entitlement, ownership, retained-value rights, or future acceptance. |
| Contestability | `L_c`, `S_d`, `F` | Can a disputed point be named without adopting an appeal system? | Preserve contestable point, rationale, and correction route. | Do not adopt appeal rights, dispute process, reviewer authority, or timelines. |
| Score ambiguity | `G_d`, `future_claim(V_c)`, `R_c` | Could a score or rubric note be read as a balance or allocation signal? | Restate score-as-rationale and no-current-reward boundaries. | Do not convert scores to rewards, shares, weights, or governance standing. |
| Strategic claiming | `G_d`, `P_d`, `D_d` | Does vague future-value language make speculative claims attractive? | Pair residue notes with explicit no-current-reward and unresolved-review language. | Do not promise that current records will or will not count later. |
| Capture risk | `P_d`, `G_d`, `D_d`, `F` | Does no-reward status reduce capture, or does it hide attention and agenda capture? | Name visibility, priority, and narrative-control benefits in review notes. | Do not adopt disclosure, sanction, monitoring, or governance mitigation policy here. |
| Exit pressure | `L_c`, `future_claim(V_c)`, `F` | Can a contributor leave while the public record still preserves useful residue? | Keep record-retention and loss-note language visible. | Do not create participant-rights, erasure, privacy, or retained-value policy. |

## Synthetic First-Pilot Packet Reading

The RQ5 hypothetical first-pilot packet gives one safe object for this bridge
because it has no real contributor, live target, live record surface, issue,
pull request, or contribution-log entry.

If that synthetic packet were used as a T5 no-reward screen, the payoff reading
would stay narrow:

| packet element | collaboration-side read | defection-side read | boundary |
|---|---|---|---|
| Source-backed research note | `R_c` depends on visible mechanism comparison, not polish or agreement. | `G_d` rises if a contributor can steer narrative without stable sources. | Do not accept persuasive synthesis without source/inference separation. |
| Synthetic `needs_revision` outcome | `L_c` depends on whether revision rationale and useful residue are visible. | `F` depends on whether a shallow or strategic packet leaves a durable reason. | Do not create appeal rights, punishment, or permanent stigma. |
| Loss notes | `future_claim(V_c)` is only preserved review relevance. | `G_d` rises if loss notes sound like deferred payout or entitlement. | Do not imply reward, retained value, ownership, or automatic future acceptance. |
| No live log entry | `R_c` remains review-prep recognition only. | `P_d * G_d` is lower because no public contribution credit is issued. | Do not create a live `CONTRIB-*` record from synthetic material. |
| Second-ring stop screen | `L_c` improves when protected boundaries are visible. | `D_d` improves when reward, rights, governance, AI, and transfer moves are named as stops. | Do not adopt any second-ring policy through the packet. |

## Minimum No-Reward Payoff Review Packet

A later T5/RQ9 review should not use the payoff model against a live
contribution unless the public record can answer:

1. What visible recognition or review value exists now?
2. What legitimacy benefit survives if the outcome is adverse?
3. What useful residue is preserved, and what promise is explicitly absent?
4. What contribution cost or private-context dependency is visible?
5. What benefit could a strategic actor extract without a reward mechanism?
6. What observable signal would detect that extraction path?
7. What existing review response would apply without creating new sanctions?
8. What future trust cost or correction path remains visible?
9. Which variables are deliberately unknown until real traces exist?
10. Which statement prevents score, loss-note, or retained-record ambiguity
    from becoming reward meaning?

If those answers are missing, the correct result is "no-reward payoff trace not
ready," not a stronger T5, C4, C5, or RQ9 claim.

## Local Repair Versus Review Stop

Safe local research can:

- clarify how recognition differs from reward;
- make loss-note language less promissory;
- name gaming benefits that remain even without payout;
- connect existing synthetic packet fields to payoff variables;
- identify which variables should remain unknown before real contribution
  traces exist;
- and prepare review questions for a later governed T5/RQ9 pass.

Stop for Joe or governed review before:

- adopting reward logic, payout formulas, score conversion, retained-value
  rights, priority, governance weight, or legal/financial meaning;
- changing contribution standards, templates, review states, appeal paths,
  disclosure obligations, sanctions, participant rights, governance, or public
  posture;
- marking T5, RQ9, C4, C5, or any related artifact stronger or complete;
- treating synthetic examples as evidence about real contributors;
- promising that current records will or will not matter in a future reward
  process;
- or taking any non-GitHub external action.

## Later Review Questions

1. Which no-reward variable is most fragile: recognition value, legitimacy
   benefit, non-promissory residue, contribution cost, gaming benefit,
   detection signal, review response, or future trust cost?
2. Which existing synthetic trace is best suited for a first no-reward payoff
   review packet?
3. Which phrases in current artifacts risk implying payout, entitlement,
   retained value, or future acceptance?
4. Which gaming benefits remain even if no payout exists?
5. Which local record repairs should happen before any reward-test packet is
   reviewed?

Until those questions receive governed review, this bridge only prepares the
evidence surface. It does not make collaboration dominate defection, prove the
no-reward baseline legitimate, strengthen C4 or C5, mark T5 or RQ9 passed,
create reward readiness, or change contribution governance.
