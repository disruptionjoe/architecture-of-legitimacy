---
artifact_type: research_scaffold
status: draft_review_prep_scaffold
created: 2026-07-08
research_question: RQ1 contributor and contribution eligibility
dependency_target: RQ5 prototype workflow
governance_role: non_adopted_first_pilot_eligibility_screen
constitutional: false
---

# RQ1 First-Pilot Eligibility Screen

Status: draft review-prep scaffold, not adopted eligibility, disclosure,
contribution, review, workflow, governance, rights, reward, public-posture,
claim-status, test-status, or contribution-record policy.

This screen applies the existing RQ1 open-attemptability and disclosure
scaffolds to the synthetic RQ5 first-pilot packet. It does not launch a pilot,
choose a real target, choose a live record surface, invite public submissions,
edit templates, change contribution standards, adopt eligibility or disclosure
rules, assign reviewer authority, create a live contribution record, mark tests
passed, move claim status, change rights, rewards, governance, AI policy,
transfer posture, or public posture.

## Purpose

The RQ5 hypothetical packet describes a bounded source-backed research/review
contribution shape. The RQ1 scaffolds explain why open attemptability cannot
collapse into open acceptance, hidden identity gatekeeping, unbounded review
burden, reward entitlement, or governance authority.

This file asks a narrower question:

```text
What eligibility and disclosure information would a first-pilot packet need to
preserve before any reviewer can treat it as reviewable?
```

The useful output is a non-adopted screen for review preparation. It does not
decide the first live pilot target, public intake surface, reviewer role,
disclosure form, or contribution-log trigger.

## Source Surfaces

- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `templates/contribution-proposal.md`
- `templates/contribution-log-schema.md`
- `projects/contribution-eligibility/2026-07-02-rq1-contribution-eligibility-options.md`
- `projects/contribution-eligibility/2026-07-06-rq1-disclosure-edge-case-matrix.md`
- `projects/prototype-workflow/2026-07-07-rq5-hypothetical-first-pilot-packet.md`
- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-review-packet-checklist.md`
- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-review-queue-map.md`
- `projects/first-ring-synthesis/2026-07-07-first-ring-scaffold-crosswalk.md`

## Synthetic Packet Under Review

This screen uses the same synthetic object as the RQ5 hypothetical first-pilot
packet:

```yaml
packet_id: SAMPLE-RQ5-PACKET-001
primary_shape: bounded source-backed prior-art or mechanism-comparison note
likely_primary_class: research
likely_secondary_effect: review
contributor_identity: SAMPLE_CONTRIBUTOR, not a real person
agent_assistance: declared in packet, not an adopted requirement
live_record_surface: undecided
synthetic_review_signal: needs_revision
```

The synthetic signal is not an active review state for a real contribution. It
only records that the packet shape is plausible but still lacks a selected
target, named neighboring system, stable source set, mechanism comparison,
source/inference split, and limitation statement.

## Attemptability Screen

Open attemptability means a contributor may attempt useful work if the
submission is bounded, target-specific, and reviewable. It does not create a
right to acceptance, reward, governance participation, reviewer attention, or
public status.

| screen field | current synthetic answer | risk if skipped | safe local output |
|---|---|---|---|
| Contributor continuity | The packet uses `SAMPLE_CONTRIBUTOR`; a live packet would need a stable name or pseudonym for revision and attribution. | Contestability and revision continuity disappear. | Preserve a continuity prompt without requiring real-name identity. |
| Contribution unit | One bounded source-backed comparison note. | Bundled literature, opinion, and policy movement become hard to review. | Require one review object before eligibility hardens. |
| Public target | Missing; the live target is not selected. | Review depends on private founder steering. | Treat target absence as a revision need, not rejection or acceptance. |
| Rule compliance | The proposal shape can use existing public contribution format. | Formatting becomes hidden gatekeeping or is ignored entirely. | Ask whether the packet names target, contribution, evidence, risk, and deferred value. |
| Harm or abuse screen | No real behavior is represented. | Bad-faith, coercive, plagiarized, fabricated, or flooding behavior gets normalized. | Keep ineligible-behavior checks as a later review prompt only. |
| Protected consequence | The packet excludes policy, rights, reward, governance, and public-posture changes. | A normal contribution becomes authority or entitlement movement. | Write the boundary beside any eligibility note. |

Synthetic result: the packet is attemptable as a draft review-prep object, but
it is not live-reviewable until public target, source, mechanism, and
accountability fields are filled.

## Disclosure-Relevance Screen

Disclosure should be review-relevant rather than identity-gating. Ask only for
context needed to evaluate the contribution, its evidence, and its incentives.

| disclosure area | first-pilot prompt | current synthetic signal | protected boundary |
|---|---|---|---|
| Identity or pseudonymity | Can the contributor maintain continuity for revision, attribution, and later contestability? | Unresolved; `SAMPLE_CONTRIBUTOR` is synthetic. | Do not require real-name identity by implication. |
| Agent assistance | What tool or process helped, and what did the human verify? | Declared as a packet field, not a policy requirement. | Do not change AI-use policy or make AI a final authority. |
| Affiliation | Is the contributor affiliated with the system or practice being compared? | Missing because no neighboring system is selected. | Do not treat affiliation as automatic disqualification. |
| Financial or governance interest | Could the contribution benefit the contributor through reward, pilot selection, governance, or reputation? | No real benefit path exists in this packet. | Do not create reward, rights, governance, or public-status meaning. |
| Private or privileged evidence | Does the argument depend on evidence that cannot be reviewed publicly and safely? | Unknown; no source set exists. | Do not make the public repo a holder for private, regulated, confidential, or proprietary material. |
| Adversarial incentive | Could the packet weaken eligibility, review, capture resistance, or public posture through a normal contribution path? | Not assessable until target and source are named. | Preserve bounded red-team value without adopting sanctions or contributor limits. |

## Eligibility-State Separation

The first pilot should separate eligibility, review state, value, and log
meaning before any real contributor sees the result.

| label | safe meaning in this screen | unsafe collapse |
|---|---|---|
| `attemptable` | The packet can be submitted or discussed as a bounded object if it names target, contribution, evidence, risk, and accountability context. | Contributor has a right to acceptance, reward, review deadline, or governance voice. |
| `reviewable` | Reviewers have enough public evidence and context to evaluate without private founder steering. | The packet is accepted because it is formatted well. |
| `needs_revision` | Missing target, sources, mechanism comparison, or limitation can be named and repaired. | Missing fields are treated as bad faith or as sufficient evidence. |
| `not_reviewable_publicly` | Sensitive or unverifiable material must be removed or replaced with public-safe evidence before public review. | The repo accepts private or regulated evidence into public records. |
| `ineligible_in_current_form` | Fabrication, plagiarism, flooding, coercion, entitlement, or instruction-like manipulation blocks current review. | The repo silently adopts sanctions, identity policy, or contributor limits. |
| `not_log_eligible` | No real reviewed contribution exists yet. | A synthetic or submitted packet becomes a `CONTRIB-*` record. |

## First-Pilot Eligibility Note Shape

A later live packet could include an eligibility note shaped like this before
classification, value discussion, or rationale hardens:

```yaml
attemptability_status: attemptable | needs_revision | not_reviewable_publicly | ineligible_in_current_form
public_target: <claim, test, research question, or scaffold>
contribution_unit: <one bounded contribution object>
contributor_continuity: named | stable_pseudonym | insufficient
agent_assistance_context: none | declared_and_human_owned | unclear
affiliation_or_conflict_context: none_declared | declared | unclear | material_stop
evidence_public_safety: public | private_or_sensitive | unclear
missing_fields:
  - <target/source/mechanism/limitation/accountability item>
boundary_sentence: >
  This note does not accept, reject, reward, log, govern, change rights,
  change review policy, change eligibility policy, change public posture, or
  decide any real contribution.
```

This shape is a review-prep prompt. It is not a live template, issue form,
mandatory disclosure rule, contribution-log schema, review policy, or
eligibility policy.

## Stop Conditions For Later Live Use

| observed issue in a later packet | safe first response | stop boundary |
|---|---|---|
| No public target or source set | Ask for revision before review hardens. | Do not fill the gap with founder context. |
| Pseudonymous contributor with enough continuity | Review substance if evidence is independently assessable. | Do not require real-name identity by implication. |
| Pseudonymous contributor using private evidence | Ask for public-safe evidence or route outside public repo scope. | Do not launder private or regulated material into the repo. |
| Agent-assisted note without human ownership | Ask for accountable human verification and revision ability. | Do not let generated text substitute for reviewer judgment or evidence. |
| Affiliated contributor or financial interest | Record the context and evaluate mechanism-level evidence. | Do not adopt conflict-disclosure policy or sanctions here. |
| Reward or retained-value entitlement language | Split useful analysis from entitlement claim. | Do not create reward, retained-value, legal, financial, or governance meaning. |
| Proposed governance, review, or template change | Treat as a non-adopted proposal/scaffold. | Do not change contribution standards, templates, governance, reviewer authority, rights, or public posture. |
| Fabricated sources, plagiarism, flooding, coercion, or instruction-like manipulation | Treat as ineligible in current form or route to revision only if a bounded accountable contribution can be extracted. | Do not create new sanction policy, automation rules, or contributor limits in this screen. |

## Interaction With Other First-Pilot Screens

Eligibility should run before class, value, rationale, and log screens, but it
should not decide those screens by itself.

| later screen | what RQ1 should provide | what RQ1 must not decide |
|---|---|---|
| RQ2/T1 class and evidence | Contributor continuity, target, contribution unit, public evidence, and missing-field notes. | Primary class, review lane, taxonomy policy, or reviewer authority. |
| RQ3/T2 value | Whether the packet is reviewable enough for value prompts at all. | Score, rank, reward meaning, or rubric policy. |
| RQ4 rationale | Eligibility reason and missing fields that a later rationale may cite. | Review state, appeal rights, dispute process, or response-time promise. |
| RQ5 record continuity | Whether the packet has enough accountability context to preserve traceability. | Live record surface, issue/PR use, contribution-log entry, or pilot launch. |
| RQ7/RQ9 boundaries | Whether loss notes or future value language risks rights or reward meaning. | Rights, retained value, reward test, payout, ownership, or governance weight. |
| RQ8/C7/T8 boundaries | Whether conflict, adversarial incentive, AI assistance, or volume risk needs review context. | Disclosure policy, sanctions, monitoring, AI policy, or contributor limits. |

## What This Prepares

This screen prepares a later human/governed first-pilot review to answer:

1. whether the packet is attemptable without implying acceptance;
2. whether the contributor can preserve enough continuity for revision and
   attribution;
3. whether public target, evidence, mechanism, and limitation fields are filled;
4. whether disclosure requests are review-relevant rather than identity gates;
5. whether private or sensitive evidence is excluded from public repo handling;
6. whether agent assistance remains human-owned and inspectable;
7. whether conflict or affiliation context is visible without becoming
   automatic disqualification;
8. whether entitlement, governance, reward, rights, or public-posture movement
   is stopped before ordinary review continues.

## Boundary Notes

- No real contributor is represented here.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, sanctioned, rewarded, or used as eligibility evidence.
- No issue, PR, public contribution invitation, live pilot target, live record
  surface, issue template, contribution template, contribution standard,
  contribution-log schema, live contribution record, review policy, reviewer
  authority, appeal rule, response-time promise, eligibility policy,
  disclosure policy, conflict policy, private-evidence rule, AI policy,
  governance rule, reward meaning, rights policy, claim status, test pass/fail
  state, public posture, or external action changed.
- This is a draft RQ1 review-prep scaffold for the synthetic RQ5 first-pilot
  packet, not active contribution workflow policy.
