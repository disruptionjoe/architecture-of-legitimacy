---
artifact_type: research_scaffold
status: draft
created: 2026-07-06
research_question: RQ1 contributor and contribution eligibility
governance_role: non_adopted_edge_case_matrix
constitutional: false
---

# RQ1 Disclosure Edge-Case Matrix

Status: draft scaffold, not adopted policy.

This matrix pressure-tests when contributor identity, affiliation, conflicts, pseudonymity, agent assistance, private evidence, and adversarial incentives become review-relevant.

It does not change `CONTRIBUTING.md`, `CONTRIBUTION-STANDARDS.md`, issue templates, governance mode, review authority, claim status, reward meaning, participant rights, public posture, or any real contribution record.

## Why This Exists

The RQ1 eligibility scaffold separates open attemptability from acceptance, authority, reward, and governance participation. The remaining practical problem is disclosure: reviewers need enough context to evaluate risk without turning identity, credentials, or proximity into hidden gatekeeping.

This artifact treats disclosure as a review-relevance question:

```text
Ask only for the context needed to evaluate the contribution, its evidence, and its incentives.
```

That keeps the project from collapsing into either:

- credential gatekeeping, where identity decides eligibility before substance is reviewed; or
- naive openness, where hidden incentives, private evidence, or automated volume can distort review.

## Review-Relevance Matrix

| edge case | attemptability default | disclosure question | review risk | safe first-pass handling |
|---|---|---|---|---|
| Pseudonymous contributor, independently checkable source-backed research | attemptable | Can the contributor maintain continuity for revision and attribution? | Future contestability may break if identity continuity disappears. | Review the work on substance; record the stable pseudonym if the contribution is logged later. |
| Pseudonymous contributor using private or privileged evidence | higher-risk attemptable | What evidence can be made public enough for review? | Reviewers may be unable to verify claims without hidden trust. | Route to `needs_revision` unless public, non-sensitive evidence can support the claim. |
| Contributor affiliated with a compared project or cited system | attemptable with disclosure | What affiliation could affect interpretation? | Mechanism comparison may become advocacy or reputation laundering. | Review the mechanism-level argument and note the affiliation as context, not automatic disqualification. |
| Contributor has direct financial interest in the outcome | attemptable with disclosure | What value transfer or market position could be affected? | Incentives may bias reward, governance, or retained-value proposals. | Keep review possible, but escalate reward/governance implications to founder review before adoption. |
| Agent-assisted draft with named human accountable for revision | attemptable | What tool/process helped, and what did the human verify? | Generated confidence may hide weak reasoning or fabricated support. | Review if sources, reasoning, and uncertainty are inspectable; require revision if the human cannot explain it. |
| Agent-generated bulk submissions without accountable human judgment | normally ineligible in current form | Who is responsible for quality, triage, and correction? | Review capacity can be exhausted by volume tactics. | Treat as spam/flooding or `needs_revision` depending on whether a bounded accountable submission can be extracted. |
| Contribution proposes eligibility, review, governance, or reward changes | attemptable but governance-sensitive | Which active rule would change if adopted? | A normal contribution path could silently move hard policy. | Accept only as non-adopted proposal/scaffold unless Joe or governance explicitly authorizes adoption. |
| Contributor asks for retained value, reward, ownership, or legal recognition | attemptable only as a proposal, not entitlement | Is this framed as research input or a claim on the project? | Premature reward or legal meaning can outrun the research phase. | Preserve useful reasoning while rejecting entitlement language before any reward system exists. |
| Submission contains private, confidential, regulated, or proprietary material | likely not reviewable publicly | Can the claim be restated using public or permitted evidence? | The repo may launder material it cannot safely hold. | Stop public intake of the sensitive material; ask for a public-safe version or route outside repo scope. |
| Contributor is adversarially interested in weakening the project | attemptable only when substance is bounded and reviewable | What incentive or attack vector is relevant? | Bad-faith proposals can smuggle capture paths into normal review. | Evaluate bounded critique or red-team value; reject coercion, deception, hidden paid advocacy, or capture attempts. |

## Synthetic Routing Cases

### Case A: Pseudonymous Prior-Art Note

A pseudonymous contributor submits a source-backed comparison to a neighboring system, names a live research question, and includes limitations.

Likely first-pass state: `submitted` or `triaged`.

Reason: the contribution is independently assessable. Identity is not necessary for review if continuity and attribution can be maintained through the pseudonym.

Disclosure still relevant:

- whether the contributor is affiliated with the compared system;
- whether any cited evidence is private or public;
- whether agent assistance was used.

### Case B: Agent-Written Rubric Proposal

A named contributor submits an agent-assisted rubric proposal and says an AI model drafted most of it.

Likely first-pass state: `submitted` if the human can explain and revise it; `needs_revision` if the proposal cannot separate generated language from actual reasoning.

Reason: agent assistance is not disqualifying. The review problem is whether accountability, evidence, and failure modes are visible enough.

Disclosure still relevant:

- what human review occurred;
- whether sources were checked;
- whether the proposal changes reward, governance, or reviewer authority.

### Case C: Governance-Change Proposal From Interested Party

A contributor affiliated with a system that would benefit from a future pilot proposes a governance transition trigger.

Likely first-pass state: `submitted` or `needs_revision`, not adopted.

Reason: affiliation is relevant but not automatically disqualifying. The governance-change surface requires extra boundary handling because adoption would change power, not just add research context.

Disclosure still relevant:

- affiliation and expected benefit;
- whether the proposal affects phase movement, reviewer authority, or public posture;
- whether the argument can be evaluated without private context.

### Case D: Reward Entitlement Claim

A contributor submits useful analysis but states that acceptance should create a future payout or retained-value right.

Likely first-pass state: split the useful analysis from the entitlement claim.

Reason: the analysis may be reviewable, but the entitlement language crosses a boundary the repo has not adopted.

Disclosure still relevant:

- whether the contributor is proposing a research model or asserting a right;
- whether any reward/retained-value claim is being smuggled into normal review;
- what useful value should be preserved if the entitlement portion is rejected.

## Draft Decision Rules For Later Review

These are review prompts, not current policy:

1. If the work is independently assessable, identity should rarely decide attemptability.
2. If the contributor's incentive materially affects interpretation, ask for disclosure before review hardens.
3. If the evidence cannot be reviewed publicly and safely, do not let the public repo become the holding place for the evidence.
4. If agent assistance is used, require accountable human judgment before the work can become more than draft material.
5. If the contribution would change governance, reward, rights, review authority, or public posture, keep it explicitly non-adopted until the proper authority approves it.
6. If a submission contains both useful reasoning and boundary-crossing claims, preserve the useful reasoning while rejecting or deferring the boundary-crossing part.

## Later Adoption Questions

- Should disclosure prompts live in `CONTRIBUTING.md`, the GitHub issue form, the Markdown proposal template, or a separate reviewer checklist?
- Which disclosures are mandatory for the first public pilot, and which are optional context?
- How can pseudonymous contributors preserve continuity without forcing real-name identity?
- What minimum human-accountability statement is enough for agent-assisted work?
- When should undisclosed conflict move a contribution from `needs_revision` to `not_accepted` or `adversarial`?
- What public-safe path exists when a potentially valuable contribution depends on private evidence?

## Boundary Notes

- No real contributor, contribution, issue, PR, dispute, reward, or governance case is selected or decided.
- No active eligibility rule, disclosure requirement, pseudonymous-contribution policy, agent-contribution policy, conflict policy, reward logic, retained-value right, governance rule, claim status, test pass/fail state, or public posture changed.
- This scaffold exists to make a future RQ1 policy review more inspectable, not to become policy by itself.
