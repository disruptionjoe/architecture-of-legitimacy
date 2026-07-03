# C2 Coupled-Stack Dependency Map

Date: 2026-07-03

Status: non-adopted research scaffold.

Purpose: prepare a bounded first pass for claim C2, which says the minimal serious object is a coupled protocol stack rather than a single ledger, token, rubric, or governance rule.

This artifact maps dependencies already visible in the repository. It does not change claim status, mark any test passed or failed, adopt policy, create reward logic, make a prior-art or novelty judgment, or decide any real contribution.

## Source Surfaces

- `CLAIMS.md` for the C2 proof burden.
- `PROTOCOL-STACK.md` for the provisional layer sequence.
- `LEGITIMACY-SCHEMA.md` for legitimacy conditions.
- `THREAT-MODEL.md` for attack surfaces and capture classes.
- `CONTRIBUTION-STANDARDS.md` and `CONTRIBUTING.md` for the current contribution workflow surface.
- `TESTS.md` for existing bounded checks.

## Working Question

If one layer is evaluated in isolation, what important legitimacy or capture risk becomes invisible?

The answer should help future work distinguish:

- a merely useful module,
- a module that needs adjacent protocol support,
- and a coupled dependency that belongs to the core C2 burden.

## Dependency Map

| focal layer | depends on | why the dependency matters | isolated-layer failure | next bounded check |
|---|---|---|---|---|
| Eligibility | contribution taxonomy, validation, AI role boundary | Open attemptability needs a path from attempted contribution to reviewable class without granting automatic status. | Openness becomes either noise tolerance or hidden gatekeeping. | Compare rejected, revised, and accepted synthetic attempts across contribution classes. |
| Contribution taxonomy | validation, value rubric, contribution log | Classes only matter if they route work into appropriate evidence and review expectations. | Taxonomy becomes labels with no operational consequence. | Test whether the same sample receives different review needs by class. |
| Validation | taxonomy, evidence minimum, cadence, contestability | A contribution can count only if reviewers can see the target, evidence, rationale, and route for challenge. | Validation becomes founder intuition or checklist theater. | Run one synthetic adverse decision with explicit rationale and revision path. |
| Value rubric | validation, legitimacy schema, threat model | Scoring should surface disagreement while staying inspectable and resistant to gaming. | Rubric scores look precise while hiding subjective authority or attack incentives. | Add failure probes for each rubric dimension before any scoring policy changes. |
| Cadence | validation, contribution log, contestability | Timing shapes fairness: too fast hides judgment, too slow erodes participant trust. | Review delay or urgency becomes an untracked governance power. | Compare rolling triage against batch review for one synthetic substantive contribution. |
| Contribution log | validation, value rubric, rights, loss notes | The log preserves why a contribution entered the record and what was compressed, deferred, or contested. | A ledger records attribution but loses the legitimacy trace. | Check whether future readers can reconstruct a synthetic decision without private context. |
| Rights | contribution log, legitimacy conditions, governance phase | Voice, exit, appeal, and retained-record claims require a stable contribution record and named authority. | Rights language becomes aspirational or reward-adjacent without enforceable meaning. | Separate retained record, retained value, appeal, and exit questions before adoption. |
| Rewards | value rubric, rights, threat model, capture monitoring | Rewards increase the prize for gaming and need legitimacy, review, and attack constraints first. | Reward logic intensifies capture before the project can detect or contest it. | Keep reward readiness gated until attack-profitability and rights questions are reviewed. |
| Governance | cadence, rights, contribution log, capture monitoring | Founder-led decisions need visible limits, transition triggers, and records of contested judgment. | Progressive decentralization remains theater or becomes premature transfer. | Map each founder power to evidence needed before transfer. |
| Capture monitoring | threat model, value rubric, rewards, governance | Capture risk changes as value, reputation, and governance power accumulate. | The system treats early trust as proof that later incentives are safe. | Tie attack-profitability variables to concrete protocol surfaces. |

## Coupling Signals

A dependency is probably C2-relevant when breaking it would make the system:

- record work without preserving the reasoning path;
- score contributions without visible contestability;
- grant rights without a stable record of accepted work;
- create rewards before attack incentives are understood;
- decentralize authority without naming what power moved;
- or rely on private founder context where a future contributor needs public rationale.

## Non-Adoption Boundary

This map is a scaffold for review. It does not:

- change the C2 claim status;
- add or remove any protocol layer;
- mark any test passed, failed, or partially passed;
- adopt review cadence, contributor rights, reward mechanisms, governance transitions, sanctions, or disclosure rules;
- choose a source packet, neighboring system, novelty position, or prior-art collision result;
- accept, reject, score, or add a real contribution.

## Review Questions

1. Which dependencies are merely convenient, and which are required for legitimacy?
2. Which isolated-layer failures already have a bounded test artifact?
3. Which failures need a new synthetic fixture before real contribution review?
4. Which dependencies become stronger only when rewards or governance power have material value?
5. What evidence would justify narrowing, weakening, or demoting C2?
