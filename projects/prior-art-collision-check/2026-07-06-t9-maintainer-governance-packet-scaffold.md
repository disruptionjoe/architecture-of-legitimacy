---
artifact_type: prior_art_source_packet_scaffold
status: source_packet_scaffold
created: 2026-07-06
test_target: T9 prior-art collision check
neighboring_system: Open-source maintainer governance and BDFL models
governance_role: non_adopted_review_preparation
constitutional: false
collision_result: unresolved
claim_status_change_requested: false
---

# T9 Maintainer Governance Packet Scaffold

Status: source-packet scaffold; no external source claims attached.

Purpose: prepare the T9-PA-05 comparison lane for open-source maintainer
governance and BDFL-style authority models before a later reviewer attaches
source evidence.

This file does not complete T9, attach sources, assign a collision level, make a
novelty judgment, change claim status, change tests, accept or reject a
contribution, adopt governance, change public posture, or create any legal,
financial, retained-value, reward, contribution-record, or maintainer-authority
consequence.

## Packet Header

```yaml
packet_id: T9-PA-05-open-source-maintainer-governance
neighboring_system: Open-source maintainer governance and BDFL models
contributor: Codex scheduled progress worker
date_prepared: 2026-07-06
target_claims_or_tests:
  - T9
  - C1
  - C2
  - C3
  - C6
review_state: source_packet_scaffold
source_packet_ready: false
source_packet_readiness: sources_required
collision_result: unresolved
candidate_collision_level: not_assigned
claim_status_change_requested: false
```

## Why This Lane Matters

The existing T9 scaffold names open-source maintainer governance and BDFL models
as a neighboring system because maintainers already accept, reject, merge,
route, and explain contributions while retaining project-direction authority.

That adjacency creates a sharp prior-art question:

```text
Does explicit maintainer authority plus public contribution history already
solve the founder-led legitimacy problem, or does it leave unresolved gaps
around contestability, retained value, reward readiness, governance transition,
and capture monitoring?
```

This scaffold prepares that comparison without deciding it.

## Source Packet Needed

A later source-backed packet should use visible sources and separate source
evidence from reviewer inference.

| source slot | minimum source needed | why it matters |
|---|---|---|
| Project governance example | One official project governance or maintainer-authority document from a mature open-source project. | Shows how authority is named, constrained, delegated, or retained. |
| Contribution review practice | One contributor guide, pull-request policy, review process, or documented merge workflow. | Shows how submissions move from attempt to accepted, revised, rejected, or closed. |
| Authority transition or role selection | One source explaining maintainer appointment, release authority, committee membership, delegation, succession, or BDFL transition. | Tests whether founder or maintainer power becomes bounded and transferable. |
| Limitation or failure-mode source | One critique, governance incident, maintainer-burnout analysis, appeal/dispute example, or project postmortem. | Prevents maintainer governance from being treated as solved simply because it is familiar. |

If one source covers multiple slots, the packet should still name which evidence
role it plays and what remains missing.

## Mechanism Axes To Fill

| axis | evidence to attach later | review hazard to avoid |
|---|---|---|
| contribution_unit | What counts as a contribution: code, docs, issues, review, release work, design, community support, or maintenance. | Treating "pull request" as the whole contribution universe. |
| validation_path | How work is triaged, reviewed, revised, accepted, merged, rejected, or closed. | Confusing public merge state with visible legitimacy rationale. |
| value_logic | How maintainers judge importance, quality, fit, risk, timing, and project direction. | Treating maintainer taste as illegitimate or treating it as self-justifying. |
| legitimacy_conditions | What visibility, contestability, voice, exit, bounded authority, non-capture, and adaptive rule-change mechanisms exist. | Assuming openness to contribution equals legitimacy of review. |
| record_trace | Whether a later participant can reconstruct why a contribution was accepted, delayed, revised, or rejected. | Ignoring private maintainer context, closed discussions, or compressed rationale. |
| retained_value | Whether contributors retain visible credit, authorship, reputation, release notes, future eligibility, governance standing, or other durable value. | Treating Git history or profile reputation as automatically equivalent to retained value. |
| reward_timing | Whether reward is absent, indirect, reputational, sponsorship-mediated, bounty-based, retroactive, or governance-linked. | Letting reward mechanics dominate before contribution legitimacy is established. |
| governance_transition | How authority moves from founder to maintainers, committee, foundation, voters, or other bodies, if it moves at all. | Calling a project decentralized because multiple maintainers exist. |
| capture_model | How the project handles maintainer capture, sponsor pressure, employer dominance, commit-bit concentration, dependency leverage, hostile forks, or burnout. | Treating capture as only economic or only adversarial, rather than also procedural and social. |
| coupled_design | Whether contribution review, record trace, authority, value logic, reward or recognition, and governance transition are designed as one object. | Overstating overlap because isolated open-source mechanisms resemble local modules. |

## Source Versus Inference Template

Use this section only after sources are attached.

```yaml
directly_supported_by_sources:
  - ""
reviewer_inferences:
  - ""
weakest_axis:
  - ""
missing_evidence:
  - ""
candidate_follow_up:
  - ""
```

## First Packet Shape

A good first packet should be narrower than "open source" as a whole.

Preferred shapes:

- one named project with mature contribution and governance documentation;
- one BDFL-to-governance transition example;
- one foundation- or committee-governed project with visible maintainer roles;
- or one maintained library with clear merge authority, contribution review, and
  role-selection documentation.

Weak shapes:

- broad claims about open source culture without project-level evidence;
- a list of famous projects with no mechanism notes;
- a comparison that treats Git history as sufficient legitimacy;
- a comparison that treats a code-review workflow as a governance-transition
  model without evidence;
- or a packet that asks to decide C2, C3, C6, reward policy, public posture, or
  contribution status as part of source gathering.

## Follow-Up Questions For Later T9 Review

1. Does maintainer governance provide enough visible rationale for rejected,
   delayed, or revised contributions to satisfy the local legitimacy-trace
   burden?
2. Does commit, merge, or release authority make founder-led authority more
   legitimate, or merely more familiar?
3. Are contributor credit, commit history, release notes, and reputation a
   retained record, retained value, or neither?
4. Which authority transitions are explicit enough to compare against this
   repo's C6 founder-phase burden?
5. How do sponsor pressure, employer concentration, maintainer burnout, and
   dependency control map onto the local economic, epistemic, and governance
   capture categories?
6. Should a later verdict-bearing review compare one named project deeply or a
   small set of governance patterns shallowly?

## Readiness Assessment

Packet state: `sources_required`.

Reason: this file prepares the comparison axes and source slots, but it does
not attach evidence. It is not ready to assign a collision level.

Allowed next step:

- Attach sources for one named open-source project or BDFL transition example,
  then fill the mechanism axes and source-versus-inference section.

Not allowed from this scaffold:

- claim-status movement;
- novelty, collision, or pass/fail verdict;
- maintainer-authority or governance recommendation;
- reward-readiness decision;
- live contribution acceptance or rejection;
- public-posture change;
- or retained-value, legal, financial, reward, governance, or contribution
  commitments.

## Boundary Notes

- No external source has been interpreted here.
- No prior-art collision verdict has been made.
- No novelty claim has been accepted, rejected, narrowed, or strengthened.
- No claim status changed.
- No governance rule changed.
- No public posture changed.
- No T9 pass/fail state changed.
- No real contribution was submitted, accepted, revised, rejected, contested, or
  rewarded.
- No reward, retained-value, legal, or financial promise is created.
