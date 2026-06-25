# Legitimacy Monad S7 Crosswalk

**Date:** 2026-06-25
**Status:** Active integration note

## Summary

The categorical Legitimacy Monad from the Time as Finality / GU S7 thread
supplies a formal engine for this repo's operational legitimacy schema.

In categorical language:

```text
local records P
  -> legitimacy operation eta_P : P -> L(P)
  -> legitimate records L(P)
```

In this repo's institutional language:

```text
raw contribution evidence
  -> validation, review, contestability, synthesis, and logging
  -> accepted records that participants can inspect, contest, and build on
```

This does not make legitimacy automatic or solved. It gives the protocol stack
a formal target: specify the operation that turns local, provisional,
contestable contribution data into stable institutional records without hiding
loss, disagreement, or capture risk.

## Key Mapping

| S7 object | Architecture-of-Legitimacy object |
| --- | --- |
| Presheaf layer | Raw contributions, persona outputs, provisional claims, review fragments, dispute evidence. |
| Local obstructions | Conflicting evaluations, missing provenance, unclear eligibility, contested value, capture attempts. |
| Legitimacy operation `L` | Validation, review, synthesis, appeal, rule update, and contribution-log admission. |
| Unit `eta_P : P -> L(P)` | The visible path from submitted contribution evidence to accepted institutional record. |
| Legitimate fixed point | Accepted contribution/log/governance artifact stable enough for participants to build on. |
| `Lose[K]` profile | What is filtered, compressed, rejected, anonymized, or deferred during validation. |
| Signed readout separation | Value/reward can be non-monotone while provenance and record visibility remain stable. |
| Provenance partial order | Contribution log, review history, appeal history, and governance-change chain. |
| Gluing obstruction | Contestability or non-capture failure that blocks institutional acceptance. |

## Claim Ledger Fit

### C2: Coupled Protocol Stack

S7 strengthens C2 because legitimacy is not one module in the stack. The
operation `L` crosses the stack:

```text
eligibility
  -> contribution taxonomy
  -> validation
  -> value rubric
  -> cadence
  -> contribution log
  -> rights
  -> rewards
  -> governance
  -> capture monitoring
```

If any layer silently changes what counts as a legitimate record, the coupled
stack can fail even when each module looks reasonable in isolation.

### C3: Legitimacy As First-Class Design Variable

S7 gives C3 a formalization path:

```text
legitimacy = capability-relative fixed-point status under L
```

Plainly:

```text
a contribution record is legitimate for a use only if the declared process
lets participants inspect, contest, retain, and build on it under the stated
rules.
```

This does not replace the existing legitimacy conditions. It organizes them as
requirements on the operation `L`.

### C7: AI Cannot Supply Legitimacy

S7 also sharpens the AI guardrail. AI can help draft, critique, summarize, or
score local data `P`, but it is not itself `L`.

AI output becomes legitimate only through the same visible, contestable,
record-preserving process as any other contribution.

## Protocol Stack Consequences

The protocol stack can now be read as an institutional legitimacy pipeline:

```text
attemptable contribution
  -> typed contribution class
  -> reviewable local evidence
  -> validation and contestability
  -> accepted record
  -> rights / retained claim / governance consequences
```

The important engineering requirement is to preserve the `eta_P` trace:

```text
What local evidence entered?
Which rules were applied?
Who or what reviewed it?
What was accepted?
What was rejected or compressed?
What can be appealed?
Which rights attach?
```

Without that trace, the project may have records, but not legitimate records.

## Capability Loss And Dissent

S7 helps avoid a common governance mistake: treating consensus as erasure.

The legitimacy operation may filter noise, manipulation, or duplicate claims,
but it should not silently erase useful minority signals. Dissent can remain
legitimate even when it does not become the accepted result.

Architecture consequence:

```text
accepted record
  plus
visible rejected/contested/deferred residue
```

is often more legitimate than a clean record with the conflict hidden.

## Bounded Test Path

The first executable institutional test is:

```text
Legitimacy Threshold Workflow v0.1
```

Run one or more sample contribution workflows through:

1. submission,
2. contribution-class assignment,
3. review against rubric,
4. accepted / needs revision / rejected decision,
5. appeal or contestability path,
6. contribution-log entry,
7. retained-rights marker,
8. explicit `Lose[K]` notes for omitted or compressed material.

Measure:

- whether future contributors can reconstruct the decision;
- whether dissent remains visible enough to contest;
- whether the record supports a later reward or governance decision;
- whether AI assistance is disclosed and non-authoritative;
- whether capture/gaming attempts are surfaced by the workflow.

Success signal:

```text
participants can build on the accepted record without requiring private
founder context.
```

Failure signal:

```text
the record appears accepted only because authority, opacity, or missing
context filled the gap.
```

## Compressed Persona-Style Review

This is a compact review, not a historical 103-persona vote.

| lens | verdict |
| --- | --- |
| Institution designer | Strong fit: S7 names the missing transformation from contribution evidence to accepted institutional record. |
| Category theorist | Strong if `L`, `eta_P`, fixed points, and loss profile are explicit; weak if "legitimacy" stays rhetorical. |
| Governance theorist | Useful because contestability and retained record become structural, not optional polish. |
| Open-source maintainer | Practical if it reduces private maintainer context and produces inspectable contribution logs. |
| Legal/rights lens | Promising but must avoid premature legal or financial promises around retained claims. |
| AI governance lens | Strong guardrail: AI can produce local data, not legitimacy itself. |
| Attack-model lens | Useful because capture becomes a gluing obstruction or fixed-point failure, not a vibes problem. |
| Contributor lens | Valuable if adverse decisions remain visible, contestable, and exit-compatible. |
| Skeptic lens | Demote if the process just renames founder judgment as monadic legitimacy. |
| Protocol engineer | Strong next step: implement a contribution workflow that preserves the `eta_P` trace. |

Panel read:

```text
S7 strengthens C2 and C3, but only if it produces workflow artifacts that make
visibility, contestability, retained record, loss, and non-capture auditable.
```

## Guardrails

Do not claim:

- the repo has solved legitimacy;
- accepted records are always correct;
- AI review creates legitimacy;
- contribution logs are reward ledgers;
- formal language eliminates politics;
- founder-led decisions are decentralized because they are documented.

Do claim:

```text
S7 gives this repo a precise formalization path for studying how local
contribution evidence becomes buildable institutional record.
```

## Cross-Repo Role

The ecosystem mapping is:

| repo | role |
| --- | --- |
| `time-as-finality` | record/finality and legitimacy-monad theory. |
| `gu-formalization` | observer/readout stress tests and signed provenance separation. |
| `temporal-issuance` | source/projection/finality/loss effect discipline. |
| `architecture-of-legitimacy` | institutional protocol stack where legitimate records govern contribution, rights, and transitions. |
| `church-of-ai` | public coordination and plain-language wrapper. |

This repo is where S7 stops being only a categorical bridge and becomes a
testable contribution workflow.

