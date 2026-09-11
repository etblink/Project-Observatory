# NFC Matched Observation-Coupled Actualization Candidate Pair — Preregistration v0.1

STATUS = PREREGISTERED__CANDIDATES_NOT_YET_CONSTRUCTED

DESIGN_SPACE_ACCEPTANCE_COMMIT = `1ba1e24b2fd5f5ceabee3c315f30b8e8b219438a`

DESIGN_SPACE_EXECUTION_COMMIT = `8f1af647388f443a493352af2eda2828060f6805`

FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Purpose

Construct the smallest matched deterministic and genuinely stochastic **research candidates** on the same NFC-visible post-observation continuation domain.

This operation does not claim either candidate is true, canonical, source-forced, empirically supported, or ready for experiment.

## Scoped pilot regime

The candidates are intentionally finite and scoped.

Let `Z` denote a quotient-visible post-observation/post-probe state carrying a certified record of the observation-linked transition.

For a declared finite horizon `L >= 1`, let

`H_L(Z)`

be the finite set of lawful quotient-visible continuation histories of length `L` beginning at `Z` under the declared admissible continuation class.

The candidate pair acts only on `H_L(Z)`. No token-level identity, hidden representative, unlicensed inverse quotient map, or primitive external coordinate may enter.

## Shared structural quantity

For each `h in H_L(Z)`, define the frozen-source structural burden

`Delta_L(h)`

as the cumulative NFC defect ledger weight along the declared continuation segment. This uses the frozen Book-I defect ledger as bookkeeping only.

The preregistration explicitly records:

`DELTA_ACTUALIZATION_AUTHORITY_IN_FROZEN_NFC = NO`

The candidates below add new physical content by assigning actualization significance to `Delta_L`; that significance is not claimed to be derived from the frozen source.

## Equal-auxiliary contract

Both candidates must share exactly the following unless an unavoidable class difference is explicitly declared:

1. the same post-observation state `Z`;
2. the same horizon `L`;
3. the same lawful history domain `H_L(Z)`;
4. the same quotient/equivalence structure;
5. the same defect function `Delta_L(h)`;
6. the same observation/probe schedule;
7. the same hidden-state policy: none beyond quotient-visible declared structure;
8. the same initial/boundary policy;
9. the same branch/scope declaration;
10. the same intervention/preparation policy;
11. the same empirical readout map;
12. the same failure and non-identifiability rules.

Any asymmetry beyond the actualization rule must be declared and charged.

## Candidate D — deterministic minimum-defect actualizer

Working name:

`D_OBS_DELTA`

Candidate law:

For `H_L(Z)`, if there exists a **unique** history

`h_* = argmin_{h in H_L(Z)} Delta_L(h)`,

then the actualization measure is

`A_Z^D = delta_{h_*}`.

If the minimum is not unique, the candidate returns

`D_TIE_FAILURE`

and makes no hidden tie-breaking choice.

The tie failure is mandatory. A secret ordering, representative label, random seed, branch preference, or future auxiliary may not be inserted after the fact.

## Candidate S — genuinely stochastic defect-weighted actualizer

Working name:

`S_OBS_DELTA`

Candidate law:

For finite nonempty `H_L(Z)`, define

`A_Z^S(h) = 2^{-Delta_L(h)} / sum_{g in H_L(Z)} 2^{-Delta_L(g)}`.

This is parameter-free at the candidate level because `Delta_L` is a nonnegative integer ledger and the weighting convention is fixed before evaluation.

The factor `2^{-Delta}` is **new physical content**. Its use is not claimed to follow from the frozen ledger/entropy theorem.

If `|H_L(Z)| >= 2`, the candidate is genuinely stochastic because every lawful finite-defect history receives strictly positive probability.

## Why these two forms are paired

Both candidates use identical domain and structural burden.

The only intended physical difference is:

- `D_OBS_DELTA`: actualization is unique-minimum force;
- `S_OBS_DELTA`: actualization is nontrivial normalized weighting.

This pair directly instantiates the accepted K1/K2 parity while minimizing auxiliary asymmetry.

## Mandatory objections

### O1 — Authority objection

The audit must explicitly state that neither law is source-forced. The purpose is candidate construction under admitted new physics.

### O2 — Horizon objection

The candidates depend on finite horizon `L`. The audit must determine whether changing `L` can change predictions. If so, `L` is a substantive auxiliary and must not be hidden.

### O3 — Global/future-dependence objection

Because `Delta_L(h)` scores a continuation segment, the candidates may be nonlocal in history/future-dependent. This must be treated as a real physical cost, not editorially minimized.

### O4 — Degeneracy objection

`D_OBS_DELTA` may often fail due to tied minima. Frequency of tie failure is itself a candidate weakness.

### O5 — Weighting objection

`2^{-Delta}` is not derived from frozen NFC. The audit must treat alternative monotone weights as rival stochastic candidates, demonstrating that this specific S-law is not uniquely licensed.

### O6 — Observation-trigger objection

The use of post-observation `Z` as the trigger is a research-design choice motivated by NFC-native interaction machinery, not a source theorem that observation causes actualization.

## Theoretical discriminability gate

The pair passes theoretical discriminability only if there exists at least one admissible pilot configuration with:

1. `|H_L(Z)| >= 2`;
2. a unique minimum-defect history `h_*`;
3. at least one higher-defect lawful history `h_1`;
4. a declared observable readout that can distinguish `h_*` from at least one history with positive `A_Z^S` weight.

Then

`A_Z^D(h_1) = 0`

while

`A_Z^S(h_1) > 0`,

so the candidates are theoretically distinguishable.

If no such pilot configuration can be constructed from the frozen observable grammar, the pair is non-identifiable and must not advance.

## Outcome taxonomy

A. `MATCHED_PAIR_WELL_FORMED_AND_THEORETICALLY_DISCRIMINABLE`

B. `MATCHED_PAIR_WELL_FORMED_BUT_NOT_YET_THEORETICALLY_DISCRIMINABLE`

C. `DETERMINISTIC_CANDIDATE_FAILS_DEGENERACY_OR_CONSISTENCY_GATE`

D. `STOCHASTIC_CANDIDATE_FAILS_NORMALIZATION_OR_CONSISTENCY_GATE`

E. `BOTH_CANDIDATES_REVEAL_UNACCEPTABLE_HIDDEN_AUXILIARIES`

F. `REPAIR_REQUIRED`

## Stop condition

Even Outcome A authorizes no experiment and no NFC mutation.

A separate operation would be required to identify or construct an actual NFC-visible pilot system, bind preparation/readout rules, and assess whether repeated observations could discriminate the candidates.
