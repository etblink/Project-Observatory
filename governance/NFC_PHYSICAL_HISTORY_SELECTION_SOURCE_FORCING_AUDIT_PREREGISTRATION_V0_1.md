# NFC Physical-History Selection Source-Forcing Audit — Preregistration V0.1

Status: `PREREGISTERED__AUDIT_NOT_EXECUTED`

Operation: `NFC_PHYSICAL_HISTORY_SELECTION_SOURCE_FORCING_AUDIT_PREREGISTRATION_V0_1`

## 0. Authorization and hard stop

This operation preregisters the selected `OBS-U001 / NFC_PHYSICAL_HISTORY_SELECTION_SOURCE_FORCING` audit and **does not execute it**.

The preregistration is governed by Project Observatory Snapshot V0.1 and the post-snapshot target-selection record. It does not alter Snapshot V0.1, does not adjudicate NFC, does not modify NFC canon, and does not update FCP.

The audit may begin only under a later explicit execution authorization after this preregistration commit exists.

## 1. Bound provenance

```text
PROJECT_OBSERVATORY_REPOSITORY = etblink/Project-Observatory
PROJECT_OBSERVATORY_SELECTION_BASE = 1a8cad05a8fba93f9bd9ef476222efccaa8d7782
METHOD_FREEZE_COMMIT = 421a1237805d41365d02105d293711c72ea116b1
SNAPSHOT_CONTENT_COMMIT = 09856095d8ff1f29f72676a768896b4f425edf17
SNAPSHOT_CONTENT_TREE = c3cd39ce3de7d11faf1680321e4f843cd1ddd94a
SNAPSHOT_MANIFEST_COMMIT = 128f6c32e06f1a6044bedabe23a354db180a7d4e

NFC_REPOSITORY = etblink/Nested-Fibrational-Cosmology
NFC_FROZEN_CANON_COMMIT = ed3047c2cbc0abc34d2549dd27754e4d3d05af78
NFC_AUDIT_BRANCH = audit/physical-history-selection-source-forcing
```

The NFC audit branch is created from the exact frozen canon commit solely as a future audit workspace. Branch creation changes no canon content.

## 2. Exact target proposition

The audit asks:

> Does the frozen canonical NFC source, from its own accepted premises and without importing an additional selector, branch-specific realization rule, probability kernel, empirical postulate, or post-freeze diagnostic assumption, force a nontrivial law or structure that selects the actual physical history from the class of structurally admissible processes?

This is a **source-forcing / independence audit**. It is not an empirical test and not a request to invent a completion of NFC.

## 3. Source boundary

### 3.1 Admissible primary source corpus

The primary corpus is frozen at NFC commit `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`.

For scientific forcing, the audit will inspect the 17 canonical TeX source books present at that commit:

- `NFC_Book_I.tex` through `NFC_Book_VII.tex`;
- `NFC_BIO_Branch.tex`;
- `NFC_CRYST_Branch.tex`;
- `NFC_GR_Branch.tex`;
- `NFC_LING_Branch.tex`;
- `NFC_NS_Branch.tex`;
- `NFC_RH_Branch.tex`;
- `NFC_SCC_Branch.tex`;
- `NFC_SM_Branch.tex`;
- `NFC_SPEC_Branch.tex`;
- `NFC_YM_Branch.tex`.

The TeX sources, not their generated PDFs, are the scientific text of record for this audit.

### 3.2 Admissible governance/provenance aids

The following same-commit files may be used to determine authority, provenance, labels, status, and search completeness, but **not to manufacture a theorem absent from the canonical TeX corpus**:

- `CANON_AUTHORITY_MODEL.md`;
- `NFC_CANON_LEDGER.md`;
- `NFC_STATE_OF_CANON.md`;
- `NFC_OBLIGATION_ROSTER.md`;
- `FINAL_VALIDATION_REPORT.md`;
- machine-readable metadata or validation outputs present at the same commit, where they merely index or validate canonical source.

Where a governance aid and canonical theorem body differ about scientific content, the frozen NFC authority hierarchy governs. In-body branch status propositions/frontiers/obligation discharges have their declared competencies; provenance summaries do not silently supersede theorem text.

### 3.3 Excluded from proof force

The following are excluded as premises for a positive source-forcing result:

- `research/foundational-reduction-continuity` and every other post-freeze/noncanonical diagnostic branch;
- Project Observatory conclusions;
- FCP interpretations or comparator dynamics;
- PGH;
- external literature;
- ordinary quantum-mechanical, GR, statistical-mechanical, cosmological, or empirical assumptions unless the frozen NFC canon itself explicitly imports them as a premise at the audited scope;
- generated PDFs as independent evidence beyond their source TeX;
- future edits, issue discussion, memory, or unpublished local work.

FCP and the noncanonical NFC reduction may be consulted **after adjudication** only for downstream interpretation, never to decide whether the frozen NFC source itself forces the selector.

## 4. Definitions frozen before execution

### 4.1 Structurally admissible process

For this audit, a structurally admissible process is any process/history candidate satisfying the frozen NFC structural admissibility conditions at the relevant scope. The audit must extract the canon's own exact definitions rather than substitute a new one.

### 4.2 Physical-history selector

A qualifying selector must do more than define admissibility. It must, from source-forced NFC premises, nontrivially narrow the admissible class toward the actual physical history by at least one of the following forms:

1. a deterministic selection law;
2. a stochastic/probabilistic law with a source-forced measure or kernel;
3. a variational/extremal principle with source-forced physical selection force;
4. a unique or equivalence-class selection theorem whose hypotheses are themselves source-forced at the claimed scope;
5. another mathematically explicit mechanism demonstrated to perform actual-history selection rather than mere structural screening.

### 4.3 What does not count as a selector by itself

The following are insufficient unless the canon supplies an additional source-forced rule that converts them into actual-history selection:

- admissibility;
- existence;
- persistence or protected persistence;
- viability;
- stability;
- finite-interface sufficiency;
- classification into regimes;
- compatibility with an observation;
- one-way coupling/no-backreaction conditions;
- branch construction or realization functors;
- an example trajectory;
- a family of allowed trajectories;
- a statement that physical history is one admissible member;
- a conditional theorem whose antecedent already assumes the selector or the physical history to be selected.

## 5. Positive forcing criterion

Outcome `A__SOURCE_FORCED_SELECTION_BRIDGE_ESTABLISHED` requires all of:

1. **Textual identification:** at least one exact canonical theorem/definition/proposition/construction is identified in the primary corpus.
2. **Source-forced premises:** every premise needed for selection is either an NFC axiom/definition at the audited scope or a theorem derived from such premises; no optional branch choice or external physical postulate is smuggled in.
3. **Selection force:** the result provably narrows the admissible process class in a way intended or mathematically sufficient to select actual physical history, not merely structural admissibility.
4. **Non-circularity:** the physical history, selector, measure, kernel, action, boundary data, or realization rule is not assumed in equivalent form among the hypotheses.
5. **Scope match:** the claimed scope is no broader than the source-forced hypotheses support.
6. **Alternative-model resistance:** no admissible model satisfying the same audited premises can vary the putative selector in a way that changes selected histories while preserving all those premises.

Failure of any one condition blocks Outcome A.

## 6. Conditional/branch-specific criterion

Outcome `B__ONLY_CONDITIONAL_OR_BRANCH_SPECIFIC_SELECTOR_ESTABLISHED` applies when the corpus contains mathematically explicit selection mechanisms, but each requires at least one additional choice not source-forced by NFC at the audited general scope, such as:

- a branch-specific dynamical law;
- chosen Hamiltonian/action/evolution rule;
- probability measure/kernel;
- realization map;
- boundary/initial condition with selection force;
- empirical calibration;
- optional test language or regime choice.

This outcome records genuine NFC-compatible dynamics without promoting compatibility into universal source forcing.

## 7. Source-nonforcing criterion

Outcome `C__SOURCE_NONFORCING_ESTABLISHED_AT_AUDITED_SCOPE` requires a constructive independence demonstration, not merely failure to find a theorem.

At least one of the following must be established:

1. **Countermodel pair:** two models/interpretations satisfying the same frozen NFC premises at the audited scope but implementing different physical-history selectors or selecting different histories;
2. **Free-parameter construction:** an explicit family of selector choices remains free while all audited NFC premises remain invariant;
3. **Conservative-extension construction:** two distinct selector extensions can be added to the same NFC structural core without contradiction and without either extension being derivable from the core;
4. **Canon-declared openness plus exhaustive dependency proof:** the canon explicitly leaves the relevant choice open and a complete dependency audit shows no higher-authority theorem closes it.

The audit must state the exact scope of nonforcing. It may not conclude that no future extension of NFC could ever supply a selector.

## 8. Underdetermination and repair criteria

`D__UNDERDETERMINED__FULL_CORPUS_OR_SCOPE_INSUFFICIENT` applies if the source contains suggestive or conflicting material but neither forcing nor independence can be established under the frozen rules.

`E__REPAIR_REQUIRED_BEFORE_ADJUDICATION` applies if an authority conflict, missing dependency, broken reference, ambiguous scope, or other source defect prevents a valid forcing decision. The audit must identify the defect and stop; it may not repair the canon inside the adjudication.

## 9. Search procedure frozen before execution

Execution must use the following sequence.

### Pass 1 — corpus census and authority map

1. verify the NFC audit branch still descends exactly from `ed3047c2...` with no scientific-content change before audit artifacts;
2. enumerate all 17 canonical TeX files and same-commit authority/provenance aids;
3. bind blob identities for every primary source file used;
4. record the authority hierarchy relevant to conflicting statements.

### Pass 2 — high-recall lexical discovery

Search the complete primary corpus using neutral term families, including stems/synonyms for:

- history, histories, trajectory, evolution, dynamics, dynamical;
- select, selection, choose, choice, actual, realized, realization, physical;
- admissible, viable, persistent, stable, process, transition;
- probability, probabilistic, measure, kernel, weight, amplitude;
- action, variational, extremal, Hamiltonian, Lagrangian;
- initial, boundary, law, unique, uniqueness, determine, determinacy.

Lexical hits are discovery aids only and carry no evidentiary weight by themselves.

### Pass 3 — semantic/dependency expansion

For every plausible selector candidate:

1. read the complete theorem/definition/proposition and its hypotheses;
2. trace cited labels and prerequisites recursively until reaching axioms/definitions or an explicit open/optional input;
3. inspect neighboring status/frontier text for scope and authority;
4. classify each required input as `SOURCE_FORCED`, `DERIVED`, `CONDITIONAL`, `BRANCH_SPECIFIC`, `EXTERNAL`, `OPEN`, or `AMBIGUOUS`;
5. construct a candidate-selection ledger.

### Pass 4 — anti-selector search

Independently search for statements indicating freedom/nonuniqueness, optional dynamics, multiple admissible processes, branch dependence, unspecified measures, open realization, or explicitly unresolved selection. This pass must not be skipped even if a positive candidate is found early.

### Pass 5 — independence/countermodel tests

Attempt the countermodel/free-parameter/conservative-extension constructions in Section 7 against the strongest surviving positive candidate. A positive selector cannot receive Outcome A until it survives these tests.

### Pass 6 — adversarial reversal

Before disposition, perform both reversals:

- **Pro-A reversal:** assume nonforcing is suspected and search specifically for the strongest overlooked source-forced selector.
- **Pro-C reversal:** assume forcing is suspected and search specifically for hidden optional premises or alternative selector models.

### Pass 7 — disposition

Assign exactly one primary outcome A–E. Record secondary observations separately. Do not average outcomes or define a hybrid that evades the frozen criteria.

## 10. Evidence ledger required from execution

The future audit must produce, at minimum:

- exact audited commit/ref identities;
- complete primary-corpus file/blob manifest;
- search-term and hit ledger;
- candidate-selector ledger;
- recursive dependency traces for every serious candidate;
- anti-selector/open-choice ledger;
- countermodel/independence attempts;
- adversarial-reversal record;
- final A–E disposition with source citations and exact scope;
- downstream-routing note that does not itself mutate FCP or NFC canon.

## 11. Frozen allowed outcomes

```text
A__SOURCE_FORCED_SELECTION_BRIDGE_ESTABLISHED
B__ONLY_CONDITIONAL_OR_BRANCH_SPECIFIC_SELECTOR_ESTABLISHED
C__SOURCE_NONFORCING_ESTABLISHED_AT_AUDITED_SCOPE
D__UNDERDETERMINED__FULL_CORPUS_OR_SCOPE_INSUFFICIENT
E__REPAIR_REQUIRED_BEFORE_ADJUDICATION
```

No outcome is preferred. Evidence that weakens NFC is admissible. Evidence that strengthens NFC is admissible. An unresolved result is admissible.

## 12. Audit firewalls

The execution must not:

- infer actual-history selection from admissibility alone;
- infer probability from multiplicity or counting without a source-forced measure;
- infer physical law from mathematical convenience;
- silently import familiar physics;
- treat a branch-specific mechanism as universal NFC law;
- treat an Observatory/FCP diagnostic statement as NFC proof;
- use absence of lexical hits as proof of nonforcing;
- stop searching after the first apparently favorable result;
- repair canon while adjudicating it;
- broaden into LS-2, globalization, empirical adequacy, or general physical realization except where a premise must be classified to test the selected proposition.

## 13. Preregistration stop state

```text
TARGET_SELECTED = YES
TARGET = OBS-U001 / NFC_PHYSICAL_HISTORY_SELECTION_SOURCE_FORCING
PREREGISTRATION_CREATED = YES
AUDIT_EXECUTION_STARTED = NO
AUDIT_RESULT = NONE
NFC_CANON_MUTATED = NO
FCP_MUTATED = NO
PROJECT_OBSERVATORY_SNAPSHOT_V0_1_REWRITTEN = NO
```

Stop here. Substantive inspection for adjudication begins only after separate execution authorization.
