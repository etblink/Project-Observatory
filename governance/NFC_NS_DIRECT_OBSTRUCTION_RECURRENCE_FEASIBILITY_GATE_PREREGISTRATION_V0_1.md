# NFC NS Direct Obstruction Recurrence Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: d1fec700e07e3bc76423054c5c446905533a6d94
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
Can the exact/conditional interface-stock evolution and the active-window visible-ledger/successor-defect evolution be combined to derive a closed upper contracting recurrence for the NS obstruction itself,

O_k := O_NS(W_k) = S_k - J_k,

without a static same-window proportionality S_k ~ Z_k between interface stock and successor defect?

Here

S_k := A_k(I),
J_k := A_k(E+B),
Z_k := mathfrakD_k,

with J_k = Z_k/gamma only under the separately accepted conditional successor-defect realization premise.

## Mandatory inequality-direction firewall
An upper estimate for S_{k+1} and an upper estimate for J_{k+1} do not imply an upper estimate for S_{k+1}-J_{k+1}. Any valid direct obstruction recurrence must provide either:
1. exact coupled evolution sufficient for the difference;
2. upper control on S_{k+1} together with lower control on J_{k+1}; or
3. an equivalent one-sided bound directly on O_{k+1}.

No sign reversal may be hidden by notation.

## Candidate routes
R1 SUBTRACT_INDEPENDENT_UPPER_BOUNDS — adversarial control; expected invalid unless an exact identity supplies the missing direction.
R2 EXACT_STOCK_PLUS_EXACT_LEDGER — use exact witness-stock evolution and any exact finite-balance evolution if source-supported.
R3 STOCK_UPPER_PLUS_LEDGER_LOWER — seek a canonical lower bound on J_{k+1} from retained/current visible defect.
R4 DIRECT_COUPLED_EVENT_ACCOUNTING — construct O evolution eventwise so that the same witness event has a certified signed effect on stock and current defect.
R5 POSITIVE_RESERVE_STATE — enlarge the state to a reserve/gap variable whose recurrence is naturally one-sided.
R6 NONNEGATIVITY_ONLY — J>=0; test whether this is sufficient for any nontrivial direct contraction.
R7 STATIC_STOCK_SUCCESSOR_COMPARISON — control only; rejected unless independently required.
R8 NO_CLOSED_DIRECT_RECURRENCE — obstruction memory and one-sided ledger inequalities prevent closure without one further stock-loss/current-defect coupling theorem.

## Required adversarial cases
1. Identity/boundary-preserving transfer, no generation, no certified stock loss.
2. Pure stock loss with no new boundary generation.
3. New boundary generation that duplicates an already-active target distinction.
4. New boundary generation that genuinely enlarges active stock.
5. Visible-ledger decay while inherited stock persists.
6. J_{k+1} much smaller than its upper estimate.
7. Window discrepancy with either sign.
8. Finite-extinction branch handled separately from geometric contraction.

## Outcomes
A__DIRECT_OBSTRUCTION_RECURRENCE_DERIVED
B__CONDITIONAL_DIRECT_RECURRENCE_SCHEMA_AVAILABLE__ONE_EXPLICIT_COUPLING_PREMISE_MISSING
C__AUGMENTED_RESERVE_STATE_CLOSES_DIRECTIONAL_GAP__OBSTRUCTION_PROJECTION_REMAINS_CONDITIONAL
D__DIRECT_RECURRENCE_NONFORCING_ESTABLISHED__STOCK_LOSS_CURRENT_DEFECT_COUPLING_REQUIRED
E__STATIC_COMPARISON_ROUTE_REINSTATED_BY_SOURCE_EVIDENCE
F__REPAIR_REQUIRED
G__UNDERDETERMINED

## Firewalls
- No revival of withdrawn alpha: I_n != mathcalB_n as a canonical identity.
- No unsupported absolute obstruction ceiling.
- No conversion of a stock into a step increment.
- No use of OpenAI forced-blowup outcome as calibration.
- Conditional bridges remain conditional and may not be promoted to frozen NFC truth.