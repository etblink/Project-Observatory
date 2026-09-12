# NFC NS Forcing Realization Candidate Gate — Preregistration v0.1

STATUS = PREREGISTERED
BASE_ACCEPTANCE_COMMIT = `a06cfa90b7063951ca9157af78997a779e8dcf91`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Question
What is the weakest lawful representation type that can serve as the certified forcing object `F_src` in the accepted chain

`F -> Q_F^{Pi,N,a} -> T_NS-FORCE-REAL -> F_src`

without yet localizing to NS windows, choosing source transport weights, or importing forced-NS outcome information?

## Candidate lanes

- R1 `CERTIFIED_OBSERVABLE_FAMILY_REUSE`: represent forcing as a Book-VI certified observable family.
- R2 `BOOK_III_FLUX_OR_ACCUMULATOR_REUSE`: represent forcing through an existing flux/accumulator object.
- R3 `SPEC_STYLE_PROBE_RESPONSE_REUSE`: represent forcing as an admissible process/probe-response object.
- R4 `ENDOGENOUS_DEFECT_REUSE`: represent forcing as ordinary NS defect burden.
- R5 `NEW_TYPED_FORCING_OBSERVABLE_FAMILY`: define a new branch-visible forcing family that reuses Book-V/VI legitimacy and continuum-interface machinery but remains typed as exogenous source.
- R6 `HYBRID_TYPED_SOURCE_PLUS_CERTIFIED_OBSERVABLE_COMPONENTS`: a new forcing-source wrapper whose components are individually certified observable families.
- R7 `NO_LAWFUL_CANDIDATE`.

## Mandatory criteria
A qualifying `F_src` must be:
1. prospectively determined from `F` and the frozen source descriptor policy;
2. branch-visible and compatible with Book-V legitimacy;
3. compatible with Book-VI continuum-interface discipline;
4. explicitly exogenous and not silently identified with endogenous defect;
5. able to preserve source support/scale/provenance data needed for later localization;
6. refinement-compatible at the representation level;
7. independent of later window assignment and source transport weighting;
8. independent of known safe/blowup outcome;
9. capable in principle of representing nonzero smooth compactly supported forcing such as the frozen OpenAI negative control without assigning it a posteriori special status.

## Mandatory adversarial tests
- observable-vs-source type test;
- flux-vs-source test;
- probe-vs-persistent-field test;
- defect-conflation test;
- wrapper-vacuity test;
- hidden-outcome test;
- loss-of-provenance test;
- overengineering test.

## Outcome taxonomy
- A `EXISTING_FROZEN_TYPE_SUFFICES_WITHOUT_NEW_DECLARATION`
- B `EXISTING_TYPE_SUFFICES_ONLY_WITH_EXPLICIT_FORCING_SUBTYPE_DECLARATION`
- C `NEW_TYPED_FORCING_OBSERVABLE_FAMILY_IS_MINIMAL`
- D `HYBRID_SOURCE_WRAPPER_IS_MINIMAL`
- E `NO_LAWFUL_CANDIDATE_IDENTIFIED`
- F `UNDERDETERMINED`
- G `REPAIR_REQUIRED`

## Guardrails
No source localization, source transport, common-state discharge, or forced regularity theorem is under adjudication. No frozen NFC mutation is authorized.