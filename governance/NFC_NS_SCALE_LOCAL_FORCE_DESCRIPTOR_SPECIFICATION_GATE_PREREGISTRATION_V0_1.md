# NFC NS Scale-Local Force Descriptor Specification Gate — Preregistration v0.1

STATUS = PREREGISTERED

BASE_ACCEPTANCE_COMMIT = `3d9e07072cbe15b4484f1162ea6504715c2b10da`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`
OPENAI_FCP_CONTROL_INTAKE = `d2c3014357ed1de66849f66c5a8cc08e0d453b4b`
OPENAI_FCP_LOAD_BEARING_AUDIT = `de51ef31b86993034e93be56a7b2cff468ffdb66`

## Question

Can the first surviving forcing-control class `NF-A` be specified prospectively as a mathematically coherent multiscale forcing descriptor that is independent of the realized regularity outcome, without yet claiming a unique scalar norm, threshold, or forced-regularity theorem?

## Design discipline

The descriptor must be based on predeclared properties of the forcing and the declared scale/window decomposition. It may not depend on whether the resulting solution blows up.

A scalar control functional should be introduced only if an aggregation rule is independently justified. A vector/profile-valued descriptor is allowed and preferred if that is the weakest nonarbitrary object.

## Required ingredients

A qualifying descriptor must declare:

1. a physical forcing object `F`;
2. a prospectively frozen decomposition into scale/window components `F_{j,k}` or an equivalent indexed family;
3. a nonnegative local burden `b_{j,k}(F)` computed from the forcing component before solving for the outcome;
4. an explicit normalization/scaling rule;
5. a time/support localization rule;
6. the relation, if any, between physical scales and NFC windows;
7. a coarse-graining/refinement policy;
8. a no-outcome-fit rule;
9. whether the descriptor is a profile, supremum, sum, or other aggregation;
10. failure conditions.

## Candidate descriptor levels

L0. raw support/smoothness metadata only;
L1. unweighted multiscale burden profile `{b_{j,k}}`;
L2. normalized dimensionless profile `{\hat b_{j,k}}`;
L3. scalar aggregation `sup_{j,k} \hat b_{j,k}`;
L4. scalar aggregation `sum_{j,k} w_{j,k}\hat b_{j,k}`;
L5. source-to-dissipation profile comparing local burden to local dissipative reserve.

The audit must select the lowest level that is both nontrivial and nonarbitrary.

## OpenAI control rule

The OpenAI/FCP construction is known to use smooth compactly supported forcing and an oscillatory/multiscale construction. That source architecture may be used to test whether the descriptor is well defined. The known blowup outcome may not be used to choose the descriptor, aggregation, coefficients, or threshold.

The gate is allowed to conclude that FCP's current intake is insufficient to numerically evaluate the descriptor. Such insufficiency is not failure if the mathematical specification itself is prospective and testable.

## Outcome taxonomy

A. `UNIQUE_SCALAR_SCALE_LOCAL_FUNCTIONAL_SPECIFIED`
B. `CANONICAL_OR_MINIMAL_MULTISCALE_PROFILE_SPECIFIED__SCALAR_AGGREGATION_OPEN`
C. `ONLY_NONCANONICAL_DESCRIPTOR_FAMILY_AVAILABLE`
D. `NO_PROSPECTIVE_SCALE_LOCAL_DESCRIPTOR_AVAILABLE`
E. `OPENAI_CONTROL_EXPOSES_DESCRIPTOR_FAILURE`
F. `UNDERDETERMINED`
G. `REPAIR_REQUIRED`

## Guardrails

No frozen NFC mutation.
No forced-regularity theorem.
No use of blowup outcome to set thresholds.
No claim that smooth compact support implies smallness.
No silent identification of physical forcing scale with NFC window index unless a bridge is explicitly declared.