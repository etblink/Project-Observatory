# NFC SPEC Probe-Representation Bridge Design-Space Audit v0.1

STATUS = EXECUTED__OUTCOME_B__SMALL_NONDOMINATED_BRIDGE_SET__NO_UNIQUE_FIRST_TARGET

PREREGISTRATION_COMMIT = `1aed72f7e138fd0bb417ec5442bc77bd684b7fa5`
BASE_ACCEPTANCE_COMMIT = `7c8998fd73b3ad7ec38afbc9435c779287c514ec`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`PRIMARY_OUTCOME = B__SMALL_NONDOMINATED_BRIDGE_SET__NO_UNIQUE_FIRST_TARGET`

Nondominated classes:

- `K1_PROCESS_REPRESENTATION_FUNCTOR`
- `K4_PHYSICAL_INTERACTION_CURRENT`

Sequencing recommendation:

`FIRST_THEOREM_TARGET = K1_PROCESS_REPRESENTATION_FUNCTOR`

`FIRST_PHYSICAL_TARGET = K4_PHYSICAL_INTERACTION_CURRENT`

This is a research-sequencing recommendation, not a truth preference.

## Executive finding

The design space does not support one bridge class that dominates on both mathematical economy and physical falsifiability.

`K1` is the cleanest minimal mathematical completion of the already-derived relational/ledger action. It asks for a representation functor from the typed admissible-process/action category into an operator category while preserving quotient equivalence, composition, and support. It adds little physical content but may still admit many inequivalent representations.

`K4` is the cleanest genuinely physical completion. It asks for a branch-visible probe/current/interaction object in the existing SPEC/YM/SM arena so that `V_P` is an actual interaction term or generator. It adds more physical structure but is correspondingly more exposed to experiment and branch-specific falsification.

Neither dominates the other.

## K1 — Process representation functor

### Core proposal

Introduce a representation

`F_rep : Proc_SPEC -> OpArena_SPEC`

with

`F_rep(P) = V_P`

and require typed composition, quotient invariance, and support compatibility with `R_P`.

### Advantages

- Closest mathematical continuation of Book-I typed process composition.
- Preserves the already-derived relational/ledger hierarchy.
- Does not itself require probabilities or amplitudes.
- Provides a clean theorem target: existence, faithfulness, uniqueness/nonuniqueness, kernel, and functoriality can be separately audited.
- If impossible under frozen constraints, that is highly informative and branch-independent.

### Liabilities

- A representation functor may exist in many inequivalent forms.
- Existence alone does not give physical meaning to operator coefficients.
- It may merely relocate the selection problem from `P -> V_P` to `which F_rep?`.
- Empirical exposure is weak until a physical realization is added.

`K1_STATUS = NONDOMINATED__BEST_FIRST_THEOREM_TARGET`

## K2 — RH-style transformed-probe plus aggregation

### Core proposal

Construct a transformation family on probes and a separately licensed aggregation/weight law, then reconstruct `V_P` from the transformed family.

### Advantages

- Has a concrete in-corpus precedent: RH reconstructs an operator from transformed probes plus branch-specific weighting.
- Makes the extra ingredients explicit instead of hiding them in matrix coefficients.
- Naturally supports operator-origin audits.

### Liabilities

- SPEC presently lacks a source-selected transformation family analogous to scaling/Mellin structure.
- The required aggregation law is already close to the missing coupling/weight law.
- Risks importing branch-specific structure by analogy.

`K2_STATUS = VIABLE_ARCHITECTURE__DOMINATED_AT_PRESENT_BY_K1_ON_ASSUMPTION_COST_AND_BY_K4_ON_PHYSICAL_DIRECTNESS`

## K3 — LING-style action grammar

### Core proposal

Construct a richer typed action/grammar object for probes, contexts, and composition before operatorization.

### Advantages

- Strongly aligned with quotient-visible process semantics.
- Excellent anti-smuggling and compositional-control layer.
- Could identify canonical probe equivalence classes and composition rules.

### Liability

It remains a process/action representation and does not by itself produce `V_P` in a linear/operator arena.

Thus it is a valuable precursor or component of K1, not a complete bridge class.

`K3_STATUS = PRECURSOR__REDUCES_TO_K1_FOR_OPERATORIZATION`

## K4 — Physical interaction current / generator

### Core proposal

Add or derive a branch-visible physical probe object—current, source, field coupling, interaction morphism, or equivalent—that already lives in the YM/SM/SPEC operator arena and defines

`P -> J_P -> V_P`.

### Advantages

- Directly addresses the physical meaning of the probe.
- Natural landing in existing operator/Hilbert structures.
- Can generate concrete channel-dependent matrix elements or strengths without pretending the relation alone fixes them.
- Strong empirical/falsification exposure.
- Failure on real spectroscopy can reject the physical bridge rather than the frozen relational architecture.

### Liabilities

- Requires genuinely new branch-specific physical content.
- Must specify realization, units, coupling structure, and possibly external apparatus mapping.
- Risk of importing standard physics unless source descent and bridge status are explicit.

`K4_STATUS = NONDOMINATED__BEST_FIRST_PHYSICAL_TARGET`

## K5 — Direct relation linearization

### Core proposal

Choose scalar coefficients on reachable edges and call the resulting matrix/operator `V_P`.

### Result

Rejected as a research-leading bridge class.

Without an independently justified coefficient semantics this merely hides the missing physical law inside the representation. It has minimal notation cost but maximal hidden-amplitude risk.

`K5_STATUS = REJECTED_AS_COMPLETE_BRIDGE__MAY_SERVE_ONLY_AS A REPRESENTATION SANDBOX`

## K6 — Hybrid routes

The only hybrids that survive reduction are principally:

- `K1 + K4`: a general representation interface constrained by a physical interaction-current realization;
- `K3 + K1`: grammar/action preprocessing followed by operator representation;
- `K2 + K4`: transformed physical probe/current family with independently licensed aggregation.

Of these, `K1 + K4` is the most structurally transparent long-run architecture, but it should not be treated as one primitive postulate. K1 and K4 impose distinct burdens and should be tested independently before combination.

## Comparative matrix

| Class | Added math | Added physics | Composition faithfulness | Hidden-weight risk | Physical landing | Falsifiability |
|---|---|---|---|---|---|---|
| K1 | Medium | Low | High | Low-Medium | Medium | Low-Medium |
| K2 | High | Medium | High | Medium | Medium | Medium |
| K3 | Low-Medium | Low | High | Low | Low | Low |
| K4 | Medium | High | Medium-High | Low if explicit | High | High |
| K5 | Low | Hidden/High | Medium | Very High | Superficial | Artificial unless independently grounded |

No composite score is used.

## Why there is no unique first target

A single ranking would collapse two distinct goals:

1. **theorem economy / structural clarification**, where K1 is preferable; and
2. **physical discrimination**, where K4 is preferable.

K1 can fail by showing no faithful/source-compatible operator representation exists without extra structure. K4 can fail by making wrong physical predictions after an explicit interaction realization. These are complementary information channels.

## Recommended sequence

1. `NFC_SPEC_PROCESS_REPRESENTATION_FUNCTOR_FEASIBILITY_GATE_V0_1`
2. if K1 is nonunique/underdetermined, do not patch it with arbitrary coefficients;
3. `NFC_SPEC_PHYSICAL_INTERACTION_CURRENT_CANDIDATE_GATE_V0_1`
4. only then evaluate a hybrid `K1 + K4` representation and transition-strength law.

This order is chosen because K1 is cheaper and may constrain the form a lawful physical interaction can take. K4 remains the first operation capable of producing a genuinely empirical interaction theory.

## Scientific consequence

The missing bridge is no longer one undifferentiated mystery. It splits into:

`representation problem` — how lawful probes acquire operator form;

and

`physical interaction problem` — what branch-specific object makes that operator physically meaningful and channel-sensitive.

The frozen corpus addresses neither completely, but it already supplies enough relational, ledger, operator-arena, normalization, RH, and LING structure to formulate both as precise independent theorem programs.

## Routing

`NFC_FROZEN_CANON_MUTATION = NO`
`FCP_READJUDICATION = NO`
`PGH_READJUDICATION = NO`

`NEXT_OPERATION = NFC_SPEC_PROCESS_REPRESENTATION_FUNCTOR_FEASIBILITY_GATE_V0_1`

`NEXT_PHYSICAL_OPERATION = NFC_SPEC_PHYSICAL_INTERACTION_CURRENT_CANDIDATE_GATE_V0_1`
