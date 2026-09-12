# NFC NS Cumulative Innovation Budget Feasibility Gate v0.1

PREREGISTRATION: 0e01ec15a97d5fb8e823ac75c97fd00da0240320

## Outcome
B__STEPWISE_RESIDUAL_DERIVED__GLOBAL_OR_REFINEMENT_INVARIANT_BUDGET_REQUIRES_BOUNDED_VARIATION_PREMISE

## Stepwise construction
Let alpha_j be the localized exogenous source object in Source(U_j), and let S_j := S(f_j) be the accepted lawful linear source transport into Source(U_{j+1}). Because both S_j(alpha_j) and alpha_{j+1} live in the same typed target source space, define the source residual

eta_j := alpha_{j+1} - S_j(alpha_j).

This residual is prospective source data once the source representation, context chain, and source transport are fixed. It does not use the solution state u or any regularity outcome.

Define the residual innovation profile

J_j^res := Q_{eta_j}^{Pi,N,a}

using the same prospectively frozen source decomposition/local seminorms/normalization discipline as the accepted source burden.

The source-level identity

alpha_{j+1} = S_j(alpha_j) + eta_j

is exact by construction. Under the accepted positive-kernel transfer envelope and local seminorm subadditivity, the burden therefore satisfies the profile inequality

B_{j+1} \preceq Gamma_j[B_j] \oplus J_j^res

on qualifying common refinements, conditional on the already isolated transfer/decomposition compatibility premise.

## Adversarial tests

- Stationary persistence: PASS. If alpha_{j+1}=S_j(alpha_j), then eta_j=0 and J_j^res=0.
- New source injection: PASS. Newly appearing source content contributes to eta_j.
- Source removal/sign change: PASS at source-object level; the residual may be signed while its innovation burden is nonnegative through the local seminorm profile.
- Component provenance: PASS only when residuals are formed componentwise or lawful merging/splitting is explicitly recorded; summing components before residual formation can hide cancellation and is prohibited.
- State independence: PASS.
- OpenAI outcome fitting: PASS; no residual threshold or budget is selected from its known blowup.

## Candidate cumulative objects

### C1 finite declared-chain cumulative profile
AVAILABLE.

For a finite declared segment m..n, move all J_j^res to a qualifying common refinement R and define

J_[m,n]^R := Ref_R(J_m^res) \oplus ... \oplus Ref_R(J_n^res).

This is a finite profile-valued source-exposure/innovation budget. It introduces no scalar weights.

### C2 refinement-stable total-variation profile
PROMISING BUT REQUIRES ONE NEW PREMISE.

If the context chain is refined by inserting intermediate lawful contexts, the sum of residual burdens can change. A chain-independent/global object therefore requires a bounded-variation/refinement-control condition, for example that the net of cumulative residual profiles over qualifying refinements is directed and bounded in the common-refinement cone, with a declared supremum/limit.

Call this premise P_NS-SOURCE-BV.

### C3 scalar cumulative norm
NOT JUSTIFIED. Scalarization remains downstream.

### C4 accumulated source work/energy
REJECTED as source-only innovation budget because it depends on the evolving solution state.

### C5 arbitrary declared J_j unrelated to residual
UNNECESSARY as the minimal route when the source schedule and lawful source transport are available. It may remain a model extension if source evolution is only partially specified.

### C6 no useful innovation object
REJECTED.

## What is derived and what is not

Derived conditionally from accepted/provisional source typing:
- the exact stepwise residual eta_j;
- the profile-valued residual burden J_j^res;
- finite declared-chain cumulative innovation profiles;
- the mixed one-step source-control inequality B_{j+1} <= Gamma_j[B_j] + J_j^res in the common-refinement order, conditional on the separately accepted scale-envelope compatibility premise.

Not derived:
- a uniform/global bound on cumulative innovation;
- refinement-independent total variation over arbitrary chains;
- late-tail summability;
- a scalar innovation threshold;
- a forced continuation theorem.

## Minimal new premise for global use

P_NS-SOURCE-BV:
The prospectively declared exogenous source schedule has bounded variation in the accepted profile cone relative to the lawful context chain/refinement system, so cumulative residual profiles remain bounded and admit a refinement-compatible envelope/limit.

This premise is about exogenous source regularity across the source-context representation. It does not assert solution regularity and is not implied merely by smooth compact support without a proved physical-time/context correspondence.

## Routing
NEXT_OPERATION = NFC_NS_MIXED_SOURCE_CONTROL_TO_COMMON_STATE_GATE_V0_1

No mutation of frozen NFC, FCP, or PGH.