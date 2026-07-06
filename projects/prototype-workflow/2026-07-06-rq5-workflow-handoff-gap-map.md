---
artifact_type: research_scaffold
status: draft
created: 2026-07-06
research_question: RQ5 prototype workflow
test_target: T3 first workflow simulation
governance_role: non_adopted_handoff_gap_map
constitutional: false
---

# RQ5 Workflow Handoff Gap Map

This scaffold maps the handoffs that still need to be inspectable before the
first public contribution workflow can be treated as ready for a real pilot. It
does not change active contribution instructions, issue templates, review
states, contribution-log policy, governance, reward meaning, or any real
contribution record.

## Purpose

The current RQ5 and T3 artifacts show that a synthetic newcomer can move from a
proposal to a log-ready review outcome. The remaining weakness is not the
absence of steps. It is whether each step hands enough information to the next
step that a contributor, reviewer, and later reader can reconstruct the decision
without private founder context.

This map turns that weakness into bounded checks for a later real pilot.

## Source Surfaces

- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `templates/contribution-proposal.md`
- `templates/contribution-log-schema.md`
- `projects/prototype-workflow/2026-07-02-rq5-prototype-workflow-synthesis.md`
- `projects/first-workflow-simulation/2026-07-02-t3-newcomer-workflow-simulation.md`
- `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md`
- `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-log-examples.md`
- `projects/first-contribution-workflow-dry-run/2026-07-05-t11-synthetic-adverse-decision-trace.md`

## Handoff Chain

| handoff | current support | exposed gap | safe next proof |
|---|---|---|---|
| Orientation to proposal | `CONTRIBUTING.md` names start files and good first contributions. | A newcomer still has to infer which live target is safest for a first pilot. | Name the pilot target in a draft artifact before any live invitation. |
| Proposal to triage | The proposal template asks for class, target, value, evidence, failure, and deferred value. | Mixed-class work can blur the primary review lane. | Require the pilot trace to name one primary class and any secondary effects. |
| Triage to evidence check | `CONTRIBUTION-STANDARDS.md` distinguishes contribution classes and research evidence minimums. | Reviewers may treat a useful review note like source-backed research, or the reverse. | Record which evidence minimum was applied and why. |
| Evidence check to governance boundary | The synthetic traces separate useful contribution value from protected moves. | The decisive stop boundary may still be hidden inside reviewer judgment. | Write one decisive boundary sentence in the review rationale. |
| Governance boundary to review state | Review states are named in standards and templates. | `needs_revision`, `not_accepted`, and `contested` can collapse if the reason is thin. | Pair each adverse state with a revision route or challenge scope. |
| Review state to loss notes | The log schema supports `loss_notes`. | Loss notes can sound like reward, retained-value, or future acceptance if imprecise. | State what value is preserved and what promise is not created. |
| Loss notes to log eligibility | The RQ5 synthesis asks what authorizes a live `CONTRIB-NNNN` entry. | A synthetic or draft contribution can look log-ready before a real decision exists. | Keep pilot dry runs in `SAMPLE-*` space until a real reviewed contribution exists. |
| Review record to contestability | The adverse-decision trace includes a contestability marker. | A challengeable point can imply an appeal process the repo has not adopted. | Mark the inspectable dispute point without promising timing, forum, or authority. |

## Pilot Handoff Checks

A later first-pilot trace should be able to answer these questions without
editing policy:

1. Which public source told the contributor what to attempt?
2. Which primary contribution class was selected?
3. Which evidence minimum applied to that class?
4. What was the decisive review reason?
5. Which protected boundary, if any, prevented adoption as submitted?
6. What revision route, if any, would make the contribution reviewable?
7. What value was preserved in `loss_notes`?
8. What promise was explicitly not created by the record?
9. What, exactly, could be contested or corrected?
10. Why is the item eligible or not eligible for a live contribution-log entry?

## State-Specific Gap Notes

| state | handoff risk | minimum trace for a pilot |
|---|---|---|
| `accepted` | Acceptance can appear to adopt policy, claim movement, reward meaning, or governance authority. | State the narrow accepted contribution unit and any boundaries that remain unadopted. |
| `needs_revision` | Revision can become an indefinite holding state. | Name the missing evidence, narrower target, or boundary clarification needed next. |
| `not_accepted` | Rejection can erase useful residue. | Preserve the useful value in `loss_notes` and explain what is not entering the project record. |
| `contested` | Contestability can imply a full appeal right. | Name the disputed point and current visible owner without adopting an appeal process. |
| `adversarial` | Bad-faith handling can become opaque or punitive. | Separate spam/manipulation evidence from ordinary weak contribution quality. |

## First-Pilot Readiness Implication

The safest next real pilot is still a bounded, source-backed prior-art or review
contribution. This map adds one extra requirement: the pilot should be evaluated
less as a content win and more as a handoff test. The useful evidence is whether
each transition carries enough context forward without asking readers to trust a
private founder explanation.

The pilot should remain low-risk:

- no claim-status movement;
- no live governance or reward promise;
- no contribution-standard rewrite;
- no appeal or response-time policy;
- no live log entry unless a real contribution has actually been reviewed.

## Later Adoption Questions

- Should `CONTRIBUTING.md` eventually include a short first-pilot target, or is
  that too much public steering before the first real test?
- Should the proposal template ask for primary and secondary contribution
  classes, or should the reviewer assign that during triage?
- Should `loss_notes` get an explicit "not a reward promise" reminder in live
  review records, or is the schema note enough?
- Which state needs the strongest minimum rationale: `needs_revision`,
  `not_accepted`, or `contested`?
- What evidence would make T3 stronger without marking it passed from synthetic
  traces alone?

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested, or
  rewarded.
- No live contribution log entry was changed.
- No claim status changed.
- No T3 or RQ5 pass/fail state changed.
- No contribution instructions, issue template, contribution standard,
  governance rule, appeal process, reward meaning, rights policy, or public
  posture changed.
- This is draft workflow evidence for later review, not active contribution
  policy.
