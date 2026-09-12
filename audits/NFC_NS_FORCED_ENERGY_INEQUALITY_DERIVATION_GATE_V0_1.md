# NFC NS Forced Energy Inequality Derivation Gate v0.1

PREREGISTRATION: 0337f3f3d2f61bb46f922668fbad83356cac227e

## Outcome
A__FORCED_ENERGY_INEQUALITY_DERIVED_CONDITIONALLY__REGULARITY_CONTROL_NOT_OBTAINED

## Conditional derivation
Assume P_NS-FORCED-BALANCE-UNIT, so the lawfully represented external source enters the NS Stage-2a test balance additively through the source pairing.

Use the same Galerkin construction and lawful energy test choice phi=u^N as in the frozen unforced proof. The convective cancellation/incompressibility structure and viscous term are unchanged, while the endogenous defect term remains nonnegative. The forced Galerkin energy relation therefore has the schematic form

(1/2) d/dt ||u^N||_{L2}^2
 + nu ||grad u^N||_{L2}^2
 + <u^N, D_N u^N>
 = <F,u^N>,

at the declared finite/refining scope, with the exact source pairing interpreted through the forced-balance bridge.

After integration,

||u^N(t)||_{L2}^2
 + 2 nu int_0^t ||grad u^N||_{L2}^2 ds
 + 2 int_0^t <u^N,D_N u^N> ds
 <= ||u^N(0)||_{L2}^2
 + 2 int_0^t <F,u^N> ds.

Zero source recovers the frozen energy inequality exactly.

## Source-work status
The source-work term <F,u> is an interaction quantity. It is not the source-only multiscale burden B_F and must not replace it. This is the first lawful point in the forced architecture at which state dependence is expected rather than suspicious.

## Optional target-side analytic envelopes
No source scalarization is required for the identity above. If one separately invokes ordinary target-side functional-analysis bounds, examples include:

1. L2 Young/Gronwall on intervals where F is in L2_x:
   2|<F,u>| <= ||F||_2^2 + ||u||_2^2,
   yielding a finite-interval L2 energy envelope from the prescribed force norm.

2. H^{-1}-H^1 duality where the declared interface licenses it:
   2|<F,u>| <= nu ||grad u||_2^2 + nu^{-1} ||F||_{H^{-1}}^2,
   allowing part of the source work to be absorbed into viscous dissipation.

These are analytic inequalities in the target continuum description. They are not NFC-derived source-gain laws and do not select a canonical source norm.

## OpenAI/FCP stress test
The admitted OpenAI construction uses smooth compactly supported forcing, zero initial velocity, positive viscosity, and uniformly bounded kinetic energy while claiming finite-time L_infinity velocity blowup. The forced energy inequality is fully compatible with that pattern.

Therefore:
- finite L2 energy control is not a forced regularity criterion;
- positive viscosity plus finite source-work control does not by itself close the NFC continuation frontier;
- bounded kinetic energy cannot replace the missing common-state/source-to-obstruction bridge.

The external result functions as a negative control exactly as preregistered: it invalidates any attempted promotion from finite-energy control to regularity, but it does not determine the correct NFC source profile or continuation threshold.

## What is established
Conditional on P_NS-FORCED-BALANCE-UNIT:
- forced Galerkin/source-work energy identity/inequality;
- exact zero-source recovery;
- lawful location of state-dependent source work;
- compatibility with standard target-side energy envelopes.

Not established:
- forced H^s or L_infinity control;
- a source-only scalar safety threshold;
- a forced common-state contraction theorem;
- a repaired forced version of the frozen NS master inequality;
- global forced regularity.

## Sharpened frontier
The energy route shows that the next useful question is not whether forcing can be inserted into the balance; it can, conditionally. The issue is what source-sensitive quantity must enter the higher regularity/continuation criterion so that the zero-initial-data OpenAI control is not falsely classified as automatically safe.

## Routing
NEXT_OPERATION = NFC_NS_FORCED_MASTER_INEQUALITY_REPAIR_DESIGN_GATE_V0_1

No mutation of frozen NFC, FCP, or PGH.