---
artifact_type: reward_readiness_boundary_map
status: non_adopted_scaffold
created: 2026-07-03
research_question: RQ9 reward logic
claim_targets:
  - C4
  - C5
governance_role: review_prep_only
constitutional: false
---

# RQ9 Reward-Readiness Boundary Map

Status: draft boundary map, not adopted reward logic.

Purpose: make RQ9 reviewable by separating reward alternatives, readiness gates, no-reward baseline, retained-value ambiguity, and capture risks before the repo changes active scoring, contribution standards, reward meaning, governance rules, claim status, public posture, or any real contribution record.

This file does not create a reward mechanism, payout formula, token design, retained-value right, governance-weight rule, legal or financial claim, contributor entitlement, claim-status decision, or active contribution-review rule. It is a bounded research scaffold for later review.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ9
- `ROADMAP.md`, especially Phase 2 and Phase 3
- `CLAIMS.md`, especially C4 and C5
- `LEGITIMACY-SCHEMA.md`, especially visibility, contestability, exit with retained record, bounded authority, and non-capture
- `PROTOCOL-STACK.md`, especially Layers 4, 6, 7, 8, 9, and 10
- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`, especially open attemptability, value rubric, and review states
- `THREAT-MODEL.md`, especially reward gaming and economic capture
- `TESTS.md`, especially T2, T5, T6, T10, and T11
- `projects/toy-payoff-model/2026-07-02-t5-collaboration-defection-payoff-model.md`
- `projects/value-rubric-options/2026-07-02-rq3-value-rubric-options.md`
- `projects/participant-rights/2026-07-03-rq7-voice-exit-retained-value-boundary-map.md`
- `projects/attack-profitability/2026-07-03-rq8-attack-profitability-variable-map.md`

## Boundary Under Review

RQ9 asks what reward mechanism could be tested without pretending the full governance problem is solved. The dangerous move is converting early contribution records, scores, retained-value language, or legitimacy benefits into reward promises before the repo has enough evidence.

This scaffold separates eight design objects that should not be collapsed:

1. **Recognition:** visible credit, rationale, and public record.
2. **Contribution score:** early value discussion, not payout math.
3. **Retained record:** durable attribution and loss notes, not ownership.
4. **Retained-value marker:** possible future relevance, not entitlement.
5. **Reward hypothesis:** a mechanism to study, not adopt.
6. **Reward-readiness gate:** evidence needed before testing a mechanism.
7. **Governance authority:** who can authorize or revise rewards.
8. **Legal or financial meaning:** outside this scaffold unless explicitly reviewed.

## Reward Alternative Inventory

| alternative | what it might test | earliest evidence needed | capture or legitimacy risk | boundary for now |
|---|---|---|---|---|
| No-reward baseline | Whether recognition, rationale, and retained records are enough for early good-faith contribution. | One or more contribution traces with visible value notes and loss notes. | Contributors may see extraction if high-value work receives only thanks. | Keep as a baseline, not a permanent anti-reward decision. |
| Symbolic credit | Whether public recognition improves collaboration without creating payout expectations. | Clear contribution classes, stable artifact links, and review rationale. | Credit can become status capture or founder-controlled prestige. | Do not convert credit to rank, payout, or governance authority. |
| Review priority or process influence | Whether useful contributors should receive faster routing or stronger voice. | Evidence that repeated useful work predicts better review quality. | Can become insider advantage and weaken open attemptability. | Do not grant priority, voting, veto, or reviewer authority here. |
| Retroactive reward pool | Whether later resources can reward earlier accepted value. | Contribution log quality, score rationale, dispute handling, and capture review. | Ambiguous records can create payout conflict and strategic early claiming. | Do not promise a pool, formula, or conversion rate. |
| Token-like issuance | Whether portable or programmable rewards help align collaboration. | Much stronger attack-profitability, governance, identity, and legal review. | Intensifies sybil behavior, speculation, and capture incentives. | Treat as a distant research object, not an implementation path. |
| Revenue-linked distribution | Whether future project revenue could map to accepted contribution value. | Revenue source, ownership structure, accounting method, and governance authorization. | Creates legal, tax, and ownership meaning outside this repo's current authority. | Do not define shares, claims, obligations, or financial terms. |
| Governance weight | Whether contribution history should affect rule-making power. | Founder-power limits, reviewer selection, appeal path, and capture safeguards. | Rewards can become rule-control, locking early contributors into dominance. | Do not attach governance power to contribution records. |

## Readiness Gates

| gate | minimum question before reward testing | evidence to inspect | stop condition |
|---|---|---|---|
| Contribution record integrity | Can future readers reconstruct what was submitted, accepted, narrowed, or deferred? | Log schema, artifact links, review state, rationale, and loss notes. | Stop if records depend on private founder memory. |
| Value-rubric stability | Can reviewers explain value without treating scores as payout shares? | RQ3 options, T2 dry run, score rationale, and disagreement notes. | Stop if scores are read as automatic reward or retained claim. |
| Contestability | Can a contributor challenge a classification or value judgment without coercion? | Dispute notes, contested-state examples, and reviewer response minimums. | Stop if reward review requires an appeal policy the repo has not adopted. |
| Attack-profitability | Which attacks become more profitable once rewards are expected? | T6 attack surface, RQ8 variables, conflict visibility, and volume-gaming scenarios. | Stop if a mechanism increases `B_a` or `P_a` without detection or mitigation evidence. |
| Retained-value language | Can the repo preserve possible future relevance without promising payout? | RQ7 retained-value marker options and T5 strategic claimant scenario. | Stop if marker language implies ownership, payout, token rights, or governance standing. |
| Governance authority | Who can authorize reward experiments, revise them, and resolve disputes? | Founder-power review, transition constraints, and current governance rules. | Stop if reward adoption would silently change founder powers or reviewer authority. |
| Participation pressure | Would rewards make contribution feel coerced, extractive, or status-dependent? | Legitimacy feedback, exit scenarios, and adverse-decision traces. | Stop if contributors must stay engaged to preserve accepted value. |
| External meaning | Would the mechanism create legal, financial, tax, employment, securities, or IP consequences? | Explicit professional review if Joe authorizes that path later. | Stop immediately; this scaffold cannot create those meanings. |

## No-Reward Baseline

The no-reward baseline is not "no rewards ever." It is the control condition for early research.

It asks whether the repo can currently provide:

- visible contribution credit,
- clear review rationale,
- useful loss notes,
- contestable decisions,
- retained public records,
- and enough legitimacy benefit that early contributors are not relying on speculative payout.

Failure signals:

- contributors need private assurances to trust the process;
- high-value work is accepted but later hard to find or credit;
- adverse decisions erase useful residue;
- score language sounds like a future payout formula;
- or contributors treat retained-value notes as debt.

## Reward Leakage Failure Modes

| failure mode | early warning | possible mitigation to test |
|---|---|---|
| Score-to-payout conversion | Review scores are discussed as shares, points, or earned balances. | Keep scores as rationale aids until a separate reward review authorizes conversion. |
| Shadow token | Retained-value markers start functioning as tradeable or transferable claims. | Use non-promissory record language and prohibit transfer meaning unless reviewed. |
| Early-contributor lock-in | Founding contributors gain permanent advantage from sparse early records. | Require later normalization, dispute windows, and capture checks before any conversion. |
| Reward-first contribution | Contributors optimize for visible metrics rather than truth-seeking or legitimacy. | Use class-sensitive review and capture-resistance notes before reward discussion. |
| Founder allocation opacity | Founder judgment becomes the hidden reward allocator. | Require visible authority boundaries and documented rationale before any reward experiment. |
| Governance capture by reward | Reward recipients gain rule-making power that protects their own advantage. | Separate contribution value from governance authority unless a later governance review adopts the link. |
| Legal or financial ambiguity | Language implies ownership, employment, revenue share, securities, or tax meaning. | Stop for explicit Joe and professional review; do not infer from repo records. |

## Candidate Review Packet Shape

```text
RQ9 review packet
  1. No-reward baseline check
  2. Reward alternative inventory
  3. Contribution-record and value-rubric readiness
  4. Retained-value language audit
  5. Attack-profitability delta
  6. Governance authority boundary
  7. Legal/financial stop-condition screen
  8. Joe/governance adoption questions
```

## Later Adoption Boundary

This scaffold can support later RQ9 review when the repo has:

- at least one real or further synthetic contribution trace with visible review rationale;
- contribution-log records that preserve value, loss, and uncertainty without payout language;
- evidence that value scores remain discussion aids rather than reward shares;
- an RQ8-style attack-profitability check for each candidate mechanism;
- a governance-authority answer for who may authorize, revise, pause, or reverse a reward experiment;
- and explicit review of any external legal, financial, tax, ownership, IP, employment, or securities implications before those meanings are created.

Until that later review happens, this scaffold does not adopt reward logic, choose a reward mechanism, create reward readiness, attach retained-value rights, define payout formulas, grant governance weight, change contribution scoring, alter rights policy, move claim status, change public posture, or decide any real contribution record.

## Stop Conditions

Stop and require Joe/governance review before:

- editing `CONTRIBUTING.md`, `CONTRIBUTION-STANDARDS.md`, `GOVERNANCE.md`, `GUARDRAILS.md`, `CLAIMS.md`, public posture, issue templates, live review policy, contribution-log policy, retained-value policy, or reward language based on this scaffold;
- adopting any reward mechanism, reward-readiness criterion, payout formula, retained-value marker, governance weight, priority rule, score conversion, sanction, disclosure requirement, or appeal path;
- treating a contribution score, review state, contribution log entry, loss note, or retained record as legal, financial, token, ownership, governance, employment, or reward entitlement;
- assigning economic value to any real or synthetic contribution;
- marking C4 or C5 stronger, moving claim status, or claiming collaboration dominance;
- adding or changing a real contribution record;
- or publishing this scaffold as active reward policy rather than draft research.
