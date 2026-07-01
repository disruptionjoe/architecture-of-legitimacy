# Architecture Of Legitimacy Steward Context

Status: active. Canonical steward load file adopted 2026-07-01 from the CapacityOS Repo Steward reference architecture. Original steward rollout: RUN-20260630-010. Surface map: `CapacityOS/system/meta/maps/repository-surfaces/architecture-of-legitimacy.yaml`.

Load this file when a Kernel directive, RCCM workflow, or direct repo-mounted run targets this repository. Do not load `steward/memory-log.md` by default unless doing stewardship or memory work, or this summary appears incomplete.

## North Star

Advance the legitimate-contribution-allocation research program: make contribution, legitimacy, and reward cohere under adversarial pressure as the seed of a capture-resistant, collaborative institution.

Change rule: do not change this North Star without very explicit conversation with Joe.

## Long-Term Objectives

- Advance the repo-owned research agenda in `RESEARCH-AGENDA.md`.
- Keep roadmap sequencing coherent with `ROADMAP.md`.
- Maintain contribution, legitimacy, and reward concepts as testable research claims rather than vague institutional language.
- Preserve the repo as a public research truth surface.

Objectives may change when Joe directs that they change.

## Measures And Countermeasures

Measures:

- Contribution workflow makes legitimate contributions easier to propose, review, and classify.
- Claims, schemas, tests, and governance documents stay mutually consistent.
- Capture and threat concerns surface before public-facing claims harden.
- New work advances the research agenda without bypassing contribution standards.

Countermeasures / risks:

- Do not promote exploratory notes into constitutional claims too early.
- Do not let reusable governance/process IP leak out through this public repo without explicit Joe approval.
- Do not flatten adversarial-pressure or capture-risk concerns into generic collaboration language.
- Do not let CapacityOS coordination become the owner of this repo's research truth.

## What This Repo Owns

This repo owns its research truth: claims, the legitimacy schema, protocol stack, governance/guardrails, threat model, essays, explorations, contribution standards, and research agenda.

## What This Repo Must Not Absorb

- CapacityOS architecture, Kernel machinery, or RCCM methodology.
- JoeOps work coordination or generalized backlog state.
- Research truth owned by other Church of AI repos.
- Reusable governance/process IP unless explicitly promoted here.

Route, don't absorb: point to truth owned elsewhere; never accrete another repo's content.

## Operating Guardrails

- Contributions follow `CONTRIBUTING.md` and `CONTRIBUTION-STANDARDS.md`.
- Governance follows `GOVERNANCE.md` and `GUARDRAILS.md`.
- Advance one lifecycle stage at a time and stop at the next real pause boundary.
- Evidence-first; apply the abstraction challenge before adding concepts.
- Public/external consequence, claim-status changes, IP extraction, or capture-risk decisions pause for Joe.
- Internal drafting can continue when it is reversible and clearly marked.
- When a hard rule matters, cite the owning source instead of copying large policy blocks here.

## Routing

- Research claims, schemas, tests, roadmap, and contribution standards stay in this repo.
- CapacityOS architecture questions route to `C:\Users\joe\JB\CapacityOS`.
- JoeOps coordination questions route to `C:\Users\joe\JB\Github Repos\joeops`.
- Durable rendered artifacts belong in `C:\Users\joe\JB\library\repos\public\architecture-of-legitimacy\`.
- Scratch, caches, and intermediate renders belong in `_local/`.

## Candidate Decisions

- The contribution workflow scaffolding created in RUN-20260630-011 is the current candidate operating pattern for Phase 1 / RQ5 contribution work.

## Durable Decisions

- This repo is public; public/private and external-consequence decisions are governed.
- Constitutional claims and the legitimacy schema are repo-owned truth.
- The real governance boundary is promotion or external consequence, not internal drafting.
- CapacityOS may coordinate or provide reusable capability, but it does not own this repo's records or decisions.

## Principles

- Preserve research sovereignty: the owning repo holds its own truth.
- Treat contribution, legitimacy, and reward as pressure-tested research concepts.
- Route reusable system learnings upward; keep local research detail local.

Decision ladder: candidate decision -> durable decision -> principle.

## Memory Log

Chronological memory lives at `steward/memory-log.md`.

After every session where this README is loaded, append useful memory from that session to the memory log. Useful memory may include Joe decisions, durable operating preferences, friction, repeated patterns, repo quirks, routing clarifications, changes to the repo's operating shape, candidate principles, or items that may later be summarized into this README.

Upward learning mechanics mainly belong in RCCM/workflow machinery. Lightweight pointer: method/workflow-module learnings go to `CapacityOS/system/rccm-learnings/`; kernel-primitive learnings go to `CapacityOS/system/kernel-learnings/`.

## Automation Hooks

Supports CapacityOS-orchestrated and direct repo-mounted runs. Automations are thin triggers; the RCCM plus this steward context supply the workflow. Execution still follows repo guardrails and external/public consequence stops.

## Local Source References

- `README.md`
- `RESEARCH-AGENDA.md`
- `ROADMAP.md`
- `CONTRIBUTING.md`
- `CONTRIBUTION-STANDARDS.md`
- `GOVERNANCE.md`
- `GUARDRAILS.md`
- `THREAT-MODEL.md`
- `CLAIMS.md`
- `LEGITIMACY-SCHEMA.md`
- `PROTOCOL-STACK.md`
