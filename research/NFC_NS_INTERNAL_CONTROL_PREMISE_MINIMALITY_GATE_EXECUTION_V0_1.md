# NFC NS Internal Control Premise Minimality Gate — Execution v0.1

STATUS: EXECUTED__AWAITING_ACCEPTANCE

PREREGISTRATION_COMMIT: `de1364024b201fd6c3674e4db4dc9048ad7d36a2`
BASE_ACCEPTANCE: `668c8ae664e95cf5bd1c498589ccc3c09d4b695a`
SOURCE_PROJECT_MUTATION: FORBIDDEN

## 1. Bound question

The frozen question is:

> Given that frozen NFC does not force a tail-uniform internal event envelope, what is the weakest explicit new premise sufficient for the current ledger-window intertwining program to obtain a finite value/oscillation bound on `E_n`, while clearly distinguishing mere boundedness from the stronger relative control needed for eventual contraction?

This execution does not ask whether any candidate premise is already a theorem of frozen NFC. The base acceptance established that the relevant tail-uniform internal envelope is not source-forced. Every surviving candidate below is therefore treated only as prospective new structural content.

## 2. Controlling inherited fact

The base acceptance establishes:

```text
ONLY_PER_STEP_FINITY_FORCED = YES
TAIL_UNIFORM_EVENT_ALPHABET_FORCED = NO
TAIL_UNIFORM_EVENT_MULTIPLICITY_FORCED = NO
CURRENT_APPLICATION_NEEDS_VALUE_CONTROL_NOT_FULL_EVENT_RECONSTRUCTION = YES
```

Accordingly, per-step finiteness cannot itself be promoted into a finite uniform late-tail ceiling for `E_n`.

## 3. Target decomposition

The preregistered phrase `finite value/oscillation bound` contains two logically distinct targets.

### T1 — absolute value control

A prospectively fixed finite constant `M_E` exists on the declared late-tail regime such that

```text
0 <= E_n <= M_E < infinity.
```

Because `E_n` is nonnegative, T1 immediately yields finite within-window oscillation:

```text
osc_k(E) = max_{n in W_k} E_n - min_{n in W_k} E_n <= M_E.
```

### T2 — oscillation-only control

A prospectively controlled finite remainder exists such that

```text
osc_k(E) <= R_k^E < infinity.
```

T2 does not imply T1. For any sequence satisfying a fixed oscillation bound, the shifted sequence

```text
E'_n = E_n + C
```

has exactly the same oscillation for arbitrary finite `C`. Hence oscillation control alone does not bound the absolute level of `E_n`.

### T3 — relative / absorbable control

Event control is strong enough to compare the harmful internal remainder to an independently defined same-state loss/control quantity with a prospectively fixed coefficient. T3 is materially stronger than either T1 or T2. Neither finite boundedness nor finite oscillation alone implies absorbability or eventual contraction.

The base acceptance identifies T1, not merely T2, as the current application need at this gate. T3 is explicitly outside the stop rule unless separately justified.

## 4. Candidate-by-candidate adjudication

### C1 — Absolute internal ceiling

```text
0 <= E_n <= M_E < infinity
```

with `M_E` prospectively fixed or independently derived.

**Result: sufficient for T1 and therefore T2; insufficient for T3.**

C1 states exactly the missing one-sided late-tail value bound and no internal event reconstruction. Given nonnegativity, no lower-bound premise beyond zero is required.

It does not supply any comparison of `M_E` or `E_n` to a same-state loss term, window average, renewal decrement, or other contraction-relevant quantity. Therefore C1 may not be consumed as relative smallness.

### C2 — Finite event envelope

Finite event alphabet plus uniform multiplicity bound, yielding a derived `M_E`.

**Result: sufficient for T1/T2 but strictly stronger than required for this gate.**

C2 carries structural content about event classes and multiplicities whose only required downstream consequence here is the derived finite ceiling. Because C1 can be stated and prospectively tested directly without reconstructing the stronger envelope, C2 is not minimal for value control.

### C3 — Internal-to-boundary domination

```text
E_n <= C_E B_n.
```

**Result: sufficient for T1 only when an independent finite boundary ceiling is available, but stronger/more structured than C1.**

C3 imposes a cross-channel domination relation and a prospectively justified coefficient. Even where the boundary channel is finite under the declared scope, this relation contains more information than the bare value ceiling needed at this gate.

C3 also does not automatically provide T3: domination by `B_n` becomes absorbable only if `B_n` is itself related with the required force to the relevant same-state net-loss quantity.

### C4 — Same-state relative domination

```text
E_n <= c_Y Y_n.
```

for an independently defined positive same-state quantity with the required relative control.

**Result: potentially sufficient for T3, therefore stronger than the present T1 target.**

C4 is the kind of premise that could support relative absorption, but precisely for that reason it is not the weakest premise for finite value control. It must also be protected against choosing `c_Y` post hoc to force contraction.

### C5 — Direct window-oscillation premise

```text
osc_k(E) <= R_k^E
```

with a prospectively declared finite/computable remainder envelope.

**Result: strictly weaker than C1 for T2, but insufficient for T1.**

C5 directly controls the quantity needed by an oscillation-only argument and avoids any pointwise ceiling. However, the additive-shift counterexample above proves that it cannot establish a finite absolute value bound on `E_n` without an additional anchor-value or level premise.

Therefore C5 would be minimal if the target were prospectively narrowed to T2 alone. It is not sufficient for the preregistered current-application value-control target inherited from the base acceptance.

C5 also does not imply T3: a finite oscillation remainder may remain arbitrarily large relative to the net loss that must absorb it.

### C6 — No additional premise

**Result: rejected.**

The base source-forcing acceptance already established that frozen NFC supplies only per-step finiteness and permits increasing finite interior complexity. Therefore no tail-uniform value bound or uniform oscillation bound follows without new content.

## 5. Minimality ordering

For the target actually controlling this gate:

```text
T1 = finite absolute value control on E_n
```

the candidate ordering is:

```text
C1  = minimal sufficient candidate
C2  = sufficient but stronger (event reconstruction/envelope structure)
C3  = sufficient only with boundary ceiling and stronger cross-channel relation
C4  = stronger relative same-state premise aimed at T3
C5  = weaker, but solves only T2 rather than T1
C6  = insufficient
```

No claim is made that C1 is the unique logically imaginable formulation. Rather, among the preregistered candidate classes and given `E_n >= 0`, a prospectively fixed finite upper ceiling is the minimal direct new premise that supplies the required value control without adding event reconstruction or relative-domination structure.

## 6. Anti-circularity / prospective checks

A lawful C1 premise must satisfy all of the following:

1. `M_E` is fixed prospectively or derived independently of endpoint success.
2. `M_E` is not selected by solving backward from a desired contraction coefficient.
3. no historical IDC statement is imported as proof of C1.
4. no withdrawn generic obstruction ceiling is renamed as C1.
5. C1 is scoped only to the declared late-tail regime for which it is prospectively asserted/tested.
6. C1 is not promoted to a finite event alphabet, multiplicity theorem, or internal-state reconstruction.
7. C1 is not promoted to relative absorbability.

## 7. Controlling outcome

```text
A__ABSOLUTE_INTERNAL_CEILING_IS_MINIMAL_FOR_VALUE_CONTROL__NOT_FOR_ABSORPTION
```

### Subsidiary result

```text
IF_TARGET_IS_NARROWED_TO_OSCILLATION_ONLY:
B__DIRECT_OSCILLATION_PREMISE_IS_STRICTLY_WEAKER_AND_MINIMAL
```

This subsidiary statement does not override A because the base acceptance explicitly identifies value control as the current gate's application requirement.

## 8. Routing consequence

The selected premise remains a **research hypothesis**, not frozen NFC truth:

```text
P_NS_INTERNAL_VALUE_CEILING:
There exists a prospectively fixed finite M_E such that
0 <= E_n <= M_E
on the declared late-tail regime.
```

Its valid immediate consequence is finite value and finite oscillation control only.

It does **not** discharge relative remainder absorption, same-state comparison, common-state completion, or eventual contraction. Any attempt to obtain those consequences requires a separately justified relative premise or a separately governed absorption gate.

## 9. Final execution state

```text
PREREGISTRATION_SATISFIED = YES
CONTROLLING_OUTCOME = A__ABSOLUTE_INTERNAL_CEILING_IS_MINIMAL_FOR_VALUE_CONTROL__NOT_FOR_ABSORPTION
C1_SELECTED_AS_RESEARCH_HYPOTHESIS = YES
C1_PROMOTED_TO_FROZEN_NFC_THEOREM = NO
RELATIVE_ABSORPTION_DERIVED = NO
CONTRACTION_DERIVED = NO
SOURCE_PROJECT_MUTATED = NO
EXTERNAL_SOURCE_SEARCH = NO
```

Hard stop for independent acceptance.