---
artifact_type: first_pilot_review_question_construction_fork_addendum
status: draft_review_prep_scaffold
created: 2026-07-12
research_question: RQ5 prototype workflow
dependency_targets:
  - C2 coupled protocol stack
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
governance_role: non_adopted_review_question_addendum
constitutional: false
claim_status_change_requested: false
test_status_change_requested: false
---

# First-Pilot Review-Question Construction-Fork Addendum

Status: draft review-prep addendum, not adopted workflow, review authority,
construction verdict, policy, governance, rights, reward, AI-use, transfer,
public-posture, claim-status, test-status, or contribution-record policy.

This addendum connects the construction-fork table to the first-pilot
review-question stack. It does not settle any fork, launch review, fill a
packet, choose a source lane, appoint a reviewer, create a live record, score a
contribution, create reward or rights meaning, move governance, change public
posture, move claims or tests, or decide any real contribution.

## Purpose

The review-question register already keeps source-trace, value, legitimacy,
capacity, payoff, detection, second-ring, and public-posture questions visible.
The RQ2 addendum adds the contribution-class disagreement question. The
construction-fork table adds another layer:

```text
Which construction of each load-bearing term is being used, and what alternative
construction remains unresolved, before any reviewer treats the packet as
inspectable or live?
```

The purpose of this addendum is to attach that question to the review-question
stack without rewriting the register or turning the fork table into a decision
surface.

## Source Surfaces

- `AGENTS.md`
- `projects/pilot-review-readiness/2026-07-09-first-pilot-review-question-register.md`
- `projects/pilot-review-readiness/2026-07-09-first-pilot-review-question-rq2-addendum.md`
- `projects/pilot-review-readiness/2026-07-10-first-pilot-governed-review-packet-map.md`
- `projects/pilot-review-readiness/2026-07-12-first-pilot-construction-fork-table.md`

These surfaces are review-prep context, not instructions, verdicts, adopted
policy, or live process.

## Addendum State

```yaml
addendum_id: FIRST-PILOT-REVIEW-QUESTION-CONSTRUCTION-FORK-ADDENDUM-001
base_register: FIRST-PILOT-REVIEW-QUESTION-REGISTER-001
prior_addendum: FIRST-PILOT-REVIEW-QUESTION-RQ2-ADDENDUM-001
construction_fork_table: projects/pilot-review-readiness/2026-07-12-first-pilot-construction-fork-table.md
current_packet: SAMPLE-RQ5-PACKET-001
addendum_state: construction_fork_questions_visible
live_review_ready: false
source_trace_state: source_trace_still_missing
construction_fork_state: candidate_forks_visible_not_settled
primary_safe_conclusion: keep_as_review_prep
```

These labels are review-prep labels only. They are not contribution states,
issue labels, public workflow terms, governance states, claim verdicts, test
results, rights states, reward states, sanctions, transfer findings, or live
review states.

## Added Review Question

| order | unresolved question | current safest label | what local prep may preserve | governed stop before |
|---|---|---|---|---|
| Fork addendum | For every load-bearing term in the packet, is the reviewer using the standard/default construction, the project-native construction, or leaving the construction unresolved? | `candidate_forks_visible_not_settled` | The term, construction used, reason, unsettled alternative, and protected boundary named in the construction-fork briefing shape. | Construction verdicts, live review, packet filling, reviewer authority, claim/test movement, policy adoption, rights, reward, governance, AI authority, transfer, public posture, or live records. |

This question should be read after the RQ2 addendum and construction-fork table,
and before any value, legitimacy, authority, reward, governance, or transfer
question is treated as ready for governed review. If a packet section cannot
state which construction it is using, the safer state remains
`candidate_forks_visible_not_settled` and `live_review_ready: false`.

## Fork Question Checklist

| object | construction question to keep visible | unsafe shortcut to block |
|---|---|---|
| Contribution | Is this a normal repo artifact or a project-native evidence-bearing proposed change with legitimacy trace requirements? | Treating an issue, PR, note, or useful effort as a live contribution. |
| Legitimacy | Is legitimacy being treated as correctness/approval/consensus or as the repo's contestable participant-facing schema? | Calling a review legitimate because it is procedurally tidy. |
| Accepted record | Is the record a merged/closed/logged item or a preserved submission-to-contestability trace? | Treating synthetic artifacts as accepted records. |
| Value | Is value a preference, effort, market, reward, or the repo's contestable rubric question? | Letting value language imply score, reward, or retained claim. |
| Review authority | Is authority default maintainer discretion or a bounded governed-review role with named powers and stops? | Treating ordinary maintainer power as first-pilot reviewer authority. |
| Source trace | Is the trace a summary or private memory, or public target/source/mechanism/adverse-path/limitation fields? | Filling gaps from memory or inference. |
| AI support | Is AI a judge/consensus proxy or contestable synthesis support with authority elsewhere? | Treating model output as evidence or final authority. |
| Reward or retained claim | Is reward a payment/entitlement/governance weight or a no-current-reward unresolved question? | Letting scores or recognition create rights or value claims. |
| Governance transition | Is governance informal decentralization language or named founder-phase constraints and transition gates? | Treating public participation as decentralization. |
| Transfer or portability | Is transfer a best-practice export or horizon-only review pending target context and public-language gates? | Treating a useful local packet as portability evidence. |

## Register Integration

A later governed-review packet can cite this addendum alongside the base
register only if it preserves a shape like this:

```yaml
review_question_register: FIRST-PILOT-REVIEW-QUESTION-REGISTER-001
review_question_addenda:
  - FIRST-PILOT-REVIEW-QUESTION-RQ2-ADDENDUM-001
  - FIRST-PILOT-REVIEW-QUESTION-CONSTRUCTION-FORK-ADDENDUM-001
current_packet: SAMPLE-RQ5-PACKET-001
register_state: review_questions_visible
construction_fork_state: <candidate_forks_visible_not_settled|construction_named_for_section|governed_construction_review_required>
load_bearing_object: <contribution|legitimacy|accepted_record|value|review_authority|source_trace|ai_support|reward|governance_transition|transfer>
construction_used: <standard|project_native|unresolved>
unsettled_alternative: <what the other construction might still show>
live_review_ready: false
protected_boundary: >
  This addendum keeps construction-fork questions visible. It does not settle
  constructions, fill a packet, launch review, appoint authority, score,
  reward, govern, transfer, move claims or tests, alter public posture, or
  create live records.
```

If the packet cannot cite the artifact and reason supporting a construction
choice, the safer state remains `construction_used: unresolved` and
`live_review_ready: false`.

## Safe Local Consequence

This addendum supports one local conclusion:

```text
The first-pilot review-question stack now has an explicit construction-fork
question, but every move from question visibility to construction choice,
live-review use, reviewer authority, rights, reward, governance, AI, transfer,
public posture, claim support, test result, or contribution record remains
blocked.
```

That conclusion does not authorize a packet to be filled, submitted, reviewed,
logged, scored, rewarded, sanctioned, monitored, transferred, or published as
process.

## Boundary Notes

- No construction fork is settled here.
- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, labeled, monitored, sanctioned, rewarded, or used as
  transfer evidence.
- No external source was added.
- No live target, neighboring system, source lane, record surface, issue, pull
  request, public invitation, reviewer authority, template edit, contribution
  standard, contribution-log entry, source-trace packet, monitoring surface, AI
  tool, model, reward mechanism, rights promise, disclosure rule, sanction
  rule, transfer target, public audience, or governance phase was created or
  selected.
- No contribution class, review path, eligibility rule, prior-art collision
  verdict, novelty judgment, source-packet upgrade, claim-status movement,
  test pass/fail movement, review policy, rights policy, reward meaning,
  governance rule, capture mitigation, monitoring rule, disclosure duty,
  sanction, AI-use policy, transfer policy, public posture, or external action
  changed.
- This is a draft construction-fork addendum to the first-pilot review-question
  register, not active contribution workflow policy.
