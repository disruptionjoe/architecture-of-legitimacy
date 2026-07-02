# T1 Contribution Taxonomy Fixture

Status: synthetic test fixture.

Purpose: pressure-test whether the current contribution classes in `CONTRIBUTION-STANDARDS.md` are usable without private founder context.

This file is not a live contribution log, acceptance record, reward record, or governance decision. All submissions below are invented examples for T1 testing.

## Test Question

Can reviewers classify sample work into the current contribution classes with enough consistency to run a first public contribution workflow?

Current classes under test:

- `research`
- `formalization`
- `protocol design`
- `review`
- `synthesis`
- `implementation`
- `maintenance`

## Use Pattern

For a dry run, have each reviewer classify each sample before reading the expected classification.

Record:

- primary class,
- optional secondary class,
- likely first review state,
- rationale,
- ambiguity or missing evidence.

The useful result is not unanimous agreement. The useful result is seeing which boundaries are stable and which ones need clarification before real contributions depend on them.

## Synthetic Samples

| id | sample submission | expected primary class | plausible secondary class | likely first review state | ambiguity to watch |
|---|---|---|---|---|---|
| T1-SAMPLE-01 | Compares the contribution workflow to three neighboring public-goods funding systems and identifies where each system handles contestability differently. | `research` | `review` | `needs_revision` if citations or mechanism-level comparisons are thin; otherwise `triaged` for substantive review. | A list of systems is not enough. The classification depends on whether the comparison explains mechanisms and limits. |
| T1-SAMPLE-02 | Defines variables for the toy payoff model and gives two simple contributor types with collaborate/defect payoff assumptions. | `formalization` | `research` | `triaged` for model review. | If the variables are asserted without definitions or failure conditions, reviewers may treat it as incomplete formalization. |
| T1-SAMPLE-03 | Proposes a monthly review cadence with triage, substantive review, contestation, and synthesis stages. | `protocol design` | `synthesis` | `triaged` for workflow review. | If the proposal also rewrites governance authority, it crosses from workflow design into governance review. |
| T1-SAMPLE-04 | Shows that the proposed value rubric can be gamed by splitting one contribution into many small submissions. | `review` | `protocol design` | `triaged` for threat and mitigation review. | A critique with no mitigation can still be review work, but it should name the affected rule or rubric. |
| T1-SAMPLE-05 | Consolidates accepted contribution-log fields, issue-template fields, and review states into a single checklist for reviewers. | `synthesis` | `maintenance` | `triaged` if it accurately preserves source meaning. | If it silently changes field meaning, it becomes protocol design or policy work and needs closer review. |
| T1-SAMPLE-06 | Adds a script that checks contribution-log entries for required fields and internal links. | `implementation` | `maintenance` | `triaged` for usefulness and false-positive review. | Tooling should support the research workflow without turning validation into final legitimacy judgment. |
| T1-SAMPLE-07 | Fixes broken Markdown links and aligns terminology from `review path` to `review state` without changing policy. | `maintenance` | `synthesis` | `accepted` or `triaged`, depending on repo procedure. | Reviewers should confirm the change is semantic cleanup, not hidden policy movement. |
| T1-SAMPLE-08 | Suggests that all accepted contributors should immediately receive voting power over roadmap decisions. | `protocol design` | none | `needs_revision` or `not_accepted` unless it names capture risks, phase constraints, and governance boundaries. | This touches governance transfer and cannot be accepted as a casual workflow tweak. |
| T1-SAMPLE-09 | Submits an AI-generated summary of the whole repo with no sources, no changed claim, and no review target. | `maintenance` only if it improves navigation; otherwise none | `synthesis` if it accurately integrates sources | `needs_revision` or `not_accepted`. | Synthesis requires an integration gain. A generic summary may add noise. |
| T1-SAMPLE-10 | Adds a prior-art citation but also claims the repo has already solved decentralized governance. | `research` for the citation component | `review` if it exposes an overclaim | `needs_revision` because the submission mixes useful evidence with prohibited overclaim. | Reviewers should separate useful evidence from unsupported public-posture claims. |

## Boundary Observations

- Research and review overlap when a source-backed comparison exposes a flaw.
- Synthesis and maintenance overlap when cleanup improves reviewer usability without changing meaning.
- Protocol design becomes governance-sensitive when it changes authority, transfer, appeal, or contributor rights.
- Implementation contributions should be judged by whether they support review clarity, not by tool polish alone.
- AI-assisted drafting should be reviewed for source fidelity and participant voice, not treated as neutral authority.

## Pass Criteria For A Later T1 Review

T1 can move toward a stronger result when:

- reviewers can classify most samples without private founder context,
- disagreements identify a specific class boundary rather than general confusion,
- synthetic examples cover accepted, revision, and not-accepted paths,
- governance-sensitive samples are recognized as requiring review rather than casual acceptance,
- and the taxonomy can represent non-code work without collapsing everything into research or maintenance.

This fixture does not mark T1 passed. It gives the repo a repeatable object for testing the taxonomy.
