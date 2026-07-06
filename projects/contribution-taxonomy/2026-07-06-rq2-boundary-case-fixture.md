---
artifact_type: contribution_taxonomy_boundary_case_fixture
status: draft_test_fixture
created: 2026-07-06
research_target: RQ2 contribution taxonomy / T1 contribution taxonomy pass
governance_role: internal_research_scaffold
constitutional: false
---

# RQ2 Contribution Taxonomy Boundary-Case Fixture

Status: draft research fixture, not adopted policy.

Purpose: pressure-test ambiguous contribution classification before real contributors depend on the taxonomy. This file does not change active contribution classes, proposal format, review states, review lanes, reviewer authority, governance rules, reward meaning, claim status, public posture, or any real contribution record.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ2
- `TESTS.md`, especially T1
- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `templates/contribution-log-schema.md`
- `projects/contribution-taxonomy/2026-07-01-t1-contribution-taxonomy-fixture.md`
- `projects/contribution-taxonomy/2026-07-02-rq2-review-path-map.md`

## Boundary Under Review

The current taxonomy names seven contribution classes:

- `research`
- `formalization`
- `protocol design`
- `review`
- `synthesis`
- `implementation`
- `maintenance`

The earlier T1 fixture checks whether reviewers can classify clear synthetic samples. The RQ2 review-path map checks how those classes might route through first-pass review. This fixture adds the missing middle: cases where two or more classes look plausible and the reviewer must preserve useful work without hiding policy movement, unsupported overclaim, or tool authority.

The useful result is not forcing every submission into one obvious label. The useful result is making ambiguity reviewable.

## Reviewer Exercise

For each boundary case, a reviewer should record:

- primary class,
- optional secondary class,
- likely first review state,
- evidence or rationale that would make the classification stronger,
- stop condition, if any,
- useful residue to preserve if the submission is narrowed or not accepted as-is.

These prompts are diagnostic aids only. They are not an active review procedure.

## Boundary Cases

| id | ambiguous submission shape | likely primary class | plausible secondary class | likely first review state | boundary problem | safe next review action | prohibited shortcut |
|---|---|---|---|---|---|---|---|
| RQ2-BC-01 | Compares two prior-art systems and rewrites the repo's value-rubric language to match one of them. | `research` for the comparison. | `synthesis` or `protocol design` for the rewrite. | `needs_revision` unless the source comparison and proposed wording are separated. | Useful evidence is bundled with a possible standard change. | Ask for a source-backed comparison first; defer wording adoption to a separate review. | Treat the rewrite as accepted just because the sources are useful. |
| RQ2-BC-02 | Defines new attack-profitability variables, then proposes an immediate anti-spam rule based on them. | `formalization` for the variables. | `protocol design` for the rule. | `triaged` for model review; governance-sensitive rule held separately if it changes authority or sanctions. | Testable model work is mixed with operational control. | Review variables and assumptions before any rule movement. | Let a model draft silently become policy. |
| RQ2-BC-03 | Finds a way to game the value rubric and proposes a mitigation that changes scoring weights. | `review` for the failure mode. | `protocol design` or `formalization` for the mitigation. | `triaged` for critique; mitigation needs a separate rubric review. | The critique may be valid even if the proposed fix is premature. | Preserve the attack path and request a bounded mitigation test. | Reject the whole contribution because the fix is not ready. |
| RQ2-BC-04 | Consolidates contribution-log, proposal-template, and issue-template fields into a checklist, but renames `review_state` meanings. | `synthesis` for the checklist. | `maintenance` if meaning is preserved; `protocol design` if meaning changes. | `needs_revision` unless field meanings are traced. | Usability cleanup can hide schema or review-state drift. | Require a source-to-checklist trace and isolate any changed meaning. | Classify as maintenance without checking semantics. |
| RQ2-BC-05 | Adds a validator that blocks entries missing required fields and labels blocked entries illegitimate. | `implementation` for the validator. | `review` for field-quality critique. | `needs_revision` because the tool overclaims authority. | Tool support is useful, but legitimacy cannot be automated by a field check. | Keep validation as a warning or evidence aid, with false-positive limits. | Let tooling decide final legitimacy. |
| RQ2-BC-06 | Submits an AI-assisted repo synthesis with source links, but no human statement of what changed or why. | `synthesis` if source-grounded. | `maintenance` if it only improves navigation. | `needs_revision`. | AI assistance may organize evidence, but the contribution still needs human review judgment. | Ask for affected surfaces, preserved meanings, and human review notes. | Treat AI fluency as evidence of correctness. |
| RQ2-BC-07 | Adds a well-sourced prior-art note, then claims the project has already solved contributor-governance legitimacy. | `research` for the source note. | `review` if it reveals an overclaim. | `needs_revision`. | A useful citation is mixed with unsupported public posture. | Preserve the citation and request removal or narrowing of the overclaim. | Accept the overclaim because the source is real. |
| RQ2-BC-08 | Fixes broken links, updates headings, and changes one sentence from "may be reviewed" to "will be accepted." | `maintenance` for link and heading fixes. | `protocol design` for the sentence change. | `needs_revision` unless the semantic change is removed. | Small wording can create hidden acceptance promises. | Accept or triage the cleanup separately from the semantic change. | Bundle semantic commitments into cleanup. |
| RQ2-BC-09 | Provides a strong red-team critique but includes one fabricated citation. | `review` for the critique if separable. | none for fabricated evidence. | `adversarial` or `not_accepted`, depending on severity and intent. | Evidence integrity can override otherwise useful reasoning. | Preserve any independently checkable critique only if provenance is repairable. | Normalize fabricated support as a minor formatting issue. |
| RQ2-BC-10 | Proposes a new contribution class for "community care" without examples, review targets, or capture risks. | `protocol design` because it changes taxonomy. | `synthesis` if it integrates existing needs. | `needs_revision`. | A taxonomy expansion may be valuable but is not justified without examples and boundaries. | Request sample submissions, affected review states, and abuse/failure cases. | Add a class because the label sounds legitimate. |

## Boundary Observations

- A primary class should name the main contribution value, not the highest-status label.
- Secondary classes are useful only when they explain a real review ambiguity.
- A contribution can contain useful residue even when the bundled policy move is not ready.
- Maintenance is narrow: it preserves meaning while improving usability.
- Implementation can support review but should not decide legitimacy.
- Research evidence and public-posture claims must be separable.
- Taxonomy expansion requires examples, review targets, and abuse cases before adoption.

## Later Review Questions

- Do reviewers need a lightweight `secondary_class` field, or would that create too much process burden?
- Should the proposal or log schema capture "useful residue" separately from `loss_notes`?
- Which ambiguous cases should be converted into reviewer exercises before a public contribution pilot?
- Should implementation contributions require an explicit false-positive and authority-limit note?
- Which wording changes are too semantic to qualify as maintenance?

## Later Review Criteria

This fixture can support a stronger RQ2/T1 result when:

- reviewers can classify boundary cases without private founder context;
- ambiguous submissions produce specific rationale instead of general uncertainty;
- useful residue is preserved without adopting premature policy;
- maintenance, synthesis, implementation, and protocol design remain distinguishable;
- and governance-sensitive or public-posture moves stop visibly rather than slipping through ordinary review.

This fixture does not mark T1 passed or RQ2 complete. It gives the repo a concrete ambiguity object for later reviewer testing.
