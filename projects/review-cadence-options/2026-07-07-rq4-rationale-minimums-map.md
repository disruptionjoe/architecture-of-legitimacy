---
artifact_type: rationale_minimums_map
status: draft_boundary_scaffold
created: 2026-07-07
research_target: RQ4 cadence and evaluation
governance_role: internal_research_scaffold
constitutional: false
---

# RQ4 Rationale-Minimums Map

Status: draft boundary scaffold.

Purpose: define the minimum visible rationale a later review record would need
for each review state before the project adopts any active review policy,
appeal rule, dispute process, reviewer-authority model, response-time promise,
or live contribution-log procedure.

This file is not a contribution policy, governance decision, cadence decision,
appeal rule, participant-rights grant, reviewer-authority change, claim-status
decision, reward rule, public-posture change, response-time promise, or live
contribution decision. It is a bounded research scaffold for testing whether a
future contributor could reconstruct review reasoning without private founder
context.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ4.
- `ROADMAP.md`, especially Phase 1 and Phase 3.
- `CONTRIBUTING.md`, especially contribution proposal format and review
  expectations.
- `CONTRIBUTION-STANDARDS.md`, especially contribution classes, review states,
  and review cadence.
- `templates/contribution-proposal.md`.
- `templates/contribution-log-schema.md`.
- `PROTOCOL-STACK.md`, especially validation, contestability, retained value,
  and governance layers.
- `LEGITIMACY-SCHEMA.md`, especially traceability, visibility, and
  contestability.
- `projects/review-cadence-options/2026-07-02-rq4-review-cadence-options.md`.
- `projects/review-cadence-options/2026-07-05-rq4-cadence-timing-comparison.md`.
- `projects/review-cadence-options/2026-07-06-rq4-adverse-review-contestability-boundary.md`.
- `projects/first-contribution-workflow-dry-run/2026-07-05-t11-synthetic-adverse-decision-trace.md`.

## Boundary Under Review

The repo already names review states:

- `submitted`;
- `triaged`;
- `accepted`;
- `needs_revision`;
- `not_accepted`;
- `contested`;
- `adversarial`.

The open RQ4 problem is not whether these labels exist. The problem is whether
each state can carry enough visible reasoning for later participants to inspect
the decision, challenge the right part of it, and preserve useful residue
without turning ordinary review into governance transfer, reward allocation, or
an appeal system.

Rationale is sufficient only when a future reader can answer:

1. What was the submitted object or proposed change?
2. Which contribution class and review lane were used?
3. What was decided now?
4. What was explicitly not decided?
5. What evidence, rule, boundary, or missing information drove the state?
6. What useful value remains if the contribution was narrowed or rejected?
7. What can be challenged without creating an automatic appeal right?
8. Which part stops for Joe, governance review, or later policy work?

## State-Level Rationale Minimums

| review state | minimum visible rationale | common weak rationale | stop boundary |
|---|---|---|---|
| `submitted` | Record the submitted object, contributor-provided class, target surface, and whether required fields are present. | "Received" with no target, class, or missing-field note. | Do not imply review, acceptance, queue priority, or reward eligibility. |
| `triaged` | Name the assigned class, review lane, missing evidence, and why triage is not a substantive decision. | A fast label that looks like acceptance or rejection. | Do not adopt policy, change review state meaning, or promise response time. |
| `accepted` | Name the accepted contribution, decisive usefulness reason, affected surface, validation performed, and what acceptance does not grant. | "Looks good" or score-only acceptance. | Do not create reward, rights, governance power, or claim-status movement. |
| `needs_revision` | Name the revision target, decisive gap, evidence needed, preserved value, and what would make the next version reviewable. | Vague "needs more work" with no route. | Do not require private founder context as the missing evidence. |
| `not_accepted` | Name the decisive reason, scope of rejection, source or boundary basis, revision route if any, and loss notes. | "Not a fit" without explaining what was decided. | Do not convert useful residue into accepted policy or retained-value promise. |
| `contested` | Name the disputed point, original rationale, contributor objection, temporary disposition, and next visible state. | "Disputed" with no object or owner. | Do not create automatic appeal rights, voting rights, reversal entitlement, or public promise. |
| `adversarial` | Name the behavior pattern, evidence threshold, harm or capture risk, and why ordinary revision is insufficient. | Treating annoyance, disagreement, or criticism as bad faith. | Do not create sanctions, disclosure requirements, identity rules, or exclusion policy without governance review. |
| `deferred_governance_sensitive` | Name the protected boundary, why ordinary review cannot decide it, useful residue, and required later review owner. | A silent backlog item that hides founder discretion. | Do not move founder powers, reviewer authority, rights, rewards, or public posture through RQ4 cadence. |
| `synthesis_pending` | Name which records need synthesis, what is unresolved, and which claim, test, or roadmap surface may later be affected. | Monthly summary that quietly revises policy or claim status. | Do not treat synthesis as canon, governance, or claim promotion without the right path. |

## Cross-State Field Map

Some fields should appear across many states, but their meanings differ by
state. A later live procedure should review these fields before adoption.

| field | strongest use | misuse risk | scaffold rule |
|---|---|---|---|
| `submitted_object` | Identifies the exact proposal, artifact, or change under review. | Reviewer responds to a softened or different proposal. | Preserve the object before narrowing it. |
| `review_lane` | Explains why the item is maintenance, research, protocol design, contested, synthesis, or governance-sensitive. | Lane label hides a substantive decision. | Pair the lane with what it can and cannot decide. |
| `decisive_reason` | Makes the state reconstructable without the reviewer present. | One vague reason absorbs all disagreement. | Use one primary reason plus secondary notes when needed. |
| `source_or_rule_basis` | Points to the file, template, rule, claim, test, or research question that mattered. | Source citation becomes authority theater. | Separate source text from reviewer inference. |
| `evidence_gap` | Shows what would change the outcome or make a revision reviewable. | Impossible evidence requirement blocks outsiders. | Prefer public or contributor-provided evidence over private context. |
| `scope_of_decision` | Separates what was decided from what remains open. | Acceptance of a narrow contribution is read as broad policy adoption. | State non-effects explicitly. |
| `loss_notes` | Preserves useful residue from rejected, narrowed, or deferred work. | Loss notes become reward, rights, or retained-value promises. | Preserve insight without granting claims. |
| `contestability_note` | Names what can be challenged now. | Every challenge becomes an appeal or governance vote. | Name challenge scope and protected boundaries together. |
| `governance_boundary` | Stops protected movement before it becomes hidden policy. | Ordinary review smuggles in governance transfer. | Route protected matters to later governance review. |
| `timing_or_owner_note` | Prevents ownerless states without promising response times. | A window becomes a public service-level promise. | Prefer "next visible state" over firm deadlines unless adopted. |

## Synthetic Application: One Proposal Across States

Synthetic proposal held constant:

- **Title:** Add a public `next_visible_state` field to review notes.
- **Contributor:** Synthetic Contributor G (agent-assisted: yes).
- **Contribution class:** protocol design, with review and contestability
  effects.
- **Target surfaces:** RQ4 review cadence, RQ5 prototype workflow,
  `CONTRIBUTION-STANDARDS.md` review expectations, and
  `templates/contribution-log-schema.md`.
- **Claim:** Contributors need to know whether an item is waiting for triage,
  batch review, revision, contestation, or governance-sensitive review.
- **Failure risk:** The field could become a response-time promise, an appeal
  right, or a hidden policy change if adopted too early.

| possible state | rationale that would be sufficient for this scaffold | visible non-effect |
|---|---|---|
| `triaged` | Assigned to protocol-design review because it changes review-note shape; evidence gap is whether the field can be non-promissory. | No field is adopted and no response-time promise exists. |
| `needs_revision` | Ask the contributor to narrow the proposal to a non-promissory note shape and add misuse examples. | No template, log schema, or review policy changes. |
| `not_accepted` | Reject as submitted because it creates implied timing expectations before review capacity exists; preserve the ownerless-state concern. | No loss note creates reward, rights, or retained-value claims. |
| `contested` | Contributor may challenge whether the timing expectation is really promissory or whether a softer field would suffice. | Contest does not create appeal rights or a reversal entitlement. |
| `deferred_governance_sensitive` | If tied to mandatory response windows or appeal rights, defer to later governance and participant-rights review. | RQ4 cannot transfer authority or create participant rights. |
| `synthesis_pending` | Preserve the proposal as evidence that open review states need visible owners or next states. | Monthly synthesis cannot silently change contribution standards. |

## Reviewer Failure Modes

1. **Score substitution.** A numeric score replaces an explanation of what was
   decided and what remains open.
2. **Founder-context dependency.** The record says "not ready" but the missing
   evidence lives only in the founder's head.
3. **Acceptance leakage.** A narrow accepted insight is read as acceptance of
   the full mechanism.
4. **Contestability inflation.** A challenge note becomes an appeal right,
   voting right, or reversal promise.
5. **Adversarial overreach.** Persistent critique or disagreement is mislabeled
   as bad faith.
6. **Timing overpromise.** A next state becomes an implied deadline before the
   repo has adopted response-time capacity.
7. **Synthesis drift.** A monthly synthesis summary changes policy, claim
   status, reviewer authority, or public posture without the correct review
   path.

## Later Review Questions

- Which rationale fields belong in reviewer-only notes, contribution-log
  entries, issue comments, or monthly synthesis?
- What is the shortest rationale that still lets a newcomer reconstruct an
  adverse decision?
- Should accepted maintenance contributions and accepted protocol-design
  contributions use different rationale minimums?
- Which review states need a visible owner before the first real external
  contribution is invited?
- When should `contestability_note` become a live field, if ever?
- How can the repo preserve useful residue without creating reward, rights, or
  retained-value expectations?
- What evidence would justify moving this scaffold into a real Phase 1 review
  procedure?

## Boundary Notes

- No real contributor is represented here.
- No real contribution was accepted, rejected, contested, scored, logged, or
  rewarded.
- No live contribution log entry, issue template, contribution proposal
  template, contribution standard, review policy, cadence rule, appeal rule,
  dispute process, reviewer-authority model, response-time promise, governance
  policy, reward meaning, rights policy, claim status, test pass/fail state, or
  public posture changed.
- This scaffold is draft research evidence for later RQ4 review, not active
  workflow policy.
