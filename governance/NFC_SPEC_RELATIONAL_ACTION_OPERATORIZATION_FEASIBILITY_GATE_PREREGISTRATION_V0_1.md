# NFC SPEC Relational Action Operatorization Feasibility Gate — Preregistration v0.1

STATUS = PREREGISTERED

BASE_ACCEPTANCE_COMMIT = `39849f97e245695e1464f154d32b6da2bfba38fb`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Question

Given the accepted canonical relational probe action `R_P` on quotient-visible SPEC classes, can frozen NFC canonically operatorize that relation without importing physical transition weights?

## Candidate constructions

1. **Powerset/Boolean direct-image action**: `J_P^B(S) = {y | exists x in S: x R_P y}`.
2. **Boolean adjacency matrix / semimodule representation** of `R_P`.
3. **Free real/complex vector-space incidence operator**: `J_P e_x = sum_{y: x R_P y} e_y`.
4. **Existing SPEC/YM Hilbert-space embedding**, if frozen theorems canonically identify quotient-visible classes with a basis or spectral subspace.
5. **RH-weighted operatorization analogy**, tested only as a branch-local template.
6. **LING grammar/free-category analogy**, tested only as a branch-local template.

## Mandatory tests

- exact composition under lawful probe chains;
- basis/semiring dependence;
- path-multiplicity inflation;
- quotient invariance;
- compatibility with the existing SPEC operator packet;
- no conversion of incidence coefficients into probabilities or amplitudes;
- uniqueness/canonicity of the operator arena;
- RH/LING branch-lift firewall.

## Outcome taxonomy

- `A__CANONICAL_OPERATORIZATION_IN_EXISTING_SPEC_ARENA_DERIVED`
- `B__CANONICAL_BOOLEAN_RELATIONAL_OPERATOR_DERIVED__HILBERT_LINEARIZATION_NOT_FORCED`
- `C__MULTIPLE_MATHEMATICAL_LINEARIZATIONS_EXIST__NO_CANONICAL_OPERATORIZATION`
- `D__NO_OPERATORIZATION_BEYOND_RELATION`
- `E__RH_OR_LING_SUPPLIES_LAWFUL_OPERATORIZATION_BRIDGE`
- `F__UNDERDETERMINED`
- `G__REPAIR_REQUIRED`

No physical strength or probability claim is authorized by this gate.
