---
artifact_type: prior_art_source_packet
status: source_packet_prepared
created: 2026-07-04
test_target: T9 prior-art collision check
neighboring_system: Gitcoin public-goods quadratic funding
governance_role: non_adopted_evidence_packet
constitutional: false
collision_result: unresolved
claim_status_change_requested: false
---

# T9 Source Packet: Gitcoin Public-Goods Quadratic Funding

Status: source packet prepared; no collision verdict assigned.

Purpose: attach a source-backed packet for Gitcoin-style public-goods quadratic
funding so a later T9 review can compare mechanisms without private founder
context.

This file does not complete T9, assign a collision level, make a novelty
judgment, change claim status, change tests, accept or reject a contribution,
adopt reward logic, change governance, or create any legal, financial,
retained-value, public-posture, or contribution-record consequence.

## Packet Header

```yaml
packet_id: T9-PA-01-gitcoin-public-goods-quadratic-funding
neighboring_system: Gitcoin public-goods quadratic funding
contributor: Codex scheduled progress worker
date_prepared: 2026-07-04
target_claims_or_tests:
  - T9
  - C2
  - C3
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
| [Gitcoin: Quadratic Funding](https://gitcoin.co/mechanisms/quadratic-funding) | current official mechanism overview | Describes QF as a public-goods funding mechanism where many smaller contributors can increase matching allocations, with round operation, project applications, donations, sybil review, and fund distribution. |
| [Gitcoin: Grants Stack](https://gitcoin.co/apps/gitcoin-grants-stack) | official platform and practice source | Describes Gitcoin Grants Stack as open-source grants infrastructure for round configuration, project applications, community contributions, fund distribution, project profiles, and sybil-resistance integration. |
| [Gitcoin: Sybil Resistance in Quadratic Funding: 2024 Approaches](https://gitcoin.co/research/quadratic-funding-sybil-resistance) | limitation and attack-surface source | Describes why QF creates sybil incentives and names Passport, MACI, and continuing defenses as part of the arms race around fake identities and matching manipulation. |
| [Gitcoin: Gitcoin Citizens Round 1](https://gitcoin.co/case-studies/gitcoin-citizens-round-1-retroactive-quadratic-funding-for-community-contributions) | practice source for non-technical community contributions | Describes a retroactive QF round for non-technical community contributions, with applications, eligibility criteria, donor participation, and lessons about voter context, eligibility clarity, and setup friction. |
| [gitcoinco/quadratic-funding](https://github.com/gitcoinco/quadratic-funding) | historical implementation and concept source | Provides a historical open-source implementation and notes that it is out of date, which limits its use as current-practice evidence. |

## Minimum Evidence Checklist

| check | packet state | note |
|---|---|---|
| Stable source named | present | The Gitcoin QF mechanism page gives the current official mechanism overview. |
| Practice source named | present | Grants Stack and the Citizens Round case study show concrete program operation and infrastructure. |
| Limitation source or limitation note included | present | Gitcoin's sybil-resistance source names fake-identity incentives and ongoing defense limits. |
| Local target named | present | The packet targets T9, with C2/C3 as comparison context. |
| Mechanism axes touched | partial | The packet covers all axes lightly; later review should deepen rejected-application traces, appeal/contestability, and governance-transition sources. |
| Source versus inference separated | present | See the sections below. |
| Boundary statement included | present | This packet is evidence preparation only. |
| Revision path visible | present | The packet is `partial_ready`, not a verdict-bearing review. |

## Source-Supported Notes

- Gitcoin-style QF allocates matching funds according to community contribution
  patterns, giving broader contributor support more matching weight than a
  simple one-to-one match.
- Gitcoin rounds include project applications, community contributions, review
  or eligibility constraints, sybil review, and fund distribution.
- Grants Stack provides infrastructure for configuring rounds, receiving
  applications, operating community contribution flows, and distributing funds.
- Grants Stack supports multiple allocation mechanisms, including QF, direct
  grants, and retroactive funding.
- Project builders can maintain profiles and funding history across rounds.
- Gitcoin Passport and related mechanisms are used to gate or weight
  participation and reduce sybil influence.
- Gitcoin's sybil-resistance materials treat fake identities and coordinated
  manipulation as a live design problem, not a solved edge case.
- The Citizens Round used retroactive QF for non-technical community
  contributions and recorded challenges around voter context, eligibility
  clarity, and setup friction.
- The historical GitHub implementation is useful background for the mechanism
  lineage but is marked out of date, so it should not be treated as current
  operational evidence.

## Mechanism Notes

| axis | source evidence | reviewer inference for later review | uncertainty |
|---|---|---|---|
| contribution_unit | Gitcoin QF commonly works through projects, grants, applicants, profiles, and round eligibility. The Citizens Round included individuals and projects doing non-technical community work. | The unit appears broader than this repo's desired contribution-by-contribution record, but Gitcoin can represent non-code and community contributions at applicant or project level. | Need examples of application records that decompose specific contributions, team roles, rejected work, or partial value. |
| validation_path | Rounds use applications, eligibility criteria, program manager or operator configuration, community donations, sybil review, and fund distribution. | Validation blends eligibility screening with community allocation signal rather than a public reviewer rationale for each contribution. | Need sources showing application review notes, revision paths, appeals, or rejected-applicant explanations. |
| value_logic | QF converts donation breadth and amount into a matching allocation; Grants Stack also supports direct and retroactive mechanisms. | Value is operationalized as community support plus matching logic, with identity and anti-collusion adjustments. This strongly overlaps reward allocation but less clearly covers legitimacy of the underlying contribution record. | Need round-level formulas, examples of adjusted outcomes, and evidence of how qualitative impact context affects funding. |
| legitimacy_conditions | Gitcoin materials emphasize public rounds, project discovery, contribution flows, sybil resistance, and lessons about voter context and eligibility clarity. | Visibility and participation are strong, but contestability, voice after adverse outcomes, retained-record semantics, and bounded authority are not yet clear from this packet. | Need governance and dispute-process sources for applicants, donors, and round operators. |
| record_trace | Grants Stack supports project profiles and reusable funding history; round pages and case studies preserve program-level outcomes. | The trace appears strongest for project funding history and weaker for explicit loss notes or filtered value from rejected or under-rewarded contributions. | Need actual round records, application artifacts, and failed or revised submission examples. |
| retained_value | Participants may retain project profiles, funding history, community visibility, and received funds when selected. | Persistent funding history resembles retained recognition, but this packet does not show a contribution-level retained-right marker comparable to this repo's future-claim question. | Need evidence on profile portability, future eligibility, and whether rejected or low-funded contributions retain visible value. |
| reward_timing | Gitcoin QF usually allocates during a round; the Citizens Round used a retroactive QF design for demonstrated past contribution. | Gitcoin covers both present-round and retroactive reward timing, making it a strong comparison for reward mechanics but not necessarily for pre-reward legitimacy trace. | Need later review to separate standard QF, retroactive QF, and Grants Stack as platform infrastructure. |
| governance_transition | Grants Stack allows program operators, DAOs, communities, and foundations to run rounds with configurable criteria. | Gitcoin may distribute operation to round managers and communities, but this packet does not yet show founder-to-distributed power transition mechanics comparable to C6. | Need Gitcoin governance sources and round-operator authority boundaries before comparing transition design. |
| capture_model | Gitcoin explicitly names sybil attacks, collusion, coordinated clusters, Passport scoring, MACI, and related defenses. | Gitcoin is highly relevant to C4/T6/T9 because it treats matching manipulation as core mechanism risk. It may offer stronger attack-defense practice than this repo currently has. | Need sources on bribery, cartel behavior, donor coordination, appeal handling, and empirical false-positive/false-negative tradeoffs. |
| coupled_design | Gitcoin QF connects application intake, project profiles, public contribution, matching formulas, sybil defense, and fund distribution. | This is a strong module-overlap candidate and possibly a coupled-overlap candidate for funding mechanics. The local repo may differ by making contribution legitimacy, loss notes, retained records, and governance transition the object under test before reward. | Later review must compare whether Gitcoin's funding stack is a coupled legitimacy object or primarily a funding-allocation stack with identity and anti-fraud controls. |

## Directly Supported Versus Inferred

Directly supported by the packet sources:

- Gitcoin QF uses community contributions and matching funds to allocate public-goods support.
- Grants Stack provides practical infrastructure for rounds, applications, contributions, fund distribution, profiles, and sybil-resistance integration.
- Gitcoin treats sybil resistance and coordinated manipulation as active mechanism-design problems.
- Gitcoin Citizens Round 1 applied retroactive QF to non-technical community contributions and surfaced practical limitations around voter context, eligibility clarity, and setup friction.
- The historical Gitcoin QF implementation should not be used as current-practice evidence without newer protocol sources.

Reviewer inferences requiring later review:

- Gitcoin QF may overlap C2 because it couples intake, identity checks, allocation logic, funding, and public records.
- The likely overlap is at least `module_overlap`, but this packet does not assign that level.
- Gitcoin appears more mature around funding and sybil-defense practice than around contribution-level legitimacy trace, explicit loss notes, retained-record semantics, or governance-transition evidence.
- The repo's differentiator may be not "public-goods funding" but the pre-reward legitimacy path from raw contribution evidence to contestable accepted record.

## Follow-Up Questions For Later T9 Review

1. Do Gitcoin round records preserve enough visible rationale for rejected,
   revised, or low-funded applications to support adverse-decision legitimacy?
2. How are applicant appeals, disputes, eligibility challenges, or sybil-review
   false positives handled?
3. Does a project profile function as retained value, retained recognition, or
   only a reusable funding interface?
4. Which Gitcoin governance sources define round-operator authority,
   community authority, and rule-change authority?
5. Are QF anti-collusion defenses portable to contribution legitimacy review,
   or only to funding-allocation math?
6. Should the eventual collision review compare Gitcoin QF as a mechanism,
   Gitcoin Grants Stack as infrastructure, or Gitcoin Citizens as a
   retroactive community-contribution case?

## Readiness Assessment

Packet state: `partial_ready`.

Reason: the packet has official mechanism, platform, attack-surface, practice,
and historical implementation sources. It is good enough to support a later
mechanism comparison, but not enough to assign a collision level because
application-review traces, contestability, rejected-work records,
governance-transition mechanics, and retained-record semantics need better
source coverage.

Allowed next step:

- Add governance, round-record, application-review, and dispute-process sources,
  then fill the T9 collision-review scaffold for `T9-PA-01`.

Not allowed from this packet:

- claim-status movement;
- novelty, collision, or pass/fail verdict;
- reward-readiness decision;
- governance recommendation;
- live contribution acceptance or rejection;
- or public-posture change.
