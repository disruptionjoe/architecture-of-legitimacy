# Legitimacy Failure Table Surface Map

Status: navigation surface map.

## Purpose

This directory contains non-adopted T4 scaffolds for making legitimacy failure
diagnosis, response routing, first-pilot screening, and diagnostic residue
inspectable before any live review or policy movement.

This map is navigation only. It does not change legitimacy conditions, response
routing policy, contribution standards, contribution templates, issue
templates, contribution-log schema, reviewer authority, claim status, test
status, governance rules, rights, rewards, AI policy, transfer posture, public
posture, hard policy, or live contribution records.

## Read Order

Use this order when trying to understand the current T4 legitimacy-failure
lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [T4 legitimacy failure table](2026-07-02-t4-legitimacy-failure-table.md) | Synthetic failure modes for testing whether legitimacy conditions can diagnose concrete failures without private founder judgment. | No legitimacy-condition change, claim verdict, test pass, governance movement, reward rule, or live contribution decision. |
| 2 | [T4 legitimacy failure response routing map](2026-07-06-t4-response-routing-map.md) | Separation of local repair, evidence gathering, Joe review, and governance/capture stops after a diagnosed failure. | No response-routing policy, appeal rule, contribution policy, rights, reward, governance, or claim/test movement. |
| 3 | [T4 first-pilot legitimacy screen](2026-07-08-t4-first-pilot-legitimacy-screen.md) | Non-live screen for checking the synthetic first-pilot packet against failure modes and routing defaults. | No pilot launch, live target selection, template edit, review-policy adoption, claim/test movement, rights, reward, governance, or public posture. |
| 4 | [T4 first-pilot diagnostic residue map](2026-07-09-t4-first-pilot-diagnostic-residue-map.md) | Residue fields a later diagnosis should preserve: failure signal, condition at risk, source/inference split, response lane, local repair delta, contestable point, and next authorization. | No appeal right, response deadline, reviewer obligation, live contribution-log requirement, governance change, rights, reward, or public posture. |

## Current Lane State

```yaml
lane_state: legitimacy_failure_review_prep_visible
failure_table: available
response_routing_map: available
first_pilot_legitimacy_screen: available
diagnostic_residue_map: available
legitimacy_condition_state: unchanged
response_routing_policy_state: not_adopted
reviewer_authority_state: unchanged
claim_status: unchanged
test_status: not_marked_passed
public_posture: unchanged
live_review_ready: false
```

These labels are review-prep labels only. They are not contribution states,
appeal states, reviewer obligations, claim verdicts, test results, governance
states, rights states, reward states, public-posture labels, or
contribution-record meanings.

## How To Read The Lane

Read the failure table first to see the current diagnostic object and the
failure modes under pressure. Then read the response-routing map to separate
local visibility repair from evidence gathering, Joe review, and
governance/capture stops.

The first-pilot legitimacy screen applies those surfaces to the synthetic RQ5
first-pilot packet without launching review. The diagnostic-residue map should
come last because it names what a later diagnosis would need to preserve before
any response lane can be interpreted.

The central distinction is:

```text
The repo can prepare legitimacy-failure review visibility; it has not
authorized legitimacy-condition changes, response-routing policy, reviewer
authority, appeal rights, deadlines, claim/test movement, governance movement,
public-posture movement, rights, rewards, or live contribution records.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded T4 legitimacy-failure review-prep lane:

- [Prototype workflow](../prototype-workflow/) for RQ5 packet, source-trace,
  record-surface, revision, and review-prep bundle scaffolds.
- [Pilot review readiness](../pilot-review-readiness/) for governed-review
  handoff, question register, answerability, and packet-map surfaces.
- [First-ring synthesis](../first-ring-synthesis/) for the current first-ring
  review-prep crosswalk and delta map.
- [Review cadence options](../review-cadence-options/) for RQ4 rationale,
  contestability, timing, and reviewer-capacity scaffolds.
- [Participant rights](../participant-rights/) for RQ7 voice, exit, retained
  record, contestability, and rights-stop scaffolds.

## Stop Conditions

Stop for Joe or governed review before:

- changing legitimacy conditions, response-routing policy, appeal policy,
  review states, reviewer authority, response-time promises, contribution
  standards, contribution templates, issue templates, contribution-log schema,
  governance files, guardrails, claims, test-status surfaces, or public-facing
  posture surfaces;
- assigning accepted, revised, rejected, contested, adverse, appealed,
  time-bound, reviewer-owned, rights-bearing, rewarded, sanctioned,
  governance-weight, claim-status, test-status, public-language, or
  contribution-record meaning;
- selecting a real first-pilot target, contribution unit, contributor, reviewer
  owner, live record surface, public audience, reward context, AI tool, or
  transfer context;
- treating synthetic packet notes, diagnostic labels, response lanes, AI
  output, private founder context, or capacity assumptions as source evidence,
  review authority, contribution value, reward entitlement, participant right,
  governance authority, or live record;
- opening an issue, pull request, review thread, public invitation,
  contribution-log entry, response-time ledger, or non-GitHub external action;
- storing private, confidential, regulated, proprietary, or unsafe material in
  the public repo.

## Safe Use

Use this map to find the current T4 legitimacy-failure artifacts and preserve
read order. Do not use it as evidence that legitimacy conditions changed,
response-routing policy exists, reviewer authority exists, appeal rights exist,
a pilot is live, a contribution can be logged, rights or rewards exist, or any
policy/status decision has already been made.
