# NFC SPEC-SM Probe Descriptor Source-Derivability Gate v0.1

STATUS = EXECUTED__OUTCOME_B__PARTIAL_SOURCE_DERIVED_DESCRIPTOR_EXISTS__PHYSICAL_CONTROL_FIELDS_OPEN

PREREGISTRATION_COMMIT = `eb73556ff4003222501b0fbe57a7770f86d138ac`
BASE_ACCEPTANCE_COMMIT = `53d9c4ad281ca31df475a49bcc45d88fcecebe19`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`B__PARTIAL_SOURCE_DERIVED_DESCRIPTOR_EXISTS__PHYSICAL_CONTROL_FIELDS_OPEN`

Frozen SPEC/SM structure does derive a nontrivial prospectively available descriptor for a lawful probe episode, but it does not yet determine enough physical control information to constrain a unique current map.

## Field-by-field adjudication

### 1. Probe-family/type identity

`DERIVED_AT_DECLARED_SPEC_SCOPE = YES`

A SPEC probe is a declared admissible process `P in P`, so probe-family/type membership is prospectively available before an outcome.

### 2. Certified observable-domain identity

`DERIVED = YES`

The spectroscopy target regime explicitly declares `C_obs`, and the probe acts on an object `X in C_obs`.

### 3. Response-window identity

`DERIVED = YES`

The spectroscopy target regime explicitly declares response window `W`. The window is part of the target regime before the probe episode is evaluated.

### 4. Source-visible gauge/representation channel

`GENERICALLY_SOURCE_SELECTED = NO`
`CONDITIONALLY_AVAILABLE_IN_RESTRICTED_DECLARED_REGIMES = YES`

The gauge-response SPEC regime and SM matter transfer provide certified gauge/matter representation content. Generator compatibility establishes that admissible probes exercise spectral modes. However, frozen NFC does not assign each generic probe to one unique gauge/matter representation channel before the outcome. A restricted future probe class may declare such a channel if it is independently source-visible.

### 5. Intervention support/context descriptor

`PHYSICAL_SUPPORT_PROFILE_DERIVED = NO`

Book-I/SPEC process accountability constrains admissibility and quotient visibility, but the frozen SPEC target regime does not provide a physical support/profile map for generic probes. This is one of the principal missing physical-control fields.

### 6. Preparation/reset/comparability metadata

`DERIVED_AS_GENERIC_PHYSICAL_PROTOCOL = NO`

A probe episode has an ordered before/after record, but frozen SPEC does not supply a generic laboratory-style preparation/reset theorem ensuring repeated trials begin from one physically identical prepared state. Such protocol information cannot be inferred from the post-response ledger.

### 7. Temporal/order position in a lawful probe chain

`DERIVED = YES_AT_DECLARED_CHAIN_SCOPE`

Probe episodes are ordered applications, and multistep ledgers concatenate along declared lawful probe chains. Sequence position/provenance can therefore be known prospectively when a chain is declared.

### 8. Pre-intervention quotient-visible state/class

`DERIVED = YES`

The episode acts on a certified observable object `X`, and the accepted relational-action analysis establishes quotient-visible parent classes. The pre-state/class may therefore enter `q(P)` without using future response information.

### 9. Ledger/provenance identity available before outcome

`PARTIAL = YES`

The identity of the declared probe, target regime, pre-state, response window, and chain position is prospective. The **value of the transition ledger**, by contrast, includes induced before/after response change and is not available before the outcome. A lawful descriptor may carry ledger schema/provenance but not the realized ledger increment.

### 10. Control-strength parameter

`SOURCE_DERIVED = NO`

No generic physical intensity/strength parameter for a probe is source-selected in frozen SPEC/SM. The SM coupling-transfer ratios constrain sector structure but do not determine the magnitude/profile of an external intervention.

## Canonical partial descriptor

The strongest source-derived prospective descriptor supported at audited scope is therefore of the form

`q_0(P;X) = (probe-class, C_obs, W, pre-state/class, declared chain position, source/provenance metadata [, restricted representation-channel when independently certified])`.

The bracketed representation-channel field is conditional and may not be assigned generically.

The following are **not** part of `q_0`:

- post-intervention response class;
- realized transition-ledger increment;
- measured frequency;
- fitted amplitude/current coefficient;
- future outcome label;
- generic physical support/profile;
- generic preparation/reset certificate;
- generic probe strength.

## Mandatory tests

### Pre/post separation

PASS. Prospective fields were separated from response-dependent ledger values.

### Quotient invariance

PASS. The accepted descriptor uses only declared probe/target metadata and quotient-visible pre-state information.

### Support/profile sufficiency

FAIL FOR COMPLETE CURRENT INPUT. Physical support/profile remains open.

### Representation-channel sufficiency

PARTIAL. Restricted gauge-response/matter channel metadata may be source-visible, but no unique generic probe-channel map is frozen.

### Sequence/composition sufficiency

PASS AT DECLARED SPEC CHAIN SCOPE.

### Reset/preparation sufficiency

FAIL FOR GENERIC PHYSICAL REPEATABILITY.

### Hidden-control-parameter test

FAIL FOR COMPLETE CURRENT INPUT. Probe strength/control magnitude is not source-derived.

### No-retrofit test

PASS. No post-outcome frequency, amplitude, or realized transition ledger was admitted into the prospective descriptor.

## Consequence for K6

The hybrid route remains viable but is now decomposed more sharply:

`P -> q_0(P)` is partly source-derived,

while a physical-protocol completion must add at least some subset of

`(support/profile, preparation/reset, physical control-strength, restricted channel assignment)`

before a non-tautological current law can be tested.

Thus K6 is not one missing arrow but two:

`P -> q_0(P) -> q_phys(P) -> J_SM(P)`

where `q_phys(P)` contains prospectively declared physical-control information not presently supplied by frozen NFC.

## Scientific status

`SOURCE_DERIVED_PARTIAL_DESCRIPTOR = YES`
`COMPLETE_PHYSICAL_PROBE_DESCRIPTOR = NO`
`POST_OUTCOME_INFORMATION_EXCLUDED = YES`
`GENERIC_PHYSICAL_SUPPORT_PROFILE = OPEN`
`GENERIC_PREPARATION_RESET_PROTOCOL = OPEN`
`GENERIC_PROBE_STRENGTH = OPEN`
`GENERIC_UNIQUE_REPRESENTATION_CHANNEL = OPEN`

## Routing

`NEXT_CURRENT_LANE_OPERATION = NFC_SPEC_SM_RESTRICTED_PHYSICAL_PROBE_PROTOCOL_DESIGN_GATE_V0_1`

This gate should design the weakest prospectively specifiable physical probe protocol that supplies the missing control fields without importing transition outcomes.

`INDEPENDENT_READY_OPERATION = NFC_NS_OPENAI_FCP_INTAKE_CROSSWALK_GATE_V0_1`

The NS/OpenAI-FCP crosswalk is now safe to open independently; nothing from it was used in this adjudication.

`NFC_FROZEN_CANON_MUTATION = NO`
`FCP_READJUDICATION = NO`
`PGH_READJUDICATION = NO`