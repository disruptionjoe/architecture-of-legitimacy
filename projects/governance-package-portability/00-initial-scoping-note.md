# Initial Scoping Note

Date: 2026-06-23

Scope: first pass only. This note creates the project container and identifies
the likely file paths and artifacts to study next. It does not inventory the
full governance package and does not propose the GU port.

## First-Pass Finding

The project is well placed in `architecture-of-legitimacy`.

The target repo already frames legitimacy through visibility, contestability,
voice, exit with retained record, adaptive rule change, bounded authority, and
non-capture. The portability question asks whether an AI-assisted research
governance package can make those legitimacy properties operational across
repositories without becoming process overhead.

## Architecture Of Legitimacy Anchors

Initial local files read:

| Path | Relevance |
| --- | --- |
| `README.md` | Frames the repository as a public research program on legitimate contribution allocation, validation, review, reward, capture resistance, and governance transition. |
| `GOVERNANCE.md` | Defines founder-led research phase and phase model from founding research through institutional generalization. |
| `RESEARCH-AGENDA.md` | Names review cadence, contribution logs, workflow, transition, attack modeling, and generalization as research questions. |
| `LEGITIMACY-SCHEMA.md` | Supplies the legitimacy criteria this project should use to judge portability. |

No existing `projects/` convention was found in the repo root during the first
scan, so this study starts a clearly named project directory under
`projects/governance-package-portability/`.

## Origin Setting: Temporal Issuance

Temporal Issuance has an explicit governance-package seed and a mature steward
system. Likely study paths:

| Path | Why it matters |
| --- | --- |
| `governance-package/README.md` | Explicitly reserves portable governance components and warns against importing TI-specific assumptions. |
| `AGENTS.md` | Repo-level agent start rules, constitutional objects, external-content handling, and steward posture. |
| `agent-governance/REPO-STEWARD.md` | Anchored steward identity, authority, wake conditions, and operating rules. |
| `agent-governance/AGENT-RUN-PROTOCOL.md` | Run preflight, decision, execution, merge, and learning-return contract. |
| `agent-runs/README.md` | Required run record fields: strongest version, strongest objection, collapse, survival, absorption, blockers, next run, files changed. |
| `agent-governance/NEXT-TRIGGER-PLAN.md` | Live queue of next research triggers and run routing. |
| `agent-governance/PROMOTION-GATES.md` | Claim, workflow, and persona promotion constraints. |
| `memory/learning-return-schema.md` | Standard workflow return schema. |
| `memory/steward-memory-summary.md` | Compressed durable memory of research state and killed paths. |
| `memory/steward-memory-log.md` | Append-style durable memory log, likely needed for origin-history reconstruction. |
| `memory/path-kills.md` | Path-kill record and resurrection logic. |
| `CLAIM-LEDGER.md` | Claim status vocabulary and claim movement surface. |
| `KILL-CRITERIA.md` | Kill classes and premature-closure guardrails. |
| `ROADMAP.md` | Phase structure and current priorities. |
| `workflows/` | Dynamic and durable workflow surfaces. |
| `personas/` and `agent-governance/PERSONA-REGISTRY.md` | Persona system and promotion/adversarial review machinery. |

Initial observation: the governance package appears to have emerged from
research pressure, not abstract planning alone. The strongest evidence is the
link between live next-trigger plans, run records, memory, claim status, and
kill criteria.

## Greenfield Transfer: AI-Native Epistemic Systems

AI-Native Epistemic Systems is already marked as the first transfer experiment.
Likely study paths:

| Path | Why it matters |
| --- | --- |
| `TRANSFER-EXPERIMENT.md` | Primary evidence for what transferred directly, what adapted, and what changed structurally. |
| `governance-package/README.md` | States seed-phase criteria for adding portable components. |
| `AGENTS.md` | Adds the dual role: pursue the research question and track transfer fidelity. |
| `agent-governance/REPO-STEWARD.md` | Shows how the steward identity was adapted for the new domain. |
| `ROADMAP.md` | Includes Phase 4 transfer experiment verdict and W002 machinery extraction. |
| `RUN-CLOSEOUT-CHECKLIST.md` | Candidate portable closeout surface. |
| `agent-runs/` | Run evidence for whether the transferred package produced research output. |
| `memory/steward-memory-summary.md` | Current compressed memory and transfer state. |
| `KILL-CRITERIA.md` | Contains K6, a domain-driven extension that may be evidence of successful adaptation rather than package failure. |
| `explorations/E006-w004-governance-audit.md` | Likely direct governance audit surface. |
| `explorations/E018-separability-theoretic-discriminator-candidate-5.md` | Important because SCS/K6 distinguishes architecture from realized independence. |

Initial observation: the transfer file claims a preliminary strong success
candidate, but this project must not accept that verdict uncritically. It
should check run outputs, stale surfaces, overhead, and whether "direct" means
actually reusable or merely copied without enough pressure yet.

## Brownfield Candidate: GU Formalization

GU Formalization already has process surfaces. This makes it a brownfield test,
not a greenfield transplant.

Likely study paths:

| Path | Why it matters |
| --- | --- |
| `README.md` | States repo layers and current public posture. |
| `RESEARCH-STATUS.md` | Defines status labels and current research map. |
| `CANON.md` | Public spine and stable claims. |
| `NEXT-STEPS.md` | Contributor routing and active work queue. |
| `DERIVATION-PROGRESS.md` | Existing progress tracking surface. |
| `canon/no-go-class-relative-map.md` | Core no-go and assumption discipline. |
| `canon/six-axis-specification-protocol.md` | Existing typed proposal admission protocol, likely not to be replaced. |
| `specifications/six-axis/` | Templates and examples for GU-specific rigor. |
| `process/` | Persona passes, dialectics, and synthesis history. |
| `process/persona-passes/INDEX.md` | Persona system already present. |
| `process/syntheses/INDEX.md` | Existing synthesis archive. |
| `explorations/` | Large active exploration surface where phase labeling may be useful. |
| `active-research/` | Frontstage theorem work, important for brownfield integration. |
| `automation/runs/` | Existing automation run traces, possible analog to agent-run logging. |
| `sources/claim-ledger.md` | Claim-mining surface, not necessarily a full claim ledger. |

Initial observation: GU already has canon/exploration separation, status labels,
six-axis admission discipline, persona passes, syntheses, active research, and
automation traces. A port should probably adapt a thin layer around phase labels,
run receipts, and witness obligations rather than transplanting TI's whole
steward system.

## Required GU Phase Lens For Later Port Plan

The GU port plan should classify runs by the following phase map:

| Phase | Meaning |
| --- | --- |
| Phase 1: Research Map | Claims, assumptions, no-go theorems, open blockers, and possible routes are mapped. |
| Phase 2: Local Mechanism | One bounded mathematical mechanism closes. |
| Phase 3: Standard Model Algebra | The construction derives the correct algebraic structure: chirality, anomaly cancellation, branching, hypercharge, generation count, and no hidden multiplicity mismatch. |
| Phase 4: Testable Physics | The framework produces quantitative predictions or explanations that touch measurable physics. |

Initial caution: most current GU outputs appear to be Phase 1 or Phase 2 unless
they explicitly close Standard Model algebra or measurable-physics obligations.

## Initial Portability Hypotheses To Test

These are hypotheses, not findings:

| Component | Initial guess | Reason to test |
| --- | --- | --- |
| Anchored steward | Research-program core | Useful, but may be too heavy for GU unless scoped as a light repo steward or phase steward. |
| Run records | Universal or research-program core | Brownfield GU needs run receipts that do not overwrite existing process history. |
| Claim ledger | Research-program core | GU has claims and canon maps, but not necessarily a unified claim-state ledger. |
| Kill criteria and path kills | Universal core for speculative research | GU's no-go discipline already fits this, but vocabulary must be GU-native. |
| Promotion gates | Universal core | GU already has promotion rule in `RESEARCH-STATUS.md`; port should align, not replace. |
| Persona registry | Optional enhancement | GU already has persona passes; registry may create overhead unless tied to review quality. |
| Memory pack | Research-program core | Helpful for continuity, but brownfield import risks duplicating `RESEARCH-STATUS.md` and `DERIVATION-PROGRESS.md`. |
| Hourly cadence | Optional or do-not-port initially | Could create process drag if not tied to high-value GU work. |
| VSM map | Optional enhancement | Needs evidence before porting. |
| Governance-change ledger | Architecture-of-legitimacy core, but optional for GU | Useful if GU governance itself changes; not necessary for theorem runs. |

## Next Study Actions

1. Build `01-governance-package-inventory.md` from the file paths above.
2. Reconstruct the Temporal Issuance origin history using `agent-runs/`,
   `memory/steward-memory-log.md`, `GOVERNANCE-CHANGE-LEDGER.md`, and
   `NEXT-TRIGGER-PLAN.md`.
3. Review AI-Native's greenfield transfer by comparing `TRANSFER-EXPERIMENT.md`
   against actual run outputs and current unused/stale surfaces.
4. Build a component portability model before drafting any GU changes.
5. Only then draft the GU brownfield port plan.

## Stop Conditions

- Do not copy files into GU before the portability model exists.
- Do not assume AI-Native's transfer verdict is correct just because the repo
  says it is a strong success candidate.
- Do not replace GU's six-axis protocol or canon/exploration status model.
- Do not treat process adoption as legitimacy evidence unless it improves
  claim clarity, review quality, falsifiability, or overclaim resistance.
