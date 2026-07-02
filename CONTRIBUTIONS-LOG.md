# Contributions Log

This log is the first prototype of the project's contribution memory.

It is not yet a reward ledger. It is a visible record of contribution, validation, and possible future claim.

## Schema

Field definitions follow [templates/contribution-log-schema.md](templates/contribution-log-schema.md).

| id | date | contributor | class | target | review_state | rubric_scores | rationale | loss_notes | links |
|---|---|---|---|---|---|---|---|---|---|
| CONTRIB-0001 | 2026-06-01 | Joe and Codex | synthesis | initial repo launch | accepted | not scored; founding record | Converted the research-discovery answers into the first public Architecture of Legitimacy research base. Founder-led founding record only; no reward system exists yet. | none recorded; not revised or narrowed | README.md; CLAIMS.md; PROTOCOL-STACK.md; LEGITIMACY-SCHEMA.md; TESTS.md; THREAT-MODEL.md |

## Review State Values

- `submitted`
- `triaged`
- `accepted`
- `needs_revision`
- `not_accepted`
- `contested`
- `adversarial`

## Open Questions

1. Should this log live in Markdown, structured data, or both?
2. Which fields are required before reward logic exists?
3. How should disputed attribution be recorded?
4. Should future-claim notes remain separate from `rationale` and `loss_notes`, and if so, how should they avoid premature legal or financial promises?
