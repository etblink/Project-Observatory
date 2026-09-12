# NFC NS Scale Envelope Gain Feasibility Gate v0.1

PREREGISTRATION: 189b4db0f000f2b02c52c8619e75f821f2e82c50

## Outcome
B__POSITIVE_KERNEL_ENVELOPE_SCHEMA_AVAILABLE__TRANSFER_DECOMPOSITION_COMPATIBILITY_PREMISE_MISSING

## Construction
Work on any qualifying common refinement R of the accepted source-profile decompositions. Let source transfer across one typed context step be the accepted linear map S_j := S(f_j).

Suppose, prospectively and independently of solution outcome, that the finite/refining source representation is compatible with the declared profile decomposition in the following sense:

1. each refined profile coordinate b has a represented source component x_b with local seminorm/norm N_b;
2. the transferred refined coordinate a can be expressed through finite or summably controlled block maps M_j(a,b):

   x'_a = sum_b M_j(a,b) x_b;

3. each block has a finite operator-seminorm bound c_j(a,b) satisfying

   N'_a(M_j(a,b)x_b) <= c_j(a,b) N_b(x_b);

4. the block representation and bounds commute with qualifying refinement/coarse-graining maps.

For normalized profile burdens bhat_b = a_b N_b(x_b), subadditivity gives

bhat'_a <= sum_b K_j(a,b) bhat_b,

where

K_j(a,b) := (a'_a/a_b) c_j(a,b) >= 0.

Thus the positive profile operator

Gamma_j[B]_a := sum_b K_j(a,b) B_b

is a noncircular scale-envelope candidate. Cross-scale redistribution is represented by off-diagonal kernel entries rather than hidden in one scalar coefficient.

## Candidate adjudication

E1 scalar multiplier — REJECTED AS FIRST TARGET. It is a special coarse envelope and loses the scale-local structure deliberately retained upstream.

E2 diagonal multiplier — INSUFFICIENT GENERALLY. It cannot represent lawful redistribution between source scales/components.

E3 positive cross-scale kernel — VIABLE.

E4 arbitrary monotone nonlinear map — TOO UNDERCONSTRAINED at present.

E5 induced finite-stage transfer envelope — SELECTED REALIZATION OF E3. When transfer/decomposition compatibility and local operator bounds are declared, the kernel coefficients are derived from the source transfer representation and local norms rather than fitted to an outcome.

E6 no useful envelope — REJECTED.

## Adversarial tests

- Cross-scale mixing: PASS via off-diagonal K_j(a,b).
- Zero: PASS.
- Addition/nonnegative scaling: PASS at envelope level.
- Stationary identity source: identity block map gives the identity kernel under an unchanged decomposition/normalization.
- Attenuation/amplification: both permitted; no sign of gain is source-forced.
- Refinement invariance: CONDITIONAL on the explicit compatibility/naturality premise above.
- Dictionary choice: the kernel is representation-relative at a finite stage, but admissible scientific content is its equivalence class under qualifying common refinement. No basis is declared physically fundamental.
- Theta_j firewall: PASS; K_j is source-transfer-derived and is not identified with endogenous Theta_j.
- Outcome fitting: PASS if S_j, decomposition, N, normalization, and block bounds are frozen before regularity outcome inspection.
- OpenAI control: remains in scope; no coefficient is selected from its known blowup.

## What is new versus already accepted
Accepted source linearity/functoriality alone does not guarantee that a chosen multiscale decomposition admits a refinement-natural finite block representation with controlled local operator seminorms. Therefore Outcome A is too strong.

The minimal additional premise is:

P_NS-SOURCE-TRANSFER-DECOMP:
The declared source transfer S_j admits a refinement-natural block representation relative to the prospectively fixed source decomposition, with finite local operator-seminorm bounds.

This is a source-representation compatibility/boundedness premise. It does not assert contraction, regularity, safety, or any relation to endogenous Theta_j.

## Scientific consequence
Under P_NS-SOURCE-TRANSFER-DECOMP, the transported-gain side of the affine source law can be bounded by a prospectively defined positive profile kernel:

G_j[B] \preceq Gamma_j[B].

The remaining independent source-control burden is innovation:

I_j \preceq J_j.

## Routing
NEXT_OPERATION = NFC_NS_CUMULATIVE_INNOVATION_BUDGET_FEASIBILITY_GATE_V0_1
FOLLOW_ON = NFC_NS_MIXED_SOURCE_CONTROL_TO_COMMON_STATE_GATE_V0_1

No mutation of frozen NFC, FCP, or PGH.