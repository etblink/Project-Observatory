# NFC SPEC-SM Matter Current Realization Gate — Preregistration v0.1

STATUS = PREREGISTERED

BASE_ACCEPTANCE_COMMIT = `e813dcf7d4b6f124b1b1532a17d62c706f703f11`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Question

Does the frozen/conditional SM matter structure contain enough source-descended representation and coupling information to instantiate a nonzero physical matter/gauge current for a declared SPEC probe, without importing textbook Standard-Model current formulae, measured amplitudes, branching fractions, or post-hoc empirical fits?

## Required distinction

The gate must distinguish:

1. existence of a matter representation space;
2. existence of a matter generator/operator;
3. gauge action on matter;
4. a conserved/current-like mathematical object;
5. a map from a declared SPEC probe `P` to a nonzero physical current `J_P`;
6. a normalization/coupling rule for that current;
7. channel-specific transition strength/probability.

No item may be promoted to a later item without theorem support.

## Mandatory candidate lanes

- SM matter datum and its exact conditional status;
- matter representation space and generator `D_M`;
- YM/SM gauge action on matter;
- Higgs/EWSB screening if relevant;
- SM coupling-transfer results and their scope;
- SPEC matter-extended operator packet `H_mat = H \otimes I_M + I \otimes D_M`;
- any continuity/interface theorem that could carry a probe into matter space;
- any frozen current, source, bilinear, Noether-type, or response object.

## Mandatory adversarial tests

- **Representation-is-not-current:** a charged representation does not by itself define `P -> J_P`.
- **Generator-is-not-current:** `D_M` or `H_mat` does not by itself define a probe source.
- **Gauge-action-is-not-probe:** gauge transformations/re-encodings cannot be relabeled as physical intervention.
- **Coupling-ratio-is-not-current-normalization:** structural coupling ratios do not automatically fix a probe-current amplitude.
- **Textbook-import firewall:** no standard QFT current formula may be used unless frozen NFC derives or explicitly licenses it.
- **Empirical-retrofit firewall:** no observed branching/frequency data may define the current.
- **Nonzero test:** a qualifying realization must be capable of producing a nontrivial current for at least one prospectively specified probe subclass.
- **Composition/quotient test:** any current map must respect declared quotient visibility and lawful probe composition at its stated scope.

## Outcome taxonomy

A. `NONZERO_MATTER_CURRENT_DERIVED_FROM_FROZEN_SM_STRUCTURE`

B. `RESTRICTED_MATTER_CURRENT_SCHEMA_DERIVED__NORMALIZATION_OR_PROBE_MAP_OPEN`

C. `MATTER_INTERACTION_ARENA_PRESENT__CURRENT_REALIZATION_REQUIRES_NEW_BRANCH_SPECIFIC_BRIDGE`

D. `SM_MATTER_STRUCTURE_INSUFFICIENT_FOR_CURRENT_REALIZATION_AT_AUDITED_SCOPE`

E. `CURRENT_CANDIDATE_EXISTS_ONLY_BY_EXTERNAL_PHYSICS_IMPORT`

F. `UNDERDETERMINED`

G. `REPAIR_REQUIRED`

## Scientific firewall

Passing this gate does not establish transition probabilities, amplitudes, empirical support, or Standard-Model correctness. Failing it does not falsify frozen NFC. No NFC canon mutation, FCP readjudication, or PGH reinterpretation is authorized.

## Deferred independent lane

A separate later operation will examine the NFC NS branch in light of the recent FCP intake of the new OpenAI Navier-Stokes paper. That material is intentionally excluded from this gate.