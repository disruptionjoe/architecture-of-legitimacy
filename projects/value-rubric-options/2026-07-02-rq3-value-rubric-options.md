---
artifact_type: value_rubric_options_scaffold
status: draft_options_scaffold
created: 2026-07-02
research_target: RQ3 initial value rubrics
governance_role: internal_research_scaffold
constitutional: false
---

# RQ3 Initial Value-Rubric Options Scaffold

Status: draft options scaffold, not adopted rubric policy.

Purpose: make the initial value-rubric question reviewable before the project changes its active scoring dimensions, score meanings, reviewer authority, reward meaning, governance mode, claim status, public posture, or any real contribution record.

This file is not a contribution-standard update, reward rule, reviewer-authority rule, governance decision, claim-status decision, public-posture change, or live contribution decision. It is a bounded research scaffold for comparing value-rubric shapes against early legitimacy, capture, and contributor-usability concerns.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ3
- `ROADMAP.md`, especially Phase 1 and Phase 2
- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `CLAIMS.md`, especially C2, C3, and C5
- `LEGITIMACY-SCHEMA.md`
- `PROTOCOL-STACK.md`, especially Layer 4
- `THREAT-MODEL.md`, especially rubric gaming and epistemic capture
- `TESTS.md`, especially T2
- `projects/value-rubric-dry-run/2026-07-02-t2-value-rubric-dry-run.md`
- `projects/contribution-taxonomy/2026-07-02-rq2-review-path-map.md`

## Boundary Under Review

RQ3 asks how value should be judged before the system has much data or legitimacy.

The repo already contains a provisional seven-dimension rubric in `CONTRIBUTION-STANDARDS.md`:

- `clarity`
- `rigor`
- `relevance`
- `novelty`
- `legitimacy`
- `capture resistance`
- `coordination value`

The open problem is not whether these labels can be used today. The open problem is which rubric shape makes early disagreements visible without pretending that scores are reward entitlements, governance authority, or final truth.

This scaffold separates five things that should not be collapsed:

1. reviewability,
2. value judgment,
3. acceptance state,
4. reward or retained-value meaning,
5. governance authority.

## Candidate Rubric Shapes

| option | shape | best early use | what it should reveal | failure mode | later adoption question |
|---|---|---|---|---|---|
| A | Keep the current seven dimensions as a discussion rubric. | First external contribution reviews where simplicity matters. | Whether reviewers can explain useful disagreements with the existing terms. | Scores may look more precise than the evidence supports. | Are the seven dimensions distinct enough after several reviews? |
| B | Add a reviewability gate before value scoring. | Submissions with missing evidence, unclear target, or possible policy boundary. | Whether a contribution is evaluable before anyone argues about value. | The gate may become hidden founder discretion if reasons are not visible. | Which missing fields should route to `needs_revision` rather than low scores? |
| C | Use class-sensitive prompts with shared legitimacy and capture checks. | Comparing research, maintenance, protocol design, and synthesis without one class dominating. | Which dimensions matter differently by contribution class. | Class-specific prompts may become too complex for newcomers. | Which prompts are common to all classes, and which are class-specific? |
| D | Split `rigor` into evidence quality and formal/test precision. | Prior-art, model, and failure-mode contributions. | Whether source-backed research and formalization are being judged on different evidence. | The rubric may overfit to technical work and undervalue synthesis or maintenance. | Does splitting rigor make review clearer or merely longer? |
| E | Record a score vector plus one decisive positive reason, one decisive concern, and one loss note. | Early reviews where preservation of useful residue matters. | Whether the reviewer can explain both value and rejected/deferred material. | Review notes may become burdensome if every minor cleanup needs a full record. | Which contribution classes need full rationale versus lightweight validation? |

## Failure-Mode Matrix

| failure mode | pressure point | early warning | possible test or mitigation |
|---|---|---|---|
| False precision | Numeric scores imply measurement quality the repo does not have. | Reviewers debate decimals or totals instead of reasons. | Use coarse `0-3` scores only with rationale text and disagreement notes. |
| Popularity scoring | Work that sounds exciting scores higher than work that reduces error. | Novelty dominates clarity, rigor, and capture resistance. | Compare scores against truth-seeking and overclaim-reduction examples. |
| Maintenance undervaluation | Cleanup and alignment work looks low value because it is not novel. | Useful non-substantive fixes receive near-zero vectors. | Keep `coordination value` and `clarity` visible for maintenance work. |
| Governance-sensitive overreach | A high-value proposal is mistaken for permission to adopt a rule. | Protocol-design work receives high scores and moves directly into policy. | Require a separate adoption boundary for authority, appeal, rights, reward, and governance changes. |
| Capture-resistance collapse | Legitimacy and capture concerns are treated as general vibes. | Reviewers cannot distinguish fairness, contestability, and attack profitability. | Ask for one legitimacy trace concern and one attack/capture concern when relevant. |
| Source-packet weakness | Research contributions are scored before evidence is reviewable. | Link lists or unsourced comparisons receive relevance credit. | Use the research-class evidence minimum before value scoring. |
| Reward leakage | Scores are interpreted as retained-value or financial claims. | Contributors or reviewers treat score totals as payout shares. | Keep score records explicitly non-reward-bearing until reward readiness is separately designed. |
| Founder-context dependency | A contribution scores well only because the founder knows why it matters. | Public artifacts cannot reconstruct the rationale. | Require target, evidence, rationale, and loss notes sufficient for future readers. |
| AI score laundering | Generated analysis gives a score vector that masks missing human judgment. | AI-generated confidence substitutes for reviewer reasons. | Require human-labeled judgment and contestable rationale for any AI-assisted review. |

## Contribution-Class Stress Points

| contribution class | value question | likely weak spot | review note to preserve |
|---|---|---|---|
| `research` | Does the source-backed comparison improve a live claim, test, or research question? | Relevance without mechanism-level comparison. | Source limits and what the project should not infer. |
| `formalization` | Does the model, variable, or definition make a claim more testable? | Formal language without usable assumptions. | Which assumption must be supplied before the work can guide decisions. |
| `protocol design` | Does the rule or workflow make review more legitimate without increasing capture risk? | High coordination value with hidden authority movement. | Which adoption boundary the proposal would cross. |
| `review` | Does the critique expose error, overclaim, attack path, or failure mode? | Negative reaction without actionable diagnosis. | The concrete failure mode and possible mitigation or open question. |
| `synthesis` | Does integration make project state clearer without erasing unresolved tension? | Smooth prose that hides disagreement or changes meaning. | Which source meanings were preserved and which tensions remain. |
| `implementation` | Does the tool or template improve inspectability without replacing judgment? | Automation becoming an opaque reviewer. | False-positive limits and human review boundary. |
| `maintenance` | Does cleanup make future contribution or review easier without changing meaning? | Low novelty hiding real coordination value. | Validation performed and statement that research meaning was not changed. |

## Candidate RQ3 Review Questions

1. Should the active rubric remain a single cross-class vector, or should it become class-sensitive?
2. Should reviewability be checked before value scoring?
3. Which dimensions are most likely to collapse into each other during real review?
4. Which dimensions are easiest to game through volume, social pressure, or AI-generated polish?
5. What rationale minimum is light enough for maintenance but strong enough for substantive research?
6. When should a high-value but governance-sensitive contribution be preserved without adopting the requested rule?
7. What evidence would justify changing the active rubric in `CONTRIBUTION-STANDARDS.md`?

## Later Adoption Boundary

This scaffold can support a later RQ3 review when the repo has:

- at least one real or further synthetic contribution scored with visible rationale;
- evidence that reviewers can distinguish value from acceptance and reward;
- a documented disagreement that reveals whether dimensions are useful or redundant;
- a capture-risk check for score gaming and AI-generated volume;
- and a clear proposal for what would change in active contribution standards.

Until that later review happens, this scaffold does not adopt any rubric option, score aggregation rule, reward mapping, reviewer authority, governance rule, claim-status movement, or contribution decision.
