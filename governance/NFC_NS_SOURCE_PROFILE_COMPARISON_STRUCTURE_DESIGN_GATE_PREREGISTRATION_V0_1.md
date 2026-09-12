# NFC NS Source Profile Comparison Structure Design Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 9445d9c27a00f7048a6f1d5407917864fa8a2515
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
What is the weakest prospective comparison structure on the accepted multiscale source-burden profiles that allows quantitative transport statements without prematurely scalarizing or importing endogenous NFC contraction semantics?

## Candidate structures
K1 Pointwise/componentwise preorder on aligned profile coordinates.
K2 Positive-cone domination after common refinement to a shared comparison grid/dictionary.
K3 L-infinity/sup norm on the profile.
K4 L1/total burden norm.
K5 Weighted quadratic norm.
K6 Majorization/order-statistic comparison.
K7 No comparison structure.

## Qualification requirements
- Representation invariance under qualifying dictionary/refinement changes.
- Common-refinement compatibility when two profiles use different finite stages.
- Zero/addition/scaling compatibility.
- Component/provenance preservation before any aggregation.
- No chosen scale weighting unless independently justified.
- No endogenous Theta_j reuse.
- No threshold fitted to the OpenAI forced-blowup outcome.

## Outcomes
A UNIQUE_SOURCE_COMPARISON_FORCED
B PARTIAL_ORDER_BY_COMMON_REFINEMENT_IS_MINIMAL__SCALAR_NORM_OPEN
C SMALL_NONDOMINATED_COMPARISON_SET
D NO_NONCIRCULAR_COMPARISON_STRUCTURE
E REPAIR_REQUIRED
F UNDERDETERMINED

## Firewall
This gate designs comparison structure only. It does not prove source nonexpansiveness, source smallness, regularity, or any endpoint theorem.