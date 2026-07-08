---
artifact_type: legitimacy_failure_first_pilot_screen
status: synthetic_test_fixture
created: 2026-07-08
test_target: T4 legitimacy failure table
related_research_question: RQ5 prototype workflow
governance_role: review_prep_only
constitutional: false
---

# T4 First-Pilot Legitimacy Screen

Status: synthetic review-prep fixture.

Purpose: apply the existing T4 legitimacy-failure table and response routing map
to the synthetic RQ5 first-pilot packet before any live pilot, template change,
review-policy change, contribution-log entry, rights promise, reward meaning,
governance movement, public-posture change, claim-status movement, or test
pass/fail decision.

This file is not a legitimacy-condition change, contribution policy, review
policy, issue-template change, appeal rule, rights policy, reward rule,
governance decision, public-pilot invitation, contribution record, claim-status
decision, or evidence that T4 or RQ5 has passed. It is a bounded screen for
later human or governed review.

## Source Surfaces

- `projects/legitimacy-failure-table/2026-07-02-t4-legitimacy-failure-table.md`
- `projects/legitimacy-failure-table/2026-07-06-t4-response-routing-map.md`
- `projects/prototype-workflow/2026-07-07-rq5-hypothetical-first-pilot-packet.md`
- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-review-packet-checklist.md`
- `projects/prototype-workflow/2026-07-07-rq5-first-pilot-second-ring-stop-map.md`

## Screening Question

```text
If the synthetic first-pilot packet were filled with a real contribution later,
which legitimacy failures should reviewers check before treating the packet as
review-ready?
```

The screen assumes no real contributor, source set, target, reviewer, issue,
pull request, contribution-log entry, reward, right, or governance action has
been selected.

## Minimum Review-Readiness Checks

| check | relevant failure modes | screen prompt | safe current output | stop boundary |
|---|---|---|---|---|
| Public decision reconstruction | T4-FM-01, T4-FM-11 | Could a newcomer reconstruct why the packet received its state from public target, evidence, rationale, and source/inference fields? | Add missing-field notes or a synthetic rationale gap. | Do not adopt active rationale requirements or publish private context. |
| Contestability without appeal promises | T4-FM-02, T4-FM-12 | Does the packet name what can be challenged and what useful residue survives a non-acceptance? | Add contestable-point and loss-note prompts. | Do not create appeal rights, deadlines, reviewer obligations, or dispute process. |
| Rule-change separation | T4-FM-03, T4-FM-10 | Does the packet distinguish ordinary review feedback from a rule-change proposal or capture-risk concern? | Add a rule-change boundary note. | Do not change governance, contribution standards, review policy, or issue templates. |
| Founder and reviewer authority visibility | T4-FM-06, T4-FM-11 | Does the packet expose where founder context or reviewer judgment would decide an outcome? | Add founder-context or reviewer-judgment dependency markers. | Do not assign reviewer authority or authorize founder exceptions. |
| Rights and retained-record boundary | T4-FM-04, T4-FM-13 | Does the packet preserve trace value without implying retained-value rights, erasure rights, appeal rights, reward, or legal claim? | Add retained-record/no-rights language. | Do not define participant rights, retained claims, or reward meaning. |
| Reward and score non-promissory boundary | T4-FM-07 | Could a value note or score be read as future compensation, governance weight, or entitlement? | Add no-current-reward and no-score-conversion language. | Do not adopt payout formulas, score conversion, governance weight, or reward readiness. |
| AI and synthetic consensus boundary | T4-FM-08, T4-FM-14 | If AI assistance or repeated framing appears, is human rationale, source trail, and independent reasoning visible? | Add AI-use/source-overlap prompts to the packet. | Do not change AI policy, reviewer authority, disclosure policy, sanctions, or eligibility rules. |
| Contribution-unit integrity | T4-FM-09 | Is the packet one bounded contribution unit rather than a bundle split for visibility or record weight? | Add dependency, duplicate, and batching prompts. | Do not create rate limits, sanctions, or eligibility restrictions. |
| Legitimacy drift review | T4-FM-05 | Could the packet satisfy fields while still hiding arbitrary or inconsistent outcomes? | Add an adverse-pattern review question. | Do not make metrics or feedback probes automatic policy triggers. |

## Synthetic First-Pilot Application

The current RQ5 hypothetical packet already names several protective screens:
class and evidence, rationale, useful residue and loss notes, log eligibility,
contestability, second-ring stops, and record-surface continuity.

The T4 screen adds one missing layer: it asks whether those screens diagnose
legitimacy failure modes rather than merely completing packet fields.

| packet area | T4 pressure | current synthetic result |
|---|---|---|
| Packet identity | A real packet must not let a draft artifact masquerade as a live record surface. | Safe for now: the packet says the live surface is undecided and no live record exists. |
| Submission snapshot | Missing target, evidence, and contributor context would create private-context dependency. | Needs later fill-in before live review; safe as a synthetic `needs_revision` example. |
| Class and evidence screen | Evidence gaps should not be misread as low value, and class choice should not shift to force acceptance. | Needs explicit source identity, relevance, mechanism comparison, and limitation before review. |
| Review rationale screen | Rationale must preserve the decisive reason without turning protected state into policy movement. | Safe as synthetic rationale only; no real decision or policy consequence exists. |
| Useful residue and loss notes | Loss notes should preserve value without creating retained-value rights or reward expectations. | Safe if loss notes remain reconstruction aids only. |
| Log eligibility | A draft packet must not become `CONTRIBUTIONS-LOG.md` evidence. | Safe: log eligibility is explicitly `No`. |
| Contestability marker | Challenge scope should be visible without implying appeal rights or response-time commitments. | Safe as a synthetic contestable point; needs governed review before live use. |
| Second-ring stop screen | Rights, reward, governance, AI, capture, and transfer dependencies must stop adoption. | Safe as review-prep only; every live consequence remains blocked. |

## Reviewer-Facing Failure Checklist

A later live first-pilot packet should not proceed to review-ready unless the
reviewer can answer these without private founder context:

1. Which public target, claim, test, research question, or scaffold is affected?
2. Which evidence is source-backed, and which statements are reviewer
   inference?
3. Which single contribution unit is being reviewed?
4. Which review state is being assigned, and what decisive reason supports it?
5. Which useful residue is preserved if the packet is revised, narrowed, or not
   accepted?
6. Which parts are contestable without creating appeal rights by implication?
7. Which protected consequences are explicitly excluded?
8. Which missing fields would create private-context dependency?
9. Which response lane applies: local workflow repair, evidence gathering, Joe
   review, or governance/capture stop?
10. Which later decision would require Joe or governed review before adoption?

## Response-Lane Defaults

| observed issue in a later packet | default lane | why |
|---|---|---|
| Missing source/inference split | Local workflow repair | The packet can ask for clearer evidence without changing policy. |
| Unclear target or contribution unit | Local workflow repair | The packet can be revised before review hardens. |
| Proposed new issue-template field | Joe review | Template adoption changes the active contribution surface. |
| Proposed appeal deadline or reviewer obligation | Joe review | This creates rights, obligations, or review-policy commitments. |
| Score-to-reward language | Governance/capture stop | Reward pressure can distort review and needs explicit authority. |
| Founder exception or private-context dependency | Governance/capture stop | Authority and inspectability are the legitimacy issue. |
| AI-generated rationale without human ownership | Local workflow repair first; Joe review if repeated as policy | A synthetic packet can require human rationale, but AI policy changes need review. |
| Repeated similar submissions or source-overlap pattern | Evidence gathering | Similarity needs visible evidence before sanctions or eligibility rules. |

## Boundary Notes

- This screen improves review inspectability only.
- It does not change active legitimacy conditions.
- It does not change the RQ5 packet, templates, contribution instructions, log
  schema, review policy, appeal path, reviewer authority, rights, rewards,
  governance, AI policy, transfer policy, claim status, public posture, or test
  status.
- It does not decide any real contribution or create a contribution-log entry.
- It should be used as a review-prep checklist until Joe or a governed process
  explicitly authorizes any live workflow or policy movement.

## Candidate Next Use

The useful next human/governed review is not "adopt this checklist." It is to
apply this screen to one fully specified hypothetical packet and ask whether T4
failure diagnosis remains stable when the packet contains real target, source,
contributor, and rationale fields.
