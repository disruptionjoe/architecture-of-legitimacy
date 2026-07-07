# Governance Package Inventory Frame

Date: 2026-07-07

Status: inventory scaffold. This file organizes what to inspect next. It does
not claim that the package is portable, complete, desirable for GU
Formalization, or ready to copy into any other repository.

## Purpose

The portability study needs a stable way to distinguish useful institutional
machinery from local workflow sediment. This inventory frame names candidate
components, the evidence each component would need, and the failure signals
that would argue against portability.

Use this frame before drafting a port plan. A later study can fill evidence
from the origin setting, greenfield transfer, and brownfield candidate without
turning the inventory itself into a verdict.

## Inventory Method

For each candidate component, record:

1. the institutional problem it is supposed to solve;
2. the minimum origin evidence that it actually mattered;
3. the minimum transfer evidence that it helped outside the origin setting;
4. the adaptation burden for a brownfield repo;
5. the capture, overhead, or false-legitimacy risk;
6. the decision boundary: keep, adapt, defer, or reject.

The decision boundary is a later review output. This file supplies the slots
needed to make that review possible.

## Candidate Component Classes

| Component class | Claimed problem solved | Origin evidence to seek | Transfer evidence to seek | Brownfield adaptation question | Failure signal |
| --- | --- | --- | --- | --- | --- |
| Anchored steward | Maintains continuity, authority boundaries, and repo-specific judgment across runs. | Steward wake conditions, authority limits, and examples where the steward prevented drift or premature promotion. | Evidence that a transferred steward improved output quality without becoming a generic process layer. | Can the target repo use a thin steward role without replacing existing local governance? | Steward text becomes identity theater, duplicates existing owner judgment, or obscures who has authority. |
| Run records and closeout | Makes agent work reviewable, resumable, and accountable. | Runs that preserved strongest objections, blockers, files changed, and next triggers in a way later work used. | Runs where the record prevented repeated work or supported a better next step. | Which receipt fields are missing from the target repo's existing process history? | Run logs accumulate but are not read, linked, or used for decisions. |
| Claim ledger and status vocabulary | Keeps claims from hardening before evidence, review, or promotion. | Claim movements with visible evidence and status constraints. | Evidence that status vocabulary prevented overclaim in the transfer repo. | Does the target already have canon, status labels, or claim maps that should be aligned instead of replaced? | Status labels become decorative or create disagreement about canonical truth. |
| Kill criteria and path-kill records | Preserves falsifiability and avoids sunk-cost continuation. | Examples where a path was killed, paused, or later resurrected under explicit conditions. | Evidence that kill criteria adapted to the new domain rather than importing origin-specific assumptions. | What counts as a native no-go, blocker, or resurrection condition in the target repo? | Kill criteria are so broad they never fire, or so rigid they suppress legitimate exploration. |
| Promotion gates | Separates draft, workflow, claim, and persona promotion from routine iteration. | Cases where gates delayed or narrowed a claim, workflow, or role before adoption. | Evidence that transferred gates caught premature promotion. | Which existing target-repo promotion rules should the gate attach to? | Gates create ceremony without changing review quality or claim discipline. |
| Memory summary and append-only memory | Carries durable context across many agent runs. | Evidence that summaries compressed useful state and logs preserved traceable changes. | Evidence that memory avoided repeated context loading or rediscovery. | What should remain in existing repo status files versus a separate memory pack? | Memory duplicates canonical files, grows stale, or becomes an unreviewed shadow source of truth. |
| Next-trigger plan and cadence | Converts open research state into actionable next work. | Next triggers that led to coherent runs and avoided priority drift. | Evidence that cadence matched the transfer repo's real work rhythm. | Does the target need scheduled cadence, manual triggers, or no cadence at all? | Cadence creates pressure to invent work or chase low-value tasks. |
| Persona registry and adversarial review | Makes review perspectives explicit and reusable. | Persona passes that found different failures than a single reviewer would have found. | Evidence that personas were adapted to the transfer domain. | Does the target already have persona, dialectic, or synthesis surfaces that should remain primary? | Personas become stylized labels without stronger objections or better synthesis. |
| Absorber discipline and same-neighbor-data tests | Prevents nearby theories or tools from absorbing the project without remainder. | Cases where the test clarified what the project uniquely explains. | Evidence that the test survived contact with a new domain. | What are the target repo's nearest absorbers and native comparison axes? | The test becomes a novelty claim instead of a constraint on overclaim. |
| Governance-change ledger | Makes process changes reviewable instead of invisible. | Process changes with reason, authority, and observed effect. | Evidence that ledgered changes reduced drift or confusion. | Is the target repo changing governance often enough to justify this surface? | Ledger maintenance outweighs the value of the changes it records. |

## Cross-Component Questions

| Question | Why it matters |
| --- | --- |
| Which components are load-bearing versus merely convenient? | Portability depends on causal value, not the presence of a file. |
| Which components require a live steward or maintainer to stay meaningful? | Some machinery fails if no one has responsibility to prune and interpret it. |
| Which components are universal, research-program-specific, or domain-specific? | A port plan should adapt by class, not copy by file path. |
| Which components protect legitimacy directly versus indirectly? | Direct protections should preserve visibility, contestability, bounded authority, or non-capture. |
| Which components create public-facing commitments? | Public posture and rights/reward/governance implications require review before adoption. |
| Which components can be tested with synthetic traces before touching real repo governance? | Synthetic traces lower risk while preserving falsifiability. |

## Evidence Packet Shape

A later evidence packet should use one row per component and include:

| Field | Meaning |
| --- | --- |
| Component | The candidate governance-package component. |
| Origin path examples | Origin surfaces where the component appears. |
| Origin function evidence | What the component did in actual work, not just what it says it does. |
| Greenfield transfer evidence | Whether the component survived or changed in the first transfer setting. |
| Brownfield conflict surface | Existing target-repo surfaces that may already solve the problem. |
| Portability class | Universal, research-program core, optional enhancement, target-specific, or do-not-port. |
| Minimum viable adapter | The thinnest target-native version worth testing. |
| Kill condition | Evidence that the component should not be ported or should be removed. |

## Portability Classes

| Class | Meaning | Review burden |
| --- | --- | --- |
| Universal | The component solves a recurring AI-assisted research problem across contexts. | Show at least origin value and one successful transfer or strong target-native need. |
| Research-program core | The component is valuable for multi-run speculative research, but must adapt to domain truth. | Show that it preserves evidence, claim discipline, or continuity without duplicating local canon. |
| Optional enhancement | The component can improve review quality or coordination when the target already has enough pressure for it. | Show a specific target pain point before adoption. |
| Target-specific | The component should be redesigned in the target repo's own vocabulary. | Show why the origin version would misfit or overreach. |
| Do-not-port | The component is local sediment, stale, too heavy, or creates false legitimacy. | Record why rejection is protective, not neglect. |

## Boundary Checks Before Any Port Plan

- Do not recommend copying a component because it exists in the origin repo.
- Do not treat greenfield transfer success language as evidence until actual
  run outputs and stale-surface risks have been checked.
- Do not replace a brownfield repo's existing canon, status, specification, or
  review machinery without a repo-local problem the replacement solves.
- Do not let governance-package language imply rights, rewards, public posture,
  claim status, or contributor commitments.
- Do not convert this inventory into a verdict. The next legitimate output is
  an evidence packet, not an adoption plan.

## Immediate Next Evidence Work

1. Fill origin evidence for each component from the origin setting.
2. Compare greenfield transfer claims against actual transfer-run outputs.
3. Identify brownfield conflict surfaces before proposing any target adapter.
4. Assign tentative portability classes only after evidence exists.
5. Record kill conditions for components that look useful but add process drag.
