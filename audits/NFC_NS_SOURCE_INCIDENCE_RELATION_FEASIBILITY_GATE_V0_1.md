# NFC NS Source Incidence Relation Feasibility Gate v0.1

PREREGISTRATION: cb9860edbd19adb49d6a047f08b0f9275ce09597
PROVISIONAL_HYPOTHESES:
- P_NS-FORCE-PAIR-REP
- T_NS-WINDOW-CONTEXT-MIN

## Outcome
B__CONTEXT_RESTRICTION_IS_MINIMAL_NEW_STRUCTURE__INCIDENCE_DERIVED

## Finding
The provisional EXOGENOUS_SOURCE_FAMILY type preserves source identity, linear structure, support/provenance, and refinement identity, but does not yet contain a canonical operation that restricts a source component to an arbitrary active Book-III context U_j.

The weakest additional structure is a context-restriction family

Res_U : EXOGENOUS_SOURCE_FAMILY -> EXOGENOUS_SOURCE_FAMILY(U)

for certified contexts U in the active transport chain, satisfying:
- Res_U(0)=0;
- linearity under source addition/scaling;
- identity on the full declared source context;
- compositionality/naturality under nested or lawfully related contexts;
- preservation of source provenance and component identity;
- compatibility with equivalent source representations;
- support monotonicity: restriction cannot manufacture source support outside the context;
- refinement consistency.

For a provenance-tracked source component alpha, define

alpha R_F j  iff  Res_{U_j}(alpha) != 0.

This yields a prospective incidence relation. Componentwise incidence is required: testing only Res_{U_j}(F_src) != 0 can confuse exact cancellation between distinct source components with absence of source.

## Candidate adjudication
### I1 context restriction
ACCEPTED as minimal.

### I2 support overlap
DERIVABLE/INTERPRETABLE after a lawful restriction/support semantics is available; not independently sufficient before that bridge.

### I3 context-local pairing
Potentially equivalent where certified local tests separate the restricted source object, but adds a local-separation theorem and is therefore not minimal.

### I4 transfer participation
Premature. It presupposes the later source-transport theorem and would conflate localization with propagation.

### I5 response-defined incidence
REJECTED. Source presence may exist without visible response; response is downstream.

### I6 arbitrary incidence
REJECTED for canonical force.

## Adversarial tests
- Zero source: PASS by Res_U(0)=0.
- Addition/scaling: PASS with componentwise provenance; total cancellation does not erase component incidence.
- Representation equivalence: requires naturality of Res_U under the accepted source-representation equivalence.
- Refinement consistency: explicit qualification condition.
- Support provenance: preserved by restriction.
- No response inversion: PASS.
- No transport weight: none introduced.
- OpenAI control: remains in scope; this structure says where source content is represented, not whether it is safe.

## Resulting window ledger support
Given W_k and its member contexts U_j,

Inc_F(W_k) := { alpha : exists j in W_k with Res_{U_j}(alpha) != 0 }.

A quantitative source ledger can now attach prospectively declared burden data to these incidences, but the burden functional and its transport weighting remain separate downstream questions.

## Sharpened frontier
F_src
 -> [Res_U missing as new local source structure]
 -> component incidence alpha R_F j
 -> window incidence Inc_F(W_k)
 -> ? quantitative source burden
 -> ? source transport law/weighting
 -> forced common-state bridge.

No source-project mutation and no forced-regularity claim.