---
artifact_type: prior_art_source_packet
status: source_packet_prepared
created: 2026-07-07
test_target: T9 prior-art collision check
neighboring_system: Python maintainer governance and BDFL transition
governance_role: non_adopted_evidence_packet
constitutional: false
collision_result: unresolved
claim_status_change_requested: false
---

# T9 Source Packet: Python Maintainer Governance

Status: source packet prepared; no collision verdict assigned.

Purpose: attach a source-backed packet for the T9-PA-05 open-source maintainer
governance lane using Python's governance transition, contribution review, core
team, and triage documentation as one named project example.

This file does not complete T9, assign a collision level, make a novelty
judgment, change claim status, change tests, accept or reject a contribution,
adopt maintainer-authority policy, change governance, or create any legal,
financial, retained-value, reward, public-posture, or contribution-record
consequence.

## Packet Header

```yaml
packet_id: T9-PA-05-python-maintainer-governance
neighboring_system: Python maintainer governance and BDFL transition
contributor: Codex scheduled progress worker
date_prepared: 2026-07-07
target_claims_or_tests:
  - T9
  - C1
  - C2
  - C3
  - C6
review_state: source_packet_prepared
source_packet_ready: false
source_packet_readiness: partial_ready
collision_result: unresolved
candidate_collision_level: not_assigned
claim_status_change_requested: false
```

## Sources

| source | role in packet | notes |
|---|---|---|
| [PEP 13: Python Language Governance](https://peps.python.org/pep-0013/) | official governance source | Defines the steering council model, core team role, council election, conflict-of-interest cap, no-confidence path, core-team membership criteria, and the history from Guido van Rossum's BDFL role to the elected steering council. |
| [PEP 8000: Python Language Governance Proposal Overview](https://peps.python.org/pep-8000/) | BDFL-transition and governance-selection source | Summarizes the governance-model selection process after Guido's retirement and lists alternative governance proposals considered before PEP 13 codified the selected model. |
| [Python Developer's Guide: Lifecycle of a pull request](https://devguide.python.org/getting-started/pull-request-lifecycle/) | contributor submission workflow source | Describes the contributor path for branch creation, tests, pull requests, review comments, conflict resolution, and updating a PR. |
| [Python Developer's Guide: Accepting pull requests](https://devguide.python.org/core-team/committing/) | maintainer review and merge practice source | Gives core-team guidance for assessing whether a PR is ready, checking related discussions, compatibility, tests, labels, CLA status, documentation, and merge behavior. |
| [Python Developer's Guide: How to join the core team](https://devguide.python.org/core-team/join-team/) | role-selection and authority-transition source | Describes how sustained contributors may gain commit privileges through nomination, poll, steering-council non-veto, account provisioning, and public team-log update. |
| [Python Developer's Guide: Triage Team](https://devguide.python.org/triage/triage-team/) | delegated review and limitation source | Describes triage-team responsibilities, PR and issue classification, coordination with core developers, closure guidance, and contributor-care norms. |

## Minimum Evidence Checklist

| check | packet state | note |
|---|---|---|
| Stable source named | present | PEP 13 is the current official governance reference for Python. |
| Practice source named | present | The Developer Guide covers contributor pull-request lifecycle and core-team merge assessment. |
| Transition source named | present | PEP 13 and PEP 8000 both document the BDFL-to-governance-model transition context. |
| Role-selection source named | present | PEP 13 and the Developer Guide describe core-team membership and commit-privilege paths. |
| Limitation source or limitation note included | present | PEP 13 names conflict-of-interest and no-confidence mechanisms; the triage guide names closure limits and core-developer consultation boundaries. |
| Local target named | present | The packet targets T9, with C1/C2/C3/C6 as comparison context. |
| Mechanism axes touched | partial | The packet covers all axes lightly; later review should inspect concrete PR decisions, adverse traces, and public rationale examples. |
| Source versus inference separated | present | See the sections below. |
| Boundary statement included | present | This packet is evidence preparation only. |
| Revision path visible | present | The packet is `partial_ready`, not a verdict-bearing review. |

## Source-Supported Notes

- Python now has a steering-council governance model rather than a continuing
  BDFL model.
- PEP 13 names a five-person steering council with broad project authority,
  including PEP decisions, code-of-conduct enforcement, asset coordination with
  the PSF, and delegation to subcommittees or processes.
- PEP 13 also constrains the council: it cannot change PEP 13 or core-team
  membership except through the mechanisms in that PEP.
- The council is elected by the core team, with conflict-of-interest limits on
  employer concentration.
- PEP 13 includes removal and accountability mechanisms, including ejection of
  core team members in exceptional circumstances and no-confidence votes
  against council members or the whole council.
- PEP 13 defines the core team as trusted volunteers who manage Python,
  participate in formal votes, and hold authority over Python project
  infrastructure.
- PEP 13 recognizes non-code contributions such as triage, review, support,
  design, infrastructure, outreach, and domain expertise as possible paths to
  core-team membership.
- Core-team membership requires a core-team vote with a two-thirds positive
  threshold and steering-council non-veto.
- PEP 8000 records a formal governance-selection process after Guido van
  Rossum's retirement, including several alternative governance proposals.
- The pull-request lifecycle guide describes a public contribution path through
  fork/branch work, local tests, pull request creation, review comments, updates,
  and conflict resolution.
- The accepting-pull-requests guide instructs core-team reviewers to check
  related discussions, target branch, acceptability, test status,
  compatibility, labels, CLA status, and documentation before merging.
- The same guide says merge authority remains with core team members and points
  to pull requests and issues as durable investigation records.
- The core-team join guide describes commit privileges as an earned role after
  consistent quality contributions, with a mentor-like offer, poll, steering
  council non-veto, account provisioning, and team-log update.
- The triage-team guide delegates issue and PR classification, labeling,
  notifying core developers, reviewing PRs, assisting contributors, and limited
  PR closure ability to triagers.
- The triage-team guide distinguishes triager authority from core-developer
  authority by asking triagers to consult core developers when unsure about PR
  closure.

## Mechanism Notes

| axis | source evidence | reviewer inference for later review | uncertainty |
|---|---|---|---|
| contribution_unit | Python recognizes code, docs, tests, triage, review, outreach, infrastructure, design, support, and domain expertise as meaningful contributions. | Python is a strong comparison for contribution classes broader than code, especially sustained maintenance and review labor. | Need concrete examples of how non-code contributions are recorded, evaluated, and later retrieved during membership or authority decisions. |
| validation_path | Contributors submit PRs; reviewers assess related discussions, branch target, tests, compatibility, documentation, labels, CLA status, and readiness before merge. | Python has a mature public PR validation path, but source evidence here mostly names reviewer checks rather than contributor-facing rationale minimums for rejected, delayed, or heavily revised work. | Need actual PR traces and issue discussions to test adverse-decision visibility. |
| value_logic | Core-team membership depends on consistent quality contributions and constructive collaboration; PR acceptance depends on fit, tests, compatibility, documentation, and project readiness. | Value is mediated through maintainer judgment and sustained trust rather than a numerical rubric or reward formula. | Need evidence about borderline cases, competing reviewer judgments, and how project-direction fit is explained to contributors. |
| legitimacy_conditions | PEP 13 names elections, no-confidence votes, conflict-of-interest limits, core-team voting, council constraints, delegation, and consensus-seeking norms. | Python has stronger formal bounded-authority machinery than many open-source projects, and it directly pressures this repo's C6 founder-transition burden. | Need evidence about participant voice below core-team status, rejected-contributor contestability, and practical visibility of council or core-team decisions. |
| record_trace | PRs, issues, PEPs, governance PEPs, team logs, and public docs preserve parts of the contribution and authority trace. | The trace is likely strong for accepted PRs, governance changes, and core-team membership, but weaker for work that is closed, abandoned, rejected, or only informally valuable. | Need adverse PR examples, closed issue histories, and examples of non-code contribution recognition. |
| retained_value | Contributors may retain commit history, PR history, issue participation, authorship, reputation, and in some cases core-team or triage-team roles. | Python gives durable recognition and authority for some contributors, but this packet does not show an explicit retained-value marker for partial, rejected, or non-merged work. | Need source-backed comparison of credit, AUTHORS, NEWS, release notes, team logs, and closed PR histories. |
| reward_timing | The packet sources focus on authority, recognition, and process, not direct payment or tokenized reward. | Python is more relevant to legitimacy, role authority, and governance transition than to direct reward-readiness mechanics. | Need separate funding, sponsorship, PSF, grants, or employment sources before comparing reward logic. |
| governance_transition | PEP 8000 records the post-BDFL governance-selection process; PEP 13 records the selected steering-council model and continuing election/amendment mechanisms. | Python is a strong named BDFL-to-council transition example and should pressure any local claim that founder-led transition design is novel merely because it is explicit. | Need later review to compare whether Python's mature language-governance transition maps to a small public research repo with contribution/reward coupling. |
| capture_model | PEP 13 includes employer-concentration limits and no-confidence paths; triage guidance limits unilateral closure in uncertain cases. | Python names several non-capture countermeasures, but this packet does not yet cover sponsor pressure, employer dominance beyond the council cap, maintainer burnout, or dependency leverage. | Need incident, burnout, sponsorship, or governance-debate sources before treating capture coverage as mature. |
| coupled_design | Python connects contribution workflow, reviewer authority, core-team membership, steering-council governance, BDFL transition, and public governance records. | The overlap with this repo is strongest for maintainer authority and governance transition, moderate for contribution legitimacy trace, and weak for reward or retained-value rights. | Later review must decide whether Python is module overlap, coupled overlap, or stronger formalization for the governance half of the local stack. |

## Directly Supported Versus Inferred

Directly supported by the packet sources:

- Python uses an elected steering council model documented in PEP 13.
- Python's current governance model was selected after Guido van Rossum stepped
  down from the BDFL role.
- PEP 13 defines core-team voting, steering-council election, conflict-of-interest
  limits, no-confidence votes, and core-team membership criteria.
- Python's public contribution workflow uses pull requests, tests, review
  comments, and updates before merge.
- Core-team members have merge authority and are asked to assess readiness,
  compatibility, tests, documentation, CLA status, and related discussions.
- The triage team can classify and review issues and PRs, assist contributors,
  and close some low-likelihood PRs, while consulting core developers when
  uncertain.

Reviewer inferences requiring later review:

- Python may create stronger pressure on C6 than the existing funding and
  knowledge-validation packets because it is a documented BDFL-to-council
  transition in a mature open-source project.
- Python may be a `coupled_overlap` candidate for maintainer authority plus
  contribution trace plus governance transition, but this packet does not assign
  that level.
- Python appears weaker as evidence for direct reward logic, retained-value
  rights, and contribution-level loss-note semantics.
- The local repo's differentiator may be the attempt to bind legitimacy trace,
  retained-value ambiguity, reward-readiness gating, and governance transition
  before a live contribution pilot, rather than open-source contribution review
  or maintainer succession alone.

## Follow-Up Questions For Later T9 Review

1. Do Python PR and issue records preserve enough visible rationale for closed,
   delayed, rejected, or heavily revised contributions to satisfy this repo's
   legitimacy-trace burden?
2. How are non-code contributions, review labor, triage, and infrastructure work
   recorded before a contributor becomes a triager or core-team member?
3. Does the core-team membership process function as retained recognition,
   retained value, governance standing, or a separate authority credential?
4. Which parts of Python's BDFL-to-council transition are portable to a small
   founder-led research repo, and which depend on Python's existing scale,
   community, and PSF context?
5. Do conflict-of-interest and no-confidence mechanisms cover only governance
   capture, or do they help with contribution-review capture too?
6. Should the later collision review compare Python alone, compare Python
   against another BDFL project, or use Python as the BDFL-transition anchor
   inside the broader T9-PA-05 maintainer-governance lane?

## Readiness Assessment

Packet state: `partial_ready`.

Reason: the packet has official governance, transition, contribution-workflow,
core-team role-selection, maintainer-review, and triage sources. It is good
enough to support a later mechanism comparison, but not enough to assign a
collision level because concrete adverse PR traces, non-code contribution
recognition examples, sponsor or employer pressure evidence, reward-adjacent
sources, and retained-value semantics still need better source coverage.

Allowed next step:

- Add one or two concrete PR/issue traces and a source on non-code contribution
  recognition or project sponsorship, then fill the T9 collision-review scaffold
  for `T9-PA-05`.

Not allowed from this packet:

- claim-status movement;
- novelty, collision, or pass/fail verdict;
- maintainer-authority or governance recommendation;
- reward-readiness decision;
- live contribution acceptance or rejection;
- public-posture change;
- or retained-value, legal, financial, reward, governance, or contribution
  commitments.

## Boundary Notes

- No prior-art collision verdict has been made.
- No novelty claim has been accepted, rejected, narrowed, or strengthened.
- No claim status changed.
- No governance rule changed.
- No public posture changed.
- No T9 pass/fail state changed.
- No real contribution was submitted, accepted, revised, rejected, contested, or
  rewarded.
- No reward, retained-value, legal, or financial promise is created.
