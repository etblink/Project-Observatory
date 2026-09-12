# NFC NS Interface Witness Status Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 93df2b9f260110065260b1dcad79bf36d66e756a
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
Can the frozen quotient/transfer structure itself certify retained weight, quotient loss, migration and reclassification for the canonical weighted boundary split witnesses, thereby supplying the status transitions needed for an interface-stock recurrence?

## Primary candidate: quotient-image cardinality
For a canonical weighted split witness w represented by a parent quotient class and its finite descendant set D(w), with q(w)=|D(w)|-1, and a lawful quotient-compatible transfer f, define the distinct target image set f[D(w)]. Candidate retained split weight:

q_f(w) := max(|f[D(w)]|-1,0).

Candidate quotient-coalescence loss:

ell_f(w) := q(w)-q_f(w).

Because f is a function on quotient classes, |f[D]|<=|D|, hence ell_f(w)>=0.

Target-context status is then tested separately: if the target image witness is boundary/collar-local it is INTERFACE_ACTIVE; if certified outside the target boundary it is MIGRATED; if multiple source lineages share a target image, provenance is merged explicitly; newly generated target splits remain the distinct B_n generation channel.

## Alternative candidates
S2 import aggregate H1/H2 loss coefficients as witness-level loss.
S3 arbitrary retention coefficient r(w).
S4 collar-type transition probability/Markov semantics.
S5 absence from target boundary = total annihilation.
S6 no witness-level status theorem.

## Mandatory tests
- q_f depends only on quotient-visible classes and lawful transfer;
- no ordering of descendants;
- identity transfer gives zero quotient loss;
- injective transfer preserves q;
- many-to-one coalescence produces nonnegative loss;
- target refinement/new splitting is not misclassified as retained old burden;
- migration and global annihilation remain distinct;
- if transfer is obstructed/undefined, no loss is inferred;
- no import of H1/H2 aggregate bounds without attribution;
- no probabilistic interpretation;
- compatibility with additive boundary generation B_n;
- exact stock recurrence is not asserted unless I_n can be identified with the total current boundary-visible witness mass.

## Outcomes
A__QUOTIENT_IMAGE_CARDINALITY_SUPPLIES_CANONICAL_WITNESS_STATUS_AND_LOSS
B__QUOTIENT_IMAGE_STATUS_SCHEMA_AVAILABLE__INTERFACE_STOCK_IDENTIFICATION_STILL_MISSING
C__ONLY_PARTIAL_STATUS_CLASSIFICATION_AVAILABLE
D__QUOTIENT_IMAGE_ROUTE_INVALID
E__REPAIR_REQUIRED
F__UNDERDETERMINED

## Stop rule
Even if quotient-image loss is valid, do not claim the I_n evolution law until the current interface burden is proved equal to the total boundary-visible mass of the transported/generated witness family.