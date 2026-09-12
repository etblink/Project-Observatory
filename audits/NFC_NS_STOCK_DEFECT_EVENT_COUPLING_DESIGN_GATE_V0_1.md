# NFC NS Stock–Defect Event Coupling Design Gate v0.1

PREREGISTRATION: 635a18354f504fb2af318e2bcaabbae346e7f44e
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Outcome
B__FINITE_SIGNED_EVENT_FLOW_SCHEMA_DERIVABLE__DISSIPATIVE_STOCK_RESOLUTION_BIAS_MISSING

## Core result
A noncircular event-flow architecture can be built from already accepted quotient-visible objects, but it does not by itself force contraction.

The memory-bearing interface side already has finite lineage accounting. At the constructed active-witness level,

M_{n+1}=M_n-R_n^S+G_n^S,

where

R_n^S:=L_n^q+X_n^mig+C_n^merge >=0,
G_n^S:=G_n^eff >=0.

The current visible-ledger side can be written as an exact accounting identity once its one-sided recurrence is augmented by its nonnegative unaccounted-decrease slack. If

J_{k+1} <= J_k-Phi_k+Psi_k+Delta_k^win,

define

sigma_k := J_k-Phi_k+Psi_k+Delta_k^win-J_{k+1} >=0.

Then

J_{k+1}=J_k-Phi_k+Psi_k+Delta_k^win-sigma_k.

Thus the signed difference drift, at any realization level where the stock variable has an exact event balance, has the form

Delta O
= Delta S-Delta J
= -R^S+G^S+Phi-Psi-Delta^win+sigma,

modulo the already-explicit active-load/window realization factors required to pass from M/I to S=A(I).

This formula is bookkeeping, not a contraction theorem.

## Sign interpretation
The formula exposes the previously hidden directional issue:
- stock resolution/exit R^S decreases O;
- effective new active stock G^S increases O;
- certified visible-ledger loss Phi decreases J and therefore increases O unless accompanied by stock resolution;
- renewal/inflow Psi increases J and therefore decreases O;
- a positive window discrepancy can decrease O after subtraction, while a negative discrepancy can increase O; its sign may not be discarded;
- extra visible-ledger decrease sigma also increases O.

Therefore a theorem that only strengthens visible-ledger dissipation can make the direct O route worse unless it simultaneously controls the stock response.

## Candidate adjudication
C1 SAME-EVENT IDENTITY — REJECTED. Current internal defect has no interface-stock identity, and boundary generation atoms are step events whereas active interface witnesses are persistent stock lineages.

C2 BOUNDARY-ONLY LINEAGE COUPLING — PARTIALLY AVAILABLE. Canonical boundary split atoms can seed/interface with active witness lineages after deduplication, but this does not couple the internal defect channel and does not control disappearance of the total current ledger.

C3 FINITE SIGNED EVENT-FLOW LEDGER — ACCEPTED / MINIMAL ARCHITECTURE. Existing stock-lineage and current-ledger objects can be retained as distinct event classes and combined only at the signed-drift accounting level. No identity between their event sets is assumed.

C4 AGGREGATE EXPOSURE INEQUALITY — REJECTED AS PRIMITIVE. A condition directly asserting Delta O <= -c O + r merely restates the desired recurrence unless derived from separately certified event flows.

C5 UNIFORM STOCK TURNOVER — NOT SOURCE-DERIVED. It would be a substantive new dynamical premise.

C6 AGE-STRUCTURED STOCK — OPTIONAL ENRICHMENT, NOT MINIMAL. Age labels could encode memory but no current theorem gives a finite lifetime or turnover law from age.

C7 STOCHASTIC HAZARD/TURNOVER — REJECTED. No licensed probability structure supplies such semantics.

C8 NO COUPLING ARCHITECTURE — TOO PESSIMISTIC. The signed event-flow schema is well-defined even though its required bias is open.

## Missing scientific theorem
The exact missing content is a dissipative stock-resolution/exposure bias, provisionally

T_NS-STOCK-RESOLUTION-BIAS.

It must be stated on independently certified event flows. A sufficient family of forms would compare total interface-stock resolution/exit against all mechanisms that expose persistent stock by reducing the current ledger, while separately accounting for new active-stock generation. Schematically, one needs a noncircular bound strong enough to control

(R^S - Phi - sigma) - (G^S-Psi-Delta^win)

from below by a positive same-state quantity or an equivalent block form.

The theorem may use quotient loss, mixing, migration, deduplication and boundary generation only through their certified provenance. It may not define R^S by the amount needed for contraction.

## Important source-alignment question
There is a promising but unproved structural correspondence:
- active-stock quotient-image loss L^q versus H1 quotient-loss;
- active-stock merge/dedup loss C^merge versus H2 finite-collar mixing;
- effective stock generation G^eff versus boundary-generation ledger mass.

These similarities are not yet quantitative crosswalks. Migration X^mig is especially distinct: it removes mass from the interface stock without necessarily destroying the underlying transported content.

## Adversarial tests
- Internal defect identity: FAILS as required; channels remain typed separately.
- Duplicate boundary generation: handled by G^eff deduplication.
- Migration: remains distinct from defect destruction.
- Falling J with persistent S: represented explicitly and remains a counterexample absent bias.
- Extra ledger decrease: captured by sigma rather than hidden.
- Window discrepancy: retained with sign.
- Probability smuggling: none.
- Static S~J: not used.
- O contraction assumed: no.

## Scientific status
SIGNED_EVENT_FLOW_SCHEMA = DERIVED
EVENT_SET_IDENTITY = NO
STOCK_RESOLUTION_VS_LEDGER_LOSS_CROSSWALK = OPEN
DISSIPATIVE_STOCK_RESOLUTION_BIAS = OPEN
DIRECT_OBSTRUCTION_CONTRACTION = NOT_ESTABLISHED

## Next operation
NFC_NS_STOCK_RESOLUTION_BIAS_EVIDENCE_GATE_V0_1

No mutation of frozen NFC, FCP or PGH.