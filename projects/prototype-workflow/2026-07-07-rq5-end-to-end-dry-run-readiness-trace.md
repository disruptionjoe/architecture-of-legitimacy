---
artifact_type: research_scaffold
status: draft
created: 2026-07-07
research_question: RQ5 prototype workflow
test_targets:
  - T3 first workflow simulation
  - T10 contribution log prototype
  - T11 legitimacy trace workflow
governance_role: non_adopted_end_to_end_dry_run
constitutional: false
---

# RQ5 End-To-End Dry-Run Readiness Trace

Status: draft scaffold, not adopted workflow policy.

This trace composes the existing RQ5, T3, T10, and T11 scaffolds into one
end-to-end dry run for a later first real contribution pilot. It does not change
active contribution instructions, issue templates, review policy, reviewer
authority, contribution-log schema, governance, reward meaning, claim status,
test pass/fail state, public posture, or any real contribution record.

## Purpose

The repo already has separate scaffolds for the candidate workflow, handoff
gaps, issue-template field parity, founder-context dependency, synthetic log
examples, and synthetic adverse decisions. The remaining RQ5 need is coherence:
can a later reviewer trace one first-pilot contribution from orientation to
log eligibility without switching between isolated maps or relying on private
founder explanation?

This artifact does not decide that the workflow is ready. It names what a dry
run would need to preserve before the first live pilot can be reviewed.

## Source Surfaces

- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `templates/contribution-proposal.md`
- `templates/contribution-log-schema.md`
- `.github/ISSUE_TEMPLATE/contribution-proposal.yml`
- `projects/prototype-workflow/2026-07-02-rq5-prototype-workflow-synthesis.md`
- `projects/prototype-workflow/2026-07-06-rq5-workflow-handoff-gap-map.md`
- `projects/prototype-workflow/2026-07-06-rq5-issue-template-field-parity.md`
- `projects/first-workflow-simulation/2026-07-02-t3-newcomer-workflow-simulation.md`
- `projects/first-workflow-simulation/2026-07-06-t3-founder-context-dependency-map.md`
- `projects/first-contribution-workflow-dry-run/2026-07-01-synthetic-contribution-trace.md`
- `projects/first-contribution-workflow-dry-run/2026-07-05-t11-synthetic-adverse-decision-trace.md`
- `projects/first-contribution-workflow-dry-run/2026-07-06-t10-log-schema-boundary-map.md`
- `projects/first-contribution-workflow-dry-run/2026-07-06-t11-retained-marker-boundary.md`

## Synthetic Pilot Packet

This packet is intentionally non-real. It gives the dry run one stable object
without creating a live issue, PR, review, score, log entry, or contributor
record.

```yaml
id: SAMPLE-RQ5-END-TO-END-001
submission_surface: structured GitHub contribution form
contributor_visibility: pseudonymous GitHub account; agent assistance declared
primary_class: research
secondary_effects:
  - review
target: TESTS.md T9 prior-art collision check; RQ5 prototype workflow
contribution_unit: >
  A bounded prior-art note comparing one public-goods funding mechanism to this
  repo's contribution-legitimacy workflow, focused only on evidence and capture
  risks.
explicit_non_targets:
  - claim-status movement
  - governance change
  - reward or retained-value promise
  - issue-template change
  - live contribution-log entry on submission
expected_first_state: submitted
```

## End-To-End Trace

| stage | dry-run question | source support | required visible record | stop boundary |
|---|---|---|---|---|
| 1. Orient | Can the contributor find a low-governance target from public files? | `CONTRIBUTING.md`, `RESEARCH-AGENDA.md`, and `TESTS.md` expose research questions and tests. | The pilot record names the target and why it is reviewable as a bounded research note. | Do not designate an official public pilot invitation from this scaffold. |
| 2. Submit | Does the intake path preserve the contribution unit, target, evidence, risk, and accountability context? | The RQ5 field-parity check shows the structured issue form covers most fields but may need explicit contributor/agent context. | The reviewer records whether identity/pseudonym and agent assistance were visible. | Do not edit issue templates or adopt disclosure policy. |
| 3. Triage | Is there one primary contribution class and a reason for secondary effects? | `CONTRIBUTION-STANDARDS.md` and the handoff map support primary-class assignment. | Review note names `research` as primary and `review` as secondary, with the deciding reason. | Do not change contribution-class definitions. |
| 4. Evidence Check | Which evidence minimum applies before substantive review? | Research-class standards require stable sources and mechanism comparison. | Review note lists the source sufficiency check and any missing mechanism comparison. | Do not lower evidence requirements for the first pilot. |
| 5. Governance Boundary | Does the contribution try to move protected state? | T3 and T11 traces show useful value must be separated from policy or claim movement. | One decisive boundary sentence says what is reviewable and what remains unadopted. | Stop before claim status, governance, reward, public posture, or real record changes. |
| 6. Review State | Can the reviewer choose a state with reconstructable rationale? | RQ4 rationale-minimums and existing workflow traces support state-specific rationale. | Rationale pairs the state with the decisive gap, accepted unit, revision route, or dispute point. | Do not adopt review policy, appeal rules, reviewer authority, or response-time promises. |
| 7. Loss Notes | Is useful residue preserved without implying future reward or acceptance? | T10 and T11 scaffolds support `loss_notes` and retained-marker boundaries. | Loss notes name preserved value and a promise not created. | Do not create reward, rights, legal, or retained-value meaning. |
| 8. Log Eligibility | Is a live `CONTRIB-NNNN` entry justified? | The log schema can represent reviewed work, but synthetic traces stay in `SAMPLE-*` space. | The record states whether the item is log-eligible and why. | Do not edit `CONTRIBUTIONS-LOG.md` unless a real contribution has been reviewed. |
| 9. Contestability | Can the contributor see what could be corrected or disputed? | The handoff and adverse-decision traces support a contestability marker. | The record names the challengeable point without promising forum, timing, or authority. | Do not adopt an appeal or dispute process. |

## Dry-Run Outcome Branches

The first real pilot does not need to end in acceptance to be useful. It needs a
record that makes the outcome inspectable.

| possible state | useful if the record shows | not enough if |
|---|---|---|
| `accepted` | The accepted unit is narrow, evidence-backed, and does not move protected state. | Acceptance silently upgrades a claim, governance rule, reward meaning, or public posture. |
| `needs_revision` | Missing evidence, source limits, or mechanism comparison are specific enough for the contributor to act. | Revision is a vague request for founder intuition or better fit. |
| `not_accepted` | Useful residue is preserved and the non-accepted part is named. | The record erases the contribution or hides the decisive reason. |
| `contested` | The disputed point is visible and separable from any unadopted appeal process. | The state implies response-time promises or appeal rights not yet adopted. |
| `adversarial` | Manipulation, spam, or capture evidence is separated from ordinary weak contribution quality. | Bad-faith labeling substitutes for rationale. |

## Coherence Checks For The Later Pilot

A later first-pilot packet should pass these coherence checks before anyone
treats it as RQ5 evidence:

1. **Surface continuity:** the same contribution unit is visible from intake to
   review rationale to log-eligibility decision.
2. **Class continuity:** the primary contribution class does not change without
   an explicit reason.
3. **Evidence continuity:** the applied evidence minimum follows from the
   primary class.
4. **Boundary continuity:** protected-state boundaries are named before any
   review state is interpreted as adoption.
5. **Residue continuity:** deferred value is preserved in `loss_notes` without
   becoming reward, rights, or future-acceptance language.
6. **Record continuity:** the final record can be reconstructed from public
   files, issue/PR text, and review notes without private founder context.

## Readiness Implication

The safest first real pilot remains a bounded, source-backed prior-art or review
contribution. This dry run narrows the preparation burden: the pilot should be
reviewed as a continuity test, not as proof that the full legitimacy workflow
works.

The pilot would strengthen RQ5 only if it produces a visible packet with:

- a public submission surface;
- one primary contribution class;
- explicit source or reasoning sufficiency;
- a state-specific rationale;
- protected-boundary language where needed;
- `loss_notes` when value is revised, deferred, or not accepted;
- a log-eligibility decision; and
- a contestability marker when the decision contains a disputable point.

## Later Adoption Questions

- Should `CONTRIBUTING.md` eventually include a short first-pilot continuity
  checklist, or should this remain an internal project scaffold until a pilot
  completes?
- Should the structured GitHub contribution form be adjusted before the first
  pilot to collect contributor/accountability context explicitly?
- Which artifact should hold the first real pilot review packet: an issue, a PR,
  a project file, or a contribution-log entry after review?
- What evidence would be enough to mark T3, T10, T11, or RQ5 stronger without
  prematurely marking them passed?

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, sanctioned, or rewarded.
- No issue template, contribution template, contribution standard, review
  policy, reviewer authority, governance rule, appeal process, response-time
  promise, rights policy, reward meaning, claim status, test pass/fail state,
  public posture, or live contribution record changed.
- This is draft workflow evidence for later RQ5 review, not active contribution
  policy.
