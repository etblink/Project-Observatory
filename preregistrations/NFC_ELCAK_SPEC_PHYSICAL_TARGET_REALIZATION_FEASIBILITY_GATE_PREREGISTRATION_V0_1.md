# NFC ELCAK SPEC Physical-Target Realization Feasibility Gate — Preregistration v0.1

STATUS = PREREGISTERED_AFTER_SOURCE_DISCOVERY_RECONNAISSANCE__VALIDATION_CRITERIA_FROZEN_BEFORE_ADJUDICATION

BASE_ACCEPTANCE_COMMIT = `7fa8c93e5c3990be967c823e10ac001508398df9`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`
SES1_EXECUTION_COMMIT = `ec12e7b924f411ba641ebac2775b0051361fb66d`

## Transparency note

This gate follows open source-discovery reconnaissance in which trapped-ion branching-ratio systems were identified as candidate SES-1 realizations. Therefore this is not a blind target-selection preregistration. It is a validation/adjudication gate: the candidate systems and adverse existing data are known, but the acceptance criteria below are frozen before deciding whether the mapping is legitimate or what consequence follows.

## Question

Does any concrete physical spectroscopy system legitimately instantiate the SES-1 parent/probe/sibling architecture strongly enough that existing or prospective branching-frequency data bear on ELCAK?

If yes, do existing data support, fail to discriminate, or contradict the equal-lawful-child null?

## Candidate systems admitted for validation

Primary candidate:
- single trapped `40Ca+`, parent `4p 2P3/2`, lower-state decay channels `4s 2S1/2`, `3d 2D5/2`, `3d 2D3/2`.

Independent control candidate:
- single trapped `138Ba+`, parent `6P3/2`, lower-state dipole-allowed decay channels `6S1/2`, `5D3/2`, `5D5/2`.

## SES-1 realization gates

R1 FIXED_PARENT: reproducible preparation of one parent state/class.
R2 INDEPENDENT_CHILD_DEFINITION: child classes defined by physical/spectroscopic state distinctions independently of observed frequencies.
R3 EXHAUSTIVE_CHANNEL_SET: cited work identifies all relevant channels at the declared scope.
R4 REPEATED_TRIAL_ACCESS: repeated preparation/decay or equivalent population-transfer protocol exists.
R5 OUTCOME_IDENTIFIABILITY: final channels are experimentally distinguishable / branching fractions measurable.
R6 ELCAK_MAPPING: if k children pass R2-R3, raw ELCAK predicts `1/k` for each.
R7 NO_FREQUENCY_DEFINED_PARTITION: observed branching fractions were not used to create/merge/split the channels.
R8 SPEC_ANALOGY: parent/intervention/response structure is close enough to SES-1 to count as a physical realization candidate, with any mismatch explicitly stated.
R9 ADVERSE_EVIDENCE_RULE: if measured fractions are materially nonuniform relative to reported uncertainty, count that against universal raw ELCAK rather than altering the child partition.
R10 SCOPE_GUARDRAIL: a failure of raw ELCAK does not by itself falsify frozen NFC; ELCAK is post-freeze candidate new physics.

## Outcomes

A = PHYSICAL_TARGET_IDENTIFIED__EXISTING_DATA_SUPPORT_ELCAK
B = PHYSICAL_TARGET_IDENTIFIED__EXISTING_DATA_NONDISCRIMINATING
C = PHYSICAL_TARGET_IDENTIFIED__EXISTING_DATA_CONTRADICT_RAW_ELCAK
D = PROSPECTIVE_TARGET_IDENTIFIED__NO_USABLE_EXISTING_DATA
E = NO_LEGITIMATE_PHYSICAL_TARGET_MAPPING
F = UNDERDETERMINED_OR_REPAIR_REQUIRED

## Consequence if C

If Outcome C is established independently in at least one valid target and corroborated by a second target, raw equal-lawful-child weighting loses first-research-target status and must not be rescued by post hoc partition redefinition.

The scientifically proper next question becomes whether actualization weighting must depend on quotient-visible dynamical/transition-strength structure rather than child count alone.

That next question is not authorized to assume Born-rule amplitudes, Einstein-A coefficients, or any particular external law as NFC truth; it would require a fresh design-space audit.

NFC_CANON_MUTATION = NO
FCP_READJUDICATION = NO_UNLESS_POSTFREEZE_FINDING_IS_LATER_REGISTERED
ELCAK_ADOPTION = NO
