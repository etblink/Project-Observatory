# NFC NS Collar Burden Representation Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 83bac004c632b8e87a86a33432175a9e84cb5b20
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
Does frozen Books I-III supply enough structure to represent interface burden I_n as a positive quotient-visible state on the finite stabilized collar alphabet, and if so, does the existing type transition operator determine burden transport or only type reclassification?

## Candidate representation levels
L0 Scalar I_n only.
L1 Tagged scalar/Dirac measure mu_n = I_n delta_{tau_n} on the realized stabilized collar type tau_n.
L2 Burden function/measure resolved across collar types using certified additive defect attribution.
L3 Burden-weighted transition operator lifting T_partial to positive measures with retained/lost mass semantics.
L4 Full stock evolution with generation/migration/loss.

## Mandatory tests
1. nonnegativity of burden state;
2. quotient/presentation invariance of collar label and burden;
3. whether I_n is proven to depend only on stabilized collar type;
4. whether Book-I ledger additivity supplies per-collar attribution or only chain additivity;
5. whether T_partial carries burden weights or only adjacency/reclassification;
6. no arbitrary normalization;
7. no assumption that B_n equals newly retained interface stock;
8. identify the minimal missing bridge if L3/L4 are not frozen.

## Outcomes
A BURDEN_MEASURE_AND_WEIGHTED_TRANSITION_DERIVED
B POSITIVE_BURDEN_STATE_AVAILABLE__BURDEN_WEIGHTED_TRANSITION_LIFT_MISSING
C ONLY_SCALAR_BURDEN_AVAILABLE
D NO_COHERENT_REPRESENTATION
E REPAIR_REQUIRED
F UNDERDETERMINED

No NFC/FCP/PGH mutation and no regularity claim.