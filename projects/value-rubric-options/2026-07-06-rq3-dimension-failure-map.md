---
artifact_type: value_rubric_dimension_failure_map
status: draft_failure_map
created: 2026-07-06
research_target: RQ3 initial value rubrics
test_target: T2 value rubric dry run
governance_role: internal_research_scaffold
constitutional: false
---

# RQ3 Value-Rubric Dimension Failure Map

Status: draft failure map, not adopted rubric policy.

Purpose: pressure-test the current value-rubric dimensions one by one so later reviewers can see where scores may become arbitrary, gameable, redundant, or governance-sensitive before any active contribution standard changes.

This file does not change `CONTRIBUTION-STANDARDS.md`, active score meanings, reviewer authority, reward meaning, governance rules, claim status, public posture, test pass/fail state, or any real contribution record. It is a bounded RQ3/T2 research scaffold.

## Source Surfaces Used

- `RESEARCH-AGENDA.md`, especially RQ3
- `TESTS.md`, especially T2
- `CONTRIBUTION-STANDARDS.md`, especially the initial value rubric
- `projects/value-rubric-options/2026-07-02-rq3-value-rubric-options.md`
- `projects/value-rubric-dry-run/2026-07-02-t2-value-rubric-dry-run.md`

## Boundary Under Review

The current provisional rubric has seven dimensions:

- `clarity`
- `rigor`
- `relevance`
- `novelty`
- `legitimacy`
- `capture resistance`
- `coordination value`

The problem this map studies is not whether those dimensions should be adopted, replaced, or scored differently. The problem is whether a reviewer can name the failure mode when a dimension is used badly.

The useful output from a later review is not a higher score. It is a more inspectable reason.

## Dimension Failure Map

| dimension | intended value signal | common false positive | collapse risk | repair question | review note to preserve |
|---|---|---|---|---|---|
| `clarity` | The contribution makes the project easier to understand, inspect, or use. | Smooth prose hides missing evidence, changed meaning, or unresolved disagreement. | Collapses into polish or persuasion. | What exact confusion, ambiguity, or workflow burden did this remove? | Name the before-state that became easier to inspect. |
| `rigor` | The contribution makes a claim, model, comparison, or workflow more precise and defensible. | Formal language or citations look rigorous while assumptions remain missing. | Collapses into technical difficulty. | Which assumption, source limit, test condition, or inference boundary became clearer? | Record the strongest remaining uncertainty. |
| `relevance` | The contribution addresses a live claim, test, research question, or workflow need. | A plausible adjacent topic receives credit because it sounds related. | Collapses into topical similarity. | Which live repo surface would change, be tested, or be better understood if the contribution succeeds? | Link the contribution to the exact agenda or test target. |
| `novelty` | The contribution surfaces a non-obvious distinction, model, evidence path, or failure mode. | New wording or unusual framing is mistaken for a new object. | Collapses into surprise. | What distinction would the repo miss without this contribution? | State whether novelty strengthens the claim or narrows an overclaim. |
| `legitimacy` | The contribution improves voice, exit, contestability, transparency, or trust in the process. | Fair-sounding language hides who can challenge, revise, or inspect the record. | Collapses into moral approval. | Who can reconstruct, question, or contest the decision after this contribution? | Preserve the actor, record, and challenge path affected. |
| `capture resistance` | The contribution reduces, exposes, or makes testable an attack, gaming, extraction, or authority-risk pathway. | A generic safety warning scores well without changing the protocol's visible risk model. | Collapses into pessimism or vibes. | Which attacker incentive, success probability, detection path, or mitigation question changed? | Name the attack surface and the remaining profitable route. |
| `coordination value` | The contribution helps future contributors know what to do next or reduces coordination cost. | Activity, volume, or administrative neatness looks valuable without improving future action. | Collapses into busyness. | What future action is easier, safer, or less founder-dependent because of this work? | Record the next user and the next action made clearer. |

## Cross-Dimension Collision Cases

| collision | bad review pattern | better review discipline |
|---|---|---|
| `clarity` versus `synthesis` polish | A rewrite receives high clarity because it sounds cleaner, even if it drops tension or changes meaning. | Ask what source meanings were preserved and what became easier to inspect. |
| `rigor` versus `novelty` | A contribution gets novelty credit for formal vocabulary even though the model does not add testable assumptions. | Separate the new object from the evidence or model that makes it usable. |
| `relevance` versus adoption pressure | A live governance-sensitive proposal receives high relevance and is treated as ready to adopt. | Score usefulness separately from authority movement, policy adoption, or rights changes. |
| `legitimacy` versus capture resistance | Fairness language receives legitimacy credit while attack incentives remain unchanged. | Require at least one visible contestability or transparency improvement and one attack-path observation when both dimensions are claimed. |
| `coordination value` versus popularity | Many small submissions appear coordinated because they create activity. | Ask whether the work reduces future review cost or only adds queue volume. |
| low `novelty` versus high truth value | Prior art that narrows the project's novelty is undervalued because it is not exciting. | Credit truth-seeking under rigor, legitimacy, and capture resistance even when novelty decreases. |

## Use With The T2 Dry Run

The existing T2 fixture can use this map as a reviewer prompt without changing score meanings.

| T2 sample | dimension failure to watch | prompt |
|---|---|---|
| `T2-SAMPLE-01` | Low novelty may be misread as low value. | Does familiar prior art still increase rigor, legitimacy, or capture resistance? |
| `T2-SAMPLE-02` | Rigor may hide missing assumptions. | Which variable or assumption is still not reviewable? |
| `T2-SAMPLE-03` | Coordination value may mask capture risk. | What authority path stays founder-dependent or opaque? |
| `T2-SAMPLE-04` | Capture resistance may be credited too generally. | Which gaming path is actually changed by the batching mitigation? |
| `T2-SAMPLE-05` | Maintenance may be undervalued because novelty is zero. | Which future review or contribution action became easier? |
| `T2-SAMPLE-06` | Implementation may become opaque reviewer authority. | What false-positive or human-review boundary must remain visible? |
| `T2-SAMPLE-07` | Clarity may be confused with persuasive prose. | What source, claim, test, or workflow surface became clearer? |
| `T2-SAMPLE-08` | Relevance may pressure governance adoption. | Which part is worth preserving without granting power? |
| `T2-SAMPLE-09` | High truth value may be bundled with a claim-status move. | What evidence can be kept while deferring authority movement? |
| `T2-SAMPLE-10` | Prior-art collision may look like project weakening. | How does narrowed novelty improve truthfulness or legitimacy? |

## Later Review Questions

1. Which dimensions most often receive false-positive scores?
2. Which dimensions collapse into each other during actual review?
3. Which contribution classes need a dimension-specific rationale note before scoring is useful?
4. Which dimensions are most vulnerable to AI-generated volume or polish?
5. Which dimensions should be checked before acceptance state, and which should only inform synthesis?
6. What evidence would justify changing the active rubric instead of only improving reviewer notes?

## Non-Adoption Boundary

This map can inform later RQ3/T2 review, but it does not:

- add or remove rubric dimensions;
- change score meanings;
- define score aggregation;
- change review states;
- change `CONTRIBUTION-STANDARDS.md`;
- create reward, retained-value, governance, or participant-rights meaning;
- mark T2 passed;
- decide any real contribution.
