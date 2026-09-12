# NFC NS Normalized Window Weight Floor Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 6515c200e4b4d7d51e16ac4787ba700106fe74ab
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Question
Do the frozen active transport-weight definition, UWB finite-state/eventual-periodic window geometry, and existing positive/noncollapse conditions imply a uniform positive lower bound p_*>0 for every nonzero normalized active-window weight on the late tail?

If yes, then for nonnegative late-tail monotone ledger D and normalized window measure mu_k,

max_{supp mu_k} D <= A_{mu_k}(D)/p_*

and hence local oscillation is bounded relatively by the same window average, avoiding an unsupported absolute ceiling.

## Candidate routes
W1 finite window cardinality alone.
W2 finite-state/eventual-periodic window geometry plus transport weights determined by state.
W3 a positive lower bound Theta_j >= theta_min >0 on the raw Book-III transport factors.
W4 positive contraction-factor/noncollapse conditions already present in the NS common-state template.
W5 restrict to the actual positive support of normalized weights and derive a support-mass floor from finitely many recurring normalized measures.
W6 no weight floor; use a periodic/block discrepancy route instead.

## Mandatory tests
1. Theta_j may lie in [0,1]; zero or arbitrarily small factors must not be silently excluded.
2. A bound on window cardinality does not imply a mass floor for arbitrary probability weights.
3. Eventual periodicity of geometry does not imply periodicity of numerical weights unless the weight values are state-determined.
4. The positive contraction-factor domain for the later net factor q must not be conflated with positivity of every raw Theta_j.
5. No cutoff may be chosen to make the discrepancy small.
6. Any conditional route must preserve UWB and renewal/common-state conditionality explicitly.

## Outcomes
A UNIFORM_POSITIVE_NORMALIZED_WEIGHT_FLOOR_DERIVED
B CONDITIONAL_WEIGHT_FLOOR_SCHEMA_EXISTS__ONE_POSITIVITY_OR_STATE_DETERMINATION_BRIDGE_MISSING
C NO_WEIGHT_FLOOR_FROM_FROZEN_ARCHITECTURE
D PERIODIC_BLOCK_ROUTE_DOMINATES
E REPAIR_REQUIRED
F UNDERDETERMINED

No source-project mutation.