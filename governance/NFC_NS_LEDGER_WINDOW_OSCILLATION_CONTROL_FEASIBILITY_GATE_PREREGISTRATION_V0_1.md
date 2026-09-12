# NFC NS Ledger Window Oscillation Control Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 7ff4161e4c3523facc3ea726b06eb4570c4bb653
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
Does the existing UWB-conditioned finite-state/isometry window architecture lawfully bound the local oscillation of the visible ledger D on successor-window supports, or is a further theorem needed to make D a function of the finite window state/transition?

## Candidate routes
O1 finite-state descent: prove D_j (and needed loss/renewal channels) are quotient-visible functions of the canonical late-tail window configuration and/or deterministic transition edge. Under UWB finite state, their ranges are then finite and a legitimate ceiling/oscillation bound follows.
O2 direct boundary-counting bound from K0 and K_*.
O3 recurrence-relative bound from SCT.6b/H1-H3.
O4 positive averaging weight-floor bound: if a uniform positive minimum normalized weight is certified, max D on a window is bounded by average D divided by that floor.
O5 reintroduce the old generic absolute ceiling M.
O6 no useful control.

## Mandatory tests
- distinguish finite geometry from finite ledger range;
- no hidden historical state in D unless encoded in declared finite configuration;
- internal and boundary ledger components both covered;
- UWB remains explicit conditional scope, not proved;
- any weight floor must be proved, not inferred from positivity at each step;
- the withdrawn generic M may not be reused;
- a derived finite-range ceiling for D is allowed only if D descends to a finite state/edge;
- no mathfrakD or obstruction comparison yet;
- no endpoint claim.

## Outcomes
A__LEDGER_OSCILLATION_BOUND_DERIVABLE_UNDER_UWB_FROM_CURRENT_CANON
B__FINITE_WINDOW_STATE_EXISTS__LEDGER_STATE_DESCENT_THEOREM_MISSING
C__RECURRENCE_RELATIVE_CONTROL_SUFFICES_WITHOUT_FINITE_STATE_DESCENT
D__NO_VIABLE_OSCILLATION_CONTROL_ROUTE
E__REPAIR_REQUIRED
F__UNDERDETERMINED

## Stop rule
Do not infer a bounded ledger merely because the collar-labelled geometry has finitely many states. The ledger must first be proved to descend to that state or transition data.