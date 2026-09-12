# NFC NS Weight State Determination Feasibility Gate v0.1

PREREGISTRATION: f7b8553f61931d3d56bf0673cb5161c7f879d27c
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Outcome
C__NORMALIZATION_REDUCES_HISTORY__WITHIN_WINDOW_THETA_WORD_REMAINS_UNCONTROLLED

## Derivation
Write the cumulative transport weight at stage j as

P_j = product_{i<j} Theta_i.

For a window whose earliest active index is a and for P_a>0,

P_j = P_a * product_{i=a}^{j-1} Theta_i.

After normalization over the window, the common prefactor P_a cancels. Therefore the normalized measure does not require the entire pre-window transport history; it depends only on the relative within-window Theta word and the declared window support.

This is a genuine simplification.

However UWB bounds only window/collar geometry and hence the length of the within-window word. Frozen Book III defines each Theta_i merely as a certified real multiplier in [0,1]. The current NS branch retains the gross transport factor generically in [0,1] and explicitly withdraws its identification with the net contraction ratio. No theorem makes the numerical Theta word a function of the finite collar-labelled window state or a finite-valued transport type.

Hence bounded word length does not make the normalized measures a finite family.

## Candidate adjudication
S1 collar state alone — NOT DERIVED.

S2 finite augmentation from an existing transport symbol/type — NOT IDENTIFIED IN FROZEN CANON. The deterministic window-transition theorem refers to a declared finite transport/defect update rule but concludes only uniqueness of the next collar-labelled window configuration; it does not supply a finite numerical Theta table.

S3 ratio cancellation — PARTIAL PASS. Common history cancels exactly when the window begins with positive cumulative weight, but the remaining within-window Theta word is uncontrolled numerically.

S4 eventual periodicity alone — REJECTED. Periodic geometry does not imply periodic numerical weights.

S5 continuous/history-dependent Theta remains — ACCEPTED as the conservative reading.

S6 periodic/block route — DOES NOT BY ITSELF REMOVE THE NUMERICAL-WEIGHT GAP; repeated geometry may still carry distinct weight measures.

## Zero-factor issue
If a raw Theta factor vanishes, subsequent cumulative products vanish. Frozen definitions do not provide a universal repair convention for normalized windows spanning such a zero. This reinforces that positivity/support management is additional content, not something supplied by UWB.

## Consequence
The previously identified route

finite recurring state -> finite recurring normalized measures -> p_*>0

cannot be completed from frozen canon without adding new transport-factor state content. Such a discretization/state-determination premise would be stronger than necessary and is not selected here.

## Routing
The highest-information alternative is to avoid requiring a weight floor by augmenting the window common state with a representation-invariant envelope/range functional that is directly controlled by the pointwise ledger recurrence.

NEXT_OPERATION: NFC_NS_LEDGER_WINDOW_ENVELOPE_STATE_DESIGN_GATE_V0_1

The next gate should compare max/sup envelope, total variation of ledger values, endpoint values on monotone tails, and block extrema as auxiliary state components. They may be used to control the window-discrepancy remainder but must not replace the additive weighted average as the primary ledger-state map.

## Status
PREWINDOW_HISTORY_CANCELS = YES_CONDITIONALLY_ON_POSITIVE_START_WEIGHT
FINITE_WITHIN_WINDOW_THETA_WORD = NO
WEIGHT_STATE_DETERMINATION_FROM_FROZEN_CANON = NO
UNIFORM_NORMALIZED_WEIGHT_FLOOR = NOT_DERIVED
ABSOLUTE_LEDGER_CEILING = NOT_INTRODUCED

No mutation of frozen NFC, FCP or PGH.