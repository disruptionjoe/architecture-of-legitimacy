---
artifact_type: observation
status: bounded_case
lane: 1
claim_status_change: none
governance_change: none
external_action: none
---

# Cross-owner revision pin observation

## Question

What prevents a later correction in one repository from silently changing the
accepted basis of a candidate owned by another repository?

## Observed case

Two public commits provide a bounded implementation case:

- CAI Systemic Failure `092cb09` completes the governance fields for
  `SFQ-0001`, including a source-record revision and an explicit correction
  route to the receiver.
- CAI Mechanism Design `59331d0` pins `CMD-0001` to the exact received inquiry
  revision and states that later source-owner corrections require explicit
  candidate review rather than silently changing the admitted basis.

| Authority | Owner in the case | Preserved operation |
| --- | --- | --- |
| Source truth and correction | CAI Systemic Failure | Correct the inquiry and notify the receiver through a governed proposal. |
| Candidate disposition | CAI Mechanism Design | Decide whether a changed source requires revision, deferral, transfer, or another candidate action. |
| Historical basis | Both commit graphs plus the pinned hash | Preserve which source revision the receiver actually admitted. |

## Legitimacy value

The revision pin makes correction non-retroactive without making it
ineffective. The source owner retains correction authority; the receiver
retains disposition authority; and the public record retains the historical
basis of the earlier decision. This prevents cross-owner truth updates from
becoming either silent policy movement or a claim that accepted records can
never be revised.

## Limits and handoff

This is one same-system observational case, not evidence that the mechanism
improves outcomes, survives conflict, or generalizes. No participant rights,
appeal process, reviewer authority, governance policy, claim status, K1 result,
or public posture changes here.

Reopen if a pinned source is later corrected. Test whether the receiver records
an explicit review while the source owner can still correct its own truth and
the old admitted basis remains reconstructible.
