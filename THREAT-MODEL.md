# Threat Model

Any system that allocates value attracts attack.

This threat model is early. Its job is to prevent "capture resistance" from becoming decorative language.

## Threat Classes

### Economic Capture

An actor uses money, rewards, employment, bribery, sponsorship, or market power to steer outcomes.

Examples:

- paying contributors to support a governance change,
- buying influence over reviewers,
- sponsoring work that shifts project priorities,
- accumulating future reward claims through low-value volume.

Questions:

- What can money buy in this system?
- Which powers should not be transferable?
- How visible are economic relationships?

### Epistemic Capture

An actor manipulates the judgment layer.

Examples:

- gaming rubrics,
- flooding the repo with plausible but low-value contributions,
- shaping definitions so their preferred work scores well,
- using AI-generated volume to create false consensus,
- laundering ideology or self-interest through technical language.

Questions:

- Which rubrics are easiest to game?
- How does the project detect synthetic consensus?
- What kinds of critique should receive high value?

### Governance Capture

An actor changes the rules to preserve or increase control.

Examples:

- founder entrenchment,
- contributor cartel formation,
- procedural changes that make appeals impossible,
- reputation systems that lock early participants into permanent dominance,
- emergency powers that never expire.

Questions:

- Which powers exist today?
- Which powers can change the rules?
- Which rules protect the rule-change process?

## Cross-Cutting Threats

### Founder Theater

The project says it will decentralize but never creates measurable transition conditions.

Mitigation candidates:

- named founder powers,
- public decision log,
- transition milestones,
- power-specific decentralization rather than vague decentralization,
- external review of milestones.

### Reward Gaming

Contributors optimize for visible scoring rather than real value.

Mitigation candidates:

- multi-dimensional rubrics,
- delayed reward,
- qualitative review,
- anti-volume weighting,
- adversarial review rewards,
- reward caps during early phases.

### Legitimacy Drift

The project remains formally compliant while participants increasingly experience it as unfair or captured.

Mitigation candidates:

- participant feedback,
- appeal metrics,
- exit interviews,
- legitimacy review cycles,
- rule-change proposals based on observed harm.

## Attack Surface Table

| surface | attacker goal | likely attack | early mitigation |
|---|---|---|---|
| Contribution intake | create noise or false contribution volume | spam, AI-generated bulk, duplicate submissions | contribution templates, triage, rate limits if needed |
| Value rubric | make preferred work score highly | rubric gaming, definition capture | rubric tests, red-team review, version history |
| Review cadence | exploit delay or urgency | pressure campaigns, rushed decisions | scheduled review windows, rationale requirements |
| Contribution log | inflate attribution | duplicate claims, unverifiable work | artifact links, reviewer notes, dispute status |
| Governance proposals | change rules for advantage | procedural capture, coalition voting | founder-phase constraints, transition criteria |
| Reward logic | extract value | sybil contribution, cartel review | delayed reward readiness, no automatic high-value payouts |
| AI support | launder bias | prompt shaping, synthetic consensus | AI-use disclosure, human contestability |

## Research Need

The project needs attack-profitability equations for each major threat class.

At minimum:

```text
Expected attack value = probability_of_success * extractable_value
Expected attack cost = direct_cost + mitigation_cost + expected_sanction + reputation_loss
Attack attractive when expected attack value > expected attack cost
```

The useful research question is not "can attacks happen?" They can.

The useful question is:

> Which protocol choices make attacks less profitable as the project becomes more valuable?

