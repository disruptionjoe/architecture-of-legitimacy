# Git Non-Capture Public Retention Source Pass

Status: public source pass, not a K1 verdict.

Lane: Lane 1, `LEGITIMACY-FEASIBILITY`.

Protocol: [2026-07-18 measurement protocol skeleton](2026-07-18-git-non-capture-measurement-protocol.md).

Threshold gate: [2026-07-19 observable thresholds](2026-07-19-git-non-capture-observable-thresholds.md).

Source-intake gate: [2026-07-19 retention source-intake gate](2026-07-19-git-non-capture-retention-source-intake.md).

Checked at: `2026-07-19T11:39:01-05:00`.

Check head: `4ad4895c1ac36d231175f6da2668867d50dc8b5d`.

## Scope

This pass applies the retention source-intake gate to concrete object
identities already named by the git Non-Capture measurement sequence. It uses
only read-only public GitHub source checks and local git ancestry checks.

It does not inspect private repository settings, branch protection, permissions,
issues, pull requests, contributor identities beyond public git metadata,
contact contributors, open issues or pull requests, use non-GitHub sources, or
query any source that requires credentials beyond ordinary GitHub read access.

It does not issue a capture-cost direction, K1 implication, legitimacy verdict,
governance change, policy adoption, public-posture change, or claim-status
change.

## Admissibility Stops Checked

| stop | pass status | note |
|---|---|---|
| Charter, Lane, governance, claim, or public-posture change required | not triggered | This artifact records a bounded source pass inside the measurement project. |
| Adverse measurement repair or suppression | not triggered | No adverse or favorable K1 verdict is issued. |
| Private settings or credentials needed as evidence | excluded | Branch protection, permissions, private forks, and admin controls remain unmeasured. |
| Contributor contact, issue opening, or external participation | excluded | No contact, solicitation, issue, pull request, or non-GitHub external action. |
| Other-repository substrate quantities | excluded | Public GitHub search was used only to look for retained copies or references to this repository's object identities. |
| Proposal, automation signal, or orchestration brief as authority | excluded | The charter, Lane manifest, and measurement artifacts govern. |

## Source Checks

| source check | observed result | threshold consequence |
|---|---|---|
| Canonical GitHub repository metadata, `gh api repos/disruptionjoe/architecture-of-legitimacy` | Public repository; `forks_count=0`, `stargazers_count=0`, `watchers_count=0`; default branch `main`; pushed at `2026-07-19T15:41:24Z`. | No public metadata hint for independent retention. |
| Canonical GitHub forks, `gh api repos/disruptionjoe/architecture-of-legitimacy/forks --paginate` | No fork rows returned. | No public fork source available for `OBS-3`. |
| GitHub repository search, `gh search repos 'architecture-of-legitimacy in:name'` | Only `disruptionjoe/architecture-of-legitimacy` returned. | No same-name public mirror candidate found on GitHub. |
| GitHub exact code search for each tested SHA | No rows returned for any tested object identity. | No `OBS-2` public object-identity reference found in admitted GitHub code search. |
| Canonical public refs, `git ls-remote --refs origin` | Only `refs/heads/main` at `4ad4895c1ac36d231175f6da2668867d50dc8b5d`; no tags. | Canonical current branch is a self-administered public ref, not independent retention. |
| Local ancestry, `git merge-base --is-ancestor <sha> HEAD` | Every tested object identity is an ancestor of current canonical `HEAD`. | Confirms current self-retention, but not observer retention outside canonical administration. |

## Tested Object Identities

| object identity | source slice or artifact | canonical current status | retaining source | object graph coverage | threshold result |
|---|---|---|---|---|---|
| `d7ebc04039795e1deb21ef6382983a6eaa224fac` | Pre-charter Lane contract slice | Ancestor of current canonical `HEAD`. | None found in admitted public GitHub sources. | None outside canonical repository. | `OBS-0 none_observed` |
| `ef35c7f4d33514cdc41d962b6673c546267d26b9` | Charter and Lane revision 2 slice | Ancestor of current canonical `HEAD`. | None found in admitted public GitHub sources. | None outside canonical repository. | `OBS-0 none_observed` |
| `b6669ae8832e1b292280e2f6e57dc782cd84b67d` | Public README alignment slice | Ancestor of current canonical `HEAD`. | None found in admitted public GitHub sources. | None outside canonical repository. | `OBS-0 none_observed` |
| `8f1cdb9ce9661b543434ed225ca8b094dfb31332` | First measurement scaffold slice | Ancestor of current canonical `HEAD`. | None found in admitted public GitHub sources. | None outside canonical repository. | `OBS-0 none_observed` |
| `5e5b88fbb29aa7eb108e3f27ca528032df339d05` | Local data pass head | Ancestor of current canonical `HEAD`. | None found in admitted public GitHub sources. | None outside canonical repository. | `OBS-0 none_observed` |
| `7d51fe63f0cd0cc8b314e3fe47eb345697f50582` | Action-set comparison head | Ancestor of current canonical `HEAD`. | None found in admitted public GitHub sources. | None outside canonical repository. | `OBS-0 none_observed` |
| `5e1c4bd30faf70cff66df25cb74d65a368fe04b6` | Observable threshold gate head | Ancestor of current canonical `HEAD`. | None found in admitted public GitHub sources. | None outside canonical repository. | `OBS-0 none_observed` |
| `bb0628d6ff3111ea699d7e9289b11502b19c95af` | Retention source-intake definition base head | Ancestor of current canonical `HEAD`. | None found in admitted public GitHub sources. | None outside canonical repository. | `OBS-0 none_observed` |
| `4ad4895c1ac36d231175f6da2668867d50dc8b5d` | Retention source-intake committed head | Current canonical `HEAD` at check start. | None found in admitted public GitHub sources. | None outside canonical repository. | `OBS-0 none_observed` |

## Threshold Application

| capture path | strongest current threshold | observed source evidence | cost source classification | current result |
|---|---|---|---|---|
| Rewrite or replace `origin/main` after a known public head | `KPH-1 tracked_self_anchor`; public GitHub source pass remains `OBS-0 none_observed` | The tested objects remain in the current canonical branch history, but no public GitHub fork, mirror candidate, same-name repository, exact-hash code reference, tag, or noncanonical ref exposed them. | Git supplies hash and ancestry anchors inside the self-administered repository. Independent observer-retention cost remains unmeasured. | No observer-retention row can move capture-cost direction. |
| Suppress or de-emphasize an adverse committed artifact | `NAV-0 no_adverse_artifact` | No adverse result-bearing artifact exists in the admitted scope. | No suppression path can be measured yet. | No navigation direction can be issued. |
| Redirect public recognition while preserving history | `RRD-0 no_entrypoint_diff` for an adverse artifact | No adverse result-bearing artifact exists, so no adverse-recognition reroute can exist. | Recognition routing remains founder/governance mediated and unmeasured for adverse content. | No recognition-routing direction can be issued. |

## Current Measurement Position

This pass admits no `OBS-3 retained_object_graph` evidence.

The public GitHub source family currently provides no public metadata hint
(`OBS-1`), no outside object-identity reference (`OBS-2`), and no external
retained object graph (`OBS-3`) for the tested old object identities.

The current `capture_cost_direction` remains `unknown`, and `K1_implication`
remains `not_evaluated`.

## Next Measurement Need

A later pass should re-open observer-retention only if a public fork, mirror,
archive, citation, or exact object-identity reference appears in an admitted
source family and can expose enough object graph data to verify the relevant
rewrite, deletion, or suppression path.

Until then, the strongest current finding remains narrower: git preserves and
names the old objects in the current canonical history, but no admitted public
source shows independent retention outside founder/governance-controlled
canonical routing.
