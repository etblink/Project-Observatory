# NFC NS Ledger Window Oscillation Control Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 7ff4161e4c3523facc3ea726b06eb4570c4bb653
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
Does the frozen NS finite-state/UWB window architecture, together with the already accepted componentwise ledger-window aggregation, imply a finite uniform bound on the local oscillation of the visible ledger values needed to control the successor-measure discrepancy? Or is a new ledger-value regularity/ceiling premise required?

## Prior accepted structure
The Ledger–Window Intertwining Feasibility Gate established an exact shifted-window identity and a discrepancy bound of the schematic form

|Err_k| <= TV(mu_{k+1}, Shift(mu_k)) * Osc_{support}(ell),

where mu_k is the active normalized window/weight measure and ell is the typed visible-ledger observable being aggregated.

The missing term is therefore a uniform bound on local ledger oscillation over the finite set of contexts actually compared by successive windows.

## Candidate routes
L1 FINITE-STATE OBSERVABLE CEILING: the UWB/finite-state classification yields only finitely many admissible window/context states, and ell is a well-defined quotient-visible observable on those states; therefore its range is finite and Osc(ell) is uniformly bounded.

L2 FINITE-STATE WINDOW GEOMETRY ONLY: the window state alphabet is finite but ell contains unbounded scalar ledger magnitudes not determined by the finite state label; no ceiling follows.

L3 BOOK-I DEFECT CAPACITY: finite quotient/collar alphabets and finite fibers directly bound each ledger component entering ell.

L4 BOOK-II BOUNDARY CAPACITY: LS-2/collar capacity bounds the boundary/interface contribution but not necessarily the full visible ledger.

L5 UCTI/COERCIVITY BOUND: existing transport/coercive inequalities supply a uniform ceiling on the ledger values used by the window map.

L6 NEW REGULARITY PREMISE REQUIRED.

## Mandatory adversarial tests
1. Finite-state-label / unbounded-value countermodel: same finite window state label with arbitrarily large scalar ledger magnitude.
2. Stage-size growth: finite local alphabet must not be confused with a uniform global count bound as U_n grows.
3. Stock/increment typing: I_n, B_n, E_n and any aggregate ledger quantity must remain distinct.
4. UWB scope: UWB may control window-boundary geometry only to the extent its frozen statement actually says so.
5. No resurrection of withdrawn absolute obstruction ceiling.
6. No endpoint or contraction assumption may be used to prove the oscillation bound consumed by contraction.
7. Conditional hypotheses must remain explicit.

## Outcomes
A FROZEN_CANON_DERIVES_UNIFORM_LEDGER_OSCILLATION_BOUND
B PARTIAL_COMPONENT_BOUNDS_EXIST__FULL_VISIBLE_LEDGER_BOUND_REQUIRES_ONE_BRIDGE
C FINITE_STATE_WINDOW_CLASSIFICATION_DOES_NOT_BOUND_LEDGER_VALUES
D NEW_LEDGER_VALUE_REGULARITY_PREMISE_REQUIRED
E REPAIR_REQUIRED
F UNDERDETERMINED

## Firewall
No mutation of NFC/FCP/PGH. No use of an absolute obstruction ceiling unless independently present and active in frozen canon. No inference from finite-state labels to bounded scalar values without an explicit quotient-visible dependence theorem.