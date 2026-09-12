# NFC NS Force-Lift Design-Space Audit v0.1

STATUS = COMPLETE
PREREGISTRATION_COMMIT = `639d7d382db564ee0e248c9b1726a69bc2fb2563`
BASE_ACCEPTANCE_COMMIT = `706dcdcad1ce9b6d5eac7bf561a54ca2e9cb351b`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`B__TWO_NONDOMINATED_LIFT_SCHEMAS_SURVIVE__EXPLICIT_RECONSTRUCTION_OR_SEPARATION_THEOREM_REQUIRED`

## Controlling finding

Frozen NFC does not supply a general continuum-to-source inverse. Nevertheless, two noncircular design schemas survive without changing the frozen foundational identity:

1. a refinement/reconstruction lift; and
2. a separating-dual lift.

Both require an explicit new bridge theorem. Neither may be treated as already canonical.

## Candidate adjudication

### L1 — arbitrary basis/test-family encoding

`FAIL_AS_STANDALONE`.

Expanding a force in an arbitrarily chosen basis can produce coefficients, but without a theorem of basis independence or equivalence the representation depends on surplus presentation choice. If a canonical/separating family is separately justified, L1 reduces to L5.

### L2 — finite relational approximant / sampling-refinement system

`SURVIVES`.

A candidate schema is:

`F -> {A_n(F)}_{n>=0} -> F_src`

where every `A_n(F)` is finite, quotient/accountability compatible, support/provenance preserving at declared resolution, additive and homogeneous in `F`, and compatible under refinement. A separate theorem must establish reconstruction or faithful continuum recovery:

`Rec({A_n(F)}) = F`

at the declared forcing scope, or at minimum an injective equivalence class strong enough for all later source-control claims.

This direction matches NFC's native finite-to-continuum discipline because it does not require Book VI to become invertible. It adds a new forcing-specific encoding theorem followed by a forward reconstruction theorem.

Main burdens:
- canonical choice/equivalence of approximants;
- anti-aliasing / separation;
- support convergence;
- vector-field and time dependence;
- compatibility with the declared NS continuum interface.

### L3 — categorical adjunction/right-lift

`NOT_DERIVED`.

Book V supplies realization functors only once licensed; Book VI supplies forward continuum legitimacy. No frozen adjunction, right adjoint, universal lifting property, or essential-surjectivity theorem was identified that would generate a continuum-to-source representative automatically.

A future adjunction could solve the problem, but positing it now would merely rename `T_NS-FORCE-LIFT`.

### L4 — branch-specific discretization/encoding functor

`SURVIVES_AS_WRAPPER_CLASS`.

This is not an independent mechanism from L2/L5. A forcing-specific encoding functor is viable if its construction is supplied either by refinement/reconstruction or by a separating family of pairings. It is therefore a governance/packaging class rather than a third primitive solution.

### L5 — separating-dual / pairing lift

`SURVIVES`.

Let `V_F` be the declared forcing space and let `T={tau_a}` be a prospectively fixed separating family of lawful test objects/functionals. Define

`R_T(F) = ( <F,tau_a> )_a`.

If the family is source-licensed for this role and separates the declared forcing class,

`R_T(F)=R_T(G) => F=G`

at the relevant equivalence scope, then `R_T(F)` is a faithful representation datum. Finite subfamilies/refinement stages may provide NFC-compatible finite approximants.

This route is mathematically economical and naturally preserves addition/scaling. But the frozen corpus does not currently select a complete/separating forcing-test family or prove that its pairings are branch-visible NFC source data.

Thus two new obligations remain:
- `T_NS-FORCE-TEST`: qualify a canonical or equivalence-invariant separating test family;
- `T_NS-FORCE-SEP`: prove separation/reconstruction on the declared force class.

### L6 — `tag(F)` / direct relabeling

`FAIL`.

No reconstruction content; it merely copies target-side ontology into a source label.

### L7 — no qualified class

`REJECTED` because L2 and L5 survive as explicit noncircular research schemas.

## Relationship between L2 and L5

The two survivors are closely related but not identical.

- L2 is primal/geometric: approximate the force by a compatible directed system of finite source objects, then prove faithful reconstruction.
- L5 is dual/observational: characterize the force by its action on a separating family, then encode those certified responses.

A hybrid is possible and may be strongest:

`F -> finite separating measurements at stage n -> A_n(F) -> directed source object -> reconstruction`.

This does not remove either burden. It exposes them cleanly.

## OpenAI negative-control review

The admitted OpenAI forcing class remains inside the target class because no smallness, regularity beyond smooth compact support, or outcome condition is imposed. Neither surviving design can classify that force as safe merely from representability. Therefore representability stays logically upstream of any forcing-control threshold.

## Minimal next theorem target

The cheaper discriminating next step is the dual route because it can fail early: ask whether frozen NFC's admissible-test/observable machinery contains, or can lawfully qualify, a forcing-test family capable of separating `C_c^infty(R^3 x (0,T);R^3)` up to the declared physical equivalence.

`NEXT_OPERATION = NFC_NS_FORCE_SEPARATING_TEST_FAMILY_FEASIBILITY_GATE_V0_1`

If that fails, route to the finite relational approximant design. If it succeeds, attempt a finite-stage/refinement realization and reconstruction theorem.

## Status

`FORCE_LIFT_CANONICAL_IN_FROZEN_NFC = NO`
`REFINEMENT_RECONSTRUCTION_SCHEMA = VIABLE_RESEARCH_ROUTE`
`SEPARATING_DUAL_SCHEMA = VIABLE_RESEARCH_ROUTE`
`CATEGORICAL_RIGHT_LIFT = NOT_DERIVED`
`ARBITRARY_BASIS_ENCODING = NOT_ACCEPTABLE`
`OPENAI_NEGATIVE_CONTROL_PRESERVED = YES`

No frozen NFC canon mutation, FCP readjudication, or PGH readjudication was performed.