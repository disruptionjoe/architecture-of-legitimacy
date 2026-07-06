---
artifact_type: t6_detection_evidence_map
status: non_adopted_scaffold
created: 2026-07-06
test_target: T6 attack-surface map
research_question: RQ8 attack and capture modeling
claim_target: C4
governance_role: review_prep_only
constitutional: false
---

# T6 Detection Evidence Map

Status: non-adopted review-prep scaffold.

Purpose: make the T6 attack-surface scenarios more reviewable by separating observable evidence from interpretation, false-positive risk, and governance-sensitive escalation.

This file does not update the threat model, adopt monitoring policy, require disclosures, define sanctions, decide contributor eligibility, change reviewer authority, change claim status, mark T6 or RQ8 complete, alter reward or rights meaning, change public posture, or decide anything about a real contributor. It is a bounded research object for later review.

## Source Surfaces Used

- `THREAT-MODEL.md`, especially the economic, epistemic, and governance capture classes.
- `TESTS.md`, especially T6 and the attack-profitability starter variables.
- `projects/attack-surface-map/2026-07-02-t6-attack-surface-map.md`.
- `projects/attack-profitability/2026-07-03-rq8-attack-profitability-variable-map.md`.
- `projects/attack-profitability/2026-07-06-rq8-capture-threshold-map.md`.

## Evidence Contract

T6 should not move from attack labels to mitigation or policy until a reviewer can distinguish four things:

1. What was directly observed in the repo record.
2. What is inferred from the observed record.
3. What alternative benign explanation remains plausible.
4. What response would cross from local workflow repair into governance-sensitive policy.

The useful minimum is not surveillance or attribution certainty. The useful minimum is a visible review bundle that prevents capture concerns from becoming private intuition.

## Evidence Quality Bands

| band | meaning | safe use |
|---|---|---|
| No signal | No repo-visible record currently supports the attack concern. | Do not escalate; preserve as a hypothesis only. |
| Weak signal | One visible pattern might indicate pressure, but benign explanations remain equally likely. | Ask for clarifying evidence, source trails, or affected claim/test links. |
| Reviewable signal | Multiple visible records, missing fields, timing facts, or rationale gaps point to a concrete attacked surface. | Create or update a review note, fixture, or local workflow check without changing policy. |
| Escalation signal | The response would change authority, eligibility, disclosure, sanction, reward, rights, governance, or public posture. | Stop for Joe/governance review before adopting the response. |

## Detection Evidence Matrix

| attack pattern | directly observable evidence | missing evidence to request | false-positive hazard | local repair before escalation |
|---|---|---|---|---|
| Low-value volume creates apparent contribution weight. | Many similar proposals, repeated phrasing, shared artifacts, duplicate claims, or queue crowding. | Links among related submissions, affected claim/test, and explanation of distinct value. | A legitimate topic cluster can look like spam when the project has few contributors. | Batch related submissions and require mechanism-level relevance before considering rate limits or eligibility changes. |
| Rubric definition capture favors cheap work. | Proposed scoring changes raise one easy artifact class while weakening truth-seeking, legitimacy, or capture-resistance review. | Who benefits, who loses, which examples change score, and which dimension becomes easier to game. | A good rubric simplification can look self-serving if the contributor's work is in scope. | Require a beneficiary/loss note and synthetic counterexample before changing active scoring policy. |
| Reward or retained-value ambiguity creates extractable benefit. | Review notes, scores, or log entries are cited as debts, payout claims, governance weight, or durable rights. | Whether the record is recognition, evidence, reward hypothesis, or retained-value claim. | Contributors may use imprecise language without trying to extract value. | Add non-promissory boundary language to review prep before considering reward or rights policy. |
| Conflict or sponsorship pressure affects review. | Review outcomes align with affiliations, sponsorship, employment, or funding patterns without better evidence quality. | Conflict evidence, role in the review, and whether the same standard was applied to comparable work. | Small communities often have overlapping relationships that are not capture. | Flag the conflict question in the review bundle before requiring disclosures or reviewer disqualification. |
| Shallow prior-art collision claims lower novelty cheaply. | Comparisons rely on labels while omitting validation, contestability, rights, reward, governance, and capture surfaces. | Mechanism-level comparison, unresolved collision notes, and source packet scope. | A short note can be a valid pointer rather than a finished collision analysis. | Ask for mechanism-level comparison and keep collision status unresolved before claim movement. |
| Smooth synthesis removes uncertainty. | Summaries omit proof burdens, caveats, failure conditions, or non-adopted status from source artifacts. | Source links, preserved uncertainty markers, and explicit changed-meaning notes. | Condensing a document can accidentally drop caveats without capture intent. | Require synthesis notes to preserve claim status and uncertainty before public-posture review. |
| Hidden AI volume or synthetic consensus lowers attacker cost. | Multiple submissions share structure, phrasing, citations, or conclusions without independent reasoning trails. | Source trail, human review note, and distinction between evidence and AI-generated synthesis. | Common templates can produce similar structure for legitimate reasons. | Ask for source trails and evidence/synthesis separation before adopting AI disclosure or rejection rules. |
| Appeal sinkholes or adverse-record loss reduce reputational cost. | Contested or non-accepted items have no rationale, loss note, next visible state, or review owner. | Narrow contested point, adverse rationale, useful residue, and response cadence. | Early prototypes may lack process fields because the process is still forming. | Preserve rationale and next visible state before adopting appeal windows or dispute policy. |
| Founder exception timing normalizes governance capture. | Exceptions appear after pressure without a rule gap, affected surface, reason, expiration, or transition implication. | The exact power used, missing rule, time boundary, and later review trigger. | Founder action may be necessary during a clearly bounded early phase. | Record the exception and rule gap before changing founder powers or transition rules. |
| Rule changes follow contested cases. | Procedure changes narrow appeal, eligibility, reviewer authority, or rationale requirements soon after an adverse event. | Affected contribution path, before/after burden, who benefits, and whether contestability is reduced. | A real process bug may be discovered by a contested case. | Require capture-risk review of the rule-change rationale before governance adoption. |
| Contribution log hides rejected residue. | Accepted records remain detailed while rejected or narrowed records lack useful residue, loss notes, or appeal state. | Whether the residue is evidence, recognition, future-use note, or non-accepted work. | Minimal rejection notes can be appropriate when no useful residue exists. | Preserve bounded loss notes before changing rights, reward, or retention policy. |
| Exit or identity pressure coerces participation. | Leaving, pseudonymous, or identity-changing contributors lose visibility, attribution path, or future review access beyond what the record says. | Stable record link, participation state, retained-record boundary, and privacy or identity concern. | Sparse records can be a tooling gap, not coercion. | Separate active participation from retained-record visibility before adopting participant-rights policy. |

## Review Bundle Template

A later T6 review can use this compact bundle for any scenario:

```text
Scenario:
Observed record:
Inference:
Benign explanation still plausible:
Missing evidence:
Affected protocol layer:
Attack-profitability variable under pressure:
Local workflow repair:
Governance-sensitive threshold:
Decision not made here:
```

## Local Repair Boundary

Local workflow repair can usually add visibility, rationale, duplicate links, source trails, review-state clarity, uncertainty markers, or non-promissory notes. It must stay reversible and tied to a concrete attacked surface.

Escalation begins when the response would change any of these:

- who may participate,
- what contributors must disclose,
- who may review,
- what sanctions apply,
- what rights or retained value mean,
- what reward or governance weight attaches,
- what founder authority permits,
- what public claim the repo makes.

## Pass Criteria For Later Use

This scaffold is useful if a future review can:

- select one attack pattern,
- cite only repo-visible evidence,
- separate observation from inference,
- name at least one plausible benign explanation,
- identify the attack-profitability variable under pressure,
- choose a local repair that does not silently become policy,
- and stop before any governance-sensitive response.

Until then, this map is evidence discipline for T6/RQ8. It does not strengthen C4, settle capture modeling, or prove the attack-surface map passed.
