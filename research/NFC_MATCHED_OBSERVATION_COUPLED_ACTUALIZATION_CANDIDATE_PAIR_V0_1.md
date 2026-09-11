# NFC Matched Observation-Coupled Actualization Candidate Pair v0.1

STATUS = EXECUTED__OUTCOME_A__MATCHED_PAIR_WELL_FORMED_AND_THEORETICALLY_DISCRIMINABLE__HORIZON_DEPENDENCE_OPEN

PREREGISTRATION_COMMIT = `8880decf18a99a09beae19aa08d95180974b60b6`

DESIGN_SPACE_ACCEPTANCE_COMMIT = `1ba1e24b2fd5f5ceabee3c315f30b8e8b219438a`

FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`PRIMARY_OUTCOME = A__MATCHED_PAIR_WELL_FORMED_AND_THEORETICALLY_DISCRIMINABLE`

with mandatory qualifier:

`HORIZON_AND_SEQUENTIAL_CONSISTENCY = OPEN__NOT_YET_SATISFIED_FOR_FUNDAMENTAL_PROMOTION`

The pair is valid as a finite-horizon research construction. It is not yet a viable fundamental actualization law.

## Frozen-source basis used

Book I defines:

- licensed internal tests and observational equivalence;
- quotient-visible canonical content;
- survivor chains as class-level persistence;
- one-step defect `delta(C_n)` as descendant multiplicity minus one;
- cumulative defect ledger `Delta` as the sum of one-step defects;
- the defect-ledger history preorder.

Book I explicitly states that survivor/defect objects are purely combinatorial at that stage and carry no dynamical or physical interpretation. Therefore assigning actualization force below is admitted **new physical content**.

## Candidate domain

Let `Z` be a quotient-visible post-observation/post-probe class carrying a certified persistent record.

Fix a finite horizon `L >= 1`.

Let `H_L(Z)` be the finite set of lawful quotient-visible continuation histories of length `L` from `Z`.

For each `h in H_L(Z)`, let `Delta_L(h)` be the cumulative Book-I defect ledger burden along that finite continuation.

No token-level representative, inverse quotient selector, primitive coordinate, or hidden label is used.

## Candidate D_OBS_DELTA

If

`argmin_{h in H_L(Z)} Delta_L(h)`

contains exactly one history `h_*`, define

`A_Z^D = delta_{h_*}`.

If the minimum is degenerate, return

`D_TIE_FAILURE`.

No hidden tie-breaker is allowed.

### New-physics content

The new postulate is:

> Among lawful post-observation continuation histories on the declared finite horizon, the unique minimum cumulative-defect history is physically actual.

Frozen NFC does not authorize this postulate.

## Candidate S_OBS_DELTA

For each `h in H_L(Z)`, define

`A_Z^S(h) = 2^{-Delta_L(h)} / N_Z`,

where

`N_Z = sum_{g in H_L(Z)} 2^{-Delta_L(g)}`.

Because `H_L(Z)` is finite and every weight is strictly positive, normalization exists and is unique.

If `|H_L(Z)| >= 2`, the law is genuinely stochastic.

### New-physics content

The new postulate is:

> Among lawful post-observation continuation histories on the declared finite horizon, physical actualization probability is proportional to `2^{-Delta}`.

Frozen NFC does not authorize this weighting rule.

## Equal-auxiliary audit

PASS.

Both candidates use the same:

- post-observation state `Z`;
- horizon `L`;
- continuation set `H_L(Z)`;
- quotient structure;
- defect ledger;
- observation trigger;
- hidden-state policy;
- boundary/initial policy;
- intervention/preparation policy;
- readout map;
- scope.

The unavoidable class difference is exactly the actualization map: Dirac support on a unique minimizer versus nontrivial normalized support.

## Constructive theoretical-discriminability witness

A legal finite refinement pattern exists with the following class structure.

At the post-observation class `Z = C_0`:

`delta(C_0) = 1`,

so `C_0` has exactly two descendants at the first continuation stage:

`C_1^a` and `C_1^b`.

At the second stage, let:

`delta(C_1^a) = 0`,

so `C_1^a` has a unique descendant `C_2^a`, while

`delta(C_1^b) = 1`,

so `C_1^b` has two descendants `C_2^{b1}`, `C_2^{b2}`.

For horizon `L = 2`, the three lawful continuation histories are:

- `h_a: C_0 -> C_1^a -> C_2^a`, with `Delta_2(h_a) = 1`;
- `h_b1: C_0 -> C_1^b -> C_2^{b1}`, with `Delta_2(h_b1) = 2`;
- `h_b2: C_0 -> C_1^b -> C_2^{b2}`, with `Delta_2(h_b2) = 2`.

The deterministic candidate gives:

`A_Z^D(h_a) = 1`,

`A_Z^D(h_b1) = A_Z^D(h_b2) = 0`.

The stochastic candidate gives raw weights:

- `2^{-1} = 1/2` for `h_a`;
- `2^{-2} = 1/4` for `h_b1`;
- `2^{-2} = 1/4` for `h_b2`.

The normalization is exactly `1`, so:

`A_Z^S = (1/2, 1/4, 1/4)`.

Thus the pair is mathematically distinguishable without raw-label inversion.

If the horizon-end classes are separated by a licensed observable readout, repeated reproducible preparations of the same `Z` would in principle generate different predicted outcome frequencies.

This establishes theoretical discriminability only. No such empirical preparation/readout protocol is presently bound.

## Anti-inversion check

PASS.

Both candidates act on lawful quotient-visible history classes. Neither attempts to recover which presentation-level representative inside an observational equivalence class was 'really' present.

The deterministic candidate chooses among distinct lawful history classes, not among quotient-identical hidden representatives.

## Authority objection

SUSTAINED AND EXPLICIT.

Neither candidate is source-forced.

`DELTA_IS_STRUCTURAL_BOOKKEEPER = YES`

`DELTA_HAS_FROZEN_ACTUALIZATION_AUTHORITY = NO`

`D_ARGMIN_AUTHORITY = NEW_PHYSICAL_POSTULATE`

`S_WEIGHTING_AUTHORITY = NEW_PHYSICAL_POSTULATE`

This operation tests candidate form, not derivation.

## Deterministic degeneracy objection

REAL.

The D-law fails whenever more than one history shares the minimum cumulative defect.

No evidence currently establishes that unique minima are generic, common, or physically privileged.

Therefore:

`D_TIE_FAILURE_RATE = UNKNOWN`

A high tie rate could make the deterministic candidate practically or fundamentally unusable.

## Stochastic weighting objection

REAL.

The specific law `2^{-Delta}` is not uniquely motivated by the frozen source. Alternatives such as other monotone functions of `Delta` would generally produce different probabilities while preserving the same frozen NFC truths.

Therefore:

`S_WEIGHTING_UNIQUENESS = NO`

The candidate is useful as a minimal representative of K2, not as a derived probability law.

## Horizon dependence objection

SUSTAINED; THIS IS THE MAIN NEW FRONTIER.

Both candidates are defined relative to finite horizon `L`.

Changing `L` can change:

- which histories exist;
- cumulative defect burdens;
- whether the D-minimum is unique;
- the S-normalization constant;
- marginal probabilities assigned to shorter prefixes.

Therefore the pair is not yet horizon-invariant.

A fundamental actualization law cannot leave its physical prediction dependent on an arbitrary analysis cutoff unless that cutoff is itself physical and independently specified.

`HORIZON_IS_CURRENTLY_A_SUBSTANTIVE_AUXILIARY = YES`

## Sequential-consistency warning

For S_OBS_DELTA, finite-horizon normalization over complete histories does not automatically imply that the marginal measure on length-`L` prefixes equals the independently normalized measure constructed directly at horizon `L` from the same rule.

For D_OBS_DELTA, a history prefix that is minimum-defect at horizon `L` need not remain the prefix of the minimum-defect history at horizon `L+1`.

Therefore:

`PROJECTIVE_CONSISTENCY = NOT_PROVED`

`DYNAMIC_TIME_CONSISTENCY = NOT_PROVED`

This blocks promotion to a fundamental law.

## Observation-trigger objection

SUSTAINED AS SCOPE LABEL.

The candidates are observation-coupled because that is the most NFC-native interface currently available. Nothing here proves that physical actualization occurs only at observation, that observation is metaphysically special, or that unobserved evolution lacks actualization.

`OBSERVATION_TRIGGER = RESEARCH_DESIGN_CHOICE`

## Ten-branch compatibility

No branch corpus is modified. Since the pair is scoped as post-observation research physics and does not rewrite branch endpoint theorems, the prior ten-branch design-space compatibility result remains intact.

This candidate operation does not grant either law authority over BIO, CRYST, GR, LING, NS, RH, SCC, SM, SPEC, or YM.

## Empirical status

`EMPIRICAL_SUPPORT_D = NONE`

`EMPIRICAL_SUPPORT_S = NONE`

`EXPERIMENT_AUTHORIZED = NO`

The constructive refinement tree is a mathematical witness of discriminability, not empirical evidence.

## Main result

The matched-pair program has succeeded at one level and exposed a more precise failure at the next.

Success:

- deterministic and stochastic candidate laws can be written on exactly the same NFC-visible domain;
- neither needs hidden quotient inversion;
- they make different predictions on an explicit lawful finite refinement pattern.

Failure/frontier:

- neither law has source authority;
- the deterministic law has tie degeneracy;
- the stochastic law has weighting nonuniqueness;
- both depend on finite horizon;
- sequential/projective consistency is unproved.

## Routing

`PAIR_CONSTRUCTION = PASS`

`THEORETICAL_DISCRIMINABILITY = PASS`

`FUNDAMENTAL_LAW_READINESS = FAIL`

`EMPIRICAL_PILOT_READINESS = FAIL`

`NEXT_OPERATION = NFC_ACTUALIZATION_HORIZON_AND_PROJECTIVE_CONSISTENCY_AUDIT_V0_1`

The next audit should test whether either candidate admits an `L`-independent or projectively consistent extension over nested history horizons without adding hidden choice, divergent normalization, or a new arbitrary measure.