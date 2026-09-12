# NFC NS Direct Obstruction Recurrence Feasibility Gate v0.1

PREREGISTRATION: b5b8c2fa7092bf78f95b10a3b45ef0439d420b68
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Outcome
D__DIRECT_RECURRENCE_NONFORCING_ESTABLISHED__STOCK_LOSS_CURRENT_DEFECT_COUPLING_REQUIRED

## Typed state
Use the accepted three-component common state

S_k := A_k(I),
J_k := A_k(E+B),
Z_k := mathfrakD_k,
O_k := O_NS(W_k) = S_k - J_k.

The targeted Book-III/SCT crosswalk gives J_k=A_k(mathcalD). Conditional on the separately accepted successor-defect realization premise, Z_k=gamma J_k for one fixed gamma>0 shared by the full ledger tuple. None of this identifies S_k with J_k or Z_k.

## Directional obstruction
For a one-sided upper recurrence on O,

O_{k+1}=S_{k+1}-J_{k+1},

a valid derivation needs either exact coupled evolution for the difference, an upper bound on S_{k+1} together with a lower bound on J_{k+1}, or an equivalent direct one-sided estimate.

The accepted interface-stock program supplies an exact recurrence for constructed active witness mass M_n and, conditional on a_I M_n <= I_n <= b_I M_n, typed upper/lower envelopes for I_n. The visible-ledger program supplies an upper loss/renewal recurrence for mathcalD and, after window aggregation, a shifted-window recurrence plus explicit window discrepancy. These are not the complementary inequality directions required to subtract the states.

In particular, an upper bound on J_{k+1} makes -J_{k+1} larger when substituted and therefore cannot give the desired upper bound on O_{k+1}.

## Decisive admissible countermodel
Consider a step/window regime allowed by the presently separated architecture:

- inherited interface stock persists under identity/boundary-preserving transfer;
- no new boundary generation occurs;
- no certified stock loss occurs;
- the current visible/successor defect decays strongly or vanishes.

At the scalar state level take, for example,

S_k=1,
J_k=0.9,
O_k=0.1,

and at the next state

S_{k+1}=1,
J_{k+1}=0,
O_{k+1}=1.

This does not violate the exact witness-stock recurrence: identity transfer with no generation/loss gives persistent stock. It also does not violate a one-sided visible-ledger decay law. Yet O grows by a factor of ten. Therefore no universal contracting recurrence O_{k+1} <= lambda O_k with lambda<1 follows from the independent stock and current-defect laws.

The numerical values are illustrative only; the countermodel is structural. Any small positive gap S_k-J_k can be exposed by a sufficiently large decrease in J while S persists.

## Candidate adjudication
R1 SUBTRACT_INDEPENDENT_UPPER_BOUNDS — REJECTED by inequality direction.

R2 EXACT_STOCK_PLUS_EXACT_LEDGER — INSUFFICIENT. The stock construction is exact for M, but I is only connected to M through a conditional two-sided active-load bridge; the visible ledger has a one-sided recurrence, and adaptive-window aggregation introduces an explicit discrepancy. More importantly, independent exact/one-sided component laws do not fix the signed difference drift.

R3 STOCK_UPPER_PLUS_LEDGER_LOWER — NOT AVAILABLE. No nontrivial lower recurrence for J_{k+1} on the needed same window state is presently source-forced.

R4 DIRECT_COUPLED_EVENT_ACCOUNTING — MOST INFORMATIVE NEXT TARGET. A lawful event-level theorem relating interface-stock persistence/loss to the current defect/loss channels could control the signed drift Delta S - Delta J. No such cross-channel theorem is currently present.

R5 POSITIVE_RESERVE_STATE — USEFUL REFORMULATION BUT NOT CLOSURE. A reserve/gap state makes the dangerous signed drift explicit; it does not determine that drift without the same missing coupling.

R6 NONNEGATIVITY_ONLY — INSUFFICIENT. J_{k+1}>=0 yields O_{k+1}<=S_{k+1}, not contraction relative to O_k.

R7 STATIC_STOCK_SUCCESSOR_COMPARISON — REJECTED as the primitive route by the accepted stock-successor gate; interface stock carries memory.

R8 NO_CLOSED_DIRECT_RECURRENCE — ACCEPTED.

## Exact missing theorem class
The missing object is not another normalization theorem. It is a stock/current-defect coupling law, provisionally named

T_NS-STOCK-DEFECT-EVENT-COUPLE.

It must be formulated on quotient-visible event/provenance data and control the signed difference

(S_{k+1}-S_k) - (J_{k+1}-J_k)

or an equivalent eventwise decomposition. It must distinguish:
- persistence of inherited interface witnesses;
- genuine stock loss/resolution;
- migration/reclassification;
- new active-stock generation;
- current internal/boundary defect increments;
- quotient/mixing loss of the visible ledger;
- adaptive-window discrepancy.

A valid theorem may imply a direct obstruction recurrence, but it may not assume one as its premise.

## Adversarial cases
1. Identity transfer/no generation/no loss — blocks contraction if J can fall independently. PASS as countermodel.
2. Pure stock loss/no generation — compatible with a future coupling theorem; does not by itself close general case.
3. Duplicate generation — must not increase active stock after deduplication; already handled by witness recurrence.
4. Genuine new active stock — can increase S and must be represented explicitly.
5. Visible-ledger decay with persistent inherited stock — decisive nonforcing case.
6. J_{k+1} below its upper estimate — confirms sign failure.
7. Window discrepancy of either sign — must remain explicit or be separately absorbed.
8. Finite extinction — does not rescue the general geometric case; may be treated separately after coupling is supplied.

## Scientific interpretation
The failed direct route is informative. The common-state frontier is not merely an indexing or normalization problem. The obstruction combines a memory-bearing stock with current defect increments. A theorem must state how resolution of current defect affects the inherited interface stock before decay of one can force decay of their difference.

## Status
DIRECT_OBSTRUCTION_RECURRENCE_FROM_EXISTING_COMPONENT_LAWS = NO
INEQUALITY_DIRECTION_GAP = ESTABLISHED
STATIC_STOCK_SUCCESSOR_PROPORTIONALITY = NOT_SOURCE_FORCED
EVENT_LEVEL_STOCK_DEFECT_COUPLING = MISSING
COMMON_STATE_OBLIGATION = OPEN

## Next operation
NFC_NS_STOCK_DEFECT_EVENT_COUPLING_DESIGN_GATE_V0_1

No mutation of frozen NFC, FCP or PGH.