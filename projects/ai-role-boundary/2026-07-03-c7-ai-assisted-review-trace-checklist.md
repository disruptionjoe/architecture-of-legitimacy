---
artifact_type: research_checklist
status: non_adopted_scaffold
created: 2026-07-03
claim_target: C7
test_target: T8 AI role boundary
governance_role: non_adopted_review_prep
constitutional: false
---

# C7 AI-Assisted Review Trace Checklist

Status: draft checklist, not adopted AI-use policy.

Purpose: make AI-assisted contribution review more inspectable by naming the
minimum trace a later reviewer would need before treating an AI-supported review
record as legitimate, contestable, and human-owned.

This checklist does not change `GUARDRAILS.md`, `CONTRIBUTING.md`,
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
- `templates/contribution-proposal.md`
- `templates/contribution-log-schema.md`
- `projects/ai-role-boundary/2026-07-02-t8-ai-role-boundary-fixture.md`
- `projects/first-workflow-simulation/2026-07-02-t3-newcomer-workflow-simulation.md`
- `projects/prototype-workflow/2026-07-02-rq5-prototype-workflow-synthesis.md`

## Review Question

For a contribution review that used AI support, can a future contributor
reconstruct and contest the human decision without treating the model as a
source of legitimacy?

The checklist is useful only if it preserves four distinctions:

1. AI assistance versus final authority.
2. Source evidence versus synthesis or wording help.
3. Human verification versus model assertion.
4. Contributor contestability versus hidden reviewer context.

## Minimum Trace Checklist

These are review prompts, not adopted required fields.

| trace area | evidence to preserve | sufficient for review prep | needs revision signal | stop boundary |
|---|---|---|---|---|
| AI-use disclosure | Who used AI and what task it performed. | The record names whether AI summarized, drafted, classified, scored as test input, generated leads, or red-teamed. | The record only says "AI-assisted" without the task. | Undisclosed bulk AI output is being treated as contributor consensus or review authority. |
| Source scope | What material the AI saw and what source material the human reviewer checked directly. | The record distinguishes model-visible material from reviewer-verified sources, links, claims, and proposal text. | The reviewer cannot tell which claims were checked directly. | A source-backed review relies on unverified AI citations or label-level source claims. |
| Human decision owner | Who chose the final review state, rationale, and any score or classification. | The final judgment is attributed to a person or governed process, and AI output is non-binding. | The rationale is polished but the decisive human reason is unclear. | AI output assigns acceptance, rejection, legitimacy, reward, rights, or governance meaning. |
| Boundary classification | Whether the AI use was allowed support, conditional support, disallowed authority, or adversarial pattern. | The record uses the T8 role-boundary vocabulary as review prep without turning it into policy. | The record names a boundary but not the reason. | A fixture, prompt, or AI suggestion silently changes AI-use policy. |
| Contestability | What the contributor can challenge or revise. | The contributor can contest the human rationale, source trace, classification, or missing evidence without needing hidden prompts. | The review state is visible but the route to correction is not. | The contributor would need private model output or founder context to understand the adverse decision. |
| Loss or deferred value | What useful residue remains if the contribution is revised, narrowed, or not accepted as-is. | `loss_notes` can preserve the useful warning, source lead, or critique without implying reward or future claim. | The review discards useful AI-assisted critique because policy adoption is unsafe. | Loss notes become a reward promise, legal claim, retained-value right, or policy commitment. |
| Capture-risk screen | Whether AI use creates synthetic consensus, volume pressure, hidden bias, or rubric gaming. | The review names any AI-specific attack signal and the human check that reduced it. | Multiple AI outputs are counted as independent support. | Synthetic consensus, undisclosed volume, or AI-scored value is treated as legitimacy evidence. |

## Candidate Review Note Shape

This shape is illustrative only. It is not a schema change.

```yaml
ai_use_disclosed: true
ai_task:
  - summary_support
  - rubric_disagreement_prompt
source_scope:
  model_saw:
    - contribution proposal
    - cited source excerpts
  human_checked:
    - proposal target
    - stable source links
    - relevance to claim or test
decision_owner: human reviewer
authority_boundary: AI output did not decide review state, score, reward, rights, legitimacy, or policy.
contestability_note: Contributor can challenge the human rationale, source trace, and missing-evidence finding.
loss_notes: Useful warning preserved; proposed policy language not adopted.
capture_risk_check:
  - synthetic consensus not counted as participant voice
  - AI-generated source leads require human verification
```

## Routing Questions For Later Reviews

These questions help a later reviewer decide whether a record is ready for a
real pilot. They do not assign a live review state.

1. If the contribution is AI-assisted, is the contribution unit small enough to
   review without rewarding volume?
2. If AI helped with prior art, are stable sources and mechanism-level limits
   present?
3. If AI helped with critique, is the failure mode observable without trusting
   the model?
4. If AI helped draft a rationale, is the decisive human reason separately
   visible?
5. If AI suggested a score, is the score clearly non-binding and used only as a
   rubric stress test?
6. If AI simulated reviewers, is that simulation separated from actual
   contributor voice?
7. If the AI-assisted contribution proposes policy language, is the useful
   warning preserved without adopting the policy?

## Later Evidence Needed

A future C7/T8 review would be stronger if it can compare this checklist against:

- one real AI-assisted contribution proposal;
- one adverse or `needs_revision` decision where the human rationale is visible;
- one source-backed AI lead that is verified or rejected by a human reviewer;
- one case where useful AI-assisted wording is preserved in loss notes without
  becoming policy; and
- one capture-risk note that distinguishes AI volume from contributor voice.

Those later artifacts should remain separate from any decision to change AI-use
policy, contribution standards, reward meaning, rights meaning, or governance.

## Boundary Notes

- No AI-use policy changed.
- No contribution policy changed.
- No issue template changed.
- No governance rule changed.
- No claim status changed.
- No public posture changed.
- No T8 pass/fail state changed.
- No real contribution was submitted, accepted, revised, rejected, contested,
  scored, logged, or rewarded.
- No reward, retained-value, rights, legal, or financial promise is created.
