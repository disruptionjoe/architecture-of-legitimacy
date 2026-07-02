---
artifact_type: ai_role_boundary_fixture
status: synthetic_test_fixture
created: 2026-07-02
test_target: T8 AI role boundary
governance_role: internal_test_record
constitutional: false
---

# T8 AI Role Boundary Fixture

Status: synthetic test fixture.

Purpose: pressure-test whether the current AI guardrails can distinguish useful
AI support from illegitimate AI authority in contribution review.

This file is not an AI-use policy, governance decision, claim-status decision,
public-posture change, live contribution decision, or evidence that T8 has
passed. It is a bounded test object for making the AI review boundary more
inspectable before real contributions depend on it.

## Source Surfaces Used

- `GUARDRAILS.md`
- `CLAIMS.md`, especially C7
- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `LEGITIMACY-SCHEMA.md`
- `PROTOCOL-STACK.md`
- `THREAT-MODEL.md`
- `TESTS.md`

## Boundary Under Test

The current guardrails permit AI use for critique, synthesis, rubric testing,
prior-art exploration, attack-surface ideation, and drafting proposals.

The same guardrails reject AI as neutral authority, final judge, source of
legitimacy, replacement for participant voice, or cover for founder preference.

For this fixture, the practical review question is:

```text
Can a reviewer use AI output while keeping the final judgment visible,
contestable, human-owned, source-traceable, and non-capturing?
```

## Use Pattern

For each AI-assisted review event, reviewers should be able to record:

- who used AI;
- what task the AI performed;
- what source material the AI saw;
- whether the AI output affected triage, evidence review, scoring, rationale,
  or synthesis;
- what the human reviewer independently checked;
- which final judgment was made by a person or governed process;
- what a contributor can contest;
- and whether the AI role is allowed support, conditional support, disallowed
  authority, or an adversarial pattern.

The useful result is not a ban list. The useful result is a boundary that lets
AI improve review quality without laundering authority.

## Role Boundary Matrix

| id | AI use case | boundary classification | allowed review use | failure mode if mishandled | minimum visible trace |
|---|---|---|---|---|---|
| T8-AI-01 | Summarize a contribution proposal for a reviewer. | allowed support | Use as an orientation aid before the reviewer checks the proposal directly. | The summary becomes the reviewer's only basis for decision. | Note that AI summarized; link or quote the source proposal; record human rationale. |
| T8-AI-02 | Suggest contribution classes for triage. | conditional support | Treat suggestions as prompts while the reviewer names the primary class and ambiguity. | AI classification silently becomes the project's taxonomy decision. | Record final class, alternative classes considered, and reviewer reason. |
| T8-AI-03 | Draft a review rationale. | conditional support | Use as wording support after the reviewer has decided the rationale. | Founder or reviewer preference is hidden behind polished AI prose. | Record the decisive human reason and any material AI wording assistance. |
| T8-AI-04 | Score a value rubric. | disallowed authority; conditional as test input | Use only as a rubric stress test or comparison point. | AI score becomes the final value judgment or reward signal. | Human score, disagreement notes, and statement that AI score is non-binding. |
| T8-AI-05 | Generate prior-art leads. | conditional support | Use as search leads requiring stable sources and mechanism-level comparison. | Hallucinated or label-level prior art narrows novelty without evidence. | Source citations checked by a human and limits recorded. |
| T8-AI-06 | Red-team attack paths. | allowed support | Use for attack-surface ideation and review questions. | AI-generated threat language is treated as proof of capture risk. | Human-selected threat class, observable signal, and mitigation boundary. |
| T8-AI-07 | Simulate multiple reviewer opinions. | conditional support | Use as a private rehearsal for possible objections. | Synthetic reviewer voices are treated as participant voice or consensus. | Label as simulation and separate it from actual contributor or reviewer feedback. |
| T8-AI-08 | Produce apparent consensus across several AI runs. | disallowed authority | Use only as evidence of synthetic-consensus risk. | Many AI outputs are counted as independent legitimacy evidence. | Record that repeated AI outputs are not participant agreement. |
| T8-AI-09 | Detect duplicate, dependent, or source-overlapping submissions. | allowed support | Use to flag review questions for human verification. | A contributor is penalized for unverified similarity. | Verified duplicate/dependency links and human check notes. |
| T8-AI-10 | Propose AI-use policy language. | conditional support; governance-sensitive | Preserve as a proposal or test input. | Policy changes through a fixture or review note without governance review. | Mark as not adopted and route any policy change through review. |
| T8-AI-11 | Draft a contribution by an AI-assisted contributor. | conditional support | Accept as a labeled submission when human review and responsibility are clear. | Bulk plausible text overwhelms review and creates false contribution value. | AI-use disclosure, human review statement, and contribution-unit boundaries. |
| T8-AI-12 | Submit undisclosed AI-generated volume. | adversarial pattern | Treat as spam, manipulation, or at least review-risk evidence. | The project mistakes volume for legitimacy, consensus, or contribution weight. | Similarity signals, disclosure gap, triage state, and rejection or revision rationale. |

## Review Boundary Probes

For any AI-assisted review, ask:

1. Can a future contributor tell what the AI did?
2. Can the contributor contest the actual decision without needing access to a
   hidden prompt or private model output?
3. Did a human reviewer verify sources, links, claims, and relevance?
4. Is the final judgment attributable to a person or governed process rather
   than to the AI system?
5. Does the record distinguish evidence from synthesis, speculation, and
   wording assistance?
6. Could the AI role create synthetic consensus, hidden bias, or review-volume
   pressure?
7. Would accepting the AI output silently change claims, governance, policy,
   reward meaning, or public posture?

## Candidate Fields For Later Review Records

These are review probes, not schema changes.

```yaml
ai_use_disclosed: true
ai_role: synthesis_support
ai_touched: summary | triage_prompt | rationale_draft | rubric_test | prior_art_leads | red_team
human_checks:
  - source material reviewed directly
  - claims verified against cited sources
  - final rationale written or approved by reviewer
authority_boundary: AI output did not decide review state, score, reward, or legitimacy.
contestability_note: Contributor can challenge the human rationale and source trace.
```

## Synthetic Review Trace

Scenario: a reviewer uses AI to summarize a long prior-art contribution and to
suggest possible rubric disagreements.

Safe trace:

1. Reviewer discloses AI summarization in the review note.
2. Reviewer checks the cited sources directly.
3. Reviewer records which rubric suggestions were accepted, rejected, or
   treated as uncertain.
4. Reviewer writes the final `needs_revision` rationale in their own name.
5. The review note explains what the contributor can revise or contest.

Unsafe trace:

1. Reviewer pastes the AI summary as the rationale.
2. Reviewer adopts an AI rubric score without naming disagreement or evidence.
3. Contributor cannot tell whether the decision came from the project, the
   founder, or the model.
4. The record says the contribution "lacks legitimacy" without explaining a
   visible source, rule, or review path.

## Pass Criteria For A Later T8 Review

T8 can move toward a stronger result when:

- allowed AI support, conditional support, disallowed authority, and adversarial
  AI patterns can be classified without private founder context;
- every AI-assisted review record can identify what the AI did and what a human
  checked;
- AI outputs do not supply final review state, value score, reward implication,
  contribution legitimacy, participant voice, or governance authority;
- contributors can contest the human rationale and source trace;
- and synthetic consensus or hidden AI volume maps to capture-risk review rather
  than contribution weight.

This fixture does not mark T8 passed. It gives the repo a repeatable object for
testing whether AI can support review without becoming an opaque substitute for
legitimacy.

## Boundary Notes

- No AI-use policy changed.
- No governance rule changed.
- No claim status changed.
- No public posture changed.
- No T8 pass/fail state changed.
- No real contribution was submitted, accepted, revised, rejected, contested, or
  rewarded.
- No reward, retained-value, legal, or financial promise is created.
