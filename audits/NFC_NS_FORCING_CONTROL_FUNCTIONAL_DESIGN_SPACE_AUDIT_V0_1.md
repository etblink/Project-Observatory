# NFC NS Forcing-Control Functional Design-Space Audit v0.1

STATUS = COMPLETE

PREREGISTRATION_COMMIT = `69e03f9f0d47fb3c72aa1a966c61bc4b4f2e3a74`
BASE_ACCEPTANCE_COMMIT = `71fb2da441133abfcf556765bf4744d21417f9d9`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`B__SMALL_NONDOMINATED_FUNCTIONAL_SET_IDENTIFIED`

No unique source-forced forcing-control functional is present in frozen NFC. Two candidate classes survive the preregistered criteria as nondominated research targets, with different strengths:

- `NF-A__PROSPECTIVE_SCALE_LOCAL_FORCE_DESCRIPTOR`
- `NF-B__NFC_NATIVE_TRANSPORT_WEIGHTED_SOURCE_LEDGER`

A state-coupled work-injection functional survives only as an a posteriori / continuation diagnostic and is therefore not selected as the first source descriptor.

## Frozen control

The OpenAI/FCP construction is used only as a preregistered adversarial control:

- smooth compactly supported force;
- zero initial velocity;
- every positive viscosity;
- uniformly bounded kinetic energy;
- finite-time `L^infty` blowup claim;
- no unforced-problem or NFC promotion.

The audit does not use knowledge of the blowup outcome to fit candidate coefficients or thresholds.

## Candidate F1 — cumulative work / energy injection

A natural physical quantity is a work-injection functional of schematic form

`W_F(t) = integral_0^t <F(s), u(s)> ds`

or a positive-envelope variant.

### Strengths

- physically interpretable;
- enters ordinary forced energy balances naturally;
- distinguishes zero initial data from zero forcing;
- can expose source-driven energy transfer even when `u_0 = 0`.

### Failure as first prospective descriptor

Its value depends on the evolving solution `u`. Therefore, without an independent upper bound expressed entirely in predeclared source/control data, it is not a purely prospective force descriptor. In the present program it qualifies as a state-coupled continuation diagnostic, not as the primary independent source-control functional.

`F1_STATUS = SURVIVES_ONLY_AS_STATE_COUPLED_A_POSTERIORI_CRITERION`

## Candidate F2 — global force-only norm

Schematic class:

`N_global(F) = ||F||_X`

for a prospectively fixed continuum norm `X` licensed by the branch interface.

### Strengths

- force-only and prospective;
- zero initial velocity does not trivialize it;
- smooth compact support does not force smallness.

### Weakness

Frozen NFC currently supplies no theorem selecting the norm `X`, its scaling, or a threshold linking `||F||_X` to the NS obstruction/common-state chain. Moreover, a purely global norm may miss dangerous concentration into scales relevant to nonlinear transfer.

`F2_STATUS = PLAUSIBLE_BUT_UNDERSELECTED_AND_POTENTIALLY_SCALE_BLIND`

## Candidate F3 — scale-local / frequency-local force descriptor

Define a prospectively fixed decomposition compatible with the declared continuum interface or finite-window hierarchy and assign source burden by scale/window. The exact formula is not frozen; the minimal schema is

`N_scale(F) = sup_or_sum_j w_j * Burden(F_j)`

with decomposition, weights, normalization, and threshold fixed before outcome data.

### Strengths

- remains force-only and prospective;
- can distinguish smoothness from concentration;
- naturally matches nonlinear-transfer questions;
- can be challenged on the OpenAI construction without post-hoc fitting.

### Weakness

No frozen NFC theorem selects the decomposition, weights, or continuum norm. This is therefore a lawful candidate design class, not a derived law.

`F3_STATUS = SURVIVES_AS_NF_A`

## Candidate F4 — NFC source-ledger / renewal-count burden

The forced-scope extension architecture permits a separate source channel rather than folding forcing into endogenous defect. The minimal discrete object is a source ledger

`S_F(W_k -> W_{k+1})`

recording only forcing-induced, quotient-visible source contribution on each declared window transition.

### Strengths

- native to the existing ledger architecture;
- preserves source/endogenous-defect separation;
- prospective if the source event rule is fixed before evolution;
- naturally compatible with common-state enlargement and renewal accounting.

### Weakness

Frozen NFC does not yet define how a continuum force maps to source events or their magnitudes. Therefore this is a schema requiring a new typed bridge.

`F4_STATUS = SURVIVES_AS_COMPONENT_OF_NF_B`

## Candidate F5 — transport-weighted source burden

The strongest NFC-native candidate is a transport-weighted source ledger, schematically

`S_k^tr = T_k[S_F]`

where `T_k` is declared by the same window/transport architecture used for the NS obstruction, but source and endogenous defect remain typed separately.

A possible forced recurrence would then take only schematic form

`O_{k+m} <= q O_k + S_k^tr`,

with no theorem status assigned here.

### Strengths

- fits existing window adaptation and transport machinery;
- preserves explicit provenance of external forcing;
- can enter the enlarged common state as a contemporaneous source component;
- is not automatically small for smooth compactly supported forcing;
- does not vanish when `u_0 = 0`;
- gives a precise theorem target for a future forced common-state bridge.

### Weakness

The source-to-ledger map, normalization, and source transport rule are all missing. These are new burdens, not consequences of present NFC.

`F5_STATUS = SURVIVES_AS_NF_B`

## Candidate F6 — source/dissipation ratio

Schematic form:

`R_F = SourceBurden / DissipativeReserve`.

This has attractive interpretation but is downstream of defining the source burden itself. It therefore cannot be the primitive candidate.

`F6_STATUS = DERIVED_DIAGNOSTIC_ONLY_AFTER_NF_A_OR_NF_B`

## Candidate F7 — support/geometry burden

Compact support, support diameter, and geometry may contribute to source control, but the OpenAI control itself has smooth compact support. Therefore support alone cannot be sufficient.

`F7_STATUS = AUXILIARY_ONLY`

## Candidate F8 — history/common-state descriptor

A forcing history descriptor is required if continuation depends on source history rather than only current force. This is architecturally legitimate because the accepted forced extension already requires an enlarged common state containing source context/history.

However, this is a state architecture, not yet a scalar control functional.

`F8_STATUS = REQUIRED_CONTEXT_LAYER__NOT_STANDALONE_CONTROL_FUNCTIONAL`

## Candidate F9 — hybrid

The most credible longer-term construction combines:

1. a prospective scale-local physical source descriptor (`NF-A`), with
2. a lawful source-to-ledger/transport bridge producing (`NF-B`).

This hybrid would distinguish physical source size/concentration from its NFC-native bookkeeping representation.

`F9_STATUS = BEST_LONGER_TERM_ARCHITECTURE`

## Candidate F10 — no justified candidate

Rejected because two noncircular candidate classes survive as research objects. Neither is yet a theorem or physically validated law.

## OpenAI adversarial-control tests

### Zero-initial-data reversal
PASS for `NF-A` and `NF-B`: neither vanishes merely because `u_0=0`.

### Bounded-energy reversal
PASS at design level: neither treats bounded kinetic energy as sufficient source subcriticality.

### Smooth/compact-support reversal
PASS: smooth compact support does not imply small `NF-A` or small `NF-B`.

### Outcome-fitting reversal
PASS: no threshold, coefficient, decomposition, or source-event rule is fitted to the known control outcome.

### Forced-extension consistency
PASS at schema level: both candidates can remain distinct from the endogenous defect burden and can be inserted into an enlarged common-state architecture.

## Comparative adjudication

`NF-A__PROSPECTIVE_SCALE_LOCAL_FORCE_DESCRIPTOR`

Best property: direct physical meaning and prospective falsifiability.
Main deficit: weakly tied to NFC until a continuum/source bridge is proved.

`NF-B__NFC_NATIVE_TRANSPORT_WEIGHTED_SOURCE_LEDGER`

Best property: strongest compatibility with the existing NS ledger/window/common-state architecture.
Main deficit: requires a new typed map from physical forcing into source ledger entries and source transport.

Neither dominates the other. `NF-A` is the better physical-source descriptor; `NF-B` is the better NFC-native continuation interface.

## Selected sequencing

`FIRST_TARGET = NF_A__PROSPECTIVE_SCALE_LOCAL_FORCE_DESCRIPTOR`

Reason: it is upstream of the NFC bookkeeping bridge and can be specified independently of the eventual solution. If no physically sensible prospective descriptor can be fixed, constructing a source ledger merely relocates the ambiguity.

`SECOND_TARGET = NF_B__NFC_NATIVE_TRANSPORT_WEIGHTED_SOURCE_LEDGER`

The next operation should therefore freeze candidate requirements for `NF-A` and test whether the OpenAI/FCP source material supplies enough published pre-outcome information to instantiate the descriptor without using the blowup result itself.

## Scientific status

`FORCED_NS_REGULARITY_PROVED = NO`
`FROZEN_NFC_NS_CONTRADICTED = NO`
`UNIQUE_FORCING_FUNCTIONAL_DERIVED = NO`
`NONDOMINATED_CANDIDATE_SET = YES`
`OPENAI_CONTROL = ACTIVE_NEGATIVE_CONTROL`
`COMMON_STATE_BRIDGE = STILL_OPEN`
`UWB = STILL_SEPARATE_AND_UNPROVED`

## Routing

`NEXT_OPERATION = NFC_NS_SCALE_LOCAL_FORCE_DESCRIPTOR_SPECIFICATION_GATE_V0_1`
`FOLLOW_ON = NFC_NS_SOURCE_TO_LEDGER_BRIDGE_FEASIBILITY_GATE_V0_1`

No frozen NFC mutation.
No FCP readjudication.
No claim of Clay/global acceptance.