---
artifact_type: participant_rights_boundary_map
status: non_adopted_scaffold
created: 2026-07-03
research_question: RQ7 voice, exit, and retained value
claim_target: C5
governance_role: review_prep_only
constitutional: false
---

# RQ7 Voice, Exit, And Retained-Value Boundary Map

Status: draft boundary map, not adopted participant-rights or reward policy.

Purpose: make RQ7 reviewable by separating voice, exit, retained record, retained-value marker, contestability, and dispute-path questions before the repo changes active contribution standards, governance rules, claim status, public posture, reward meaning, or any real contribution record.

This file does not grant contributor rights, create reward promises, create legal or financial claims, define appeal policy, change reviewer authority, revise governance, or decide how any real contribution should be handled. It is a bounded research scaffold for later review.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ7
- `ROADMAP.md`, especially Phase 1, Phase 3, and Phase 4
- `CLAIMS.md`, especially C3, C5, C6, and C7
- `LEGITIMACY-SCHEMA.md`, especially voice, contestability, exit with retained record, and bounded authority
- `PROTOCOL-STACK.md`, especially Layers 6, 7, 8, and 9
- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `GUARDRAILS.md`
- `THREAT-MODEL.md`, especially governance capture, reward gaming, and legitimacy drift
- `projects/prototype-workflow/2026-07-02-rq5-prototype-workflow-synthesis.md`
- `projects/founder-phase-constraint/2026-07-02-t7-founder-phase-constraint-review-prep.md`
- `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md`

## Boundary Under Review

RQ7 asks what rights participants should have from day one. The risky move is treating every desirable legitimacy condition as an immediately adopted right, reward entitlement, governance power, or legal claim.

This scaffold separates six design objects that should not be collapsed:

1. **Visibility:** can a participant see the rules, rationale, and record?
2. **Voice:** can a participant propose changes or supply structured feedback?
3. **Contestability:** can a participant challenge a classification or rationale?
4. **Exit with retained record:** can a participant leave without erasing accepted work?
5. **Retained-value marker:** can a record preserve possible future relevance without promising payout or control?
6. **Dispute path:** can disagreement be recorded without adopting a full appeal court or distributed governance process?

## Candidate Rights Boundary Matrix

| candidate boundary | attaches to | minimum record needed | legitimacy purpose | over-promise risk | later adoption question |
|---|---|---|---|---|---|
| Rule visibility | All participants. | Public rules, proposal fields, review states, and rationale expectations. | Reduces hidden-founder-context dependence. | Static rules may be mistaken for mature governance. | Which rule surfaces must be checked before the first real contribution pilot? |
| Contribution record visibility | Accepted contributions and possibly reviewed non-accepted residue. | Artifact link, target, review state, rationale, reviewer path, and loss notes where relevant. | Lets future contributors reconstruct why a contribution counted or did not count. | Public record can imply final truth or reward entitlement. | Which non-accepted residue deserves durable preservation? |
| Structured voice | Participants who submit a bounded proposal, critique, or rule-change request. | Targeted issue, proposal, or review note with a named affected rule or workflow. | Converts dissatisfaction into inspectable evidence. | Voice may be mistaken for voting power or veto authority. | Which kinds of rule-change proposals are safe before distributed governance exists? |
| Contestability | Contributors affected by an adverse review state or disputed classification. | Disputed point, original rationale, requested change, and reviewer response. | Makes adverse decisions reviewable without hiding behind authority. | A contest path may imply an appeal policy the repo has not adopted. | What is the smallest contested-state record that preserves legitimacy without creating a court? |
| Exit with retained record | Contributors with accepted work, and possibly contributors with preserved loss notes. | Stable contribution link, contributor identifier or pseudonym, accepted record, and exit note if supplied. | Avoids coercion through erasure. | Retention language may imply perpetual platform, legal, or financial obligations. | What retention commitments are realistic for a public repo? |
| Retained-value marker | Accepted contributions, or deferred value explicitly preserved by review. | Non-promissory marker that names possible future relevance and its uncertainty. | Keeps early value from vanishing before rewards are designed. | Marker may become a shadow token, payout claim, or governance-weight proxy. | Which marker language preserves optionality without creating entitlement? |
| Correction and annotation | Contributors or reviewers who identify an error in the record. | Correction note linked to the original artifact and rationale. | Lets the record learn without rewriting history. | Corrections can become silent meaning changes or retroactive acceptance. | When should correction append rather than replace? |
| AI-use transparency | AI-assisted contributors or reviewers. | Disclosure of AI assistance and human judgment boundary. | Preserves contestability when AI supports synthesis or critique. | AI disclosure may drift into AI authority if reviewers rely on generated scores. | Which AI uses require disclosure in a rights or dispute context? |

## Candidate Day-One Minimums

These are review prompts, not adopted minimum rights:

- Participants can inspect contribution classes, proposal fields, review states, and guardrails before submitting.
- Contributors can receive a visible reason when a contribution is accepted, needs revision, not accepted, contested, or treated as adversarial.
- Useful deferred value can be preserved through `loss_notes` without creating a reward promise.
- Accepted contribution records can remain visible even if the contributor later stops participating.
- A contributor can name the exact classification or rationale they dispute.
- Rule-change proposals can be submitted as contributions, but they do not become policy merely because they are submitted or valuable.
- AI assistance can support drafting, critique, and synthesis, but human judgment and contestability remain visible.

## Retained-Value Marker Options

| option | meaning | what it preserves | what it must not imply | useful test |
|---|---|---|---|---|
| A. No marker beyond normal record | Accepted work is visible, but no future-value note is added. | Attribution and rationale. | Future reward, governance weight, or retained claim. | Does normal attribution provide enough trust for early contributors? |
| B. Non-promissory future-relevance note | The record says the work may matter if future rights or rewards are designed. | Optionality and reviewer memory. | Payout, ownership, legal claim, or guaranteed review weight. | Can contributors understand this as evidence preservation, not entitlement? |
| C. Review-credit marker | The record says the work should be considered in later contribution-history review. | Link between early work and later synthesis. | Automatic scoring, reward conversion, or governance standing. | Does this help later reviewers avoid forgetting early value? |
| D. Loss-note marker | The record preserves value that was revised, narrowed, or not accepted as-is. | Useful residue and contributor-visible loss. | Compensation for rejected work or deferred acceptance. | Does it make adverse decisions feel more legitimate without confusing status? |
| E. Explicit no-reward baseline | The record states no reward or retained-value right is currently attached. | Clarity and anti-overclaim discipline. | A permanent decision against future rewards. | Does negative clarity reduce ambiguity without discouraging contribution? |

## Exit Scenarios To Pressure-Test

| scenario | record question | legitimacy risk | boundary to preserve |
|---|---|---|---|
| Accepted contributor stops participating. | Does the accepted record remain visible and attributed? | Exit becomes coercive if recognition disappears. | Retain accepted record unless safety, legal, or moderation issues require review. |
| Contributor asks to change display identity. | Can attribution be updated without hiding historical context? | Public record may reveal more identity than the contributor intended. | Separate stable record integrity from display-name policy. |
| Contributor disputes `needs_revision`. | Is the disputed issue visible enough for future review? | Founder judgment becomes unchallengeable. | Preserve the contested point without guaranteeing reversal. |
| Contributor withdraws a proposal before review. | Does anything remain, and who decides? | The repo may preserve material the contributor meant to retract. | Decide later whether withdrawal creates a visible stub or no durable record. |
| Contributor is later classified as adversarial. | What happens to previously accepted work? | Retaliatory erasure or uncritical retention can both harm legitimacy. | Preserve historical record while marking later risk if relevant. |
| Pseudonymous contributor loses access to identity. | Can contribution continuity survive? | Future claim and contest paths may fail. | Require enough continuity for retained-record claims before promising more. |
| Contributor exits after a governance dispute. | Can their accepted work remain without forcing continued participation? | Exit can become a loyalty test. | Retain contribution history while separating it from ongoing governance authority. |

## Dispute-Path Questions

A minimal dispute path can be studied before the project adopts appeal policy. The first review packet should answer:

1. What exactly is being disputed: contribution class, evidence sufficiency, review state, value score, loss note, retained-value marker, reviewer conduct, or rule meaning?
2. What record must be visible before a dispute is reviewable?
3. Which disputes can be handled by correction or annotation rather than appeal?
4. Which disputes would cross into governance, public posture, reward, or contributor-rights policy and require Joe/governance review?
5. What is the minimum reviewer response that preserves contestability without pretending the system has distributed authority?
6. How does the record preserve legitimate dissatisfaction without rewarding pressure campaigns or adversarial volume?

## Failure Modes

| failure mode | early warning | possible mitigation to test |
|---|---|---|
| Rights inflation | Draft language sounds like adopted participant rights or legal guarantees. | Use candidate, scaffold, and non-promissory labels until governance review. |
| Reward leakage | Retained-value markers are read as payout shares or token claims. | Pair marker options with explicit no-reward language and adoption stops. |
| Voice theater | Participants can speak, but feedback never affects rules. | Track rule-change proposals and name whether they changed anything. |
| Exit coercion | Contributors fear losing attribution or future relevance if they leave. | Test retained-record language on synthetic exit scenarios. |
| Contestability overload | Every decision becomes a full appeal process. | Separate correction, annotation, dispute note, and governance appeal. |
| Founder shield | Founder-led review cites rights language while retaining opaque discretion. | Require visible rationale and named authority boundary. |
| Capture by grievance | Bad-faith actors use voice or contest paths to exhaust review. | Define reviewability thresholds and adversarial-state boundaries before adoption. |
| AI legitimacy laundering | AI-generated dispute or review text masks missing human judgment. | Require disclosure and human contestable rationale for AI-supported review. |

## Candidate Review Packet Shape

```text
RQ7 review packet
  1. Rights boundary inventory
  2. Day-one minimum candidate
  3. Retained-value marker options
  4. Exit scenario pressure test
  5. Dispute-path minimum record
  6. Failure-mode and capture-risk notes
  7. Joe/governance adoption questions
```

## Later Adoption Boundary

This scaffold can support later RQ7 review when the repo has:

- at least one real or further synthetic contribution with visible review rationale;
- a contribution record that demonstrates whether `loss_notes` are understandable;
- a contestability example or synthetic disputed-state trace;
- an exit scenario pressure test that distinguishes retained record from retained reward;
- clear language separating contributor voice from voting power, veto authority, or governance standing;
- and a capture-risk review for any retained-value marker.

Until that later review happens, this scaffold does not adopt participant rights, retained-value markers, appeal paths, dispute rules, reward promises, governance powers, reviewer authority, claim-status movement, public-posture changes, or contribution decisions.

## Stop Conditions

Stop and require Joe/governance review before:

- editing `CONTRIBUTING.md`, `CONTRIBUTION-STANDARDS.md`, `GOVERNANCE.md`, `GUARDRAILS.md`, `CLAIMS.md`, public posture, issue templates, live review policy, contestability rules, or contribution-log policy based on this scaffold;
- adopting any participant right, appeal path, retained-value marker, reward logic, governance power, reviewer authority, identity-retention rule, or exit policy;
- treating a retained-value marker as legal, financial, token, ownership, governance, or reward entitlement;
- marking C5 stronger or moving claim status;
- adding or changing a real contribution record;
- or publishing this scaffold as active rights policy rather than draft research.
