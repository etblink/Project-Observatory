# NFC NS Boundary Defect Atomization Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 8afe26789ce99bc86137daa58ff384df7087162f
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
Is the stepwise boundary-defect increment B_n already decomposable, from frozen NFC alone, into a finite quotient-visible family of boundary defect atoms/witnesses whose total weight is exactly B_n?

## Target
Find the weakest canonical atomization of B_n that does not require raw token identity, arbitrary binary decomposition of multiway splits, or assumptions about later persistence.

## Candidate atomizations
A1 unit events: one weight-1 atom per primitive class-splitting event.
A2 parent-class atoms: one quotient-visible boundary parent/split witness carrying weight delta(C) for its multiway split.
A3 collar-type atoms: one stabilized collar-type witness carrying the boundary-ledger weight attributable to that type.
A4 scalar-only: no canonical atomization beyond B_n itself.

## Mandatory tests
- exact reconstruction B_n=sum q(w);
- invariance under relabeling/presentation;
- no arbitrary ordering of descendants;
- locality to LS-2 collar/boundary ledger;
- compatibility with Book-I ledger additivity;
- no claim that an atom persists into I_{n+1};
- no retention/loss coefficient;
- no endpoint-dependent definition.

## Outcomes
A__CANONICAL_WEIGHTED_BOUNDARY_ATOMIZATION_DERIVABLE
B__ATOMIZATION_SCHEMA_AVAILABLE__ONE_ATTRIBUTION_BRIDGE_MISSING
C__ONLY_SCALAR_BOUNDARY_INCREMENT_CANONICAL
D__ATOMIZATION_INCOHERENT
E__REPAIR_REQUIRED
F__UNDERDETERMINED

## Stop rule
This gate ends at step-increment atomization. It may not infer active-stock persistence or an I_n evolution law.