# Git Non-Capture Measurement Protocol Skeleton

Status: protocol skeleton.

Lane: Lane 1, `LEGITIMACY-FEASIBILITY`.

Charter target: `governance/CHARTER.md#first-experiment`.

## Question

On this repository's git substrate, does capture cost become non-decreasing as
accumulated legitimacy and participation grow because of git properties, rather
than because of founder decisions?

This skeleton does not answer the question. It defines the minimum separation a
later measurement needs before it can issue a result.

## Measurement Object

The measured object is this repository as a git-backed public research program.
The first pass should use only repo-local git history and public repository
surfaces unless a later governed review explicitly admits another source.

## Candidate Variables

| variable | first-pass source | founder-discretion risk | admissibility note |
|---|---|---|---|
| Accumulated legitimacy proxy | Ratified charter, lane manifest, accepted public artifacts, visible rationale trails. | Joe decides ratification and can choose what receives attention. | Must not treat file count or ceremony as legitimacy. |
| Participation proxy | Git authors, contribution records, public proposal traces, review traces. | Founder-led merge/review authority can admit or ignore participation. | Must separate authored commits from meaningful participation. |
| Git substrate resistance | Forkability, replicated history, signed or attributable commits where available, immutable ancestry. | Founder can still control canonical branch, merge policy, and public framing. | Measure substrate properties separately from repository governance choices. |
| Capture cost proxy | Minimum action set needed to alter canonical history, suppress prior record, or redirect recognition. | Founder can raise or lower practical cost by policy, access, and attention. | Name whether cost comes from git mechanics or founder choice. |
| Adverse route visibility | Whether an adverse finding can remain visible in history after rejection or disagreement. | Founder can accept, ignore, bury, or reframe the finding. | Visibility through git history is not the same as accepted legitimacy. |

## Time Slices

A later measurement should compare at least three slices:

| slice | purpose | required evidence |
|---|---|---|
| Before charter ratification | Baseline founder-led repository state. | Commit history and pre-charter governance surfaces. |
| At charter and Lane revision 2 | Point where the first falsifier was ratified. | `governance/CHARTER.md`, `LANES.yaml`, and public README alignment. |
| After first measurement artifacts | Whether measurement preparation changed capture surface. | This directory, later measurement outputs, and any review traces. |

## Founder-Discretion Inventory

Each measurement row must name whether Joe or founder-led governance controls:

- merge authority;
- branch protection or repository settings;
- public README framing;
- charter ratification;
- reviewer appointment;
- acceptance of adverse findings;
- escalation to external publication; and
- any source included beyond local git history.

If an observed rise in capture cost depends on one of these controls, the row is
founder-determined unless it also shows an independent git-substrate mechanism.

## Admissibility Stops

Stop before issuing a result if the run would require:

- changing the charter, Lane manifest, governance, claims, or public posture;
- suppressing or repairing an adverse measurement while it is open;
- using private repository settings or credentials as evidence;
- contacting contributors, opening issues, or soliciting external participation;
- importing another repository's substrate quantities; or
- treating a proposal, automation signal, or orchestration brief as authority.

## Output Shape For A Later Measurement

A result-bearing artifact should include:

| field | requirement |
|---|---|
| `measurement_scope` | Exact slices, sources, and excluded sources. |
| `substrate_mechanism` | What git makes harder to capture independent of founder choice. |
| `legitimacy_participation_delta` | What changed with legitimacy or participation. |
| `founder_discretion_label` | Which inputs Joe/founder-led governance controls. |
| `capture_cost_direction` | Increasing, flat, falling, or unknown. |
| `K1_implication` | `not_evaluated`, `adverse_candidate`, `supports_but_not_proven`, or `unknown`. |

No later artifact should mark K1 cleared or fired without naming the founder
discretion inventory and the exact evidence path.
