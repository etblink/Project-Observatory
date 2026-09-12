# NFC NS Scale-Local Force Descriptor Specification Gate v0.1

STATUS = COMPLETE

PREREGISTRATION_COMMIT = `3ad0394f2b11e77b994c2aa75641d5dba5e49dc4`
BASE_ACCEPTANCE_COMMIT = `3d9e07072cbe15b4484f1162ea6504715c2b10da`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`B__MINIMAL_MULTISCALE_PROFILE_SPECIFIED__SCALAR_AGGREGATION_OPEN`

The lowest nontrivial prospective forcing descriptor that survives the gate is a profile-valued object defined relative to an explicitly frozen decomposition. No unique scalar aggregation is presently justified.

## Descriptor

Let `Pi = {Pi_{j,k}}` be a prospectively declared decomposition/localization family over scale index `j` and time/window index `k`, fixed before any regularity outcome is inspected.

Define

`F_{j,k} := Pi_{j,k} F`.

For each component, declare a local source seminorm/norm `N_{j,k}` and scale factor `a_{j,k}` before outcome inspection. The normalized local burden is

`bhat_{j,k}(F) := a_{j,k} N_{j,k}(F_{j,k})`.

The minimal descriptor is the full indexed profile

`Q_F^{Pi,N,a} := { bhat_{j,k}(F) }_{j,k}`.

The tuple `(Pi,N,a)` is part of the descriptor specification and cannot be altered after data/outcome inspection.

## Why profile-valued rather than scalar

Frozen NFC does not currently prove whether source burdens across scales should combine by maximum, sum, weighted sum, quadratic norm, transport product, or another rule. Prematurely choosing one would introduce unsupported physics/mathematics.

Therefore the descriptor retains the complete normalized burden profile and defers scalarization.

## Normalization discipline

The normalization `a_{j,k}` must be fixed by one of the following prospectively declared rules:

1. dimensional/scaling normalization derived from the declared forced NS interface;
2. comparison to a separately certified local dissipative scale;
3. a finite NFC/window normalization derived by an explicit bridge theorem.

No normalization is selected merely because it separates the OpenAI control from a desired regular regime.

## Physical-scale / NFC-window firewall

Physical scale index `j` and NFC window index `k` are distinct unless a bridge is proved. A descriptor may use a product index `(j,k)` without identifying them.

A future bridge may map physical scale-local source burden into an NFC window/source ledger, but that is the separately routed `NF-B` problem.

## Refinement policy

If the decomposition is refined, the descriptor must preserve provenance by retaining child components or by using an explicitly declared coarse-graining map. Hidden averaging is prohibited.

The gate does not assert decomposition-independence. Canonicity is relative to the declared decomposition and normalization rule.

## OpenAI/FCP control

The FCP intake records smooth compactly supported forcing, zero initial velocity, bounded kinetic energy, and finite-time blowup claim. The load-bearing audit records an explicitly oscillatory, band/scale-structured construction with separated supports and controlled stress realization.

This is sufficient to conclude that a multiscale descriptor is well posed in principle for the control: smoothness and compact support do not collapse the profile to a small or single-scale object.

However, the currently inspected FCP intake/audit material does not provide a complete prospectively normalized numerical table `{bhat_{j,k}}` for the entire forcing. Therefore:

`OPENAI_CONTROL_DESCRIPTOR_NUMERICAL_EVALUATION = NOT_COMPLETED`

This is an evidence limitation, not a descriptor failure.

## Level adjudication

`L0 support/smoothness metadata` — insufficient; OpenAI control is smooth and compactly supported.

`L1 unweighted multiscale burden profile` — nontrivial but normalization incomplete.

`L2 normalized dimensionless/local-comparison profile` — selected minimal target, provided `(Pi,N,a)` is frozen prospectively.

`L3 supremum scalarization` — not justified.

`L4 weighted-sum scalarization` — not justified.

`L5 source/dissipation profile` — promising downstream extension but requires a certified dissipative comparison bridge.

## Adversarial checks

### Zero-initial-data reversal
PASS. `Q_F` depends on the source, not `u_0`.

### Bounded-energy reversal
PASS. Bounded kinetic energy does not determine the source profile.

### Smooth compact support reversal
PASS. Smooth compact support imposes no automatic smallness claim on the normalized profile.

### Scale-concentration reversal
PASS by construction: the profile retains scale-local information rather than collapsing it globally.

### Outcome-fitting reversal
PASS: decomposition, local norm, normalization, and refinement policy are required to be frozen before use against an outcome.

## What is and is not established

Established:

- a mathematically coherent prospective multiscale source descriptor can be specified;
- profile-valued representation is less assumption-heavy than scalarization;
- the descriptor is compatible with later NFC source-ledger transport without identifying the two prematurely.

Not established:

- a unique decomposition;
- a unique norm;
- a unique normalization;
- a scalar threshold;
- a forced-regularity theorem;
- numerical classification of the OpenAI control as subcritical or supercritical under a selected profile.

## Scientific status

`PROSPECTIVE_MULTISCALE_DESCRIPTOR = YES_RELATIVE_TO_DECLARED_SPECIFICATION`
`UNIQUE_SOURCE_FORCED_DESCRIPTOR = NO`
`SCALAR_CONTROL_FUNCTIONAL = OPEN`
`OPENAI_NUMERICAL_PROFILE = NOT_YET_RECONSTRUCTED`
`FORCED_NS_REGULARITY = NOT_PROVED`

## Routing

`NEXT_OPERATION = NFC_NS_SOURCE_TO_LEDGER_BRIDGE_FEASIBILITY_GATE_V0_1`

That gate should ask whether the profile `Q_F` can be mapped into a typed, transport-weighted NFC source ledger without identifying physical scales with NFC windows or folding source burden into endogenous defect.

A later operation may perform a full numerical reconstruction of the OpenAI forcing profile only if the required source data and normalization specification are frozen prospectively.

No frozen NFC mutation.
No FCP readjudication.