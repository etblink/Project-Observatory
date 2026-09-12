# NFC NS ↔ OpenAI/FCP Intake Crosswalk Gate v0.1

STATUS = EXECUTED__OUTCOME_B__NO_DIRECT_CONTRADICTION__MATERIAL_FORCED_SCOPE_STRESS_TEST_IDENTIFIED

PREREGISTRATION_COMMIT = `aae321936d1f85c27eefd4cb422dc7c956f400fd`
OBSERVATORY_BASE_COMMIT = `58557ac6c8197ab860a652a1f2dd299ed37b0b0d`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`
FCP_OPENAI_NS_SOURCE_INTAKE_MERGE = `d2c3014357ed1de66849f66c5a8cc08e0d453b4b`
FCP_OPENAI_NS_LOAD_BEARING_AUDIT_MERGE = `de51ef31b86993034e93be56a7b2cff468ffdb66`
FCP_OPENAI_NS_EXTERNAL_REVIEW_MERGE = `6770011acefcc36f57f1492c08ff58f6442ba6f1`

## Primary outcome

`B__NO_DIRECT_CONTRADICTION__MATERIAL_FORCED_SCOPE_STRESS_TEST_IDENTIFIED`

The boundedly admitted OpenAI result does not directly contradict the frozen NFC NS branch because the FCP-admitted theorem is essentially a **smoothly forced** finite-time blowup construction, while the frozen NFC NS regularity chain is formulated without an external forcing term in its canonical energy/master-inequality structure.

However, the OpenAI result materially sharpens the NFC NS frontier by providing an exceptionally strong negative control against any silent extension of the frozen regularity criterion to forced dynamics.

## FCP-admitted external result used in this crosswalk

At FCP's accepted scope, the OpenAI theorem claim has the following controlling features:

- dimension 3;
- arbitrary fixed viscosity `nu > 0`;
- smooth compactly supported external force;
- zero initial velocity;
- smooth compactly supported solution before blowup time;
- uniformly bounded kinetic energy / `L^2` norm;
- `L^infinity` velocity blowup at finite time;
- claimed correspondence to Clay alternatives (C)/(D), with forcing essential;
- no promotion to an unforced blowup theorem.

FCP later reproduced the preregistered load-bearing analytic nodes A1-A4 and global parameter-consistency gate without finding a material defect, while explicitly preserving the ceiling: not a full independent human re-proof, not global consensus, not Clay recognition, and no authorized NFC consequence.

## Lane 1 — Scope correspondence

`DIRECT_SCOPE_MATCH = NO`

Frozen NFC NS defines an endpoint target in terms of a Leray weak solution and `L^infinity_t H^1_x` regularity. Its canonical Galerkin energy inequality has the unforced form

`||u(t)||_2^2 + 2 nu integral ||grad u||_2^2 <= ||u_0||_2^2`.

No external-force work term appears in that inequality. Likewise, the frozen master inequality depends on viscosity, coercivity, nonlinearity, and `||u_0||_{H^s}`, but contains no external-force norm/source term.

Therefore the OpenAI forced construction is outside the demonstrated frozen scope of the NFC NS regularity criterion.

This blocks Outcome A.

## Lane 2 — Energy lesson

`BOUNDED_L2_SUFFICIENT_FOR_REGULARITY = NO`

The OpenAI result is directly relevant as a scope-controlled counterexample to any inference of the form

`bounded kinetic energy / bounded L2 -> bounded velocity / regularity`

in forced three-dimensional Navier–Stokes.

This does **not** falsify frozen NFC NS, because the branch's endpoint chain depends on stronger obstruction/continuation hypotheses, not on the `L^2` energy estimate alone.

The result does, however, strengthen a methodological guardrail: the Leray energy estimate is an existence/control input, not a regularity certificate.

## Lane 3 — External-force term

`FORCED_SCOPE_SOURCE_TERM_PRESENT_IN_FROZEN_NFC_NS = NO`

The frozen Stage-2a balance identity contains convection, viscosity/dissipation, and the NFC defect burden. The symbol `f` used there is a test function, not an externally prescribed physical forcing field.

A forced-scope extension would therefore require an explicit additional source/work term together with a lawful source-descended representation of the force in the obstruction/ledger architecture.

The OpenAI construction makes this omission operationally important rather than merely formal.

## Lane 4 — Master-inequality adversarial test

This is the strongest crosswalk finding.

Frozen NFC NS states the master inequality schematically as

`nu * c_* > 2 * C_NL(s) * ||u_0||_{H^s}`

along with NS-A through NS-E.

The OpenAI construction starts from

`u_0 = 0`.

Therefore, if one were to **naively** extend the frozen master inequality to the forced problem without adding a force/source contribution, its right-hand side would vanish and the inequality would be automatically favorable for every `nu > 0` with positive `c_*`.

But the FCP-admitted OpenAI construction claims finite-time blowup under smooth forcing.

Hence:

`NAIVE_FORCED_SCOPE_REUSE_OF_CURRENT_MASTER_INEQUALITY = INVALIDATED_AS_A_GENERALIZATION`

This is not a contradiction to the frozen theorem because the forced case is outside its established scope. It is a decisive warning that any future forced extension must contain an additional forcing/source burden or must explicitly fail another declared hypothesis on the OpenAI construction.

## Lane 5 — Common-state bridge

`DIRECT_EVIDENCE_FOR_COMMON_STATE_BRIDGE = NONE`
`DIRECT_COUNTEREXAMPLE_TO_COMMON_STATE_BRIDGE = NONE`

The open common-state obligation must supply common temporal state, renewal control, same-state obstruction comparison, and a ledger-state map linking the contracting ledger quantity to the transport-weighted imbalance.

The OpenAI proof does not use NFC's obstruction/ledger variables and therefore does not directly discharge or refute this bridge.

However, it supplies a future adversarial criterion: in a forced-scope NFC encoding of the OpenAI solution, any claimed common-state bridge must either

1. visibly fail one of its hypotheses before blowup, or
2. map the forcing-induced growth into an obstruction/source term that prevents the false contraction-to-regularity conclusion.

A bridge that remained fully satisfied while predicting forced regularity on this benchmark would be falsified.

## Lane 6 — UWB

`DIRECT_EVIDENCE_FOR_UWB = NONE`
`DIRECT_COUNTEREXAMPLE_TO_UWB = NONE`

Compact spatial support of the OpenAI force/solution is not equivalent to NFC's `UWB` uniform window-boundary hypothesis. UWB concerns the variable-window boundary/uniformity architecture internal to NFC.

No lawful map from compact support to UWB satisfaction or failure is presently frozen.

Therefore the OpenAI construction neither discharges nor refutes UWB.

## Lane 7 — Obstruction sensitivity

`FORCED_SCOPE_OBSTRUCTION_BENCHMARK = MATERIAL`

A credible forced-scope NFC obstruction architecture should detect the OpenAI blowup construction before endpoint closure. At least one of the following must occur:

- the external force contributes a source burden that prevents contraction;
- the common-state bridge fails;
- UWB/global-uniformity fails;
- the active continuation criterion fails;
- another explicitly declared forced-scope hypothesis fails.

If a forced extension encoded the OpenAI solution while all its regularity hypotheses remained satisfied, that extension would be empirically/mathematically falsified at the theorem-correspondence level.

## Lane 8 — Continuation criterion

`FROZEN_CONTINUATION_CHAIN_STATUS = UNCHANGED`

The existing NS.6.1/NS.7.1 chain remains conditional on hypothetical discharge of the common-state bridge and separately on UWB where global-uniformity is consumed.

The OpenAI intake supplies no reason to promote or demote those internal statuses directly.

Its effect is instead to sharpen what a future **forced** continuation criterion must account for.

## Lane 9 — Relation to the OpenAI proof architecture

FCP's load-bearing audit found no material defect in its preregistered A1-A4 and global-parameter checks. That raises the value of the construction as an adversarial benchmark: it is not merely a headline-level claimed counterexample, but a source packet with a reproduced formal build and targeted analytic checks at FCP's declared scope.

This still does not authorize importing the OpenAI proof machinery into NFC.

## Lane 10 — Scientific consequence

The strongest justified consequence is not

`OpenAI disproves NFC NS`

and not

`OpenAI validates NFC NS`.

It is:

`OpenAI identifies the exact missing burden in any forced-scope generalization of the current NFC NS regularity architecture.`

That burden is an explicit source/forcing contribution to the balance, obstruction, and continuation machinery.

## Sharpened forced-scope architecture

A future extension would need, at minimum, a forced balance of the schematic form

`d/dt E + dissipation <= nonlinear/defect burden + forcing work/source burden`,

and a corresponding obstruction evolution law in which the forcing contribution is visible rather than absorbed into existing defect notation by fiat.

The master inequality would then require an additional source-size/control term or an equivalent source-sensitive hypothesis.

The exact form is **not** derived in this audit.

## Outcome review

`A__DIRECT_MATERIAL_CONTRADICTION` — NOT EARNED: scope mismatch is decisive.

`B__NO_DIRECT_CONTRADICTION__MATERIAL_FORCED_SCOPE_STRESS_TEST_IDENTIFIED` — EARNED.

`C__MATERIALLY_STRENGTHENS_EXISTING_NFC_NS_BRIDGE` — NOT EARNED: no common-state/UWB theorem is strengthened.

`D__NO_MATERIAL_RELEVANCE` — REJECTED: the zero-initial-data/master-inequality stress test is materially informative.

`E__SCOPE_AMBIGUITY_REPAIR_REQUIRED` — NOT EARNED: the frozen branch is sufficiently clear to establish that external forcing is not present in the demonstrated energy/master-inequality chain.

## Routing

`NEXT_NS_OPERATION = NFC_NS_FORCED_SCOPE_EXTENSION_FEASIBILITY_GATE_V0_1`

This next operation should **not** attempt to prove forced regularity. It should ask only whether the frozen NS architecture has a noncircular place to insert a source term into:

1. the discrete balance identity;
2. the obstruction/defect ledger;
3. the common-state bridge;
4. the active continuation criterion;
5. the master inequality.

The OpenAI construction should be preregistered as a negative-control benchmark: any candidate forced extension must classify which hypothesis fails on that construction rather than silently predicting regularity.

`NFC_FROZEN_CANON_MUTATION = NO`
`FCP_READJUDICATION = NO`
`OPENAI_THEOREM_IMPORT_INTO_NFC = NO`