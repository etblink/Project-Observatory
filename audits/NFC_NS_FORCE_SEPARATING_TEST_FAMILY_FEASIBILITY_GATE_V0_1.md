# NFC NS Force Separating-Test-Family Feasibility Gate v0.1

STATUS = COMPLETE
PREREGISTRATION_COMMIT = `64a91f744a13a8e3790a4723266e933a0a6a7067`
BASE_ACCEPTANCE_COMMIT = `153d179633cf26c62983133a5ff4566a161f5cb2`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`C__SPATIAL_SEPARATING_STRUCTURE_EXISTS__SPACETIME_SOURCE_TEST_COMPLETION_REQUIRES_DISTINCT_NEW_INGREDIENTS`

## Controlling finding

The frozen NS branch already contains a materially relevant internal structure: an admissible Galerkin test family `{e_k}` declared dense in spatial `L^2` and used in the weak-solution construction. This supplies a legitimate spatial separation precedent.

It does not, by itself, furnish a separating test family for

`C_c^infty(R^3 x (0,T); R^3)`.

Two additional burdens remain logically distinct:

1. temporal separation / spacetime completion;
2. qualification of the resulting pairings as lawful `EXOGENOUS_SOURCE_FAMILY` representation data rather than merely target-side weak-form probes.

## Candidate adjudication

### S1 — existing spatial Galerkin family alone

`PARTIAL_ONLY`.

A spatial family dense in `L^2(R^3)` can separate spatial `L^2` slices, assuming the ordinary Hilbert-space pairing at the declared continuum scope. It cannot distinguish two forces with identical spatial projections after an uncontrolled or absent treatment of the time variable.

Therefore S1 is insufficient for the declared spacetime force class.

### S2 — componentwise/vectorized spatial family

`PARTIAL_ONLY`.

Adding canonical Cartesian/vector components can address vector-valuedness at the target continuum level, but it does not repair the missing time separation. Moreover, any component decomposition must remain within the already licensed continuum target structure and may not be read back into Book-I primitives.

### S3 — spacetime tensor family `{e_k(x) psi_m(t)}`

`MATHEMATICALLY_SUFFICIENT_IF_QUALIFIED__NOT_FROZEN_DERIVED`.

If `{psi_m}` is a prospectively fixed family separating the declared temporal function class, then tensor products with a separating spatial family can separate smooth compactly supported spacetime vector fields under the usual pairing. This is a viable design.

However, frozen NFC does not currently select or certify a temporal family `{psi_m}` for this exogenous-source role. Choosing a Fourier, wavelet, polynomial, bump, or other temporal basis by convenience would introduce a new choice whose equivalence/canonicity must be proved or explicitly declared as branch-specific structure.

### S4 — all lawful compactly supported smooth continuum test fields

`TARGET_SIDE_SEPARATION_AVAILABLE_IN_STANDARD_CONTINUUM_MATHEMATICS__SOURCE_ROLE_NOT_DERIVED`.

At the target continuum level, pairing against all compactly supported smooth test fields separates ordinary distributions and therefore smooth forces. But invoking that familiar fact does not solve the NFC problem. Book VI licenses continuum notation for certified source-descended structures; it does not automatically certify arbitrary target-side test fields as source-side representation objects.

Thus S4 demonstrates mathematical separability but not lawful NFC source representation.

### S5 — force-adaptive tests

`FAIL`.

Selecting tests after inspecting the force profile or blowup behavior risks circularity and empirical retrofit. Adaptive refinement may be lawful only after a prospective adaptation rule is frozen independently of the outcome.

### S6 — no separating structure

`REJECTED`.

The existing spatial Galerkin family and ordinary spacetime tensor construction provide enough positive mathematical structure that a complete negative result would be too strong.

## Why Outcome B is not yet earned

Outcome B would require one bounded new qualification theorem. The audit finds at least two distinct unresolved steps:

- `T_NS-FORCE-TIME-SEP`: qualify a temporal/spacetime separating structure prospectively and in a presentation/equivalence controlled way;
- `T_NS-FORCE-PAIR-REAL`: prove that the resulting pairings are lawful exogenous-source representation data under the Book-V/VI anti-smuggling discipline.

These may eventually be packaged in one theorem, but their proofs must discharge separate logical obligations. Merely naming one theorem does not collapse them.

## Minimal constructive schema

A viable future schema is:

`F -> { <F, e_k \otimes psi_m \otimes v_a> }_{k,m,a}`

where:

- `{e_k}` is the existing NS spatial Galerkin family or a prospectively certified equivalent family;
- `{psi_m}` is a qualified temporal separating family;
- `{v_a}` is the finite vector-component basis or an equivalent invariant encoding;
- the total family is prospectively fixed;
- a separation theorem proves equality of all pairings implies equality of the force at the declared continuum equivalence scope;
- a separate realization theorem certifies the coefficient family as `EXOGENOUS_SOURCE_FAMILY` data.

Finite truncations then provide a natural route toward the finite/refinement architecture identified in the preceding design-space audit.

## Relationship to L2 refinement route

This gate reveals that the dual and refinement routes may converge operationally:

`spacetime separating pairings -> finite coefficient truncations -> directed refinement system -> reconstruction`.

Thus the strongest future construction may be a hybrid rather than choosing permanently between L2 and L5.

## OpenAI control

The smooth compactly supported OpenAI force remains in scope. No temporal test family, truncation rule, or threshold may be chosen after consulting its singular outcome. Representability/separation alone must not classify the force as safe or unsafe.

## Routing

`NEXT_OPERATION = NFC_NS_SPACETIME_FORCE_TEST_SYSTEM_DESIGN_GATE_V0_1`

The next gate should compare the smallest prospectively fixed temporal/spacetime test systems compatible with the existing NS Galerkin family and ask whether their equivalence can be established without privileging an arbitrary basis.

## Status

`SPATIAL_GALERKIN_SEPARATION_PRECEDENT = PRESENT`
`FULL_SPACETIME_SEPARATING_FAMILY = NOT_FROZEN_DERIVED`
`TEMPORAL_SEPARATION = OPEN`
`SOURCE_PAIRING_REALIZATION = OPEN`
`DUAL_FORCE_LIFT = PARTIALLY_SUPPORTED`

No frozen NFC canon mutation, FCP readjudication, or PGH readjudication was performed.