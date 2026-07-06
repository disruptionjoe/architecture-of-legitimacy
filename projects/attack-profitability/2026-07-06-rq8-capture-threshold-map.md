---
artifact_type: rq8_capture_threshold_map
status: non_adopted_scaffold
created: 2026-07-06
research_question: RQ8 attack and capture modeling
test_target: T6 attack-surface map
claim_target: C4
governance_role: review_prep_only
constitutional: false
---

# RQ8 Capture Threshold Map

Status: review-prep scaffold, not adopted mitigation, disclosure, sanction, reward, rights, governance, or contributor-eligibility policy.

Purpose: make attack-profitability review sharper by naming when an attack pattern can be handled as local workflow repair and when it crosses into governance-sensitive escalation.

This file does not change the threat model, define sanctions, require disclosures, adopt contributor eligibility rules, adopt reviewer powers, create reward or retained-value meaning, change claim status, mark T6 or RQ8 complete, or decide anything about a real contributor. It is a bounded RQ8 research object for later review.

## Source Surfaces Used

- `THREAT-MODEL.md`, especially economic capture, epistemic capture, governance capture, and the attack-profitability starter.
- `PROTOCOL-STACK.md`, especially validation, value rubrics, cadence, contribution log, rights, rewards, governance, and capture monitoring.
- `CLAIMS.md`, especially C4 and the warning that attack modeling can demote claims if value accumulation makes capture easier.
- `TESTS.md`, especially T6 and the attack-profitability variables.
- `projects/attack-surface-map/2026-07-02-t6-attack-surface-map.md`.
- `projects/attack-profitability/2026-07-03-rq8-attack-profitability-variable-map.md`.
- Recent RQ1-RQ7 scaffolds as boundary evidence, without repeating their lanes or adopting their policies.

## Boundary Under Review

The existing RQ8 variable map asks which term a protocol choice changes:

```text
P_a * B_a > C_a + M + D_a * S_a + R_a
```

This map adds a second question:

```text
Is the response still local workflow repair,
or has it become policy, rights, reward, sanction, disclosure, reviewer-authority,
governance, or public-posture change?
```

Local workflow repair can usually improve visibility, rationale, source trails, queue state, duplicate linking, and non-promissory notes. Escalation begins when the response changes who may participate, what must be disclosed, who has authority, what rights attach, what sanctions apply, what rewards mean, or what public claim the repo makes.

## Threshold Matrix

| attack pattern | first exposed variable | local repair threshold | escalation threshold | review risk if collapsed |
|---|---|---|---|---|
| Low-value volume creates apparent contribution weight. | `P_a * B_a` | Link duplicates, batch related submissions, require relevance to a claim/test/surface, and preserve triage rationale. | Rate limits, ineligibility, sanctions, identity rules, or contribution-class exclusion. | Anti-volume repair becomes hidden gatekeeping against open attemptability. |
| Hidden AI or synthetic consensus lowers attacker cost. | `C_a + D_a` | Ask for source trails, distinguish evidence from synthesis, and record uncertainty markers. | AI-use disclosure mandate, identity policy, rejection rule, or sanction for non-disclosure. | Detection work becomes an adopted AI policy without review. |
| Rubric definition capture makes cheap work score well. | `B_a` | Record who benefits, who loses, and which dimension becomes easier to game. | Active rubric rewrite, reward-weight change, reviewer-authority change, or claim-status movement. | Analysis of scoring incentives silently becomes scoring policy. |
| Prior-art shallowness makes novelty attacks cheap. | `P_a` | Require mechanism-level comparison and preserve unresolved collision status. | Novelty verdict, claim promotion/demotion, public-posture change, or source-packet acceptance rule. | Readiness review gets mistaken for a prior-art conclusion. |
| Review cadence gaming uses urgency or delay. | `P_a + R_a` | Record queue state, rationale minimums, unresolved-contest markers, and next visible state. | Appeal windows, response-time promises, reviewer assignment powers, or dispute-resolution policy. | Process visibility becomes an adopted appeal or service-level guarantee. |
| Reward or retained-value ambiguity increases extractable benefit. | `B_a` | Add non-promissory boundary language and separate record, recognition, reward, and future-value markers. | Payout formula, retained-right marker, governance weight, legal/financial claim, or reward-readiness decision. | Useful residue becomes shadow entitlement or is erased to avoid entitlement. |
| Founder exception timing makes governance capture easier. | `M + D_a` | Record the exception, affected surface, rule gap, and capture-risk question. | Founder powers, emergency rules, transition triggers, rollback policy, or public governance posture. | Founder discretion is normalized as permanent control or blocked before real review. |
| Exit, identity, or adverse-review residue can be weaponized. | `R_a + B_a` | Preserve the narrow contestable point, rationale, and useful residue boundary. | Participant rights, privacy/identity policy, deletion rule, retained-record right, sanction, or appeal policy. | The repo either coerces participation through records or overpromises retention rights. |
| Contributor conflict or sponsorship pressure affects review. | `D_a + R_a` | Flag missing conflict evidence and separate behavior evidence from identity assumptions. | Disclosure requirements, conflict bans, reviewer disqualification rules, sanctions, or eligibility limits. | Conflict visibility becomes identity-based exclusion or unreviewed disclosure policy. |
| Public posture overclaim raises attacker benefit. | `B_a + R_a` | Mark draft, scaffold, unresolved, or non-adopted status where needed. | Public claim, status change, external publication, claim ledger movement, or canonical verdict. | Status hygiene becomes reputation management or silent claim revision. |

## Variable-Specific Escalation Signals

| variable | local signal to study | escalation signal |
|---|---|---|
| `B_a` | The attacker gains attention, queue priority, synthesis influence, or apparent value without mature reward. | The response would define payout, retained value, governance weight, legal/financial meaning, or public claim strength. |
| `P_a` | The process lacks source trails, duplicate links, rationale fields, uncertainty markers, or review-state clarity. | The response would change eligibility, rejection rules, appeal rights, reviewer authority, or evidence policy. |
| `C_a` | Better templates, source requirements, batching, and relevance prompts make cheap attacks more expensive. | The response would impose broad participation burdens or exclusion criteria. |
| `M` | Extra review friction is narrow, reversible, and tied to an identified attack surface. | The mitigation becomes permanent policy, governance rule, or contributor obligation. |
| `D_a` | A missing observable signal can be added to a review note, checklist, or synthetic fixture. | Detection requires surveillance, identity linkage, disclosure mandates, or cross-repo monitoring. |
| `S_a` | The review can name that sanctions would be a later policy question. | The response rejects, bans, penalizes, publicly labels, or limits a real contributor. |
| `R_a` | A durable rationale, disputed-state marker, or correction note changes future trust costs. | The response creates reputational punishment, public shaming, rights loss, or governance standing. |

## Synthetic Threshold Scenarios

These scenarios are non-real review fixtures. They should not be used to infer intent or behavior from any real contributor.

| scenario | local review action | escalation question |
|---|---|---|
| Three similar AI-assisted synthesis submissions remove caveats from the same claim. | Link the submissions, require source trails, and preserve uncertainty markers in review notes. | Does the repo need an AI-use disclosure rule, or is source-trace review enough for now? |
| A sponsor-backed contributor proposes a rubric dimension that favors sponsored work. | Ask who benefits, which work becomes easier to score, and which capture-resistance dimension weakens. | Does conflict disclosure or reviewer separation need policy review? |
| A rejected contribution leaves a useful loss note that later synthesis wants to cite. | Preserve the loss note and the reason it is not acceptance, reward, or retained value. | Does later use require participant-rights, appeal, attribution, or retained-record policy? |
| A governance proposal follows an adverse review and narrows future contestability. | Mark the timing, affected rule, affected contribution path, and capture-risk question. | Does this become founder-authority, transition, rollback, or rule-change governance review? |
| A prior-art comparison uses labels to claim the project is not novel. | Require mechanism-level comparison and keep collision status unresolved. | Does the evidence justify claim demotion, public posture change, or T9/T6 movement? |

## Safe Next Review Prompts

1. Which attack pattern can be handled by adding observability to a synthetic or draft review record?
2. Which response would require changing participation, disclosure, authority, rights, reward, sanction, or governance rules?
3. Which variable is the response actually trying to change: `B_a`, `P_a`, `C_a`, `M`, `D_a`, `S_a`, or `R_a`?
4. Does the response preserve open attemptability, or does it quietly gate participation?
5. Does the response preserve useful residue, or erase it to avoid reward or rights ambiguity?
6. Does the response reduce capture risk before value accumulates, or only after a valuable decision has already been made?

## Relationship To Current RQ8 Work

The RQ8 variable map names the modeling vocabulary. The T6 attack-surface map names attack scenarios and candidate levers. This map sits between them:

- it does not add new threat classes;
- it does not adopt mitigations;
- it does not update the public threat model;
- it does not mark T6, RQ8, or C4 stronger;
- it only tells a later reviewer when the response is still local workflow repair and when it must be escalated.

RQ8 becomes more reviewable when future artifacts can take one scenario, name the variable under pressure, show the local repair available, and name the exact governance-sensitive threshold that stops the run.

## Stop Conditions

Stop and require Joe/governance review before:

- adopting any mitigation, disclosure rule, sanction, ineligibility rule, reward rule, rights policy, appeal path, reviewer-authority change, founder power, transition trigger, rollback rule, privacy/identity policy, retained-value marker, or public claim;
- editing `CLAIMS.md`, `GOVERNANCE.md`, `GUARDRAILS.md`, `CONTRIBUTING.md`, `CONTRIBUTION-STANDARDS.md`, `CONTRIBUTIONS-LOG.md`, issue templates, live review policy, reward language, participant-rights language, or public posture based on this scaffold;
- assigning economic value to retained claims or treating a synthetic attack scenario as evidence about a real contributor;
- marking C4, T6, RQ8, attack modeling, or capture resistance passed, failed, or solved;
- rejecting, sanctioning, labeling, limiting, or recording a real contributor based on this scaffold;
- writing to another repo or taking any non-GitHub external action;
- or publishing this scaffold as active threat-model, governance, reward, disclosure, or sanctions policy rather than draft research.
