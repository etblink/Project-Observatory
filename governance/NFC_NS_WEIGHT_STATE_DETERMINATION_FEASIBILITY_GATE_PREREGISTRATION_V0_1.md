# NFC NS Weight State Determination Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 8983db172c5735b2565b251900d403e7b776961b
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Question
Does frozen NFC already determine the normalized active NS window weight measure from the finite canonical window state, perhaps after a finite lawful augmentation by quotient-visible transport data? Or does the cumulative transport-factor history carry continuous/unbounded information not captured by the finite state classification?

## Relevant frozen definitions
- Book III: Theta_n(U_n) in [0,1] is the certified fraction of C_n surviving transport.
- NS active weights are induced by cumulative products of Theta_j.
- The NS finite-state/UWB theorem classifies collar-labelled window configurations.
- The deterministic window-transition theorem assumes a declared finite transport/defect update rule, but its conclusion is only uniqueness of the next window configuration.

## Candidate routes
S1 COLLAR STATE ALONE determines every relative Theta and hence normalized weights.
S2 FINITE AUGMENTATION: add a finite quotient-visible transport symbol/type already present in the declared update rule; relative Theta values then come from a finite table.
S3 RATIO CANCELLATION: although absolute cumulative products are history-dependent, normalization within a bounded window cancels common history and depends only on the finite within-window Theta word.
S4 EVENTUAL PERIODICITY alone forces numerical weight periodicity.
S5 CONTINUOUS/HISTORY-DEPENDENT Theta remains; no finite state determination follows.
S6 PERIODIC-BLOCK route avoids individual weight-state determination.

## Mandatory tests
1. A real-valued Theta in [0,1] is not finite merely because its domain geometry is finite.
2. Normalization may cancel a common prefactor but not the relative within-window Theta sequence.
3. The phrase 'finite transport/defect update rule' may not be interpreted as a finite table of numerical Theta values unless frozen canon says so.
4. Same collar-labelled state with different C_n magnitudes/transport ratios must be admitted unless explicitly excluded.
5. No new quantization/discretization of Theta.
6. Zero factors and support changes must be handled honestly.

## Outcomes
A NORMALIZED_WEIGHT_STATE_DETERMINATION_DERIVED
B FINITE_AUGMENTATION_SUFFICES__ONE_EXISTING_TYPED_LINK_MISSING
C NORMALIZATION_REDUCES_HISTORY_BUT_WITHIN_WINDOW_THETA_WORD_REMAINS_UNCONTROLLED
D NO_FINITE_WEIGHT_STATE_DETERMINATION_FROM_FROZEN_CANON
E PERIODIC_BLOCK_ROUTE_DOMINATES
F REPAIR_REQUIRED
G UNDERDETERMINED

No source-project mutation.