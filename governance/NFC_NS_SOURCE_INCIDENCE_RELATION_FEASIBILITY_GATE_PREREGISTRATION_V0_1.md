# NFC NS Source Incidence Relation Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: a64a2c07a55644b50a5e4b9a13c2e088cdbd489e
PROVISIONAL_HYPOTHESES:
- P_NS-FORCE-PAIR-REP
- T_NS-WINDOW-CONTEXT-MIN
PROVISIONAL_ONLY: YES

## Question
Given a provisional lawful EXOGENOUS_SOURCE_FAMILY representative F_src and typed active transport contexts Ctx(j)=(U_j,Sigma_j), can source incidence with a context be defined noncircularly from existing structure, or must the source family acquire an explicit context-restriction/localization operation first?

## Candidate incidence rules
I1 — Context restriction: alpha R_F j iff Res_{U_j}(alpha) is nonzero, where Res is a lawful source-family restriction map.
I2 — Source-support overlap: alpha R_F j iff source support intersects support/domain carried by U_j.
I3 — Context-local pairing: alpha R_F j iff some certified local test in U_j pairs nontrivially with alpha.
I4 — Transfer participation: alpha R_F j iff alpha appears in a declared source transfer chain through U_j.
I5 — Response-defined incidence.
I6 — Arbitrary declared incidence relation.

## Tests
- incidence must be prospective;
- zero source has empty incidence;
- addition/scaling compatibility;
- equivalent source representations induce equivalent incidence;
- refinement/restriction consistency across nested or successor contexts;
- support provenance is respected;
- cancellation must be distinguished from absence where relevant;
- no response inversion;
- no source transport weight is assumed;
- OpenAI forcing remains in scope.

## Outcomes
A INCIDENCE_ALREADY_DEFINED_BY_EXISTING_PROVISIONAL_STRUCTURE
B CONTEXT_RESTRICTION_IS_MINIMAL_NEW_STRUCTURE__INCIDENCE_DERIVED
C MULTIPLE_NONDOMINATED_INCIDENCE_STRUCTURES_REMAIN
D NO_NONCIRCULAR_INCIDENCE_AVAILABLE
E REPAIR_REQUIRED
F UNDERDETERMINED

No source-project mutation or forced-regularity claim.