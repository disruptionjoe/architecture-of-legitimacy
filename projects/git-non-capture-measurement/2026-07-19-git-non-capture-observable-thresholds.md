# Git Non-Capture Observable Thresholds

Status: observable-threshold gate, not a measurement verdict.

Lane: Lane 1, `LEGITIMACY-FEASIBILITY`.

Protocol: [2026-07-18 measurement protocol skeleton](2026-07-18-git-non-capture-measurement-protocol.md).

Source pass: [2026-07-19 local data pass](2026-07-19-git-non-capture-local-data-pass.md).

Prior comparison: [2026-07-19 action-set comparison](2026-07-19-git-non-capture-action-set-comparison.md).

Defined at: `2026-07-19T08:39:30-05:00`.

Definition head: `7d51fe63f0cd0cc8b314e3fe47eb345697f50582`.

## Scope

This gate defines the observable evidence levels a later result-bearing pass
must use before moving `capture_cost_direction` away from `unknown`.

It uses only tracked repository surfaces and local git facts already admitted by
the protocol. It does not inspect private repository settings, GitHub API state,
branch protection, permissions, issues, pull requests, or external publication
state.

It does not issue a capture-cost direction, K1 implication, governance change,
policy adoption, public-posture change, or legitimacy verdict.

## Admissibility Stops Checked

| stop | pass status | note |
|---|---|---|
| Charter, Lane, governance, claim, or public-posture change required | not triggered | This gate adds only a measurement artifact and navigation entries. |
| Adverse measurement repair or suppression | not triggered | No adverse or favorable result is issued. |
| Private settings or credentials needed as evidence | excluded | Branch protection, permissions, and admin controls remain unmeasured. |
| Contributor contact, issue opening, or external participation | excluded | No contact, solicitation, issue, pull request, or non-GitHub external action. |
| Other-repository substrate quantities | excluded | Only this repository's git substrate is in scope. |
| Proposal, automation signal, or orchestration brief as authority | excluded | The charter, Lane manifest, and prior measurement artifacts govern. |

## Threshold Model

Each later measurement row should label the strongest observed level reached for
the relevant path. A higher level can include lower-level evidence, but lower
levels must not be counted as if they prove the higher one.

### 1. Known-Public-Head Evidence

Question: can a later observer distinguish a rewrite from ordinary branch
movement by comparing against an old public object identity?

| level | evidence | what it can support | what it cannot support |
|---|---|---|---|
| `KPH-0 local_memory_only` | The old head is known only from the actor's unstaged notes, local terminal history, or memory. | No result-bearing rewrite threshold. | Any claim that the public could detect the rewrite. |
| `KPH-1 tracked_self_anchor` | The old head is recorded in a tracked artifact reachable from the public history, such as this measurement directory. | Git-history detectability if the tracked history remains reachable. | Observer independence or prevention of authorized ref movement. |
| `KPH-2 named_public_ref` | A public branch, tag, release ref, or comparable named git/GitHub ref pointed to the old object before the alleged rewrite. | Stronger public reference-point evidence for rewrite comparison. | Resistance if the same authority can delete or retarget the ref. |
| `KPH-3 independent_retained_anchor` | A public fork, clone, archive, mirror, citation, or other independent source retains or cites the old object graph. | Observer-side retention outside the canonical repository's ref choice. | Governance acceptance or public salience of the retained object. |

Minimum for a result-bearing rewrite row: `KPH-1`. Minimum for attributing a
rewrite cost to independent observer retention: `KPH-3`.

### 2. Independent Observer Availability

Question: is an old object graph actually retained outside founder-controlled
repository administration?

| level | evidence | what it can support | what it cannot support |
|---|---|---|---|
| `OBS-0 none_observed` | No public retained-copy evidence is present in admitted sources. | Observer availability remains unmeasured. | Any increased-cost finding based on observers. |
| `OBS-1 public_metadata_hint` | Public metadata suggests forks, stars, watchers, or references, but no old object identity is tied to a retained copy. | A search target for a later governed pass. | Retention of the relevant old object graph. |
| `OBS-2 object_identity_reference` | A public source outside this repository names the old commit, tree, blob, or diff identity. | Detectability outside founder memory. | Full object retention or ability to reconstruct all suppressed context. |
| `OBS-3 retained_object_graph` | A public fork, mirror, archive, or clone exposes the old object graph or enough ancestry to verify the relevant rewrite or deletion. | Independent retention cost for history rewrite or suppression. | Recognition, acceptance, or legitimacy of the retained record. |

Minimum for using observer availability as a capture-cost source: `OBS-3`.
`OBS-1` and `OBS-2` can justify follow-up, but they do not by themselves move
`capture_cost_direction`.

### 3. Adverse-Artifact Navigation State

Question: if an adverse artifact is committed, can an ordinary public reader
find it through expected repository entry points?

| level | evidence | what it can support | what it cannot support |
|---|---|---|---|
| `NAV-0 no_adverse_artifact` | No committed adverse artifact exists in the admitted scope. | No navigation result. | Any claim about suppression or discoverability. |
| `NAV-1 committed_only` | The artifact is committed but not linked from the measurement project, agenda, tests, top-level README, or other ordinary map. | Git record preservation only. | Ordinary public discoverability. |
| `NAV-2 project_indexed` | The artifact is linked from its local project README or adjacent project map. | Local project discoverability. | Repository-level salience. |
| `NAV-3 repo_indexed` | The artifact is linked from at least one repo-level navigation surface such as `RESEARCH-AGENDA.md`, `TESTS.md`, or `projects/README.md`. | Ordinary repository navigation evidence. | Acceptance, favorable treatment, or external publication. |
| `NAV-4 adverse_status_preserved` | The link and surrounding text preserve the adverse or result-bearing status rather than burying it under neutral framing. | Stronger recognition-path evidence. | Governance acceptance beyond the stated artifact status. |

Minimum for measuring adverse-artifact public navigation: `NAV-3`. Minimum for
measuring whether adverse status remained visible rather than merely retained:
`NAV-4`.

### 4. Recognition-Routing Diff

Question: did tracked entry points reroute attention away from a retained
record, interpretation, or adverse status while leaving history intact?

| level | evidence | what it can support | what it cannot support |
|---|---|---|---|
| `RRD-0 no_entrypoint_diff` | No tracked entry-point diff changes the artifact's link, label, order, status, or summary. | No recognition-routing result. | Any claim of rerouting. |
| `RRD-1 mechanical_repair` | A diff fixes a broken link, typo, stale path, or index omission without changing status, salience, or interpretation. | Maintenance classification. | Capture or suppression inference. |
| `RRD-2 salience_shift` | A diff changes link presence, order, summary, status wording, or read-order position in a way that changes ordinary attention. | Recognition-routing evidence. | Whether the shift is benign or capture-motivated. |
| `RRD-3 adverse_status_shift` | A diff removes, softens, relabels, or counter-frames an adverse status while preserving the underlying record. | Strong evidence that recognition is governance-mediated. | Git-substrate resistance independent of governance choice. |
| `RRD-4 external_publication_shift` | A governed, authorized public-facing surface outside normal repo navigation changes the record's recognition. | Public-salience evidence if admitted by a later governed pass. | Repo-local git mechanism by itself. |

Minimum for a recognition-routing measurement row: `RRD-2`. `RRD-3` should be
classified as founder/governance-mediated unless a later pass names an
independent git-substrate mechanism that made the rerouting harder.

## Direction Gate For Later Passes

A later result-bearing pass may move `capture_cost_direction` only if all of
the following are true:

1. It names the action path being measured: rewrite, suppression, or
   recognition rerouting.
2. It names the strongest observed threshold level for the relevant evidence
   family.
3. It separates the cost source into git mechanics, observer availability,
   platform settings, and founder/governance choice.
4. It compares at least two time slices where legitimacy or participation proxy
   changed, rather than treating record mass alone as legitimacy.
5. It states whether the measured cost is prevention, detection, retention, or
   recognition cost.

If the strongest observed source is `KPH-1`, `NAV-3`, or `RRD-2` without
`OBS-3`, the safe classification is not "git raises capture cost." It is
"git preserves or exposes a record while recognition and canonical routing
remain governance-mediated."

If an apparent increase depends on branch protections, deletion permissions,
maintainer access, release controls, or platform retention guarantees, the row
must remain platform-setting or founder/governance mediated unless those
settings are admitted by a later governed source pass.

## Current Application To Known Artifacts

| path | current strongest threshold | reason | consequence |
|---|---|---|---|
| Rewrite or replace `origin/main` after a known public head | `KPH-1 tracked_self_anchor`; `OBS-0 none_observed` | Prior heads are recorded in tracked measurement artifacts, but no independent retained object graph has been admitted. | Rewrite detectability is locally defined; observer-retention cost is unmeasured. |
| Suppress or de-emphasize an adverse committed artifact | `NAV-0 no_adverse_artifact` | No adverse measurement artifact exists in the admitted scope. | Suppression cannot be measured yet. |
| Redirect public recognition while preserving history | `RRD-0 no_entrypoint_diff` for an adverse artifact | No adverse result exists, so no adverse-recognition diff can exist. | Recognition-routing remains a defined future measurement path. |

Therefore `capture_cost_direction` remains `unknown`, and `K1_implication`
remains `not_evaluated`.

## Next Measurement Need

The next result-bearing pass should apply this gate to a concrete time-slice
comparison. It should not add governance mechanisms, change public posture, or
try to make the result favorable. If the strongest observed evidence remains
tracked self-anchoring with no independent retained object graph, the pass
should say that directly rather than crediting founder-controlled publication
or navigation to the git substrate.
