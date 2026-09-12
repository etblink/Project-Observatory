# NFC NS Scale Envelope Gain Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: e9c22175c4c2b900630b655d8a54df9ac114c58c
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
Can the accepted profile-valued source burden and linear/functorial source transfer support a noncircular, refinement-natural positive envelope operator Gamma_j that bounds transported source burden across scales without scalarization, endogenous-Theta reuse, or outcome fitting?

## Frozen inputs
- profile coordinate bhat_a = a_a N_a(Pi_a F), with prospectively declared projection/decomposition Pi, local norm/seminorm N, normalization a;
- common-refinement coordinatewise order;
- linear functorial source transfer S(f_j), distinct from endogenous Theta_j;
- no universal source monotonicity theorem.

## Candidate envelope forms
E1 scalar multiplier gamma_j B — low complexity but loses scale-local transfer structure.
E2 diagonal scale multiplier — preserves coordinates but forbids cross-scale redistribution.
E3 positive cross-scale kernel/operator K_j with
  Ref_R(B_{j+1})_a <= sum_b K_j(a,b) Ref_R(B_j)_b
on qualifying common refinements.
E4 arbitrary monotone nonlinear Gamma_j — too unconstrained unless further structure forces it.
E5 exact induced finite-stage transfer envelope from the linear source map plus subadditive local norms, required to be natural under refinement.
E6 no useful envelope.

## Mandatory tests
1. Cross-scale mixing.
2. Dictionary/refinement invariance.
3. Zero/addition/nonnegative scaling.
4. Provenance preservation.
5. Stationary-source identity case.
6. Amplifying and attenuating source cases.
7. No endogenous Theta_j reuse.
8. No scalarization unless separately justified.
9. Coefficients/kernel fixed from source transfer + declared decomposition/norm data before solution outcome.
10. OpenAI construction remains rejection control only.

## Outcome classes
A ENVELOPE_DERIVED_FROM_ACCEPTED_STRUCTURE_WITH_NO_NEW_PREMISE
B POSITIVE_KERNEL_ENVELOPE_SCHEMA_AVAILABLE__TRANSFER_DECOMPOSITION_COMPATIBILITY_PREMISE_MISSING
C ONLY_DIAGONAL_OR_SCALAR_ENVELOPE_AVAILABLE
D NO_NONCIRCULAR_SCALE_ENVELOPE
E REPAIR_REQUIRED
F UNDERDETERMINED

No forced-regularity claim and no mutation of frozen NFC/FCP/PGH.