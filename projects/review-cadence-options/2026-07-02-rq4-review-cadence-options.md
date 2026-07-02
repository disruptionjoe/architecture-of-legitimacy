---
artifact_type: review_cadence_options_scaffold
status: draft_options_scaffold
created: 2026-07-02
research_target: RQ4 cadence and evaluation
governance_role: internal_research_scaffold
constitutional: false
---

# RQ4 Review-Cadence Options Scaffold

Status: draft options scaffold.

Purpose: make the RQ4 cadence question reviewable before the project adopts
any active cadence rule.

This file is not a contribution policy, governance decision, appeal rule,
reviewer-authority change, claim-status decision, reward rule, public-posture
change, or live contribution decision. It is a bounded research scaffold for
comparing review-cadence options against legitimacy and capture-risk concerns.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ4
- `ROADMAP.md`, especially Phase 1 and Phase 3
- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `CONTRIBUTIONS-LOG.md`
- `templates/contribution-proposal.md`
- `templates/contribution-log-schema.md`
- `PROTOCOL-STACK.md`, especially Layer 5
- `LEGITIMACY-SCHEMA.md`
- `THREAT-MODEL.md`
- Recent synthetic workflow, log, failure, attack, and AI-boundary fixtures

## Boundary Under Review

Current repo surfaces already imply a mixed cadence:

- simple maintenance can be reviewed continuously;
- substantive research should be batched;
- contested decisions should be summarized publicly;
- monthly synthesis should update claims, tests, and roadmap;
- early review remains founder-led until standards are clear enough to
  distribute responsibly.

The open design problem is not whether review needs a cadence. The problem is
which decisions can move quickly without becoming arbitrary, and which decisions
need slower batch review because they affect legitimacy, capture risk, or future
governance.

## Candidate Review Lanes

| lane | examples | candidate timing shape | rationale minimum | boundary note |
|---|---|---|---|---|
| `intake_triage` | classify submitted proposals; identify missing fields; ask for source packets | rolling, lightweight | class, target, missing fields, next state | Triage is not acceptance, scoring, reward, or policy adoption. |
| `maintenance_review` | link fixes, template cleanup, typo repair, schema-aligned formatting | rolling or small batch | affected surface, why it is non-substantive, validation performed | Stop if the change alters research meaning, governance, reward, or contribution rights. |
| `substantive_research_review` | prior art, claim critique, mechanism comparison, threat analysis | scheduled batch | source/evidence check, mechanism relevance, failure mode, review state | Batch review reduces urgency pressure and makes comparisons visible. |
| `protocol_design_review` | workflow, review cadence, appeal, rights, reward, or governance proposals | scheduled batch plus governance-boundary check | affected protocol layer, who gains/loses, capture-risk note, adoption status | Accepting value from a proposal is separate from adopting the proposed rule. |
| `contested_decision_review` | challenged classification, adverse decision, disputed attribution, loss-note challenge | scheduled dispute window or monthly synthesis | disputed point, original rationale, contributor objection, temporary disposition | Contestability needs an owner and visible state, but this scaffold does not create appeal rights. |
| `monthly_synthesis` | accepted work summary, open disputes, rule-learning notes, unresolved risks | monthly candidate cycle | what changed, what stayed unresolved, which claims/tests are affected | Synthesis should not silently move claim status or governance policy. |
| `governance_sensitive_defer` | founder powers, transition triggers, reward readiness, protected-license questions | no automatic cadence; Joe/governance review needed | reason for stop, proposed review owner, dependency | These are pause boundaries, not backlog items to push through cadence. |

## Option Set

### Option A: Rolling Triage, Weekly Batch, Monthly Synthesis

Shape:

- rolling intake triage for completeness and contribution class;
- weekly batch for substantive research and protocol-design proposals;
- monthly synthesis for accepted records, open disputes, and rule-learning notes;
- governance-sensitive items remain deferred until the proper review path exists.

Best when:

- the repo starts receiving enough proposals that delay becomes visible;
- contributors need quick acknowledgement but not instant acceptance;
- source-backed research and protocol proposals need comparison against each other.

Risks:

- weekly batches can become performative if no one owns the review;
- a fast triage note can be mistaken for a decision;
- monthly synthesis may quietly become policy revision unless boundaries are explicit.

### Option B: Continuous Maintenance, Twice-Monthly Substantive Review

Shape:

- continuous review only for clearly non-substantive maintenance;
- twice-monthly substantive review for research, formalization, review, and synthesis;
- contested decisions stay open until the next substantive review window;
- monthly synthesis records unresolved items rather than forcing closure.

Best when:

- the project wants low review burden during early public work;
- most contributions are likely to be research notes or prior-art proposals;
- founder-context dependency is still high and should be exposed slowly.

Risks:

- contributors may wait too long for feedback;
- contested states may feel ownerless between windows;
- batch review can hide founder discretion if rationale fields are thin.

### Option C: Pilot-Gated Cadence Before Real External Review

Shape:

- run one or more synthetic or invited pilot reviews before adopting a public cadence;
- use the pilot to measure time-to-triage, rationale sufficiency, and contested-state handling;
- do not advertise a fixed review schedule until the pilot exposes the operating load.

Best when:

- the repo wants to avoid overpromising public responsiveness;
- the first external contribution is expected to be source-heavy or governance-adjacent;
- the project wants evidence before choosing between Option A and Option B.

Risks:

- too much pilot gating can delay real contribution attempts;
- contributors may not know when to expect decisions;
- the project may look open while still depending heavily on founder judgment.

## Candidate Rationale Minimums

Any later cadence proposal should preserve these fields for review decisions:

| field | reason |
|---|---|
| `proposal_or_artifact_link` | lets future contributors inspect the actual submitted work |
| `primary_contribution_class` | prevents one rubric from flattening unlike work |
| `target_claim_test_or_surface` | ties review to live project questions |
| `review_lane` | explains whether the item was triage, maintenance, substantive, protocol design, contested, synthesis, or deferred |
| `review_state` | keeps submitted, triaged, accepted, needs revision, not accepted, contested, and adversarial states distinct |
| `decisive_reason` | names the main reason for the state rather than hiding behind a score |
| `evidence_gap_or_source_note` | especially important for research-class and prior-art work |
| `governance_or_reward_boundary` | prevents policy, rights, or reward movement through ordinary review |
| `loss_notes` | preserves useful residue when work is narrowed, revised, or not accepted |
| `contestability_note` | names what can be challenged and what remains out of scope |

## Capture And Legitimacy Checks

For each cadence option, reviewers should ask:

1. Does the timing create urgency pressure that favors loud, connected, or
   founder-aligned contributors?
2. Does the timing create delay that makes contestability formal but unusable?
3. Does batching improve comparison quality or only hide decisions?
4. Can a future contributor reconstruct why a contribution entered a review
   lane and why it received its state?
5. Which decisions must stop rather than move through cadence because they
   touch founder power, reviewer authority, reward, retained-value meaning,
   protected licenses, or public posture?

## Adoption Questions For Later Review

- Which lane should own first-response triage for a real external contribution?
- What response-time promise, if any, is safe before regular reviewers exist?
- Which contribution classes should never receive same-day acceptance?
- How should contested decisions be represented while unresolved?
- Should `CONTRIBUTIONS-LOG.md` record review lane in addition to review state?
- Where should monthly synthesis live if it later becomes real: contribution
  log, run record, separate review notes, or roadmap update?
- What evidence would justify moving from founder-only review to named
  non-founder reviewers for a narrow contribution class?

## Later Review Criteria

This scaffold can support a later cadence decision when:

- at least one synthetic or real contribution has been routed through a named
  review lane;
- the decisive rationale and loss notes are sufficient for a newcomer to
  reconstruct the decision;
- contested-state handling has an owner, timing expectation, and unresolved
  disposition;
- governance-sensitive items stop visibly instead of being smuggled through
  ordinary review;
- and the chosen cadence reduces founder-context dependency without pretending
  the project is decentralized.

This scaffold does not adopt any option. It gives the repo a compact object for
comparing cadence choices before real contributors depend on them.
