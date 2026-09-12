# NFC NS Boundary Witness Persistence Design Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 2721423730b9908bb7748a85f9ff54f87bda367a
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
Given the canonically atomized weighted boundary-defect witnesses generated at each step, what is the weakest lawful mechanism for determining which burden remains in the later interface stock I_n?

## Candidate mechanisms
P1 raw witness identity across stages.
P2 Book-III transport-class lineage plus boundary/collar restriction at each target context.
P3 cumulative sum of all prior boundary atoms.
P4 collar-type Markov persistence using T_partial.
P5 disappearance from the next collar equals annihilation.
P6 typed lineage with statuses INTERFACE_ACTIVE, MIGRATED, RECLASSIFIED/SPLIT_MERGED, and RESOLVED, where RESOLVED requires a separately certified resolution/removal rule.
P7 no coherent persistence mechanism.

## Mandatory tests
- quotient visibility/no raw token identity;
- compatibility with witness-preserving Book-III transfer maps;
- exact distinction between persistence and new generation;
- migration out of the interface must not be conflated with global annihilation;
- no probabilistic semantics for T_partial unless independently licensed;
- genuine removal must be certified, not inferred from absence;
- split/merge must conserve or explicitly transform ledger weight;
- stock/increment types remain distinct;
- no monotonicity or contraction assumed;
- zero endpoint/outcome dependence.

## Outcomes
A__EXISTING_TRANSPORT_AND_RESTRICTION_FULLY_DEFINE_ACTIVE_STOCK
B__TYPED_LINEAGE_SCHEMA_AVAILABLE__GENUINE_RESOLUTION_SEMANTICS_MISSING
C__PERSISTENCE_REQUIRES_MULTIPLE_NEW_BRIDGES
D__NO_NONCIRCULAR_PERSISTENCE_SCHEMA
E__REPAIR_REQUIRED
F__UNDERDETERMINED

## Stop rule
Do not define a boundary-loss coefficient or contraction factor. If current canon lacks a lawful meaning of defect resolution/removal, isolate that as the next theorem target.