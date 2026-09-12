# NFC NS Successor Defect Realization Premise Minimality Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: cadc571ed3ed9176c56faab79090389eac1d75de
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Question
What is the weakest explicit new realization premise that is sufficient—not merely suggestive—to transport the accepted active-window Book-II ledger recurrence and its loss/renewal channels into the NS successor-defect state mathfrakD without violating the MIG-052 type firewall or manufacturing contraction by normalization?

## Objects
Let
A_k(D), A_k(Phi^quot), A_k(Phi^mix), A_k(Psi)
be the accepted active transport-weighted aggregates of the visible ledger and its declared loss/renewal channels.

The branch consumes the same-state tuple
(mathfrakD_k, Phi_k^quot, Phi_k^mix, Psi_k)
inside the conditional contraction proof.

## Candidate premises
P1 EXACT TOTAL ONLY:
mathfrakD_k = A_k(D), leaving channel realization unspecified.

P2 EXACT COMPONENTWISE:
mathfrakD_k = A_k(D), Phi_k^q=A_k(Phi^q), Phi_k^m=A_k(Phi^m), Psi_k=A_k(Psi).

P3 COMMON FIXED POSITIVE NORMALIZATION:
there exists one prospectively fixed gamma>0 such that for all late k,
mathfrakD_k = gamma A_k(D),
Phi_k^q = gamma A_k(Phi^q),
Phi_k^m = gamma A_k(Phi^m),
Psi_k = gamma A_k(Psi),
with the same gamma for every channel and step.

P4 UNIFORM TWO-SIDED TOTAL COMPARISON:
alpha A_k(D)<=mathfrakD_k<=beta A_k(D), with no channel map.

P5 CHANNELWISE BI-LIPSCHITZ COMPARISON:
uniform two-sided comparisons for D, Phi^q, Phi^m, Psi, possibly with different constants.

P6 VARIABLE COMMON NORMALIZATION gamma_k>0 with controlled ratios gamma_{k+1}/gamma_k.

P7 ONE-SIDED COMPARISON ONLY.

## Sufficiency tests
1. Recurrence preservation: transfer the aggregated recurrence including the window discrepancy into a correctly indexed mathfrakD recurrence.
2. Channel preservation: H1/H2 lower bounds and renewal upper bound must remain on the same realized state.
3. Additivity: Phi=Phi^q+Phi^m and loss-vs-renewal signs must be preserved.
4. Nonnegativity.
5. Normalization cannot be selected to force q<1.
6. The geometric vs finite-extinction split must remain intact.
7. Window-discrepancy remainder must transform explicitly.
8. Internal/boundary naming may not be used as evidence unless an explicit channel map is part of the premise.

## Outcomes
A EXACT_COMPONENTWISE_REALIZATION_IS_MINIMAL_SUFFICIENT
B COMMON_FIXED_POSITIVE_NORMALIZATION_IS_MINIMAL_SUFFICIENT
C CHANNELWISE_BILIPSCHITZ_REALIZATION_IS_MINIMAL_SUFFICIENT
D VARIABLE_NORMALIZATION_IS_REQUIRED
E NO_SCALAR_REALIZATION_PREMISE_IS_SUFFICIENT__RICHER_STATE_MAP_REQUIRED
F REPAIR_REQUIRED
G UNDERDETERMINED

No source-project mutation.