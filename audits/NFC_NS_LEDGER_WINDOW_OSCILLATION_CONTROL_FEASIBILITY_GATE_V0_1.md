# NFC NS Ledger Window Oscillation Control Feasibility Gate v0.1

PREREGISTRATION: 8b0f19381854da5c1006834be5f2ab125e7284a3
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Outcome
B__FINITE_WINDOW_STATE_EXISTS__LEDGER_STATE_DESCENT_THEOREM_MISSING

## Evidence adjudication
Under UWB, the frozen NS branch proves that sufficiently late collar-labelled window configurations range over a finite state space and, with deterministic transition, eventually enter a finite cycle. This is a theorem about window configurations/geometry.

The shared-core SCT doctrine separately names D_n=E_n+B_n as the visible obstruction ledger and supplies conditional loss/renewal laws. It does not explicitly prove that the numerical tuple (D_n,E_n,B_n,Phi_n,Psi_n) is a function solely of the canonical window configuration or deterministic transition edge.

Therefore finite window geometry does not yet license a finite numerical range for D.

## Candidate adjudication
O1 finite-state descent — SELECTED as the minimal viable route, but the descent theorem is missing.
O2 direct K0/K_* boundary counting — INSUFFICIENT for the full visible ledger because D includes internal as well as boundary obstruction and current canon does not bound the internal ledger solely by boundary cardinality.
O3 SCT.6b recurrence-relative control — INSUFFICIENT as an oscillation theorem. Conditional net decay controls temporal evolution but does not by itself compare values sampled by two different adaptive averaging measures without a same-window value/range bridge.
O4 averaging weight-floor route — POTENTIALLY USEFUL DOWNSTREAM, but no uniform positive floor for the normalized active transport weights has been identified from the currently inspected canon; pointwise positivity would not suffice.
O5 old absolute ceiling M — REJECTED. The withdrawn route remains withdrawn.
O6 no route — TOO PESSIMISTIC.

## Minimal missing theorem
T_NS-LEDGER-CONFIG-DESCENT:
On the declared late-tail NS regime, prove that the visible ledger tuple needed by SCT and the ledger-state map is a quotient-visible function of a finite canonical state sufficient to determine the relevant transfer step. The state may be the UWB window configuration together with its deterministic transition edge if one configuration alone is insufficient.

Formally, seek a map

F_D : State_or_Edge_NS -> R_{>=0}^m

whose components recover D, E, B and whichever Phi/Psi channels are consumed, invariant under the isometries/presentation changes already certified by the window classification.

If this theorem holds under UWB, finiteness of State_or_Edge_NS immediately yields a legitimate finite range and hence a derived oscillation ceiling for each ledger component. This would be a new derived ledger bound, not the withdrawn unsourced obstruction ceiling.

## Consequence for intertwining
Conditional on T_NS-LEDGER-CONFIG-DESCENT and UWB, define

M_D := max_{s in State_or_Edge_NS} F_D^D(s),

and similarly an oscillation bound. Then

|Delta_k^win(D)| <= TV(mu_{k+1},S mu_k) * osc_k(D)

has a certified finite right-hand side. Absorbability or relative smallness would still be a later question; mere finiteness does not imply contraction.

## Next operation
NFC_NS_LEDGER_CONFIG_DESCENT_FEASIBILITY_GATE_V0_1

No mutation of frozen NFC, FCP or PGH.