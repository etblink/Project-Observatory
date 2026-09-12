# OBS-U002 — NFC LS-2 Source-Forcing Audit Preregistration V0.1

Status: `PREREGISTERED__NOT_EXECUTED`

Operation: `OBS_U002_NFC_LS2_SOURCE_FORCING_AUDIT_PREREGISTRATION_V0_1`

Selected uncertainty: `OBS-U002`

Target class: `FROZEN_SOURCE_FINITE_INTERFACE_SUFFICIENCY`

Short name: `NFC_LS2_SOURCE_FORCING`

## 0. Governing boundary

This commit preregisters one bounded adversarial audit under the frozen Project Observatory Charter. It does **not** execute the audit and does not modify, reinterpret, repair, or extend NFC canon.

The audit is read-only with respect to `etblink/Nested-Fibrational-Cosmology`. An Observatory result is noncanonical unless separately taken up under NFC governance.

This preregistration is prospectively bound to the selected-target commit:

```text
TARGET_SELECTION_COMMIT =
5258c93ff369f8487ac4ffdd653631d196f065d2

TARGET_SELECTION_TREE =
1c667d32b46ca64481eae9fd8fc4ac06bafb1b01

SNAPSHOT_V0_2_FREEZE_COMMIT =
5ceca12bcba7402addd98d52a9797172aec6c870

SNAPSHOT_V0_2_CONTENT_COMMIT =
2a7beb27f261c960a1a667830c2e4898e9966f7f
```

No substantive source-forcing derivation, countermodel construction, or outcome adjudication may be recorded in this preregistration commit.

## 1. Exact question under test

The audit asks:

> Does the frozen canonical NFC spine, using only source-admissible premises actually established at the frozen boundary, force an LS-2-equivalent finite-interface sufficiency theorem strong enough to make the relevant downstream observable/state determination factor through a uniformly bounded collar/interface; or can a lawful model (or lawful family of models) satisfy the admitted locality, quotient, finite-carrier/refinement, stabilization, persistence/transfer, and other source-established premises while that finite-interface sufficiency fails?

The target is a **source-forcing** question. It is not a request to decide whether LS-2 is useful, plausible, repairable, or desirable.

## 2. Frozen source boundary

The evidentiary source boundary is the frozen NFC canon:

```text
REPOSITORY = etblink/Nested-Fibrational-Cosmology
CANONICAL_REF = archive/nfc-canonical-ed3047c2
CANONICAL_COMMIT = ed3047c2cbc0abc34d2549dd27754e4d3d05af78
CANONICAL_ROOT_TREE = 00ef55ff36d5e9663ca1ef2c9566e2bc1396f973
```

The exact theorem-bearing spine corpus and blob identities are frozen in:

`audits/OBS_U002_NFC_LS2_FROZEN_SOURCE_MANIFEST_V0_1.md`

Only those seven frozen spine `.tex` files may carry substantive premise/proof force for outcomes A–D. Canon/governance metadata may resolve status and authority but may not add theorem premises.

The later noncanonical file `research/NFC_FOUNDATIONAL_REDUCTION_CONTINUITY.md` is **background only**. It motivated the target and may be used to identify search vocabulary, but it is forbidden as proof of forcing or nonforcing.

## 3. Target predicate: LS-2-equivalent finite-interface sufficiency

For this audit, a result counts as `LS2_EQUIVALENT` only if it establishes, over the claimed source scope, a nontrivial bounded-interface determination property of the following operative form.

For each admissible target region/system `U` and relevant downstream observable/state map `q_U`, there is an interface/collar statistic `c_U` supported on a collar of bounded thickness and a map `Phi_U` such that

```text
q_U = Phi_U o c_U.
```

Equivalently:

```text
c_U(x) = c_U(y)  ==>  q_U(x) = q_U(y).
```

For a global or regime-uniform LS-2 claim, the collar bound must be uniform over the source-declared scope; it may not grow without bound with the interior size in a way that lets the collar swallow the whole system.

The following do **not** by themselves satisfy the target predicate:

- finite carrier size;
- finite valence;
- finite collar alphabet;
- bounded propagation speed;
- local detectability;
- stabilization of a refinement chain on one fixed finite carrier;
- existence of finitely many quotient classes;
- a packet-specific computational certificate;
- a boundary-capacity counting inequality that already assumes factorization through the interface.

A theorem can count as equivalent even if it does not use the literal name `LS-2`, but equivalence must be demonstrated at the level of the bounded-interface factorization above, not by terminological resemblance.

## 4. Source-admissible premise rule

During execution, every premise used in a positive derivation or tested by a countermodel must be entered into a premise ledger with source file, label/section, status tag, and dependency role.

Admissibility rules are frozen as follows:

1. `[D]` definitions and standing rules may define the audit universe and typed objects, but a definition does not acquire extra empirical or physical force by being definitional.
2. `[U]` results may be used at their exact proved scope.
3. `[C]` results may be used only with their complete declared hypothesis set. A hypothesis appearing inside a conditional theorem is **not** thereby promoted to a globally established premise.
4. `[B]` bridge/interface statements may be used only at their declared bridge scope and may not self-promote to `[U]` force.
5. `[R]` remarks are non-load-bearing and cannot close a proof gap.
6. `[O]` obligations are not established premises.
7. Historical, superseded, front-matter, or status-summary prose cannot override the applicable source-authority hierarchy.
8. No premise may be imported from FCP, PGH, ordinary GR/QFT/QM, external literature, later NFC diagnostics, or branch-specific assumptions unless the frozen spine itself explicitly imports and discharges that premise at the required scope.
9. No target-equivalent assumption may be hidden inside a renamed locality, collar, transfer, screening, persistence, or stabilization premise. Circular use of finite-interface sufficiency forces a non-A outcome.

## 5. Frozen operational distinctions

The execution must keep the following propositions separate unless the frozen source itself proves an implication between them:

```text
P1 = bounded/local propagation or update dependence
P2 = local detectability by an admitted test family
P3 = finite stabilization of refinement/quotient structure
P4 = finite interface/collar alphabet
P5 = finite-interface sufficiency / bounded-collar factorization
```

The audit may establish implications among P1–P5 only by source-traceable proof. In particular, P1–P4 are not preregistered as implying P5.

## 6. Positive forcing criterion

Outcome A requires a complete, noncircular derivation from the admitted frozen source premises to the target predicate.

A valid positive case must provide:

- exact source labels and dependency chain;
- all conditional hypotheses and their discharge status;
- exact target scope (regions, regimes, observables/states);
- the collar/interface object and boundedness condition;
- a demonstrated factorization or logically equivalent sufficiency theorem;
- confirmation that no step imports post-freeze diagnostic reasoning or an unproved target-equivalent hypothesis.

Mere absence of a countermodel does not establish forcing.

## 7. Negative forcing / countermodel criterion

Outcome C requires more than failure to find a proof. It requires either:

1. an explicit lawful model satisfying every admitted premise relevant to the purported forcing theorem while violating the exact target predicate; or
2. a lawful parameterized family of finite models showing that for every proposed source-uniform collar bound there exist sufficiently large members with identical admissible collar data but distinct target-relevant outcomes/states; or
3. a formal independence/non-implication argument of equivalent strength.

A countermodel is admissible only if it:

- satisfies the frozen typed definitions used by the target;
- satisfies every `[U]`/admitted `[D]` premise claimed to force LS-2 at the audited scope;
- satisfies any `[C]` premise only when its complete hypothesis set is explicitly included;
- preserves the relevant observational quotient/refinement/stabilization assumptions rather than evading them;
- violates finite-interface sufficiency itself, not merely an unrelated stronger interpretation;
- does not exploit a presentation-level label or hidden coordinate prohibited by the frozen no-smuggling rules.

One lawful countermodel is sufficient to defeat a universally quantified forcing claim. If the putative source claim is only packet-specific or otherwise scoped, the countermodel must match that scope.

## 8. Required execution procedure

When separately authorized, execution must proceed in this order:

### Pass 1 — source map

Mechanically identify all occurrences and dependency neighbors in the seven frozen spine books for the audit vocabulary, including at minimum:

`LS-2`, `interface`, `collar`, `screen`, `locality`, `local`, `stabilization`, `refinement`, `boundary`, `determin`, `propagation`, `persistence`, `transfer`, `quotient`, `factor`, `sufficien`.

Record exact labels and source locations before interpreting their force.

### Pass 2 — premise ledger

Classify every potentially load-bearing statement under Section 4 and construct the smallest explicit premise set that could support P5.

### Pass 3 — strongest positive derivation

Attempt the strongest source-faithful derivation of P5. Any use of a target-equivalent conditional assumption must be exposed as such rather than counted as derivation.

### Pass 4 — adversarial nonforcing test

Attempt to falsify the strongest positive derivation with an admissible countermodel or independence construction under Section 7.

### Pass 5 — equivalence and scope audit

Check whether any positive theorem is genuinely LS-2-equivalent, merely packet-specific, merely a counting consequence conditional on factorization, or a weaker P1–P4 result.

### Pass 6 — outcome assignment

Assign exactly one controlling outcome from Section 9. Subsidiary surviving results may be recorded without changing that controlling outcome.

No external source search is permitted. No canon repair is permitted. No new NFC axiom may be proposed inside the execution artifact.

## 9. Frozen outcome taxonomy and precedence

The controlling result must be exactly one of:

```text
A__LS2_EQUIVALENT_SOURCE_FORCED
B__PARTIAL_FINITE_INTERFACE_CONSEQUENCE_ONLY
C__SOURCE_NONFORCING_ESTABLISHED_BY_COUNTERMODEL_OR_INDEPENDENCE_ARGUMENT
D__CURRENT_SOURCE_INSUFFICIENT_TO_DECIDE
E__SOURCE_OR_SCOPE_DEFECT_DISCOVERED
```

Outcome rules:

### A — LS2 equivalent source forced

Use only if Section 6 is satisfied and the adversarial pass finds no valid premise/scope defect. A source theorem that assumes P5 or an equivalent screening condition does not qualify.

### B — partial finite-interface consequence only

Use when the source proves a genuine positive consequence related to interfaces/collars (for example finite interface alphabet, bounded counting conditional on factorization, or packet-scoped sufficiency) but does not establish the preregistered P5 target at the claimed broader scope, and no explicit nonforcing construction strong enough for C is established.

### C — source nonforcing established

Use when Section 7 is satisfied. If a weaker positive theorem also survives, record it as a subsidiary result; C remains controlling for the universal/source-forcing target.

### D — current source insufficient to decide

Use when neither a complete forcing proof nor a valid nonforcing/independence argument is established, and the source boundary is coherent enough that E does not apply. Failure to find a proof alone is D, not C.

### E — source or scope defect discovered

Use when the audit cannot be validly adjudicated because the frozen source boundary, same-tier source semantics, target quantifiers, or required object/scope is internally defective or irreducibly ambiguous. E is not a scientific repair authorization; it is a stop condition requiring a separately governed scope/repair decision.

Precedence when multiple observations occur:

```text
E if adjudication itself is invalidated by source/scope defect;
otherwise C over B when a valid nonforcing construction exists;
otherwise A if the complete forcing criterion is met;
otherwise B if a genuine positive partial consequence is established;
otherwise D.
```

A and C may not both be recorded as controlling. If both appear supported, classify the inconsistency under E and stop.

## 10. Bias-control and firewall rules

The execution must not:

- define “passing” as preserving NFC;
- define “failure” as damaging NFC;
- infer boundary sufficiency from locality merely because later branch architecture needs it;
- treat a finite alphabet as proof that the alphabet is sufficient;
- let a collar radius scale with the whole interior and still call the result nontrivial LS-2;
- treat source silence as formal independence;
- use the noncanonical foundational-reduction continuity record as evidence for C;
- promote a later Observatory finding into NFC canon;
- rewrite an NFC file, status, theorem, ledger, or branch;
- expand into `OBS-U003` globalization, physical-history selection, empirical adequacy, or NS common-state completion;
- perform an external literature search;
- propose repairs or replacement axioms in the controlling adjudication.

## 11. Stop condition for this preregistration

After freezing this document and its source manifest:

```text
OBS_U002_TARGET_SELECTED = YES
OBS_U002_AUDIT_PREREGISTERED = YES
OBS_U002_AUDIT_EXECUTED = NO
NFC_REPOSITORY_MUTATED = NO
NFC_CANON_MODIFIED = NO
OUTCOME_ADJUDICATED = NO
COUNTERMODEL_CONSTRUCTED = NO
DERIVATION_EXECUTED = NO
EXTERNAL_SOURCE_SEARCH = NO
```

Stop here. Execution requires a new, explicit authorization.