# NFC SPEC-SM Probe-Current Bridge Design-Space Audit v0.1

STATUS = EXECUTED__OUTCOME_B__SMALL_NONDOMINATED_BRIDGE_SET_IDENTIFIED

PREREGISTRATION_COMMIT = `399a3b459545c4050d2e1fd3e342811e4bae83f2`
BASE_ACCEPTANCE_COMMIT = `7fdd5820794dd7842ff359ed4a51f50445953be8`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`B__SMALL_NONDOMINATED_BRIDGE_SET_IDENTIFIED`

No existing frozen theorem already supplies a restricted physical current bridge. The design-space comparison leaves two scientifically admissible, nondominated routes:

1. `K5_EXPLICIT_PHYSICAL_SOURCE_CURRENT` — directly add one prospectively declared physical current/source map with transformation, support/profile, domain, and normalization status fully exposed;
2. `K6_HYBRID_PROBE_DESCRIPTOR_TO_CURRENT` — first derive a quotient-visible probe descriptor from the already-certified SPEC probe/response architecture, then separately map that descriptor into the SM/SPEC operator/current arena by an explicit new physical bridge.

Neither route is established as true. They optimize different goals.

## Frozen positive structure carried into the audit

The frozen corpus already provides enough structure to constrain the codomain of a future current:

- source-descended SM matter representation content;
- a transferred gauge action on that content;
- the screened vacuum sector `H_0`;
- finite Hermitian matter generator `D_M`;
- matter-extended SPEC operator packet `H_mat = H \otimes I_M + I \otimes D_M`;
- conditional relative gauge-sector coupling information;
- SPEC quotient-visible probe episodes and episode-level transition ledgers.

Thus the missing object is no longer an arbitrary operator arena. It is an explicit map from a prospectively described physical intervention into that constrained arena.

## Candidate adjudication

### K1 — Generator-deformation bridge

`DISPOSITION = INCOMPLETE_AS_STANDALONE_BRIDGE__VALID_TARGET_FORM`

Writing

`D_M -> D_M + V_P`

or

`H_mat -> H_mat + V_P`

is mathematically legitimate after `V_P` is known, but it does not derive `V_P` from a physical probe. If `P` is defined to be the operator perturbation, the bridge is tautological. If `P` is independently operational, an additional map `P -> V_P` remains exactly the missing object.

K1 is therefore retained as the natural landing form of a future bridge, not as a complete bridge class by itself.

### K2 — Gauge-source/current bridge

`DISPOSITION = PHYSICALLY_NATURAL__NOT_SOURCE_DERIVED`

The SM gauge representation structure and relative coupling constraints make a gauge-covariant current a natural possible codomain. But the frozen corpus contains no theorem turning a generic SPEC probe into such a source/current. Importing a familiar Noether or textbook gauge current would violate the audit firewall unless separately declared as new physical structure.

K2 is best understood as a specialization of K5 or K6 once the current bridge has been supplied.

### K3 — Vacuum-sector insertion bridge

`DISPOSITION = DOMAIN_COMPATIBLE_TARGET__NOT_DERIVED`

`H_0` and its matter extension provide a legitimate physical operator domain. A bounded or form-compatible nonzero probe insertion could in principle act there. But frozen NFC does not select one from the operational probe record. Vacuum/domain compatibility constrains a candidate; it does not create it.

### K4 — Response-derived operator bridge

`DISPOSITION = NO_UNIQUE_PHYSICAL_OPERATOR_DERIVED`

The accepted SPEC relational/ledger action supplies support, before/after response information, lawful composition, and additive bookkeeping. Combining those data with `D_M`, `H_0`, or `L_SPEC` admits many algebraic constructions (commutators, derivations, free linearizations, ledger characters, etc.). None is source-selected as the physical intervention operator.

The same quotient-visible probe record can support inequivalent operator assignments without changing its certified relational semantics. Therefore K4 fails uniqueness/authority at current frozen scope.

### K5 — Explicit external physical-source primitive

`DISPOSITION = NONDOMINATED__MINIMAL_PHYSICAL_ROUTE`

A lawful new premise may directly declare a physical current map

`J_SM : P_phys -> A_SM/SPEC`

provided the probe class is specified prospectively and the map declares:

- gauge/representation transformation law;
- support/profile rule;
- domain and vacuum compatibility;
- nontriviality conditions;
- normalization status;
- composition/sequence behavior if relevant;
- failure conditions;
- explicit separation from transition amplitudes and probabilities.

This route adds the least intermediate structure. Its disadvantage is that it places most of the new physics directly in the current map, so scientific legitimacy depends on strong prospective specification and empirical exposure.

### K6 — Hybrid representation-plus-current bridge

`DISPOSITION = NONDOMINATED__BEST_SOURCE_COUPLED_ROUTE`

A second viable route is to split the bridge:

`P_phys -> q(P) -> J_SM(P)`

where `q(P)` is a quotient-visible, source-descended probe descriptor derived from the existing SPEC probe/response architecture, and the second arrow is the explicitly new physical current law.

Examples of admissible descriptor content include certified probe class, declared support/context class, response-window label, representation/gauge channel label when independently source-visible, and episode-ledger metadata. The descriptor may not contain measured branching frequencies or the desired operator coefficients.

This route adds more structure than K5, but it gains a stronger anti-smuggling interface: the physical bridge acts only on source-certified probe descriptors rather than unrestricted raw experimental labels.

It is therefore the best current candidate if the research goal is to preserve maximal NFC source coupling while still introducing the minimum genuinely new physical law.

## Mandatory adversarial tests

### T1 — Tautology

PASS for K5/K6 only if the physical probe is specified independently of `J_SM(P)`. K1 alone fails as a bridge when `P` is merely renamed `V_P`.

### T2 — Rescaling

OPEN AND EXPLICIT. For either K5 or K6, `J_P -> a J_P` may remain a live freedom until a later normalization theorem or calibration principle fixes `a`. This does not invalidate the structural current bridge, but blocks calibrated strength claims.

### T3 — Gauge redundancy

PASS. Gauge re-encodings are excluded as physical currents. A qualifying current must transform covariantly rather than merely enact gauge redundancy.

### T4 — Zero current

PASS criterion retained: the chosen declared probe subclass must produce a demonstrably nonzero insertion for at least one admissible intervention.

### T5 — Support/profile

DECISIVE. A current map with unspecified support/profile is underdefined. K5 must declare it directly; K6 may derive some support/context information in `q(P)` before applying the current law.

### T6 — Empirical retrofit

PASS firewall. No operator coefficient may be inferred from the transition frequencies that the eventual model is supposed to predict.

### T7 — Outcome-strength firewall

PASS. Even a completed `P -> J_SM(P)` does not yet yield channel amplitudes, rates, or probabilities. Those remain separate later burdens.

### T8 — Restricted subclass

SUPPORTED IN PRINCIPLE, NOT YET INSTANTIATED. A first physical candidate should target one prospectively identifiable probe family rather than generic spectroscopy. The frozen corpus does not yet select which family.

## Dominance analysis

K1, K2, and K3 are useful **landing forms or specializations** but do not solve the mapping problem independently.

K4 is the strongest attempt to avoid new physics entirely, but fails because the frozen probe/ledger data do not source-select one physical numerical operator assignment.

K5 and K6 remain nondominated:

- K5 minimizes added architecture;
- K6 maximizes source coupling and auditability.

Neither is a truth preference.

## Recommended sequencing

`BEST_FIRST_BRIDGE_DESIGN_TARGET = K6_HYBRID_PROBE_DESCRIPTOR_TO_CURRENT`

Reason: K6 lets the next operation test how much of the current's input can already be fixed by frozen SPEC before adding the genuinely new physical arrow. A negative result naturally collapses back to K5. A positive result reduces the freedom in the eventual physical-current premise.

`FALLBACK_PHYSICAL_ROUTE = K5_EXPLICIT_PHYSICAL_SOURCE_CURRENT`

## Sharpened frontier

The current chain is:

`physical probe P`
` -> certified SPEC episode/response data`
` -> ? source-descended probe descriptor q(P)`
` -> ? physical current law B_SM-PROBE-CURRENT`
` -> J_SM(P)`
` -> ? normalization`
` -> ? matrix-element/channel-strength rule`
` -> transition kernel`.

The first question is therefore no longer whether a current can be imagined, but whether the **input descriptor to that current can be source-selected before new physical coefficients enter**.

## Scientific status

`FROZEN_SM_CURRENT_BRIDGE = NOT_DERIVED`
`VIABLE_NEW_PHYSICS_BRIDGE_CLASSES = {K5, K6}`
`TRUTH_PREFERENCE_K5_VS_K6 = NO`
`BEST_FIRST_DESIGN_TARGET = K6`
`CURRENT_NORMALIZATION = OPEN`
`CHANNEL_STRENGTHS = OPEN`
`EMPIRICAL_SUPPORT_FOR_NEW_CURRENT = NONE`

## Routing

`NEXT_OPERATION = NFC_SPEC_SM_PROBE_DESCRIPTOR_SOURCE_DERIVABILITY_GATE_V0_1`

This next gate should determine whether frozen SPEC/SM structure can derive a sufficiently rich quotient-visible descriptor `q(P)` for a restricted physical probe class—support/context, representation channel, response window, preparation/reset metadata—without encoding the current or transition outcome itself.

`DEFERRED_SEPARATE_OPERATION = NFC_NS_OPENAI_FCP_INTAKE_CROSSWALK_GATE_V0_1`

`NFC_FROZEN_CANON_MUTATION = NO`
`FCP_READJUDICATION = NO`
`PGH_READJUDICATION = NO`