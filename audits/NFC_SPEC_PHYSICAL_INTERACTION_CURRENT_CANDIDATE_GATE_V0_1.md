# NFC SPEC Physical Interaction Current Candidate Gate v0.1

STATUS = EXECUTED

PREREGISTRATION_COMMIT = `688970510f82ed5c3bafd8df0316db8ae99e4e89`
BASE_ACCEPTANCE_COMMIT = `4dccced747aec023fd159c9623085d18a0724f68`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`B__MINIMAL_PHYSICAL_INTERACTION_CURRENT_SCHEMA_CONSTRUCTIBLE__SCIENTIFIC_PREMISE_MISSING`

## Executive finding

A minimal noncircular physical-interaction schema can be written without embedding amplitudes or probabilities into its definition. The weakest useful candidate is an operator-valued probe current

`J_SPEC : P -> A_SPEC`

where `P` is the declared admissible SPEC probe class and `A_SPEC` is the already-constrained real/invariant-bilinear operator arena containing `L_SPEC` at the declared gauge-response scope.

The frozen corpus does **not** derive this map for generic probes. Therefore the schema is constructible as explicit new branch-specific physics, not source-derived NFC theorem content.

## Minimal candidate schema

For each admissible probe `P`, introduce a branch-visible interaction object

`J_SPEC(P)`

subject to:

1. **Domain/codomain:** `J_SPEC(P)` acts on the same certified observable/operator arena as `L_SPEC`, or on a declared compatible extension already licensed by YM/SM.
2. **Quotient covariance:** source-equivalent probes and quotient-equivalent states induce equivalent interaction action.
3. **Zero/identity limit:** a null probe maps to the zero interaction object (or declared identity-neutral element, depending on target convention).
4. **Composition law:** sequential probes have an explicitly declared composition/update rule; no assumption is made that `J(Q o P)=J(Q)+J(P)` unless separately proved.
5. **No amplitude content:** `J_SPEC(P)` itself is not a transition amplitude, probability, branching fraction, or fitted response frequency.
6. **No probability content:** no stochastic normalization is built into `J_SPEC`.
7. **Source-visible parameters:** any coupling constants or scale factors required to instantiate `J_SPEC(P)` are declared separately and remain visible burdens.
8. **Operator-packet compatibility:** `J_SPEC(P)` must preserve the domain/invariant requirements needed for lawful comparison with `L_SPEC`.
9. **Branch-scope discipline:** YM/SM representation data may constrain the form of `J_SPEC` only where their frozen conditional hypotheses apply.
10. **Empirical exposure:** a later rule relating `J_SPEC` and the spectral modes of `L_SPEC` must produce predictions that can disagree with measured responses.

## Why this is the minimal physical step

The accepted free-representation result already shows that formal operators can be manufactured once a target is chosen. Adding another purely algebraic representation would therefore add no physical content.

The minimum genuinely physical move is instead to assert that a declared experimental/intervention probe corresponds to a branch-visible interaction object in the same arena that carries the frozen SPEC spectral structure.

This assertion adds one new physical bridge:

`PHYSICAL_PROBE -> INTERACTION_OBJECT`

while leaving the later strength/probability law open.

## Candidate-class adjudication

### I1 Operator-valued current

**PASS as minimal schema.**

It cleanly separates representation, interaction, and later coupling/probability semantics. It is compatible with the existing SPEC operator packet and can retain quotient visibility.

### I2 Bounded perturbation `V_P`

**PASS only as a specialization of I1.**

Writing `L_SPEC -> L_SPEC + V_P` is useful only after boundedness/domain preservation are proved for the chosen arena. It should not be the primitive definition because it presupposes additive operator structure and a common domain.

### I3 Generator derivation / commutator

**VIABLE BUT STRONGER.**

A derivation such as `[J_P, -]` adds algebraic assumptions not needed for the minimal bridge and can fail in target arenas lacking the required associative/*-algebra structure.

### I4 Source/current term in branch equation

**VIABLE BUT BRANCH-SPECIFIC.**

Useful where a branch already has an equation admitting a source term; not generic enough to define all SPEC probes.

### I5 YM/SM current

**PROMISING RESTRICTED REALIZATION, NOT GENERIC SOURCE DERIVATION.**

Frozen YM/SM structure supplies gauge and matter representation content and structural coupling data at conditional scope. It can constrain a future interaction current, but does not currently map every generic SPEC probe to a unique gauge/matter current.

### I6 RH-style transformed probe

**ARCHITECTURAL PRECEDENT ONLY.**

RH demonstrates how branch-specific transformed-probe data plus weighting/aggregation can build an operator. Those ingredients are not generic SPEC data.

### I7 LING-style context action

**STRUCTURAL PRECURSOR ONLY.**

It supports context-dependent lawful action but is not by itself physical interaction structure.

### I8 Direct weighted-edge operator

**REJECTED AS MINIMAL PHYSICAL BRIDGE.**

Assigning numerical edge weights at this stage hides the unresolved coupling/amplitude law inside the representation and risks fitting the answer into the bridge.

### I9 No minimal candidate

**REJECTED.**

The operator-valued current schema is coherent and sufficiently explicit to expose rather than hide the missing physics.

## Adversarial tests

### Representation vs physics

PASS. `J_SPEC` is explicitly new physical bridge content, not claimed as a theorem of the accepted free representation.

### Hidden amplitude

PASS. No amplitude or channel weight occurs in the primitive schema.

### Circularity / fitting

PASS at schema level. Any later parameters must be fixed independently of the branching data used for validation.

### Gauge / basis / relabeling invariance

PASS as a required condition, not a proved universal theorem. Concrete realization must demonstrate covariance/invariance in the selected branch arena.

### Composition / path ordering

PASS with open burden. The schema requires an explicit composition law and does not silently assume commutativity or additivity.

### Zero-probe limit

PASS as a required structural axiom.

### Branch-scope leakage

PASS. YM/SM inputs are restricted to their declared conditional domains.

### Same-support / different-current

PASS conceptually. Distinct `J_SPEC` assignments can act on the same accepted reachability support and therefore can produce distinct later predictions. Thus the current adds potential empirical content beyond the relational layer.

### Current rescaling

**OPEN AND IMPORTANT.**

`J_SPEC -> a J_SPEC` can remain structurally admissible unless a normalization theorem fixes `a`. This freedom is deliberately not hidden. It becomes a separate coupling/normalization burden.

### External-dynamics equivalence

PASS as a firewall. If a future `J_SPEC` simply reproduces a conventional externally supplied interaction Hamiltonian/current, the result must be classified as imported branch-specific physics rather than NFC source derivation.

## Relation to frozen SM coupling structure

The SM branch contains structural gauge-coupling seeds and a conditional coupling-transfer theorem at its own declared scope. These facts demonstrate that NFC branch books already permit nontrivial coupling structure after additional branch-specific hypotheses and transfer machinery are supplied.

They do **not** derive the generic SPEC probe-current map and must not be used to preassign transition strengths for the present candidate.

## Sharpened frontier

The accepted hierarchy becomes:

`probe P`
` -> certified episode / Path_SPEC`
` -> constrained operator arena`
` -> J_SPEC(P)  [minimal new physical bridge candidate]`
` -> ? normalization / coupling functional`
` -> ? channel matrix elements or strengths`
` -> ? transition kernel`

The earlier abstract representation gap is now replaced by a concrete scientific premise:

`P_PHYS: each declared physical probe admits a quotient-visible branch-local interaction representative J_SPEC(P) in the constrained operator arena.`

This premise is not frozen-source derived.

## Scientific status

`SOURCE_DERIVED_GENERIC_INTERACTION_CURRENT = NO`
`MINIMAL_NONCIRCULAR_INTERACTION_CURRENT_SCHEMA = YES`
`NEW_PHYSICAL_PREMISE_REQUIRED = YES`
`AMPLITUDE_OR_PROBABILITY_BUILT_IN = NO`
`NORMALIZATION_FIXED = NO`
`EMPIRICAL_SUPPORT = NONE`

## Routing

The highest-information next operation is to test a restricted realization where the frozen corpus is strongest rather than inventing a universal current immediately:

`NEXT_OPERATION = NFC_SPEC_YM_GAUGE_RESPONSE_INTERACTION_CURRENT_REALIZATION_GATE_V0_1`

This gate should ask whether the gauge-response SPEC regime plus frozen YM operator/gauge structure can instantiate `J_SPEC(P)` for a nontrivial probe subclass without importing measured branching ratios or external interaction amplitudes.

`NFC_FROZEN_CANON_MUTATION = NO`
`FCP_READJUDICATION = NO`
`PGH_READJUDICATION = NO`
