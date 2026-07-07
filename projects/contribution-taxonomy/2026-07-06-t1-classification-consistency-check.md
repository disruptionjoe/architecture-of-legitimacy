---
artifact_type: t1_classification_consistency_check
status: draft_review_scaffold
created: 2026-07-06
research_target: T1 contribution taxonomy / RQ2 contribution taxonomy
governance_role: internal_research_scaffold
constitutional: false
---

# T1 Classification Consistency Check

Status: draft research scaffold, not adopted policy.

Purpose: make the T1 success signal reviewable by defining how to compare
multiple reviewer classifications of the same synthetic contribution samples.
This file does not change active contribution classes, proposal format, review
states, review lanes, reviewer authority, contribution standards, governance
rules, reward meaning, claim status, public posture, test pass/fail state, or
any real contribution record.

## Source Surfaces Used

- `TESTS.md`, especially T1
- `RESEARCH-AGENDA.md`, especially RQ2
- `projects/contribution-taxonomy/2026-07-01-t1-contribution-taxonomy-fixture.md`
- `projects/contribution-taxonomy/2026-07-02-rq2-review-path-map.md`
- `projects/contribution-taxonomy/2026-07-06-rq2-boundary-case-fixture.md`

## Boundary Under Review

T1 asks whether contributors can classify sample work consistently. The
existing taxonomy fixture provides samples and expected classifications, while
the RQ2 boundary-case fixture exposes ambiguous cases. The remaining gap is the
comparison step: when two reviewers classify the same sample differently, what
kind of disagreement is useful evidence and what kind signals taxonomy failure?

This scaffold treats consistency as a review signal, not a pass/fail verdict.
It should help a later reviewer see whether disagreements are specific,
bounded, and repairable before any public contribution pilot depends on the
taxonomy.

## Suggested Reviewer Record Shape

For each synthetic sample, each reviewer would record:

| field | purpose | caution |
|---|---|---|
| `sample_id` | Names the fixture case under review. | Use synthetic IDs only; this is not a live contribution record. |
| `primary_class` | Names the main contribution value. | Do not choose the highest-status label by default. |
| `secondary_class` | Explains a real ambiguity, if present. | Leave blank when it adds noise. |
| `first_review_state` | Names the likely first disposition. | This is diagnostic, not active workflow policy. |
| `classification_rationale` | Gives the reason a later reviewer can compare. | A label without rationale is not enough evidence. |
| `stop_condition` | Flags governance, reward, rights, public-posture, or evidence-integrity stops. | Do not resolve the stop inside this exercise. |
| `useful_residue` | Names what remains useful if the submission is narrowed or not accepted as-is. | Do not turn residue into reward or rights language. |
| `confidence` | Marks whether the classification felt clear, mixed, or weak. | Confidence is not authority. |

## Consistency Signals

| signal | useful meaning | example reading |
|---|---|---|
| Primary-class match | Reviewers see the same main contribution value. | Two reviewers classify `T1-SAMPLE-02` as `formalization` because variables and assumptions are the contribution core. |
| Compatible primary/secondary split | Reviewers disagree on order but name the same boundary. | One reviewer marks `review` primary and another marks `protocol design` primary for a rubric-gaming mitigation, but both identify the critique/fix split. |
| Shared stop condition | Reviewers notice the same governance, reward, rights, public-posture, or evidence-integrity boundary. | Reviewers classify `T1-SAMPLE-08` differently but both stop ordinary review because it shifts roadmap voting power. |
| Rationale convergence | Reviewers use different labels but cite the same evidence need. | Both ask for source relevance notes before a prior-art comparison can move. |
| Useful-residue convergence | Reviewers preserve the same useful part of a mixed submission. | Both keep a citation or failure mode while rejecting an unsupported overclaim. |

## Failure Signals

| failure signal | why it matters | likely repair target |
|---|---|---|
| Class collapse | Most samples become `research`, `synthesis`, or `maintenance` without clear boundaries. | Clarify class definitions or sample prompts before real review. |
| Private-context dependency | Reviewers need founder knowledge to decide the class. | Add public context, examples, or source links to the fixture. |
| Hidden policy movement | A reviewer classifies semantic or authority-changing edits as maintenance. | Strengthen maintenance/protocol-design boundary examples. |
| Tool-authority confusion | Implementation work is treated as final legitimacy judgment. | Add implementation false-positive and authority-limit prompts. |
| Public-posture leakage | Useful evidence is bundled with claims that the project has already proven more than it has. | Separate evidence preservation from overclaim removal. |
| No rationale trail | Reviewers can pick labels but cannot explain the distinction. | Add a rationale field or smaller boundary cases. |

## First Comparison Packet

The first useful packet should stay small. A later dry run could compare
reviewer outputs for these synthetic cases:

| fixture case | why include it | consistency question |
|---|---|---|
| `T1-SAMPLE-03` | Protocol-design proposal with synthesis overlap. | Do reviewers separate workflow design from governance movement? |
| `T1-SAMPLE-05` | Checklist synthesis with maintenance overlap. | Do reviewers check whether source meanings are preserved? |
| `T1-SAMPLE-06` | Implementation support for contribution-log validation. | Do reviewers keep tooling subordinate to human review judgment? |
| `T1-SAMPLE-08` | Immediate voting-power proposal. | Do reviewers stop governance-sensitive movement visibly? |
| `T1-SAMPLE-10` | Useful citation mixed with unsupported overclaim. | Do reviewers preserve evidence while rejecting public-posture leakage? |
| `RQ2-BC-04` | Checklist that renames `review_state` meanings. | Do reviewers catch semantic drift hidden in cleanup? |
| `RQ2-BC-05` | Validator that labels blocked entries illegitimate. | Do reviewers separate implementation utility from legitimacy authority? |
| `RQ2-BC-08` | Link cleanup bundled with an acceptance promise. | Do reviewers distinguish maintenance from policy commitment? |

This packet is intentionally diagnostic. It should not be used to mark T1
passed, complete RQ2, accept a real contribution, or update contribution
standards.

## Candidate Comparison Notes

When reviewer outputs differ, the later reviewer should classify the
disagreement before trying to repair it:

| disagreement type | interpretation | possible next step |
|---|---|---|
| Benign label ordering | Reviewers identify the same two classes but rank them differently. | Keep primary/secondary fields and clarify rationale. |
| Boundary ambiguity | Reviewers disagree because the submission genuinely mixes contribution types. | Split the submission or ask for a narrower proposal. |
| Evidence insufficiency | Reviewers cannot classify because source, target, or rationale is missing. | Route to `needs_revision` in a later live workflow; here, record the missing evidence. |
| Governance-sensitive drift | Reviewers disagree because the work changes authority, rights, reward, appeal, or public posture. | Stop ordinary review and preserve only the diagnostic residue. |
| Taxonomy failure | Reviewers cannot explain the difference even after evidence is named. | Revise class definitions or add new examples before real contributors depend on the taxonomy. |

## Later Review Criteria

This scaffold can support a stronger T1/RQ2 result when:

- most clear samples produce primary-class agreement or compatible
  primary/secondary splits;
- ambiguous samples produce specific rationale rather than general confusion;
- reviewers consistently catch governance-sensitive, reward-sensitive,
  rights-sensitive, public-posture, and evidence-integrity stops;
- maintenance, synthesis, implementation, protocol design, research, review,
  and formalization remain distinguishable under mixed cases;
- and useful residue can be preserved without adopting premature policy or
  changing real contribution records.

This scaffold does not mark T1 passed or RQ2 complete. It gives the repo a
compact comparison layer for a later reviewer dry run.
