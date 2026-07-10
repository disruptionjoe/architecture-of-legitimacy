# AI Role Boundary Surface Map

Status: navigation surface map.

## Purpose

This directory contains non-adopted C7/T8 scaffolds for making AI-assisted
review visible, contestable, human-owned, source-checkable, and non-capturing
before any live contribution review depends on it.

This map is navigation only. It does not adopt AI-use policy, require
disclosure, select tools or models, attach model output as evidence, assign
reviewer authority, launch review, change claim status, change test status,
create rights or rewards, move governance, alter transfer posture, change public
posture, or create live contribution records.

## Read Order

Use this order when trying to understand the current AI-boundary lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [T8 AI role boundary fixture](2026-07-02-t8-ai-role-boundary-fixture.md) | Role-boundary examples for allowed support, conditional support, disallowed authority, and adversarial AI patterns. | No AI policy, claim, test, governance, public-posture, rights, reward, or live-record movement. |
| 2 | [C7 AI-assisted review trace checklist](2026-07-03-c7-ai-assisted-review-trace-checklist.md) | Minimum visible trace for AI-supported review records: AI task, source scope, human decision owner, contestability, loss notes, and capture-risk screen. | No schema, template, reviewer-authority, AI policy, reward, rights, or contribution-record movement. |
| 3 | [C7/T8 AI authority failure map](2026-07-06-c7-t8-ai-authority-failure-map.md) | Failure patterns where AI assistance becomes hidden authority, citation laundering, synthetic consensus, reviewer abdication, or contestability failure. | No AI-use policy, contribution policy, issue-template, governance, reviewer-authority, claim, test, public-posture, or rights/reward movement. |
| 4 | [C7/T8 AI-assisted review dry-run trace](2026-07-07-c7-ai-assisted-review-dry-run-trace.md) | Synthetic trace applying the checklist and failure map to the RQ5 first-pilot packet while keeping the packet in review-prep state. | No live target, live record surface, issue, PR, template edit, reviewer assignment, claim/test movement, reward, rights, governance, transfer, or public-posture movement. |
| 5 | [C7/T8 first-pilot AI-boundary ledger](2026-07-09-c7-t8-first-pilot-ai-boundary-ledger.md) | First-pilot AI pressure labels for local trace repair, source-trace gaps, AI capture review, governed AI review, and do-not-use-live stops. | No disclosure mandate, sanction, eligibility limit, reviewer authority, AI tool/model selection, AI policy, transfer, public-posture, or live-record movement. |

## Current Lane State

```yaml
lane_state: ai_boundary_review_prep_visible
fixture: available
trace_checklist: available
authority_failure_map: available
dry_run_trace: available
first_pilot_ai_boundary_ledger: available
live_review_ready: false
source_trace_state: source_trace_still_missing
ai_policy_state: not_adopted
reviewer_authority_state: unchanged
disclosure_rule_state: not_adopted
tool_or_model_selection: none
model_output_as_evidence: false
claim_status: unchanged
test_status: not_marked_passed
public_posture: unchanged
```

These labels are review-prep labels only. They are not contribution states,
issue labels, policy states, sanctions, reviewer-authority assignments, rights
markers, reward states, governance states, transfer states, claim verdicts, or
test results.

## How To Read The Lane

Read the fixture first to get the basic role vocabulary. Then read the trace
checklist and failure map together: one names what must be visible, the other
names how AI becomes hidden authority. The dry-run trace applies that boundary
to the synthetic RQ5 packet. The first-pilot ledger then sorts the remaining AI
pressures into local repair, source-trace, capture-review, governed-review, and
live-use stops.

The central distinction is:

```text
The repo can prepare AI-boundary review visibility; it has not authorized
AI-use policy, reviewer authority, disclosure mandates, sanctions, tool
selection, model evidence, live review, rights, rewards, governance, transfer,
public-posture movement, contribution records, or claim/test movement.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded AI-boundary review-prep lane:

- [Prototype workflow](../prototype-workflow/) for RQ5 packet, source-trace,
  record-surface, revision, and review-prep bundle scaffolds.
- [Attack profitability](../attack-profitability/) for capture-escalation
  concerns including AI volume, conflict, and public-posture pressure.
- [Attack surface map](../attack-surface-map/) for detection evidence and
  false-positive screens.
- [Second-ring synthesis](../second-ring-synthesis/) for the cross-lane
  governance, rights, capture, AI, reward, and transfer stop stack.
- [Pilot review readiness](../pilot-review-readiness/) for governed-review
  handoff and packet-map surfaces.

## Stop Conditions

Stop for Joe or governed review before:

- selecting a real first-pilot target, source lane, contribution unit,
  contributor, reviewer owner, live record surface, AI tool, model, prompt
  protocol, disclosure placement, sanction path, eligibility limit, public
  audience, or transfer context;
- filling a live source-trace packet or changing a synthetic packet into a live
  contribution object;
- opening an issue, pull request, review thread, public invitation, or
  contribution-log entry;
- editing contribution templates, issue templates, contribution standards,
  review policy, AI-use policy, governance files, guardrails, claims,
  test-status surfaces, or public-facing posture surfaces;
- assigning reviewer authority, AI-use rules, disclosure requirements,
  sanctions, appeal rights, eligibility restrictions, score meaning, reward
  logic, retained-value rights, governance weight, transfer criteria, or public
  language;
- treating model output, repeated AI output, simulated reviewer voices, or AI
  scores as source evidence, participant voice, review authority, legitimacy
  evidence, contribution value, or reward meaning;
- assigning contribution classifications, accepted/rejected states, test
  outcomes, claim-status movement, legal/financial meaning, or
  contribution-record meaning;
- or taking any non-GitHub external action.

## Safe Use

Use this map to find the current C7/T8 AI-boundary artifacts and preserve read
order. Do not use it as evidence that a live AI-assisted review procedure
exists, disclosure rules exist, reviewer authority exists, AI tools are
approved, model output can be evidence, rights or rewards exist, a contribution
can be logged, or any policy/status decision has already been made.
