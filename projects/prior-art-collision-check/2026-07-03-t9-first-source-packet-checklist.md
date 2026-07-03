---
artifact_type: prior_art_source_packet_checklist
status: pilot_readiness_scaffold
created: 2026-07-03
test_target: T9 prior-art collision check
governance_role: internal_test_record
constitutional: false
---

# T9 First Source-Packet Checklist

Status: pilot-readiness scaffold.

Purpose: make the first real prior-art contribution review easier to run
without letting a reviewer make a novelty, collision, claim-status, governance,
or reward decision before the evidence packet is visible.

This file does not complete T9, choose a neighboring system, attach sources,
make a collision verdict, change a claim, accept a contribution, or create any
reward, retained-value, legal, financial, or governance right.

## Use Boundary

Use this checklist before filling the T9 review packet in
`2026-07-02-t9-prior-art-collision-review-scaffold.md`.

The checklist answers one narrow question:

```text
Is this source packet ready for a mechanism-level prior-art comparison?
```

It should not answer:

- whether the repo's coupled-stack claim is novel;
- whether C2 or C3 should be promoted, narrowed, or demoted;
- whether a real contribution should be accepted;
- whether a neighboring system is better or worse;
- or whether reward, rights, governance, or public posture should change.

## Packet Header

Use one packet per neighboring system.

```yaml
packet_id: ""
neighboring_system: ""
contributor: ""
date_prepared: ""
target_claims_or_tests:
  - "T9"
  - ""
review_state: submitted
source_packet_ready: false
claim_status_change_requested: false
```

## Minimum Evidence Checklist

All required fields should be answerable from visible sources or clearly labeled
reviewer inference.

| check | pass condition | why it matters |
|---|---|---|
| Stable source named | The packet names at least one stable primary or official source. | Prevents label-level comparisons. |
| Practice source named | The packet includes a source about actual operation, implementation, round design, process history, or known use when available. | Separates formal design from lived mechanism behavior. |
| Limitation source or limitation note included | The packet includes a critique, evaluation, failure-mode source, or explicit note that such a source was not found yet. | Keeps novelty review from becoming advocacy. |
| Local target named | The packet names the claim, test, research question, or axis being compared. | Prevents broad literature notes from drifting away from repo needs. |
| Mechanism axes touched | The packet includes notes for contribution unit, validation path, value logic, record trace, governance, reward timing, and capture model when relevant. | Keeps comparison at mechanism level. |
| Source versus inference separated | The packet lists what the sources directly support separately from what the reviewer infers. | Makes later disagreement reconstructable. |
| Boundary statement included | The packet states that no claim status, reward, governance, or public-posture change is made inside the packet. | Preserves review gates. |
| Revision path visible | Missing evidence is routed to `needs_revision` or follow-up questions rather than hidden rejection. | Preserves useful partial work. |

## Mechanism Notes Template

```yaml
mechanism_notes:
  contribution_unit:
    source_evidence: ""
    reviewer_inference: ""
    uncertainty: ""
  validation_path:
    source_evidence: ""
    reviewer_inference: ""
    uncertainty: ""
  value_logic:
    source_evidence: ""
    reviewer_inference: ""
    uncertainty: ""
  legitimacy_conditions:
    source_evidence: ""
    reviewer_inference: ""
    uncertainty: ""
  record_trace:
    source_evidence: ""
    reviewer_inference: ""
    uncertainty: ""
  retained_value:
    source_evidence: ""
    reviewer_inference: ""
    uncertainty: ""
  reward_timing:
    source_evidence: ""
    reviewer_inference: ""
    uncertainty: ""
  governance_transition:
    source_evidence: ""
    reviewer_inference: ""
    uncertainty: ""
  capture_model:
    source_evidence: ""
    reviewer_inference: ""
    uncertainty: ""
  coupled_design:
    source_evidence: ""
    reviewer_inference: ""
    uncertainty: ""
```

## Readiness States

| state | meaning | allowed next step |
|---|---|---|
| `ready_for_review` | Minimum evidence is present and mechanism notes separate source evidence from inference. | Fill the T9 review packet and assign a candidate collision level. |
| `needs_revision` | The packet is relevant but missing sources, axes, limitations, or source/inference separation. | Ask for a narrower packet or additional evidence. |
| `not_usable_yet` | The packet is mostly labels, advocacy, unsupported summary, or off-target material. | Preserve useful source leads in loss notes if any exist. |
| `governance_stop` | The packet asks to change claim status, governance, reward, rights, public posture, or contribution decisions directly. | Route to Joe or governed review; do not decide inside T9. |

## First Pilot Recommendation

The first real packet should be narrow enough to review in one pass.

Good shape:

- one neighboring system;
- two or three stable sources;
- three to five mechanism axes emphasized;
- one explicit limitation;
- one candidate collision level framed as provisional;
- and no requested claim-status, reward, governance, or public-posture change.

Weak shape:

- a broad survey of many systems;
- links without mechanism notes;
- a persuasive novelty argument with no limitation;
- AI-generated synthesis with no source trail;
- or a proposal that asks the reviewer to accept a governance or reward
  consequence as part of the prior-art comparison.

## Reviewer Prompts

Before assigning any collision level, ask:

1. What exactly do the sources show?
2. What is the reviewer inferring beyond the sources?
3. Which comparison axis has the weakest evidence?
4. Would a future contributor be able to reconstruct the rationale without
   private founder context?
5. Is any claim-status or public-posture change being implied too early?
6. What useful value should be preserved in `loss_notes` if the packet needs
   revision or cannot be used yet?

## Boundary Notes

- No source packet has been completed here.
- No neighboring system has been selected for actual review.
- No prior-art collision verdict has been made.
- No novelty claim has been accepted, rejected, narrowed, or strengthened.
- No claim status changed.
- No governance rule changed.
- No public posture changed.
- No T9 pass/fail state changed.
- No real contribution was submitted, accepted, revised, rejected, contested, or
  rewarded.
- No reward, retained-value, legal, or financial promise is created.
