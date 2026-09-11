# NFC Equal-Lawful-Child Kernel Formalization and Falsification Gate v0.1

STATUS = PREREGISTERED

BASE_ACCEPTANCE_COMMIT = `b79577a4ad2efb055bdb06ea9a9c4aebc7af6e67`

FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Purpose

Formalize the Equal-Lawful-Child Actualization Kernel (`ELCAK`) as a conditional post-freeze model, prove or refute its internal mathematical properties, enumerate exact failure conditions, and identify candidate NFC branch regimes that could support a prospective test.

This operation does **not** adopt ELCAK into NFC and does not treat any branch as evidence for it.

## Conditional postulate

For each post-observation continuation class `C`, let `Ch(C)` be the finite nonempty set of lawful child classes at the next declared continuation stage. Book I gives

`|Ch(C)| = delta(C)+1`.

ELCAK adds the physical postulate:

`P(C'|C) = 1/|Ch(C)|` for every `C' in Ch(C)`.

No probability is assigned to unlawful children.

## Required mathematical checks

M1. local normalization.

M2. finite-path/cylinder normalization.

M3. projective consistency under marginalization.

M4. quotient/representation invariance.

M5. no hidden inverse selection at singular interfaces.

M6. unique-continuation reduction: if `delta(C)=0`, probability one goes to the sole child.

M7. Markov/locality status: determine exactly what dependence is assumed.

M8. path surprisal and relation to the existing defect ledger.

M9. existence/uniqueness of an infinite-path measure when the declared continuation tree is infinite but locally finite; if additional measure-theoretic assumptions are required, state them rather than silently importing them.

M10. compatibility with observation-induced transitions and branch scope.

## Required falsification attempts

F1. Find a finite lawful tree on which ELCAK fails normalization or projective consistency.

F2. Find a quotient automorphism/representation change under which ELCAK changes.

F3. Show whether equal weighting conflicts with any frozen theorem when siblings have unequal quotient-visible properties.

F4. Test whether the child partition can be manipulated by refinement choice, test-family choice, or stage choice; identify the exact preregistration needed to block post-hoc partition tuning.

F5. Test whether finite stabilization makes ELCAK empirically vacuous or trivial on relevant regimes.

F6. Test whether repeated trials can be defined without assuming independence that NFC does not provide.

F7. Compare ELCAK with the deterministic control under exactly matched continuation domains; declare any asymmetry.

## Branch testbed survey

All ten frozen branches must be screened only for prospective suitability:

- BIO
- CRYST
- GR
- LING
- NS
- RH
- SCC
- SM
- SPEC
- YM

A branch may be rated:

`T0__NO_PLAUSIBLE_TESTBED`

`T1__FORMAL_TESTBED_ONLY`

`T2__PROSPECTIVE_MODEL_LEVEL_TESTBED_POSSIBLE`

`T3__EMPIRICAL_TESTBED_POSSIBLE_WITH_NEW_PROTOCOL`

No branch may be rated T3 merely because it contains observations, transitions, frequencies, or probabilities. T3 requires a plausible route to prospectively fixed lawful sibling classes plus repeated/interventional physical data.

## Outcomes

A. `ELCAK_MATHEMATICALLY_COHERENT__EMPIRICAL_TARGET_IDENTIFIED`

B. `ELCAK_MATHEMATICALLY_COHERENT__NO_CURRENT_EMPIRICAL_TARGET`

C. `ELCAK_REQUIRES_MATHEMATICAL_REPAIR`

D. `ELCAK_CONTRADICTS_FROZEN_NFC`

E. `UNDERDETERMINED`

F. `REPAIR_REQUIRED`

## Guardrails

- Frozen NFC remains read-only.
- Equal weighting is an explicit new postulate, not a recovered theorem.
- Branch-local frequency or selection laws are not evidence for ELCAK.
- Independence/i.i.d. assumptions may not be silently added.
- Any empirical test must freeze the child partition before observing outcomes.
- The deterministic control remains mandatory under matched auxiliaries.

## Routing

If A: open a separately preregistered target-specific model/experiment design gate.

If B: retain ELCAK as a mathematically coherent conditional model and stop before empirical claims.

If C or D: repair or reject before further development.