---
artifact_type: governance_package_do_not_port_signal_register
status: signal_register
created: 2026-07-12
research_target: RQ10 generalization
governance_role: non_adopted_internal_review_artifact
constitutional: false
transfer_policy_change_requested: false
claim_status_change_requested: false
---

# Governance Package Do-Not-Port Signal Register

Status: do-not-port signal register; no portability verdict assigned.

Purpose: define the evidence signals that should make later governance-package
portability review defer, reject, or remove a component before treating it as
portable, adaptable, useful, or ready for target-context discussion.

This file does not recommend copying governance machinery into another
repository, does not evaluate another repository, does not assign a
portability class to any component, does not classify any component as
do-not-port, does not change transfer policy, does not change public posture,
and does not create rights, reward, governance, contributor, or
cross-repository commitments.

## Source Surfaces Used

- `projects/governance-package-portability/README.md`
- `projects/governance-package-portability/01-governance-package-inventory.md`
- `projects/governance-package-portability/02-portability-evidence-boundary.md`
- `projects/governance-package-portability/03-process-drag-check.md`
- `projects/generalization/2026-07-06-rq10-transfer-failure-boundary.md`
- `projects/generalization/2026-07-09-rq10-first-pilot-transfer-risk-triage.md`
- `projects/generalization/2026-07-09-rq10-c8-public-language-boundary.md`
- `RESEARCH-AGENDA.md`
- `TESTS.md`

No other repository supplies evidence for this artifact. These notes are
boundary work over already prepared local portability and RQ10 review-prep
surfaces.

## Why This Register Is Needed

The inventory frame asks later reviewers to classify candidate components as
universal, research-program core, optional enhancement, target-specific, or
do-not-port. The evidence boundary says those classes cannot be assigned from
labels alone. The process-drag check then asks whether legitimacy gain exceeds
ceremony, stale-surface risk, duplicate authority, and attention cost.

This register adds the negative side of that review:

```text
What evidence would make a component unsafe, premature, too costly, or too
misfit to move, even if it looks useful in the origin setting?
```

The useful output is a signal layer, not a verdict layer. A later reviewer can
use the signals to stop an over-eager port plan before process becomes false
legitimacy.

## Signal Labels

Use these labels before any portability classification. They are review
signals, not verdicts.

| label | meaning | forbidden inference |
|---|---|---|
| `native_surface_sufficient` | The target already has a surface that solves the same problem well enough. | The origin component is useless everywhere. |
| `authority_collision_visible` | The component would create a second place where decisions, truth, or ownership appear to live. | The existing target surface must be replaced. |
| `maintenance_burden_unowned` | The component needs upkeep, pruning, or interpretation but no owner or expiry condition is visible. | All maintenance-heavy process should be rejected. |
| `decision_use_absent` | The component exists, but later work does not read, cite, or act on it. | The component could never become useful after redesign. |
| `ceremony_exceeds_clarity` | The component lengthens the process without improving source facts, inference boundaries, contestability, or review quality. | The component is only ceremonial in every context. |
| `shadow_truth_risk_high` | The component can become stale memory, hidden canon, or unreviewed claim status. | Memory, ledgers, or summaries are categorically bad. |
| `target_vocabulary_misfit` | The component imports origin language that weakens target-native rigor. | The target should never borrow concepts from elsewhere. |
| `external_consequence_pressure` | The component would imply public, legal, financial, civic, governance, rights, reward, or participant commitments. | The component is forbidden forever. |
| `evidence_substitute_missing` | The target cannot expose the evidence the component requires, and no safe substitute has been defined. | Private or sensitive contexts cannot ever be legitimate. |
| `removal_condition_missing` | The component has no condition under which it should be removed, retired, or thinned. | Any component without a removal rule is already harmful. |

## Component Signal Register

| component class | do-not-port signal to look for | evidence before reopening | safe local consequence |
|---|---|---|---|
| Anchored steward | Steward role would duplicate owner judgment, create identity theater, or blur who can decide. | A target-native authority gap plus evidence that a thin steward prevents drift without replacing local truth. | Record `authority_collision_visible` or `native_surface_sufficient`; leave the component unclassified. |
| Run records and closeout | Records accumulate without later decision use, or the record format pressures agents to invent work. | A before/after chain where a prior record avoided duplication, preserved blockers, or improved selection. | Record `decision_use_absent` or `ceremony_exceeds_clarity`; do not impose receipt fields. |
| Claim ledger and status vocabulary | Ledger vocabulary competes with existing canon, theorem status, or accepted public truth. | A specific overclaim risk that native status surfaces cannot already handle. | Record `authority_collision_visible`; do not create a target ledger. |
| Kill criteria and path-kill records | Kill labels either never fire or suppress legitimate exploration by appearing more certain than the evidence. | A path paused, killed, or reopened under explicit criteria that remain contestable. | Record `ceremony_exceeds_clarity`; do not mark target paths killed. |
| Promotion gates | Gates add ceremony after decisions are already obvious or already governed elsewhere. | A case where the gate delayed, narrowed, or rejected premature movement. | Record `native_surface_sufficient` or `decision_use_absent`; do not add gate policy. |
| Memory summary and append-only memory | Memory duplicates canon, grows stale, or becomes shadow truth for later agents. | Evidence that memory reduced repeated context loading while staying subordinate to canonical surfaces. | Record `shadow_truth_risk_high`; do not create memory surfaces. |
| Next-trigger plan and cadence | Cadence pressures agents to manufacture low-value work or chase easy closure. | Evidence that triggers selected worthy work and had no-worthy-work stops that were actually used. | Record `maintenance_burden_unowned`; do not schedule cadence. |
| Persona registry and adversarial review | Personas become stylized labels without materially different objections or better synthesis. | A review where distinct perspectives found failures a single pass likely missed. | Record `ceremony_exceeds_clarity`; do not add registry machinery. |
| Absorber discipline and same-neighbor-data tests | The test becomes novelty theater instead of an overclaim constraint. | A comparison that narrowed claims or exposed non-absorption without public posture inflation. | Record `target_vocabulary_misfit`; do not make novelty verdicts. |
| Governance-change ledger | The ledger costs more attention than the process changes it explains. | A governance change whose reason, authority, and later effect stayed reviewable because of the ledger. | Record `maintenance_burden_unowned`; do not create a ledger. |

## Cross-Cutting Do-Not-Port Tests

Before a later evidence packet assigns a component any portability class, it
should pass these negative tests.

| test | review question | signal if failed |
|---|---|---|
| Native sufficiency test | What target-native surface already solves this problem, and why is it insufficient? | `native_surface_sufficient` |
| Authority test | Would this create a second source of truth, decision, status, or ownership? | `authority_collision_visible` |
| Use test | Has later work actually used this component to decide, resume, stop, or contest? | `decision_use_absent` |
| Vocabulary test | Does the component preserve target-native rigor, or import origin terms that hide the real object? | `target_vocabulary_misfit` |
| Maintenance test | Who prunes, updates, expires, or removes the component? | `maintenance_burden_unowned` |
| Evidence test | Can the target safely expose the facts the component needs, or define a substitute? | `evidence_substitute_missing` |
| Public-consequence test | Would the component imply rights, rewards, governance power, sanctions, public readiness, or external commitment? | `external_consequence_pressure` |
| Removal test | What evidence would make the component thinner, deferred, rejected, or retired? | `removal_condition_missing` |

## Minimum Signal Record Shape

A later reviewer can record a signal without assigning a verdict by using this
shape:

| field | required content |
|---|---|
| Component | Candidate governance-package component. |
| Signal label | One or more labels from this register. |
| Source fact | The local source or trace that makes the signal visible. |
| Reviewer inference | Why the signal may matter, explicitly marked as inference. |
| Native overlap | Existing target surface or target evidence requirement at risk. |
| Reopen evidence | What would need to be shown before classification could continue. |
| Safe consequence | Defer, thin, remove from candidate set, or ask for governed review. |
| Stop boundary | Any adoption, public posture, rights, reward, governance, or cross-repo action boundary. |

## Relationship To Other Portability Artifacts

This register is subordinate to the evidence boundary and process-drag check.
It does not replace source evidence, target conflict review, or governed
classification.

Use the artifacts this way:

1. Use the inventory frame to name candidate components.
2. Use the evidence boundary to separate source facts, observed effects,
   reviewer inference, and stop boundaries.
3. Use the process-drag check to compare legitimacy gain against attention
   cost, ceremony, duplicate authority, and staleness.
4. Use this register to name the signal that would justify deferral, rejection,
   thinning, or removal before any port plan.

## Safe Local Consequence

This register allows one narrow conclusion:

```text
The portability study now has do-not-port signal labels, but no
governance-package component is classified, recommended, rejected, copied,
exported, or adopted.
```

That conclusion lets later RQ10 work stop a weak portability move without
turning review-prep labels into transfer policy.

## Current Non-Conclusions

- No governance-package component is portable.
- No governance-package component is do-not-port.
- No origin, transfer, or brownfield verdict is accepted.
- No target repo, target context, second pilot, or port plan is selected,
  ranked, recommended, or requested.
- No transfer policy, C8 status, claim status, public posture, governance rule,
  participant right, reward meaning, or contributor commitment changes.
- No cross-repository action is requested.

## Stop Conditions

Stop for Joe or governed review before:

- recommending, copying, exporting, adopting, or rejecting a governance-package
  component for another repository;
- assigning a portability class or do-not-port verdict to any component;
- selecting, ranking, or naming a target repo, client, civic setting, funding
  process, public audience, or second pilot;
- changing C8 wording, claim status, test status, transfer policy, governance,
  contribution standards, rights, reward, AI policy, or public posture;
- creating a live issue, pull request, contribution-log entry, review packet,
  public invitation, or external publication surface;
- or taking any non-GitHub external action.

## Boundary Notes

- No other repository supplies evidence here, and no other repository was
  edited.
- No governance-package component was copied.
- No portability class, target recommendation, process adoption, public
  language, or do-not-port verdict was approved.
- This is a draft RQ10 review-prep artifact, not transfer policy, a port plan,
  or a portability finding.
