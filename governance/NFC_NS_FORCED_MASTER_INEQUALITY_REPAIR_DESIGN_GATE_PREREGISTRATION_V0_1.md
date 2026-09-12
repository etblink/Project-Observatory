# NFC NS Forced Master Inequality Repair Design Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 11147285c1cde2a465496454becd38fb23f65f1d
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
What is the lowest-assumption structural repair of the frozen unforced NS master inequality for a forced target, given that the old condition depends on viscosity/coercivity and initial H^s size but contains no source term, and the OpenAI/FCP control has u0=0 with nonzero smooth compactly supported forcing and claimed finite-time blowup?

## Design requirements
A forced sufficient criterion must:
- reduce to the frozen unforced criterion at zero source;
- not classify a forced problem as safe merely because u0=0;
- keep source burden distinct from endogenous defect;
- preserve the accepted multiscale/profile information until a theorem licenses scalarization;
- compare source drive against a prospectively defined dissipative/coercive reserve rather than against known outcomes;
- remain compatible with source gain/innovation envelopes;
- state explicit failure conditions.

## Candidate repairs
M1 Add one scalar source norm/amplitude to the old initial-data term.
M2 Duhamel/semigroup effective source amplitude with dissipative memory kernel.
M3 Profile-local source-versus-dissipative-reserve domination, e.g. B_source \preceq R_diss with strict margin on aligned common refinements, combined with the unforced initial-state condition.
M4 Cumulative source-gain/innovation profile dominated by a cumulative dissipative reserve.
M5 State-coupled source-work bound inserted directly into the master criterion.
M6 Leave the old master inequality unchanged for forced scope.
M7 No coherent repair.

## Mandatory tests
1. zero-source reduction;
2. u0=0 forced reversal;
3. same scalar norm / different scale distribution;
4. source gain and innovation compatibility;
5. refinement/dictionary invariance;
6. source/endogenous type discipline;
7. no coefficient fitted to OpenAI outcome;
8. ability to fail on some smooth compactly supported forces;
9. compatibility with a future common-state/continuation theorem rather than energy control alone.

## Outcomes
A PROFILE_LOCAL_SOURCE_DISSIPATION_REPAIR_DOMINATES_AS_FIRST_TARGET
B SMALL_NONDOMINATED_REPAIR_SET
C ONLY_SCALAR_OR_STATE_COUPLED_REPAIR_SURVIVES
D NO_NONCIRCULAR_REPAIR
E REPAIR_REQUIRED
F UNDERDETERMINED

No forced-regularity theorem is authorized by this design gate.