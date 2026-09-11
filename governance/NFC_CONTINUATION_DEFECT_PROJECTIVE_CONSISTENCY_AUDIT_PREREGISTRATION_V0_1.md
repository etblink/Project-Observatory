# NFC Continuation-Defect Projective-Consistency Audit — Preregistration v0.1

STATUS = PREREGISTERED__AUDIT_NOT_EXECUTED

BASE_ACCEPTANCE_COMMIT = `be131f787346e7f559e78c564c867be4de04c001`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Questions

1. Do Book-II Binary Rigidity / Binary Stability lawfully imply that the Book-I continuation branching relevant to `delta(C_n)` is always unary or binary?
2. Under what exact branching condition do cylinder weights proportional to `2^{-Delta_L(h)}` form an `L`-independent projective family without horizon-by-horizon renormalization?
3. If that condition is not source-forced, is there a parameter-free local rule built from the Book-I continuation defect count that yields a projectively consistent stochastic research candidate for arbitrary finite branching?
4. Does any such mathematical consistency result confer physical actualization authority? The preregistered answer must remain **no** unless separately proved.

## Fixed definitions

For a continuation node `C`, let

`k(C) := # children of C = delta(C) + 1`.

For a finite history `h = (C_0,...,C_L)`, let

`Delta_L(h) := sum_{i=0}^{L-1} delta(C_i)`.

## Candidate 1: global base-2 defect weight

`W_2(h) := 2^{-Delta_L(h)}`.

Test whether child mass conservation

`sum_{C' child of C} 2^{-delta(C)} = 1`

holds exactly and identify its scope.

## Candidate 2: local inverse-branching weight

Define local child transition weight

`p(C'|C) := 1 / (delta(C)+1) = 1/k(C)`

for every child `C'` of `C`.

Define cylinder measure

`mu_L(h) := product_{i=0}^{L-1} 1/(delta(C_i)+1)`.

Test normalization and projective consistency on arbitrary finite continuation trees.

This rule is a **mathematical candidate measure only**. Equal child weighting is not preregistered as source-forced physical probability.

## Mandatory distinctions

- compression-fiber cardinality vs refinement-child cardinality;
- stable merge arity vs continuation split arity;
- mathematical probability measure vs physical actualization probability;
- projective consistency vs empirical adequacy;
- equal weighting by symmetry/indifference vs theorem-forced weighting.

## Outcomes

A. `SOURCE_FORCED_BINARY_LIFT__BASE2_MEASURE_PROJECTIVELY_CONSISTENT`
B. `BINARY_LIFT_ONLY_CONDITIONAL__BASE2_MEASURE_CONDITIONAL`
C. `NO_SOURCE_BINARY_LIFT__BASE2_NOT_GENERAL__INVERSE_BRANCHING_PROJECTIVE_REPAIR_EXISTS`
D. `NO_SOURCE_BINARY_LIFT__NO_PROJECTIVE_DEFECT_ONLY_REPAIR`
E. `UNDERDETERMINED`
F. `REPAIR_REQUIRED`

## Mutation boundary

Project Observatory only. Frozen NFC and all ten branches remain read-only. No experiment or canon mutation is authorized.