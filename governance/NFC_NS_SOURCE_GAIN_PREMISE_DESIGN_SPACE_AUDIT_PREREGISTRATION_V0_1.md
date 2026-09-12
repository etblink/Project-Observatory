# NFC NS Source Gain Premise Design-Space Audit — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: a769ecc047fe5a515cd9af44b0bcc6d36e1c268b
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
What is the weakest explicit new scientific premise capable of controlling exogenous-source burden across NFC NS transport contexts, given that no monotonicity is source-forced and profile comparison is available only through common-refinement domination?

## Candidate premise classes
K1 Uniform nonexpansive source transport: B_{j+1} \preceq B_j.
K2 Contextwise bounded gain: B_{j+1} \preceq G_j[B_j], with prospectively bounded gain operator G_j.
K3 Affine source law: B_{j+1} \preceq G_j[B_j] \oplus I_j, separating transported source from genuinely new source innovation.
K4 Finite cumulative source budget: cumulative profile innovation/variation over the declared interval is bounded.
K5 Direct work-injection premise coupling source to solution response.
K6 Scalar smallness premise on a chosen norm.
K7 No useful premise identifiable.

## Evaluation axes
Type correctness; minimality; preservation of profile information; distinction between persistent source and new innovation; empirical/specification burden; compatibility with stationary, attenuating, and amplifying sources; compatibility with compact support; no dependence on endogenous Theta_j; no post-hoc use of OpenAI blowup outcome; ability to enter a later forced common-state/continuation theorem.

## Mandatory controls
- Stationary source should not require fictitious innovation.
- Time-varying source must permit genuine innovation.
- Source amplification must be represented explicitly rather than hidden.
- Zero source must remain zero without innovation.
- OpenAI smooth compactly supported forcing remains in scope and is not classified safe/unsafe by fitted constants.

## Outcomes
A UNIQUE_MINIMAL_PREMISE_IDENTIFIED
B SMALL_NONDOMINATED_PREMISE_SET
C AFFINE_GAIN_PLUS_INNOVATION_IS_MINIMAL_GENERAL_SCHEMA__BOUND_SELECTION_OPEN
D ONLY_SCALAR_SMALLNESS_WORKS
E NO_USEFUL_PREMISE
F UNDERDETERMINED

No regularity or endpoint claim is authorized.