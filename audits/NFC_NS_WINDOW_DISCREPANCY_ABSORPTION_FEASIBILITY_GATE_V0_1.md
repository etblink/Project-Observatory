# NFC NS Window Discrepancy Absorption Feasibility Gate v0.1

PREREGISTRATION: 24f1e016d89ed39d591506678c8a950ebf862a34
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Outcome
C__NO_ABSORPTION_DERIVED__RELATIVE_POSITIVE_REMAINDER_PREMISE_IS_MINIMAL

## Finding
Under the accepted common-fixed-normalization realization premise, the transferred successor-defect recurrence is

mathfrakD_{k+1}
<= mathfrakD_k - Phi_k + Psi_k + R_k^win.

Existing structure does not derive that R_k^win vanishes, is summable, or is small relative to the strict loss margin.

The minimal additional per-step absorption premise is one-sided:

P_NS-WINDOW-REMAINDER-ABSORB:
There exists one prospectively fixed xi in [0,1), independent of late-tail step, such that

(R_k^win)_+ <= xi (Phi_k-Psi_k)

throughout the declared late-tail regime.

Only the positive part is constrained because negative window discrepancy strengthens, rather than weakens, the loss recurrence.

## Conditional consequence
Then

mathfrakD_{k+1}
<= mathfrakD_k - (1-xi)(Phi_k-Psi_k).

If separately

Psi_k <= eta_tilde Phi_k,
Phi_k >= (c1+c2) mathfrakD_k,

we obtain

mathfrakD_{k+1}
<= [1-(1-xi)(1-eta_tilde)(c1+c2)] mathfrakD_k.

Define

kappa_forcedwin := 1-(1-xi)(1-eta_tilde)(c1+c2).

The geometric case requires kappa_forcedwin in (0,1). If the effective loss factor is >=1, the finite-extinction alternative is treated separately by nonnegativity. Xi is fixed prospectively and may not be tuned to force either regime.

## Candidate adjudication
A1 exact shift — NOT DERIVED. The adaptive active window at k+1 need not equal the one-step pushforward of the current normalized measure.

A2 current structure derives loss-controlled discrepancy — NOT DERIVED. No theorem relates the total-variation/window-value mismatch to Phi-Psi.

A3 summable positive discrepancy — NOT DERIVED. The envelope audit yields only nonincrease of M_k, and the weight audits do not yield summable TV.

A4 periodic/block telescoping — NOT DERIVED. Eventual periodicity is geometric; numerical normalized weights need not be periodic, so exact cancellation over a geometric cycle does not follow.

A5 envelope decay — NOT DERIVED. Only nonincrease is established until the ledger-state realization transfers proportional loss to one common state.

A6 explicit relative absorption premise — ACCEPTED / MINIMAL PER-STEP CLOSURE. It constrains exactly the harmful remainder relative to already-certified net loss and introduces no absolute ceiling.

A7 shifted-state redefinition — REJECTED as primary repair. It would change the frozen branch's actual-successor-window semantics instead of proving compatibility with them.

A8 no absorption available — TOO PESSIMISTIC as a research route; the explicit relative premise is coherent and sharply typed.

## Scientific interpretation
The window discrepancy is not a hidden algebraic error. It is a genuine compatibility condition between the adaptive-window update and the ledger dynamics. The audit has reduced that compatibility requirement to one dimensionless relative-remainder premise.

This premise is new scientific/mathematical content, not frozen NFC truth.

## Next operation
NFC_NS_LEDGER_STATE_MAP_CONDITIONAL_COMPLETION_GATE_V0_1

That gate should determine exactly which portions of common-state burden (f) become conditionally complete under:
- P_NS-SUCCESSOR-DEFECT-REALIZATION;
- P_NS-WINDOW-REMAINDER-ABSORB;
- the already explicit total-renewal/H1/H2 hypotheses;
while keeping the same-state obstruction comparison and any unresolved renewal premise separate.

No mutation of frozen NFC, FCP or PGH.