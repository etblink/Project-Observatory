# NFC NS Ledger Envelope Evolution Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 2ce6ae394db62a5b1fb348b372244c1f0da2c722
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Question
Does the current reconditioned Book-II/NS visible-ledger architecture imply a closed decay or finite-extinction law for the auxiliary support supremum M_k of the visible ledger, sufficient to make the successor-window discrepancy remainder summable or absorbable?

## Starting structure
Under the separately hypothetical total-renewal discharge, the frozen NS branch records a visible-ledger recurrence of the form

D_{n+1} <= D_n - (1-eta_tilde) Phi_n,

with D_n>=0 and Phi_n>=0.

For the window discrepancy state

M_k := max{D_j : j in supp(mu_{k+1}) union supp(S mu_k)},

we already have

|Delta_k^win(D)| <= TV(mu_{k+1},S mu_k) M_k.

## Candidate routes
E1 MONOTONICITY ONLY: D_{n+1}<=D_n implies a nonincreasing envelope over forward-moving windows, but not decay.

E2 PROPORTIONAL LOSS ON D: if Phi_n >= c_D D_n with c_D>0, then D_{n+1} <= q_D D_n, q_D=1-(1-eta_tilde)c_D<1, yielding geometric envelope decay or finite extinction.

E3 H1/H2 DIRECTLY SUPPLY E2 in current canon.

E4 H1/H2 LOWER BOUNDS ARE AGAINST mathfrakD, so E2 requires the still-missing ledger-state realization/comparison.

E5 SCT.6b generic doctrine supplies a D-side lower comparison independent of the NS branch realization.

E6 FINITE-STATE/UWB alone yields envelope decay.

## Mandatory tests
1. Use the MIG-052 reconditioned typing, not superseded alpha/IDC shortcuts.
2. Do not move H1/H2 inequalities between D and mathfrakD without an explicit map.
3. Nonincrease must not be called contraction.
4. Forward-window ordering must be stated if used.
5. Finite-extinction and geometric cases must remain separate.
6. A summable discrepancy conclusion requires quantitative envelope decay, not only boundedness.

## Outcomes
A GEOMETRIC_OR_EXTINCTION_ENVELOPE_DECAY_DERIVED
B ENVELOPE_NONINCREASE_DERIVED__PROPORTIONAL_LOSS_BRIDGE_MISSING
C CONDITIONAL_ENVELOPE_DECAY_SCHEMA_EXISTS__LEDGER_STATE_COMPARISON_REQUIRED
D NO_USEFUL_ENVELOPE_EVOLUTION
E REPAIR_REQUIRED
F UNDERDETERMINED

No source-project mutation.