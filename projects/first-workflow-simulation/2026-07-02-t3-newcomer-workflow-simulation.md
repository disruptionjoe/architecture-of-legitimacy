---
artifact_type: workflow_simulation
status: complete
created: 2026-07-02
test_target: T3 first workflow simulation
governance_role: internal_test_record
constitutional: false
---

# T3 Newcomer Workflow Simulation

This fixture walks one synthetic newcomer contribution from proposal intake to a
log-ready review outcome. It does not create a real contribution, does not edit
`CONTRIBUTIONS-LOG.md`, does not decide anyone's work, and does not mark T3
passed.

## Source Surfaces Used

- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `CONTRIBUTIONS-LOG.md`
- `templates/contribution-proposal.md`
- `templates/contribution-log-schema.md`
- `TESTS.md`

## Synthetic Newcomer Scenario

- **Persona:** First-time pseudonymous contributor.
- **Agent assistance:** Yes, labeled.
- **Contribution class:** review.
- **Target:** `TESTS.md`, T8 AI role boundary.
- **Proposed contribution:** A short red-team note arguing that AI-assisted
  review should never supply final legitimacy authority, with two failure modes
  and one suggested boundary sentence for a future T8 fixture.
- **Why this scenario:** It is small enough for a newcomer to attempt, touches a
  live test, and surfaces the difference between useful critique and adopting a
  governance rule.

## Step-By-Step Simulation

| step | newcomer action | project check | simulated result | founder-context dependency |
|---|---|---|---|---|
| 1. Orientation | Reads the public start files named in `CONTRIBUTING.md`. | Can the contributor find the live question without private context? | Pass. T8 is visible in `TESTS.md`; contribution classes are visible in `CONTRIBUTION-STANDARDS.md`. | Low. |
| 2. Proposal draft | Uses `templates/contribution-proposal.md` and labels agent assistance. | Does the proposal name class, target, value, evidence/reasoning, failure, and deferred value? | Pass with one gap: evidence is reasoning-only, not prior art. | Low. |
| 3. Submission state | Marks proposed review state as `submitted`. | Does the workflow avoid asking the contributor to self-accept or self-score as truth? | Pass. Self-assessment is discussion input, not a decision. | Low. |
| 4. Triage | Reviewer classifies the work. | Is the primary class recognizable? | Pass. Primary class is `review`; secondary relevance is protocol design. | Medium: reviewer must decide whether the proposed sentence is merely feedback or a policy change. |
| 5. Evidence check | Reviewer checks whether the contribution needs citations. | Does the current standard distinguish review from research-class evidence minimums? | Pass. A red-team note can be reasoning-based, but prior-art claims would need sources. | Medium. |
| 6. Governance boundary | Reviewer separates critique from adoption. | Would accepting the note silently change AI authority policy? | Needs revision before adoption. The critique can be useful, but the suggested boundary sentence should not become policy through this simulation. | High unless reviewer records the boundary explicitly. |
| 7. Review rationale | Reviewer records decisive reason. | Can a newcomer reconstruct the outcome? | Pass if rationale says the critique is useful but policy language needs a separate governance review. | Medium. |
| 8. Log readiness | Reviewer prepares a candidate log entry outside the live namespace. | Can the log schema represent the decision and deferred value? | Pass. `loss_notes` can preserve the useful warning without accepting a policy sentence. | Low. |

## Synthetic Proposal Snapshot

```yaml
title: AI review boundary red-team note
contributor: Synthetic Newcomer (pseudonymous; agent-assisted)
contribution_class: review
target: TESTS.md; T8 AI role boundary
summary: >
  Identifies a failure mode where AI-assisted review becomes an opaque
  substitute for legitimacy rather than a synthesis aid.
evidence_or_reasoning: >
  Reasoning-based red-team note. It does not claim prior-art coverage and
  should not be treated as a research-class comparison.
failure_or_risk: >
  The proposed boundary sentence may be too broad and could block useful AI
  summarization if adopted without a separate T8 review.
loss_or_deferred_value: >
  Even if the sentence is not adopted, the warning should inform a future AI
  role boundary fixture.
proposed_review_state_on_submit: submitted
```

## Candidate Log Entry If This Were Real

This is an example only. It should not be copied into `CONTRIBUTIONS-LOG.md`
unless a real contribution exists and a real review decision has been made.

```yaml
id: SAMPLE-T3-001
date: 2026-07-02
contributor: Synthetic Newcomer (pseudonymous; agent-assisted)
class: review
target: TESTS.md; T8 AI role boundary
review_state: needs_revision
rubric_scores:
  clarity: 2
  rigor: 1
  relevance: 3
  novelty: 1
  legitimacy: 2
  capture_resistance: 2
  coordination_value: 2
rationale: >
  The critique usefully identifies an AI-authority failure mode for T8, but the
  proposed boundary sentence would change policy if adopted as-is. A revised
  version should separate the warning from any normative rule change.
loss_notes: >
  The policy sentence is not accepted in this simulated outcome, but the warning
  should remain available when a future T8 fixture defines allowed and disallowed
  AI review uses.
links:
  - synthetic example only; no issue or PR
```

## Newcomer Usability Findings

1. **The public workflow is followable for a small review contribution.** A
   newcomer can identify a live test, choose a contribution class, fill the
   proposal template, and understand the possible review states.
2. **The main ambiguity is the review/policy boundary.** The workflow needs the
   reviewer to say when a useful critique is being preserved without adopting a
   proposed rule.
3. **Founder judgment is still present, but can be made inspectable.** The
   decisive judgment is not hidden if the rationale names the boundary: useful
   red-team note, not yet policy.
4. **The log schema can carry the result without a live contribution.** The
   `loss_notes` field is enough to preserve deferred value without implying
   reward, acceptance, or governance movement.

## Later T3 Pass Criteria

T3 should not be marked passed from this fixture alone. A later review could
consider T3 stronger when:

- a real newcomer can submit using the public template without private founder
  context;
- the review rationale clearly distinguishes useful contribution value from
  unaccepted policy language;
- the log entry can reconstruct the decision without hidden context;
- disputed or revised value is preserved without creating reward, legal, or
  governance promises.

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested, or
  rewarded.
- No claim status changed.
- No T3 pass/fail state changed.
- No AI review policy or governance rule changed.
- No reward, retained-value, legal, or financial promise is created.
