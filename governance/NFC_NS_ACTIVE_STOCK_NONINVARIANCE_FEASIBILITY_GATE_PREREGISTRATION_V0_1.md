# NFC NS Active-Stock Noninvariance Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: dbf731473080c62b8c0aaea9031fcbcdd1bd49b2
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
Does frozen NFC force a deterministic noninvariance/turnover property for active interface-stock witnesses strong enough that a uniform positive fraction of active stock must enter H1 quotient loss or H2 mixing loss on every sufficiently late relevant block/window?

## Candidate routes
N1 ALL ACTIVE STOCK NONINVARIANT: interface-defect status itself forces eventual H1 erasure.
N2 OBSTRUCTION-EXCESS NONINVARIANT: only the part of active stock contributing to above-threshold obstruction is forced noninvariant, after separating any protected persistent component.
N3 FINITE-STATE TURNOVER: finite collar alphabet/UWB/eventual periodicity forces witness turnover.
N4 GENERATOR/TOGGLE TURNOVER: DW/TC/LAR or Phase-A generator structure forces active witness change.
N5 DISSIPATION-BIAS TURNOVER: H1/H2/SB2 ledger dissipation forces stock turnover indirectly.
N6 PERSISTENCE-COMPATIBLE COUNTERMODEL: a quotient-visible active interface witness may remain lawfully invariant/persistent under the declared transfer while current defect channels evolve.
N7 NO DETERMINISTIC TURNOVER SOURCE-FORCED.

## Mandatory tests
1. Book-III persistent-observable/transfer machinery explicitly permits lawful persistence; defect status cannot negate that without theorem.
2. H1 applies to non-invariant mismatch, not invariant quotient-visible content.
3. H2 needs incompatible patterns; a stable compatible lineage may evade it.
4. Finite-state/eventual periodicity allows fixed points and cycles; finiteness alone is not turnover.
5. Deterministic transition does not imply every witness changes.
6. Toggle completeness means operations are available, not that actual history executes each toggle.
7. Ledger dissipation may not be promoted to stock turnover without the cross-channel theorem under test.
8. Above-threshold obstruction must not be assumed to identify a noninvariant stock subset unless source-defined.

## Outcomes
A__UNIFORM_ACTIVE_STOCK_TURNOVER_DERIVED
B__OBSTRUCTION_EXCESS_TURNOVER_DERIVED__PERSISTENT_CORE_SEPARABLE
C__ONLY_CONDITIONAL_TURNOVER_SCHEMA_AVAILABLE__NEW_DYNAMICAL_PREMISE_REQUIRED
D__INVARIANT_ACTIVE_STOCK_ALLOWED__TURNOVER_NOT_SOURCE_FORCED
E__REPAIR_REQUIRED
F__UNDERDETERMINED

## Firewalls
No stochastic hazard interpretation. No claim that availability of a generator means its execution. No use of endpoint regularity. No static stock-successor proportionality. No source mutation.