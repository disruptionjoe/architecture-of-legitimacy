---
artifact_type: research_scaffold
status: draft
created: 2026-07-02
research_question: RQ5 prototype workflow
governance_role: non_adopted_synthesis
constitutional: false
---

# RQ5 Prototype Workflow Synthesis

This scaffold assembles the repo's current first-contribution workflow pieces into
a candidate one-page flow for later review. It does not change active contribution
instructions, issue templates, review states, contribution-log policy, governance,
reward meaning, or any real contribution record.

## Source Artifacts

- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `.github/ISSUE_TEMPLATE/contribution-proposal.yml`
- `.github/ISSUE_TEMPLATE/contribution.md`
- `.github/ISSUE_TEMPLATE/research-task.yml`
- `templates/contribution-proposal.md`
- `templates/contribution-log-schema.md`
- `projects/first-workflow-simulation/2026-07-02-t3-newcomer-workflow-simulation.md`
- `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md`
- `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-log-examples.md`

## Candidate One-Page Flow

| stage | contributor-facing action | reviewer/project action | record produced | open adoption question |
|---|---|---|---|---|
| 1. Orient | Read the public start files and choose a live claim, test, document, or research question. | Keep live targets discoverable through `RESEARCH-AGENDA.md` and `TESTS.md`. | None. | Should RQ5 name a short "start here for first contribution" path, or is `CONTRIBUTING.md` enough? |
| 2. Draft | Use the contribution proposal template or GitHub contribution form. | Preserve class, target, evidence, risk, and loss/deferred-value fields. | Proposal issue, PR, or draft artifact. | Which path is canonical for the first real pilot: issue, PR, or local proposal file? |
| 3. Submit | Mark the contribution as `submitted`; do not self-accept. | Triage contribution class and target. | Public submission record. | Should mixed-class contributions require one primary class? |
| 4. Review | Supply evidence or reasoning appropriate to the class. | Apply evidence, risk, relevance, and governance-boundary checks. | Review rationale. | What is the minimum rationale for each review state? |
| 5. Classify | Receive one of the current review states. | Choose `accepted`, `needs_revision`, `not_accepted`, `contested`, or `adversarial` only with explicit rationale. | Review-state decision. | Who may issue the first decision while governance remains founder-led? |
| 6. Preserve | If revised or not accepted as-is, keep useful deferred value visible. | Use `loss_notes` without implying reward, legal claim, or future governance right. | Candidate log entry or review note. | When should loss notes live in a log entry versus the review thread? |
| 7. Log | Do not write into the live log unless there is a real reviewed contribution. | Add a `CONTRIB-NNNN` record only after a real decision. | `CONTRIBUTIONS-LOG.md` entry. | What exact event authorizes adding the first live log entry? |
| 8. Contest | If the contributor disputes the state, keep the disputed point reconstructable. | Record contestability without silently changing appeal or governance policy. | Public rationale or contested-state note. | Does RQ5 need a minimal contested-decision path before the first pilot? |

## What The Current Artifacts Already Support

- A first-time contributor can find contribution classes, review states, rubric dimensions, and proposal fields without private context.
- The proposal and issue templates ask for target, value, evidence/reasoning, failure risk, and loss/deferred value.
- The log schema can represent non-code work, review rationale, rubric scores, links, and loss notes.
- The T3 simulation shows a small review contribution can move from proposal to log-ready outcome if the policy-adoption boundary is named.
- The T10 examples show accepted, needs-revision, and not-accepted outcomes can preserve value without using the live `CONTRIB-NNNN` namespace.
- The T11 trace shows the first real pilot should probably be a bounded prior-art or review contribution, not a new governance mechanism.

## Gaps Before Adoption

1. **Canonical submission path:** choose whether the first real pilot starts as a GitHub issue, PR, or local proposal artifact.
2. **Minimum rationale:** define the shortest acceptable reviewer rationale for each state without adopting a full appeal workflow.
3. **Founder-context exposure:** state which parts of the first review remain founder-led and how the rationale makes that visible.
4. **Log-entry trigger:** define when a reviewed contribution becomes eligible for a live `CONTRIB-NNNN` entry.
5. **Contestability stub:** decide whether `contested` needs a minimal public record format before any real disputed decision occurs.
6. **Pilot scope:** pick one low-governance, low-reward-risk contribution type for the first real workflow test.

## Candidate First Pilot

A bounded source-backed prior-art or review contribution remains the safest first
pilot because it can test evidence quality, relevance, rationale clarity, and loss
notes without adopting governance rules, reward logic, founder-power changes, or
claim-status movement.

Minimum pilot constraints:

- target one live claim, test, or research question;
- include stable sources or a clearly bounded reasoning path;
- avoid proposing immediate governance or reward adoption;
- record one decisive review rationale;
- preserve deferred value through `loss_notes` if the work is revised or not accepted as-is;
- avoid adding a live `CONTRIB-NNNN` entry until a real reviewed contribution exists.

## Later RQ5 Adoption Questions

- Should this synthesis become a one-page workflow in `CONTRIBUTING.md`, or stay as a project artifact until a real pilot completes?
- Which fields from the Markdown proposal and GitHub issue form must remain identical?
- What is the smallest public review note that makes a founder-led decision inspectable?
- Does the project need an explicit "not adopted as policy" label for protocol-design suggestions in contribution reviews?
- What evidence would be enough to mark T3, T10, T11, or RQ5 stronger without overclaiming pass/fail status?

## Boundary Notes

- No live contribution was created, reviewed, accepted, revised, rejected, contested, scored, logged, or rewarded.
- No issue template, contribution template, contribution standard, governance rule, claim status, public posture, reward meaning, or real contribution record changed.
- This scaffold is draft synthesis for later review, not active workflow policy.
