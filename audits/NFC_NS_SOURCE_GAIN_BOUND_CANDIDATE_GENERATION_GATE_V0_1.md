# NFC NS Source Gain Bound Candidate Generation Gate v0.1

PREREGISTRATION: a54340b929e4136ad7de820adf169682b9d18d7c

## Outcome
B__SMALL_NONDOMINATED_CANDIDATE_SET

## Context
Accepted upstream structure provides: profile-valued local source burden B_j; common-refinement comparison order; functorial exogenous source transfer distinct from endogenous Theta_j; and the affine bookkeeping schema

B_{j+1} \preceq G_j[B_j] \oplus I_j.

External evidence excludes naive safety criteria based only on smoothness, compact support, zero initial velocity, positive viscosity, or bounded kinetic energy. No candidate below is calibrated to the known OpenAI forced-blowup outcome.

## Candidate adjudication

### K1 — common-refinement scale-envelope/operator gain
QUALIFIES / FIRST GAIN TARGET.

On a qualifying common refinement R, seek an order-compatible positive profile operator Gamma_j^R such that

Ref_R(G_j[B]) \leq Gamma_j^R(Ref_R(B))

coordinatewise, with compatibility under further refinement. Gamma_j may be diagonal, block-local, or more general positive/order-preserving, but its structure must be prospectively declared from source-side representation/localization data. This preserves the multiscale information already judged load-bearing and does not reuse endogenous Theta_j.

Scientific burden: no frozen theorem supplies Gamma_j or its coefficients. The first meaningful question is whether a minimal order-Lipschitz/profile-envelope class can be stated without arbitrary scale weights.

### K2 — temporal-variation envelope
QUALIFIES AS SECONDARY INNOVATION DESCRIPTOR, NOT FIRST GAIN TARGET.

Because the physical force is a spacetime object, prospective temporal variation can in principle bound newly changing source content. However converting target-side temporal variation into context-indexed I_j requires a lawful time/context correspondence or an equivalent source restriction theorem. That bridge is not yet available in the accepted architecture.

### K3 — support-motion/localization envelope
COMPLEMENTARY ONLY.

Support incidence and context restriction are already meaningful. But fixed support can contain arbitrarily changing amplitudes/scale content, while moving support need not imply large source burden. Support motion can constrain where innovation occurs, not generally how large it is.

### K4 — source-only flux envelope
PROMISING BUT ADDITIONAL STRUCTURE REQUIRED.

A source flux across context boundaries could provide a transport-aware gain/innovation constraint. No accepted source-flux object currently exists, and importing the endogenous Book-III flux would violate the channel separation already established. This is a later design route, not the first target.

### K5 — cumulative innovation budget
QUALIFIES / FIRST INNOVATION TARGET.

Given independently typed innovation profiles I_j, a prospective interval/window envelope

I_j \preceq J_j,

and a common-refinement cumulative object such as

J_[m,n] := J_m \oplus ... \oplus J_n

is structurally admissible. It preserves profile information if addition occurs only after common-refinement alignment. A finite/summable budget could enter a forced continuation theorem without asserting source contraction.

Scientific burden: the innovation sequence and interval/index measure must be defined prospectively; no finite budget is source-forced.

### K6 — mixed profile law
QUALIFIES AS PREFERRED COMPLETE ARCHITECTURE, BUT IS COMPOSITE.

The smallest presently viable complete source-control architecture is

G_j[B] \preceq Gamma_j[B],
I_j \preceq J_j,

hence

B_{j+1} \preceq Gamma_j[B_j] \oplus J_j.

K6 is not an independent mechanism; it is the composition of K1 and K5. It dominates either alone for general time-varying forcing because persistent transported gain and genuinely new innovation are separately controlled.

### K7 — state-coupled work injection
DOWNSTREAM DIAGNOSTIC ONLY.

<F,u>-type work is dynamically meaningful but depends on the evolving solution state. It cannot serve as the primary source-only Gamma/J premise without circularity.

### K8 — reuse endogenous Theta_j
REJECTED.

No theorem identifies exogenous source gain with endogenous NFC transport contraction.

### K9 — scalar source norm/smallness
NOT FIRST-LINE.

A one-number bound discards the scale distribution intentionally retained upstream. It may become lawful only after a theorem proves a scalarization adequate for continuation. The OpenAI control additionally blocks naive interpretations of compact support/smoothness/bounded energy as sufficient scalar safety.

### K10 — no useful candidate
REJECTED.

K1 and K5 provide noncircular research targets.

## Nondominated set

GAIN_TARGET = K1__COMMON_REFINEMENT_SCALE_ENVELOPE
INNOVATION_TARGET = K5__CUMULATIVE_PROFILE_BUDGET
COMPLETE_ARCHITECTURE = K6__K1_PLUS_K5

K1 has the lowest additional structural burden among gain candidates because it acts directly on the accepted profile cone/order. K5 has the lowest additional burden among innovation candidates because it does not need a new source-flux ontology or state response. Neither is evidence-backed as true; both are suitable for separate feasibility/falsification gates.

## OpenAI negative control
The OpenAI/FCP construction remains in the declared forcing class. This gate chooses no coefficient, threshold, norm, or aggregation weight from its known outcome. It functions only to reject candidate interpretations that would infer safety from smoothness, compact support, zero initial velocity, positive viscosity, or bounded kinetic energy.

## Routing
NEXT_1 = NFC_NS_SCALE_ENVELOPE_GAIN_FEASIBILITY_GATE_V0_1
NEXT_2 = NFC_NS_CUMULATIVE_INNOVATION_BUDGET_FEASIBILITY_GATE_V0_1
THEN = NFC_NS_MIXED_SOURCE_CONTROL_TO_COMMON_STATE_GATE_V0_1

No mutation of frozen NFC, FCP, or PGH.