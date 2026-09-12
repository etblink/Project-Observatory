# NFC NS Interface Burden Evolution Transfer Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: b133aceef88c95f926412ab582914d9f0778712e
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
Conditional on the minimal uniform two-sided active-load bridge a_I M_n <= I_n <= b_I M_n, does the exact witness-mass recurrence provide a properly typed evolution law for the frozen interface burden I_n with a genuine boundary-loss channel, sufficient at the structural level for part (b) of the common-state obligation?

## Inputs
M_{n+1}=M_n-L_n+G_n,
where L_n=L_n^q+X_n^mig+C_n^merge >=0 and G_n=G_n^eff>=0,
plus 0<a_I<=b_I<infinity uniformly on the declared regime.

## Candidate transferred envelope
(a_I/b_I)I_n-a_I L_n+a_I G_n <= I_{n+1}
<= (b_I/a_I)I_n-b_I L_n+b_I G_n.

## Tests
- all quantities live on one temporal step n->n+1;
- I is never equated to a step increment;
- L_n is a certified loss of current interface witness mass, not an inferred disappearance;
- G_n is deduplicated new boundary generation;
- comparison constants are uniform and not fitted for contraction;
- no claim that the coefficient b_I/a_I is <1;
- no claim that loss dominates generation;
- distinguish structural discharge schema from actual frozen-canon discharge.

## Outcomes
A__PART_B_DISCHARGED_FROM_FROZEN_CANON
B__PART_B_CONDITIONAL_DISCHARGE_SCHEMA_COMPLETE__ACTIVE_LOAD_BRIDGE_UNPROVED
C__TRANSFER_ENVELOPE_INSUFFICIENT_FOR_PART_B
D__TYPE_ERROR_OR_CIRCULARITY
E__REPAIR_REQUIRED
F__UNDERDETERMINED

## Stop rule
Even if the evolution envelope is valid, do not claim common-state contraction, same-state obstruction comparison, renewal control, ledger-state mapping, UWB, or NS endpoint closure.