# NFC NS Spacetime Force Test-System Design Gate v0.1

STATUS = COMPLETE
PREREGISTRATION_COMMIT = `f6517727b02e1057e6dad6f9f06e4429dfeeb29a`
BASE_ACCEPTANCE_COMMIT = `5ff4898b1ad7ed0e04af015a99ab96c12f991d35`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`B__TWO_NONDOMINATED_TEST_SYSTEMS_SURVIVE__BASIS_FREE_IDENTITY_FIRST__REFINEMENT_DICTIONARY_SECOND`

## Controlling result

Two designs survive for different purposes:

1. **T1 full basis-free test space** is the cleanest mathematical identity/separation target.
2. **T4 multiresolution compactly supported dictionary** is the strongest finite/refinement implementation target.

Neither is already selected by frozen NFC, and neither alone completes source realization.

## Candidate adjudication

### T1 — full basis-free test space

`SURVIVES_AS_IDENTITY_STANDARD`.

For a smooth compactly supported vector forcing field `F`, the family of pairings

`phi -> <F,phi>`

with all compactly supported smooth vector test fields separates `F` at the ordinary continuum/distributional level. This avoids arbitrary basis choice and gives a clean equivalence criterion:

`<F-G,phi>=0 for all phi in D => F=G`.

Advantages:
- basis independent;
- exact support-sensitive continuum identity standard;
- natural reference against which any countable/finite encoding can be judged.

Limitations:
- target-side continuum mathematics, not yet NFC source data;
- uncountable/infinite family does not itself meet finite-stage source architecture;
- does not supply window localization or source transport.

### T2 — frozen spatial Galerkin family x temporal family

`SURVIVES_CONDITIONALLY__NOT PREFERRED AS IDENTITY STANDARD`.

This route leverages real frozen NS structure, but the temporal family is new and the tensor representation may inherit unnecessary basis dependence. It remains useful as an implementation cross-check once temporal equivalence is controlled.

### T3 — countable rational bump dictionary

`SURVIVES_MATHEMATICALLY__COORDINATE_DEPENDENT`.

A dense countable dictionary of rationally parameterized compactly supported bumps can separate smooth compactly supported fields if density and continuity conditions are proved. It offers explicit enumeration and finite truncation.

But it depends on the chosen continuum coordinate presentation and dictionary construction. This is acceptable only as a declared branch coordinate with an equivalence theorem showing that represented force identity does not depend on that choice.

### T4 — multiresolution compactly supported dictionary

`SURVIVES_AS_IMPLEMENTATION_TARGET`.

A prospectively fixed compactly supported multiresolution system has several advantages:
- finite data at each scale;
- explicit refinement maps;
- support localization;
- natural connection to the accepted multiscale forcing profile;
- compatibility with a directed finite-source approximation.

It remains noncanonical unless its choice is either source-descended or shown equivalent, for force-representation purposes, to alternative qualifying systems.

### T5 — arbitrary orthonormal spacetime basis

`FAIL_AS_PRIMARY_DESIGN`.

Mathematically adequate in many function spaces but unnecessarily presentation dependent and weak on support/localization provenance.

### T6 — adaptive post-force dictionary

`FAIL` unless the adaptation rule is prospectively frozen independently of the singular outcome. As stated, it violates the retrofit firewall.

### T7 — no qualifying system

`REJECTED`.

## Key distinction

The audit freezes a two-level architecture:

`FORCE_IDENTITY_STANDARD = T1`

`FINITE_REFINEMENT_REALIZATION_CANDIDATE = T4`

T1 tells us what it means for two representations to encode the same continuum force. T4 is a candidate mechanism for approximating that identity standard through finite, support-aware refinement data.

This avoids requiring the implementation dictionary itself to be physically fundamental.

## Equivalence burden

A future T4 construction should not need to prove that one particular multiresolution dictionary is uniquely canonical. A weaker and more appropriate theorem would be:

> any two qualifying refinement dictionaries that converge to the same T1 test-functional object define equivalent `EXOGENOUS_SOURCE_FAMILY` representations.

This would move canonicity from basis identity to representation-equivalence.

## Relation to frozen NS Galerkin family

The existing `{e_k}` family remains useful as an internal consistency/control lane. A completed lift should reproduce the same weak spatial projections on overlapping scope. Failure to do so would signal an interface inconsistency.

## OpenAI control

The OpenAI smooth compact force remains in scope. No dictionary element, refinement stopping rule, or coefficient threshold may be chosen using its known blowup behavior.

## Routing

`NEXT_OPERATION = NFC_NS_MULTIRESOLUTION_FORCE_LIFT_FEASIBILITY_GATE_V0_1`

This next gate should ask whether a generic support-aware refinement system can be specified abstractly enough to avoid choosing a particular wavelet/basis implementation, while still providing finite stages, refinement compatibility and convergence to the T1 identity standard.

## Status

`BASIS_FREE_CONTINUUM_IDENTITY_STANDARD = AVAILABLE_TARGET_SIDE`
`FINITE_REFINEMENT_IMPLEMENTATION_ROUTE = VIABLE`
`UNIQUE_TEST_SYSTEM_CANONICALITY = NOT_REQUIRED`
`REPRESENTATION_EQUIVALENCE_THEOREM = REQUIRED`
`SOURCE_ROLE_REALIZATION = STILL_OPEN`

No frozen NFC canon mutation, FCP readjudication, or PGH readjudication was performed.