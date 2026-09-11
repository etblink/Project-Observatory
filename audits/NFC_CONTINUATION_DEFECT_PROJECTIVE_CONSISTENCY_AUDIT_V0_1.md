# NFC Continuation-Defect Projective-Consistency Audit v0.1

STATUS = EXECUTED__OUTCOME_C__NO_SOURCE_BINARY_LIFT__INVERSE_BRANCHING_PROJECTIVE_REPAIR_EXISTS

PREREGISTRATION_COMMIT = `dc5b51dd85aae33c427e165a05fa16269b8addfa`
BASE_ACCEPTANCE_COMMIT = `be131f787346e7f559e78c564c867be4de04c001`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`PRIMARY_OUTCOME = C__NO_SOURCE_BINARY_LIFT__BASE2_NOT_GENERAL__INVERSE_BRANCHING_PROJECTIVE_REPAIR_EXISTS`

## Binary-lift adjudication

Book II's Binary Rigidity theorem is stated for non-trivial stable fibers under B-stable compression and toggle-admissible continuation. Binary Stability separately rules out stable pure `k`-merges with `k >= 3` in the WL-1 single-edge regime.

Book I's continuation defect is a different object:

`delta(C_n) = # { C_{n+1} subset C_n } - 1`,

so it counts the number of finer observational classes descending from a current class under test-family refinement.

No frozen theorem was identified equating:

- compression-fiber cardinality with refinement-child cardinality, or
- stable merge arity with continuation split arity.

Therefore:

`BOOK_II_BINARY_RIGIDITY_IMPLIES_DELTA_IN_0_1 = NOT_ESTABLISHED`

The proposed binary lift is not licensed at source level.

## Exact base-2 consistency condition

At a node `C` with `k = delta(C)+1` children, extending every prefix by one level multiplies each child cylinder by the same local factor

`2^{-delta(C)} = 2^{-(k-1)}`.

The total child mass descending from a unit-mass parent is therefore

`M(k) = k * 2^{-(k-1)}`.

Exact local mass conservation requires

`k * 2^{-(k-1)} = 1`.

For positive integer `k`, this holds exactly for:

- `k=1`: `1*1 = 1`;
- `k=2`: `2*(1/2) = 1`.

For every `k>=3`,

`k * 2^{-(k-1)} < 1`.

Therefore the unnormalized cylinder rule

`W_2(h)=2^{-Delta_L(h)}`

is projectively mass-conserving exactly on unary/binary continuation trees.

Since source-forced unary/binary continuation branching has not been proved, the original `S_OBS_DELTA` rule is not a general source-compatible projective measure.

## Conditional binary theorem

Conditional on a declared continuation-tree hypothesis

`BCH: delta(C) in {0,1} for every relevant continuation node C`,

the weights

`mu_L(h)=2^{-Delta_L(h)}`

are normalized and projectively consistent for every finite horizon.

Proof is inductive: each unary node passes its incoming mass unchanged; each binary node divides it into two children of half the mass. Therefore total mass is preserved at every level and marginalization from `L+1` to `L` returns the previous cylinder mass.

This is a valid conditional theorem but `BCH` is not presently source-forced.

## General inverse-branching repair

Book I supplies the exact child count structurally:

`k(C)=delta(C)+1`.

Define, for every child `C'` of `C`,

`p(C'|C) := 1/k(C) = 1/(delta(C)+1)`.

Then for every finite-branching node:

`sum_{C' child of C} p(C'|C) = k(C) * 1/k(C) = 1`.

For a length-`L` history

`h=(C_0,...,C_L)`, define

`mu_L(h) := product_{i=0}^{L-1} 1/(delta(C_i)+1)`.

### Normalization theorem

For every finite rooted continuation tree, `mu_L` sums to 1 over all length-`L` histories.

Proof: induction on horizon. The root has mass 1. At every node, incoming mass is partitioned among exactly `k(C)` children, each receiving `1/k(C)` of that mass. Hence outgoing child mass sums to incoming mass. Repeating level by level preserves total mass 1.

### Projective-consistency theorem

The family `{mu_L}` is projectively consistent under prefix marginalization:

for every length-`L` history prefix `h_L`,

`mu_L(h_L) = sum_{h_{L+1} extending h_L} mu_{L+1}(h_{L+1})`.

This follows from the same local identity

`sum_children 1/k(C) = 1`.

Therefore a horizon-free cylinder measure exists on the finite continuation system and, under the usual consistency construction where an infinite continuation space is well-defined, the finite-dimensional distributions possess the required projective property.

No claim about an infinite-history measure beyond the declared mathematical conditions is made here.

## Is the inverse-branching rule source-forced probability?

NO.

The rule is mathematically natural because it is the unique **equal-child** local weighting compatible with normalization at each node. But frozen NFC does not establish the physical premise:

> all lawful child continuation classes at a node must receive equal physical actualization weight.

The children are observationally distinct classes, not necessarily symmetry-equivalent physical alternatives. Representation invariance forbids raw-label dependence but does not force equal weights for structurally distinct children.

Therefore:

`INVERSE_BRANCHING_MEASURE_MATHEMATICALLY_CANONICAL_GIVEN_EQUAL_CHILD_PREMISE = YES`

`EQUAL_CHILD_PREMISE_SOURCE_FORCED = NO`

`PHYSICAL_ACTUALIZATION_AUTHORITY = NO`

## Consequence for the stochastic candidate

The previous `S_OBS_DELTA` law should not be promoted in its global `2^{-Delta}` form unless the binary continuation hypothesis is separately established.

A repaired horizon-free representative K2 candidate is available:

`S_OBS_BRANCH_UNIFORM`:

at each post-observation continuation node `C`, choose among its lawful quotient-visible child classes with equal local probability

`1/(delta(C)+1)`.

The resulting path measure is normalized and projectively consistent by construction.

This candidate is **less arbitrary mathematically** than horizon-by-horizon normalization, but its equal-child physical premise remains new physics.

## Consequence for the deterministic candidate

Binary/projective mass conservation does not repair `D_OBS_DELTA`.

The deterministic finite-horizon argmin rule can still reverse when the horizon changes. A separate local deterministic candidate would be required for time consistency, for example a rule selecting a uniquely distinguished child at each step by a declared local score. Any such score/authority rule remains new physics and tie failure remains possible.

Therefore:

`STOCHASTIC_PROJECTIVE_REPAIR = YES`

`DETERMINISTIC_PROJECTIVE_REPAIR = NOT_SUPPLIED_BY_THIS_AUDIT`

## Scientific interpretation

This operation discovers a genuine mathematical structure but not a physical selector theorem.

Book I's defect count already contains enough information to construct a canonical **uniform branching measure once equal-child weighting is postulated**. The key identity is not the cumulative additive defect `Delta` itself, but the local branching number `delta+1`.

This narrows the stochastic completion problem from:

`invent an arbitrary global measure`

to:

`justify or falsify an equal-child local actualization principle, or identify the quotient-visible structural variables that should replace equal weighting`.

That is a substantial reduction in mathematical arbitrariness while leaving the physical-authority question open.

## Routing

`BOOK_II_BINARY_LIFT = NOT_ESTABLISHED`

`BASE2_GLOBAL_WEIGHT = CONDITIONAL_ON_BINARY_CONTINUATION`

`INVERSE_BRANCHING_PROJECTIVE_MEASURE = PROVED_MATHEMATICALLY`

`EQUAL_CHILD_PHYSICAL_AUTHORITY = NEW_CONTENT_REQUIRED`

`STOCHASTIC_CANDIDATE_HORIZON_PROBLEM = REPAIRED_AT_MATHEMATICAL_LEVEL`

`DETERMINISTIC_CANDIDATE_HORIZON_PROBLEM = OPEN`

`NFC_CANON_MUTATION = NO`

`EXPERIMENT_AUTHORIZED = NO`

`NEXT_OPERATION = NFC_EQUAL_CHILD_ACTUALIZATION_AUTHORITY_AND_DETERMINISTIC_LOCAL_COUNTERPART_AUDIT_V0_1`

The next operation should test two linked questions: (1) whether any frozen symmetry/congruence principle can justify equal weighting among lawful child continuation classes without confusing representation invariance with physical indifference; and (2) whether a minimally matched local deterministic counterpart can be defined on the same child domain without reintroducing horizon dependence or hidden tie-breaking.