# First Workflow Simulation Surface Map

Status: navigation surface map.

## Purpose

This directory contains non-live T3 workflow-simulation artifacts for checking
whether a newcomer contribution can move from public orientation through review
rationale and log readiness without hidden founder context.

This map is navigation only. It does not change workflow policy, contribution
standards, templates, contribution records, reviewer authority, claim status,
test status, governance, rights, rewards, AI policy, transfer posture, public
posture, hard policy, or live-review state.

## Read Order

Use this order when trying to understand the current T3 simulation lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [T3 newcomer workflow simulation](2026-07-02-t3-newcomer-workflow-simulation.md) | Synthetic walkthrough from proposal intake to a log-ready review outcome. | No real contributor, live contribution record, review decision, reward, claim, or test movement. |
| 2 | [T3 founder-context dependency map](2026-07-06-t3-founder-context-dependency-map.md) | Checks where public context is sufficient, where reviewer judgment must be visible, and where governance-sensitive moves stay blocked. | No workflow-policy, review-state, appeal, template, reviewer-authority, rights, reward, governance, or live-record adoption. |

## Current Lane State

```yaml
lane_state: t3_simulation_review_prep_visible
newcomer_simulation: available
founder_context_dependency_map: available
workflow_policy_state: not_adopted
live_contribution_state: none
live_log_entry: none
review_authority: pending_governed_review
claim_status: unchanged
test_status: not_marked_passed
public_posture: unchanged
```

These labels are review-prep labels only. They are not contribution states,
workflow policy, reviewer appointments, appeal paths, rights markers, reward
states, governance states, claim verdicts, test results, or public-facing
commitments.

## How To Read The Lane

Read the newcomer workflow simulation first to see the synthetic path through
orientation, proposal drafting, triage, evidence review, policy-boundary
separation, rationale, and log readiness.

Then read the founder-context dependency map to identify which steps are
already supported by public files, which steps need explicit reviewer rationale,
and which steps remain governance-sensitive and outside T3 simulation evidence.

The central distinction is:

```text
The repo can inspect whether a synthetic newcomer workflow is intelligible; it
has not authorized a live workflow, live contribution record, reviewer
authority, appeal route, reward meaning, rights meaning, or test pass/fail
movement from these artifacts.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded T3 workflow-simulation lane:

- [Prototype workflow](../prototype-workflow/) for RQ5 packet, source-trace,
  record-surface, revision, and review-prep bundle scaffolds.
- [First contribution workflow dry run](../first-contribution-workflow-dry-run/)
  for T10/T11 synthetic contribution-log, trace, loss-note, and contestability
  scaffolds.
- [Contribution eligibility](../contribution-eligibility/) for RQ1 eligibility,
  disclosure, contributor-continuity, and protected-consequence screens.
- [Contribution taxonomy](../contribution-taxonomy/) for RQ2/T1 contribution
  class, evidence-minimum, review-path, and class-boundary screens.
- [Review cadence options](../review-cadence-options/) for rationale minimums,
  contestability, cadence, and reviewer-capacity scaffolds.
- [AI role boundary](../ai-role-boundary/) for C7/T8 agent-assistance and
  hidden-authority boundaries.

## Stop Conditions

Stop for Joe or governed review before:

- selecting a real first-pilot target, contribution unit, contributor,
  reviewer owner, live record surface, source lane, or public audience;
- filling a live packet, opening an issue, opening a pull request, or editing a
  live contribution-log entry;
- editing contribution templates, issue templates, contribution standards,
  workflow policy, review policy, reviewer authority, governance files,
  guardrails, claims, or test-status surfaces;
- assigning contribution classifications, review states, appeal paths, response
  times, evidence thresholds, score meanings, reward logic, retained-value
  rights, governance weight, source-trace sufficiency, transfer criteria, public
  language, claim-status movement, test-status movement, legal/financial
  meaning, or contribution-record meaning;
- storing private, confidential, regulated, proprietary, or unsafe material in
  the public repo;
- or taking any non-GitHub external action.

## Safe Use

Use this map to find the current T3 simulation artifacts and preserve read
order. Do not use it as evidence that a live workflow exists, a reviewer has
authority, a contribution can be logged, an appeal path exists, rights or
rewards exist, or any policy/status decision has already been made.
