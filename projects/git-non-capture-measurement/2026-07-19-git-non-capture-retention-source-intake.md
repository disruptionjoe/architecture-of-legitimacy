# Git Non-Capture Retention Source-Intake Gate

Status: source-intake gate, not a measurement verdict.

Lane: Lane 1, `LEGITIMACY-FEASIBILITY`.

Protocol: [2026-07-18 measurement protocol skeleton](2026-07-18-git-non-capture-measurement-protocol.md).

Threshold gate: [2026-07-19 observable thresholds](2026-07-19-git-non-capture-observable-thresholds.md).

Prior application: [2026-07-19 time-slice threshold application](2026-07-19-git-non-capture-time-slice-threshold-application.md).

Defined at: `2026-07-19T10:39:21-05:00`.

Definition base head: `bb0628d6ff3111ea699d7e9289b11502b19c95af`.

## Scope

This gate defines how a later pass may admit `OBS-3 retained_object_graph`
evidence for the git Non-Capture measurement.

It does not perform a public-fork search, inspect private repository settings,
inspect branch protection, inspect permissions, inspect issues or pull
requests, contact contributors, open issues or pull requests, use non-GitHub
external sources, or query any source that requires credentials not already
available for ordinary GitHub versioning.

It does not issue a capture-cost direction, K1 implication, legitimacy verdict,
governance change, policy adoption, public-posture change, or claim-status
change.

## Admissibility Stops Checked

| stop | pass status | note |
|---|---|---|
| Charter, Lane, governance, claim, or public-posture change required | not triggered | This artifact defines a source-admission gate inside the measurement project. |
| Adverse measurement repair or suppression | not triggered | No adverse or favorable K1 verdict is issued. |
| Private settings or credentials needed as evidence | excluded | Branch protection, permissions, admin controls, and nonpublic clones remain unmeasured. |
| Contributor contact, issue opening, or external participation | excluded | No contact, solicitation, issue, pull request, or non-GitHub external action. |
| Other-repository substrate quantities | excluded | The only admissible target is this repository's git object graph. |
| Proposal, automation signal, or orchestration brief as authority | excluded | The charter, Lane manifest, and measurement artifacts govern. |

## Source Families

| source family | admitted use | maximum level before object verification | notes |
|---|---|---|---|
| Canonical repository tracked artifact | Records a known old head or expected object identity. | `KPH-1 tracked_self_anchor` | This cannot by itself become `OBS-3` because the source is self-anchored. |
| Canonical repository named ref | Records that a public branch, tag, or release ref pointed to an object. | `KPH-2 named_public_ref` | This remains under canonical repository administration unless independently retained. |
| Public GitHub fork or mirror | May establish external retention if the old commit and needed ancestry/tree data are reachable from that source. | `OBS-3 retained_object_graph` only after verification | Fork count, star count, or watcher metadata without the object identity is at most `OBS-1`. |
| Public source naming an old object identity | May establish that an outside source knew the object identity. | `OBS-2 object_identity_reference` | Naming a commit is not enough to prove retained object graph availability. |
| Non-GitHub public archive, mirror, clone, or citation | Out of scope for this run. | not admitted here | A later run must explicitly admit the source family before using it. |
| Private clone, local cache, terminal history, or agent memory | Excluded. | none | These sources cannot support a public observer-retention row. |

## Required Row Fields

A later source pass may label a row `OBS-3 retained_object_graph` only when it
records all of these fields:

| field | requirement |
|---|---|
| `old_object_identity` | Commit, tree, blob, or diff identity from a prior time slice or result-bearing artifact. |
| `retaining_source` | Public source that is not the canonical repository's own current branch history. |
| `retrieval_method` | Reproducible read-only method used to observe the object graph. |
| `source_independence_label` | Whether the retaining source is independent of founder/governed repository administration. |
| `object_graph_coverage` | Whether the source exposes enough ancestry, tree, blob, or diff data to verify the relevant rewrite, deletion, or suppression path. |
| `retention_scope` | Which prior slice, artifact, or object identity is actually retained. |
| `founder_discretion_label` | Founder or governance inputs that still control recognition, canonical routing, publication, or acceptance. |
| `threshold_result` | Strongest threshold reached: `OBS-0`, `OBS-1`, `OBS-2`, or `OBS-3`. |

## Non-Counting Evidence

The following evidence may justify a follow-up pass but must not be counted as
`OBS-3`:

- a public fork count, star count, watcher count, or repository metadata hint
  without the old object identity;
- a canonical branch, tag, release, or tracked artifact controlled by the same
  repository administration;
- a public page that names an old commit but does not expose enough object graph
  data to verify the action path;
- a local clone, local cache, terminal output, memory, or unpublished note; or
- a source whose use would require private credentials, contact, outreach, or
  non-GitHub external action.

## Direction Rule

`OBS-3 retained_object_graph` can support an observer-retention cost row only
for the specific old object graph it verifies. It does not prove governance
acceptance, ordinary public salience, adverse-artifact discoverability, or
capture resistance independent of recognition routing.

If the best retained evidence is `OBS-0`, `OBS-1`, or `OBS-2`, the safe finding
remains that git may expose self-anchored records, while independent observer
retention is not yet measured.

## Current Measurement Position

No `OBS-3` evidence is admitted by this artifact.

The current `capture_cost_direction` remains `unknown`, and `K1_implication`
remains `not_evaluated`.

## Next Measurement Need

A later source pass can use this gate to test one or more old object identities
from the charter and measurement slices against public retained-object evidence.
Until that pass admits an external retained object graph, the previous
time-slice application remains the current result: tracked self-anchors are
useful detectability evidence, not independent observer-retention evidence.
