---
artifact_type: value_rubric_dry_run
status: synthetic_test_fixture
created: 2026-07-02
test_target: T2 value rubric dry run
governance_role: internal_test_record
constitutional: false
---

# T2 Value Rubric Dry Run

Status: synthetic test fixture.

Purpose: pressure-test whether the current value rubric in `CONTRIBUTION-STANDARDS.md` surfaces useful disagreements across different contribution types.

This file is not a live contribution log, acceptance record, reward record, governance decision, or claim-status decision. All submissions below are invented examples for T2 testing.

## Rubric Under Test

Score order:

```text
clarity / rigor / relevance / novelty / legitimacy / capture_resistance / coordination_value
```

Current score meanings:

- `0`: not present
- `1`: useful but minor
- `2`: substantial
- `3`: project-shaping

Scores should not be treated as automatic reward. They are a tool for discussion.

## Use Pattern

For a dry run, reviewers should independently score each sample before reading the suggested score vector.

Record:

- score vector,
- decisive reason for the highest score,
- decisive reason for the lowest score,
- whether the review state should change,
- and which rubric dimension caused the most disagreement.

The useful result is not identical scoring. The useful result is learning whether disagreement is informative, arbitrary, or hiding a missing rubric dimension.

## Synthetic Score Matrix

| id | class | hypothetical contribution | likely first review state | suggested score vector | useful disagreement to watch |
|---|---|---|---|---|---|
| T2-SAMPLE-01 | `research` | Compares the contribution workflow to Wikipedia dispute resolution and one public-goods funding system, with citations and mechanism-level notes. | `triaged` for substantive review. | `2 / 2 / 3 / 1 / 2 / 2 / 2` | Novelty may be low while relevance is high; reviewers should not confuse familiar prior art with low value. |
| T2-SAMPLE-02 | `formalization` | Defines contributor types and variables for the toy payoff model, but gives no assumptions for detection probability or sanction cost. | `needs_revision`. | `2 / 2 / 3 / 2 / 1 / 2 / 2` | Rigor may be split: useful variables, incomplete assumptions. Reviewers should name the missing assumption instead of flattening the score. |
| T2-SAMPLE-03 | `protocol design` | Proposes a monthly review cadence with triage, substantive review, contestation, and synthesis stages, but leaves founder authority untouched. | `needs_revision`. | `3 / 2 / 3 / 2 / 2 / 1 / 3` | Coordination value can be high even when capture-resistance is weak. The rubric should expose that tradeoff. |
| T2-SAMPLE-04 | `review` | Shows how the value rubric can be gamed by splitting one contribution into many small submissions and proposes a batching mitigation. | `triaged` for threat and mitigation review. | `2 / 3 / 3 / 2 / 2 / 3 / 3` | Reviewers may disagree whether mitigation belongs under rigor, capture resistance, or coordination value. |
| T2-SAMPLE-05 | `maintenance` | Fixes broken internal links and aligns terminology from "review path" to "review state" without changing policy. | `accepted` or `triaged`, depending on review procedure. | `3 / 1 / 2 / 0 / 2 / 1 / 3` | Low novelty should not erase high clarity or coordination value for maintenance work. |
| T2-SAMPLE-06 | `implementation` | Adds a script that checks contribution-log entries for required fields and internal links, with clear false-positive warnings. | `triaged` for usefulness review. | `2 / 2 / 2 / 1 / 2 / 2 / 3` | Tooling can improve legitimacy by making records inspectable, but it should not become final authority. |
| T2-SAMPLE-07 | `synthesis` | Rewrites the project summary in smoother language but does not link any claim, test, source, or workflow surface. | `needs_revision` or `not_accepted`. | `1 / 0 / 0 / 0 / 0 / 0 / 0` | Persuasive prose should not score as synthesis unless it preserves and improves project state. |
| T2-SAMPLE-08 | `protocol design` | Proposes immediate voting power for all accepted contributors without phase constraints, appeal rules, or capture analysis. | `needs_revision` or `not_accepted`. | `2 / 1 / 2 / 2 / 1 / 0 / 1` | A contribution can be relevant and non-obvious while still unsafe to adopt. Capture resistance should carry the objection. |
| T2-SAMPLE-09 | `synthesis` | Drafts a claim-ledger update that lowers an overclaim and links it to T9 prior-art work, but asks reviewers to change claim status immediately. | `needs_revision`. | `2 / 2 / 3 / 2 / 2 / 2 / 2` | The content may be valuable while the requested claim-status move crosses a governance boundary. |
| T2-SAMPLE-10 | `research` | Provides a source-backed prior-art collision check arguing that a neighboring system already contains part of the coupled-stack claim, with limits named. | `triaged` for substantive review. | `2 / 3 / 3 / 2 / 3 / 3 / 2` | This may reduce novelty while increasing legitimacy and rigor. The rubric should reward truth-seeking over persuasion. |

## Boundary Observations

- The rubric is most useful when it separates high value from easy acceptance.
- Low novelty can coexist with high coordination value, especially for maintenance.
- High relevance does not cure weak capture resistance.
- Governance-sensitive proposals can receive useful scores without being adopted.
- Prior art that narrows novelty can still score highly because it improves truthfulness.
- Tooling should improve inspectability and reviewer discipline, not replace judgment.

## Questions For A Later T2 Review

1. Do reviewers use `legitimacy` and `capture_resistance` distinctly, or do they collapse them?
2. Does `coordination_value` rescue low-novelty maintenance work appropriately?
3. Are any dimensions redundant after reviewers score all 10 samples?
4. Does the rubric explain why a contribution is useful but still `needs_revision`?
5. Are score disagreements anchored in evidence, or mostly reviewer taste?

## Pass Criteria For A Later T2 Review

T2 can move toward a stronger result when:

- reviewers can score most samples without private founder context,
- score disagreements identify a specific dimension rather than general confusion,
- the rubric surfaces useful tradeoffs between value, legitimacy, and capture risk,
- high scores do not imply automatic acceptance, reward, or governance movement,
- and low novelty or maintenance work can still receive appropriate coordination-value credit.

This fixture does not mark T2 passed. It gives the repo a repeatable object for testing the value rubric.
