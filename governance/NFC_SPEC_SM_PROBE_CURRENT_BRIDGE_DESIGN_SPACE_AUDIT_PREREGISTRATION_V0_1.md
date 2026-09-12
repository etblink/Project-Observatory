# NFC SPEC-SM Probe-Current Bridge Design-Space Audit — Preregistration v0.1

STATUS = PREREGISTERED__NOT_YET_ADJUDICATED

BASE_ACCEPTANCE_COMMIT = `7fdd5820794dd7842ff359ed4a51f50445953be8`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Question

Among minimal additional branch-specific structures compatible with the frozen SPEC/SM/YM architecture, what is the smallest scientifically meaningful bridge class capable of mapping a prospectively declared physical probe `P` to a nonzero operator-valued matter/gauge current `J_SM(P)` without hiding transition amplitudes, observed branching fractions, or fitted probabilities inside the bridge?

This audit compares bridge classes. It does **not** assert that any candidate is true.

## Frozen positive structure

The audit may use only already-frozen source/branch structure, including:

- SPEC probe episodes, response classes, transition ledgers, and the accepted relational/ledger action;
- the constrained SPEC operator arena and `L_SPEC`;
- SM source-descended matter representations;
- screened vacuum sector `H_0` and matter generator `D_M`;
- `H_mat = H \otimes I_M + I \otimes D_M`;
- transferred gauge action and conditional coupling-ratio information;
- Book-V branch-legitimacy / no-hidden-supplementation rules.

The audit may use no observed transition frequencies, measured branching ratios, textbook current formulas as assumed NFC results, or post hoc fit parameters.

## Mandatory candidate bridge classes

### K1 — Generator-deformation bridge
A prospectively declared probe control `P` induces a branch-visible deformation

`D_M -> D_M + V_P`

or equivalently `H_mat -> H_mat + V_P`, with `V_P` the current/insertion object. The audit must determine what additional data are needed to map an operational probe to `V_P` and whether this merely renames the missing bridge.

### K2 — Gauge-source/current bridge
A probe is represented by a gauge-covariant source/current landing in the SM gauge representation content, schematically

`P -> J_P in g_obs-valued / representation-compatible current space`.

No textbook Noether/current formula may be imported without a separately declared bridge.

### K3 — Vacuum-sector insertion bridge
A probe acts through a nonzero operator on the screened physical vacuum/matter sector `H_0` (or its matter extension), preserving declared domains and gauge/screening compatibility.

### K4 — Response-derived operator bridge
Attempt to derive a nonzero `V_P` from the accepted SPEC relational/ledger action plus `D_M`, `H_0`, `L_SPEC`, commutator/derivation structure, or another already-frozen algebraic construction. Mathematical definability is insufficient unless the construction is unique or source-selected and has physical intervention semantics.

### K5 — Explicit external physical-source primitive
Declare a new branch-specific current/source object with transformation law, support/profile, domain, normalization status, and coupling slot independently of transition data. This is scientifically admissible only if the new premise is explicit, prospectively testable, and does not encode outcome frequencies.

### K6 — Hybrid representation-plus-current bridge
A restricted physical probe class is first mapped to a source-descended representation/control descriptor and then to a current/operator insertion. The two stages must remain independently auditable.

## Evaluation axes

Each candidate is graded on:

1. added physical structure;
2. source/branch compatibility;
3. quotient visibility;
4. gauge covariance / representation compatibility;
5. vacuum and operator-domain compatibility;
6. nontriviality for a prospectively identifiable probe class;
7. compositional/sequence behavior where applicable;
8. normalization transparency;
9. separation from amplitudes/probabilities;
10. empirical/falsification exposure;
11. risk of tautology (`P` defined as the operator it is supposed to derive);
12. risk of hidden textbook import.

## Mandatory adversarial tests

### T1 — Tautology test
Defining `P := V_P` does not count as a bridge from a physical probe to an operator.

### T2 — Rescaling test
If `V_P -> a V_P` remains free, that freedom must be exposed. A bridge may still qualify structurally, but cannot claim calibrated strength.

### T3 — Gauge-redundancy test
Pure gauge transformations/re-encodings cannot count as physical currents.

### T4 — Zero-current test
A construction that always yields zero or an identity-only perturbation does not instantiate the target.

### T5 — Support/profile test
A physical intervention must state how its spatial/internal/support profile is represented; unexplained support may not be hidden in coefficients.

### T6 — Empirical-retrofit test
No bridge may derive its operator coefficients from the same transition frequencies it is later asked to predict.

### T7 — Outcome-strength firewall
Even a lawful `P -> J(P)` does not by itself establish `|M_i|^2`, rates, Born-like probabilities, or a transition kernel.

### T8 — Restricted-subclass test
A bridge may qualify for a nontrivial declared probe subclass without solving all possible SPEC probes, but the subclass must be prospectively characterizable.

## Outcome taxonomy

- `A__UNIQUE_MINIMAL_BRIDGE_CLASS_IDENTIFIED`
- `B__SMALL_NONDOMINATED_BRIDGE_SET_IDENTIFIED`
- `C__ONLY_EXPLICIT_NEW_PHYSICAL_SOURCE_PRIMITIVE_SURVIVES`
- `D__NO_NONTAUTOLOGICAL_CURRENT_BRIDGE_IDENTIFIED_AT_CURRENT_SCOPE`
- `E__EXISTING_FROZEN_STRUCTURE_ALREADY_SUPPLIES_RESTRICTED_CURRENT_BRIDGE`
- `F__UNDERDETERMINED`
- `G__REPAIR_REQUIRED`

## Sequencing guardrail

No candidate current may be promoted into a transition-strength law in this operation. If a viable bridge class is identified, a later separately preregistered gate must test normalization and channel-strength derivability.

## Deferred independent lane

`NFC_NS_OPENAI_FCP_INTAKE_CROSSWALK_GATE_V0_1` remains deferred and independent. No information from the OpenAI Navier–Stokes paper or its FCP intake may influence this bridge design-space adjudication.