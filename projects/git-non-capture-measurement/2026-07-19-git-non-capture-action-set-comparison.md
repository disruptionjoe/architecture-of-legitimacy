# Git Non-Capture Action-Set Comparison

Status: action-set comparison, not a measurement verdict.

Lane: Lane 1, `LEGITIMACY-FEASIBILITY`.

Protocol: [2026-07-18 measurement protocol skeleton](2026-07-18-git-non-capture-measurement-protocol.md).

Source pass: [2026-07-19 local data pass](2026-07-19-git-non-capture-local-data-pass.md).

Compared at: `2026-07-19T07:40:50-05:00`.

Comparison head: `5e5b88fbb29aa7eb108e3f27ca528032df339d05`.

## Scope

This comparison uses only local git facts and tracked public repository
surfaces. It does not use private repository settings, GitHub API state, branch
protection configuration, contributor contact, issues, pull requests, or
external publication state.

It defines candidate action sets for later measurement. It does not issue a
capture-cost direction, K1 implication, governance change, policy adoption,
public-posture change, or legitimacy verdict.

## Admissibility Stops Checked

| stop | pass status | note |
|---|---|---|
| Charter, Lane, governance, claim, or public-posture change required | not triggered | This artifact only compares action sets inside the measurement project and related indexes. |
| Adverse measurement repair or suppression | not triggered | No adverse or favorable result is issued. |
| Private settings or credentials needed as evidence | excluded | Branch protection, repository permissions, and admin controls remain unmeasured. |
| Contributor contact, issue opening, or external participation | excluded | No non-GitHub external action and no GitHub issue or pull request action. |
| Other-repository substrate quantities | excluded | Only this repository's git substrate is in scope. |
| Proposal, automation signal, or orchestration brief as authority | excluded | The prior run handoff selected the next bounded measurement need; the charter governs. |

## Action-Set Model

For this pass, a capture path is modeled as the minimum visible action set
needed to make a captured state stick in the public research surface. Each row
separates four sources of cost:

- git mechanics: hashes, parent ancestry, object retention, and diffs;
- public clone or fork availability: whether another observer already holds the
  old object graph;
- GitHub or platform settings: branch protection, permissions, deletion powers,
  and remote administration, all unmeasured here; and
- founder or governance choices: merge authority, README framing, acceptance,
  emphasis, and external-publication decisions.

The point is not to prove that git prevents capture. The point is to prevent a
later measurement from crediting founder discretion, platform settings, or
observer behavior to the git substrate.

## Source Snapshot

| field | observed value | source command | founder-discretion label |
|---|---|---|---|
| Current comparison head | `5e5b88fbb29aa7eb108e3f27ca528032df339d05` | `git rev-parse HEAD` | Git object identity is substrate-visible; canonical branch target is governance-controlled. |
| Current branch | `main` | `git branch --show-current` | Canonical branch naming and use are founder/governance controlled. |
| Upstream parity | `HEAD` and `origin/main` differed by `0 0` commits | `git rev-list --left-right --count HEAD...origin/main` | Public remote publication is visible; permissions and branch protections are not measured. |
| Total commits at comparison head | `204` | `git rev-list --count HEAD` | Commit count is record mass, not legitimacy or participation. |
| Prior known public head | `8f1cdb9ce9661b543434ed225ca8b094dfb31332` | Local data pass pre-pass head | Known hashes make later rewrites detectable only to observers who retain or know the old head. |
| Current measurement artifact count | `3` | Tracked files in this directory | More artifacts increase audit surface, not by themselves legitimacy or capture cost. |

## Capture Path Comparison

| capture path | target captured effect | minimum visible action set | git-substrate cost visible here | public clone or fork cost visible here | platform or settings cost visible here | founder/governance discretion | first-pass status |
|---|---|---|---|---|---|---|---|
| Rewrite or replace `origin/main` after a known public head | The canonical remote branch no longer contains the known prior history or adverse artifact. | Move the canonical ref by force-push, replacement branch, deletion and recreation, or repository migration; then make the new ref the public reference point. | Known commit hashes and parent ancestry make a rewrite detectable against retained heads such as `8f1cdb9` or `5e5b88f`. Git does not stop an authorized ref move by itself. | A clone or fork made before the rewrite could preserve the old object graph, but this local pass has no evidence of actual independent clones or forks. | Branch protection, repository permissions, deletion powers, and GitHub retention behavior are unmeasured. | High: canonical remote control, branch policy, and public explanation remain founder/governance or platform-admin dependent. | `unknown`; git supplies detection anchors, not a measured prevention cost. |
| Suppress or de-emphasize an adverse committed artifact | An adverse finding exists in history but is removed from ordinary navigation, omitted from indexes, or framed as non-load-bearing. | Commit the adverse artifact, then later delete it, unlink it from `README.md`, `RESEARCH-AGENDA.md`, `TESTS.md`, or project maps, or reframe it in later narrative. If the old commit is rewritten away, this collapses into the first path. | If the adverse artifact stays in reachable history, git preserves the add/delete and framing diffs. Git does not force indexes, README emphasis, or acceptance language to keep pointing at it. | Independent clones or forks could retain the artifact after deletion, but observer availability is unmeasured. | GitHub file history and search behavior may aid discovery, but this pass does not measure platform indexing or retention guarantees. | High: acceptance, linking, labels, rationale, and public emphasis are governance-controlled. | `unknown`; git can preserve a record while recognition remains governance-mediated. |
| Redirect public recognition while preserving underlying history | The history remains intact, but the public entry points direct attention to a different interpretation, priority, or claimed result. | Edit public entry points, indexes, claim summaries, project maps, or read orders so the retained record is technically present but no longer governs attention. | Git diffs reveal the recognition shift after the fact. Git does not assign public salience, acceptance, priority, or legitimacy. | Clones and forks preserve the old text if fetched earlier, but this pass has no observer-side evidence. | Platform rendering, search, and default branch display may affect salience, but those are unmeasured. | Very high: README framing, index order, claim wording, and external-publication choices are founder/governance controlled. | `unknown`; this path is likely recognition-mediated, not substrate-resolved, but no direction is measured here. |

## Preliminary Separation

This pass supports three separations for a later result-bearing measurement:

1. Git can make a capture move detectable when an observer knows or retains the
   old object identity. That is not the same as preventing the move.
2. Git can preserve prior text in reachable history. That is not the same as
   forcing public recognition, acceptance, or emphasis.
3. The current repository history still shows thin participation evidence. A
   one-author history cannot by itself show that capture cost rises with
   participation.

Therefore `capture_cost_direction` remains `unknown`, and `K1_implication`
remains `not_evaluated`.

## Next Measurement Need

A later result-bearing pass needs an observable threshold for each path:

| need | why it matters | safe source candidates |
|---|---|---|
| Known-public-head evidence | To distinguish a detectable rewrite from a rewrite only the founder remembers. | Tags, releases, archived refs, or public commit references already present in normal repository history. |
| Independent observer availability | To know whether an old object graph is actually retained outside founder control. | Public clone/fork evidence only if available without contact, credentials, or private settings. |
| Adverse-artifact navigation state | To measure whether a committed adverse artifact remains discoverable through ordinary public entry points. | Tracked README, agenda, tests, project maps, and file history. |
| Recognition-routing diff | To separate preserved history from redirected public attention. | Tracked changes to entry points and indexes. |

No later pass should move from `unknown` to a direction without naming whether
the measured cost is coming from git mechanics, observer availability, platform
settings, or founder/governance choice.
