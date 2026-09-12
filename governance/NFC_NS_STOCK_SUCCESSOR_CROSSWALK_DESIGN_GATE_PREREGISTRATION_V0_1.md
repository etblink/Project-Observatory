# NFC NS Stock–Successor Crosswalk Design Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 61c4ff679f470d8fe9cd599302d004b7672e6a28
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Question
What is the weakest noncircular architecture capable of relating the active averaged interface stock

S_k := A_k(I)

to the realized successor-defect state

Z_k := mathfrakD_k,

without identifying a level stock with a step increment?

## Available accepted structure
- Conditional active-load bridge: a_I M_n <= I_n <= b_I M_n, where M_n is active quotient-distinguishability mass.
- Exact finite witness-mass evolution for M_n: retained active witness images + genuinely new boundary distinctions - certified losses, with obstructed transfers blocking the theorem rather than counting as loss.
- Canonical boundary-defect atomization for newly generated boundary ledger mass.
- Canonical mass-preserving Book-III E/B <-> SCT visible-ledger crosswalk.
- Conditional successor-defect realization: Z_k=gamma A_k(Dcal), gamma>0 fixed.

## Candidate architectures
S1 DIRECT PROPORTIONALITY:
S_k comparable to Z_k at the same window.

S2 FINITE-MEMORY STOCK:
M_n controlled by a bounded moving sum of recent boundary-generation ledger masses because every active witness resolves within a uniform lifetime L.

S3 GEOMETRIC SURVIVAL KERNEL:
old witness mass decays under lawful transfer at a uniform rate r<1, so M_n is a convolution of past boundary generation with a summable survival kernel.

S4 EXACT STOCK RECURRENCE + CURRENT GENERATION:
use the exact M_n recurrence but leave retained stock as its own state; derive the obstruction through an augmented state rather than compare stock statically to current Z_k.

S5 THRESHOLD-REGIME RESERVE:
only on O_NS(W_k)>=T_NS, derive lower/upper comparison of stock with current successor defect from branch reserve/continuation hypotheses.

S6 DIRECT OBSTRUCTION RECURRENCE:
abandon static S-to-Z comparison and derive a closed recurrence for O=S-J from the joint evolution of S and J. This is the frozen alternative to burden-(d)'s two-sided comparison route.

S7 NEW STATIC STOCK/SUCCESSOR COMPARISON PREMISE.

## Mandatory adversarial tests
1. Persistent witness with zero current generation: active stock may remain nonzero while current boundary increment vanishes.
2. Burst generation followed by persistence: stock can encode history not present in current ledger.
3. Finite collar alphabet does not imply finite witness lifetime.
4. Quotient-image loss need not occur at every step; persistent distinctions may survive indefinitely unless a theorem says otherwise.
5. Any survival rate/lifetime must be source-derived or prospectively declared, not fitted to make S-J positive.
6. Interior defect contributes to Z but not directly to boundary/interface witness stock.
7. Threshold restriction cannot assume the comparison it is meant to prove.
8. Direct-recurrence route must retain stock/increment typing and use the already derived I/M evolution law.

## Outcomes
A DIRECT_STATIC_COMPARISON_DERIVED
B FINITE_MEMORY_ROUTE_DOMINATES
C GEOMETRIC_SURVIVAL_ROUTE_DOMINATES
D AUGMENTED_STOCK_STATE_DOMINATES__STATIC_COMPARISON_NOT_NATURAL
E DIRECT_OBSTRUCTION_RECURRENCE_DOMINATES
F NEW_STATIC_COMPARISON_PREMISE_REQUIRED
G REPAIR_REQUIRED
H UNDERDETERMINED

No source-project mutation.