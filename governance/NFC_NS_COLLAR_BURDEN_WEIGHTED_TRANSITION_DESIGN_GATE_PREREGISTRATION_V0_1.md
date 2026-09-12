# NFC NS Collar Burden Weighted Transition Design Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 1d0c934b64ad7d2613cb800aad24364f7d01e094
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
What is the weakest noncircular semantics for lifting a lawful stabilized collar-type transition into a burden transition, so that retained old interface burden, genuine loss, and genuinely new burden are determined from certified structure rather than from a coefficient chosen to make later contraction work?

## Candidate lift classes
W1 Arbitrary retention coefficient r(tau->tau') in [0,1] multiplying I_n.
W2 Witness-level partial persistence map: represent interface burden by certified finite defect witnesses/events with additive nonnegative weights; use lawful witness-preserving transfer to identify retained witnesses; define loss as old witnesses without retained images and generation as target witnesses not descended from retained old witnesses.
W3 Markov/stochastic lift of T_partial.
W4 Perron-Frobenius/eigenvalue-based retention factor from T_partial.
W5 Pure type adjacency with no burden weights.
W6 No coherent lift.

## Mandatory tests
1. no probability semantics unless separately licensed;
2. no contraction coefficient chosen from downstream needs;
3. identity transfer preserves all retained witness burden absent separately certified loss/generation;
4. exact no-double-count decomposition of retained/lost/new burden;
5. quotient/presentation invariance of witness identity class;
6. lawful handling of splitting/merging under transfer;
7. compatibility with Book-I ledger additivity and Book-III witness-preserving transfer maps;
8. B_n relation kept separate until proved;
9. composition/refinement coherence;
10. explicit failure if interface burden has no event/witness decomposition.

## Outcomes
A WITNESS_PERSISTENCE_LIFT_DOMINATES_AS_FIRST_TARGET
B SMALL_NONDOMINATED_LIFT_SET
C ONLY_FREE_RETENTION_COEFFICIENT_AVAILABLE
D NO_NONCIRCULAR_WEIGHTED_LIFT
E REPAIR_REQUIRED
F UNDERDETERMINED

No frozen NFC mutation and no regularity claim.