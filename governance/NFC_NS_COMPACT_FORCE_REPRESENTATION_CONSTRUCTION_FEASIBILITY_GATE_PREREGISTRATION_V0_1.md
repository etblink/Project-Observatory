# NFC NS Compact Force Representation Construction Feasibility Gate — Preregistration v0.1

STATUS = PREREGISTERED
BASE_ACCEPTANCE_COMMIT = `ebb5d591f3433b1ae76113487b1f57eb799b2619`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Target
Attempt to construct the accepted post-freeze candidate

`R_F : C_c^infty(R^3 x (0,T); R^3) -> EXOGENOUS_SOURCE_FAMILY`

using only frozen NFC machinery plus the explicitly declared candidate target type, and isolate the first missing construction step if the map cannot be completed.

## Candidate construction lanes
1. invert/pull back the Book-VI continuum interface;
2. expand physical forcing against certified NS test/observable families and encode coefficients;
3. realize forcing as a Book-I admissible process family;
4. realize forcing as a formal tagged target-side copy;
5. construct a branch-specific lift theorem from physical forcing descriptors to certified source data.

## Mandatory requirements
The construction must preserve zero, addition, scalar rescaling, support/time-support, provenance, descriptor identity, representation equivalence, and lawful refinement/coarsening. It must not assume window localization, transport weights, continuation, or outcome.

## Adversarial tests
- continuum inversion/surjectivity;
- basis completeness and coordinate dependence;
- admissible-process type mismatch;
- tagged-copy vacuity;
- hidden source localization;
- loss of support/provenance;
- OpenAI outcome leakage.

## Outcome taxonomy
- A `FULL_CONSTRUCTION_FROM_FROZEN_MACHINERY`
- B `CONSTRUCTION_AVAILABLE_ON_RESTRICTED_SUBCLASS`
- C `CONSTRUCTION_BLOCKED_AT_CONTINUUM_TO_SOURCE_LIFT`
- D `CONSTRUCTION_BLOCKED_AT_TEST_BASIS_OR_COMPLETENESS`
- E `ONLY_VACUOUS_TARGET_COPY_AVAILABLE`
- F `UNDERDETERMINED`
- G `REPAIR_REQUIRED`

## Guardrails
No frozen canon mutation and no claim that the candidate premise is true merely because a formal target type can be declared.