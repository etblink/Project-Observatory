# NFC NS Force Separating-Test-Family Feasibility Gate — Preregistration v0.1

STATUS = PREREGISTERED
BASE_ACCEPTANCE_COMMIT = `153d179633cf26c62983133a5ff4566a161f5cb2`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Question

Can frozen NFC, especially the NS branch's existing Galerkin test family `{e_k}` dense in `L^2`, provide or lawfully qualify a separating family of test functionals for the declared smooth compactly supported time-dependent vector forcing class, sufficient to support the dual force-lift route without arbitrary basis supplementation?

## Frozen forcing class

`C_F^cpt(T) = C_c^infty(R^3 x (0,T); R^3)`

## Candidate lanes

- S1 — existing NS spatial Galerkin family `{e_k}` alone.
- S2 — vectorized/componentwise use of `{e_k}`.
- S3 — spacetime tensor family `{e_k(x) psi_m(t)}` with a prospectively qualified temporal family `{psi_m}`.
- S4 — all lawful compactly supported continuum test fields licensed by the NS/Book-VI weak formulation.
- S5 — finite-stage adaptive test families selected from the force profile itself.
- S6 — no separating family available at frozen scope.

## Mandatory gates

A qualifying family must be:

1. prospectively specified independently of the force outcome;
2. lawful under the existing NS/Book-VI interface rather than imported merely because it is standard distribution theory;
3. separating on the declared forcing class at the stated equivalence scope;
4. capable of handling vector components and time dependence;
5. presentation/basis invariant, or accompanied by an equivalence theorem proving that alternative admissible choices yield the same represented source object;
6. compatible with the distinction between force representation and later window localization;
7. nonadaptive to the observed blowup outcome;
8. suitable for finite-stage refinement if the eventual NFC representation is finite at each stage.

## Adversarial tests

- spatial-only insufficiency;
- arbitrary temporal-basis smuggling;
- vector-component loss;
- weak-form test vs source-representation role confusion;
- density without separation at the required topology;
- support/provenance loss;
- adaptive-test circularity;
- basis dependence.

## Outcome taxonomy

- A — frozen NFC already supplies a fully qualifying separating force-test family.
- B — a qualifying family is constructible using frozen ingredients plus one bounded new qualification theorem.
- C — partial separating structure exists but time/vector/support completion requires more than one substantive new ingredient.
- D — no nonarbitrary separating family can be qualified at audited scope.
- E — only target-side continuum tests work, with no lawful source role.
- F — underdetermined.
- G — repair required.

No NFC canon mutation, FCP readjudication, or PGH readjudication is authorized.