# Contribution Log Schema

Field schema for each entry in [CONTRIBUTIONS-LOG.md](../CONTRIBUTIONS-LOG.md). Review states and rubric dimensions follow [CONTRIBUTION-STANDARDS.md](../CONTRIBUTION-STANDARDS.md).

| field | meaning |
|---|---|
| `id` | `CONTRIB-NNNN` |
| `date` | YYYY-MM-DD |
| `contributor` | name or pseudonym (note if agent-assisted) |
| `class` | research / formalization / protocol design / review / synthesis / implementation / maintenance |
| `target` | file(s) or claim(s) addressed |
| `review_state` | submitted / triaged / accepted / needs_revision / not_accepted / contested / adversarial |
| `rubric_scores` | clarity, rigor, relevance, novelty, legitimacy, capture_resistance, coordination_value (0-3 each) |
| `rationale` | short reviewer rationale |
| `loss_notes` | useful value lost, deferred, compressed, or not yet accepted into the project record |
| `links` | issue / PR / source links |

Scores are a tool for discussion, not automatic reward (per CONTRIBUTION-STANDARDS).

`loss_notes` should be used when a contribution is revised, narrowed, or not accepted as-is. It should not create a reward promise or future legal/financial claim; it is a reconstruction aid for legitimacy, contestability, and later synthesis.
