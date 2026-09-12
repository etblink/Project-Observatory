# NFC NS Forcing Realization and Localization Bridge Minimality Gate — Preregistration v0.1

STATUS = PREREGISTERED
BASE_ACCEPTANCE_COMMIT = `3ae3449a91e93c5ebb53fe49bace1704b397561a`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Question
What is the minimum noncircular theorem package needed to carry a prospectively declared physical forcing field into the NFC-NS variable-window source ledger: one monolithic forcing/localization bridge, or two typed stages separating forcing realization from window localization?

## Candidate architectures

### A — One-stage monolithic bridge
`T_NS-FORCE-LOC : (F, Q_F, R_NS) -> S_F(W_k)`

A single theorem simultaneously certifies the physical forcing object and assigns its source components to NFC windows.

### B — Two-stage typed bridge
1. `T_NS-FORCE-REAL : (F, Q_F, R_NS) -> F_src`
2. `T_NS-SOURCE-LOC : (F_src, {W_k}) -> S_F(W_k)`

The first stage establishes lawful branch-visible/source-descended forcing representation. The second localizes only the already-certified forcing object into the window system.

### C — Three-stage bridge
Physical forcing realization, intermediate continuum-locality object, then NS-window localization.

### D — No lawful bridge package from present architecture

## Minimality criteria
A preferred architecture must minimize independent assumptions while preserving:
- explicit source provenance;
- separation of physical forcing from endogenous defect;
- Book-V legitimacy witness requirements;
- Book-VI interface discipline;
- support fidelity;
- variable-window compatibility;
- refinement compatibility;
- representation invariance;
- no outcome leakage;
- independent status of later source transport weighting.

## Mandatory adversarial tests
- **Bundling fallacy:** one theorem name does not make two logically independent assumptions one assumption.
- **Ontology-by-localization:** localization may not silently establish that the physical forcing is a lawful NFC object.
- **Overfactorization:** do not introduce extra intermediate stages unless they carry an independently necessary invariant or theorem burden.
- **Map-factorization test:** if the monolithic map canonically factors through a distinct certified forcing object, that is evidence for the two-stage form.
- **Countermodel test:** consider cases where lawful forcing realization exists but localization differs across window policies, and cases where a proposed incidence law exists for a target field that is not lawfully realized.
- **OpenAI control:** architecture must not be selected because it better fits the known forced-blowup outcome.

## Outcome taxonomy
- A `ONE_STAGE_MONOLITHIC_BRIDGE_IS_MINIMAL_AND_NONCIRCULAR`
- B `TWO_STAGE_REALIZATION_THEN_LOCALIZATION_IS_MINIMAL`
- C `THREE_OR_MORE_TYPED_STAGES_ARE_REQUIRED`
- D `NO_MINIMAL_BRIDGE_PACKAGE_IDENTIFIED`
- E `UNDERDETERMINED`
- F `REPAIR_REQUIRED`

## Guardrails
No proof of a forcing realization theorem is attempted here. No source transport law is adjudicated. No forced regularity conclusion is authorized. The operation determines only the minimal logical architecture of the missing bridge.