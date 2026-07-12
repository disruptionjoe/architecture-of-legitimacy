---
artifact_type: first_pilot_construction_fork_table
status: draft_review_prep_scaffold
created: 2026-07-12
research_question: RQ5 prototype workflow
claim_targets:
  - C2 coupled protocol stack
  - C3 legitimacy as design variable
test_targets:
  - T3 first workflow simulation
  - T9 prior-art collision check
  - T10 contribution log prototype
  - T11 legitimacy trace workflow
dependency_targets:
  - RQ1 contributor and contribution eligibility
  - RQ2 contribution taxonomy
  - RQ3 initial value rubrics
  - RQ4 cadence and evaluation
  - RQ6 governance transition
  - RQ7 voice, exit, and retained value
  - RQ8 attack and capture modeling
  - RQ9 reward logic
  - RQ10 generalization
  - C7/T8 AI role boundary
governance_role: non_adopted_construction_audit
constitutional: false
claim_status_change_requested: false
test_status_change_requested: false
---

# First-Pilot Construction Fork Table

Status: draft review-prep construction audit, not adopted workflow, review
authority, construction verdict, policy, public posture, claim-status,
test-status, or contribution-record movement.

This table applies the repo operating note on construction forks to the current
first-pilot review-prep stack. It identifies terms that have a tempting
standard/default construction and a project-native construction. It does not
settle which construction a later governed review must use, and it does not
make any construction live.

## Purpose

The first-pilot packet map names the sections a later governed review could
inspect. This file adds one more safety layer:

```text
Before a reviewer treats a load-bearing term as obvious, name which
construction of that term is being used and what must stay unresolved.
```

The immediate value is not a new decision. The value is preventing later review
from silently importing default meanings for contribution, legitimacy, value,
review authority, reward, or transfer when this repo studies those objects as a
coupled protocol stack.

## Source Surfaces

- `AGENTS.md`
- `CLAIMS.md`
- `LEGITIMACY-SCHEMA.md`
- `PROTOCOL-STACK.md`
- `projects/first-pilot-review-prep-read-order.md`
- `projects/pilot-review-readiness/2026-07-10-first-pilot-governed-review-packet-map.md`
- `projects/prototype-workflow/2026-07-09-rq5-review-prep-bundle-map.md`
- `projects/second-ring-synthesis/2026-07-09-second-ring-first-pilot-stop-stack.md`

No external sources are introduced here. Existing repo artifacts are treated as
review-prep evidence, not instructions, verdicts, adopted policy, or live
process.

## Fork Table

| object | standard/default construction to avoid silently importing | project-native construction to name explicitly | why the fork matters | current use rule |
|---|---|---|---|---|
| Contribution | A GitHub issue, pull request, task, comment, or useful effort. | An evidence-bearing proposed change that must pass eligibility, class, validation, rationale, log, rights, and reward boundaries before it can carry institutional meaning. | A later packet could look complete because a normal repo artifact exists while still lacking the legitimacy trace this project studies. | Keep `target_selected: false`; do not treat any artifact as a live contribution. |
| Legitimacy | Correctness, popularity, maintainer approval, consensus, or procedural cleanliness. | Participant-facing acceptability under visibility, contestability, voice, exit with retained record, adaptive rule change, bounded authority, and non-capture conditions. | A review can be accurate but still illegitimate by this repo's own schema. | Use legitimacy as a review question, not as a verdict or status movement. |
| Accepted record | A merged change, closed issue, logged entry, or accepted review state. | A preserved trace from submission evidence through validation path, accepted content, loss notes, contestability, and any rights marker. | The repo's S7 reading depends on trace preservation, not just record existence. | Do not create a live contribution-log entry or call any synthetic packet accepted. |
| Value | Market price, effort spent, founder taste, reviewer preference, or reward amount. | A contestable rubric question across clarity, truth-seeking, formal rigor, coordination value, novelty, legitimacy value, and capture resistance before reward meaning exists. | Value language can leak into reward or rights claims before the project has adopted reward logic. | Do not score, rank, convert, reward, or assign retained value. |
| Review authority | Whoever can merge, moderate, administer, or give an opinion. | A bounded governed-review role whose powers, evidence base, rationale duties, appeal path, and second-ring stops are named before use. | Default maintainer authority could bypass the founder-phase and reviewer-capacity questions. | Keep `review_authority: none_assigned`; do not appoint reviewers or launch review. |
| Source trace | A summary, citation list, memory of the case, or private context. | Publicly inspectable target, neighboring-system, source, mechanism, adverse-path, limitation, and source/inference fields. | Missing source fields are the first hard stop in the current first-pilot stack. | Keep `source_trace_state: source_trace_still_missing`; do not fill fields locally. |
| AI support | AI as judge, consensus proxy, source of reviewer confidence, or hidden summarizer. | AI as contestable support for synthesis, critique, drafting, or trace organization, with human/governed authority retained elsewhere. | AI can appear to solve ambiguity while becoming an opaque legitimacy substitute. | Do not assign AI final authority, select tools, or turn model output into evidence. |
| Reward or retained claim | A payment, token, ownership stake, entitlement, or governance weight. | A no-current-reward state plus an unresolved retained-record and retained-value question for later governed review. | Reward language can create legal, financial, rights, or governance meaning prematurely. | Keep `reward_state: no_current_reward`; do not create rights, payouts, or governance weight. |
| Governance transition | Decentralization language, DAO-like voting, founder promise, or informal community input. | Explicit founder-led phase constraints, named powers, transition evidence, rollback conditions, and governed stops. | A public pilot could imply legitimacy-preserving decentralization before the project has earned it. | Do not move founder powers, phase state, emergency rules, or governance policy. |
| Transfer or portability | A generalizable best practice, reusable governance package, or exportable process. | Horizon-only transfer until target-context evidence, source traces, second-ring stops, process-drag review, and public-language review exist. | A useful local packet could be misread as permission to port governance machinery elsewhere. | Keep `transfer_state: horizon_only`; do not choose a target, claim portability, or export process. |

## Briefing Rule For Later Review

A later first-pilot branch brief should add a short construction row for every
load-bearing object it uses:

```yaml
object: <term>
construction_used: standard | project_native | unresolved
reason: <why that construction is being used in this section>
unsettled_alternative: <what the other construction might still show>
protected_boundary: <what this construction choice does not authorize>
```

If the construction is unresolved, the brief should say so plainly instead of
defaulting to either side. If a construction choice would settle policy,
reviewer authority, rights, reward, transfer, public language, claim status, or
test status, it belongs in Joe or governed review, not unattended Progress.

## Safe Local Consequence

This table supports one local conclusion:

```text
The first-pilot review-prep stack now has a visible construction-fork checklist
for its load-bearing terms, but every fork remains review-prep only until a
later governed review explicitly names and justifies the construction in use.
```

That conclusion does not authorize target selection, packet filling, live
review, record creation, reviewer assignment, source-lane choice, scoring,
reward, rights, governance movement, transfer, public posture movement, claim
movement, test movement, external action, or any real contribution decision.

## Boundary Notes

- No fork is settled here.
- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, labeled, monitored, sanctioned, rewarded, or used as transfer
  evidence.
- No external source was added.
- No live target, neighboring system, source lane, source packet, record
  surface, issue, pull request, public invitation, reviewer authority,
  template edit, contribution standard, contribution-log entry, monitoring
  surface, AI tool, model, reward mechanism, rights promise, disclosure rule,
  sanction rule, transfer target, public audience, or governance phase was
  created or selected.
- No contribution class, review path, eligibility rule, disclosure duty,
  prior-art collision verdict, novelty judgment, source-packet upgrade,
  claim-status movement, test pass/fail movement, review policy, rights policy,
  reward meaning, governance rule, capture mitigation, monitoring rule,
  sanction, AI-use policy, transfer policy, public posture, or external action
  changed.
