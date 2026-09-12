# NFC NS Window Discrepancy Absorption Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: c7012e486396fe1322a3396d232a3c5a8ca539a9
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Question
Conditional on the newly isolated common fixed-normalization realization premise, can the actual-successor-window discrepancy remainder be absorbed into the strict ledger loss margin using only existing frozen/accepted structure, or is one additional relative remainder premise required?

## Conditional recurrence
Under P_NS-SUCCESSOR-DEFECT-REALIZATION,

mathfrakD_{k+1}
<= mathfrakD_k - Phi_k + Psi_k + R_k^win,

R_k^win = gamma Delta_k^win.

The accepted finite-measure estimate gives

|R_k^win| <= gamma TV(mu_{k+1},S mu_k) M_k.

Under the separately hypothetical renewal-control route,

Psi_k <= eta_tilde Phi_k,

and H1/H2 give

Phi_k >= (c1+c2) mathfrakD_k.

## Candidate absorption routes
A1 EXACT SHIFT: mu_{k+1}=S mu_k, hence R_k^win=0.
A2 LOSS-CONTROLLED TV/OSCILLATION: derive R_k^{win,+} <= xi (Phi_k-Psi_k) with xi<1 from current geometry/ledger structure.
A3 SUMMABLE DISCREPANCY: sum_k R_k^{win,+}<infinity, sufficient for asymptotic/perturbed contraction though not necessarily per-step contraction.
A4 EVENTUAL PERIODIC/BLOCK TELESCOPING cancels discrepancies over a full geometric cycle.
A5 ENVELOPE DECAY: M_k decays fast enough that R_k is summable.
A6 EXPLICIT RELATIVE ABSORPTION PREMISE:
R_k^{win,+} <= xi (Phi_k-Psi_k), one prospectively fixed xi in [0,1).
A7 REDEFINE THE BRANCH STATE ON THE SHIFTED CURRENT MEASURE and avoid the discrepancy.
A8 NO ABSORPTION AVAILABLE.

## Mandatory adversarial tests
1. Only the positive part of R harms contraction; negative discrepancy may not be bounded symmetrically if a weaker one-sided condition suffices.
2. Do not infer exact shift from adaptive-window coherence.
3. UWB/eventual periodic geometry does not imply numerical weight periodicity after the weight-state gate.
4. Envelope M_k is only nonincreasing, not geometrically decaying.
5. A summable perturbation is weaker than per-step absorption and must not be relabeled as the latter.
6. Redefining the branch state may not silently change the frozen obstruction/window semantics.
7. Any new xi must be prospective and may not be chosen from the desired contraction outcome.
8. Finite-extinction alternative remains separate.

## Outcomes
A DISCREPANCY_ABSORPTION_DERIVED_FROM_CURRENT_STRUCTURE
B SUMMABLE_PERTURBATION_DERIVED__PER_STEP_ABSORPTION_NOT_DERIVED
C NO_ABSORPTION_DERIVED__RELATIVE_POSITIVE_REMAINDER_PREMISE_IS_MINIMAL
D SHIFTED_STATE_REFORMULATION_DOMINATES
E REPAIR_REQUIRED
F UNDERDETERMINED

No source-project mutation.