---
artifact_type: research_scaffold
status: draft
created: 2026-07-07
research_question: RQ5 prototype workflow
test_targets:
  - T3 first workflow simulation
  - T10 contribution log prototype
  - T11 legitimacy trace workflow
governance_role: non_adopted_record_surface_comparison
constitutional: false
---

# RQ5 First-Pilot Record-Surface Comparison

Status: draft review-prep scaffold, not adopted workflow, issue-template,
review, contribution-log, governance, rights, reward, public-posture,
claim-status, or contribution-record policy.

This comparison evaluates where a later first-pilot contribution packet could
be recorded without choosing a live surface. It does not launch a pilot, select
a target, invite public contributions, edit templates, open an issue or PR,
adopt reviewer authority, create a live contribution-log entry, mark tests
passed, move claim status, change rights, rewards, governance, AI policy,
transfer posture, public posture, or decide any real contribution.

## Purpose

The first-pilot review queue identifies record-surface choice as the next safe
local-prep question. The problem is not only where a contributor submits work.
It is how the repo preserves the chain from submission to review to possible
log entry without making a draft, issue, or review note look like adopted
policy or accepted contribution memory.

The useful comparison question is:

```text
What does each possible record surface preserve, and what protected meaning
would it risk implying if used too early?
```

This file compares surfaces only. It is not a first-pilot launch plan.

## Source Surfaces

- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `CONTRIBUTIONS-LOG.md`
- `templates/contribution-proposal.md`
- `templates/contribution-log-schema.md`
- `.github/ISSUE_TEMPLATE/contribution-proposal.yml`
- `.github/ISSUE_TEMPLATE/contribution.md`
- `.github/ISSUE_TEMPLATE/research-task.yml`
- `projects/prototype-workflow/2026-07-06-rq5-issue-template-field-parity.md`
- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-review-packet-checklist.md`
- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-review-queue-map.md`

## Surface Roles

| surface | strongest role | main preservation value | main premature-meaning risk |
|---|---|---|---|
| Structured contribution issue | Public intake record for a proposed contribution. | Captures class, target, contribution, why it matters, evidence, risk, and loss/deferred value in a consistent form. | Looks like the default live pilot path before accountability, reviewer authority, and log-conversion questions are settled. |
| Legacy Markdown contribution issue | Flexible public intake record with richer self-assessment prompts. | Preserves value self-assessment and loss/deferred value in a human-readable form. | Duplicates the structured form and may create field drift or public confusion over which intake path is authoritative. |
| Research-task issue | Task definition surface before a contributor performs the work. | Separates bounded question, claim target, method, success condition, and failure condition. | Can be mistaken for a contribution record even though it describes work to do, not work submitted or reviewed. |
| Pull request | Change-set and review surface for concrete repo edits. | Preserves diff, review comments, commit trail, and merge boundary. | Merge may be mistaken for accepted contribution status, test pass, reward eligibility, or claim movement unless the review note says otherwise. |
| Draft project artifact | Reversible repo-local packet or scaffold under `projects/`. | Preserves packet structure, boundary notes, rationale screens, and reviewer-prep logic without requiring live issue or PR action. | Can accumulate synthetic work that looks like adopted workflow if not clearly marked as draft and non-adopted. |
| Contribution-log entry | Post-review project memory for accepted or otherwise classified real contributions. | Preserves `CONTRIB-*` identity, review state, rationale, loss notes, and links after review. | Creates the strongest false signal if used before review: live record, accepted memory, future-claim implication, or reward expectation. |

## Record-Chain Requirements

A first-pilot record chain should preserve these meanings across surfaces:

| requirement | intake issue | PR | project artifact | contribution log |
|---|---|---|---|---|
| Submission snapshot | Strong if the issue form is used directly. | Medium if the PR body copies the proposal. | Medium if the artifact quotes or summarizes the proposal. | Weak; the log should link back rather than duplicate intake. |
| Contribution unit | Strong when class, target, and contribution fields are filled. | Strong when the diff is narrow. | Strong when the packet names exactly one unit. | Strong only after reviewer records the accepted or classified unit. |
| Evidence and source limits | Medium; structured form allows evidence but does not require it for all classes. | Medium to strong if review comments check missing evidence. | Strong for a prepared review packet. | Medium; log should summarize, not become a source packet. |
| Review rationale | Weak; submitter forms should not decide review state. | Strong if reviewer comments are explicit and durable. | Strong if the packet has a rationale screen. | Strong after review, if rationale is concise and linked. |
| Boundary sentence | Weak unless added by reviewer. | Medium if included in PR review. | Strong; the packet can require protected non-conclusions. | Strong but only after review, not on submission. |
| Useful residue and loss notes | Medium; intake can name deferred value. | Medium if reviewer preserves narrowed or rejected value. | Strong for draft review-prep. | Strong after review; `loss_notes` is a schema field. |
| Contestability marker | Weak; intake should not imply appeal rights. | Medium if review records the disputed point. | Strong as a review-prep field. | Medium after review, if it avoids appeal promises. |
| Log eligibility | Weak; proposal is not eligibility. | Medium if review distinguishes merge from log eligibility. | Strong if packet includes a log-eligibility screen. | Final only after review. |

## Surface-Specific Use Boundaries

### Structured Contribution Issue

Use as candidate public intake only after a governed decision says the
structured form is the preferred first-pilot entry point. Until then, it is a
visible possible surface, not the active route.

Preserves well:

- class, target, contribution, and rationale for why it matters;
- evidence or reasoning when the contributor supplies it;
- failure/risk and loss/deferred value.

Needs later decision:

- whether GitHub account identity is enough contributor context;
- whether agent assistance, affiliation, conflict, or self-assessment should be
  collected directly;
- whether optional evidence is enough for research-class work.

### Legacy Markdown Contribution Issue

Use only as a comparison surface unless the repo deliberately keeps two intake
routes. Its strength is richer contributor context and value self-assessment.
Its weakness is duplication beside the structured contribution issue.

Preserves well:

- value self-assessment;
- explicit source limits;
- failure modes;
- loss or deferred value.

Needs later decision:

- whether the legacy template should be retired, redirected, or mirrored;
- whether contributor self-assessment helps review or creates reward confusion.

### Research-Task Issue

Use for defining a task before contribution, not for recording the submitted
contribution. It can help a first pilot only if the pilot target is a bounded
research task and the actual submitted result is recorded elsewhere.

Preserves well:

- question, claim target, method, success condition, and failure condition;
- why a task is bounded enough for a contributor to attempt.

Needs later decision:

- how to link task issue, submission issue or PR, and eventual review receipt;
- whether task authorship and contribution authorship should be separate.

### Pull Request

Use as a change-set and review surface when the first pilot changes repo files.
It is poor as the only intake surface unless the PR body also preserves the
proposal fields.

Preserves well:

- diff, review comments, commit trail, and merge or close boundary;
- concrete evidence of what changed.

Needs later decision:

- whether merge means only "change accepted" or also "contribution accepted";
- where review rationale and loss notes live if the PR is closed or narrowed;
- how to keep PR comments from becoming hidden governance precedent.

### Draft Project Artifact

Use for non-live review preparation, packet simulation, or reviewer screens.
This is the safest surface for unattended Progress because it can be explicit
about non-adoption and does not require public issue or PR activity.

Preserves well:

- packet outline;
- protected non-conclusions;
- rationale, residue, log-eligibility, and contestability screens;
- comparison logic across existing scaffolds.

Needs later decision:

- when a draft artifact becomes stale, superseded, or ready for governed review;
- whether any packet outline should become a template.

### Contribution Log Entry

Use only after review. The log is the strongest memory surface and therefore
the worst place to put a mere proposal, draft, synthetic fixture, or unreviewed
pilot packet.

Preserves well:

- contribution id;
- class, target, review state, scores if used, rationale, loss notes, and links;
- later reconstruction of why the project accepted, narrowed, rejected,
  contested, or classified the contribution.

Needs later decision:

- whether the first real pilot can ever enter as `submitted` or should enter
  only after `triaged` or later review;
- whether accepted and non-accepted real contributions both deserve log entries;
- how to avoid reward, rights, legal, financial, or retained-value implication.

## Safe Chain Patterns To Test Later

These are candidate patterns for later governed review, not adopted process.

| pattern | chain | benefit | stop boundary |
|---|---|---|---|
| Issue-first packet | Structured contribution issue -> draft project review packet -> log only after review. | Preserves public intake while keeping review rationale and log eligibility separate. | Requires decision that the structured form is the live first-pilot intake surface. |
| PR-first packet | Pull request with proposal fields -> PR review -> log only after review. | Works when contribution is a concrete repo edit with a durable diff. | Requires clear statement that merge does not automatically imply reward, test pass, or claim movement. |
| Task-to-submission packet | Research-task issue -> contribution issue or PR -> draft review packet -> log only after review. | Separates "task requested" from "contribution submitted" and "contribution reviewed." | Requires linking discipline so task authorship, contributor authorship, and reviewer rationale do not blur. |
| Artifact-first dry run | Draft project artifact -> governed review decision before any live surface. | Safest for pre-pilot rehearsal and unattended Progress. | Must not be described as live contribution workflow or accepted project memory. |

## First-Pilot Surface Readiness Screen

Before any later live first pilot chooses a surface, the packet should answer:

1. Which surface records the submitted object?
2. Which surface records reviewer rationale?
3. Which surface records useful residue or loss notes?
4. Which surface decides log eligibility?
5. Which surface links the chain together?
6. Which protected meanings are explicitly not changed?
7. What would require Joe/governed review before the surface is used?

If those answers are not visible, the live pilot should pause.

## Non-Adopted Recommendation For Later Review

The safest shape to evaluate later is a separated chain rather than a single
all-purpose surface:

```text
intake surface -> review packet -> contribution log only after review
```

That chain would let a later first pilot preserve public submission, rationale,
loss notes, contestability, and log eligibility without treating submission,
review, and accepted memory as the same event.

This is a review-prep recommendation only. It does not choose the intake
surface, authorize a first pilot, or change live process.

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, sanctioned, rewarded, or used as transfer evidence.
- No issue, PR, project artifact, or contribution-log entry was created as a
  live pilot surface.
- No issue template, contribution template, contribution standard,
  contribution-log schema, live contribution record, review policy, reviewer
  authority, appeal rule, response-time promise, governance rule, emergency
  rule, rollback rule, participant-rights policy, reward meaning, AI-use
  policy, transfer policy, claim status, test pass/fail state, public posture,
  or external action changed.
- This is a draft research scaffold for later RQ5 review preparation, not
  active contribution workflow policy.
