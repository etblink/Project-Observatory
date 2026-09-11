# NFC Equal-Lawful-Child Kernel Formalization and Falsification Gate — Independent Acceptance v0.1

STATUS = ACCEPTED__OUTCOME_B__COHERENT_CONDITIONAL_MODEL__NO_CURRENT_EMPIRICAL_TARGET

EXECUTION_COMMIT = `c30b8d886b336da449df342938f8d7d34a071314`

PREREGISTRATION_COMMIT = `26c921509796bc4d531eb5cba2d48fba4a6f0f62`

BASE_ACCEPTANCE_COMMIT = `b79577a4ad2efb055bdb06ea9a9c4aebc7af6e67`

FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Acceptance decision

`PRIMARY_OUTCOME_ACCEPTED = B__ELCAK_MATHEMATICALLY_COHERENT__NO_CURRENT_EMPIRICAL_TARGET`

`OUTCOME_CORRECTION_REQUIRED = NO`

## Mathematical review

PASS.

The local kernel `1/|Ch(C)|` is normalized, and multiplication over finite paths yields a normalized cylinder family. Marginalization is projectively consistent because each local child kernel sums to one.

The execution correctly avoids claiming that this probability law is already contained in NFC. The only frozen-source ingredient is the lawful child count; equal physical weighting is explicitly post-freeze new physics.

## Infinite-path review

PASS WITH SCOPE GUARDRAIL.

The execution properly distinguishes finite-horizon projective consistency from a fully promoted infinite-path measure. Standard measure-extension machinery can complete the mathematical model under the stated countable/cylinder assumptions, but that is ordinary external mathematics, not source-level NFC theorem content.

No physical authority follows from existence of the measure.

## Representation review

PASS.

ELCAK is invariant under representation changes that preserve the declared parent-child continuation relation. If the child partition changes, the physical/model specification has changed rather than merely its notation.

This is why prospective partition freezing is mandatory.

## Partition-selection vulnerability

ACCEPTED AS A REAL LIMITATION.

The execution correctly identifies the continuation/refinement protocol as an auxiliary burden. A probability law over children cannot be empirically meaningful if the analyst is free to split or merge the child classes after seeing outcomes.

This does not refute ELCAK, but it blocks any present empirical claim until the test family, child-equivalence rule, stage map, window, and stopping protocol are prospectively fixed.

## State-sufficiency / Markov review

PASS.

The kernel is local in the declared state. That locality is physically harmless only if the declared state contains all quotient-visible history relevant to future continuation, or if a separate state-sufficiency hypothesis is made explicit.

The execution does not silently assume i.i.d. repeated trials. This is essential.

## Defect/surprisal review

PASS.

The new path surprisal

`sum log(delta+1)`

is not identified with the frozen defect ledger

`sum delta`.

Their coincidence in unary/binary regimes (with base-2 logarithm) is correctly treated as a special case, not a universal source theorem.

## Testbed survey review

PASS.

The branch ratings are conservative:

- SPEC and BIO qualify only as `T2__PROSPECTIVE_MODEL_LEVEL_TESTBED_POSSIBLE`;
- no branch is promoted to `T3__EMPIRICAL_TESTBED_POSSIBLE_WITH_NEW_PROTOCOL` yet;
- RH is correctly excluded as a physical empirical target;
- SCC is retained as a structural/counterexample environment rather than phenomenological evidence.

SPEC is presently the stronger observation-linked candidate because it already contains admissible probes, response classes, probe episodes, and transition ledgers. BIO is the stronger generation/repetition candidate because it already contains replication/heredity structure. Neither currently supplies a prospectively frozen physical actualization fork plus repeated/interventional data.

## Scientific-status review

PASS.

`SOURCE_DERIVATION = NO`

`PHYSICAL_AUTHORITY = NONE`

`EMPIRICAL_SUPPORT = NONE`

`CURRENT_EMPIRICAL_TESTABILITY = NO`

`CONDITIONAL_MODEL_STATUS = QUALIFIED_FOR_TARGET_FEASIBILITY_WORK`

These labels are appropriately conservative.

## Accepted routing

`NFC_FROZEN_CANON_MUTATION_REQUIRED = NO`

`FCP_READJUDICATION_REQUIRED = NO`

`PGH_READJUDICATION_REQUIRED = NO`

`ELCAK_ADOPTION = NOT_AUTHORIZED`

`NEXT_OPERATION = NFC_ELCAK_SPEC_BIO_TARGET_QUALIFICATION_GATE_V0_1`

The next gate should compare SPEC and BIO as target-construction environments under the exact same ELCAK prerequisites. It must be allowed to conclude that neither can reach T3 without genuinely new experimental/realization machinery.