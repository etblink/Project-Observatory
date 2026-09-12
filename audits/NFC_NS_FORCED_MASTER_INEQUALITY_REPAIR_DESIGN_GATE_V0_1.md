# NFC NS Forced Master Inequality Repair Design Gate v0.1

PREREGISTRATION: 0fe380cd4dfa2a7d0c9707c11db3b315e44876f7

## Outcome
A__PROFILE_LOCAL_SOURCE_DISSIPATION_REPAIR_DOMINATES_AS_FIRST_TARGET

## Problem exposed by the forced control
The frozen master inequality

nu c_* > 2 C_NL(s) ||u_0||_{H^s}

contains no external-source term. In a forced target with u_0=0 it is therefore automatically favorable whenever the left side is positive. The OpenAI/FCP forced-blowup control demonstrates that such a source-blind extension cannot serve as a sufficient forced-regularity criterion.

This does not falsify the frozen unforced statement; it blocks silent promotion to forced scope.

## Selected repair architecture
Retain the frozen initial-state condition only on the scope where it is already licensed, and add a separate source-sensitive reserve condition rather than folding source size into the same scalar.

Let B_k^src denote the accepted profile-valued source burden or its prospectively controlled next-step envelope

Bhat_{k+1}^src := Gamma_k[B_k^src] \oplus J_k^res.

Introduce a prospectively defined dissipative/coercive reserve profile R_k^diss on a qualifying common refinement of the same scale/context arena.

The selected source-side repair condition is schematically

Bhat_k^src \preceq (1-epsilon_F) R_k^diss

for some prospectively declared strict margin epsilon_F in (0,1), or an equivalent profile-cone domination with explicit reserve.

This is a design target, not a proved theorem.

## Why profile-local domination is selected
- Zero source makes the source condition vacuous and returns the unforced architecture.
- u_0=0 does not make a nonzero forced problem automatically safe.
- Concentrated high-scale source burden cannot be hidden by a small total scalar norm.
- The gain kernel Gamma and exact innovation residual J^res enter without new scalarization.
- The source remains distinct from endogenous defect and renewal.
- The criterion has a clear falsification mode: the source profile exceeds the certified dissipative reserve somewhere in the aligned profile cone.

## Candidate adjudication

### M1 one scalar source norm
NOT FIRST TARGET. It loses scale distribution and needs a theorem proving that loss harmless.

### M2 Duhamel/semigroup effective amplitude
VIABLE ANALYTIC ALTERNATIVE, HIGHER STRUCTURAL BURDEN. It requires a declared semigroup/memory kernel and usually a scalar source norm. It may become a useful consequence of a later operator realization.

### M3 profile-local source/dissipation domination
SELECTED / DOMINANT FIRST TARGET.

### M4 cumulative gain/innovation profile domination
COMPLEMENTARY, NOT INDEPENDENT. It can be incorporated by using Gamma and J^res to forecast the source profile that must fit beneath the reserve.

### M5 source-work bound
ENERGY-LEVEL / STATE-COUPLED. The previous gate showed this can bound kinetic energy without controlling regularity.

### M6 unchanged old master inequality
REJECTED FOR FORCED SCOPE by the zero-initial-data reversal.

### M7 no coherent repair
REJECTED.

## Missing scientific object
The repair is useful only if R_k^diss is lawfully constructed and compared to the source profile. Frozen NFC has coercive/viscous and obstruction structures, but no accepted theorem currently resolves them into a source-aligned dissipative reserve profile.

Define the next missing bridge:

T_NS-SOURCE-DISS-PROFILE:
construct a representation/refinement-invariant dissipative reserve profile R_k^diss from declared NFC NS coercive/viscous data and prove that it lives in a comparison arena compatible with the source burden profile, without identifying physical source scales with NFC windows by fiat.

## OpenAI control discipline
No epsilon_F, reserve profile, normalization, or scale weighting is selected from the known OpenAI outcome. If a future sufficient theorem based on this architecture is valid, the OpenAI construction must fail at least one independently fixed hypothesis; that is a later test, not a calibration rule.

## Routing
NEXT_OPERATION = NFC_NS_SOURCE_DISSIPATION_PROFILE_BRIDGE_FEASIBILITY_GATE_V0_1

No mutation of frozen NFC, FCP, or PGH.