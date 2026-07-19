# Git Non-Capture Time-Slice Threshold Application

Status: threshold application, not a K1 verdict.

Lane: Lane 1, `LEGITIMACY-FEASIBILITY`.

Protocol: [2026-07-18 measurement protocol skeleton](2026-07-18-git-non-capture-measurement-protocol.md).

Source pass: [2026-07-19 local data pass](2026-07-19-git-non-capture-local-data-pass.md).

Prior comparison: [2026-07-19 action-set comparison](2026-07-19-git-non-capture-action-set-comparison.md).

Threshold gate: [2026-07-19 observable thresholds](2026-07-19-git-non-capture-observable-thresholds.md).

Applied at: `2026-07-19T09:41:13-05:00`.

Application head: `5e1c4bd30faf70cff66df25cb74d65a368fe04b6`.

## Scope

This pass applies the existing threshold gate to concrete repository time
slices. It uses only local git history and tracked public repository surfaces.

It does not inspect private repository settings, GitHub API state, branch
protection, permissions, issues, pull requests, contributor contact, external
publication state, or any other repository's substrate quantities.

It does not issue a legitimacy verdict, declare K1 fired or cleared, change the
charter or Lane manifest, adopt capture mitigations, move public posture, or
claim that the North Star holds.

## Admissibility Stops Checked

| stop | pass status | note |
|---|---|---|
| Charter, Lane, governance, claim, or public-posture change required | not triggered | This artifact applies an already-defined evidence gate inside the measurement project. |
| Adverse measurement repair or suppression | not triggered | No adverse or favorable K1 verdict is issued. |
| Private settings or credentials needed as evidence | excluded | Branch protection, permissions, and admin controls remain unmeasured. |
| Contributor contact, issue opening, or external participation | excluded | No contact, solicitation, issue, pull request, or non-GitHub external action. |
| Other-repository substrate quantities | excluded | Only this repository's git substrate is in scope. |
| Proposal, automation signal, or orchestration brief as authority | excluded | The charter, Lane manifest, and prior measurement artifacts govern. |

## Time-Slice Inputs

| slice | commit | time | commits | tracked paths | measurement artifacts | legitimacy or participation proxy changed | founder-discretion risk |
|---|---|---|---:|---:|---:|---|---|
| Pre-charter Lane contract | `d7ebc04039795e1deb21ef6382983a6eaa224fac` | `2026-07-16T19:04:43-05:00` | 199 | 188 | 0 | First-class Lane contract installed before charter ratification; no measurement project artifacts. | Lane framing was founder-approved repo work. |
| Charter and Lane revision 2 | `ef35c7f4d33514cdc41d962b6673c546267d26b9` | `2026-07-16T20:34:52-05:00` | 200 | 189 | 0 | Ratified charter and Lane revision 2 created the first explicit falsifier. | Charter ratification is Joe/founder authority, not a git property. |
| First measurement scaffold | `8f1cdb9ce9661b543434ed225ca8b094dfb31332` | `2026-07-18T23:43:31-05:00` | 203 | 192 | 2 | Measurement protocol and project map made K1 instrumentation navigable. | Measurement preparation is authored and indexed under founder-governed repository control. |
| Observable threshold gate | `5e1c4bd30faf70cff66df25cb74d65a368fe04b6` | `2026-07-19T08:42:40-05:00` | 206 | 195 | 5 | Local data, action comparison, and threshold gate made known-head and navigation criteria explicit. | Canonical branch, README/agenda/test links, acceptance, and public emphasis remain governance-mediated. |

Visible author identities across the admitted local history: `1`.

## Threshold Application

| capture path | strongest current threshold | observed time-slice change | cost source classification | current result |
|---|---|---|---|---|
| Rewrite or replace `origin/main` after a known public head | `KPH-1 tracked_self_anchor`; `OBS-0 none_observed` | Later measurement artifacts record prior heads in tracked history, but no admitted source shows an independent retained object graph. | Git supplies hash and ancestry detection anchors. Canonical ref control, public explanation, and retention outside this repository remain platform or governance mediated. | Detection evidence exists inside the repository; observer-retention cost is unmeasured. |
| Suppress or de-emphasize an adverse committed artifact | `NAV-0 no_adverse_artifact` | No adverse result-bearing artifact exists in the admitted scope. | No suppression row can be measured yet. | No navigation direction can be issued. |
| Redirect public recognition while preserving history | `RRD-0 no_entrypoint_diff` for an adverse artifact | Agenda, tests, and project README links added measurement artifacts, but there is no adverse artifact whose status was rerouted. | Existing navigation is founder/governance authored. Git records diffs but does not assign salience or acceptance. | No recognition-routing direction can be issued. |

## Time-Slice Finding

The legitimacy proxy changed in the admitted slices: charter ratification, Lane
revision 2, and measurement artifacts made the first falsifier more explicit and
more navigable.

The participation proxy did not materially change in the admitted local scope:
the history still shows one visible author identity and no admitted independent
observer-retention evidence.

The strongest current rewrite evidence is self-anchored detectability inside
tracked history. That is useful, but it is not an independent retention source
and it is not prevention. The strongest current adverse-navigation and
recognition-routing evidence remains absent because there is not yet an adverse
measurement artifact to navigate or reroute.

Therefore the current scope does not support moving `capture_cost_direction`
away from `unknown`.

## Output Fields

| field | value |
|---|---|
| `measurement_scope` | Local git history and tracked public repository surfaces through application head `5e1c4bd`. |
| `substrate_mechanism` | Commit hashes, parent ancestry, tracked self-anchors, and git diffs make some later rewrites or reroutes detectable if the relevant history remains reachable. |
| `legitimacy_participation_delta` | Legitimacy instrumentation increased through charter ratification and measurement artifacts; participation evidence did not increase in admitted local history. |
| `founder_discretion_label` | High: canonical branch, public framing, artifact indexing, adverse-finding acceptance, and external publication remain founder/governance controlled or unmeasured. |
| `threshold_application` | `KPH-1` with `OBS-0` for rewrite; `NAV-0` for adverse suppression; `RRD-0` for adverse recognition routing. |
| `capture_cost_direction` | `unknown` |
| `K1_implication` | `not_evaluated` |

## Next Measurement Need

A result-bearing pass still needs at least one of:

- admitted `OBS-3 retained_object_graph` evidence for an old object graph;
- an actual committed adverse artifact with ordinary navigation evidence; or
- a recognition-routing diff against an adverse or result-bearing artifact.

Without one of those, the honest finding remains: current git evidence preserves
and exposes records better than memory alone, but the measured resistance is not
yet attributable to git substrate capture cost independent of founder-governed
recognition and canonical routing.
