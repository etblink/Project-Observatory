# NFC Actualization Parity-Breaking Evidence Requirements Audit — Preregistration v0.1

STATUS = PREREGISTERED__AUDIT_NOT_EXECUTED
DATE = 2026-09-11

## 1. Operation

NFC_ACTUALIZATION_PARITY_BREAKING_EVIDENCE_REQUIREMENTS_AUDIT

This is a bounded methodological audit housed in Project Observatory. It asks what kind of theoretical or empirical evidence could legitimately break the accepted frozen-scope parity between deterministic and genuinely stochastic actualization completions.

The operation must not invent a selector, choose a preferred ontology, or propose an experiment before establishing discriminability requirements.

## 2. Exact provenance

PROJECT_OBSERVATORY_BASE = 712f00f57268bf07c87249c55942a0ea57bb5472
PROJECT_OBSERVATORY_BRANCH = research/nfc-actualization-parity-breaking-evidence-v0.1

NFC_FROZEN_CANON_COMMIT = ed3047c2cbc0abc34d2549dd27754e4d3d05af78
NFC_FROZEN_CANON_TREE = 00ef55ff36d5e9663ca1ef2c9566e2bc1396f973

ACCEPTED_PARITY_RESULT = C__COMPLETION_CLASS_PARITY_PRESERVED_AT_FROZEN_SCOPE
PARITY_ACCEPTANCE_COMMIT = 712f00f57268bf07c87249c55942a0ea57bb5472

## 3. Frozen question

> What minimum evidence structure would be sufficient to discriminate deterministic actualization (K1) from genuinely stochastic actualization (K2) without circularly encoding the desired completion class into auxiliary assumptions, representations, initial conditions, hidden variables, coarse-graining, or statistical interpretation?

## 4. Evidence classes to classify

E1__SOURCE_THEORETIC
A new theorem from accepted premises rules out one completion class or derives the other.

E2__BRANCH_TO_SOURCE_LIFT
A branch-local deterministic/stochastic mechanism is proved to lift representation-independently and universally to the history-level actualization frontier.

E3__EMPIRICAL_DISTRIBUTIONAL
Observed frequencies/distributions distinguish fully specified K1 and K2 candidate completions.

E4__EMPIRICAL_SEQUENCE_LEVEL
Pathwise/temporal structure, not merely aggregate frequencies, distinguishes the candidate completions.

E5__INTERVENTIONAL_OR_COUNTERFACTUAL
A qualified intervention/counterfactual protocol yields different observable predictions under the two completion classes.

E6__REPRESENTATION_OR_COMPLEXITY
Compression, simplicity, canonicality, or representation invariance is proposed as evidence for one class.

E7__NEGATIVE_IDENTIFIABILITY
A proof shows that the classes are observationally equivalent at the licensed interface, making empirical discrimination impossible without stronger assumptions.

## 5. Required discriminability standard

For empirical evidence to break parity, two candidate completions D and S must be specified strongly enough that they induce distinct observable consequence sets under the same admissible interface and the same auxiliary-data policy.

Let O(D,A) and O(S,A) denote the licensed observable consequence sets under common auxiliary assumptions A.

A parity-breaking empirical discriminator requires at minimum:

`O(D,A) != O(S,A)`

with the difference traceable to completion class rather than unequal auxiliary freedom.

If every stochastic observable law can be reproduced by a deterministic enlarged-state completion allowed under A, or every deterministic observable law is contained as a degenerate stochastic case, then aggregate data alone do not identify ontic completion class.

## 6. Anti-smuggling requirements

Any proposed discriminator must pass:

R1__SAME_OBSERVABLE_INTERFACE
R2__SAME_SCOPE
R3__SAME_AUXILIARY_FREEDOM
R4__PREDECLARED_DECISION_RULE
R5__REPRESENTATION_RESISTANCE
R6__NO_HIDDEN_VARIABLE_ASYMMETRY
R7__NO_PROBABILITY_INTERPRETATION_ASYMMETRY
R8__FAILURE_EXPOSURE
R9__ATTRIBUTION_TO_COMPLETION_CLASS
R10__NFC_SCOPE_COMPATIBILITY

## 7. Mandatory reversals

### Deterministic emulation reversal

Try to reproduce any proposed stochastic observable distribution using deterministic dynamics on an enlarged hidden state/random-seed space. If allowed auxiliary freedom makes this possible without violating NFC, the observable distribution does not by itself establish genuine stochasticity.

### Stochastic embedding reversal

Represent a deterministic completion as a Dirac/degenerate stochastic kernel. If a proposed test treats that notation as stochastic evidence, reject it.

### Coarse-graining reversal

Test whether deterministic fine-grained evolution can look stochastic after NFC observational quotienting.

### Branch-lift reversal

For any branch-local discriminator, demand a theorem showing that branch-specific assumptions are not doing the discriminatory work.

### Complexity reversal

Test whether simplicity/canonicality preferences change under equivalent encoding or hidden-state relocation.

## 8. Outcome taxonomy

Exactly one primary outcome must be selected.

A__SOURCE_THEORETIC_PARITY_BREAKER_IS_CURRENTLY_AVAILABLE

Frozen or already-accepted NFC machinery already supplies a noncircular theoretical discriminator not recognized by the prior audit.

B__EMPIRICAL_PARITY_BREAKING_IS_POSSIBLE_IN_PRINCIPLE_UNDER_CURRENT_NFC_INTERFACE

There exists a representation-resistant empirical discriminator class that can distinguish K1/K2 without first restricting one class by extra ontology.

C__EMPIRICAL_PARITY_BREAKING_REQUIRES_STRONGER_CANDIDATE_SPECIFICATION

Deterministic-vs-stochastic completion class alone is too broad for empirical discrimination; testability requires concrete candidate laws plus matched auxiliary assumptions. Source-theoretic or branch-lift evidence may still break parity.

D__PARITY_IS_OBSERVATIONALLY_UNIDENTIFIABLE_AT_CURRENT_NFC_SCOPE

A source-bound argument establishes that no licensed observation can distinguish K1/K2 even after concrete candidate specification unless NFC's observational interface itself changes.

E__UNDERDETERMINED

The current source/method does not support a responsible A–D classification.

F__FORMAL_REPAIR_REQUIRED

A protocol/source defect blocks adjudication.

## 9. Acceptance standard

Outcome B requires an explicit discriminator construction or theorem-class that survives all mandatory reversals.

Outcome C requires a constructive identifiability argument showing why completion class alone underdetermines observables, plus examples of what additional specification would make the question testable.

Outcome D requires a stronger impossibility result than ordinary underdetermination: observational equivalence must be source-forced for all admissible concrete K1/K2 candidates at the current interface.

## 10. Stop conditions

At execution end:

- produce one evidence-requirements audit artifact;
- select exactly one A–F outcome;
- do not invent or endorse a selector;
- do not mutate NFC/FCP/PGH;
- do not propose a specific experiment unless the audit first establishes a discriminator class that justifies doing so;
- do not create empirical credit.

AUDIT_PREREGISTERED = YES
AUDIT_EXECUTED = NO
