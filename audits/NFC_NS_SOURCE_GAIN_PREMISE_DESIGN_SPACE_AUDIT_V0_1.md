# NFC NS Source Gain Premise Design-Space Audit v0.1

PREREGISTRATION: f8183e14e34a50da99d3489a33bf46036571be02

## Outcome
C__AFFINE_GAIN_PLUS_INNOVATION_IS_MINIMAL_GENERAL_SCHEMA__BOUND_SELECTION_OPEN

## Finding
The minimal general premise capable of representing stationary, attenuating, amplifying, and time-varying exogenous sources without collapsing them into one monotonicity class is an affine profile law

B_{j+1} \preceq G_j[B_j] \oplus I_j,

where:
- B_j is the accepted profile-valued local source burden in context U_j;
- G_j is a source-specific gain/profile transformer acting on the common-refinement profile order;
- I_j is genuinely new exogenous source innovation entering between contexts;
- \oplus denotes profile composition/addition only after common-refinement alignment.

This is a schema, not yet a quantitative theorem. Bounds on G_j or cumulative I_j remain open and must be prospectively specified or derived.

## Candidate adjudication
K1 Uniform nonexpansive transport — too restrictive as a general premise; excludes lawful amplification by assumption.
K2 Bounded gain without innovation — insufficient for genuinely time-varying/newly injected source content.
K3 Affine gain + innovation — ACCEPTED / MINIMAL GENERAL SCHEMA. Separates persistence/transport from new forcing input.
K4 Finite cumulative budget — potentially useful downstream but requires an already-defined innovation sequence and aggregation law.
K5 Direct work injection — dynamically relevant but state-coupled; not a source-only transport premise.
K6 Scalar smallness — premature and loses multiscale structure.
K7 No useful premise — too pessimistic.

## Minimal typing requirements
G_j must preserve zero, positive scaling and provenance, be compatible with common refinement, and must not be identified with endogenous Theta_j. I_j must be independently source-typed, vanish when no genuinely new source enters, preserve provenance, and be comparable in the same profile arena.

## Controls
- Stationary source: choose I_j=0 and G_j acting as identity on the represented source profile.
- Attenuating/amplifying source: encoded through G_j without changing the ontology of source innovation.
- Newly switched-on or time-modified forcing: represented through I_j.
- Zero source: remains zero when G_j(0)=0 and I_j=0.
- OpenAI control: remains in scope. No gain coefficient, threshold, or innovation budget is fitted to its known outcome.

## Scientific frontier
The remaining question is no longer the form of the source law. It is what independent physical or mathematical principle, if any, constrains G_j and the cumulative innovation profile I_j strongly enough to enter a forced common-state continuation theorem.

Candidate next gate: NFC_NS_SOURCE_GAIN_CONSTRAINT_EVIDENCE_GATE_V0_1.

No source-project mutation.