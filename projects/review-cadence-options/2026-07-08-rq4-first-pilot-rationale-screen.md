---
artifact_type: first_pilot_rationale_screen
status: draft_review_prep_scaffold
created: 2026-07-08
research_target: RQ4 cadence and evaluation
depends_on:
  - RQ5 prototype workflow
  - T3 first workflow simulation
  - T10 contribution log prototype
  - T11 legitimacy trace workflow
governance_role: non_adopted_first_pilot_rationale_screen
constitutional: false
---

# RQ4 First-Pilot Rationale Screen

Status: draft review-prep scaffold, not adopted review, cadence, appeal,
dispute, reviewer-authority, response-time, contribution-log,
public-posture, claim-status, or contribution-record policy.

This screen applies the existing RQ4 rationale-minimum and contestability
scaffolds to the synthetic RQ5 first-pilot packet. It does not launch a pilot,
choose a live record surface, open an issue or PR, edit templates, adopt review
policy, assign reviewer authority, create appeal rights, promise response
times, change claim or test status, create rights or rewards, change
governance, alter public posture, or decide any real contribution.

## Purpose

The synthetic first-pilot packet already gives the repo a non-live object with
class, evidence, protected-boundary, loss-note, log-eligibility,
contestability, and second-ring stop screens. The RQ4 question is narrower:

```text
Can a first-pilot review record preserve the decisive reason and next visible
state without turning review preparation into review policy?
```

This file keeps that rationale screen separate from any live pilot decision.

## Source Surfaces

- `projects/review-cadence-options/2026-07-07-rq4-rationale-minimums-map.md`
- `projects/review-cadence-options/2026-07-06-rq4-adverse-review-contestability-boundary.md`
- `projects/prototype-workflow/2026-07-07-rq5-hypothetical-first-pilot-packet.md`
- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-review-queue-map.md`
- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-review-packet-checklist.md`
- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-second-ring-stop-map.md`
- `projects/first-ring-synthesis/2026-07-07-first-ring-scaffold-crosswalk.md`
- `CONTRIBUTION-STANDARDS.md`
- `templates/contribution-proposal.md`
- `templates/contribution-log-schema.md`

## Packet Held Constant

This screen uses the same synthetic packet identity as the RQ5 hypothetical
first-pilot packet.

```yaml
packet_id: SAMPLE-RQ5-PACKET-001
record_surface_for_this_artifact: draft project artifact
live_record_surface: undecided; requires Joe/governed review before use
primary_class: research
secondary_effects:
  - review
candidate_target_shape: >
  one source-backed prior-art or mechanism-comparison note addressing a live
  test, research question, or existing scaffold
synthetic_review_state: needs_revision
live_log_entry: none
```

`needs_revision` is a synthetic packet outcome for this scaffold only. It is
not a live review decision.

## First-Pilot Rationale Fields

A later live review record should not adopt these fields without review. For
prep purposes, this screen shows the minimum visible rationale shape the first
pilot would need.

| field | synthetic packet value | why it matters | protected boundary |
|---|---|---|---|
| `submitted_object` | One bounded source-backed prior-art or mechanism-comparison note, still hypothetical. | The review object must be stable before it is classified or narrowed. | Do not choose a real target or invite a contributor. |
| `review_state` | `needs_revision` as a synthetic outcome. | Missing target and source detail should be visible, not absorbed into private judgment. | Do not create a live review state or contribution-log entry. |
| `decisive_reason` | Packet shape is coherent, but it lacks a selected target, named neighboring system, stable sources, source/inference split, and limitation statement. | A future reader can see what would make the packet reviewable. | Do not mark RQ4, RQ5, T3, T10, or T11 passed. |
| `evidence_gap` | Target, source set, mechanism comparison, source-versus-inference split, and limitation statement. | The missing evidence is public-review evidence, not founder memory. | Do not require private founder context as the missing evidence. |
| `scope_of_decision` | Only the packet's review-prep completeness is evaluated. | Prevents a packet-shape judgment from becoming a policy judgment. | Do not adopt review policy, issue-template fields, or contribution standards. |
| `protected_boundary` | No claims, tests, rights, rewards, governance, AI policy, transfer posture, public posture, or real records move. | Keeps review language from implying adoption. | Joe/governed review before any protected movement. |
| `useful_residue` | The packet preserves a reusable rationale shape for later first-pilot discussion. | Useful structure survives without acceptance or reward. | Do not create retained-value, rights, reward, legal, ownership, or governance meaning. |
| `log_eligibility` | Not eligible; no real contributor, contribution unit, or accepted review exists. | Keeps synthetic work out of `CONTRIBUTIONS-LOG.md`. | Do not create a real `CONTRIB-*` entry. |
| `contestability_marker` | A reviewer could challenge whether a bounded research/review contribution is the safest first-pilot shape. | Names the disputable point without inventing appeal process. | Do not create appeal rights, reversal entitlement, dispute forum, or timing promise. |
| `next_visible_state` | Later Joe/governed review of live target, live surface, reviewer authority, and required context. | Avoids ownerless deferral while keeping live decisions gated. | Do not promise response time or assign reviewer authority. |

## State-Specific Screen

The RQ4 rationale-minimums map says each state needs different visible
reasoning. For this synthetic packet, the relevant state is `needs_revision`.

| `needs_revision` element | first-pilot screen |
|---|---|
| Revision target | Fill one public target, one neighboring system or source set, and the mechanism-comparison fields. |
| Decisive gap | The packet does not yet contain enough concrete source-backed evidence for review. |
| Evidence needed | Stable sources, source/inference split, limitation statement, and target surface. |
| Preserved value | The packet structure itself is useful as a review-prep object. |
| Next reviewable version | A non-live packet with named sources and a selected target, still outside live log and issue surfaces. |
| Non-effects | No policy, claim, test, right, reward, governance, public-posture, or real-record movement. |

If a later live packet lands in `accepted`, `not_accepted`, `contested`, or
`deferred_governance_sensitive`, the decisive reason and boundary sentence
should be rewritten for that state rather than copied from this synthetic
screen.

## Contestability Without Appeal Adoption

The contestable point is narrow:

```text
Is a bounded source-backed research/review contribution the right first-pilot
shape, or would another low-governance contribution class test the workflow
more honestly?
```

Challengeable now:

- whether `research` should be the primary class;
- whether `review` is a secondary effect or a separate class;
- whether the missing evidence list is enough for later review;
- whether a different low-governance packet shape would better test RQ5.

Not challengeable through this scaffold:

- reviewer appointment;
- appeal rule;
- dispute process;
- response-time expectation;
- issue-template or proposal-template change;
- contribution-log entry;
- rights, reward, or governance meaning;
- claim, test, or public-posture movement.

## Next-Visible-State Options

The phrase `next_visible_state` is useful only if it avoids becoming a promise.

| option | safe meaning | misuse risk |
|---|---|---|
| `prep_complete_for_governed_review` | The packet has enough visible fields for Joe/governed discussion. | Sounds like approval to launch a pilot. |
| `needs_source_packet` | The packet needs a selected target and source set. | Becomes an indefinite blocker with no visible owner. |
| `deferred_governance_sensitive` | A live choice would affect authority, rights, rewards, governance, or public posture. | Hides founder discretion if the protected boundary is not named. |
| `not_log_eligible` | The object remains synthetic or unreviewed. | Erases useful residue instead of preserving review-prep value. |

For the current synthetic packet, the safest next visible state is:

```text
needs_source_packet_before_governed_review
```

That phrase is a scaffold label only. It is not a live contribution state or a
response-time commitment.

## Later Review Questions

1. Which rationale fields belong in a first-pilot packet, and which would be
   excess process before the first real contribution?
2. Should `next_visible_state` be reviewer-only, contributor-visible, or absent
   until a live review process exists?
3. What is the shortest `needs_revision` rationale that still lets a newcomer
   know what to do next?
4. Which evidence gaps can be filled by public sources, and which would still
   depend on founder context?
5. When does a contestability marker become an appeal policy question rather
   than a review-record clarity question?

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, sanctioned, rewarded, or used as transfer evidence.
- No issue, PR, public contribution invitation, live pilot target, live record
  surface, or reviewer role was created or selected.
- No issue template, contribution template, contribution standard,
  contribution-log schema, live contribution record, review policy, reviewer
  authority, appeal rule, dispute process, response-time promise, governance
  rule, emergency rule, rollback rule, participant-rights policy, reward
  meaning, AI-use policy, transfer policy, claim status, test pass/fail state,
  public posture, or external action changed.
- This is a draft research scaffold for later RQ4/RQ5 review preparation, not
  active contribution workflow policy.
