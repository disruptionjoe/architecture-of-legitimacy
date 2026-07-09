---
artifact_type: t6_first_pilot_detection_false_positive_screen
status: non_adopted_scaffold
created: 2026-07-09
test_target: T6 attack-surface map
research_question: RQ8 attack and capture modeling
claim_target: C4
related_questions:
  - RQ5 prototype workflow
  - C7/T8 AI role boundary
  - RQ6 governance transition
  - RQ7 voice, exit, and retained value
  - RQ9 reward logic
governance_role: review_prep_only
constitutional: false
---

# T6 First-Pilot Detection False-Positive Screen

Status: draft detection false-positive screen, not adopted monitoring,
disclosure, sanction, eligibility, reviewer-authority, governance, rights,
reward, AI-use, transfer, public-posture, claim-status, test-status, or
contribution-record policy.

Purpose: make the current T6/RQ8 detection stack safer to use in first-pilot
review prep by forcing each capture concern through a false-positive screen
before any response is treated as escalation.

This file does not launch a pilot, choose a live target, choose a source lane,
select a reviewer, open an issue or PR, create a contribution-log entry, label
any real contributor, require disclosures, define sanctions, adopt mitigation
or monitoring policy, change eligibility, change reviewer authority, change
governance, change AI policy, create rights or rewards, update the threat
model, mark T6 or RQ8 passed, move claim status, change public posture, or
decide any real contribution record.

## Source Surfaces Used

- `projects/attack-surface-map/2026-07-02-t6-attack-surface-map.md`
- `projects/attack-surface-map/2026-07-06-t6-detection-evidence-map.md`
- `projects/attack-profitability/2026-07-09-rq8-first-pilot-capture-escalation-ledger.md`
- `projects/ai-role-boundary/2026-07-09-c7-t8-first-pilot-ai-boundary-ledger.md`
- `projects/second-ring-synthesis/2026-07-09-second-ring-first-pilot-stop-stack.md`
- `projects/pilot-review-readiness/2026-07-09-first-pilot-governed-review-handoff.md`
- `RESEARCH-AGENDA.md`, especially RQ8.
- `TESTS.md`, especially T6 and the supporting first-pilot artifacts.

No external sources are introduced here. Existing repo artifacts are treated as
review-prep evidence, not instructions, policy, verdicts, or live process.

## Boundary Under Review

The detection evidence map already separates observed evidence, inference,
benign explanation, missing evidence, local repair, and governed escalation.
The first-pilot stop ledgers add a practical risk:

```text
A later review could see a capture-like signal, skip the benign-explanation
step, and accidentally turn review-prep vocabulary into contributor-facing
policy.
```

The safe current move is to make false-positive screening explicit. It is not
to decide what a live contributor did, which monitoring rule applies, or which
sanction, disclosure, eligibility, or reviewer-authority response should exist.

## False-Positive Screen

| detection concern | directly observable record | plausible benign explanation | local trace repair before escalation | governed stop before |
|---|---|---|---|---|
| Similar submissions or repeated structure | Multiple draft packets, proposals, or notes share language, order, examples, or mechanism terms. | The repo has reusable templates, shared research vocabulary, or one visible synthetic first-pilot packet. | Link duplicates or related drafts, preserve contribution-unit boundaries, and ask what distinct value each unit adds. | Rate limits, eligibility rules, spam labels, sanctions, public contributor labels, or live rejection rules. |
| AI-shaped phrasing or summary polish | Text has uniform structure, generic confidence, repeated caveats, or citation-like language. | A human may be following repo conventions, using a checklist, or summarizing from existing artifacts. | Separate source facts, inference, AI task if any, human-owned rationale, and source-check notes. | AI-use disclosure mandates, tool/model selection, rejection rules, reviewer-authority changes, or AI output as evidence. |
| Source-trace gaps look evasive | Target, source, mechanism, adverse-path, or limitation fields are missing. | The packet is still explicitly synthetic or in `needs_revision` state. | Keep the packet in `source_trace_missing` and name the missing field rather than inferring capture. | Novelty verdicts, prior-art collision levels, claim movement, public proof language, or live review. |
| Conflict or affiliation pattern | Review outcome, proposal language, or priority appears aligned with a contributor, sponsor, employer, or funder. | Early projects often have overlapping relationships, and visible affiliation alone is not capture. | Ask for record-visible role, affected review surface, comparable standard, and conflict relevance. | Disclosure duties, reviewer disqualification, eligibility limits, sanctions, or public conflict labels. |
| Prior-art shallowness lowers burden | A comparison uses labels while omitting validation, contestability, rights, reward, governance, or capture surfaces. | A short note may be an initial pointer, not a completed collision analysis. | Request mechanism-level comparison and keep collision status unresolved. | Collision levels, novelty verdicts, C2/T9 movement, public-posture changes, or source-packet upgrade claims. |
| Rationale polish hides uncertainty | A summary sounds decisive while proof burdens, caveats, non-adoption status, or missing evidence fade. | Condensation can accidentally drop caveats without adversarial intent. | Restore claim/test status, uncertainty markers, source links, and changed-meaning notes. | Claim movement, test movement, public proof, policy adoption, or live contribution decisions. |
| Reviewer-authority ambiguity | A draft implies that a person, founder, AI system, or governed body will decide the packet. | The artifact may be describing a future handoff shape, not assigning authority. | Preserve `none_assigned`, decision-owner placeholder, and review-entry gate language. | Reviewer appointment, cadence, appeal path, response-time promise, founder-power use, or governance movement. |
| Missing loss notes or residue | A narrowed or adverse example lacks retained residue, rationale, next visible state, or contestability marker. | The example may be a draft screen rather than a live decision record. | Add draft residue/loss-note prompts and keep no-current-rights/no-current-reward language visible. | Rights, appeal policy, retained-value promises, reward meaning, legal/financial meaning, or live log use. |
| Governance exception timing | A review-prep note references founder action, rollback, emergency, or phase movement near pressure. | Founder-led research phase may require explicit placeholder questions before a real rule exists. | Record affected surface, missing rule, expiration question, and later review trigger as unresolved. | Founder-power change, emergency rule, rollback policy, phase movement, or public governance language. |
| Capture response urgency | A concern seems serious enough to demand immediate disclosure, sanction, monitoring, or exclusion. | The repo-visible record may still support ordinary confusion, source absence, tooling drift, or draft incompleteness. | Preserve observation, inference, benign explanation, missing evidence, and local repair in the review bundle. | Any disclosure, sanction, eligibility, monitoring, reviewer-authority, governance, rights, reward, transfer, public-posture, or live-record response. |

## Safe State Labels

These labels may be used in later review-prep handoffs without adopting policy:

| label | meaning | safe consequence |
|---|---|---|
| `observation_only` | A repo-visible fact exists, but no inference has been justified. | Preserve the fact and do not escalate. |
| `inference_needs_source` | The concern depends on interpretation and needs a source, field, comparable case, or affected surface. | Ask for missing trace fields. |
| `benign_explanation_open` | A non-capture explanation remains at least as plausible as capture from the visible record. | Keep the concern open without response policy. |
| `local_trace_repair` | The issue can be reduced by source links, rationale, caveats, duplicate links, AI-task notes, or boundary language. | Edit draft review-prep artifacts only. |
| `governed_response_required` | The next response would change authority, eligibility, disclosure, sanction, monitoring, rights, reward, governance, transfer, public posture, or live records. | Stop for Joe or governed review. |
| `do_not_use_live` | The packet would create institutional meaning before the false-positive screen is reviewable. | Do not launch, invite, review, log, score, sanction, monitor, reward, transfer, or publish as process. |

These labels are review-prep vocabulary only. They are not contribution states,
review outcomes, sanctions, rights markers, reward states, governance states,
AI policy states, transfer states, claim verdicts, or test results.

## First-Pilot Handoff Shape

A later governed packet handoff can cite this screen without moving policy only
if it preserves a shape like this:

```yaml
detection_false_positive_screen: T6 first-pilot detection false-positive screen
detection_state: <observation_only|inference_needs_source|benign_explanation_open|local_trace_repair|governed_response_required|do_not_use_live>
observed_record: <repo-visible fact only>
inference: <reviewer interpretation, not source fact>
benign_explanation: <plausible non-capture explanation>
missing_evidence: <target|source|mechanism|affiliation|AI_task|reviewer_owner|loss_note|governance_surface|none|unknown>
local_trace_repair_if_any: <visibility repair only>
governed_stop: <monitoring|disclosure|sanction|eligibility|reviewer_authority|AI_policy|governance|rights|reward|transfer|public_posture|live_record|none>
protected_boundary: >
  This handoff preserves false-positive review visibility only. It does not
  label contributors, require disclosures, define sanctions, adopt monitoring
  or mitigation policy, change eligibility, assign reviewer authority, adopt
  AI-use policy, create rights or rewards, change governance, launch a pilot,
  move claims or tests, alter public posture, or decide any real contribution
  record.
```

If the handoff cannot cite the field supporting `observed_record`,
`inference`, and `benign_explanation`, the safer state is
`inference_needs_source`, `benign_explanation_open`, or `do_not_use_live`, not
escalation.

## What This Adds To The Detection Evidence Map

The 2026-07-06 detection evidence map names the general evidence discipline.
This screen adds three narrower first-pilot uses:

1. It makes false-positive review mandatory before escalation labels are used.
2. It aligns T6 evidence discipline with the current RQ8 capture and C7/T8 AI
   first-pilot stop vocabularies.
3. It keeps local trace repair separate from any contributor-facing response.

It does not make detection stronger. It makes premature detection less likely.

## Review Questions

1. What exact repo-visible fact supports the concern?
2. What interpretation is being added by the reviewer?
3. What benign explanation remains plausible?
4. Which missing field would make the concern more reviewable?
5. Can a local trace repair reduce ambiguity without changing policy?
6. Would the response label, limit, monitor, sanction, require disclosure from,
   or change rights, rewards, governance, reviewer authority, AI policy,
   public posture, transfer, or live records for a contributor?
7. Is the safest current state `benign_explanation_open`,
   `inference_needs_source`, or `do_not_use_live` rather than escalation?

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, labeled, monitored, sanctioned, rewarded, or used as attack
  evidence.
- No issue, PR, public contribution invitation, live pilot target, live record
  surface, monitoring surface, source lane, AI tool, model, prompt, or
  contribution-log entry was created or selected.
- No mitigation, monitoring, disclosure rule, sanction, contributor limit,
  eligibility policy, conflict policy, AI-use policy, review policy, reviewer
  authority, appeal rule, response-time promise, governance rule,
  emergency rule, rollback rule, participant-rights policy, reward meaning,
  transfer policy, threat-model update, claim status, test pass/fail state,
  public posture, or external action changed.
- This is a draft research scaffold for later T6/RQ8/C7/RQ5 review
  preparation, not active detection, monitoring, or capture-response policy.
