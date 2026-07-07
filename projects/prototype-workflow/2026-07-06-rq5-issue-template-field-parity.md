---
artifact_type: research_scaffold
status: draft
created: 2026-07-06
research_question: RQ5 prototype workflow
governance_role: non_adopted_field_parity_check
constitutional: false
---

# RQ5 Issue-Template Field-Parity Check

Status: draft scaffold, not adopted workflow policy.

This check compares the current contribution submission surfaces before the
first real pilot. It does not change `CONTRIBUTING.md`, contribution standards,
issue templates, review policy, reviewer authority, contribution-log schema,
claim status, test pass/fail state, governance, public posture, reward meaning,
or any real contribution record.

## Why This Exists

The RQ5 prototype workflow synthesis asks which fields from the Markdown
proposal and GitHub issue form must remain identical. That question matters
because field drift can make the first pilot look public and inspectable while
silently dropping the context a reviewer needs later.

The current surfaces are close, but not identical:

- `templates/contribution-proposal.md` is the richest contributor-facing
  template.
- `.github/ISSUE_TEMPLATE/contribution-proposal.yml` is the structured GitHub
  form most likely to be used for first public intake.
- `.github/ISSUE_TEMPLATE/contribution.md` is a legacy Markdown issue template
  with some fields that the structured form omits.
- `templates/contribution-log-schema.md` is a reviewer/project record schema,
  not a submission form.

The safe next step is not to edit the templates immediately. It is to make the
field drift visible enough for a later governed workflow decision.

## Submission Field Comparison

| field or meaning | Markdown proposal template | structured GitHub contribution form | legacy Markdown issue template | log schema | parity risk |
|---|---|---|---|---|---|
| Title | `Title` field. | GitHub issue title prefix. | GitHub issue title prefix. | Not a field. | Low: title can live in issue metadata. |
| Contributor identity or pseudonym | `Contributor` field, with agent-assisted yes/no. | Missing. | Missing. | `contributor` records name or pseudonym and agent assistance. | Medium: later attribution and agent accountability may require reviewer inference. |
| Contribution class | Explicit class field. | Required dropdown. | Explicit class prompt. | `class`. | Low: all submission paths preserve the class meaning. |
| Target | Target files or claims. | Required `target` field. | Target files or claims. | `target`. | Low: all submission paths preserve target meaning. |
| Summary or contribution unit | `Summary`. | Required `contribution` field. | "What does it do / why is it relevant" prompt. | Partly in `rationale` and links. | Medium: summary and review rationale can blur unless the review later names the accepted unit. |
| Why it matters | Folded into `Summary`. | Required `why` field. | Folded into relevance prompt. | Not a standalone field. | Medium: the structured form has the clearest prompt; the Markdown template may rely on contributor judgment. |
| Evidence or reasoning | Prior art / sources field with research-class requirements. | Optional `evidence` field with research-class requirements. | Prior art / sources prompt. | `links` plus `rationale`. | Medium: optional evidence is correct for non-research work, but research-class submissions need review attention. |
| Source limits | Named in source prompt. | Named in evidence prompt. | Named in source prompt. | Not explicit. | Medium: source limits may disappear when the reviewer converts a submission into a log entry. |
| Value self-assessment | Explicit 0-3 rubric self-assessment. | Missing. | Explicit 0-3 rubric self-assessment. | `rubric_scores` as reviewer/project scores. | High: contributor self-assessment can be useful evidence, but scores can be mistaken for reward shares. |
| Failure or risk | Explicit field. | Optional `risks` field. | Explicit field. | Partly in `rationale` or `loss_notes`. | Low to medium: the meaning survives, but optionality should be intentional. |
| Loss or deferred value | Explicit field. | Optional `loss_or_deferred_value` field. | Explicit field. | `loss_notes`. | Low to medium: the meaning survives, but reviewer conversion should avoid reward promises. |
| Proposed review state on submit | Defaults to `submitted`. | Missing. | Missing. | `review_state`. | Low if all issues enter as `submitted`; medium if missing state creates ambiguity in first-pilot traces. |
| Reviewer-only rationale | Reviewer-use section. | Missing. | Missing. | `rationale`. | Low: reviewer fields should usually stay out of submitter forms. |
| Reviewer rubric scores | Reviewer-use section. | Missing. | Missing. | `rubric_scores`. | Low: reviewer scoring should not be prefilled by submitters. |

## Minimum Parity Set For Later Review

For a first real pilot, the submission surfaces should preserve the same meaning
for these fields:

1. Contribution class.
2. Target file, claim, test, document, or research question.
3. Contribution unit or summary.
4. Evidence or reasoning, including source limits for research-class work.
5. Failure or risk.
6. Loss or deferred value.
7. Contributor identity, pseudonym, or agent-assistance accountability.

The first six are already mostly covered. The seventh is the clearest mismatch:
the Markdown proposal template asks for contributor/agent-assistance context,
and the log schema needs contributor context, but the structured GitHub form does
not collect it directly.

## Fields That Should Not Be Flattened

Some fields should stay different across submission and review records:

- `review_state` belongs to project review, not contributor self-certification.
- `rationale` belongs to reviewer/project reasoning.
- reviewer `rubric_scores` should not be confused with contributor
  self-assessment or future reward shares.
- `id`, `date`, and `links` are record fields created when a contribution is
  logged, not when it is merely proposed.

Flattening these fields into one form would make intake easier but weaken the
line between proposal, review, and accepted record.

## Candidate Repair Packets

These are later review packets, not changes made here:

| packet | possible change | benefit | stop boundary |
|---|---|---|---|
| Structured GitHub form parity | Add a contributor/accountability prompt and optional value self-assessment prompt to `.github/ISSUE_TEMPLATE/contribution-proposal.yml`. | Makes the likely public intake path closer to the Markdown proposal. | Do not adopt without deciding whether agent-assistance and rubric self-assessment should be public intake fields. |
| Legacy Markdown issue template cleanup | Decide whether `.github/ISSUE_TEMPLATE/contribution.md` should remain, redirect to the structured form, or mirror it exactly. | Reduces duplicated public intake surfaces. | Do not delete or retire a template in a scheduled run without review. |
| Log conversion checklist | Create a reviewer-only checklist for converting a proposal into a log-eligible record. | Preserves distinction between submitter claims and project rationale. | Do not change `templates/contribution-log-schema.md` or live log policy from this scaffold. |
| Disclosure placement review | Use the RQ1 disclosure matrix to decide where agent assistance, affiliation, and conflict prompts belong. | Avoids identity gatekeeping while keeping review-relevant context visible. | Do not adopt mandatory disclosure policy from this artifact. |

## First-Pilot Readiness Implication

The first pilot can still use the structured GitHub contribution form if the
reviewer explicitly checks for missing contributor/accountability context and
source limits before moving from `submitted` to a review state.

The safer first-pilot trace would record:

- which submission surface was used;
- whether contributor or agent-assistance context was visible;
- whether research-class evidence requirements were satisfied;
- whether contributor self-assessment was present or absent;
- how the reviewer converted the submission into rationale, scores, links, and
  loss notes without creating reward or retained-right meaning.

## Later Adoption Questions

- Should the structured GitHub form ask for contributor identity or pseudonym,
  or is GitHub account identity enough for the first pilot?
- Should agent-assistance disclosure be a dedicated intake field, a reviewer
  prompt, or part of a later RQ1 disclosure policy?
- Should contributor value self-assessment be collected on intake, or does it
  make score-to-reward confusion too likely?
- Should the legacy Markdown issue template stay available once the structured
  form is the preferred path?
- Should the first pilot require a reviewer-only log-conversion checklist before
  any live `CONTRIB-NNNN` entry is created?

## Boundary Notes

- No issue template changed.
- No active contribution instruction changed.
- No contribution standard, review state, log schema, governance rule, appeal
  path, participant right, reward meaning, claim status, public posture, or
  test pass/fail state changed.
- No real contribution, issue, PR, review decision, score, log entry, dispute,
  reward, retained claim, or contributor identity was created or decided.
- This scaffold is draft workflow evidence for later RQ5/RQ1 review, not active
  contribution policy.
