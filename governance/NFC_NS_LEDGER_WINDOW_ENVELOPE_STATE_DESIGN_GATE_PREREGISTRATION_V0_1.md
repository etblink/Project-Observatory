# NFC NS Ledger Window Envelope State Design Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 11028d4c0d55b616fe0138b9b3a0702ffc524b11
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Question
What is the minimal auxiliary window-state quantity that controls the ledger oscillation term in the accepted successor-measure discrepancy bound while preserving the active transport-weighted average as the primary ledger-state map?

## Candidate auxiliary states
E1 SUPPORT SUPREMUM:
M_k := max{D_j : j in supp(mu_{k+1}) union supp(S mu_k)}.
Since D_j >=0, osc_k(D) <= M_k.

E2 SUPPORT RANGE:
R_k := max D_j - min D_j. Exact for the discrepancy but carries two extrema and no simpler obvious evolution law.

E3 TOTAL VARIATION OF LEDGER VALUES:
V_k := sum |D_{j+1}-D_j| on the combined support. Stronger than needed and sensitive to support ordering.

E4 ENDPOINT PAIR:
(D_left,D_right) on a monotone tail. Minimal only if monotonicity and contiguous ordered support are already established for every compared window.

E5 BLOCK MAXIMUM OVER A PERIOD:
maximum over one eventual-periodic geometry block. Requires choosing/knowing the period and does not help before periodic entry.

E6 NO AUXILIARY STATE.

## Mandatory tests
1. Auxiliary state may bound the discrepancy but may not replace the additive weighted average as the primary map.
2. No absolute universal ceiling is assumed; the envelope is dynamic state data.
3. Representation invariance: definitions use ledger values and declared window supports, not presentation labels.
4. Successor evolution must remain separately proved.
5. Finite extinction must be handled separately from geometric decay.
6. No use of endpoint regularity or obstruction contraction to prove the state needed to derive them.

## Outcomes
A SUPPORT_SUPREMUM_IS_MINIMAL_AUXILIARY_STATE
B SUPPORT_RANGE_IS_MINIMAL
C TWO_COMPONENT_ENVELOPE_REQUIRED
D NO_USEFUL_AUXILIARY_STATE
E REPAIR_REQUIRED
F UNDERDETERMINED

## Downstream target
With M_k accepted, the intertwining remainder satisfies

|Delta_k^win(D)| <= TV(mu_{k+1},S mu_k) M_k.

The next feasibility gate should ask whether the conditional pointwise Book-II visible-ledger evolution implies a closed recurrence/decay law for M_k over the forward-moving active window family.

No source-project mutation.