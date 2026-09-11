# NFC Matched Observation-Coupled Actualization Candidate Pair — Independent Acceptance v0.1

STATUS = ACCEPTED__OUTCOME_A__FINITE_HORIZON_PAIR_WELL_FORMED__PROJECTIVE_CONSISTENCY_OPEN

EXECUTION_COMMIT = `acbafd13e632f65ed4be01ad34ce84bb4cc6e806`

PREREGISTRATION_COMMIT = `8880decf18a99a09beae19aa08d95180974b60b6`

DESIGN_SPACE_ACCEPTANCE_COMMIT = `1ba1e24b2fd5f5ceabee3c315f30b8e8b219438a`

FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Acceptance decision

`PRIMARY_OUTCOME_ACCEPTED = A__MATCHED_PAIR_WELL_FORMED_AND_THEORETICALLY_DISCRIMINABLE`

`OUTCOME_CORRECTION_REQUIRED = NO`

with qualification:

`FUNDAMENTAL_PROMOTION_BLOCKED_BY_PROJECTIVE_CONSISTENCY_FRONTIER = YES`

## Preregistration compliance

PASS.

The execution uses the same post-observation domain, horizon, quotient structure, defect ledger, hidden-state policy, preparation policy, and readout assumptions for both candidates. It explicitly charges the deterministic argmin rule and stochastic `2^{-Delta}` weighting rule as new physical content.

## Constructive discriminability check

PASS.

The explicit two-step continuation tree is a lawful Book-I-style refinement pattern and produces a unique minimum-defect history plus two higher-defect lawful histories. Therefore the deterministic candidate assigns zero support where the stochastic candidate assigns positive support.

This proves mathematical/theoretical discriminability. It does not establish an empirical preparation protocol.

## Anti-inversion check

PASS.

Both candidates act on quotient-visible continuation histories rather than hidden representatives inside a quotient class. No inverse selector on observationally equivalent tokens is used.

## Authority check

PASS AS AN EXPLICIT NEW-PHYSICS CONSTRUCTION.

The execution does not misstate the frozen defect ledger as an actualization theorem. Book I treats survivor/defect bookkeeping as combinatorial at the source stage. The physical statements

- `minimum Delta is actual`, and
- `probability is proportional to 2^{-Delta}`

are correctly labeled as candidate postulates.

## Deterministic degeneracy check

SUSTAINED.

`D_OBS_DELTA` is undefined on tied minima. This is scientifically preferable to hidden tie-breaking, but the prevalence of ties is unknown and may become a decisive weakness.

## Stochastic uniqueness check

SUSTAINED.

Nothing in frozen NFC uniquely forces the exponential base-2 weighting. Other monotone weightings remain conservative candidate alternatives. Therefore `S_OBS_DELTA` is a representative K2 law, not a derived probability theorem.

## Horizon/projective-consistency check

OPEN AND LOAD-BEARING.

The execution correctly notes that finite-horizon normalization does not automatically yield a coherent measure on nested horizons and that deterministic minimum-defect prefixes can change when the horizon is extended.

A new canonical clue was independently checked during acceptance: Book II proves Binary Rigidity under B-stable compression and toggle-admissible continuation, and separately rules out stable pure `k`-merges with `k >= 3` in the WL-1 single-edge regime.

This clue is important but does **not** yet solve the candidate problem. The Book-II results are stated for stable compression fibers / merge operations. The candidate law is defined on Book-I continuation-history branching. No frozen theorem was identified that directly proves:

`every relevant continuation node has exactly one or two descendant history classes`.

Therefore lifting Binary Rigidity to the candidate continuation tree would itself require proof.

## Why the binary route matters

If a future theorem establishes that every relevant continuation node has branching number `k in {1,2}`, then for the stochastic local defect factor

`w(k) = 2^{-(k-1)}`

one has

`k * w(k) = 1`

for both `k=1` and `k=2`.

Equivalently:

- unary continuation contributes total child weight `1`;
- binary continuation contributes `2 * 2^{-1} = 1`.

Under a properly factorized tree law, this is exactly the algebraic identity needed for local mass conservation across refinement levels. It therefore creates a plausible route to an `L`-independent projective measure based on the existing defect count.

For `k >= 3`, however,

`k * 2^{-(k-1)} < 1`,

so the same simple rule loses mass unless additional normalization is inserted. That would reintroduce horizon/node dependence or new structure.

This makes the binary-lift question highly informative.

## Scope guardrail

The acceptance does not claim:

- Binary Rigidity governs all Book-I history branching;
- `2^{-Delta}` is source-forced probability;
- observation is physically special;
- a global infinite-history measure exists;
- either candidate is empirically supported.

## Accepted routing

`FINITE_HORIZON_PAIR = ACCEPTED_AS_RESEARCH_CANDIDATE`

`THEORETICAL_DISCRIMINABILITY = ACCEPTED`

`EMPIRICAL_PILOT = NOT_AUTHORIZED`

`FUNDAMENTAL_ACTUALIZER = NOT_ESTABLISHED`

`BINARY_RIGIDITY_LIFT = UNPROVED__HIGH_VALUE_TARGET`

`NEXT_OPERATION = NFC_BINARY_CONTINUATION_DEFECT_MEASURE_PROJECTIVE_CONSISTENCY_AUDIT_V0_1`

The next audit should test, without assuming the answer, whether the Book-II binary-rigidity / binary-stability results can lawfully constrain the Book-I continuation-history branching relevant to `Delta`; if they can, it should then prove or refute projective consistency of the `2^{-Delta}` cylinder weights. It must separately audit the deterministic argmin law, which does not gain consistency merely from stochastic mass conservation.