# NFC NS Force Representability Premise Minimal-Form Gate v0.1

STATUS = COMPLETE
PREREGISTRATION_COMMIT = `d837fcb06d00456779b75c8d8750587fa292ffac`
BASE_ACCEPTANCE_COMMIT = `5ffcfc9f5e597804c9242babf0b3188c398281eb`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`B__C2_P3_IS_MINIMAL`

## Selected forcing class

`C_F^cpt(T) := C_c^infty(R^3 x (0,T); R^3)`

within a prospectively declared finite time horizon `T>0` and the declared NS continuum-interface regime.

This is the class of smooth compactly supported vector forcing fields. The selection is not based on the known OpenAI blowup outcome. It is chosen because:
- smoothness keeps the first forced-scope representability problem separate from distributional/source-regularity complications;
- compact support supplies concrete source identity/support data needed for later localization tests;
- the class is infinite-dimensional and closed under addition and scalar multiplication, preventing a handpicked/vacuous candidate;
- no smallness, safety, or continuation behavior is built into membership;
- it is materially narrower than all smooth forcing fields while remaining physically/mathematically nontrivial.

The frozen OpenAI forcing lies in this class for an independently stated reason: FCP records it as smooth and compactly supported. Its inclusion is therefore a valid negative-control consequence, not a class-tailoring input.

## Selected premise strength

`P3`.

Define the candidate post-freeze premise `P_NS-FORCE-REP^cpt`:

> There exists a faithful representation map
>
> `R_F : C_F^cpt(T) -> EXOGENOUS_SOURCE_FAMILY`
>
> on the declared NS continuum-interface scope such that:
> 1. source provenance and physical support/time support are preserved;
> 2. the prospectively fixed multiscale descriptor identity `Q_F^{Pi,N,a}` is preserved as declared source metadata;
> 3. `R_F(0)=0`;
> 4. `R_F(F+G)` is the lawful source-family sum of `R_F(F)` and `R_F(G)` whenever both fields share the declared interface scope;
> 5. `R_F(aF)` is the lawful scalar rescaling of `R_F(F)` for declared scalars `a`;
> 6. equivalent physical source descriptions map to equivalent source-family objects;
> 7. lawful refinement/coarsening of the declared source decomposition is respected;
> 8. no window localization, source transport weight, continuation property, regularity conclusion, or empirical outcome is assumed.

The addition/scaling clauses are not transition-probability assumptions. They encode the native vector-space structure of the selected forcing class and prevent the representation from degenerating into an arbitrary set injection.

## Candidate-class review

### C1 — all smooth forcing
REJECTED AS UNNECESSARILY BROAD FOR FIRST TEST.

Representability over arbitrary noncompact smooth forcing adds global support/growth issues before the basic bridge is understood.

### C2 — smooth compactly supported forcing
SELECTED.

It is broad, infinite-dimensional, source-localizable in principle, and does not encode safety.

### C3 — divergence-free compact forcing
NOT MINIMAL.

The incompressible NS equations constrain velocity; external forcing need not be restricted a priori to a divergence-free representative because gradient components may interact with pressure/Helmholtz decomposition. Imposing divergence-free forcing would introduce an extra structural restriction before it has been shown necessary for the representation problem.

### C4 — norm-small forcing
REJECTED.

This would confound representability with a later continuation/safety criterion.

### C5 — NFC-internal generated forcing only
REJECTED AS CIRCULAR/TOO NARROW.

It assumes the very representability issue under test by defining admissibility through NFC generation.

### C6 — finite-dimensional handpicked family
REJECTED AS UNDERBROAD/VULNERABLE TO VACUITY.

It could be chosen to make representation artificially easy and would not test the general bridge.

## Premise-strength review

### P1 — bare existence
REJECTED AS TOO WEAK/VACUOUS.

An arbitrary injection into a newly named type would carry little scientific content.

### P2 — fidelity only
NEARLY SUFFICIENT BUT UNDERCONSTRAINED.

Without preserving zero/addition/scaling, a representation could distort the native source algebra while still being called faithful informally.

### P3 — structural fidelity plus algebra
SELECTED.

This is the weakest form that makes the map meaningfully testable and nonarbitrary while remaining upstream of localization/dynamics.

### P4/P5
REJECTED AS OVERLOADED.

Localization, transport weighting, and continuation are already separate accepted burdens.

## OpenAI negative control

Because FCP's admitted OpenAI forcing is smooth and compactly supported, it belongs to `C_F^cpt(T)` on a horizon containing its support. This does not make `P_NS-FORCE-REP^cpt` true or false. It only guarantees that any eventual realization construction cannot evade the known forced-blowup example by silently excluding it from the first test class.

## Scientific consequence

The first new forced-NS premise is no longer an unrestricted existential. It is a concrete structural hypothesis:

`P_NS-FORCE-REP^cpt`.

This premise can now be attacked constructively: attempt to build `R_F` from frozen NFC process/interface structure and test zero, addition, scaling, support, provenance, and refinement preservation.

## Status

`SELECTED_FORCE_CLASS = C_c^infty_COMPACT_SUPPORT`
`SELECTED_PREMISE_STRENGTH = P3_STRUCTURAL_FAITHFUL_LINEAR_COMPATIBILITY`
`PREMISE_TRUTH_STATUS = UNADJUDICATED_POST_FREEZE_CANDIDATE`
`OPENAI_NEGATIVE_CONTROL_INCLUDED_PROSPECTIVELY = YES`
`SAFETY_SMALLNESS_BUILT_IN = NO`

## Routing

`NEXT_OPERATION = NFC_NS_COMPACT_FORCE_REPRESENTATION_CONSTRUCTION_FEASIBILITY_GATE_V0_1`

The next gate should attempt a concrete construction of `R_F` using only frozen NFC machinery plus the explicitly declared post-freeze premise target, and must report exactly where construction fails if it cannot be completed.

`NFC_FROZEN_CANON_MUTATION = NO`
`FCP_READJUDICATION = NO`
`PGH_READJUDICATION = NO`