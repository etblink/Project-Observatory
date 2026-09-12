# NFC NS Source Profile Comparison Structure Design Gate v0.1

PREREGISTRATION: 1aa71c3ee5679400b19e16d79d263d70495bb729

## Outcome
B__PARTIAL_ORDER_BY_COMMON_REFINEMENT_IS_MINIMAL__SCALAR_NORM_OPEN

## Construction
Let B and B' be accepted profile-valued local source burdens produced by qualifying multiscale systems. To compare them without privileging one dictionary, first pass both to any qualifying common refinement R. Let Ref_R(B), Ref_R(B') be the induced nonnegative coordinate/profile data on R. Define

B \preceq_R B' iff Ref_R(B)_a <= Ref_R(B')_a for every aligned coordinate a,

with equivalence under further common refinement. The representation-invariant preorder is the equivalence class of these comparisons under qualifying refinements.

## Why this is minimal
- It preserves scale information rather than aggregating it.
- It introduces no scale weighting.
- It is compatible with zero, nonnegative scaling, addition, componentwise provenance, and refinement.
- Different dictionaries can be compared only after a common refinement, avoiding coordinate smuggling.
- It is a preorder/partial-order structure sufficient to formulate source nonexpansiveness or controlled growth later.

## Candidate adjudication
K1 direct componentwise order — viable only after alignment; alone too representation-dependent.
K2 positive-cone domination after common refinement — ACCEPTED / MINIMAL.
K3 sup norm — downstream scalarization; loses location within profile and is not forced.
K4 L1 total burden — downstream scalarization; allows compensation between scales and is not forced.
K5 weighted quadratic norm — introduces unjustified weights/geometry.
K6 majorization — weaker in some directions but adds sorting/aggregation semantics not licensed by source structure.
K7 no comparison — too pessimistic; common-refinement order is available.

## Adversarial tests
- Dictionary invariance: PASS conditionally on qualifying common-refinement maps.
- Cancellation: PASS because source components/provenance remain separate prior to any summation.
- Stationary source: can satisfy equality B_{j+1}=B_j.
- Amplification: can be represented by B_j \preceq B_{j+1}; no false contraction imposed.
- OpenAI control: unaffected; no safety threshold or fitted norm enters.

## Remaining burden
The order permits meaningful statements such as

B_{j+1} \preceq B_j,
B_{j+1} \preceq G_j(B_j),
or
B_{j+1} \preceq B_j \oplus I_j,

but none is yet proved. A separate source-transport monotonicity/growth theorem is required.

## Next operation
NFC_NS_SOURCE_TRANSPORT_MONOTONICITY_FEASIBILITY_GATE_V0_1

No source-project mutation.