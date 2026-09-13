# HiVenues — Executive Product Adjudication 0.1.0

## Status

```text
DECISION_CLASS = EXECUTIVE_PRODUCT_ADJUDICATION
DECISION_OWNER = USER / PROJECT EXECUTIVE
DECISION_DATE_LOCAL = 2026-09-12
DECISION = B
IMPLEMENTATION_AUTHORIZATION = NO
SOURCE_PROJECT_MUTATION = NONE
ASTRA_RESULT_MUTATION = NONE
```

This record binds an executive product decision after three evidence lines were reviewed together:

1. the original 2024 HiVenues founding article;
2. the ten original 2024 UI screenshots supplied by the user;
3. the frozen existing-HiVenues ↔ independent GPT-6 Astra comparison.

The selected doctrine is **B**:

> HiVenues is primarily a **branded Hive-native social/business frontend for places**, and the website/Studio exists to make that usable, beautiful, safe, and operator-manageable.

This is a product-doctrine decision. It is not authorization to port Astra code, rewrite the current v2 schema, change production, activate Hive writes, or deploy anything.

---

## 1. Exact comparison baseline

The immediately preceding independent comparison froze:

```text
EXISTING_HIVENUES_MAIN = 9351655112a25fd8a1d115d8c402534726b1e035
EXISTING_HIVENUES_TREE = 15e1d93a6f84bbca233e9313410b29bc88ef470b

ASTRA_GREENFIELD_COMMIT = e7a03c1aa7e5b8a30e7e8a77b3d927f9e168daf2
ASTRA_GREENFIELD_TREE = 9810d4d44fae5bb43bfd28ce8a350306307aa22c

COMPARISON_FREEZE_COMMIT = ef1a3e8bf5800e5a9f048215c080c468bda17f28
COMPARISON_FREEZE_TREE = c1811edce27ef9dd3423f7b5caed6fd505e1bf41
```

The comparison found no aggregate winner and instead selected a complementary synthesis with a material product-thesis divergence.

---

## 2. Founding visual evidence binding

The user supplied the ten original 2024 UI images directly in the adjudication conversation. Their exact local evidence identities were recorded before this decision.

```text
IMG_3078.jpeg  9521102d781fe9561b9c37e69b925e62d06d478c47dab283da57b29a281e09bf  1180x1536
IMG_3079.png   37524868ac08075d773814dd2b480a4248a9fa8f5905bee9f6795e600f0a74af  1536x735
IMG_3080.png   24896566598b7a2aacfa02860b66b467e657ff9a02121ca29f0488a979aa12fc  1536x735
IMG_3081.png   e903a989661ea3e4ff537da45a5abe1c965640b8616255acd701a8076acf553a  1536x735
IMG_3082.png   ffc2c0088375772a12f2e6329c15b44af32f6db2071037775f74a2c80fbd81bd  1536x735
IMG_3083.png   dcfae440a0724e2cf386414a387574b59db9124ca9547990340dea90cc6173ac  1536x735
IMG_3084.png   833c4437f8e5b424fdd017caea2b14f38d9a03734c7f64f2f37cbfa9e8aa201c  1536x735
IMG_3085.png   f265ef8f6c0d8ecf27ef3e6f46f47dbfc48818655cab1ceb411d8f3725a3c016  1536x506
IMG_3086.png   b25c21d02c64040829bc5ec227df4f388c1823e1159e4232a17db0546964d2a4  1536x649
IMG_3087.png   ca58ac8b4580334fdb47a009a643181130a5cfb9851ecf936294243fd8d17183  1536x697
```

The images show, in substance:

- a familiar public business landing page with `Join Our Community` as the principal product CTA;
- a venue-branded Hive community surface with Threads and Community Posts;
- community join/leave and public payout context;
- a venue-native beer-mug interaction for Hive vote weight;
- full Hive posts rendered within the venue shell;
- portable user profiles, follows, blogs, wall posts, and person-to-person wall publishing;
- an inbox with encrypted-message material;
- profile settings;
- a wallet translating Hive Power, Resource Credits, HBD, voting power, progression, and `Pay Tab` into venue-specific language.

These images are product evidence, not a command to restore the 2024 visual implementation.

---

## 3. Executive product definition

The governing product definition is now:

> **HiVenues turns a real-world place into its own purpose-built Hive frontend. The place supplies the identity, context, vocabulary, business facts, and visual experience; Hive supplies portable identity, community, publishing, social interaction, durable public content, rewards, and economic primitives. HiVenues translates those primitives into the language of the place rather than exposing a generic blockchain application.**

A shorter internal formulation is:

```text
PLACE_FIRST_EXPERIENCE
+
HIVE_FOUNDATIONAL_INFRASTRUCTURE
+
VENUE_NATIVE_TRANSLATION
=
HIVENUES
```

### Consequence

A HiVenue is **not** defined as a generic venue website to which Hive may optionally be attached without changing the product's identity.

That later product interpretation is superseded at the doctrine level.

This does **not** mean:

- every public visitor must sign in;
- every page must show Hive terminology;
- every venue action must write on-chain;
- every venue surface must visibly expose community controls;
- transaction authority follows automatically from community availability;
- the current v2 source must be immediately rewritten.

The product should make Hive structurally real while making unnecessary blockchain complexity experientially quiet.

---

## 4. Reaffirmed doctrines

The following existing decisions survive and are strengthened by the founding evidence and Astra convergence.

### R1 — Venue-first presentation

Visitors experience the place first. HiVenues/Hive infrastructure must not become the visual identity of the venue.

### R2 — Translate Hive; do not merely expose or remove it

The correct UX move is contextual translation.

Examples in principle:

- voting influence may be expressed in venue-native language while retaining real Hive semantics;
- community participation may be labeled according to the social meaning of the place;
- economic actions must use ordinary-user wording while preserving explicit value/signing truth;
- protocol detail remains available where needed for informed consent, audit, and advanced users.

### R3 — Public browsing does not require authentication

A visitor must be able to understand the venue, events, visit information, and public social context without mandatory Keychain interaction.

### R4 — Portable Hive identity remains the social identity

HiVenues should not invent a proprietary parallel social-identity system merely to simplify presentation.

### R5 — Semantic authoring, not free-form page construction

The current semantic venue/page/resource/component direction is reaffirmed.

The independent Astra line converged on the same essential authoring shape: semantic structure, real rendered venue, and contextual editing.

### R6 — One responsive semantic source

Do not create independent desktop/mobile content trees.

### R7 — Real renderer as preview authority

Studio must preview the actual semantic result, not a disconnected mock representation.

### R8 — Typed transaction integrity

The existing proposal/apply/discard, stable identity, digest, validation, exact history, explicit Save/reopen, and fail-closed authoring machinery remains a core strength.

### R9 — Local/user-controlled Hive signing

Patron and merchant authority remains explicit. Ordinary social/economic actions must not silently acquire server-side private-key authority.

### R10 — Transaction capability remains separately privileged

Hive-native product identity does not collapse payment/security boundaries.

A visual payment control cannot create merchant authority. Community participation cannot imply funds authority.

### R11 — Accessibility, provenance, and cross-platform qualification remain release requirements

Visual maturation must not trade away the existing accessibility, deterministic test, CI, provenance, recovery, or production-safety discipline.

---

## 5. Superseded or narrowed doctrines

### S1 — `HIVE_COMMUNITY_IS_OPTIONAL_PRODUCT_CAPABILITY`

**Disposition: SUPERSEDED AS PRODUCT DOCTRINE.**

The accepted PM1 architecture deliberately allowed a complete public venue presence with no Hive activation and treated Community as optional.

That was a coherent general-site-platform decision, but it is no longer the governing definition of what a production HiVenue *is*.

#### Replacement

Hive-native social identity/community is foundational to the HiVenues product model.

However, the source/runtime may still represent:

- pre-connection authoring states;
- synthetic fixtures;
- offline/local development states;
- public read-only fallback states;
- temporarily unavailable Hive services.

Therefore this executive decision does **not** require removing `community.state = disabled` from the current schema immediately.

Instead distinguish:

```text
SCHEMA_REPRESENTABILITY != PRODUCT_QUALIFICATION
```

A source may be representable before a Hive binding exists; a venue should not be called a fully qualified HiVenue merely because its brochure pages render.

### S2 — `GENERIC_VENUE_WEBSITE_IS_THE_UNIVERSAL_PRODUCT_SURFACE`

**Disposition: NARROWED.**

The public venue surface remains universal for browsing and place identity, but it is an entry surface into a larger Hive-native place experience rather than the complete product definition.

### S3 — `COMMUNITY_IS_SECONDARY_APPLICATION_MODULE`

**Disposition: SUPERSEDED.**

Community may be visually quiet or contextually placed, but it is not conceptually an accessory.

### S4 — raw Hive terminology as primary ordinary-user language

**Disposition: REJECTED.**

The original 2024 prototype already demonstrated the stronger direction through contextual metaphors such as the beer-vote control and venue-themed wallet concepts. Astra independently reinforced this translation principle.

---

## 6. New or strengthened product doctrines

### N1 — Hive foundational, venue language primary

```text
HIVE = FOUNDATIONAL
BLOCKCHAIN_JARGON = MINIMIZED
SEMANTIC_TRUTH = PRESERVED
```

### N2 — Events should become persistent social objects

The Astra greenfield line independently introduced a high-value concept: an event retains a stable Hive discussion/social identity across ordinary business edits.

Adopt this as a design target subject to a separately preregistered integration contract.

The desired meaning is:

```text
EVENT_BUSINESS_STATE
  date / time / title / ticket / venue facts

+

EVENT_SOCIAL_IDENTITY
  stable Hive discussion identity
  conversation / replies / stories / post-event continuity

=

PERSISTENT_PLACE_MEMORY
```

Changing an event date or presentation must not casually destroy its accumulated social identity.

No exact `author/permlink` schema is frozen by this decision.

### N3 — Place memory is a product asset

HiVenues should make real gatherings persist socially after the physical moment ends: announcement → anticipation → attendance → discussion → photos/stories → recap → durable community history.

### N4 — Astra visual quality becomes a reference ceiling, not a code dependency

Lowlight and Forma establish a stronger 2026 product-quality reference for venue atmosphere and Studio calmness.

The existing implementation should converge toward that class of perceived finish while retaining its stronger accessibility and engineering discipline.

### N5 — Existing transaction core, calmer operator surface

The Studio should preserve the current typed authoring engine underneath a substantially more productized interaction language.

Desired synthesis:

```text
ASTRA_CALM_PRODUCT_SHELL
+
EXISTING_TYPED_AUTHORING_ENGINE
```

The operator should understand *what they are changing* before being exposed to *how the internal transaction machinery works*.

### N6 — Social/economic actions require semantic consequence previews

Ordinary language is not permission to obscure consequence.

A signer/review boundary should say, in user terms:

- what will happen;
- who will sign;
- whether value moves;
- whether the action becomes public/on-chain;
- whether it can be reversed by HiVenues.

Protocol detail may be expandable rather than dominant.

---

## 7. What is explicitly not being adopted from the 2024 prototype

The founding screenshots are evidence of intent, not a frozen UI specification.

Do not restore by default:

- the 2024 dashboard visual hierarchy;
- raw community payout emphasis as primary place navigation;
- desktop-first fixed layouts;
- prototype-era profile navigation;
- old wallet metaphors without current usability/accessibility validation;
- any security or signing behavior merely because the prototype displayed it.

The doctrine survives; the prototype implementation does not control the future UI.

---

## 8. Relationship to the independent Astra result

The executive decision does **not** select Astra wholesale.

### Adopt from Astra as product direction

- Hive foundational product thesis;
- venue-native translation of Hive actions;
- event as persistent social object;
- stronger atmospheric generated-site quality;
- calmer/productized Studio interaction language;
- clear separation between configuring a place and signing a Hive consequence.

### Preserve from existing HiVenues as controlling machinery

- broad semantic domain/resource model;
- stable identities and shared consumers;
- typed authoring transactions;
- deterministic validation and history;
- explicit persistence/reopen semantics;
- Keychain and authority discipline;
- accessibility/browser evidence;
- cross-platform CI;
- actual Hive integration;
- production/deployment/recovery discipline.

### Synthesis thesis

```text
ASTRA_PRODUCT_PHILOSOPHY
+ ASTRA_HUMAN_LANGUAGE
+ ASTRA_EVENT_SOCIAL_MODEL
+ ASTRA_VISUAL_CEILING
+ EXISTING_DOMAIN_MODEL
+ EXISTING_AUTHORING_INTEGRITY
+ EXISTING_SECURITY
+ EXISTING_PRODUCTION_DISCIPLINE
= TARGET_HIVENUES_DIRECTION
```

---

## 9. Concrete implementation sequence

No implementation starts from this record alone. The next source-project operation should be separately authorized and should follow this order.

### Phase 1 — Doctrine reconciliation, no feature implementation

Create one HiVenues source-project decision record that:

1. binds this executive adjudication and the frozen Astra comparison;
2. states that historical PM1 documents remain provenance records and are not rewritten in place;
3. records the precise supersession of the optional-Hive product doctrine;
4. distinguishes schema-valid preconnection/offline states from production HiVenue qualification;
5. preserves transaction/security boundaries;
6. updates the roadmap so later work cannot accidentally optimize toward a generic non-Hive website builder.

**Stop after documentation/routing reconciliation.**

### Phase 2 — Hive-native product contract

Preregister a bounded product/architecture contract for:

- minimum Hive binding required for a production-qualified HiVenue;
- public anonymous/read-only behavior;
- fallback behavior when Hive reads are unavailable;
- identity/community entry semantics;
- venue-native terminology registry;
- when raw Hive/protocol terminology is revealed;
- distinction among release, public Hive publication, social action, and value-moving action.

Do not change production in this phase.

### Phase 3 — Event social-object design

Before implementation, freeze:

- stable event business identity;
- stable Hive social identity;
- creation timing and authority;
- editing consequences;
- cancellation/reschedule behavior;
- deletion/archive behavior;
- reply/story/post-event continuity;
- migration for existing events;
- offline/unbound event state;
- exact signer and failure semantics.

Only then implement the smallest end-to-end event social binding.

### Phase 4 — Finish only the still-relevant Issue #199 operator gaps

Re-audit the open #199 matrix against this doctrine before resuming mechanically.

Likely retained needs include:

- ticket/reservation actions;
- timestamp editing;
- general media;
- component recipes;
- complete fresh-archetype journeys;
- remaining resource/menu lifecycle work where still open.

Do not finish a gap merely because the old roadmap listed it if the new doctrine changes the task.

### Phase 5 — Studio product-language convergence

Retain the existing transaction engine while redesigning the operator surface toward:

- clearer venue/task language;
- less implementation vocabulary;
- calmer hierarchy;
- semantic section editing;
- stronger direct-manipulation/contextual selection where safe;
- explicit consequence review only when consequence matters;
- clean distinction among draft, saved source, release, Hive publication, social signing, and value movement.

### Phase 6 — Generated-experience visual convergence

Use:

- original 2024 intent as doctrine evidence;
- Astra Lowlight/Forma as modern quality references;
- existing HiVenues reference archetypes as semantic/accessibility/regression fixtures.

Raise the generated-site bar without venue-specific renderer forks or hidden template authority.

### Phase 7 — Reconcile social surfaces

Revisit profiles, follows, community, walls/inbox/messaging, rewards/wallet translation, and place memory under modern security/UX constraints.

Do not blindly restore every 2024 feature. Each social surface must justify its present-day place in the experience.

### Phase 8 — Measured quality/release gates

Only after the product doctrine and relevant PM4 work converge should Issue #200-style measured quality/release gates be run.

Required classes should include:

- operator task completion;
- patron comprehension;
- mobile/responsive quality;
- accessibility;
- security/authority comprehension;
- Hive failure/fallback behavior;
- real renderer/source integrity;
- performance;
- cross-platform deterministic qualification;
- production transition safety.

### Phase 9 — External user validation

Executive adjudication is sufficient to choose product direction, but not sufficient to establish usability.

After a coherent candidate exists, test with real venue operators and patrons. Use failures to revise the implementation rather than to reopen the already-set product identity unless evidence genuinely warrants it.

---

## 10. Portfolio consequence

The previous independent experiment has served its purpose.

The next HiVenues work should not be another unconstrained architecture exercise.

The correct next operation is:

```text
HIVENUES_PRODUCT_DOCTRINE_RECONCILIATION_V0_1
```

It should be documentation/routing only, bounded to the source project, and should stop before code implementation.

---

## 11. Final executive disposition

```text
HIVENUES_PRIMARY_IDENTITY = BRANDED_HIVE_NATIVE_SOCIAL_BUSINESS_FRONTEND_FOR_PLACES
PUBLIC_VENUE_SITE = REQUIRED_ENTRY_AND_PLACE_IDENTITY_SURFACE
HIVE = FOUNDATIONAL_INFRASTRUCTURE
HIVE_JARGON = CONTEXTUALLY_MINIMIZED
COMMUNITY = FOUNDATIONAL_PRODUCT_DIMENSION
PUBLIC_SIGN_IN_REQUIREMENT = NO
SEMANTIC_STUDIO = REAFFIRMED
FREEFORM_PAGE_BUILDER = REJECTED
EVENT_SOCIAL_OBJECT_DIRECTION = ADOPTED_FOR_SEPARATE_DESIGN
EXISTING_TYPED_AUTHORING_ENGINE = PRESERVE
EXISTING_SECURITY_AND_PRODUCTION_DISCIPLINE = PRESERVE
ASTRA_CODE_PORT = NOT_AUTHORIZED
2024_UI_REVERSION = NOT_AUTHORIZED
NEXT_OPERATION = HIVENUES_PRODUCT_DOCTRINE_RECONCILIATION_V0_1
```

The governing aim is not to make Hive invisible by making it optional.

The governing aim is to make Hive **native enough that the user can focus on the place**.
