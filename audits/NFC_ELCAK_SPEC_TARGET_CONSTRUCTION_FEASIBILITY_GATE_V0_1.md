# NFC ELCAK SPEC Target-Construction Feasibility Gate v0.1

STATUS = EXECUTED__OUTCOME_A__VALID_PREEMPIRICAL_SPEC_TARGET_SKELETON_CONSTRUCTIBLE

PREREGISTRATION_COMMIT = `622399cae4b07dac30e20f4a3ad9a84d205def89`
BASE_ACCEPTANCE_COMMIT = `455b9b00173d53012fa13fd18d05bd133f1b95fd`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`PRIMARY_OUTCOME = A__VALID_PREEMPIRICAL_SPEC_TARGET_SKELETON_CONSTRUCTIBLE__READY_FOR_SEPARATE_REALIZATION_GATE`

A valid pre-empirical ELCAK target skeleton can be constructed from frozen SPEC definitions plus explicit protocol declarations, without assuming equal weighting and without pretending a concrete apparatus or ordinary physical measurement is already present.

This is a formal target-design result only.

`PHYSICAL_REALIZATION = NOT_ESTABLISHED`

`EMPIRICAL_TESTBED = NOT_YET_ESTABLISHED`

`ELCAK_EMPIRICAL_SUPPORT = NONE`

## Constructed target skeleton: SES-1

Name:

`SES-1__SPEC_ELCAK_SIBLING_RESPONSE_TARGET_SKELETON`

### 1. Parent class

Choose a branch-visible observable object `X_0` in the certified SPEC observable class and freeze its pre-probe spectroscopic response class `R_0` under a declared preparation/check family.

The empirical realization gate must later bind a concrete physical instance whose pre-trial record certifies membership in `R_0`.

No token-level identity is required; comparability is quotient-class based.

### 2. Fixed probe

Choose one admissible SPEC probe `P_0` and freeze its complete protocol description before any outcome data.

The target skeleton uses the frozen SPEC notion of a probe episode: an ordered application of an admissible probe together with a certified before/after response record in a declared response window.

This does not upgrade the probe episode into ordinary physical measurement.

### 3. Fixed response window and comparison discipline

Choose a bounded discrete response window `W_0` and a frozen spectroscopic-equivalence rule `~_Spec` inherited from the declared SPEC comparison discipline.

Continuum-response density is not required for SES-1 and is intentionally excluded from the first target to avoid an unnecessary continuum bridge.

### 4. Lawful sibling set

Define

`Ch_SPEC(R_0,P_0,W_0)`

as the set of all distinct quotient-visible spectroscopic response classes certified as transition-accessible from parent class `R_0` under the fixed probe `P_0` within `W_0`, under the frozen comparison discipline.

A concrete SES-1 target qualifies only if:

- the set is finite;
- `k = |Ch_SPEC| >= 2`;
- each valid post-probe episode maps to exactly one class in the set;
- all branch-recognized invalid / apparatus-failure / protocol-violation outcomes are specified separately before data collection.

The child classes are defined by response equivalence and transition accessibility, not by ELCAK probabilities or observed frequencies.

### 5. Exhaustivity schema

The valid sibling set is prospectively exhaustive relative to the declared target scope by construction:

- valid response episodes in `(R_0,P_0,W_0)` must map to one of the frozen transition-accessible response classes;
- episodes outside the declared validity conditions are not silently forced into the sibling set and are coded under prospectively declared failure/exclusion categories.

This is scoped exhaustivity, not a claim about every physically conceivable response outside `W_0` or outside SPEC's declared branch regime.

### 6. Reset / conditioning rule

Before each trial, run the frozen preparation/check procedure and accept the trial only if the pre-probe observable state is certified in parent response class `R_0` with the required state record present.

If preparation fails, the episode is not an ELCAK trial and is logged separately.

This rule establishes logical comparability without asserting that a concrete laboratory reset procedure already exists.

### 7. State-sufficiency record

For each accepted trial, record the full prospectively declared branch-visible pre-probe state packet needed by the target protocol, including at minimum:

- parent response class `R_0`;
- fixed probe identity/type `P_0` at the quotient-visible protocol level;
- declared continuation/probe channel;
- response window `W_0`;
- any branch-visible transported invariant or loss-ledger variable the protocol declares future-relevant;
- bounded preparation history if required.

SES-1 does not assume Markov sufficiency for free. A physical realization must either:

1. justify that this packet is sufficient for future sibling probabilities; or
2. explicitly carry a state-sufficiency hypothesis as part of the empirical model.

### 8. ELCAK null

If the bound target has `k` valid sibling classes, ELCAK predicts

`H_ELCAK: p_i = 1/k` for every `i = 1,...,k`.

No fitted probability parameters are permitted under the null.

### 9. Outcome registration

Each accepted post-probe episode is assigned exactly once to its frozen quotient-visible sibling class using the preregistered response-equivalence rule.

No class boundary may be changed after outcome inspection.

Ambiguous episodes must be handled by a prospectively frozen ambiguity/failure rule rather than analyst discretion.

### 10. Falsifier

For a later realized target with preregistered sample size/stopping rule, let `N_i` be the count in sibling class `i` and `N = sum_i N_i`.

Use a preregistered multinomial goodness-of-fit decision rule against the parameter-free uniform null `(1/k,...,1/k)`. An exact multinomial or preregistered likelihood-ratio statistic is admissible; the precise significance / error policy must be frozen in the later empirical protocol.

The target is falsifiable because sufficiently nonuniform registered frequencies can reject the ELCAK null without requiring a fully specified deterministic alternative.

## Construction-gate adjudication

`S1 PARENT_TYPE = PASS`

SPEC supplies a certified observable class and quotient-visible response classes.

`S2 PROBE_TYPE = PASS`

SPEC supplies admissible probes and probe episodes.

`S3 CHILD_SPACE = PASS_AS_FORMAL_SCHEMA`

Spectroscopic response classes plus transition accessibility provide an ELCAK-neutral child-space definition. A concrete target must later demonstrate finite `k >= 2`.

`S4 EXHAUSTIVITY_SCHEMA = PASS_AT_DECLARED_SCOPE`

Scoped exhaustivity is achieved by freezing all valid transition-accessible response classes within `W_0` and separately freezing invalid/failure categories.

`S5 RESET_SCHEMA = PASS_AS_PROTOCOL_LOGIC`

Comparability can be defined by re-certification into the same parent response class. Physical reset feasibility remains for the realization gate.

`S6 STATE_RECORD = PASS_WITH_EXPLICIT_SUFFICIENCY_BURDEN`

A finite declared state packet can be specified. Physical sufficiency is not source-forced and remains a model burden.

`S7 NUMERICAL_NULL = PASS`

For finite `k >= 2`, ELCAK gives `p_i = 1/k`.

`S8 FALSIFIER = PASS`

A parameter-free multinomial null admits a preregistered goodness-of-fit rejection rule.

`S9 NONCIRCULARITY = PASS`

Child definitions are structural/response-based, not frequency- or ELCAK-defined.

`S10 REALIZATION_SEPARATION = PASS`

The construction explicitly stops before apparatus selection, physical binding, trial execution, or empirical interpretation.

## Strong failure checks

### Hidden identity

No token-level continuation identity is used. Parent and child states are quotient-visible response classes.

### Partition manipulation

Blocked by prospective freezing of `W_0`, response equivalence, transition accessibility rule, valid/failure categories, and stopping rule.

### Apparatus smuggling

No specific apparatus is assumed. This is intentionally left open.

### Equal-weight smuggling

The sibling partition is complete before probabilities are assigned. Equal weighting appears only in the ELCAK null after the partition is frozen.

### Branch-dynamics smuggling

SPEC transition certification establishes lawful response change, not actualization probability. The audit does not promote transition accessibility to weighting authority.

## What remains before T3

The formal target skeleton is not yet a T3 empirical testbed. A separately preregistered realization operation must bind:

1. a concrete physical system corresponding to `X_0/R_0`;
2. a physically implementable fixed probe `P_0`;
3. a concrete bounded response window and detector/readout mapping to the frozen response classes;
4. evidence that the valid sibling set is finite, nontrivial, and operationally exhaustive;
5. a realizable reset/conditioning procedure;
6. trial independence/exchangeability assumptions or an explicit dependence model;
7. apparatus-failure handling;
8. a practical sample-size/stopping rule and error policy.

Only after those are bound can the program ask whether T3 is achieved.

## Scientific interpretation

SES-1 shows that ELCAK is not blocked at the level of abstract experimental logic. The remaining barrier is physical realization and protocol binding.

This is informative because it separates two questions that were previously entangled:

- `Can ELCAK be formulated as a falsifiable SPEC-style target?` → YES.
- `Does NFC currently contain or identify a real physical experiment testing it?` → NO.

## Routing

`NEXT_OPERATION = NFC_ELCAK_SPEC_PHYSICAL_TARGET_REALIZATION_FEASIBILITY_GATE_V0_1`

That operation should search only for a concrete physical target architecture satisfying SES-1. It must not collect data, and it must be allowed to conclude `NO_PHYSICAL_SPEC_TARGET_IDENTIFIED`.

A target may be proposed from existing external physical systems only if the mapping from physical preparation/probe/readout to frozen SPEC response classes is explicit and does not assume ELCAK.

NFC_CANON_MUTATION = NO
FCP_READJUDICATION = NO
PGH_READJUDICATION = NO
ELCAK_ADOPTION = NO
DATA_COLLECTION = NO
EMPIRICAL_SUPPORT = NONE
