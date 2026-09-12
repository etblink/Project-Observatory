# NFC NS Normalized Window Weight Floor Feasibility Gate v0.1

PREREGISTRATION: 35895723c1884fa43cb29ede0567e3ad042cb84e
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Outcome
B__CONDITIONAL_WEIGHT_FLOOR_SCHEMA_EXISTS__WEIGHT_STATE_DETERMINATION_BRIDGE_MISSING

## Frozen-source findings
The active NS weight is determined from cumulative Book-III transport factors, schematically omega_j from products of Theta_i. Frozen Book III certifies only Theta_i in [0,1]. No positive lower bound Theta_i >= theta_min >0 is available.

The UWB theorem, by contrast, makes the collar-labelled window-configuration state space finite and—together with deterministic window transition—eventually periodic. It does not say that the numerical normalized weight measure is a function of that finite state.

The later positive contraction-factor domain concerns the net route-conditional factor q = 1-(1-eta_tilde)(c1+c2), not every raw Theta_i or every normalized atom of the active averaging measure. Those objects may not be conflated.

## Candidate adjudication
W1 finite window cardinality alone — REJECTED. A probability vector on at most K atoms may contain arbitrarily small positive atoms.

W2 finite-state/eventual-periodic geometry plus state-determined weights — CONDITIONAL / SUFFICIENT. If there exists a representation-invariant map

    OmegaWeight : window_state -> normalized positive measure mu

so that every late active mu_k is OmegaWeight(s_k), then the finite eventual cycle supplies only finitely many normalized measures. The minimum of all positive atom masses over that finite family is a uniform p_*>0.

W3 raw Theta lower bound — NOT PRESENT IN FROZEN CANON and stronger than necessary.

W4 positive net contraction-factor/noncollapse — REJECTED AS SUPPORT for the weight floor. It concerns different typed quantities.

W5 positive-support minimum from finitely recurring normalized measures — DERIVED once W2's state-determination bridge is supplied.

W6 periodic/block route — REMAINS AVAILABLE but does not dominate yet; it would still need numerical control of the weight measures or an exact block identity.

## Conditional consequence
Assume T_NS-WEIGHT-STATE-DETERMINATION and UWB/eventual periodicity. Let p_*>0 be the minimum nonzero atom mass over the finite recurring normalized measures. For any nonnegative D on the support,

max D <= A_mu(D)/p_*.

If the late-tail ledger is nonincreasing under the separately conditional renewal-control route, then on any finite successor-window union

osc(D) <= max D <= const * A(D),

with the exact constant depending only on the finite family of normalized measures and the comparison between the two relevant supports. This is a relative, not absolute, oscillation bound.

## Why the bridge is not already proved
Frozen window determinism states that the next collar-labelled window configuration is determined by the current window configuration plus the declared finite transport/defect update rule. The active averaging weights, however, are defined from cumulative transport-factor history. No frozen theorem identifies normalized weight values with the collar-labelled state or proves that repeated/isometric window states carry the same normalized measure.

## Sharpened missing theorem
T_NS-WEIGHT-STATE-DETERMINATION:
On the late NS safe tail, prove that the normalized active transport-weight measure used by the window averaging operator is a representation-invariant function of the finite canonical window state (or of a finite augmentation of that state already determined by frozen data), so that eventual periodicity of state implies eventual periodicity of normalized measures.

No absolute obstruction ceiling is introduced.

## Next operation
NFC_NS_WEIGHT_STATE_DETERMINATION_FEASIBILITY_GATE_V0_1

This gate should test whether the declared finite transport/defect update rule already contains enough data to augment the finite state by the relative transport factors needed to determine normalized window weights, without importing a continuous/unbounded memory variable.

No mutation of frozen NFC, FCP or PGH.