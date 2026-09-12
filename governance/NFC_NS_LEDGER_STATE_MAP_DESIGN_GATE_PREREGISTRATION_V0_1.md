# NFC NS Ledger-State Map Design Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 85897276413c7d6eb29132f24148800573b180ef
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
What is the weakest typed map from the Book-II visible obstruction ledger D_n=E_n+B_n to the NS normalized successor-defect state mathfrakD_k that can lawfully transfer loss/renewal recurrences and H1/H2 bounds across the adaptive window architecture?

## Candidate maps
L1 direct identity D_n=mathfrakD_n.
L2 point-sampling map selecting one representative n(k) per window.
L3 componentwise active transport-weighted window aggregation:

A_k(D):= [sum_{j in W_k} omega_j D_j]/[sum_{j in W_k} omega_j],

with corresponding A_k(E), A_k(B), A_k(Phi), A_k(Psi), and mathfrakD_k identified/compared to A_k(D) only through an explicit normalization/realization law.

L4 unweighted window average.
L5 supremum/max over the window.
L6 cumulative sum over the window.
L7 no coherent map.

## Required theorem burden for an aggregation route
A valid map must specify:
1. temporal correspondence between ledger step j and NS window k;
2. active window W_k and transport weights omega_j already declared by the NS architecture;
3. normalization and component typing;
4. nonnegativity;
5. preservation/transfer of H1/H2 loss lower bounds;
6. transfer of the D-side loss/renewal recurrence to a mathfrakD-side recurrence;
7. compatibility across successor adaptive windows, i.e. an averaging/evolution intertwining or controlled boundary-remainder theorem;
8. no identification with the Stage-2a operator D_n;
9. no assumption that gross transport Theta equals the net contraction ratio;
10. positive contraction-factor domain treated downstream, not built into the map.

## Outcomes
A__COMPONENTWISE_ACTIVE_WINDOW_AGGREGATION_IS_CANONICALLY_SUFFICIENT
B__ACTIVE_WINDOW_AGGREGATION_IS_MINIMAL_SCHEMA__INTERTWINING_THEOREM_MISSING
C__TWO_NONDOMINATED_MAPS_SURVIVE
D__NO_TYPED_MAP_SURVIVES
E__REPAIR_REQUIRED
F__UNDERDETERMINED

## Stop rule
Do not assert a mathfrakD recurrence merely by averaging a D recurrence over changing/adaptive windows. Any commutation/remainder burden must be explicit.