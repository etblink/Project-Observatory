# NFC ELCAK SPEC Physical-Target Realization Feasibility Gate v0.1

STATUS = EXECUTED__OUTCOME_C__PHYSICAL_TARGET_IDENTIFIED__EXISTING_DATA_CONTRADICT_RAW_ELCAK

PREREGISTRATION_COMMIT = `1d2b57e94d3987df635da6704fc229c8cdca1f81`
BASE_ACCEPTANCE_COMMIT = `7fa8c93e5c3990be967c823e10ac001508398df9`
SES1_EXECUTION_COMMIT = `ec12e7b924f411ba641ebac2775b0051361fb66d`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`PRIMARY_OUTCOME = C__PHYSICAL_TARGET_IDENTIFIED__EXISTING_DATA_CONTRADICT_RAW_ELCAK`

Two independent trapped-ion spectroscopy systems satisfy the validation criteria strongly enough to bear on the raw equal-lawful-child candidate. In both systems, a single excited parent state has three independently defined lower-state decay channels. Raw ELCAK therefore predicts `1/3` for each channel. Published branching fractions are strongly nonuniform.

This is adverse evidence against the post-freeze raw ELCAK model. It is **not** a falsification of frozen NFC.

## Primary target: single trapped 40Ca+

Published system:

R. Gerritsma, G. Kirchmair, F. Zaehringer, J. Benhelm, R. Blatt, C. F. Roos, “Precision measurement of the branching fractions of the 4p 2P3/2 decay of Ca II,” European Physical Journal D 50, 13–19 (2008), DOI `10.1140/epjd/e2008-00196-9`; arXiv `0807.2905`.

### Physical architecture

Parent state:

`4p 2P3/2`

Declared lower-state channels:

1. `4s 2S1/2`
2. `3d 2D5/2`
3. `3d 2D3/2`

The experiment uses a single trapped `40Ca+` ion, high-fidelity state preparation/detection, and repeated optical pumping / population-transfer monitoring to determine branching fractions.

Published branching fractions:

- `0.9347(3)` to `4S1/2`
- `0.0587(2)` to `3D5/2`
- `0.00661(4)` to `3D3/2`

The three channels are defined by distinct atomic final states, independently of the observed frequencies.

### ELCAK prediction

For `k = 3`, raw ELCAK predicts:

`(1/3, 1/3, 1/3)`.

The published fractions are grossly inconsistent with this null relative to their reported uncertainties.

`CA40_ELCAK_RESULT = CONTRADICTED`

## Independent control target: single trapped 138Ba+

Published system:

N. Kurz, M. R. Dietrich, Gang Shu, R. Bowler, J. Salacka, V. Mirgon, B. B. Blinov, “Precision measurement of the branching ratio in the 6P3/2 decay of BaII with a single trapped ion,” Physical Review A 77, 060501(R) (2008), DOI `10.1103/PhysRevA.77.060501`; arXiv `0804.4173`.

### Physical architecture

Parent state:

`6P3/2`

All declared dipole-allowed lower-state channels:

1. `6S1/2`
2. `5D3/2`
3. `5D5/2`

Measurements were performed on single trapped `138Ba+` ions using laser preparation and electron-shelving / population-transfer techniques.

Published normalized branching fractions:

- `0.756 ± 0.046`
- `0.0290 ± 0.0015`
- `0.215 ± 0.0064`

Again, the child channels are defined by distinct spectroscopic final states independently of their measured frequencies.

### ELCAK prediction

Raw ELCAK predicts:

`(1/3, 1/3, 1/3)`.

The measured fractions are strongly nonuniform and incompatible with that prediction.

`BA138_ELCAK_RESULT = CONTRADICTED`

## SES-1 realization-gate adjudication

### R1 FIXED_PARENT

PASS for both systems.

A single excited atomic level is repeatedly prepared / populated.

### R2 INDEPENDENT_CHILD_DEFINITION

PASS.

The children are distinct lower atomic states, identified spectroscopically and by angular-momentum/state labels independently of branching-frequency observations.

### R3 EXHAUSTIVE_CHANNEL_SET

PASS at declared dipole/radiative scope for the cited measurements.

The cited experiments explicitly treat the listed lower states as the relevant/all allowed decay channels for the measured excited-state branching problem.

### R4 REPEATED_TRIAL_ACCESS

PASS.

Both experiments rely on repeated preparation/population-transfer cycles on single trapped ions.

### R5 OUTCOME_IDENTIFIABILITY

PASS.

The experiments successfully estimate channel branching fractions via high-fidelity state-detection / shelving / population-transfer methods.

### R6 ELCAK_MAPPING

PASS for the raw candidate.

The SES-1 mapping is:

- parent response state = excited atomic level;
- fixed preparation/probe protocol = declared laser population/preparation cycle;
- lawful children = distinct transition-accessible lower-state response classes;
- registered result = final spectroscopic state/channel.

With three children, raw ELCAK predicts equal probability `1/3` per class.

### R7 NO_FREQUENCY_DEFINED_PARTITION

PASS.

The final-state partition is not constructed from the measured branching frequencies.

### R8 SPEC_ANALOGY

PASS WITH SCOPE QUALIFICATION.

These are not frozen-NFC-certified physical realizations of the SPEC branch. They are external physical spectroscopy systems whose parent/intervention/transition/readout structure instantiates the SES-1 target architecture closely enough to test the post-freeze ELCAK model.

The spontaneous/radiative decay segment is physical dynamics between preparation and readout rather than a theorem that observation itself causes the transition. Therefore this gate bears directly on **raw equal weighting over lawful post-preparation/post-interaction response children**, not on every conceivable observation-triggered actualization theory.

### R9 ADVERSE_EVIDENCE RULE

PASS and triggered.

The observed nonuniform fractions count against raw ELCAK. No post hoc child splitting/merging is allowed to repair the null.

### R10 SCOPE GUARDRAIL

PASS.

`RAW_ELCAK = DISFAVORED / CONTRADICTED BY VALIDATED EXTERNAL TARGETS`

`FROZEN_NFC = UNCHANGED`

## Scientific consequence

The first stochastic completion candidate has failed its first serious physical realization test.

That failure is informative rather than program-ending. It shows that **child count alone is not enough** to determine actualization weights in ordinary spectroscopy-like branching.

The external systems exhibit strong channel asymmetry, so any viable stochastic actualization candidate capable of covering this domain must permit probabilities to depend on some quotient-visible channel-specific dynamical structure rather than assigning equal weight solely from sibling cardinality.

Symbolically, the failed raw model is:

`P(C_i | C) = 1 / |Ch(C)|`.

A future candidate, if pursued, would need a form such as:

`P(C_i | C) = W(C -> C_i) / sum_j W(C -> C_j)`

for a lawfully defined nonnegative channel weight `W`.

This equation is only a design-space template. This audit does **not** identify, derive, or authorize `W`.

In particular, the audit does not import Einstein-A coefficients, dipole matrix elements, Born amplitudes, or measured branching ratios into NFC as source authority.

## Why the result does not rescue deterministic actualization

Failure of equal stochastic weighting does not imply deterministic actualization. Both validated systems exhibit repeatable nontrivial frequency distributions over several channels, so a naive one-child deterministic selector would also require additional hidden-state or contextual structure to recover those observed frequencies.

The appropriate update is therefore not `stochastic -> deterministic`; it is:

`child-count-only weighting -> rejected as universal candidate`.

## Program-level status update

`ELCAK_FIRST_RESEARCH_TARGET_STATUS = WITHDRAWN`

`ELCAK_CONDITIONAL_MATHEMATICAL_COHERENCE = PRESERVED`

`ELCAK_UNIVERSAL_PHYSICAL_CANDIDATE = REJECTED_AT_VALIDATED_TARGET_SCOPE`

`POSTFREEZE_ACTUALIZATION_GAP = STILL_OPEN`

`DETERMINISTIC_STOCHASTIC_SOURCE_PARITY = NOT_OVERTURNED`

`NEW_EMPIRICAL_LESSON = ACTUALIZATION_WEIGHTING_IF_STOCHASTIC_MUST_ALLOW_CHANNEL_SENSITIVE_STRUCTURE`

## Routing

`NEXT_OPERATION = NFC_CHANNEL_WEIGHTED_ACTUALIZATION_DESIGN_SPACE_AUDIT_V0_1`

The next operation should ask what classes of quotient-visible channel weight could be introduced without circularly defining `W` from observed frequencies and without silently importing an external quantum rule.

It must include `NO_NONCIRCULAR_WEIGHT_CANDIDATE_JUSTIFIED` as a valid outcome.

A separate question should test whether the new external adverse result deserves durable registration in the NFC post-freeze accepted-findings branch and FCP provenance surfaces. No such mutation is performed here.

NFC_CANON_MUTATION = NO
FCP_READJUDICATION = NO
PGH_READJUDICATION = NO
ELCAK_ADOPTION = NO
