# NFC Dynamics-vs-Actualization Identifiability Gate v0.1

STATUS = EXECUTED__OUTCOME_C__NO_SEPARATELY_IDENTIFIABLE_ACTUALIZATION_LAYER_AT_AUDITED_SCOPE

PREREGISTRATION_COMMIT = `3f1bf17541febfdd73f0047b8457e5b4e1a3c187`
BASE_ACCEPTANCE_COMMIT = `a07a55c3d4146859d0b97933ee6188c39cf81416`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`
FROZEN_NFC_TREE = `00ef55ff36d5e9663ca1ef2c9566e2bc1396f973`

## Primary outcome

`PRIMARY_OUTCOME = C__NO_SEPARATELY_IDENTIFIABLE_ACTUALIZATION_LAYER_AT_AUDITED_SCOPE`

Secondary qualification:

`FROZEN_NFC_COMPLETE_PHYSICAL_TRANSITION_KERNEL = NOT_SUPPLIED_UNIVERSALLY`

`DYNAMICAL_DERIVATION_FRONTIER_REMAINS = YES`

This result does not claim that frozen NFC already contains complete physical dynamics. It establishes a narrower identifiability result: once a complete, prospectively declared physical transition kernel is fixed on the quotient-visible outcome partition, an additional layer that merely samples according to that same kernel contributes no separately observable law.

## Formal identifiability result

Let:

- `D` be the complete declared dynamical specification;
- `K_D(o'|o,I)` be its transition kernel under intervention/preparation `I`;
- `A` be a proposed actualization mechanism;
- `O` be the quotient-visible outcome map.

If `A` only says that one realized outcome is sampled according to `K_D`, then

`P(O_{n+1}=o' | D,A,I) = K_D(o'|o,I) = P(O_{n+1}=o' | D,I)`.

Therefore for every finite observable sequence,

`P(O_1,...,O_N | D,A,I) = P(O_1,...,O_N | D,I)`

provided A contributes no additional state variable, correlation rule, memory law, intervention dependence, or change to the transition kernel.

At that scope, `A` is formally distinguishable as a label or ontology but empirically redundant.

## What would make an actualization layer separately identifiable?

At least one of the following must occur prospectively:

1. `A` changes the one-step outcome probabilities relative to `K_D`;
2. `A` changes multi-step correlations while preserving one-step marginals;
3. `A` changes intervention response;
4. `A` introduces a separately observable state variable or conserved/violated quantity;
5. `A` imposes a history-selection constraint excluding dynamical paths that `D` otherwise gives nonzero weight;
6. `A` predicts branch/scope dependence not already encoded in `D`.

Any such proposal becomes a real physical completion candidate because it can, in principle, disagree with dynamics-only predictions.

## Why merely renaming probabilities fails

A transition law and an actualization law are not experimentally distinct merely because one is called 'dynamics' and the other 'actualization'. If both generate the same normalized kernel on the same outcome algebra under the same interventions, there is no statistical experiment that can identify which label generated the frequencies.

Likewise, saying 'the dynamics gives possibilities, actualization chooses one' adds no empirical content when the choice frequencies and correlations are exactly those already specified by the dynamics.

## Frozen-source review

### Book I

Book I supplies admissible tests, quotient-visible alternatives, refinement, continuation multiplicity, and defect bookkeeping. It explicitly does not begin from a probability space or physical interpretation. It therefore supplies the sample/outcome architecture but not a second probability law.

Its anti-inversion rule also blocks hidden token identity from becoming an empirical selector behind an observational equivalence class.

### Book II

Book II supplies deterministic witness updates and local boundary determinacy at observable-class scope. Its own caveat excludes promotion to fine-grained microscopic determinism. Nothing in the audited Book-II structure adds a distinct outcome-selection probability once a physical transition law is separately fixed.

### Book III

Book III is a persistence, transfer, comparison, and coercive-balance layer. Its stated role is to control how certified observables persist and transfer. No independently observable actualization variable or probability kernel is introduced.

### Books IV-VII

The universal source, branch realization, continuum interface, and governance layers can certify and scope a future physical law but do not independently create empirical probabilities. Book V requires endpoint-visible structure and prohibits hidden supplementation; Book VII forbids promotion of source-side structure into stronger physical force without a transfer theorem.

Thus governance can house a distinct actualization theory only if that theory adds certified, testable content.

## Ten-branch audit

The complete frozen branch set was checked at the role level established by prior Observatory audits:

- `BIO`: contains conditional population selection dynamics. Its one-step population update is already the dynamical law; no separate universal actualizer is supplied.
- `CRYST`: observable diffraction/symmetry structure; no separate physical outcome-selection law identified.
- `GR`: branch-local geometric dynamics/closure under declared hypotheses; no second selection layer identified.
- `LING`: contrast/compositional/context-response structure; no physical actualization layer.
- `NS`: continuation/obstruction dynamics and closure frontiers; no second outcome-selection layer.
- `RH`: mathematical admissibility/selection-exclusion program, not a physical stochastic actualizer.
- `SCC`: structural carrier/counterfactual architecture; explicitly structural, with distinct histories still possible; no physical actualizer.
- `SM`: harmonized branch structure and imported dynamics; no separate actualization law.
- `SPEC`: probe-response and transition ledgers; no transition-amplitude/probability law in frozen SPEC and no second actualization layer.
- `YM`: spectral/coercive branch dynamics/structure; no separate actualization layer.

`TEN_BRANCH_SEPARATE_ACTUALIZER_IDENTIFIED = NO`

## BIO control case

BIO demonstrates why the distinction matters. Under its conditional evolutionary hypotheses, finite-stage population composition obeys a normalized differential-replication update. That update already determines the next population distribution. Appending a statement that an 'actualizer' samples according to exactly that distribution changes no observable population prediction.

This does not mean BIO solves fundamental actualization. It means BIO supplies an explicit example where the empirical probability-bearing content belongs to the branch dynamics itself.

## SPEC / spectroscopy control case

The accepted ELCAK spectroscopy program showed that naive equal-child actualization made a sharp prediction and was contradicted by established unequal branching fractions. That was a real, separately identifiable completion because it changed the probability kernel.

The successor channel-weighted design audit found no NFC-native weight with authority. If externally supplied transition dynamics already predicts the measured channel weights, then defining an 'actualization kernel' equal to those transition weights adds no new empirical content.

This is the key negative-control result.

## Strongest pro-actualization reversal

A genuine reversal is easy to state but not realized in the frozen corpus:

- Hold the complete dynamics `D` fixed.
- Add `A` that modifies correlations, conditional frequencies, intervention response, or allowable histories while leaving `D` unchanged.
- Exhibit `P(O|D,A,I) != P(O|D,I)`.

Such an A would be separately identifiable.

No frozen-source or branch object satisfying this requirement was identified.

## Strongest anti-actualization reversal

If `D` already supplies the complete kernel over the prospectively frozen quotient-visible alternatives, and `A` merely declares that one outcome is realized according to that same kernel, then A is observationally redundant by construction.

This argument is representation-independent provided the same outcome algebra and intervention protocol are used.

## Interpretation guardrail

This audit does not settle ontology.

The statements

- 'one outcome occurs',
- 'why this outcome rather than another?',
- 'is probability ontic or epistemic?',
- 'is there a unique realized history?'

may remain philosophically or interpretively substantive. The present result is only that no *additional empirically identifiable probability law* follows from naming a second layer when all observable statistics are already fixed by the dynamics.

## Scientific consequence

The actualization frontier should now be split into two different questions:

1. **Dynamical probability problem:** derive or identify the physical transition kernel on NFC's quotient-visible branch outcomes.
2. **Residual ontology/selection problem:** ask whether anything remains beyond that kernel, but require a new observable consequence before treating it as a scientific law rather than an interpretation.

`ACTUALIZATION_AS_INDEPENDENT_PROBABILITY_LAW = NOT_SUPPORTED_AT_AUDITED_SCOPE`

`DYNAMICAL_TRANSITION_KERNEL_AS_PRIMARY_EMPIRICAL_OBJECT = YES`

`RESIDUAL_INTERPRETIVE_OR_ONTOLOGICAL_QUESTION = OPEN`

## Routing

`NFC_FROZEN_CANON_MUTATION = NO`
`FCP_READJUDICATION = NO`
`PGH_READJUDICATION = NO`

`NEXT_OPERATION = NFC_TRANSITION_KERNEL_SOURCE_AND_BRANCH_DERIVABILITY_GATE_V0_1`

The next operation should ask whether frozen NFC plus its branch structures can derive any physically calibrated transition kernel at all, or whether transition probabilities necessarily enter through additional branch-specific physics. This should be conducted before any further universal actualization model is proposed.
