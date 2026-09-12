# NFC NS Source Transport Monotonicity Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 56fea34a7aaa6b6543cf17e8c5a05752a84553a7

## Question
Given functorial source transfer S(f_j), context restriction, and the accepted common-refinement profile preorder, does frozen NFC or the provisional forced-NS architecture imply any nontrivial monotonicity/growth law for exogenous-source burden across successive contexts?

## Candidate laws
K1 Nonexpansive: B_{j+1} \preceq B_j.
K2 Isometric/stationary when the represented physical source is unchanged.
K3 Controlled affine growth: B_{j+1} \preceq G_j(B_j) \oplus I_j with separately typed source gain/innovation.
K4 Support-monotone restriction only: disappearance outside the represented source support, without amplitude monotonicity.
K5 Endogenous Theta-linked contraction.
K6 No nontrivial monotonicity forced.

## Mandatory tests
- stationary persistent source across changing endogenous contexts;
- changing source amplitude/profile;
- restriction to contexts entering/leaving compact source support;
- refinement invariance;
- componentwise cancellation/provenance;
- OpenAI compactly supported forced-blowup control;
- conservative extensions preserving frozen theorem truth with different source transport gains.

## Outcomes
A NONEXPANSIVENESS_FORCED
B SUPPORT_ONLY_MONOTONICITY_FORCED__AMPLITUDE_GROWTH_OPEN
C AFFINE_GROWTH_SCHEMA_AVAILABLE__NEW_SOURCE_GAIN_PREMISE_REQUIRED
D NO_NONTRIVIAL_MONOTONICITY_SOURCE_FORCED
E REPAIR_REQUIRED
F UNDERDETERMINED

No source-project mutation or regularity conclusion.