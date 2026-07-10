# Review Cadence Options Surface Map

Status: navigation surface map.

## Purpose

This directory contains non-adopted RQ4 scaffolds for making review cadence,
timing, contestability, rationale minimums, first-pilot rationale fields, and
reviewer-capacity pressure inspectable before any live review or policy
movement.

This map is navigation only. It does not adopt cadence policy, appeal policy,
review states, reviewer authority, response-time promises, contribution
standards, contribution templates, issue templates, contribution-log schema,
claim status, test status, governance rules, rights, rewards, AI policy,
transfer posture, public posture, or live contribution records.

## Read Order

Use this order when trying to understand the current RQ4 review-cadence lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [RQ4 review-cadence options scaffold](2026-07-02-rq4-review-cadence-options.md) | Candidate review-lane shapes, rationale minimums, capture checks, and later adoption questions. | No cadence option, review policy, appeal rule, reviewer authority, governance decision, claim movement, or live record. |
| 2 | [RQ4 cadence timing comparison](2026-07-05-rq4-cadence-timing-comparison.md) | Comparison of rolling, continuous, and pilot-gated timing against the same synthetic contribution. | No review-cadence decision, response-time promise, appeal rule, claim/test movement, public-posture movement, or live review. |
| 3 | [RQ4 adverse-review contestability boundary](2026-07-06-rq4-adverse-review-contestability-boundary.md) | Adverse outcome traces, contested states, rationale minimums, and timing implications. | No adverse-state policy, appeal adoption, governance rule, reviewer-authority movement, sanction, rights, reward, or live record. |
| 4 | [RQ4 rationale-minimums map](2026-07-07-rq4-rationale-minimums-map.md) | Minimum visible rationale fields a later review record would need across review states. | No rationale requirement, cadence decision, contribution-standard edit, governance change, claim/test movement, or live review. |
| 5 | [RQ4 first-pilot rationale screen](2026-07-08-rq4-first-pilot-rationale-screen.md) | Non-live screen for what a synthetic first-pilot packet can preserve before appeal, cadence, or state meaning hardens. | No first-pilot launch, target selection, review-state adoption, appeal rule, template edit, rights, reward, governance, or public posture. |
| 6 | [RQ4 first-pilot reviewer-capacity screen](2026-07-09-rq4-first-pilot-reviewer-capacity-screen.md) | Capacity-pressure screen for review ownership, attention budget, rationale load, contestability load, and synthesis load. | No reviewer appointment, reviewer-authority assignment, response-time promise, review launch, claim/test movement, or live contribution record. |

## Current Lane State

```yaml
lane_state: review_cadence_review_prep_visible
cadence_options_scaffold: available
timing_comparison: available
contestability_boundary: available
rationale_minimums_map: available
first_pilot_rationale_screen: available
reviewer_capacity_screen: available
cadence_policy_state: not_adopted
appeal_policy_state: not_adopted
review_state_meaning: not_adopted
reviewer_authority_state: unchanged
response_time_promise_state: not_adopted
claim_status: unchanged
test_status: not_marked_passed
public_posture: unchanged
live_review_ready: false
```

These labels are review-prep labels only. They are not contribution states,
issue labels, appeal states, response-time commitments, reviewer-authority
assignments, governance states, claim verdicts, test results, public-posture
labels, or contribution-record meanings.

## How To Read The Lane

Read the options scaffold first to understand the candidate review-lane shapes:
rolling triage plus weekly batch, continuous maintenance plus twice-monthly
substantive review, and pilot-gated cadence before real external review.

Then read the timing comparison and contestability boundary together. The
timing comparison keeps one synthetic contribution constant while changing the
review rhythm; the contestability boundary shows what must stay visible when an
adverse or contested state appears.

The rationale-minimums map should come next because it names the visible fields
a later review record would need before any review state can be interpreted.
The first-pilot rationale screen and reviewer-capacity screen then apply the
lane to the synthetic RQ5 first-pilot packet without launching review, adopting
appeals, appointing reviewers, or promising response times.

The central distinction is:

```text
The repo can prepare review-cadence visibility; it has not authorized cadence
policy, appeal policy, review-state meaning, reviewer authority, response-time
promises, claim/test movement, public-posture movement, rights, rewards,
governance movement, contribution standards, or live contribution records.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded RQ4 review-cadence review-prep lane:

- [Contribution eligibility](../contribution-eligibility/) for RQ1 eligibility,
  disclosure, contributor-continuity, and protected-consequence screens.
- [Contribution taxonomy](../contribution-taxonomy/) for RQ2/T1 class,
  evidence-minimum, ambiguity, and review-path scaffolds.
- [Value rubric options](../value-rubric-options/) for RQ3/T2 value-rubric
  options, dimension failures, first-pilot value screens, and disagreement
  ledgers.
- [Prototype workflow](../prototype-workflow/) for RQ5 packet, source-trace,
  record-surface, revision, and review-prep bundle scaffolds.
- [Pilot review readiness](../pilot-review-readiness/) for governed-review
  handoff, question register, answerability, and packet-map surfaces.

## Stop Conditions

Stop for Joe or governed review before:

- changing cadence policy, appeal policy, review states, reviewer authority,
  response-time promises, contribution standards, contribution templates, issue
  templates, contribution-log schema, governance files, guardrails, claims,
  test-status surfaces, or public-facing posture surfaces;
- assigning accepted, revised, rejected, contested, adverse, appealed,
  time-bound, reviewer-owned, rights-bearing, rewarded, sanctioned,
  governance-weight, claim-status, test-status, public-language, or
  contribution-record meaning;
- selecting a real first-pilot target, contribution unit, contributor,
  reviewer owner, live record surface, public audience, reward context, AI
  tool, or transfer context;
- treating synthetic packet notes, review-prep labels, AI output, private
  founder context, or capacity assumptions as source evidence, review
  authority, contribution value, reward entitlement, participant right,
  governance authority, or live record;
- opening an issue, pull request, review thread, public invitation,
  contribution-log entry, response-time ledger, or non-GitHub external action;
- storing private, confidential, regulated, proprietary, or unsafe material in
  the public repo.

## Safe Use

Use this map to find the current RQ4 review-cadence artifacts and preserve read
order. Do not use it as evidence that cadence policy exists, appeal policy
exists, reviewer authority exists, response-time commitments exist, a pilot is
live, a contribution can be logged, rights or rewards exist, or any
policy/status decision has already been made.
