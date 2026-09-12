# NFC NS Same-State Obstruction Comparison Design Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: f4562a10f3fedaa420340df8e1864a38592d7e4d
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Question
What is the weakest noncircular architecture capable of supporting the frozen burden-(d) comparison

a mathfrakD_k <= O_NS(W_k) <= b mathfrakD_k + rho_k,

with rho_k absorbable by mathfrakD_k, now that the stock/increment error has been isolated and a candidate typed ledger state exists?

## Frozen algebraic identity to test
Book III defines C_n = B_n^bulk - I_n. The NS obstruction is

O_NS(W_k) = Avg^tr_{W_k}(B_n^bulk - C_n - (E_n+B_n)).

Pure substitution therefore gives the correctly typed formal identity

O_NS(W_k) = Avg^tr_{W_k}(I_n - E_n - B_n),

where I_n is the stage-level interface burden and E_n,B_n are Book-III step defect increments. This algebra does NOT identify I_n with any increment and does NOT identify E_n/B_n with the Book-II visible ledger channels.

## Candidate architectures
C1 DIRECT COMPARISON PREMISE: postulate the frozen two-sided comparison itself. Sufficient but potentially hides all mechanism.

C2 THREE-COMPONENT COMMON STATE:
X_k := (A_k(I), A_k(E+B), mathfrakD_k),
O_k = A_k(I)-A_k(E+B),
then prove separate comparisons tying A_k(I) and A_k(E+B) to mathfrakD_k.

C3 NET-STOCK RESERVE:
prove constants r_I>r_E>=0 such that
A_k(I) >= r_I mathfrakD_k,
A_k(E+B) <= r_E mathfrakD_k,
which gives a lower comparison O_k >= (r_I-r_E)mathfrakD_k; obtain a separate upper stock bound for O.

C4 ABSOLUTE-VALUE/CONE COMPARISON:
prove
|A_k(I)-A_k(E+B)| comparable to mathfrakD_k,
without independently comparing its terms.

C5 ACTIVE-LOAD + SUCCESSOR-DEFECT REALIZATION:
use the accepted conditional active-load bridge for I and the candidate successor-defect realization for the visible ledger to derive C2/C3, if an explicit crosswalk between Book-III E+B and the realized visible ledger exists.

C6 REINTRODUCE alpha I=Bcal or an absolute obstruction ceiling — FORBIDDEN CONTROL.

C7 DIRECT CLOSED RECURRENCE FOR O instead of two-sided comparison — separate frozen alternative route; compare information cost honestly.

## Mandatory tests
1. Preserve stock/increment typing: I_n is level stock; E_n/B_n are step increments.
2. Preserve Book-II / Book-III channel distinction unless a bridge is proved.
3. O_NS is not assumed nonnegative unless its frozen regime/definition guarantees it.
4. Lower comparison requires a genuine positive reserve; subtraction can cancel.
5. Upper comparison may use an absorbable remainder but not an unsupported absolute ceiling.
6. Constants may not be chosen from the desired contraction outcome.
7. Direct-recurrence alternative may not silently reuse the comparison constants.
8. Any use of active-load or successor-defect realization must remain explicitly conditional on their new premises.

## Outcomes
A THREE_COMPONENT_COMMON_STATE_DOMINATES_AS_MINIMAL_ARCHITECTURE
B NET_STOCK_RESERVE_DOMINATES_AS_MINIMAL_ARCHITECTURE
C DIRECT_COMPARISON_PREMISE_IS_UNAVOIDABLE
D DIRECT_OBSTRUCTION_RECURRENCE_DOMINATES
E NO_COHERENT_ROUTE
F REPAIR_REQUIRED
G UNDERDETERMINED

No mutation of frozen NFC, FCP or PGH.