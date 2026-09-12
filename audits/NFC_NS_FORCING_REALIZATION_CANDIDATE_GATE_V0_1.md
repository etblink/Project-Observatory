# NFC NS Forcing Realization Candidate Gate v0.1

STATUS = COMPLETE
PREREGISTRATION_COMMIT = `ae4e543c86337722658f23f2f8afaff6f3453a8e`
BASE_ACCEPTANCE_COMMIT = `a06cfa90b7063951ca9157af78997a779e8dcf91`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`C__NEW_TYPED_FORCING_OBSERVABLE_FAMILY_IS_MINIMAL`

## Candidate review

### R1 — Certified observable family reuse
INSUFFICIENT WITHOUT TYPE CHANGE.

Book VI defines a certified observable family as realized stabilized local observable outcomes carried across regimes. A prescribed external forcing field is not, merely by being smooth and measurable, a realized stabilized outcome of the NS system. Treating it as one would invert target/source semantics.

The reusable part is the family/continuum-interface machinery, not the existing observable-outcome type itself.

### R2 — Book-III flux/accumulator reuse
REJECTED AS TYPE MISMATCH.

Flux and accumulator objects record transported/accumulated observable content across certified boundaries. They can later carry source influence after a source has been represented, but they do not by themselves identify the exogenous source.

### R3 — SPEC-style probe/response reuse
REJECTED AS GENERIC REPRESENTATION.

A probe is an admissible intervention episode/process, whereas a forcing field may persist over a spacetime support and need not be episodic. A time-local impulse subclass might later admit a probe interpretation, but that does not cover generic smooth forcing and therefore cannot be the general `F_src` type.

### R4 — Endogenous defect reuse
REJECTED.

External forcing and endogenous NS defect burden must remain typed separately. Conflation would destroy the distinction established by the accepted forced-scope audits and undermine the OpenAI negative control.

### R5 — New typed forcing observable family
QUALIFIES AND IS MINIMAL.

Define a branch-visible exogenous source family

`F_src = {s_R}_{R in Reg_NS}`

where each `s_R` is the certified representation, at regime `R`, of the prospectively declared external forcing data relevant to that regime. The family is not an outcome observable; it is an explicitly typed `EXOGENOUS_SOURCE` object governed by Book-V legitimacy and Book-VI interface rules.

Minimum required fields/structure:
- source provenance identity;
- physical support/time-support descriptor;
- scale/decomposition identity inherited from `Q_F^{Pi,N,a}`;
- transformation/refinement law across lawful regime changes;
- zero-source identity (`F=0` maps to the zero forcing family);
- representation invariance under physically equivalent source descriptions;
- explicit nonidentity with endogenous defect burden;
- no window localization yet;
- no source transport weighting yet.

This is new branch-specific content but uses existing NFC constitutional/interface machinery rather than a new foundational formalism.

### R6 — Hybrid source wrapper plus observable components
NOT CURRENTLY MINIMAL.

A wrapper around several certified observable families may become useful if distinct source components require independently certified carrier types, but no such necessity is established yet. The single typed source-family object already preserves the needed provenance/decomposition data.

## Why Outcome B is not enough
Calling the object a mere subtype of `certified observable family` would still alter the semantic contract of that existing type, whose elements are realized stabilized local observable outcomes. The forcing object is input/source data, not system output. The clean minimal move is therefore a new sibling type using the same Book-V/VI compatibility machinery.

## Minimal schema

`T_NS-FORCE-REAL : (F, Q_F^{Pi,N,a}, R_NS) -> F_src`

with `F_src` satisfying:

1. `TYPE(F_src) = EXOGENOUS_SOURCE_FAMILY`;
2. Book-V legitimacy witness exists;
3. Book-VI interface representation is lawful on the declared scope;
4. `F=0 => F_src=0`;
5. source provenance is preserved;
6. refinement/coarsening obeys a declared compatible map;
7. no dependence on later solution outcome;
8. no identification with `D_endogenous`;
9. no localization or source transport is assumed.

## OpenAI negative-control review
The schema can represent a nonzero smooth compactly supported source prospectively without declaring it safe or dangerous. Therefore it does not encode the OpenAI blowup outcome. Any future continuation theorem must still fail visibly on that construction through the realized source burden or another explicit hypothesis.

## Scientific consequence
The first missing forced-NS theorem now has a concrete target object rather than an abstract placeholder:

`F -> Q_F^{Pi,N,a} -> ? T_NS-FORCE-REAL -> F_src`.

The next question is whether the frozen Book-VI interface machinery is already sufficient to prove a realization theorem into this new type once the type is declared, or whether an additional source-specific realization axiom is needed.

## Status

`EXISTING_FROZEN_TYPE_REUSED_UNCHANGED = NO`
`NEW_FOUNDATIONAL_TOOLKIT_REQUIRED = NO`
`NEW_BRANCH_SPECIFIC_SOURCE_TYPE_REQUIRED = YES`
`FORCING_REALIZATION_THEOREM = NOT_YET_PROVED`
`SOURCE_LOCALIZATION = DOWNSTREAM_OPEN`
`SOURCE_TRANSPORT = DOWNSTREAM_OPEN`

## Routing

`NEXT_OPERATION = NFC_NS_FORCING_REALIZATION_THEOREM_FEASIBILITY_GATE_V0_1`

`NFC_FROZEN_CANON_MUTATION = NO`
`FCP_READJUDICATION = NO`
`PGH_READJUDICATION = NO`