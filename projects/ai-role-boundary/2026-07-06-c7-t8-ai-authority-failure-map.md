---
artifact_type: research_failure_map
status: non_adopted_scaffold
created: 2026-07-06
claim_target: C7
test_target: T8 AI role boundary
governance_role: non_adopted_review_prep
constitutional: false
---

# C7/T8 AI Authority Failure Map

Status: draft failure map, not adopted AI-use policy.

Purpose: pressure-test where AI assistance in contribution review crosses into
hidden authority, evidence laundering, reviewer abdication, or contestability
failure before any real contribution review depends on the boundary.

This artifact does not change `GUARDRAILS.md`, `CONTRIBUTING.md`,
`CONTRIBUTION-STANDARDS.md`, `CONTRIBUTIONS-LOG.md`, `TESTS.md`, any issue
template, or any live review procedure. It is a bounded review-prep artifact for
C7 and T8.

## Source Surfaces Used

- `CLAIMS.md`, especially C7
- `GUARDRAILS.md`
- `LEGITIMACY-SCHEMA.md`
- `PROTOCOL-STACK.md`
- `THREAT-MODEL.md`
- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `CONTRIBUTIONS-LOG.md`
- `templates/contribution-log-schema.md`
- `projects/ai-role-boundary/2026-07-02-t8-ai-role-boundary-fixture.md`
- `projects/ai-role-boundary/2026-07-03-c7-ai-assisted-review-trace-checklist.md`

## Boundary Under Test

C7 says AI can support judgment, critique, synthesis, and review, but cannot
itself supply legitimacy. T8 asks whether the repo can define allowed and
disallowed AI uses in review.

For this map, the practical failure question is:

```text
When would an AI-supported review record stop being visible, contestable,
human-owned, source-traceable, and non-capturing?
```

The goal is not to forbid useful AI help. The goal is to keep AI from becoming
an unreviewable decision layer.

## Failure Map

| id | failure pattern | how it appears | legitimacy damage | minimum visible trace | stop or review gate |
|---|---|---|---|---|---|
| AI-F1 | Hidden final judge | The review state, score, or acceptance rationale tracks AI output, but the record presents it as human judgment. | Bounded authority and contestability fail because the contributor cannot identify the actual decision maker. | Name the human reviewer, final decision owner, and any AI output treated as non-binding. | Stop before acceptance, rejection, scoring, reward implication, or rights implication if the human decision reason is not visible. |
| AI-F2 | Summary-only review | A reviewer reads an AI summary instead of the contribution, source links, or cited evidence. | Visibility fails because the decisive evidence path is compressed into unverified synthesis. | Record source material checked directly by the reviewer and what the AI summarized. | Treat as `needs_revision` for the review record until direct source checks are named. |
| AI-F3 | Citation laundering | AI-generated or AI-selected source claims are treated as stable prior art without human verification. | Research rigor and contestability fail because contributors cannot separate source evidence from model assertion. | List stable sources checked by a human and mark unverified leads separately. | Do not use the review to narrow novelty, demote a claim, or reject a contribution for missing prior art until source verification is visible. |
| AI-F4 | Synthetic consensus | Multiple AI outputs or simulated reviewer voices are counted as independent participant agreement. | Voice fails because synthetic output substitutes for actual contributor or reviewer feedback. | Label simulations and repeated AI outputs as private rehearsal only. | Stop before treating model agreement as participant consensus, governance evidence, or public support. |
| AI-F5 | Rubric score substitution | AI produces a value score that becomes the effective contribution valuation. | Value judgment becomes opaque and may create reward or retained-value implications without accountable review. | Preserve human score, disagreement notes, and a statement that AI scoring was non-binding test input. | Stop before log entry, reward-readiness analysis, or retained-value language if the human valuation is missing. |
| AI-F6 | Rationale polishing masks preference | AI-drafted prose makes a founder or reviewer preference look like neutral technical judgment. | Legitimacy fails because hidden authority is laundered through polished language. | Record the decisive human reason before or alongside any wording assistance. | Treat the rationale as incomplete if the reviewer cannot name the reason without AI prose. |
| AI-F7 | Prompt opacity blocks contestability | The contributor would need hidden prompts, model outputs, or private context to understand or challenge the decision. | Contestability fails even if the final state is public. | Name the human rationale, source trace, missing evidence, and revision path in the review record. | Stop before adverse decisions if the challenge path depends on private model context. |
| AI-F8 | AI-volume pressure | A contributor submits high-volume AI-generated material with limited human selection or responsibility. | Open attemptability degrades into noise and can pressure reviewers to mistake volume for value. | Require contribution-unit boundaries, AI-use disclosure, and human responsibility for each submitted unit. | Route to spam, adversarial, or `needs_revision` review if volume overwhelms inspectability. |
| AI-F9 | Policy drift through generated language | AI-assisted wording in a fixture or review note effectively changes AI-use policy, reviewer authority, or contribution standards. | Adaptive rule change is bypassed because policy moves through a local artifact. | Mark policy language as proposal, test input, or non-adopted review prep. | Joe/governance review is required before policy, standards, templates, or public posture change. |
| AI-F10 | Capture-screen deferral | AI-specific attack signals are noticed but left outside the review because they are "only process issues." | Non-capture weakens because synthetic consensus, prompt shaping, and review-volume pressure remain unmodeled. | Record the AI-specific capture signal and the human check or later review needed. | Route to capture-risk review before treating the contribution as cleanly accepted or rejected. |

## Local Repair Versus Review Gate

A later review record can usually repair an AI trace locally when:

- the human reviewer can name the final reason;
- sources and contribution text were checked directly;
- AI output is labeled as synthesis, wording help, rubric test input, source
  lead, or red-team prompt;
- the contributor can contest the human rationale without hidden model context;
- and no policy, reward, rights, governance, or public-posture implication is
  created.

Joe or governance review is required before:

- AI output supplies a final decision, score, legitimacy judgment, reward
  implication, or rights implication;
- AI-use policy or contribution standards change;
- reviewer authority or appeal/contestability routes change;
- generated text becomes public posture or project policy;
- or synthetic consensus is treated as participant voice.

## Review Prompts

For a later AI-assisted review, ask:

1. What did AI do, and what did a human decide?
2. Which source material did the human check directly?
3. Would the same review rationale be understandable without hidden prompts?
4. Can the contributor challenge the actual human reason?
5. Did AI affect triage, evidence review, scoring, rationale drafting, prior-art
   leads, or capture analysis?
6. Does any AI output create pressure toward reward, rights, policy, public
   posture, or governance claims?
7. Are synthetic reviewer voices, repeated AI outputs, or AI-generated volume
   separated from real participant voice?

## Later Evidence Needed

A stronger C7/T8 review would need:

- one real AI-assisted contribution proposal with disclosed AI use;
- one adverse or `needs_revision` decision with human rationale and revision
  path visible;
- one AI-generated prior-art lead that is verified or rejected by a human;
- one case where AI-drafted wording is preserved without becoming policy; and
- one capture-risk note for synthetic consensus or AI-volume pressure.

Those later artifacts should remain separate from any decision to change AI-use
policy, contribution standards, reward meaning, rights meaning, governance, test
pass/fail state, claim status, or public posture.

## Boundary Notes

- No AI-use policy changed.
- No contribution policy changed.
- No issue template changed.
- No governance rule changed.
- No reviewer authority changed.
- No claim status changed.
- No public posture changed.
- No T8 pass/fail state changed.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, or rewarded.
- No reward, retained-value, rights, legal, or financial promise is created.
