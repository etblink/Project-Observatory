# NFC SPEC Transition Coupling Object Feasibility Gate — Preregistration v0.1

STATUS = PREREGISTERED

BASE_ACCEPTANCE_COMMIT = `cb6f3a492f0aa417987d5e76b1e73836fb2253e5`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Question

Can a non-arbitrary branch-visible transition-coupling object `M_SPEC(parent, probe, child)` be constructed solely from already-frozen SPEC/YM/SM/spine objects, without importing measured branching fractions or standard quantum transition amplitudes as unexplained primitives?

## Candidate frozen ingredients

- `L_SPEC` and its theorem-visible spectral/eigenclass structure;
- the SPEC operator packet `(L_SPEC, Dom(L_SPEC), Inv_SPEC, B_loss)`;
- admissible probes `P` and response signatures `Resp(X;P)`;
- transition-accessible spectral packets;
- transition ledgers;
- SPEC spectral margin;
- YM transport-compatible invariant bilinear form;
- YM root/gauge/operator structure;
- SM superselection, matter-representation and matter-extended operator structure where licensed;
- Book-III transport/coercive invariants.

## Qualification criterion

A candidate `M_SPEC` qualifies only if:

1. the parent, probe and child each have a frozen branch-visible representation in the formula;
2. the construction yields child-specific nonnegative couplings before target outcome frequencies are observed;
3. it is invariant under frozen quotient/presentation equivalence;
4. it contains no arbitrary child-specific constants or basis tie-breakers;
5. its relation to physical transition strength is established by a theorem or a separately identified open bridge, not assumed by analogy;
6. it distinguishes at least some inequivalent accessible channels;
7. it can be normalized into prospective relative probabilities;
8. its failure conditions are explicit.

## Mandatory reversals

- Probe representation reversal: is the probe represented as an operator/vector in the same space as spectral modes, or merely as an admissible process label?
- Eigenclass reversal: do eigenclasses/eigenvalues determine coupling or only mode identity/location?
- Bilinear-form reversal: does the invariant bilinear form act on the relevant parent/probe/child objects, or only on YM root/operator directions?
- Matter-extension reversal: does the SM/SPEC matter operator include an interaction/coupling term capable of inducing relative channel amplitudes, or only uncoupled/harmonized structure?
- Response reversal: does `Resp(X;P)` contain a quantitative amplitude/rate, or only a quotient-visible signature/class?
- Conservative extension: can two different coupling assignments preserve all frozen theorem truths?

## Outcome taxonomy

- `A__TRANSITION_COUPLING_OBJECT_ALREADY_DERIVABLE`
- `B__COUPLING_OBJECT_DERIVABLE_UP_TO_ONE_EXPLICIT_TRANSFER_THEOREM`
- `C__PARTIAL_GEOMETRIC_OR_OPERATOR_COUPLING_STRUCTURE_ONLY`
- `D__NO_NONARBITRARY_COUPLING_OBJECT_FROM_FROZEN_INGREDIENTS`
- `E__GENUINELY_NEW_BRANCH_PRIMITIVE_OR_INTERACTION_TERM_REQUIRED_AT_AUDITED_SCOPE`
- `F__UNDERDETERMINED`
- `G__REPAIR_REQUIRED`

Outcome E requires stronger evidence than D; it should be used only if conservative-extension analysis shows existing frozen ingredients cannot determine channel-specific couplings without adding new branch content.

## Routing

No frozen NFC mutation. No FCP/PGH readjudication. If D is accepted, identify the narrowest new theorem/bridge obligation. If E is accepted, identify the narrowest genuinely new branch primitive or interaction term, without asserting any particular standard-physics interpretation.