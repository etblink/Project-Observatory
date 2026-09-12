# NFC NS Source Transport Law Design Gate v0.1

PREREGISTRATION: 7d9ff84b978adb9b45fd15edd428717827c4ca88

## Outcome
B__FUNCTORIAL_SOURCE_TRANSFER_IS_MINIMAL_NEW_STRUCTURE__SCALAR_WEIGHTING_OPEN

## Finding
The existing Book-III transport factor Theta_j governs transported certified observable content in the endogenous transport architecture. It cannot be reused as an exogenous-source contraction/weight coefficient without an independent theorem. A stationary external source may persist unchanged while endogenous observables contract, so direct reuse fails the type and adversarial tests.

The weakest coherent source-transport structure is instead a functorial pushforward on the newly typed source family. For every lawful context transfer

f_j : U_j -> U_{j+1},

define

S(f_j) : Source(U_j) -> Source(U_{j+1})

with the following required properties:
- zero preservation;
- linearity under source addition/scaling;
- provenance/component identity preservation or explicitly recorded lawful merging/splitting;
- compatibility with source-representation equivalence;
- composition: S(f_{j+1} o f_j)=S(f_{j+1}) o S(f_j) when the context transfers compose;
- naturality with context restriction where both operations are defined;
- no assumption of norm contraction, attenuation, or equality with Theta_j.

## Candidate adjudication
### T1 reuse Theta_j
REJECTED. Endogenous survivor transport and exogenous-source persistence are different typed channels; no frozen theorem equates their transport factors.

### T2 functorial source pushforward
ACCEPTED as minimal new structure.

### T3 restriction-only persistence
INSUFFICIENT for claims about identity/provenance propagation across contexts. It can recompute local presence but does not state whether entries in successive ledgers are the same transported source component.

### T4 response-derived source transport
REJECTED as inversion of downstream dynamics.

### T5 arbitrary scalar source weights
REJECTED absent derivation.

## Adversarial tests
- Stationary source vs contracting endogenous observables: PASS; source transfer may be identity while Theta_j<1.
- Zero source: PASS.
- Addition/scaling: PASS by linearity.
- Composition: explicit requirement.
- Leaving a context: restriction may vanish while source provenance persists globally.
- Theta_j noninheritance: explicit firewall.
- OpenAI control: unaffected; no safety/smallness rule is introduced.

## Transported source ledger
Given L_F(W_k), a transported ledger may track source components along S(f_j) while retaining local profile burdens. However no canonical scalar source weight or contraction coefficient is yet available.

## Sharpened frontier
L_F(W_k)
 -> [source pushforward functor S missing as new structure]
 -> transported source identity/provenance
 -> ? quantitative source transport bound / scalarization
 -> ? source-driven continuation inequality
 -> forced common-state bridge.

No source-project mutation and no forced-regularity claim.