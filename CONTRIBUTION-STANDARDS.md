# Contribution Standards

This file defines the first working standards for contribution. These standards are provisional and should be improved by contributors.

## Open Attemptability

Anyone may attempt to contribute if they follow project rules.

Open attemptability does not mean:

- every contribution is accepted,
- every contributor receives governance power,
- every submission receives reward,
- or every participant has equal context or authority.

It means identity, status, credentials, history, or social proximity should not block someone from attempting useful work.

## Contribution Classes

### Research

Adds relevant prior art, source-backed comparison, or literature context.

Good example:

> A comparison of this project's legitimacy schema to Elinor Ostrom's design principles and retroactive public goods funding.

Weak example:

> A broad list of links with no explanation of relevance.

### Formalization

Turns a claim into definitions, variables, models, tests, or failure conditions.

Good example:

> A toy payoff model that identifies conditions under which collaboration dominates defection.

Weak example:

> A confident statement that collaboration is better without a model.

### Protocol Design

Proposes rules, workflows, roles, rights, or phase transitions.

Good example:

> A review cadence proposal with decision states, appeal path, and failure modes.

Weak example:

> "Let the community vote" without specifying who counts, what is voted on, or how capture is prevented.

### Review

Improves rigor by finding errors, overclaims, missing prior art, attack paths, or legitimacy failures.

Good example:

> A red-team critique showing how a proposed rubric can be gamed.

Weak example:

> A dislike response without actionable reasoning.

### Synthesis

Integrates multiple contributions into clearer project state.

Good example:

> A revised claim ledger that demotes overclaims and links each claim to a test.

Weak example:

> Rephrasing existing text without improving structure or accuracy.

### Implementation

Builds tools, templates, automation, or workflows that support the research program.

Good example:

> A script that validates contribution-log fields or checks internal links.

Weak example:

> A polished app before the underlying workflow is defined.

### Maintenance

Improves the usability, consistency, or upkeep of existing project surfaces without changing research claims.

Good example:

> A link fix, taxonomy alignment, or issue-template cleanup that makes contribution review easier to run.

Weak example:

> Rewriting project direction while labeling the change as cleanup.

## Research-Class Evidence Minimum

Research-class and prior-art contributions should include enough evidence for a reviewer to evaluate the contribution without private context.

A first pass should:

- name the source, system, author, or practice being compared;
- provide a stable citation, link, or bibliographic reference for each central source;
- explain why the source matters to a live claim, test, document, or research question;
- compare mechanisms rather than only labels, especially contribution validation, value allocation, voice, contestability, and capture risk where relevant;
- separate what the source shows from what the contributor infers;
- name at least one limitation, uncertainty, or failure mode of the comparison.

Missing one or more of these elements should usually lead to `needs_revision`, not automatic rejection. This threshold supports review clarity; it does not create reward, retained-value, governance, or legal claims.

## Initial Value Rubric

Each accepted contribution may be evaluated across these dimensions:

| dimension | question |
|---|---|
| clarity | Does it make the project easier to understand or use? |
| rigor | Does it make a claim more precise, testable, or defensible? |
| relevance | Does it address a live research question? |
| novelty | Does it surface a non-obvious distinction, model, or path? |
| legitimacy | Does it improve voice, exit, contestability, transparency, or trust? |
| capture resistance | Does it reduce or clarify attack risk? |
| coordination value | Does it help future contributors know what to do next? |

Suggested scoring for early tests:

- `0`: not present,
- `1`: useful but minor,
- `2`: substantial,
- `3`: project-shaping.

Scores should not be treated as automatic reward. They are a tool for discussion.

## Review States

- `submitted`: contribution received.
- `triaged`: contribution classified by type.
- `accepted`: useful enough to enter the project record.
- `needs_revision`: promising but incomplete.
- `not_accepted`: not useful for the project in current form.
- `contested`: contributor or reviewer challenges the classification.
- `adversarial`: spam, manipulation, plagiarism, or bad faith.

## Review Cadence

Initial proposal:

- simple maintenance contributions can be reviewed continuously,
- substantive research contributions should be reviewed in batches,
- contested decisions should be summarized publicly,
- monthly synthesis should update claims, tests, and roadmap.

## First Valid Contribution

A first valid contribution should do one of the following:

- improve one claim in [CLAIMS.md](CLAIMS.md),
- add a source-backed prior-art comparison,
- propose or test a value rubric,
- add an attack scenario to [THREAT-MODEL.md](THREAT-MODEL.md),
- refine the toy payoff model in [TESTS.md](TESTS.md),
- or improve the contribution workflow itself.
