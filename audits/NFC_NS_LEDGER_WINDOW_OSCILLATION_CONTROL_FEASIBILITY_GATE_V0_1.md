# NFC NS Ledger Window Oscillation Control Feasibility Gate v0.1

PREREGISTRATION: a345968ace58772030c61935cee13695e7f71388
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Outcome
C__FINITE_STATE_WINDOW_CLASSIFICATION_DOES_NOT_BOUND_LEDGER_VALUES

## Finding
The frozen UWB/finite-state result classifies canonical collar-labelled NS window configurations. Under |partial W_k| <= K_* the configuration-state space is finite, and together with deterministic window transition this yields eventual periodicity of window geometry. It does not state that the scalar Book-II visible obstruction ledger

D_n := E_n + B_n

is determined by the window-configuration label, nor that temporally repeated/isometric windows carry equal ledger values.

Therefore finite state of geometry cannot by itself imply a finite range or a uniform oscillation bound for D_n.

## Candidate adjudication
L1 finite-state observable ceiling — REJECTED. The missing dependence theorem D_n = F(window-state) is absent.

L2 finite-state window geometry only — ACCEPTED as the correct reading. UWB bounds the number of collar-labelled configurations, not ledger magnitude.

L3 Book-I defect capacity — INSUFFICIENT for the full visible ledger. Primitive one-step defects are finite for each finite quotient class, but no frozen theorem gives a uniform late-tail bound on the total internal-plus-boundary ledger solely from the finite window-state label.

L4 Book-II boundary capacity — PARTIAL ONLY. Boundary capacity controls local outcome multiplicity/collar geometry. It may constrain boundary-channel combinatorics, but does not provide an absolute ceiling for the full D_n because the internal defect channel remains distinct and stage-dependent.

L5 UCTI/SCT coercivity bound — RELATIVE ONLY. Frozen SCT statements provide comparisons such as D_n <= C_n or eventual D_n <= (1-epsilon) C_n under their stated hypotheses. They do not supply an absolute uniform ceiling on C_n or D_n.

L6 new absolute ledger regularity premise — NOT YET JUSTIFIED. Failure of the finite-state ceiling does not force an absolute-bound axiom; a relative oscillation route remains available.

## Adversarial countermodel shape
Hold the same admissible collar-labelled window configuration fixed while allowing the source-side/interior defect magnitude carried at the corresponding transfer stage to vary. Nothing in the frozen finite-state/isometry theorem identifies these scalar ledger magnitudes with the geometric state label. Hence identical finite-state geometry with distinct D values is not excluded by that theorem.

## Important surviving route
Under the separately conditional late-tail ledger recurrence

D_{n+1} <= D_n - (1-eta_tilde) Phi_n,

D_n is nonincreasing. On any finite successor-window support this gives a range bound by the largest D value on that support. To turn that into a representation-invariant relative oscillation estimate in terms of A_k(D), one needs control of the normalized active-window weights (or an equivalent same-state positive comparison). This route avoids any unsupported absolute obstruction ceiling.

## Next operation
NFC_NS_NORMALIZED_WINDOW_WEIGHT_FLOOR_FEASIBILITY_GATE_V0_1

Question: do UWB, finite-state/eventual-periodic window geometry, the active cumulative transport weights, and any existing noncollapse/positive-domain conditions imply a uniform positive lower bound on every nonzero normalized weight appearing in a late active window? If yes, monotone D gives osc(D) <= const * A(D); if no, identify the minimal missing premise or alternative periodic-block route.

## Status
FINITE_STATE_GEOMETRY = YES_CONDITIONAL_ON_UWB
LEDGER_AS_FUNCTION_OF_WINDOW_STATE = NO
ABSOLUTE_LEDGER_CEILING = NO
RELATIVE_OSCILLATION_ROUTE = OPEN
WITHDRAWN_CEILING_REINTRODUCED = NO

No mutation of frozen NFC, FCP or PGH.