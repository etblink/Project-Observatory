# NFC Equal-Lawful-Child Kernel Formalization and Falsification Gate v0.1

STATUS = EXECUTED__OUTCOME_B__COHERENT_CONDITIONAL_MODEL__NO_CURRENT_EMPIRICAL_TARGET

PREREGISTRATION_COMMIT = `26c921509796bc4d531eb5cba2d48fba4a6f0f62`

BASE_ACCEPTANCE_COMMIT = `b79577a4ad2efb055bdb06ea9a9c4aebc7af6e67`

FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Primary outcome

`PRIMARY_OUTCOME = B__ELCAK_MATHEMATICALLY_COHERENT__NO_CURRENT_EMPIRICAL_TARGET`

ELCAK is internally coherent as a **conditional post-freeze model** on a prospectively fixed, locally finite continuation tree. It does not contradict the frozen NFC theorem corpus at the audited scope.

No existing NFC branch currently supplies all ingredients needed for a calibrated empirical test without additional protocol construction.

## Formal model

Let `T` be a rooted continuation tree whose nodes are quotient-visible lawful continuation classes. For each node `C`, let

`Ch(C) = {C'_1,...,C'_k}`

be the finite nonempty set of lawful children under a prospectively fixed continuation/refinement protocol.

Book I gives

`k(C) = delta(C)+1`.

ELCAK adds the new physical postulate

`K_S(C,C') = 1/k(C)` if `C' in Ch(C)`, and `0` otherwise.

The child partition and the continuation protocol are model inputs fixed before outcome observation; they are not inferred from frequencies.

## M1 — Local normalization

PASS.

For each `C`,

`sum_{C' in Ch(C)} K_S(C,C') = k(C) * 1/k(C) = 1`.

## M2 — Finite-path normalization

PASS.

For a finite path

`h_L = (C_0,C_1,...,C_L)`

with `C_{i+1} in Ch(C_i)`, define

`mu_L(h_L) = product_{i=0}^{L-1} 1/k(C_i)`.

Induction on `L` shows the weights of all depth-`L` continuations from a fixed root sum to one. The induction step follows because the child weights at each terminal node sum to one.

## M3 — Projective consistency

PASS FOR FINITE CYLINDERS.

Marginalizing one stage gives

`sum_{C_{L+1} in Ch(C_L)} mu_{L+1}(h_L,C_{L+1}) = mu_L(h_L)`.

Thus the finite-horizon cylinder family is projectively consistent.

For an infinite locally finite continuation tree, promotion to a sigma-additive measure on infinite path space requires the ordinary measure-theoretic extension machinery for consistent cylinder probabilities. That is standard mathematics external to the NFC source, not a new physical premise. This audit does not claim that theorem as an NFC result.

`INFINITE_PATH_MEASURE_STATUS = MATHEMATICALLY_AVAILABLE_WITH_STANDARD_EXTENSION_THEOREM__NOT_NFC_SOURCE_CONTENT`

## M4 — Quotient / representation invariance

PASS WITH A FIXED CONTINUATION RELATION.

If a representation change or quotient automorphism preserves the declared parent-child relation, it preserves `k(C)` and therefore preserves ELCAK probabilities.

If a change alters the child partition itself, it is not merely a relabeling of the same ELCAK model; it changes the model input. This is why the continuation/refinement protocol must be frozen prospectively.

## M5 — No hidden inverse selection

PASS.

ELCAK acts on quotient-visible child classes. It never selects a hidden representative from inside a singular observational-equivalence class. Therefore it does not construct a forbidden inverse to the quotient map.

## M6 — Unique-continuation reduction

PASS.

If `delta(C)=0`, then `k(C)=1` and ELCAK assigns probability one to the sole lawful child. The model therefore reduces correctly on unique-continuation nodes.

## M7 — Markov/locality status

CONDITIONAL / EXPLICIT.

The transition kernel is local in the declared state `C`: probabilities depend on the current node's lawful child set and not separately on earlier history.

This is not automatically a physical Markov theorem of frozen NFC. The model must therefore declare one of two equivalent bookkeeping conventions:

1. `C` is a history-augmented canonical continuation state containing all prior quotient-visible information relevant to lawful continuation; or
2. a separate state-sufficiency/Markov hypothesis is added.

The first convention minimizes extra physics but can enlarge the state space. No information relevant to lawful child construction may be silently discarded.

`STATE_SUFFICIENCY_BURDEN = EXPLICIT`

## M8 — Path surprisal versus defect ledger

PASS AS A NEW MODEL QUANTITY; NOT IDENTICAL TO FROZEN DEFECT.

ELCAK gives path surprisal

`I_S(h_L) = -log mu_L(h_L) = sum_i log k(C_i) = sum_i log(delta(C_i)+1)`.

Frozen Book-I cumulative defect is

`Delta(h_L) = sum_i delta(C_i)`.

These are generally different quantities.

For unary/binary branching, `delta in {0,1}` and with logarithm base 2,

`I_S(h_L) = Delta(h_L)`

along the branching-count component. For higher branching they diverge.

Therefore ELCAK does not derive probability directly from the existing additive defect ledger. It constructs a new information quantity from canonical child count.

`NO_LEDGER_PROBABILITY_EQUIVALENCE_CLAIM = YES`

## M9 — Infinite-path status

PASS AT CONDITIONAL MATHEMATICAL SCOPE.

Finite branching plus the consistent local kernels supplies a coherent cylinder family. An infinite-history probability measure can be obtained under the standard measurable-path construction, provided the continuation protocol yields the required countable/cylinder structure.

This is sufficient for model coherence but adds no source authority.

## M10 — Observation-linked compatibility

PASS AT MODEL SCOPE.

Prior accepted audits established that NFC can contain quotient-visible observation/probe-induced transitions while stopping short of actualization. ELCAK can be attached after such a transition by applying the kernel to the prospectively declared lawful post-observation continuation set.

No branch theorem is thereby reinterpreted as an actualization theorem.

## F1 — finite-tree normalization attack

FAILED TO BREAK ELCAK.

Arbitrary finite rooted trees with nonempty finite child sets normalize by local summation. Unequal branching factors do not create the earlier `2^{-Delta}` inconsistency because ELCAK uses the exact inverse local child count.

## F2 — representation attack

FAILED UNDER PARTITION-PRESERVING REPRESENTATIONS.

Because the rule depends only on child-set cardinality, quotient-preserving relabelings do not change it.

A representation that changes the lawful child relation changes the model rather than representing the same model.

## F3 — unequal quotient-visible sibling structure

NO CONTRADICTION; AUTHORITY REMAINS NEW PHYSICS.

ELCAK deliberately assigns equal probability even when siblings differ in quotient-visible properties. Frozen NFC does not forbid this, but neither does it require it. This remains the central falsifiable physical indifference premise.

## F4 — partition / stage tuning attack

SURVIVES ONLY WITH A STRONG PREREGISTRATION FIREWALL.

The probability rule is sensitive to how lawful siblings are partitioned. Book I permits nested refinement stages, and a different declared test/refinement protocol can alter the child structure.

Therefore any empirical ELCAK instantiation must freeze before outcomes are observed:

- the admissible test family or branch-local probe discipline;
- the stage/refinement map;
- the parent state definition;
- the child-equivalence rule;
- the observation window;
- the stopping/horizon rule if finite data are used.

Post-hoc splitting or merging of children to improve fit is prohibited.

`PARTITION_PREREGISTRATION = MANDATORY`

This is an auxiliary-model burden, not a mathematical contradiction.

## F5 — finite-stabilization attack

DOES NOT BREAK MODEL; CAN MAKE IT TRIVIAL.

If the continuation process enters a region where every node has one child, ELCAK becomes deterministic with probability one thereafter. Thus finite stabilization can produce long or terminal trivial sectors.

A useful empirical target requires repeated access to nontrivial nodes with `delta>0`.

`NONTRIVIAL_TEST_REQUIRES_BRANCHING_NODES = YES`

## F6 — repeated-trial / independence attack

IMPORTANT LIMITATION.

ELCAK defines conditional transition probabilities along one declared continuation process. It does **not** by itself imply that repeated physical trials are independent or identically distributed.

Frequency testing therefore requires either:

- a protocol that physically resets to the same certified parent class with the same child partition, plus a separately justified exchangeability/independence approximation; or
- a likelihood/test procedure that uses the full conditional sequence without assuming i.i.d. trials.

`IID_NOT_SOURCE_FORCED = YES`

This prevents naive frequency claims.

## F7 — deterministic control

PASS AS REQUIRED CONTROL DESIGN.

The deterministic comparator must share the same:

- parent/child continuation tree;
- state definition;
- observation map;
- branch target regime;
- initial/boundary policy;
- intervention/reset protocol;
- data exclusion/preregistration policy.

Only the actualization law may differ.

A deterministic control may be partial on ties; such a tie is recorded as a nonprediction/failure, not resolved post hoc.

## Ten-branch prospective testbed survey

### BIO — `T2__PROSPECTIVE_MODEL_LEVEL_TESTBED_POSSIBLE`

Strengths: finite physical configurations, explicit admissible probe discipline, replication/heredity structure, generation-like continuation, and conditional evolutionary dynamics.

Blocker: no existing canonical mapping identifies repeated physical replication outcomes with a prospectively frozen ELCAK sibling partition, and no reset/independence protocol is supplied.

### CRYST — `T1__FORMAL_TESTBED_ONLY`

Strengths: explicit physical-style probe/response and quotient-visible diffraction structure.

Blocker: the branch primarily performs structural inference/classification; a repeated actualization fork with prospectively fixed lawful continuation children is not currently identified.

### GR — `T1__FORMAL_TESTBED_ONLY`

The branch has lawful dynamics/realization structure but no practical repeated sibling-choice protocol or empirical ELCAK mapping at canonical scope.

### LING — `T1__FORMAL_TESTBED_ONLY`

It has contrast/compositional transitions but does not presently supply a physical-history actualization protocol; using linguistic frequencies would introduce additional semantic/social modeling far outside this gate.

### NS — `T1__FORMAL_TESTBED_ONLY`

The branch is frontier-focused on continuation/regularity. It does not presently define repeated physical actualization forks with frozen child partitions.

### RH — `T0__NO_PLAUSIBLE_TESTBED`

The RH branch is a mathematical descendant program, not a physical repeated-history actualization regime.

### SCC — `T1__FORMAL_TESTBED_ONLY`

SCC is structurally rich but explicitly lacks direct phenomenological/physical upgrade. Its distinct-history/canonical-carrier machinery is useful for counterexamples, not an empirical ELCAK target.

### SM — `T1__FORMAL_TESTBED_ONLY`

The super-branch is structural/harmonization-focused and inherits YM/GR scope. No prospective repeated actualization protocol is present.

### SPEC — `T2__PROSPECTIVE_MODEL_LEVEL_TESTBED_POSSIBLE`

This is the strongest observation-linked candidate because it already has admissible probe families, response classes, before/after probe episodes, and certified transition ledgers.

Blocker: the branch explicitly stops short of identifying a probe episode with an ordinary external physical measurement event, and it does not currently define multiple lawful post-probe continuation children plus repeated physical trials.

### YM — `T1__FORMAL_TESTBED_ONLY`

The branch supplies rich spectral/coercive structure but no direct repeated sibling-actualization protocol.

## Survey verdict

`T3_EMPIRICAL_TESTBED_IDENTIFIED = NO`

`STRONGEST_T2_CANDIDATES = SPEC; BIO`

SPEC is the cleaner observation-linked structural testbed; BIO is the cleaner repeated-generation structural testbed. Neither is yet an empirical test.

## Exact model failure modes

ELCAK must be rejected or restricted if any target-specific instantiation shows:

1. lawful child sets are not prospectively well-defined;
2. child partitions depend on outcome data or post-hoc tuning;
3. the same certified parent state admits incompatible child partitions under equally authoritative protocols with no selection rule between them;
4. a claimed representation change alters probabilities without changing physical content;
5. required state information is omitted so that the kernel is not conditionally well-defined;
6. physical data, under a valid matched protocol, exclude equal-child weighting;
7. branch transfer requires hidden labels or violates a source/Book-VII scope firewall.

## Scientific status

`MATHEMATICAL_COHERENCE = PASS`

`SOURCE_DERIVATION = NO`

`PHYSICAL_AUTHORITY = NONE`

`EMPIRICAL_SUPPORT = NONE`

`CURRENT_EMPIRICAL_TESTABILITY = NO`

`CONDITIONAL_MODEL_STATUS = QUALIFIED_FOR_TARGET_FEASIBILITY_WORK`

## Routing

`NFC_CANON_MUTATION = NO`

`FCP_READJUDICATION = NO`

`PGH_READJUDICATION = NO`

`ELCAK_ADOPTION = NOT_AUTHORIZED`

`NEXT_OPERATION = NFC_ELCAK_SPEC_BIO_TARGET_QUALIFICATION_GATE_V0_1`

A subsequent gate may compare SPEC and BIO as **prospective target-construction environments** and determine whether either can be upgraded from T2 to T3 with a genuinely physical, prospectively frozen protocol. It must be allowed to conclude that neither can.