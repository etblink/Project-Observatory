# NFC NS Ledger-State Map Conditional Completion Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 72036119f83e47f9e42fad2417bf386ba7ce7642
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Purpose
Classify exactly which requirements of frozen common-state burden (f), the ledger-state map, become conditionally complete under the newly isolated explicit research premises, without promoting any other part of the common-state obligation.

## Conditional premise set
P1 P_NS-SUCCESSOR-DEFECT-REALIZATION: one fixed gamma>0 realizes the whole active aggregated ledger tuple as the NS successor-defect/loss/renewal tuple.
P2 P_NS-WINDOW-REMAINDER-ABSORB: (R_k^win)_+ <= xi(Phi_k-Psi_k), with fixed xi in [0,1).
P3 the separately explicit total-renewal route: Psi_k <= eta_tilde Phi_k with eta_tilde<1.
P4 H1/H2 on the same realized state: Phi_k >= (c1+c2) mathfrakD_k with c1,c2>0.

## Frozen burden-(f) checklist
The frozen common-state obligation requires an explicit typed map from the Book-II visible ledger to mathfrakD specifying:
1. temporal index;
2. window/averaging convention;
3. normalization;
4. H1/H2 lower-bound transfer;
5. loss/renewal recurrence transfer;
6. same-state obstruction comparison of burden (d);
7. preservation of nonnegativity;
8. positive contraction-factor domain, or separate finite-extinction treatment.

## Questions
- Which checklist items are supplied by accepted construction plus P1/P2/P3/P4?
- Is item 6 actually part of the map's internal construction, or merely a cross-reference to still-open burden (d)?
- Does the resulting factor
  kappa_win = 1-(1-xi)(1-eta_tilde)(c1+c2)
  provide the required geometric/extinction split without hidden assumptions?
- What remains scientifically unproved even if the schema is logically complete?

## Outcomes
A BURDEN_F_CONDITIONALLY_COMPLETE__OTHER_COMMON_STATE_BURDENS_REMAIN_OPEN
B BURDEN_F_PARTIALLY_COMPLETE__ONE_MAP_INTERNAL_REQUIREMENT_REMAINS
C PREMISE_SET_INSUFFICIENT_FOR_BURDEN_F
D REPAIR_REQUIRED
E UNDERDETERMINED

## Firewall
This gate may not declare the common-state obligation discharged. P1 and P2 are new explicit research premises, not frozen NFC theorems. Total-renewal control and same-state obstruction comparison remain separate unless independently established. The active-load bridge for interface-burden evolution is also separate.