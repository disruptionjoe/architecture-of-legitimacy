# First Contribution Workflow Dry Run

Status: synthetic workflow evidence map

## Purpose

This project holds non-live T10 and T11 artifacts for testing whether a
contribution can move through proposal, review, rationale, loss notes,
contestability, and log-readiness without relying on private founder context.

The directory is review-prep only. It does not create live contribution records,
change `CONTRIBUTIONS-LOG.md`, change `templates/contribution-log-schema.md`,
alter test state, adopt review policy, create rights or reward meaning,
change governance, move claim status, or change public posture.

## Read Order

1. [Synthetic contribution log examples](2026-07-01-synthetic-contribution-log-examples.md)
   pressure-test the log schema with accepted, needs-revision, and not-accepted
   `SAMPLE-*` entries.
2. [Synthetic contribution trace](2026-07-01-synthetic-contribution-trace.md)
   walks one synthetic research contribution through submission, triage,
   evidence review, rationale, retained record, and loss notes.
3. [T11 synthetic adverse-decision trace](2026-07-05-t11-synthetic-adverse-decision-trace.md)
   adds a bounded not-accepted path with rationale, revision route, loss notes,
   and contestability marker.
4. [T10 contribution log schema boundary map](2026-07-06-t10-log-schema-boundary-map.md)
   identifies field-level risks before any live contribution-log use.
5. [T11 retained-marker boundary](2026-07-06-t11-retained-marker-boundary.md)
   separates retained record, retained recognition, useful residue, and
   rights/reward claims.
6. [T10/T11 first-pilot log-readiness screen](2026-07-08-t10-t11-first-pilot-log-readiness-screen.md)
   applies the T10/T11 boundaries to the synthetic first-pilot packet.

## Artifact Index

| artifact | role | preserved boundary |
|---|---|---|
| `2026-07-01-synthetic-contribution-log-examples.md` | T10 schema pressure examples | Synthetic entries stay out of the live `CONTRIB-*` namespace. |
| `2026-07-01-synthetic-contribution-trace.md` | T11 normal-path workflow trace | No real contribution is accepted, rejected, rewarded, or logged. |
| `2026-07-05-t11-synthetic-adverse-decision-trace.md` | T11 adverse-path trace | A status-movement request can be refused without creating appeal or sanction policy. |
| `2026-07-06-t10-log-schema-boundary-map.md` | T10 field-risk map | Review state, scores, loss notes, and links remain descriptive rather than policy-making. |
| `2026-07-06-t11-retained-marker-boundary.md` | T11 retained-record boundary | Retained residue stays separate from reward, rights, governance weight, or ownership. |
| `2026-07-08-t10-t11-first-pilot-log-readiness-screen.md` | First-pilot log-readiness screen | The synthetic packet is log-screen-ready, not live-log-entry-ready. |

## Current Evidence Shape

The directory shows that the existing contribution surfaces can represent:

- synthetic submission and triage;
- review state and rationale;
- source and evidence gaps;
- useful residue through `loss_notes`;
- contestability markers without appeal-policy adoption;
- log-readiness questions before live `CONTRIB-*` use.

It does not show that a real contributor can yet reconstruct a real review from
public records, that the live-use evidence burden has been met, or that the
repo has adopted rights, rewards, reviewer authority, appeal paths, or
governance movement from these artifacts.

## Later Evidence Needed

A stronger T10/T11 review would need a real or explicitly governed first-pilot
packet with:

- a real contribution unit or clearly authorized pilot target;
- public source and review links;
- a review decision with decisive rationale;
- non-promissory loss notes where value is deferred;
- a contestability marker that does not create appeal policy;
- an explicit decision about whether a live `CONTRIB-*` entry is justified.

Until then, this directory should be read as synthetic review-prep evidence,
not as active contribution workflow policy.
