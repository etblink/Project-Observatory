# NFC NS Source Transport Law Design Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 1d1e790104a9f02b64f6d1a13f2b0b7fb1a213c0
PROVISIONAL_HYPOTHESES:
- P_NS-FORCE-PAIR-REP
- T_NS-WINDOW-CONTEXT-MIN
- lawful context restriction Res_U
PROVISIONAL_ONLY: YES

## Question
Given a pre-transport exogenous source ledger on the active Book-III context chain, what is the weakest noncircular transport structure for source content? In particular, may the existing endogenous transport factor Theta_j be reused, or is a distinct source-transfer law required before any weighting/contraction statement is meaningful?

## Candidate classes
T1 — Reuse endogenous Theta_j directly as source weight.
T2 — Functorial source pushforward: for each lawful context transfer f_j:U_j->U_{j+1}, define a source map S(f_j):Source(U_j)->Source(U_{j+1}), preserving zero/linearity/provenance and composing with transfer chains.
T3 — Restriction-only persistence: source ledger is re-evaluated independently in each context using Res_U, with no pushforward semantics.
T4 — State/response-derived source transport.
T5 — Arbitrary new scalar source weight per step.
T6 — No justified source transport.

## Evaluation axes
- type correctness;
- compatibility with Book-III transfer composition;
- restriction naturality;
- preservation of provenance/component identity;
- representation invariance;
- no endogenous-defect conflation;
- no response inversion;
- no unjustified contractivity assumption;
- ability to support a later transported source ledger;
- OpenAI negative-control compatibility.

## Mandatory adversarial tests
1. A stationary exogenous source may persist even when endogenous observable content contracts.
2. Zero source must remain zero under transport.
3. Source addition/scaling must commute with transport.
4. Two-step source transport must equal composed one-step transport where contexts compose lawfully.
5. If a source leaves the represented context, its later restriction may vanish without implying annihilation of the original source.
6. No source contraction coefficient may be inferred from Theta_j unless separately proved.

## Outcomes
A EXISTING_BOOK_III_TRANSPORT_ALREADY_APPLIES_TO_EXOGENOUS_SOURCE
B FUNCTORIAL_SOURCE_TRANSFER_IS_MINIMAL_NEW_STRUCTURE__SCALAR_WEIGHTING_OPEN
C RESTRICTION_ONLY_IS_SUFFICIENT__NO_PUSHFORWARD_NEEDED
D NO_NONCIRCULAR_SOURCE_TRANSPORT_AVAILABLE
E REPAIR_REQUIRED
F UNDERDETERMINED

No source-project mutation or forced-regularity claim.