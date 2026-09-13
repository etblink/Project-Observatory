# HiVenues ↔ Independent GPT-6 Astra — Convergence / Divergence / Synthesis Ledger 0.1.0

## Purpose

This ledger records what two independent development histories teach us before any implementation is allowed to borrow from the other.

A `SYNTHESIS_CANDIDATE` is not an implementation instruction. It is a finding eligible for a separately authorized convergence operation after this audit freezes.

# A. Independent convergence ledger

## C1 — semantic authoring over free-form page building

```text
EXISTING = YES
ASTRA = YES
CONFIDENCE = HIGH
```

Both reject a generic rectangle/text-box website builder. Operators manipulate semantic venue concepts.

Existing examples include stable pages, semantic component kinds, shared events/programs/menus/equipment and curated recipes.

Astra's smaller vocabulary includes first impression, events, community, menu/services and visit information.

**Inference:** this is likely a robust product invariant rather than historical accident.

## C2 — structure + real canvas + contextual inspector

```text
EXISTING = PAGE_STRUCTURE + REAL_V2_RENDERER + INSPECTOR
ASTRA = SECTION_OUTLINE + RELEASED/DRAFT_RENDERER + INSPECTOR
CONFIDENCE = HIGH
```

The near-identical high-level Studio geometry arose independently.

**Disposition:** preserve as a HiVenues core interaction model.

## C3 — one semantic source across responsive views

Both reject separate desktop/mobile content trees.

Existing explicitly freezes Desktop → Tablet → Mobile responsive inheritance and uses the real renderer at 390/834/1440 evidence sizes.

Astra's public phone iframe and desktop venue read the same released configuration.

**Disposition:** robust invariant.

## C4 — venue-specific visual recipes instead of one platform skin

Both independently conclude that a listening bar/restaurant/workshop/music venue should not merely receive a logo/color swap.

Existing demonstrates multiple typography/density/hero/list/gallery recipe families.

Astra demonstrates Lowlight versus Forma through materially different typography, palette, composition, imagery and vocabulary.

**Disposition:** robust invariant.

## C5 — patron identity should remain Hive-owned/portable

Both avoid inventing a proprietary HiVenues social identity as the primary patron identity.

**Disposition:** robust invariant.

## C6 — public browsing should not require blockchain expertise or a signature

Both let ordinary venue information remain readable before sign-in and move signing to explicit participation/economic actions.

This remains compatible with the separate disagreement over whether Hive itself is an optional venue capability.

**Disposition:** robust invariant.

## C7 — configuration edits and Hive mutations are different authority domains

Both independently establish that changing a venue/site is not the same thing as posting/voting/transferring on Hive.

Existing uses separate authoring/integration/security ownership classes and Keychain boundaries.

Astra visibly separates editing the venue from separately reviewed operation intents.

**Disposition:** robust invariant.

## C8 — explicit operation review and least authority

Both recognize Posting versus Active consequences and refuse to treat financial operations like ordinary UI state.

Astra independently reconstructs Posting for social participation and Active for HBD transfer.

Existing goes farther with production-grade key minimization, Keychain self-signing and server-credential governance.

**Disposition:** robust invariant.

## C9 — stable semantic identity should survive ordinary edits

Both use stable identity rather than title/order as object identity.

Existing uses stable ids for pages/components/resources/media/navigation and exact transaction history.

Astra uses stable event ids plus author/permlink discussion identity across event edits.

**Disposition:** robust invariant.

## C10 — failure/unavailable states should be explicit

Both avoid pretending unavailable integrations succeeded.

Existing is strongly fail-closed throughout authoring, integrations and deployment.

Astra visibly identifies simulation, live-read fallback, and unavailable booking/provider boundaries.

**Disposition:** robust invariant.

# B. Material divergence ledger

## V1 — Hive foundation versus optional capability

```text
EXISTING_V2 = HIVE_COMMUNITY_OPTIONAL
ASTRA = HIVE_FOUNDATIONAL_TO_HIVENUE
IMPORTANCE = VERY_HIGH
```

This is the controlling philosophical divergence.

Existing PM1 deliberately broadens HiVenues into a venue-first public-site product that remains valid without Hive.

Astra interprets a HiVenue as intrinsically a specialized Hive frontend even when the visitor never sees blockchain machinery.

This difference affects source requirements, onboarding, event semantics, identity, navigation and the answer to “why build this on Hive?”.

## V2 — event resource versus event-social object

Existing models events as rigorous shared business resources with stable ids and derived Event detail.

Astra additionally binds an event to stable Hive discussion identity and connects patron stories to event identity.

The latter creates a stronger bridge between physical gathering and persistent decentralized community.

## V3 — deep transaction rigor versus operator mental-model simplicity

Existing has a sophisticated proposed/accepted/digest/inverse/checkpoint model.

Astra uses simpler product language: draft, released venue, separate signing action.

The two are not mutually exclusive; they operate at different abstraction layers.

## V4 — current visual system ceiling

Existing has broader, systematically tested reference variation.

Astra currently achieves the stronger flagship visual/product impression in Lowlight and Forma.

## V5 — semantic breadth versus bounded coherence

Existing models multiple pages, navigation, media, events, programs, menus, equipment, capabilities and migration.

Astra intentionally constrains the product to two venue kinds and five section kinds.

Existing is more general; Astra is easier to perceive as one coherent product.

## V6 — durable checkpoint versus explicit release snapshot

Existing separates session proposal/accepted draft and durable workspace Save, while production publication remains outside v2 authoring.

Astra adds a local released snapshot distinct from autosaved draft, creating a clearer “what visitors see” mental model even though it is not deployment.

## V7 — real Hive/production maturity

Existing has real Keychain self-signing, production operations and a live venue.

Astra deliberately stops at simulation and local preview.

This is primarily maturity asymmetry, not a conceptual contradiction.

# C. Maturity-asymmetry ledger

## M1 — existing project advantage

Existing has:

- years/iterations of product history;
- production Fourth Street deployment;
- real Hive community/user flows;
- Keychain self-signing;
- payments/onboarding/moderation;
- deployment/rollback/health/readiness;
- many CI and browser gates;
- cross-platform deterministic qualification;
- a richer semantic source model;
- v1→v2 compatibility pressure.

These are genuine accomplishments and cannot be dismissed as mere legacy complexity.

## M2 — Astra bounded-run limitation

Astra has:

- two venue recipes;
- five primary semantic section kinds;
- browser-local persistence;
- simulation-only signing;
- no proven successful live Hive feed in-app;
- no production hosting;
- no tenant/auth/operator infrastructure;
- no durable media service;
- 19 core tests rather than the existing project's large CI envelope.

These gaps limit claims about production architecture but do not invalidate product/UX insights.

## M3 — fairness consequence

Do not read D13/D14 existing wins as evidence that existing D1/D3/D5 decisions are better.

Do not read D1/D3/D5 Astra wins as evidence that Astra's localStorage/signing/runtime choices should replace existing production machinery.

# D. Synthesis-candidate ledger

## S1 — restore “Hive foundational” as a product invariant without making blockchain interaction mandatory for browsing

**Source:** V1 / D1 / D4

Candidate principle:

> Every published HiVenue should have an intentional Hive-native role in its architecture, while ordinary visitors can browse the venue without understanding Hive or signing anything.

This is not the same as forcing a Community tab onto every page or requiring login before venue information.

A separately authorized design operation should decide whether:

- Hive binding becomes a publish/admission requirement rather than a draft-creation requirement;
- a HiVenue may hide most community chrome while still participating in portable identity/social objects;
- non-Hive public-site mode belongs outside the HiVenues product or remains a lower-level draft/website capability.

## S2 — retain existing semantic source/transaction rigor behind a more Astra-like Studio shell

**Source:** C1/C2, V3, D2, D12

Preserve:

- stable ids;
- typed commands;
- server-side target resolution;
- expected digest;
- proposal/apply/discard;
- exact inverse history;
- shared-consumer correctness;
- explicit persistence.

Explore presenting these through:

- task-level Design / Events / Menu & services / Community / Media workspaces;
- direct human language;
- less provenance/debug chrome in the default operator view;
- progressive disclosure for advanced integrity details.

## S3 — make events durable Hive social objects

**Source:** V2 / D7

Add a separately designed relationship from existing stable event resources to stable Hive discussion/content identity.

Requirements before implementation:

- event business identity and Hive post identity remain distinct but linked;
- editing title/time must not silently change discussion identity;
- announcing an event to Hive is a separately reviewed signing operation;
- an event may aggregate related patron stories/media without claiming custody of those posts;
- deletion/cancellation semantics must acknowledge immutable/public Hive history.

## S4 — adopt venue-native Hive vocabulary and consequence disclosure

**Source:** D5 / C6/C7/C8

Strong candidates include the pattern, not necessarily the literal copy:

- human action first;
- Hive operation second;
- protocol details available at review;
- financial/authority consequences explicit;
- no crypto-dashboard visual language.

## S5 — raise the existing visual recipe ceiling using principles, not copied Astra assets/code

**Source:** D3 / V4

Study:

- stronger typography scale;
- bolder venue-specific composition;
- photography/art direction;
- less generic platform chrome in generated venues;
- clearer conversion hierarchy;
- richer mobile composition;
- venue-brand presence inside Studio preview.

Do not copy Lowlight/Forma code or assets merely because they won this visual comparison.

## S6 — expose a clear Draft → Released experience above existing persistence semantics

**Source:** V6 / D12

A later design should test whether operators understand:

```text
DRAFT = what I am editing
RELEASE = what visitors are meant to see
PUBLISH_TO_HIVE = a separate signed social action
DEPLOY = an operational delivery action
```

Existing exact checkpoint/provenance rules should remain underneath this model.

## S7 — use mobile-specific composition recipes without a second mobile content tree

**Source:** C3 / D10

Astra's bottom navigation and mobile hierarchy are useful product evidence. Existing responsive-inheritance rules should remain controlling.

## S8 — preserve existing production/key/security model

**Source:** D8 / D13 / D14

This is a `SYNTHESIS_CANDIDATE` specifically because it should **not** be displaced by greenfield novelty.

Keep:

- local user Keychain signing;
- no patron Hive private keys on server;
- exact authority tier;
- fail-closed capability activation;
- deployment provenance;
- health/readiness/rollback discipline;
- deterministic and browser qualification.

## S9 — finish typed operator journeys rather than importing Astra's simpler data model

**Source:** D9

Current #199 gaps should remain visible and be closed in the existing semantic model. Astra demonstrates that operators should be able to complete these tasks coherently, but it does not justify replacing stable resources with a flatter five-section schema.

## S10 — validate synthesis with people before major implementation

**Source:** portfolio external-survivability doctrine

Before a large convergence refactor, run a counterbalanced task test with real venue operators/patrons using frozen A/B or carefully matched prototypes. The next section defines the recommended experiment.

# E. Do-not-port ledger

The following should **not** be copied from B into A simply because B won some product dimensions:

```text
ASTRA_LOCALSTORAGE_AS_PRODUCTION_PERSISTENCE
ASTRA_SIMULATION_SIGNER_AS_PRODUCTION_SIGNER
ASTRA_FIXED_TWO_VENUE_KIND_MODEL_AS_FINAL_TAXONOMY
ASTRA_FIVE_SECTION_LIMIT_AS_FINAL_PLATFORM_BOUND
ASTRA_UNVERIFIED_LIVE_READ_PATH
ASTRA_ONE_SESSION_TEST_DEPTH_AS_RELEASE_GATE
```

The following should **not** be preserved from A merely because A is mature:

```text
OPTIONAL_HIVE_PREMISE_WITHOUT_REEXAMINATION
UTILITARIAN_STUDIO_CHROME_AS_A_DESIGN_CONSTRAINT
IMPLEMENTATION_TERMINOLOGY_IN_ORDINARY_PATRON_UI
SEPARATE_EVENT_AND_COMMUNITY_MODELS_IF_A_LINKED_SOCIAL_OBJECT_IS_BETTER
```

# F. Recommended next external experiment

Do not immediately implement the synthesis ledger.

Run a small **blind, task-based comparative user study** first.

### Operator track

Recruit venue operators/nontechnical business users. Counterbalance which implementation they encounter first. Ask them to complete equivalent tasks without coaching:

1. understand what the product is;
2. change brand/first impression;
3. update an event including time;
4. update a menu/service item;
5. understand what is draft versus visitor-visible;
6. identify whether an action would publish/sign on Hive;
7. preview mobile;
8. recover from one intentionally invalid edit.

Measure:

- task completion;
- time to completion;
- wrong turns;
- assistance requests;
- confidence about what will become public;
- confidence about what requires signing;
- perceived visual/product quality.

### Patron track

Use matched venue experiences and ask patrons to:

1. find today's/next event;
2. find menu/hours/location;
3. understand the community proposition;
4. join/share/support through a safe simulation;
5. distinguish Support from sending money;
6. review a payment simulation and state what would become public/irreversible;
7. move between two venues with the same identity.

Measure comprehension and trust, not preference alone.

### Blindness rule

Call the implementations A/B or use neutral names. Do not tell participants which was built by the long-running project versus Astra.

### Decision rule

Use the study to decide which synthesis candidates have demonstrated human value before altering canonical HiVenues.
