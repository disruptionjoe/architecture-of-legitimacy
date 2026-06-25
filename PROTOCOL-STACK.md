# Protocol Stack

The project studies a minimally coherent stack for legitimate collaborative value creation.

The stack is provisional. It exists so contributors can critique, refine, test, and replace components without losing sight of the coupled design problem.

## Why A Stack

No single module appears sufficient.

- A contribution ledger can record work without judging value.
- A value rubric can score work without preserving legitimacy.
- A reward mechanism can intensify gaming if validation is weak.
- Open participation can invite noise and attack without filtering.
- Founder control can move quickly while quietly becoming permanent.
- Decentralization can distribute power without preventing capture.

The working hypothesis is that these pieces must be designed together.

The [S7 Legitimacy Monad Crosswalk](explorations/legitimacy-monad-s7-crosswalk-2026-06-25.md) gives one formal reading of this stack:

```text
raw contribution evidence
  -> legitimacy operation
  -> accepted record with explicit loss, contestability, and rights metadata
```

That reading is useful only if the protocol preserves the trace from local evidence to accepted record. If the trace is missing, the stack may create records, but not legitimate records.

## Layer 1: Eligibility

Eligibility asks who can attempt to contribute and what kinds of contributions can enter the system.

Initial principle:

Anyone may attempt to contribute if they follow the project's rules of participation. Openness means open attemptability, not automatic acceptance, status, voting power, or reward.

Open questions:

- What behavior should make a contributor temporarily or permanently ineligible?
- Should anonymous or pseudonymous contributions be accepted?
- How should agent-generated contributions be labeled?
- How should conflicts of interest be disclosed?

## Layer 2: Contribution Taxonomy

Not all contributions should be judged by one rubric.

Initial contribution classes:

- `research`: prior art, citations, literature maps, conceptual comparisons.
- `formalization`: models, definitions, payoff equations, schemas.
- `protocol design`: rules, workflows, governance proposals, failure modes.
- `implementation`: code, automation, templates, issue workflows.
- `review`: critique, red-team analysis, rubric testing, adversarial assessment.
- `synthesis`: integrating multiple contributions into clearer project state.
- `maintenance`: cleanup, link fixes, triage, contributor support.

Open questions:

- Which classes are missing?
- Which classes should be reward-eligible?
- Which classes are necessary but not sufficient for reward?

## Layer 3: Validation

Validation asks whether a contribution should count.

Initial validation criteria:

- relevance to an open question,
- traceable reasoning or source support,
- clear change to project state,
- inspectability by future contributors,
- no hidden dependency on private founder context,
- and no obvious manipulation of the review process.

Validation should distinguish:

- `accepted`: useful enough to enter the project record,
- `needs revision`: promising but incomplete,
- `not accepted`: not useful for the project as submitted,
- `harmful or adversarial`: manipulation, spam, plagiarism, or bad-faith behavior.

## Layer 4: Value Rubrics

Value is context-sensitive, so the first rubrics should be simple and contestable.

Candidate dimensions:

- `clarity`: does it make the project easier to understand or use?
- `truth-seeking`: does it reduce error, overclaim, or confusion?
- `formal rigor`: does it make a claim more testable or precise?
- `coordination value`: does it help contributors know what to do next?
- `novelty`: does it surface a non-obvious path or distinction?
- `legitimacy value`: does it improve voice, exit, contestability, transparency, or trust?
- `capture resistance`: does it reduce attack profitability or governance drift?

The first rubrics should not pretend to be final. Their job is to make evaluation discussable.

## Layer 5: Cadence

Cadence asks when and how contributions are reviewed.

Initial candidate:

- lightweight rolling triage for simple contributions,
- scheduled review batches for substantive contributions,
- public monthly synthesis of accepted contributions and open disputes,
- explicit review notes for rejected or contested work.

Open questions:

- What cadence is fast enough to keep contributors engaged?
- What cadence is slow enough to avoid arbitrary judgment?
- Which decisions require batch review rather than immediate founder judgment?

## Layer 6: Contribution Log

The contribution log is the first prototype of memory and attribution.

It should record:

- contributor identifier,
- contribution type,
- date,
- artifact link,
- validation status,
- value notes,
- reviewer or validation path,
- and any retained-value or future-claim marker.

The log is not yet a full reward ledger. It is the minimum inspectable substrate for one.

S7 implication:

```text
The log should preserve the eta_P trace: submission evidence, validation path,
accepted content, rejected or compressed residue, reviewer/rationale, appeal
status, and any rights marker.
```

## Layer 7: Rights

Accepted contributors may need more than thanks.

Candidate rights:

- `visibility`: accepted contributions remain visible in the project record.
- `voice`: contributors can contest evaluations or propose rule changes.
- `exit`: contributors can leave without erasing accepted contribution history.
- `retained claim`: accepted work may create a future claim if the project later creates rewards.
- `appeal`: contributors can ask for a review of a disputed classification.

Open questions:

- Which rights attach to all participation?
- Which rights attach only to accepted contributions?
- Which rights attach only after repeated or high-value contribution?

## Layer 8: Rewards

Rewards are deliberately not first.

The project should research reward logic before issuing strong reward promises. Possible future mechanisms include:

- symbolic credit,
- priority influence in review or proposal processes,
- retroactive reward pools,
- inflation-like issuance,
- revenue-linked distribution,
- governance weight,
- or retained-value rights in future project entities.

Any reward mechanism must be studied against legitimacy and capture risk.

## Layer 9: Governance

Governance starts founder-led and should say so plainly.

Initial mode:

The founder may make final decisions while the project is young, but decisions should be documented, contestable, and increasingly constrained by public rules.

The research problem:

What milestones justify transferring specific powers from founder judgment to more distributed processes?

## Layer 10: Capture Monitoring

As value accumulates, the system needs attack-surface monitoring.

Initial capture categories:

- economic capture,
- epistemic capture,
- governance capture,
- reputation capture,
- contributor cartel formation,
- AI-rubric gaming,
- and founder entrenchment.

Capture monitoring should eventually connect to explicit attack-profitability models.
