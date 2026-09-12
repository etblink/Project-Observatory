# NFC SPEC-SM Probe Descriptor Source-Derivability Gate — Preregistration v0.1

STATUS = PREREGISTERED__NOT_YET_ADJUDICATED

BASE_ACCEPTANCE_COMMIT = `53d9c4ad281ca31df475a49bcc45d88fcecebe19`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Question

Can frozen SPEC/SM structure derive a prospectively available, quotient-visible probe descriptor `q(P)` rich enough to constrain a later physical-current law `q(P) -> J_SM(P)`, without encoding the current, measured transition frequencies, or post-intervention outcome?

## Candidate descriptor fields

The audit must separately classify whether frozen NFC derives, merely permits, or lacks each field:

1. probe-family/type identity;
2. certified observable-domain identity;
3. declared response-window identity;
4. source-visible gauge/representation channel;
5. intervention support/context descriptor;
6. preparation/reset/comparability metadata;
7. temporal/order position in a lawful probe chain;
8. pre-intervention quotient-visible state/class;
9. ledger/provenance identity available before outcome;
10. any required control-strength parameter.

## Firewall

The descriptor may not contain:

- post-intervention response class;
- observed branching frequency;
- fitted amplitude or current coefficient;
- future outcome label;
- any quantity whose definition presupposes `J_SM(P)`.

## Mandatory tests

- pre/post separation;
- quotient invariance;
- support/profile sufficiency;
- representation-channel sufficiency;
- sequence/composition sufficiency;
- reset/preparation sufficiency;
- hidden-control-parameter test;
- no-retrofit test.

## Outcomes

- `A__SUFFICIENT_SOURCE_DERIVED_PROBE_DESCRIPTOR_EXISTS`
- `B__PARTIAL_SOURCE_DERIVED_DESCRIPTOR_EXISTS__PHYSICAL_CONTROL_FIELDS_OPEN`
- `C__ONLY_THIN_PROBE_LABEL_DERIVED__INSUFFICIENT_FOR_CURRENT_BRIDGE`
- `D__NO_NONTAUTOLOGICAL_PREINTERVENTION_DESCRIPTOR_DERIVED`
- `E__UNDERDETERMINED`
- `F__REPAIR_REQUIRED`

No current law, current normalization, transition-strength law, or empirical fit is authorized in this operation.

`DEFERRED_SEPARATE_OPERATION = NFC_NS_OPENAI_FCP_INTAKE_CROSSWALK_GATE_V0_1`