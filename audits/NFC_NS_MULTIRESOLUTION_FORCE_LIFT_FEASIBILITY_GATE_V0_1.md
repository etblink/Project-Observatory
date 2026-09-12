# NFC NS Multiresolution Force Lift Feasibility Gate v0.1

PREREGISTRATION: 3892cd1140f68e55d7377574b2550fcc2c076ced

## Outcome
B__DICTIONARY_INVARIANT_MULTIRESOLUTION_RECONSTRUCTION_SCHEMA_EXISTS__SOURCE_PROMOTION_THEOREM_MISSING

## Construction
Let T be the basis-free compactly supported smooth spacetime test space and I_F(phi)=<F,phi>. A qualifying multiresolution dictionary D={D_n,rho_{n+1,n}} is required to have finite compact/support-aware stages whose union is separating/dense for the declared test topology. Define A_n^D(F) by the finite list of pairings of F against D_n.

The finite system is required to satisfy zero/addition/scaling, support provenance, and refinement coherence. Its projective/refinement limit represents the restriction of I_F to the dictionary union. Separation/density then reconstructs I_F uniquely on T.

Thus, for two qualifying dictionaries D and E, if both reconstruction theorems hold, their limiting objects are equivalent exactly when they induce the same basis-free functional I_F. Dictionary invariance is therefore mediated by the continuum identity standard rather than by a privileged coordinate basis.

## Adversarial tests
- Dictionary dependence: PASS at reconstruction level; D and E may have different finite coefficients but converge to the same I_F.
- Null kernel: PASS conditionally on declared separation/reconstruction theorem.
- Refinement coherence: PASS as a qualification requirement, not automatic for arbitrary dictionaries.
- Support leakage: PASS conditionally when support/localization tolerance is part of dictionary qualification.
- Basis smuggling: PASS; no dictionary is promoted to physical fundamentality.
- Continuum-to-source firewall: CRITICAL LIMIT. The construction reconstructs the target-side force functional; it does not prove that the equivalence class of refinement systems is a lawful NFC EXOGENOUS_SOURCE_FAMILY.
- OpenAI negative control: PASS. The construction applies to arbitrary smooth compactly supported forcing and introduces no smallness/safety threshold.

## Result
A noncircular dictionary-invariant finite/refinement reconstruction schema exists. It removes the basis-choice obstruction to finite representation. The remaining irreducible bridge is a promotion theorem

T_NS-FORCE-PAIR-REAL:
[equivalence class of qualifying refinement systems reconstructing I_F]
 -> [lawful EXOGENOUS_SOURCE_FAMILY object]

with preservation of provenance, support, addition/scaling, and refinement identity.

No frozen NFC theorem presently supplies this promotion merely from target-side pairings. Therefore Outcome A is not warranted.

## Sharpened frontier
F -> I_F -> {A_n^D(F)}_D / reconstruction equivalence -> [T_NS-FORCE-PAIR-REAL missing] -> F_src -> source localization.

No source-project scientific mutation is authorized.