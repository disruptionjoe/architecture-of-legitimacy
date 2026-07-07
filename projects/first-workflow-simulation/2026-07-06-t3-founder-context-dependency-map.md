---
artifact_type: workflow_simulation_analysis
status: draft
created: 2026-07-06
test_target: T3 first workflow simulation
research_question: RQ5 prototype workflow
governance_role: non_adopted_dependency_map
constitutional: false
---

# T3 Founder-Context Dependency Map

This map turns the founder-context notes in the T3 newcomer workflow simulation
into inspectable checks for a later first-pilot review. It does not change
active contribution instructions, issue templates, review states, contribution
log policy, governance, reward meaning, reviewer authority, or any real
contribution record.

## Purpose

The current T3 simulation shows that a newcomer can follow the public proposal
path for a small review contribution. Its remaining risk is not that every step
requires private founder context. The risk is narrower: a few decisive moments
can still hide founder judgment unless the review record names the evidence,
boundary, and reason.

This map separates founder context into three categories:

- public-context sufficiency: the existing public files already carry the step;
- review-judgment dependency: a reviewer must decide, but can explain the basis;
- governance-sensitive dependency: the step would change policy, authority, or
  rights if adopted and therefore remains outside this test.

## Source Surfaces

- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `templates/contribution-proposal.md`
- `templates/contribution-log-schema.md`
- `projects/first-workflow-simulation/2026-07-02-t3-newcomer-workflow-simulation.md`
- `projects/prototype-workflow/2026-07-02-rq5-prototype-workflow-synthesis.md`
- `projects/prototype-workflow/2026-07-06-rq5-workflow-handoff-gap-map.md`
- `projects/first-contribution-workflow-dry-run/2026-07-05-t11-synthetic-adverse-decision-trace.md`

## Dependency Map

| decision point | current public support | hidden founder-context risk | inspectable review check | boundary preserved |
|---|---|---|---|---|
| Choosing a live target | `CONTRIBUTING.md`, `RESEARCH-AGENDA.md`, and `TESTS.md` expose live questions. | A newcomer may still need private advice to know which target is safe for a first attempt. | Review note names why the chosen target is live and low-governance-risk. | Does not designate an official pilot target. |
| Classifying the contribution | `CONTRIBUTION-STANDARDS.md` names contribution classes and examples. | Mixed review/protocol-design work can be classified by intuition rather than visible criteria. | Reviewer names one primary class, any secondary effect, and the deciding reason. | Does not change class definitions. |
| Applying evidence minimums | Research-class evidence minimums are public; review-class reasoning can be acceptable. | A reviewer can require sources for some reasoning contributions but not others without explaining why. | Review note says which class-specific evidence minimum applied and whether missing evidence is a revision request. | Does not adopt new evidence thresholds. |
| Separating critique from policy | The T3 simulation and RQ5 handoff map name the policy-adoption boundary. | A useful critique can quietly become a rule, or be rejected because it sounds policy-like. | Rationale states what value is preserved and what proposed rule is not adopted. | Does not change AI, governance, contribution, or review policy. |
| Choosing review state | Review states are named in the standards and proposal template. | `needs_revision`, `not_accepted`, and `contested` can reflect founder preference if rationale is thin. | Rationale names the decisive missing element, accepted unit, or disputed point. | Does not change review-state meanings. |
| Writing loss notes | The log schema supports `loss_notes`. | Loss notes can imply reward, retained value, or future acceptance if not bounded. | Loss note states the retained insight and explicitly names any promise not created. | Does not create reward, legal, retained-value, or governance claims. |
| Deciding log eligibility | The live log uses real contribution records; synthetic examples stay outside it. | A log-ready draft can be mistaken for a live contribution decision. | Review record states why the item is or is not eligible for `CONTRIB-NNNN`. | Does not write a live contribution record. |
| Marking contestability | `contested` exists as a review state; the adverse trace uses a contestability marker. | Naming a dispute point can look like an adopted appeal process. | Record the specific challengeable point without promising timing, forum, or authority. | Does not adopt an appeal or dispute process. |

## First-Pilot Review Prompts

A later pilot review can use these prompts without editing policy:

1. Which public file gave the contributor enough context to attempt the work?
2. Which part of the decision required reviewer judgment rather than private
   founder knowledge?
3. Was the primary contribution class named with a visible reason?
4. Was the evidence minimum tied to the contribution class?
5. Did the rationale separate useful value from unadopted policy language?
6. Did `loss_notes` preserve value without creating a reward or rights promise?
7. Could a later reader reconstruct the decision without asking the founder?
8. What would need Joe review before becoming active policy?

## Dependency Reduction Targets

| target | low-risk improvement | still gated |
|---|---|---|
| Proposal clarity | Ask the contributor or reviewer to name the primary target and class in the review record. | Changing proposal templates or issue forms. |
| Rationale clarity | Include one sentence explaining the decisive boundary or missing evidence. | Adopting minimum rationale policy. |
| Policy separation | Preserve proposed policy language as deferred value rather than silently adopting it. | Changing contribution instructions, AI policy, or governance rules. |
| Log reconstruction | Keep synthetic or draft traces outside live `CONTRIB-NNNN` space until a real reviewed contribution exists. | Deciding the first live log-entry trigger. |
| Contestability | Name the point that could be challenged or corrected. | Adopting an appeal route, response time, or decision authority. |

## Later T3 Evidence

T3 would become stronger if a real first contribution shows:

- the contributor used only public files to identify the target and proposal
  fields;
- the reviewer named the primary class and evidence minimum;
- the rationale recorded the decisive boundary without adopting policy;
- useful residue was preserved in `loss_notes`;
- any disputed point was visible without promising an appeal path;
- the final record can be understood without private founder explanation.

This would still not by itself prove the full workflow. It would only reduce
the specific failure signal that the process depends on founder intuition at
every step.

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested, or
  rewarded.
- No live contribution log entry was changed.
- No claim status changed.
- No T3 or RQ5 pass/fail state changed.
- No contribution instructions, issue template, contribution standard, review
  policy, reviewer authority, governance rule, appeal process, reward meaning,
  rights policy, or public posture changed.
- This is draft workflow evidence for later review, not active contribution
  policy.
