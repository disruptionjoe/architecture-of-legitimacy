---
artifact_type: contribution_taxonomy_review_path_scaffold
status: draft_mapping_scaffold
created: 2026-07-02
research_target: RQ2 contribution taxonomy
governance_role: internal_research_scaffold
constitutional: false
---

# RQ2 Contribution Taxonomy Review-Path Map

Status: draft mapping scaffold, not adopted policy.

Purpose: make the current contribution classes easier to route during first-pass review without changing the active classes, review states, reviewer authority, governance mode, reward meaning, or any real contribution record.

This file is not a contribution-standard update, governance decision, appeal rule, reward rule, claim-status decision, public-posture change, or live contribution decision. It is a bounded research scaffold for comparing contribution classes against candidate review paths.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ2
- `ROADMAP.md`, especially Phase 1 and Phase 3
- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `templates/contribution-proposal.md`
- `templates/contribution-log-schema.md`
- `projects/contribution-taxonomy/2026-07-01-t1-contribution-taxonomy-fixture.md`
- `projects/contribution-eligibility/2026-07-02-rq1-contribution-eligibility-options.md`
- `projects/review-cadence-options/2026-07-02-rq4-review-cadence-options.md`

## Boundary Under Review

RQ2 asks which contribution types should be recognized separately. The current repo already names seven contribution classes:

- `research`
- `formalization`
- `protocol design`
- `review`
- `synthesis`
- `implementation`
- `maintenance`

The open problem is not whether these labels exist. The open problem is whether a reviewer can map a submission from class to review path without relying on private founder context.

This scaffold separates four things that should not be collapsed:

1. contribution class,
2. intake evidence,
3. review lane,
4. review state.

## Candidate Class-To-Review-Path Map

| contribution class | contribution shape | candidate intake evidence | candidate review lane | likely first-pass states | ambiguity check |
|---|---|---|---|---|---|
| `research` | Prior art, literature context, source-backed comparison, or practice review. | Stable source, mechanism-level relevance, source limits, target claim/test/question. | `substantive_research_review`. | `triaged` or `needs_revision`. | A link list is not enough; the submission must explain why the source matters. |
| `formalization` | Definitions, variables, models, tests, or failure conditions. | Defined variables, assumptions, worked example or test path, named limits. | `substantive_research_review` with formalization focus. | `triaged` or `needs_revision`. | A confident assertion is not formalization unless it becomes testable. |
| `protocol design` | Rules, workflows, roles, rights, phase transitions, or review procedures. | Affected protocol layer, who gains/loses, capture-risk note, adoption boundary. | `protocol_design_review`; governance-sensitive items stop for later review. | `triaged`, `needs_revision`, or deferred as governance-sensitive. | Workflow proposals become governance proposals when they alter authority, rights, appeal, reward, or transfer. |
| `review` | Error finding, overclaim reduction, attack-path critique, rubric critique, or legitimacy failure diagnosis. | Targeted claim/surface, failure mode, evidence or reasoning, possible mitigation or open question. | `substantive_research_review` or threat/legitimacy review. | `triaged` or `needs_revision`. | A dislike response is not review unless it gives actionable reasoning. |
| `synthesis` | Integration of multiple repo surfaces into clearer project state. | Source list, preserved meanings, changed structure, unresolved tensions. | `monthly_synthesis` or synthesis review. | `triaged` or `needs_revision`. | Rephrasing is not synthesis unless it improves state, accuracy, or future review. |
| `implementation` | Tools, templates, automation, validation scripts, or workflow support. | Supported workflow, validation behavior, false-positive risk, limits on authority. | `implementation_review` or maintenance review when non-substantive. | `triaged` or `needs_revision`. | Tooling may assist review but must not become final legitimacy judgment. |
| `maintenance` | Link fixes, terminology alignment, formatting cleanup, schema-aligned upkeep. | Affected paths, validation performed, statement that meaning was not changed. | `maintenance_review`. | `accepted` for plainly non-substantive fixes, otherwise `triaged`. | Cleanup becomes policy work if it changes research meaning, contribution rights, or governance. |

## Candidate Routing Rules

These rules are draft review aids, not active policy:

- Classify the primary contribution first, then record secondary classes only when they explain a real ambiguity.
- Treat `triaged` as a routing state, not acceptance.
- Route missing source packets, unclear targets, or thin failure modes to `needs_revision` before treating the work as not useful.
- Stop protocol-design work that changes authority, rights, appeal, reward, retained-value meaning, public posture, or governance transition.
- Preserve useful residue through `loss_notes` when a submission is narrowed, revised, or not accepted as-is.
- Keep maintenance review narrow: validate the cleanup and confirm it does not change policy or research meaning.

## Synthetic Review-State Examples

These examples are invented review-path probes. They are not contribution records and do not use the live `CONTRIB-NNNN` namespace.

| example id | class under test | submission shape | candidate first state | rationale check |
|---|---|---|---|---|
| RQ2-MAP-01 | `research` | Compares the project to one public-goods funding system with stable sources, mechanism comparison, and limits. | `triaged` | Enough evidence exists for substantive review, but acceptance still requires review. |
| RQ2-MAP-02 | `research` | Provides ten links with no explanation of relevance. | `needs_revision` | The source packet is present but not reviewable without mechanism-level notes. |
| RQ2-MAP-03 | `formalization` | Defines attack-profitability variables and gives two worked scenarios. | `triaged` | The contribution is testable enough for model review. |
| RQ2-MAP-04 | `protocol design` | Proposes immediate contributor voting power over roadmap decisions. | `needs_revision` or governance-sensitive defer | The value may be reviewable, but authority transfer cannot move through ordinary review. |
| RQ2-MAP-05 | `review` | Shows how a value rubric can be gamed by splitting work into many small submissions. | `triaged` | The critique names an affected mechanism and failure path. |
| RQ2-MAP-06 | `implementation` | Adds a checker for missing contribution-log fields and reports false-positive limits. | `triaged` | Tooling supports review but does not decide legitimacy. |
| RQ2-MAP-07 | `maintenance` | Fixes broken internal links and confirms no semantic changes. | `accepted` or `triaged` | Plain cleanup can be accepted quickly only when the non-substantive boundary is visible. |
| RQ2-MAP-08 | none | Submits fabricated citations or plagiarized text. | `adversarial` | The problem is conduct and evidence integrity, not contribution class. |

## Stop Conditions By Class

| trigger | normal disposition |
|---|---|
| The submission changes founder powers, transition triggers, appeal rights, reviewer authority, participant rights, reward logic, retained-value meaning, or public posture. | Stop ordinary review and route to future Joe/governance review. |
| The submission lacks a target claim, test, document, or research question. | `needs_revision` unless the missing target reflects bad-faith volume or spam. |
| Research or prior-art work lacks stable sources, relevance notes, mechanism comparison, or limits. | `needs_revision`; do not reject useful source leads merely because they are incomplete. |
| Maintenance changes alter source meaning or policy. | Reclassify as synthesis, protocol design, or governance-sensitive work before review continues. |
| Implementation claims to automate final judgment or legitimacy. | Stop or revise; tooling may support review but cannot supply legitimacy. |
| The submission contains fabricated evidence, plagiarism, harassment, coercion, or flooding. | `adversarial` or `not_accepted` depending on severity and local review judgment. |

## Adoption Questions For Later Review

- Should the project add an explicit `review_lane` field to proposal or log templates?
- Should `maintenance` be the only class eligible for fast acceptance before the first real contribution pilot?
- Which protocol-design proposals must always stop for Joe/governance review?
- How should reviewers record secondary classes without making classification too complex?
- Should synthetic examples become a reusable reviewer exercise before any public call for contributions?
- What evidence would justify changing the active contribution classes rather than only adding review guidance?

## Later Review Criteria

This scaffold can support a stronger RQ2 result when:

- reviewers can map most synthetic submissions to a primary class and first review state without private founder context;
- class ambiguity produces specific rationale rather than general uncertainty;
- governance-sensitive protocol proposals stop visibly instead of slipping through ordinary review;
- maintenance and synthesis remain distinct enough to prevent hidden policy movement;
- and the proposal/log templates can preserve routing rationale without becoming too burdensome for contributors.

This scaffold does not adopt any review path. It gives the repo a compact object for comparing taxonomy routing before real contributors depend on it.
