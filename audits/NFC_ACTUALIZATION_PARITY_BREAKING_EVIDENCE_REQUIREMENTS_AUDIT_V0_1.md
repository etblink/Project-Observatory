# NFC Actualization Parity-Breaking Evidence Requirements Audit v0.1

STATUS = EXECUTED__PRIMARY_OUTCOME_C
DATE = 2026-09-11

## 1. Operation

NFC_ACTUALIZATION_PARITY_BREAKING_EVIDENCE_REQUIREMENTS_AUDIT

Execution of the preregistration frozen at `51427680b7bac3f83f763b111e9ff9a7b04b430e`.

## 2. Exact provenance

PROJECT_OBSERVATORY_PREREG_COMMIT = 51427680b7bac3f83f763b111e9ff9a7b04b430e
PROJECT_OBSERVATORY_BRANCH = research/nfc-actualization-parity-breaking-evidence-v0.1

NFC_FROZEN_CANON_COMMIT = ed3047c2cbc0abc34d2549dd27754e4d3d05af78
NFC_FROZEN_CANON_TREE = 00ef55ff36d5e9663ca1ef2c9566e2bc1396f973

PARITY_ACCEPTANCE_COMMIT = 712f00f57268bf07c87249c55942a0ea57bb5472
PARITY_RESULT = C__COMPLETION_CLASS_PARITY_PRESERVED_AT_FROZEN_SCOPE

## 3. Primary result

PRIMARY_OUTCOME = C__EMPIRICAL_PARITY_BREAKING_REQUIRES_STRONGER_CANDIDATE_SPECIFICATION

Short statement:

> Deterministic actualization and genuinely stochastic actualization are too broad as completion classes to generate a representation-resistant empirical discriminator by themselves. Empirical discrimination becomes meaningful only after specifying concrete candidate laws on both sides, fixing the same observable interface, scope, initial/boundary-data policy, hidden-state allowance, and probability interpretation, and then showing that their licensed observable consequence sets differ. Frozen NFC supplies no class-level empirical discriminator and does not prove universal observational indistinguishability after such concrete specification.

## 4. Why completion class alone is not a prediction

A completion class says how actualization is structured in general, but does not yet specify a unique law.

K1 permits many deterministic selector laws:

`h* = A_D(H; theta_D)`

with different lawful parameters/auxiliary structures `theta_D`.

K2 permits many genuinely stochastic laws:

`mu_S(. | H; theta_S)`

with different weights, kernels, histories, and auxiliary structures `theta_S`.

Therefore the observable consequence set of the entire class is a union over many candidate laws. Broad unions can overlap almost completely even when particular members make sharply different predictions.

CLASS_LABEL_ALONE_GENERATES_TESTABLE_PREDICTION = NO

## 5. NFC observational-interface consequence

Book I grants canonical force to observational quotient classes, not hidden presentation detail. This immediately creates a coarse-graining problem for ontic discrimination:

- deterministic fine-grained histories can map to the same quotient-level statistics as stochastic models;
- stochastic internal structure can collapse to deterministic-looking quotient outcomes;
- observational equivalence does not by itself identify what hidden structure produced an outcome.

This does not prove permanent unidentifiability. It means any empirical parity breaker must be stated at the licensed quotient/interface level and must survive alternative hidden-state realizations allowed by the candidate specification.

## 6. Deterministic-emulation reversal

Given a concrete stochastic observable law over a finite or suitably encoded sequence space, one can in principle construct a deterministic enlarged-state model whose initial hidden state/seed selects the sequence according to the same observable distribution.

This construction does not prove that nature is deterministic. It proves that **observed frequencies alone** cannot establish genuine ontic stochasticity while unrestricted hidden-state/seed freedom remains available.

For the reversal to be blocked, a candidate theory must independently restrict the admissible hidden-state space or initial-state distribution. That restriction is part of the candidate specification and must be charged symmetrically.

AGGREGATE_FREQUENCY_EVIDENCE_ALONE_BREAKS_PARITY = NO

## 7. Stochastic-embedding reversal

Any deterministic selector can be represented by a degenerate/Dirac stochastic kernel.

Therefore the mere appearance of probability notation or a stochastic formalism cannot distinguish genuine K2 from K1 embedded in that formalism.

A K2 candidate must make a nondegeneracy claim—multiple outcomes/history continuations carrying irreducible nonzero physical weight—and that claim must produce observable consequences not equally realizable by an allowed K1 candidate.

PROBABILITY_NOTATION_BREAKS_PARITY = NO

## 8. Coarse-graining reversal

NFC's observational quotient makes this reversal especially important.

A deterministic microtrajectory can induce stochastic-looking quotient transitions whenever multiple hidden microstates map to one observable class. Conversely, a stochastic microprocess can induce a deterministic quotient transition when all supported microtransitions land in the same observable class.

Thus:

`fine-grained completion class != automatically identifiable quotient-level completion class`.

A valid parity-breaking experiment must target a difference that survives NFC's admissible quotient/interface.

## 9. Evidence-class adjudication

### E1 — source-theoretic

Can break parity in principle.

A new theorem could do so if it derived, from accepted source premises, either:

- single-valued actualization with no nontrivial stochastic freedom; or
- an irreducible normalized nondegenerate history measure/kernel and its physical interpretation.

Frozen NFC currently contains neither.

STATUS = POSSIBLE_IN_PRINCIPLE__NOT_CURRENTLY_AVAILABLE

### E2 — branch-to-source lift

Can break parity in principle only if a branch-local mechanism is proved to be source-forced, representation-independent, and universal rather than dependent on branch-specific hypotheses.

No such lift is currently established.

STATUS = POSSIBLE_IN_PRINCIPLE__NO_CURRENT_LIFT

### E3 — empirical distributional

Cannot break parity at the broad class level because deterministic hidden-state models can reproduce stochastic observable distributions when auxiliary freedom is unrestricted, and deterministic laws are degenerate stochastic laws.

Can discriminate **concrete** D/S candidates when matched auxiliary rules yield different observable distributions.

STATUS = CANDIDATE_LEVEL_ONLY

### E4 — empirical sequence/path level

Potentially more informative than aggregate frequencies because temporal correlations, transition support, recurrence, and path constraints can differ even when marginals agree.

But class-level parity still survives unless deterministic auxiliary freedom and stochastic kernels are concretely bounded.

STATUS = CANDIDATE_LEVEL_ONLY__HIGHER_INFORMATION_THAN_AGGREGATES

### E5 — interventional/counterfactual

Potentially discriminating if the two concrete completions predict different responses under the same admissible intervention/counterfactual protocol.

Again, the protocol must not grant one side extra hidden-state freedom or interpretive rules.

STATUS = CANDIDATE_LEVEL_ONLY

### E6 — representation/complexity

Compression, simplicity, uniqueness of notation, or canonical representation is not by itself physical evidence for K1 or K2. Equivalent encodings can move complexity between dynamics, state, measure, and hidden variables.

Such criteria may guide model selection only after a representation-resistant complexity measure and physical rationale are separately justified.

STATUS = NONQUALIFYING_BY_ITSELF

### E7 — negative identifiability

Current NFC supports local/structural reasons for underdetermination but does not prove that **all** fully specified deterministic and stochastic completion pairs are observationally equivalent at every licensed interface.

Therefore a universal impossibility result is not justified.

STATUS = NO_GLOBAL_IMPOSSIBILITY_THEOREM

## 10. Minimum candidate specification for an empirical test

Before an empirical D-vs-S discriminator is meaningful, both candidate completions must freeze at least:

1. HISTORY_DOMAIN — exact admissible history/state domain;
2. ACTUALIZATION_LAW — deterministic map or nondegenerate stochastic kernel/measure;
3. INITIAL_BOUNDARY_POLICY — what initial/boundary data are fixed, distributed, or inferred;
4. HIDDEN_STATE_POLICY — whether enlarged latent state/random seed is allowed and under what constraints;
5. OBSERVABLE_MAP — exact NFC-licensed map from histories/states to recorded observables;
6. SCOPE — where the law is claimed to apply;
7. PARAMETER_POLICY — fixed parameters, fit parameters, and pre-data estimation rules;
8. STOCHASTIC_INTERPRETATION — if K2, what the weights physically mean and how repeated records relate to them;
9. INTERVENTION_POLICY — if relevant, what operations are admissible and how each model responds;
10. DECISION_FUNCTIONAL — preregistered rule mapping data to reject/survive/inconclusive.

Without matched specification on these fields, any apparent discriminator can be attributed to unequal auxiliaries rather than completion class.

## 11. Formal discriminability condition

Let D and S be concrete candidate completions and A the common auxiliary-policy package.

Let `O(D,A)` and `O(S,A)` denote the sets of licensed observable probability laws / sequence laws / intervention responses each candidate permits.

A necessary condition for empirical discrimination is:

`O(D,A) != O(S,A)`.

A strong one-shot falsifier requires an observable event/test whose permitted consequences are disjoint.

A statistical discriminator requires at least a predeclared functional with distinct asymptotic or finite-sample behavior under the two candidate consequence sets.

If:

`O(D,A) = O(S,A)`

then no observation at that interface can distinguish the two candidate completions; stronger interface or assumptions are required.

## 12. What would genuinely break parity

The audit identifies three legitimate routes:

### Route T — theorem

A new source theorem rules out K1 or K2 or derives one with physical force.

### Route L — lift

A branch-local mechanism is proved to lift universally without branch-specific discriminatory assumptions.

### Route E — empirical candidate discrimination

Two fully specified D/S candidates with matched auxiliaries produce different licensed observable consequence sets and a preregistered test selects between them.

No fourth shortcut is currently justified.

## 13. Why Outcome B is not justified

The audit does not find a **class-level** representation-resistant empirical test that distinguishes determinism from genuine stochasticity while leaving both classes otherwise unrestricted.

Any apparent distributional discriminator can be neutralized by changing hidden-state freedom or by degenerate stochastic embedding unless those options are already fixed by candidate identity.

## 14. Why Outcome D is too strong

Current NFC does not establish a universal no-go theorem saying every fully specified K1 candidate has an observationally equivalent K2 candidate, or vice versa, under every possible licensed interface.

Once concrete laws and auxiliary policies are fixed, distinct predictions may exist.

Therefore the correct result is stronger-specification requirement, not permanent observational unidentifiability.

## 15. Primary adjudication

PRIMARY_OUTCOME = C__EMPIRICAL_PARITY_BREAKING_REQUIRES_STRONGER_CANDIDATE_SPECIFICATION

SOURCE_THEORETIC_BREAKER_CURRENTLY_AVAILABLE = NO
BRANCH_TO_SOURCE_LIFT_CURRENTLY_AVAILABLE = NO
CLASS_LEVEL_EMPIRICAL_DISCRIMINATOR = NO
CONCRETE_CANDIDATE_EMPIRICAL_DISCRIMINATION = POSSIBLE_IN_PRINCIPLE
GLOBAL_OBSERVATIONAL_IMPOSSIBILITY_PROVED = NO

## 16. Scientific consequence

The parity frontier is now operationally sharper.

The scientifically meaningful next step is **not** to collect generic evidence for determinism or randomness.

It is to construct or identify concrete candidate actualization laws whose auxiliary freedoms are matched tightly enough that they make different quotient-visible predictions.

Until such candidates exist, an empirical program cannot attribute observed differences to completion class itself.

## 17. Routing recommendation

The next highest-information operation should be a **candidate-generation feasibility gate**, not an experiment:

`NFC_ACTUALIZATION_CANDIDATE_GENERATION_FEASIBILITY_GATE`

Question:

> Does frozen NFC contain enough structure to generate at least one non-ad-hoc deterministic completion candidate and at least one non-ad-hoc genuinely stochastic completion candidate with matched scope/interface, such that both are failure-exposed and make distinguishable predictions?

The gate must allow the answer `NO_CANDIDATE_PAIR_JUSTIFIED`.

Only if a qualified pair exists should a prospective empirical discriminator be designed.

## 18. Stop state

AUDIT_EXECUTED = YES
PRIMARY_OUTCOME = C__EMPIRICAL_PARITY_BREAKING_REQUIRES_STRONGER_CANDIDATE_SPECIFICATION
CLASS_LEVEL_TEST = NOT_JUSTIFIED
CANDIDATE_LEVEL_TEST = POSSIBLE_IN_PRINCIPLE
NFC_MUTATED = NO
FCP_MUTATED = NO
PGH_MUTATED = NO
SELECTOR_INVENTED = NO
EXPERIMENT_OPENED = NO
EMPIRICAL_CREDIT_CREATED = NO
