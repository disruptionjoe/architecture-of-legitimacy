# Git Non-Capture Local Data Pass

Status: source-separated local data pass, not a measurement verdict.

Lane: Lane 1, `LEGITIMACY-FEASIBILITY`.

Protocol: [2026-07-18 measurement protocol skeleton](2026-07-18-git-non-capture-measurement-protocol.md).

Measured at: `2026-07-19T06:58:36-05:00`.

Pre-pass repository head: `8f1cdb9ce9661b543434ed225ca8b094dfb31332`.

## Scope

This pass uses only local git history and tracked public repository surfaces. It
does not use private repository settings, GitHub API state, branch-protection
configuration, contributor contact, issues, pull requests, or external
publication state.

It records source facts and founder-discretion labels so a later measurement can
compare action sets without silently treating founder control as git-substrate
resistance.

## Admissibility Stops Checked

| stop | pass status | note |
|---|---|---|
| Charter, Lane, governance, claim, or public-posture change required | not triggered | This artifact changes only the measurement project and local indexes/state. |
| Adverse measurement repair or suppression | not triggered | No adverse or favorable result is issued. |
| Private settings or credentials needed as evidence | excluded | Branch protection and repository permissions are not measured here. |
| Contributor contact, issue opening, or external participation | excluded | No non-GitHub external action and no GitHub issue/PR action. |
| Other-repository substrate quantities | excluded | Only this repository's git history is used. |
| Proposal, automation signal, or orchestration brief as authority | excluded | Prior run handoff is collision context; charter and repo surfaces govern. |

## Local Git Snapshot

| field | observed value | source command | founder-discretion label |
|---|---|---|---|
| Root commit | `8356ccd18231610413f9ab0929876dcf476f3a4f` | `git rev-list --max-parents=0 HEAD` | Git-substrate ancestry anchor; canonical interpretation remains founder-framed. |
| Current pre-pass head | `8f1cdb9ce9661b543434ed225ca8b094dfb31332` | `git rev-parse HEAD` | Git-substrate object identity; canonical branch target is governance-controlled. |
| Current branch | `main` | `git branch --show-current` | Canonical branch choice is founder/governance controlled. |
| Upstream parity | `HEAD` and `origin/main` differed by `0 0` commits | `git rev-list --left-right --count HEAD...origin/main` | Remote publication is routine versioning; branch protections were not measured. |
| Remote | `https://github.com/disruptionjoe/architecture-of-legitimacy.git` | `git remote -v` | Public remote supports cloning/forking; repository administration remains founder/platform controlled. |
| Total commits at pre-pass head | `203` | `git rev-list --count HEAD` | Commit count is not legitimacy; it is only accumulated record mass. |
| Visible author identities | `1` | `git log --all --format='%aN'` grouped by unique name | Participation is author-dominated in this pass; meaningful participation is not established. |
| Tags | none returned | `git tag --list` | No tag anchors beyond branch history are present. |
| Tracked paths at pre-pass head | `192` | `git ls-tree -r --name-only HEAD` | File count is not legitimacy; it only bounds the visible record. |

## Slice Facts

| slice | commit | time | commit count | tracked paths | observed change | founder-discretion risk |
|---|---|---|---:|---:|---|---|
| Pre-charter Lane contract | `d7ebc04039795e1deb21ef6382983a6eaa224fac` | `2026-07-16T19:04:43-05:00` | 199 | 188 | First-class Lane contract installed before charter ratification. | Lane framing originated in founder-approved repo work. |
| Charter and Lane revision 2 | `ef35c7f4d33514cdc41d962b6673c546267d26b9` | `2026-07-16T20:34:52-05:00` | 200 | 189 | Charter ratified and lanes re-pointed from manifest render to charter. | Charter ratification is Joe/founder authority, not a git property. |
| Public alignment and state | `b6669ae8832e1b292280e2f6e57dc782cd84b67d` | `2026-07-18T22:39:44-05:00` | 202 | 190 | Public README aligned with the ratified charter after lane state snapshot. | README framing is directly editable by founder/governance. |
| First measurement scaffold | `8f1cdb9ce9661b543434ed225ca8b094dfb31332` | `2026-07-18T23:43:31-05:00` | 203 | 192 | Git Non-Capture protocol scaffold added. | Measurement preparation may raise visibility, but this pass does not measure cost direction. |

## Mechanism Separation

| capture path | git-substrate mechanism visible in this pass | founder/governance input visible in this pass | first-pass status |
|---|---|---|---|
| Alter canonical history | Commit hashes and parent ancestry make rewritten history detectable against known hashes. | The canonical branch and remote administration are controlled outside local git facts. | source fact only |
| Suppress prior record | Existing commits remain addressable in the local object graph at this pass. | Continued public availability, branch protection, and administrative deletion are not measured. | source fact only |
| Redirect recognition | Git preserves diffs showing when public framing changed. | README, charter ratification, and acceptance language are founder/governance-controlled. | source fact only |
| Bury adverse finding | A committed adverse artifact would have an object hash and ancestry position. | Acceptance, linking, public emphasis, and external publication remain founder-controlled. | source fact only |
| Inflate participation | Git can count visible authorship, but current history shows one visible author identity. | The founder can admit, ignore, merge, or frame participation. | participation proxy currently thin |

## Output Fields For Later Measurement

| field | first-pass value |
|---|---|
| `measurement_scope` | Local git history and tracked public repository surfaces through pre-pass head `8f1cdb9`. |
| `substrate_mechanism` | Commit-hash ancestry, local object graph, public remote clone target, branch/remotes visible in local git. |
| `legitimacy_participation_delta` | Charter ratification and measurement scaffold are visible; meaningful participation delta is not established. |
| `founder_discretion_label` | High: charter ratification, canonical branch, README framing, merge/review authority, adverse-finding acceptance, and external publication remain founder/governance controlled or unmeasured. |
| `capture_cost_direction` | `unknown` |
| `K1_implication` | `not_evaluated` |

## Next Measurement Need

The next result-bearing pass should define an action-set comparison for at least
three capture paths:

1. rewriting or replacing `origin/main` after a known public head;
2. suppressing or de-emphasizing an adverse committed artifact; and
3. redirecting public recognition while preserving underlying git history.

Each row should name whether the cost comes from git mechanics, public clone or
fork availability, GitHub/platform settings, or Joe/founder governance choices.
Until that action-set comparison exists, the capture-cost direction remains
`unknown` and K1 remains `not_evaluated`.
