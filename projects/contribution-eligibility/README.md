# Contribution Eligibility Surface Map

Status: navigation surface map.

## Purpose

This directory contains non-adopted RQ1 scaffolds for contributor and
contribution eligibility, disclosure relevance, first-pilot attemptability, and
eligibility gap visibility.

This map is navigation only. It does not adopt eligibility policy, disclosure
policy, conflict policy, contributor limits, sanctions, review policy, reviewer
authority, contribution standards, templates, claim status, test status, rights,
rewards, governance, AI policy, transfer posture, public posture, or live
contribution records.

## Read Order

Use this order when trying to understand the current contribution-eligibility
lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [RQ1 contribution eligibility options](2026-07-02-rq1-contribution-eligibility-options.md) | Candidate principles for open attemptability, reviewability, identity/status neutrality, pseudonymous contribution, agent assistance, and conflict disclosure. | No eligibility rule, disclosure requirement, contribution-standard, governance, reward, or live-record movement. |
| 2 | [RQ1 disclosure edge-case matrix](2026-07-06-rq1-disclosure-edge-case-matrix.md) | Review-relevance cases for identity, affiliation, conflicts, pseudonymity, agent assistance, private evidence, and adversarial incentives. | No disclosure mandate, identity policy, conflict policy, sanction, reviewer-authority, rights, reward, governance, or public-posture movement. |
| 3 | [RQ1 first-pilot eligibility screen](2026-07-08-rq1-first-pilot-eligibility-screen.md) | Screen for what a synthetic first-pilot packet would need before reviewability, accountability, and public-evidence questions can be inspected. | No live target, live record surface, public invitation, template edit, eligibility policy, disclosure policy, AI policy, rights, reward, governance, transfer, or public-posture movement. |
| 4 | [RQ1 first-pilot eligibility gap ledger](2026-07-09-rq1-first-pilot-eligibility-gap-ledger.md) | Gap labels for target, contribution unit, contributor continuity, public evidence, disclosure relevance, private-evidence boundary, agent accountability, and protected consequences. | No target selection, live packet fill, issue/PR creation, source-lane choice, policy adoption, claim/test movement, rights, reward, governance, transfer, or live-record movement. |

## Current Lane State

```yaml
lane_state: contribution_eligibility_review_prep_visible
eligibility_options: available
disclosure_edge_case_matrix: available
first_pilot_eligibility_screen: available
first_pilot_gap_ledger: available
eligibility_policy_state: not_adopted
disclosure_policy_state: not_adopted
conflict_policy_state: not_adopted
contributor_limit_state: not_adopted
live_review_ready: false
source_trace_state: source_trace_still_missing
claim_status: unchanged
test_status: not_marked_passed
public_posture: unchanged
```

These labels are review-prep labels only. They are not contribution states,
issue labels, policy states, sanctions, reviewer-authority assignments, rights
markers, reward states, governance states, transfer states, claim verdicts, or
test results.

## How To Read The Lane

Read the options scaffold first to understand the difference between open
attemptability, reviewability, identity/status neutrality, pseudonymity,
agent-assisted work, and conflict disclosure. Then read the disclosure matrix
to see how review relevance differs from credential gatekeeping or automatic
disqualification.

The first-pilot screen applies those distinctions to the synthetic RQ5 packet.
The gap ledger should come last because it turns the earlier screen into labels
a later governed review can preserve before any live use.

The central distinction is:

```text
The repo can prepare eligibility and disclosure visibility; it has not
authorized eligibility policy, disclosure mandates, contributor limits,
sanctions, reviewer authority, live review, rights, rewards, governance,
transfer, public-posture movement, contribution records, or claim/test
movement.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded RQ1 eligibility review-prep lane:

- [Prototype workflow](../prototype-workflow/) for RQ5 packet, source-trace,
  record-surface, revision, and review-prep bundle scaffolds.
- [Contribution taxonomy](../contribution-taxonomy/) for RQ2/T1 class,
  evidence-minimum, review-path, and class-boundary screens.
- [First-ring synthesis](../first-ring-synthesis/) for the current first-ring
  review-prep crosswalk and delta map.
- [Pilot review readiness](../pilot-review-readiness/) for governed-review
  handoff, question-register, answerability, and packet-map surfaces.
- [AI role boundary](../ai-role-boundary/) for C7/T8 agent-assistance and
  hidden-authority boundaries.

## Stop Conditions

Stop for Joe or governed review before:

- selecting a real first-pilot target, source lane, contribution unit,
  contributor, reviewer owner, live record surface, public audience, or transfer
  context;
- filling a live source-trace packet or changing a synthetic packet into a live
  contribution object;
- opening an issue, pull request, review thread, public invitation, or
  contribution-log entry;
- editing contribution templates, issue templates, contribution standards,
  review policy, eligibility policy, disclosure policy, governance files,
  guardrails, claims, test-status surfaces, or public-facing posture surfaces;
- requiring identity, pseudonymity, affiliation, conflict, private-evidence,
  agent-assistance, contributor-limit, sanction, appeal, or response-time
  policy;
- assigning contribution classifications, accepted/revised/rejected states,
  reviewer authority, score meaning, reward logic, retained-value rights,
  governance weight, source-trace sufficiency, transfer criteria, public
  language, claim-status movement, test-status movement, legal/financial
  meaning, or contribution-record meaning;
- storing private, confidential, regulated, proprietary, or unsafe material in
  the public repo;
- or taking any non-GitHub external action.

## Safe Use

Use this map to find the current RQ1 eligibility artifacts and preserve read
order. Do not use it as evidence that live eligibility rules exist, disclosure
requirements exist, contributor limits exist, sanctions exist, reviewer
authority exists, rights or rewards exist, a contribution can be logged, or any
policy/status decision has already been made.
