---
artifact_type: prior_art_source_packet
status: source_packet_prepared
created: 2026-07-03
test_target: T9 prior-art collision check
neighboring_system: Optimism Retro Funding
governance_role: non_adopted_evidence_packet
constitutional: false
collision_result: unresolved
claim_status_change_requested: false
---

# T9 Source Packet: Optimism Retro Funding

Status: source packet prepared; no collision verdict assigned.

Purpose: attach a first source-backed packet for Optimism-style retroactive
public goods funding so a later T9 review can compare mechanisms without
private founder context.

This file does not complete T9, assign a collision level, make a novelty
judgment, change claim status, change tests, accept or reject a contribution,
adopt reward logic, change governance, or create any legal, financial,
retained-value, public-posture, or contribution-record consequence.

## Packet Header

```yaml
packet_id: T9-PA-02-optimism-retro-funding
neighboring_system: Optimism Retro Funding
contributor: Codex scheduled progress worker
date_prepared: 2026-07-03
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
| [Optimism Retro Funding 2025](https://optimism.io/blog/retro-funding-2025) | current official program direction | Describes 2025 shift toward continuous rewards, metrics-driven and human-guided evaluation, 850M OP dedicated to Retro Funding, and known 2024 reliability and measurement gaps. |
| [Optimism Community Hub: Retro Funding Round 4](https://github.com/ethereum-optimism/community-hub/blob/main/pages/citizens-house/rounds/retropgf-4.mdx) | official round design / practice source | Documents Round 4 scope, timeline, metrics-based badgeholder voting, median-based result calculation, reward caps/floors, public ballots, and badgeholder participation. |
| [Lessons learned from two years of Retroactive Public Goods Funding](https://gov.optimism.io/t/lessons-learned-from-two-years-of-retroactive-public-goods-funding/9239) | limitation and practice-reflection source | Summarizes learning across several rounds, including overwhelm in project-based voting, metrics limits, and lack of strong evidence that retroactive funding has superior outcomes yet. |
| [Evaluating Voting Design Vulnerabilities for Retroactive Funding](https://arxiv.org/abs/2505.16068) | formal limitation / vulnerability source | Reviews Optimism RetroPGF voting mechanisms and analyzes vulnerabilities in quadratic, mean, and median voting designs. |

## Minimum Evidence Checklist

| check | packet state | note |
|---|---|---|
| Stable source named | present | The official 2025 Optimism post gives current program direction. |
| Practice source named | present | The Round 4 Community Hub page records a concrete round design and process. |
| Limitation source or limitation note included | present | The OSO lessons-learned post and arXiv vulnerability paper both name unresolved measurement or voting-design issues. |
| Local target named | present | The packet targets T9, with C2/C3 as comparison context. |
| Mechanism axes touched | partial | The packet covers all axes lightly; later review should deepen retained-value, governance-transition, and capture-model evidence. |
| Source versus inference separated | present | See the sections below. |
| Boundary statement included | present | This packet is evidence preparation only. |
| Revision path visible | present | The packet is `partial_ready`, not a verdict-bearing review. |

## Source-Supported Notes

- Retro Funding rewards demonstrated impact after work has occurred, rather than funding only future promises.
- Optimism frames the program around the principle that positive impact to the Collective should lead to reward.
- The 2025 plan shifts from annual rounds toward ongoing impact evaluation and regular rewards.
- The 2025 plan explicitly combines onchain metrics with human expertise and qualitative feedback.
- In 2024, Retro Funding rewarded more than 400 builders with 20m OP across three rounds.
- The official 2025 post names reliability, predictability, accuracy, and evidence of ecosystem-growth effects as active improvement areas.
- Round 4 focused on onchain builders, used metrics-based badgeholder voting rather than direct project voting, made votes public after the voting period, and calculated results through a median-based process.
- Round 4 had eligibility requirements, a sign-up and application-review period, voting, result calculation, and grant delivery.
- The lessons-learned source reports that earlier rounds exposed voter overwhelm, weak differentiation among borderline projects, inconsistent lists, and limits of metrics-only evaluation.
- The arXiv vulnerability source treats Optimism RetroPGF voting mechanisms as analyzable for strategic or design vulnerabilities.

## Mechanism Notes

| axis | source evidence | reviewer inference for later review | uncertainty |
|---|---|---|---|
| contribution_unit | Retro Funding evaluates projects/builders and their demonstrated impact, with Round 4 focused on onchain builders. | The contribution unit appears coarser than this repo's desired individual contribution record, but it does represent completed work rather than promised work. | Need source detail on how project applications decompose team, individual, maintenance, research, or infrastructure contributions. |
| validation_path | Round 4 included application review and badgeholder voting; the 2025 plan combines metrics and human expertise. | Validation is mediated by eligibility, metrics, and badgeholder judgment rather than a public contribution-by-contribution rationale. | Need application-review criteria, reviewer notes, and appeal or revision mechanics if visible. |
| value_logic | Optimism uses impact evaluation, metrics, badgeholder preferences, median calculations, and reward-size constraints. | Value is strongly tied to demonstrated ecosystem impact and allocation mechanics, not to a local legitimacy trace from raw contribution evidence to accepted record. | Need round-specific formulas and examples of qualitative adjustment. |
| legitimacy_conditions | Round 4 made metric-weight ballots public after voting and aimed to reduce coercion/social pressure by having badgeholders vote on metrics instead of projects. | Visibility is stronger for ballot mechanics than for contributor-facing contestability or adverse-decision rationale. | Need sources on participant voice, challenge paths, and rejected-applicant explanations. |
| record_trace | Round pages and result-calculation links preserve process and results. | The trace is visible at round/project/allocation level, but may not preserve loss notes or filtered value from unsuccessful or under-rewarded contributions. | Need actual result records and rejected/low-reward application examples. |
| retained_value | Retro Funding provides OP rewards to selected projects/builders; Optimist Profiles provide persistent identity across the Collective. | Persistent identity and prior rewards may create durable recognition, but this is not the same as an explicit retained-value marker for each accepted contribution. | Need source detail on profile history, future eligibility, and whether non-funded contributions retain any claim. |
| reward_timing | The mechanism is retroactive and the 2025 direction aims for more continuous rewards. | This strongly overlaps the repo's reward-timing question, while differing from the repo's current no-reward pre-pilot boundary. | Need later review to compare retroactive reward after visible impact against this repo's still-non-promissory contribution log. |
| governance_transition | Badgeholders and the Citizens' House participate in allocation decisions; Retro Funding is part of the Optimism Collective. | Retro Funding has a distributed allocation body, but this packet does not yet show founder-to-distributed transition mechanics comparable to C6. | Need governance sources for badgeholder selection, removal, powers, and Collective governance evolution. |
| capture_model | Official sources name coercion/social-pressure concerns and metrics-based design choices; limitation sources name voting-design and measurement issues. | Capture concern is active, especially around voting design, metric choice, expertise, and allocation reliability. | Need sources on sybil resistance, bribery/collusion controls, badgeholder incentives, and application screening. |
| coupled_design | Retro Funding connects impact evidence, voting or metrics, public result calculation, rewards, and Collective governance context. | This is the strongest overlap candidate: it appears more coupled than a simple grant program, but its unit of account and legitimacy trace may differ from this repo's contribution-record hypothesis. | Later review needs a verdict-bearing comparison against C2/C3, after richer governance and rejected-work sources are attached. |

## Directly Supported Versus Inferred

Directly supported by the packet sources:

- Retro Funding is retroactive and rewards demonstrated impact.
- Optimism uses human and metrics-based evaluation in current program design.
- Round 4 used metrics selected and weighted by badgeholders, public ballots, median calculations, and eligibility constraints.
- Optimism's own 2025 planning names reliability, predictability, accuracy, and measurement of program success as open problems.
- Independent formal analysis has begun treating RetroPGF voting designs as vulnerable to mechanism-level problems.

Reviewer inferences requiring later review:

- Optimism Retro Funding may overlap C2 because it binds impact evidence, evaluation, reward allocation, and governance context.
- The overlap may be `module_overlap` or `coupled_overlap`, but this packet does not decide which.
- Optimism appears to operate at project or builder granularity more than contribution-record granularity.
- The repo's stronger differentiator may be contestable contribution trace, explicit loss notes, and retained-record semantics rather than retroactive reward itself.

## Follow-Up Questions For Later T9 Review

1. Does Optimism preserve enough visible rationale for unsuccessful, revised, or under-rewarded applications to satisfy this repo's legitimacy-trace burden?
2. Are badgeholder ballots and result calculations contestable by contributors, or mainly transparent after the fact?
3. Does Optimist Profile history function like a retained-record layer, or only as ecosystem identity?
4. Which governance sources explain how badgeholders are selected, constrained, and replaced?
5. Do the voting-design vulnerability findings imply capture risks this repo should model before any reward-readiness move?
6. Should the eventual collision review compare Optimism Round 4 only, the 2025 continuous-rewards direction only, or the program across multiple rounds?

## Readiness Assessment

Packet state: `partial_ready`.

Reason: the packet has stable program, practice, limitation, and vulnerability
sources. It is good enough to support a later mechanism comparison, but not
enough to assign a collision level because governance-transition mechanics,
contestability, rejected-work traces, and retained-record semantics still need
better source coverage.

Allowed next step:

- Add governance and rejected-application/process sources, then fill the T9
  collision-review scaffold for `T9-PA-02`.

Not allowed from this packet:

- claim-status movement;
- novelty, collision, or pass/fail verdict;
- reward-readiness decision;
- governance recommendation;
- live contribution acceptance or rejection;
- or public-posture change.
