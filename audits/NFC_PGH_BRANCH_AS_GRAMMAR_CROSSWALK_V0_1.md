# NFC ↔ PGH Branch-as-Grammar Crosswalk — v0.1

STATUS = EXECUTED__PRIMARY_OUTCOME_B
DATE = 2026-09-11

## 1. Operation

NFC_PGH_BRANCH_AS_GRAMMAR_CROSSWALK

This report executes the preregistered, read-only conceptual crosswalk between the frozen NFC branch architecture and current canonical PGH.

## 2. Exact provenance

PROJECT_OBSERVATORY_REPOSITORY = etblink/Project-Observatory
PROJECT_OBSERVATORY_PREREG_COMMIT = cabded6594f18edadd273e0f6dff206149b87b9e
PROJECT_OBSERVATORY_BRANCH = research/nfc-pgh-branch-as-grammar-crosswalk-v0.1

NFC_REPOSITORY = etblink/Nested-Fibrational-Cosmology
NFC_FROZEN_CANON_COMMIT = ed3047c2cbc0abc34d2549dd27754e4d3d05af78
NFC_FROZEN_CANON_TREE = 00ef55ff36d5e9663ca1ef2c9566e2bc1396f973
NFC_BOOK_V = NFC_Book_V.tex
NFC_SCC_BRANCH = NFC_SCC_Branch.tex
NFC_ACCEPTED_POST_FREEZE_REGISTRATION = 0c8617e93a419439c84aeba241653b30f27e785d

PGH_REPOSITORY = etblink/Physical-Grammar-Hypothesis
PGH_CANONICAL_MAIN = d8a16161f33d3bb8f97c15f095ca651c169f5896
PGH_CANONICAL_TREE = 772b0946912aeae73cfec6b1676e71911fb89cb5
PGH_ACTIVE_FORMAL_GRAMMAR = PGH-GRAM-0010
PGH_ACTIVE_BRIDGE = PGH-OBJ-0051
PGH_ACTIVE_PACKAGE = PGH-OBJ-0052

No source project was mutated in this operation.

## 3. Primary result

PRIMARY_OUTCOME = B__PARTIAL_CORRESPONDENCE__GRAMMAR_ANALOGY_USEFUL_BUT_INCOMPLETE

ACTUALIZATION_RELATION = NEITHER_SIDE_SUPPLIES_ACTUALIZATION_AT_AUDITED_SCOPE

### Short statement

The intuition that an NFC branch is grammar-like is structurally informative, but the exact identity

`NFC_BRANCH = PGH_GRAMMAR`

is too strong.

A closer crosswalk is:

`NFC branch grammar-like kernel` ↔ `PGH G`

while

`NFC full branch package (target category + realization functor + bridge + declared hypotheses + endpoint/closure machinery)`

maps more nearly to

`PGH candidate package (G + J + S + I)`

than to `G` alone.

The correspondence is therefore nontrivial and project-specific, but incomplete.

## 4. Source-bound architecture on each side

### 4.1 NFC branch architecture

Book V defines a licensed branch candidate as a target category `C` plus a realization functor

`F : POT -> C`

licensed by an explicit bridge theorem. Its endpoint is `E = F(U)`, where `U` is the universal source object. Canonical branch force requires certified source descent, endpoint visibility, a legitimacy witness, and exclusion of hidden-channel supplementation.

Book V expressly allows declared branch-specific hypotheses, but requires them to be visible in the branch's legitimacy accounting rather than hidden.

The SCC branch makes this architecture concrete. It declares a target category, realization functor, terminal predicate, branch-specific dependency spine, named obligations, and a bridge stack. Its closure machinery then constrains/canonicalizes source-descended SCC structures.

Thus an NFC branch is not merely a set of productions. It is a governed realization package downstream of a common source.

### 4.2 PGH grammar architecture

`PGH-GRAM-0010` declares as grammar identity:

- three observed binary roles;
- three arbitrary-finite latent/source roles;
- fixed pairwise triangle incidence;
- mutual source independence;
- arbitrary normalized local stochastic kernels compatible with incidence.

From these compact structural commitments it generates a proper observable model class `T_ind` and excludes the nondegenerate perfect-common-bit distribution for every allowed local kernel/source cardinality.

The grammar explicitly separates grammar rules from model data: local cardinalities and local kernel values are not grammar rules.

`PGH-OBJ-0051` is then a separate bridge. It realizes the entire model class as prospective empirical joint distributions while deliberately performing no proper-subset selection, local-kernel selection, latent-cardinality fit, or new response-equation selection.

`PGH-OBJ-0052` further separates the complete empirical candidate into `C_triangle=(G,J,S,I)`.

Therefore canonical PGH itself distinguishes the formal grammar from the full physical-candidate package.

## 5. Axis-by-axis crosswalk

### Axis A — Generativity

NFC:

A lawful branch receives source-descended structure through `F` and constrains/realizes an endpoint family inside a target category. Branch books may add lawful closure, transport, equivalence, or branch-specific dynamics under declared hypotheses.

PGH:

`PGH-GRAM-0010` more directly generates a family/model class from a compact structural package while leaving local kernels free.

Assessment:

`CORRESPONDENCE = REAL_BUT_ASYMMETRIC`

Both architectures define nontrivial families from compact structural constraints. PGH's object called `G` is more purely generative; an NFC branch already includes a realization map from an upstream source.

### Axis B — Exclusion

NFC:

Branch legitimacy, collapse/admissibility conditions, terminal predicates, and no-hidden-channel rules exclude unlawful descendants or endpoint claims. Specific branches may add further conditional exclusions.

PGH:

The fixed triangle topology plus source independence excludes distributions even with arbitrary local kernels. PGH explicitly attributes this selectivity to the topology/independence package rather than to free local response laws.

Assessment:

`CORRESPONDENCE = STRONG_STRUCTURAL`

Both systems attach explanatory importance to compact constraints that rule out otherwise available structures. The scientific interpretation of that exclusion differs.

### Axis C — Composition

NFC:

Composition appears through POT morphisms, realization functors, admissible extension/transport, gluing/amalgamation, and branch-specific categorical structure.

PGH:

Composition appears through stochastic kernels and source-access topology; earlier PGH scaffolds also explicitly treat composition as a grammar ingredient.

Assessment:

`CORRESPONDENCE = PARTIAL`

Both are compositional, but the primitive compositional objects and their physical roles are different.

### Axis D — Identification/equivalence

NFC:

The source and branches use observational quotienting, source equivalence, path/endpoint equivalence, carrier equivalence, and branch identity. Book V requires branch-visible observables to be invariant under source-equivalent replacement.

PGH:

`PGH-GRAM-0010` is defined up to graph isomorphism preserving its structural identity. PGH separately proves that formal equivalence alone does not entail physical equivalence unless an additional physical-significance restriction is imposed.

Assessment:

`CORRESPONDENCE = STRONG_FORMAL__PHYSICAL_FORCE_DIFFERS`

Both sharply distinguish presentation changes from structural identity. PGH is more explicit that a formal quotient/equivalence does not automatically carry physical force.

### Axis E — Derivation/dynamics

NFC:

NFC branches can contain branch-local processes or dynamics. Accepted post-freeze audits nevertheless found no source-forced universal actual-history selector, and SCC recursion/canonicalization does not actualize one history.

PGH:

`PGH-GRAM-0010` permits arbitrary local stochastic kernels compatible with its incidence structure. Its bridge preserves multiple empirically incompatible response laws and explicitly performs no local-kernel selection.

Assessment:

`CORRESPONDENCE = STRONG_AT_ADMISSIBILITY_LEVEL__NO_SHARED_ACTUALIZATION`

Both architectures can constrain a space of lawful processes/responses without selecting one actual trajectory/response law.

### Axis F — Representation invariance

NFC:

Book V defines endpoint visibility and canonical branch projection relative to source-equivalent/isomorphic data and a declared realization functor.

PGH:

Grammar identity is invariant under graph isomorphism preserving observed/source classes, incidence, independence, and binary observed alphabet. Mere renaming is explicitly presentation change.

Assessment:

`CORRESPONDENCE = STRONG`

This is not merely shared vocabulary; both projects contain explicit invariance machinery. However, PGH-S demands eventual recovery across genuinely different faithful mathematical surface languages, a stronger burden not established for NFC branches as grammars.

### Axis G — No-smuggling

NFC:

Book V prohibits undeclared hidden-channel supplementation. A branch may use declared branch-specific hypotheses so long as their role is explicit and certified.

PGH:

Strong PGH imposes a stricter explanatory accounting test: substantive physics may not merely be relocated into grammar primitives, topology, scope, semantics, interpretation, or an unexplained initial structure. PGH's preserved failure records explicitly say selective graph/wiring/topology information must be charged to candidate identity and that an auxiliary physical scope law can simply relocate the law-selection burden.

Assessment:

`CORRESPONDENCE = SHARED_DISCIPLINE_WITH_MATERIAL_TENSION`

NFC's no-smuggling rule asks whether extra structure is declared and lawfully licensed. Strong PGH additionally asks whether the declared structure itself explains physical possibility rather than merely encoding/relocating substantive physics.

This is the largest obstacle to literal branch=grammar identity.

### Axis H — Actualization

NFC:

Accepted audits establish at the audited frozen scope that the source does not force a universal actual-history selector and SCC canonicalizes without actualizing. The sharpened missing-object class is an `ACTUALIZATION_LAW_OVER_ADMISSIBLE_HISTORIES`.

PGH:

The current grammar generates a proper model class, but its bridge retains multiple incompatible response laws. It does not choose a local kernel, response law, or physical instantiation. `PGH-H0` explicitly retains the live-null possibility

`P = Select_L(W(G))`

in which an independent law set performs substantive physical selection.

Assessment:

`ACTUALIZATION_RELATION = NEITHER_SIDE_SUPPLIES_ACTUALIZATION_AT_AUDITED_SCOPE`

PGH currently sharpens the same kind of conceptual boundary but does not fill NFC's gap.

### Axis I — Null-law correspondence

NFC's accepted missing actualization law and PGH's live null are structurally analogous:

- NFC: admissibility/canonicalization can leave multiple histories, requiring an additional actualization law if one history must be physically selected;
- PGH-H0: grammar can leave well-formed possibilities, with an independent `L` doing substantive selection.

The analogy is informative but not an identity. PGH-H0 concerns selection of physical possibility from grammatical well-formedness at a broader programmatic level; NFC's accepted result concerns actual-history selection within its audited architecture.

Assessment:

`CORRESPONDENCE = NONTRIVIAL_ANALOGY__SCOPE_NOT_IDENTICAL`

## 6. Strongest mapping

The strongest source-supported Pro-Correspondence reading is:

1. an NFC branch has a compact declared structural identity;
2. it defines lawful source descent and branch-specific admissibility;
3. it supports composition/continuation and equivalence/canonicalization;
4. it excludes hidden supplementation and unlawful endpoint upgrades;
5. it can generate/constrain a family of branch-visible structures;
6. it may leave multiple lawful histories/processes unresolved.

Those roles correspond nontrivially to PGH's generativity, contextual constraint, composition, equivalence, permitted derivation, exclusion, representation discipline, and anti-smuggling burdens.

PRO_CORRESPONDENCE_READING = SURVIVES_IN_PART

The mapping is stronger than the trivial statement that both are mathematical rule systems.

## 7. Strongest anti-correspondence reading

The literal identity fails for three source-bound reasons.

### 7.1 Unit mismatch

An NFC branch is defined as a target category plus realization functor plus bridge and branch-specific hypotheses. PGH deliberately reserves `G` for the formal grammar and keeps semantic bridge `J`, physical scope `S`, and instantiation `I` separate.

Therefore the whole NFC branch corresponds more naturally to a PGH candidate package than to `G` alone.

### 7.2 Explanatory-burden mismatch

NFC permits declared branch-specific hypotheses if they are explicit and lawfully licensed. PGH-S asks the stronger question whether physically selective assumptions are actually generated/explained by grammar or merely relocated into declared structure.

A lawful NFC branch can therefore remain scientifically valid while failing strong-PGH law-exhaustion criteria.

### 7.3 Physical-force mismatch

NFC branch legitimacy certifies lawful descent within NFC's own source architecture. PGH requires independent justification before treating formal equivalence, topology, or grammatical structure as physically constitutive.

ANTI_CORRESPONDENCE_READING = SURVIVES_AS_LIMIT_ON_LITERAL_IDENTITY

It does not reduce the entire correspondence to generic resemblance; it limits the scope of the mapping.

## 8. Actualization reversal

Assume one architecture contains the other's missing selector.

### PGH -> NFC candidate

`PGH-GRAM-0010` does not qualify:

- local kernels remain arbitrary;
- the bridge realizes the full model class rather than selecting a member;
- multiple incompatible empirical response laws remain;
- no actual physical instantiation exists;
- strong PGH is unconfirmed and R2B unsatisfied.

Thus PGH supplies exclusion/admissibility, not NFC's missing actualization law.

### NFC -> PGH candidate

The accepted NFC source/SCC audits already exclude source-forced universal actualization at the audited scope. Branch-specific dynamics do not satisfy PGH-S merely by existing; if substantive selection depends on branch-specific physical hypotheses, PGH's accounting would treat that content as a separate burden rather than as proof that grammar exhausted law.

Thus NFC supplies no hidden strong-PGH actualization mechanism either.

ACTUALIZATION_REVERSAL = FAILS_BOTH_DIRECTIONS

## 9. Why Outcome A is not justified

A deep one-to-one structural correspondence would require a stable mapping between the same kinds of objects.

The exact sources instead show a systematic level shift:

`NFC branch` includes structures corresponding to `PGH G`, `J`, and parts of scope/instantiation accounting.

The correspondence is therefore not clean enough to classify as `A__DEEP_STRUCTURAL_CORRESPONDENCE_WITH_DISTINCT_SCOPE`.

## 10. Why Outcome C or D is too weak/strong respectively

Outcome C (`GENERIC_FORMAL_RESEMBLANCE_ONLY`) is too weak because the projects independently contain specific parallel machinery for generativity, exclusion, representation invariance, equivalence, anti-smuggling, lawful transformations, and the separation of formal canonicality from physical selection.

Outcome D (`STRUCTURAL_TENSION_OR_ANTI_CORRESPONDENCE`) is too strong because the mismatches do not destroy the mapping. They clarify its level: grammar-like structure is a genuine component of NFC branchhood, but branchhood is broader than grammar and strong PGH imposes additional explanatory burdens.

## 11. Primary adjudication

PRIMARY_OUTCOME = B__PARTIAL_CORRESPONDENCE__GRAMMAR_ANALOGY_USEFUL_BUT_INCOMPLETE

Accepted crosswalk statement, pending independent acceptance:

> Frozen NFC branch architecture contains a genuine grammar-like layer: compact structural constraints govern admissibility, lawful composition/continuation, equivalence, exclusion, and source-descended realization. Current PGH formalizes closely related generative/exclusion roles in an explicitly separated grammar `G`. However, a full NFC branch is not equivalent to a PGH grammar: it already contains realization/bridge and branch-specific hypothesis structure corresponding more nearly to a larger PGH candidate package, and strong PGH imposes an additional law-exhaustion/no-relocation burden not required merely for NFC branch legitimacy.

## 12. Actualization adjudication

ACTUALIZATION_RELATION = NEITHER_SIDE_SUPPLIES_ACTUALIZATION_AT_AUDITED_SCOPE

More specifically:

- NFC has substantial admissibility, dynamics, recursion, and canonicalization, but no source-forced universal actual-history selector at the accepted audited scope;
- PGH-GRAM-0010 has substantive model-class exclusion, but leaves local response laws free and its bridge deliberately performs no member/response selection;
- PGH-H0 remains a live null in which an independent law set performs substantive selection.

The two projects therefore meet at a shared frontier rather than one solving the other's frontier.

## 13. Scientific significance

The historical intuition that NFC branches are grammars should be refined rather than discarded.

A more precise research statement is:

> NFC branchhood appears to factor into a grammar-like admissibility/generative kernel plus realization/bridge/scope structure. PGH isolates these layers explicitly and asks whether the grammar-like kernel can bear more of the physical-selection burden than NFC requires of it.

This refinement is more informative than literal identity because it identifies exactly where the projects diverge and where a future theory would need new content.

The shared unresolved frontier is not merely "more grammar." It is the transition from a constrained family of lawful possibilities to substantive physical selection/actualization without relocating that selection into an auxiliary law, bridge, scope rule, or hidden semantic choice.

## 14. Authority and empirical firewall

This crosswalk does not establish:

- that PGH-S is true;
- that NFC validates PGH;
- that PGH validates NFC;
- that PGH-GRAM-0010 is physically correct;
- that NFC branches are literally grammars in PGH's technical sense;
- that either project has empirical support from the other;
- that PGH is an FCP framework;
- that a unique physical grammar exists;
- that an actualization law has been found.

PGH remains empirically untested at the current candidate scope, Strong PGH remains unconfirmed, and R2B remains unsatisfied.

## 15. Stop state

NFC_PGH_CROSSWALK_PREREGISTERED = YES
NFC_PGH_CROSSWALK_EXECUTED = YES
PRIMARY_OUTCOME = B__PARTIAL_CORRESPONDENCE__GRAMMAR_ANALOGY_USEFUL_BUT_INCOMPLETE
ACTUALIZATION_RELATION = NEITHER_SIDE_SUPPLIES_ACTUALIZATION_AT_AUDITED_SCOPE
NFC_MUTATED = NO
PGH_MUTATED = NO
FCP_MUTATED = NO
PGH_TARGET_SEARCH_RESUMED = NO
EMPIRICAL_CREDIT_CREATED = NO
DOWNSTREAM_ACCEPTANCE_EXECUTED = NO
