# Contribution Taxonomy Surface Map

Status: navigation surface map.

## Purpose

This directory contains non-adopted RQ2/T1 scaffolds for making contribution
classes, review-path routing, ambiguous boundary cases, consistency signals,
and first-pilot class/evidence disagreements inspectable before real
contributors depend on the taxonomy.

This map is navigation only. It does not adopt taxonomy policy, review paths,
review states, reviewer authority, contribution standards, contribution
templates, issue templates, contribution-log schema, claim status, test status,
governance rules, rights, rewards, AI policy, transfer posture, public posture,
or live contribution records.

## Read Order

Use this order when trying to understand the current contribution-taxonomy
lane.

| order | artifact | use it for | protected boundary |
|---|---|---|---|
| 1 | [T1 contribution taxonomy fixture](2026-07-01-t1-contribution-taxonomy-fixture.md) | Synthetic samples for testing whether reviewers can classify contribution types without private founder context. | No live contribution log, acceptance record, reward record, governance decision, claim movement, or test pass. |
| 2 | [RQ2 contribution taxonomy review-path map](2026-07-02-rq2-review-path-map.md) | Draft separation of contribution class, intake evidence, review lane, and review state. | No active class, review-path, review-state, reviewer-authority, governance, reward, or contribution-record adoption. |
| 3 | [RQ2 contribution taxonomy boundary-case fixture](2026-07-06-rq2-boundary-case-fixture.md) | Ambiguous cases where useful work, policy movement, overclaim, evidence integrity, and tool authority must stay separable. | No taxonomy expansion, proposal-format change, review-lane adoption, governance rule, reward meaning, public posture, or live record. |
| 4 | [T1 classification consistency check](2026-07-06-t1-classification-consistency-check.md) | Comparison signals for reviewer agreement, compatible disagreement, stop-condition recognition, and taxonomy failure. | No active reviewer procedure, contribution standard, test verdict, claim status, public posture, or contribution record. |
| 5 | [RQ2 first-pilot class/evidence screen](2026-07-08-rq2-first-pilot-class-evidence-screen.md) | Non-live screen for classifying a synthetic first-pilot packet and naming missing evidence before review, value, or rationale hardens. | No pilot launch, target selection, live surface, template edit, reviewer assignment, test pass, rights, reward, governance, public posture, or contribution record. |
| 6 | [RQ2 first-pilot class-boundary disagreement ledger](2026-07-09-rq2-first-pilot-class-boundary-ledger.md) | Review-prep labels for class ordering, missing evidence, mechanism ambiguity, policy movement, residue, semantic drift, tool authority, and public overclaim. | No live classification, taxonomy change, review-path adoption, reviewer authority, claim/test movement, rights, rewards, governance, AI policy, transfer, public posture, or live record. |

## Current Lane State

```yaml
lane_state: contribution_taxonomy_review_prep_visible
taxonomy_fixture: available
review_path_map: available
boundary_case_fixture: available
classification_consistency_check: available
first_pilot_class_evidence_screen: available
class_boundary_disagreement_ledger: available
active_taxonomy_policy_state: unchanged
review_path_state: not_adopted
reviewer_authority_state: unchanged
claim_status: unchanged
test_status: not_marked_passed
public_posture: unchanged
live_review_ready: false
```

These labels are review-prep labels only. They are not contribution states,
issue labels, review states, policy states, claim verdicts, test results,
rights states, reward states, governance states, public-posture labels, or
contribution-record meanings.

## How To Read The Lane

Read the T1 fixture first to see the current synthetic samples and the seven
classes under pressure: `research`, `formalization`, `protocol design`,
`review`, `synthesis`, `implementation`, and `maintenance`.

Then read the RQ2 review-path map and boundary-case fixture together. The
review-path map separates class, evidence, lane, and state; the boundary-case
fixture shows where useful evidence, synthesis, implementation, maintenance,
protocol design, policy movement, and evidence integrity can become bundled.

The consistency check should come next because it explains what kind of reviewer
agreement or disagreement is useful evidence. The first-pilot class/evidence
screen and class-boundary disagreement ledger then apply the lane to the
synthetic RQ5 first-pilot packet without making it live.

The central distinction is:

```text
The repo can prepare contribution-taxonomy review visibility; it has not
authorized taxonomy adoption, review-path adoption, reviewer authority,
contribution-standard edits, claim/test movement, public-posture movement,
rights, rewards, governance movement, or live contribution records.
```

## Adjacent Lanes

Read these neighboring surfaces before interpreting this lane as broader than a
bounded RQ2/T1 taxonomy review-prep lane:

- [Contribution eligibility](../contribution-eligibility/) for RQ1 eligibility,
  disclosure, contributor-continuity, and protected-consequence screens.
- [Value rubric options](../value-rubric-options/) for RQ3/T2 value rubric
  options, dimension failures, first-pilot value screens, and disagreement
  ledgers.
- [Prototype workflow](../prototype-workflow/) for RQ5 packet, source-trace,
  record-surface, revision, and review-prep bundle scaffolds.
- [First-ring synthesis](../first-ring-synthesis/) for the cross-lane first
  ring review-prep map.
- [Pilot review readiness](../pilot-review-readiness/) for governed-review
  handoff, question register, answerability, and packet-map surfaces.

## Stop Conditions

Stop for Joe or governed review before:

- changing contribution classes, review paths, review states, reviewer
  authority, contribution standards, contribution templates, issue templates,
  contribution-log schema, governance files, guardrails, claims, test-status
  surfaces, or public-facing posture surfaces;
- assigning accepted, revised, rejected, adversarial, scored, rewarded,
  sanctioned, rights-bearing, retained-value, governance-weight, claim-status,
  test-status, public-language, or contribution-record meaning;
- selecting a real first-pilot target, contribution unit, contributor, reviewer
  owner, live record surface, public audience, reward context, AI tool, or
  transfer context;
- treating synthetic samples, review-prep labels, AI output, implementation
  checks, or private founder context as source evidence, review authority,
  contribution value, reward entitlement, participant right, governance
  authority, or live record;
- opening an issue, pull request, review thread, public invitation, contribution
  log entry, score ledger, or non-GitHub external action;
- storing private, confidential, regulated, proprietary, or unsafe material in
  the public repo.

## Safe Use

Use this map to find the current RQ2/T1 contribution-taxonomy artifacts and
preserve read order. Do not use it as evidence that active taxonomy policy
exists, review paths exist, reviewer authority exists, a pilot is live, a
contribution can be logged, rights or rewards exist, or any policy/status
decision has already been made.
