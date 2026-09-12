# NFC SPEC Transition-Strength Derivability Gate — Preregistration v0.1

STATUS = PREREGISTERED

BASE_ACCEPTANCE_COMMIT = `36f35d00587cd838a3ab61ed4885b6e4dca8df39`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Question

Can frozen SPEC, using only its certified operator/response structure and already-licensed frozen imports from YM, SM and the canonical spine, derive prospective **relative transition strengths** among a fixed set of quotient-visible post-probe response channels, without importing measured branching fractions or standard quantum transition laws as unexplained primitives?

## Required object

A qualifying transition-strength object must supply nonnegative child-specific weights

`W_i = W(parent, probe, child_i)`

such that:

1. every `W_i` is computable before target outcome frequencies are observed;
2. weights are representation-invariant at the declared SPEC quotient scope;
3. normalization `P_i = W_i / sum_j W_j` is mathematically well-defined;
4. `W_i/W_j` is nontrivial for at least some inequivalent channels;
5. the ratio is derived from frozen SPEC/YM/SM/operator content rather than imported empirical branching data;
6. any auxiliary constants are themselves frozen-derived or prospectively fixed independently of the target frequencies;
7. the construction survives SPEC no-smuggling and Book-V/VII promotion discipline.

## Mandatory candidate families

- spectral eigenvalues / gaps / margins;
- overlap, projection, or response-signature quantities already certified in SPEC;
- generator-compatibility structure;
- transition-ledger quantities;
- YM covariant-Laplacian / gauge-sector structure;
- SM gauge/harmonization structure;
- Book-III transport/coercive quantities;
- Book-IV normalization/invariants;
- any frozen theorem that explicitly relates parent and child operator data.

## Mandatory adversarial tests

1. **Allowed-vs-weighted:** identifying a channel as allowed is not assigning its probability.
2. **Eigenvalue-vs-matrix-element:** spectral locations/gaps do not determine transition strengths unless an explicit theorem connects them.
3. **Response-vs-rate:** quotient-visible response difference is not automatically a transition rate.
4. **Ledger-vs-intensity:** bookkeeping additivity is not physical intensity/amplitude additivity.
5. **Symmetry degeneracy:** symmetry can relate channels but does not generally weight inequivalent channels.
6. **External-QM leakage:** Born-rule amplitudes, dipole matrix elements, Fermi golden rule, oscillator strengths and selection-rule coefficients count as external unless frozen-derived.
7. **Empirical leakage:** measured branching fractions may validate or falsify a derived law but may not define it.
8. **Parameter freedom:** if free channel-specific parameters can fit arbitrary fractions, no derivation has occurred.
9. **Conservative countermodel:** attempt to preserve every frozen SPEC/YM/SM theorem while varying relative channel weights.

## Outcome taxonomy

- `A__RELATIVE_TRANSITION_STRENGTHS_DERIVABLE_FROM_FROZEN_SPEC_STACK`
- `B__PARTIAL_CHANNEL_RELATIONS_DERIVABLE_BUT_NOT_FULL_WEIGHTS`
- `C__ONLY_ALLOWED_CHANNELS_OR_SPECTRAL_STRUCTURE_DERIVABLE`
- `D__WEIGHTS_REQUIRE_NEW_BRANCH_SPECIFIC_DYNAMICAL_BRIDGE`
- `E__EXTERNAL_STANDARD_PHYSICS_IMPORT_REQUIRED_AT_CURRENT_SCOPE`
- `F__UNDERDETERMINED`
- `G__REPAIR_REQUIRED`

Outcome D/E must be supported by a constructive nonforcing argument, not only by failure to locate a formula.

## Routing

No mutation of frozen NFC. No FCP or PGH readjudication. If D/E is accepted, the next operation should determine the **minimal scientific bridge object** required: e.g. a branch-visible transition operator with matrix-element-like channel couplings, together with a falsifiable derivation target against already-known spectroscopy.