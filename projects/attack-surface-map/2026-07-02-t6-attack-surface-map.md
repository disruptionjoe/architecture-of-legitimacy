---
artifact_type: attack_surface_map
status: synthetic_test_fixture
created: 2026-07-02
test_target: T6 attack-surface map
governance_role: internal_test_record
constitutional: false
---

# T6 Attack-Surface Map

Status: synthetic test fixture.

Purpose: pressure-test whether the current threat classes in `THREAT-MODEL.md` and protocol layers in `PROTOCOL-STACK.md` imply concrete mitigations rather than only naming capture resistance as a goal.

This file is not a threat-model update, governance decision, reward rule, claim-status decision, public posture change, or evidence that T6 has passed. It is a bounded test object for mapping attacks to observable signals and candidate design responses.

## Threat Classes Under Test

The fixture uses the three current high-level threat classes:

- economic capture
- epistemic capture
- governance capture

It cross-checks those classes against the current protocol stack layers: eligibility, contribution taxonomy, validation, value rubrics, cadence, contribution log, rights, rewards, governance, and capture monitoring.

## Use Pattern

For each attack scenario, reviewers should record:

- the primary threat class,
- which protocol layer is attacked first,
- which legitimacy condition is most at risk,
- what observable signal would reveal the attack early,
- which mitigation is local workflow repair versus governance-sensitive policy,
- and which attack-profitability variable the mitigation changes.

The useful result is not a complete security model. The useful result is seeing whether attack classes produce concrete mitigations and test probes before value, reward, or governance power makes attacks more attractive.

## Attack Scenario Matrix

| id | threat class | attacked surface | attacker goal | early observable signal | candidate mitigation | attack-profitability lever |
|---|---|---|---|---|---|---|
| T6-AM-01 | economic capture | contribution intake | Buy a visible stream of low-value submissions to create apparent contribution weight. | Many similar submissions arrive from linked identities, sponsors, or coordinated language patterns. | Batch related submissions, require mechanism-level relevance, and record dependency or duplicate links. | Raises `C_a`; lowers `P_a` by reducing volume advantage. |
| T6-AM-02 | economic capture | value rubrics | Shape scoring around work the attacker can cheaply mass-produce. | Proposed rubric edits increase weight for easy artifacts while reducing truth-seeking, legitimacy, or capture-resistance scrutiny. | Require rubric-change notes to name who benefits, who loses, and which dimensions become easier to game. | Lowers `B_a`; raises detection probability `D_a`. |
| T6-AM-03 | economic capture | rewards | Convert early non-promissory scores into implied future payout claims. | Contributors cite scores as debts, obligations, or retained-value promises before reward readiness exists. | Keep early scores explicitly non-promissory and separate present recognition from future reward hypotheses. | Lowers extractable benefit `B_a`. |
| T6-AM-04 | economic capture | reviewer selection | Sponsor or reward reviewers to favor a class of contributions. | Review outcomes correlate with external affiliations or sponsorship without stronger evidence quality. | Add conflict-of-interest disclosure prompts and flag disputed reviews for batch review. | Raises detection probability `D_a`; raises sanction/reputation cost `S_a + R_a`. |
| T6-AM-05 | epistemic capture | prior-art review | Narrow novelty by comparing labels while ignoring mechanism differences. | Prior-art notes cite neighboring systems but do not compare validation, voice, contestability, or capture risk. | Enforce the research-class evidence minimum and require mechanism-level comparison. | Lowers `P_a` by making shallow collision claims less persuasive. |
| T6-AM-06 | epistemic capture | synthesis | Rewrite project state in smoother language while flattening uncertainty and open questions. | Summary contributions remove caveats, proof burdens, or failure conditions without explaining the change. | Require synthesis to preserve claim status, uncertainty markers, and links to source surfaces. | Raises `C_a`; raises detection probability `D_a`. |
| T6-AM-07 | epistemic capture | AI support | Use AI-generated volume to simulate consensus or reviewer confidence. | Multiple submissions repeat the same structure, citations, or conclusions without independent reasoning. | Require AI-use disclosure, source trails, and review notes that distinguish evidence from AI-generated synthesis. | Lowers `P_a`; raises detection probability `D_a`. |
| T6-AM-08 | epistemic capture | validation | Launder ideology, preference, or self-interest through technical vocabulary. | Contributions use formal language but do not connect to a live claim, test, source, or protocol layer. | Triage for relevance first, then ask for the affected claim/test and falsification path. | Raises `C_a`; lowers probability of acceptance `P_a`. |
| T6-AM-09 | governance capture | appeal path | Make contestation formally available but practically slow or ownerless. | Contested items have no response window, owner, disposition state, or synthesis cadence. | Add appeal state tracking and unresolved-contest review windows before real disputes accumulate. | Lowers `P_a`; raises reputational cost `R_a` for procedural sinkholes. |
| T6-AM-10 | governance capture | founder authority | Convert founder discretion into permanent control while calling it early-phase pragmatism. | Founder-only exceptions appear without reason, rule gap, or transition implication. | Record founder-phase exceptions and map each to a missing rule, bounded power, or transition trigger. | Raises detection probability `D_a`; lowers long-term benefit `B_a`. |
| T6-AM-11 | governance capture | rule-change process | Change procedure after a contested case to make future challenges harder. | Appeal windows shrink, reviewer eligibility narrows, or rationale requirements weaken after adverse pressure. | Require capture-risk review for rule changes that alter voice, contestability, bounded authority, or exit. | Raises `C_a`; raises `D_a`. |
| T6-AM-12 | governance capture | contribution log | Preserve accepted records while hiding rejected residue that matters for legitimacy. | Adverse decisions lack loss notes, deferred-value notes, or appeal state. | Keep loss notes and residue markers in non-accepted or narrowed contribution records. | Lowers `B_a` from suppressing inconvenient evidence. |
| T6-AM-13 | cross-class | rights and exit | Pressure contributors to stay by making accepted work hard to preserve outside active participation. | Leaving contributors lose practical visibility, attribution, or future review path even when records remain in history. | Separate active participation from retained-record visibility and preserve stable links to accepted work. | Lowers coercive benefit `B_a`; raises legitimacy cost of attack. |
| T6-AM-14 | cross-class | capture monitoring | Treat capture monitoring as a checklist after the valuable decision has already happened. | Attack analysis appears only after reward, governance, or major policy movement is proposed. | Add pre-decision capture checks for changes touching rewards, authority, review eligibility, or appeal rules. | Raises upfront mitigation cost `M`; lowers `P_a`. |

## Mitigation Boundary Notes

- A mitigation candidate is not automatically a policy change.
- Workflow repairs can usually improve visibility, rationale, or record fields without changing governance authority.
- Changes to rewards, retained-value meaning, reviewer authority, founder powers, appeal rights, or public claims require review outside this fixture.
- Economic, epistemic, and governance attacks often overlap; the first attacked surface should be recorded so the response is concrete.
- A good-faith contributor can still trigger an attack pattern accidentally. The map should diagnose incentives and surfaces, not assume bad faith.

## Candidate Review Questions

1. Which scenarios are detectable using current repo fields, and which need a new field or review state?
2. Which mitigations reduce attack profitability without making contribution review too heavy for early participants?
3. Where do `legitimacy` and `capture_resistance` rubric dimensions overlap, and where do they diagnose different risks?
4. Which scenarios require founder-phase constraints before real contributions create disputed value?
5. Which attack-profitability variable is easiest for the current protocol stack to affect: `P_a`, `B_a`, `C_a`, `M`, `D_a`, `S_a`, or `R_a`?

## Pass Criteria For A Later T6 Review

T6 can move toward a stronger result when:

- economic, epistemic, and governance attack classes each map to concrete protocol surfaces,
- each attack has an observable early signal rather than only a label,
- mitigations identify whether they are local workflow repairs or governance-sensitive changes,
- at least one mitigation changes a named attack-profitability variable,
- and reviewers can distinguish ordinary dissatisfaction from capture pressure without private founder context.

This fixture does not mark T6 passed. It gives the repo a repeatable object for testing whether capture resistance can become operational before rewards or governance power accumulate.
