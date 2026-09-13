# HiVenues ↔ Independent GPT-6 Astra — Evidence Matrix 0.1.0

## Verdict vocabulary

```text
EXISTING_WINS
ASTRA_WINS
COMPLEMENTARY
INSUFFICIENT_EVIDENCE
```

No aggregate numerical score is used.

## Matrix

| ID | Dimension | Disposition | Secondary flags | Controlling reason |
| --- | --- | --- | --- | --- |
| D1 | Product thesis / founding-idea fidelity | **ASTRA_WINS** | SYNTHESIS_CANDIDATE | Existing PM1 deliberately makes Hive Community optional and allows a complete public HiVenue with no Hive activation. Astra keeps Hive identity/social/economic state structurally foundational while translating it into venue language. Under the founding challenge's controlling question, Astra is the closer interpretation. |
| D2 | Studio information architecture / interaction model | **COMPLEMENTARY** | INDEPENDENT_CONVERGENCE, SYNTHESIS_CANDIDATE | Both independently converge on semantic structure + real rendered canvas + contextual inspector rather than an arbitrary free-form builder. Existing wins transaction/state rigor and deep stable-resource editing; Astra wins shell coherence, task-oriented top-level navigation and visual product polish. |
| D3 | Generated-site visual quality / venue credibility | **ASTRA_WINS** | SYNTHESIS_CANDIDATE | Lowlight and Forma read more like premium 2026 venue products than the current canonical v2 reference renders. Existing references are credible and much broader, but the current visual artifact still looks more systematized/template-like in several archetypes. |
| D4 | Hive-native architecture / Hive structurally essential | **COMPLEMENTARY** | INDEPENDENT_CONVERGENCE, MATURITY_ASYMMETRY, SYNTHESIS_CANDIDATE | Astra is conceptually more Hive-native: every venue binds community/account identity, events bind discussion identity and social/economic actions become explicit intents. Existing has far deeper real Hive integration, production Keychain self-signing, community, Threads, profiles, payments, onboarding and authority governance, but v2 makes Hive optional. |
| D5 | Translation of Hive for ordinary users | **ASTRA_WINS** | SYNTHESIS_CANDIDATE | Astra consistently translates operations into venue-native language such as Join the room, Share a moment, Support and Your pocket, while exposing authority/consequence at review time. Existing has strong safe boundaries but more platform-facing vocabulary and a more visibly separate Community/Hive product layer. |
| D6 | Venue generalization / avoiding one-template product | **EXISTING_WINS** | INDEPENDENT_CONVERGENCE, MATURITY_ASYMMETRY | Existing proves a broader semantic factory across Fourth Street, Juniper, restaurant and live-music references, multiple pages, shared resources and multiple hero/list/gallery recipes. Astra proves meaningful variation with Lowlight and Forma but only two venue kinds and five section kinds. |
| D7 | Events, community and persistent social-object model | **ASTRA_WINS** | SYNTHESIS_CANDIDATE | Astra gives events stable Hive discussion references and links venue stories back to event identity; editing schedule data does not mutate discussion identity. Existing has stronger event/resource machinery and rich community surfaces, but canonical v2 evidence does not bind event identity and community discussion as one durable object. |
| D8 | Identity, signing, authority, transaction safety | **EXISTING_WINS** | INDEPENDENT_CONVERGENCE, MATURITY_ASYMMETRY | Both distinguish Posting from Active consequences, avoid server custody of patron keys and use explicit review boundaries. Existing additionally has real Keychain self-signing, production deployment gates, exact least-privilege audits, payments/onboarding/moderation and live operational evidence. Astra's signer is intentionally simulation-only. |
| D9 | Media, menus, reservations, tickets, ordinary business workflows | **COMPLEMENTARY** | MATURITY_ASYMMETRY, SYNTHESIS_CANDIDATE | Existing has a richer semantic resource model, managed media, shared-resource lifecycle and menu authoring, but canonical #199 still explicitly lacks ticket/reservation action editing, timestamp editing, general non-Hero media, component recipes and complete archetype journeys. Astra exposes a more complete small operator workflow now—events/times/actions, menus, media and disclosed booking/ticket simulation—but with much shallower resource breadth and no production providers. |
| D10 | Responsive/mobile experience | **COMPLEMENTARY** | INDEPENDENT_CONVERGENCE, EVIDENCE_ASYMMETRY, SYNTHESIS_CANDIDATE | Both use one semantic source/configuration across responsive views. Existing has systematic 390/834/1440 browser geometry, overflow and accessibility evidence across several archetypes. Astra's Lowlight mobile product is visually stronger and uses a clearer mobile-specific navigation composition while retaining the same released configuration. |
| D11 | Accessibility / non-pointer interaction | **EXISTING_WINS** | MATURITY_ASYMMETRY | Existing has explicit WCAG-oriented contracts, non-drag alternatives, repeated pinned-browser Axe/geometry gates and 44px target checks. Astra includes semantic controls, keyboard reordering/focal adjustment, visible focus and reduced-motion styling, but explicitly does not claim a full accessibility certification or broad device audit. |
| D12 | State, persistence, release, undo/redo, authoring safety | **COMPLEMENTARY** | INDEPENDENT_CONVERGENCE, SYNTHESIS_CANDIDATE | Existing has stronger transactional semantics: expected digests, proposal/apply/discard, exact inverse history, durable checkpoint Save/reopen, stale-state rejection and shared-resource consequences. Astra has a clearer product model of autosaved draft vs separately released local snapshot, cross-tab conflict detection and up to 30 undo snapshots. |
| D13 | Engineering, tests and reproducibility | **EXISTING_WINS** | MATURITY_ASYMMETRY | Existing canonical CI passes deterministic Ubuntu/Windows gates, dependency audits, scope classification and pinned-Chromium evidence with extensive source/history oracles. Astra is reproducibly frozen and passes 19 core tests, TypeScript and build, but has one managed environment and no packaged unattended browser suite. |
| D14 | Production readiness / operational completeness | **EXISTING_WINS** | MATURITY_ASYMMETRY | Existing includes an observed production Fourth Street deployment, explicit current/last-good identities, health/readiness, beta Keychain self-signing, active payment/onboarding/moderation capabilities and rollback discipline. Astra explicitly remains a local demonstration with no real auth, broadcast/reconciliation, hosted config, tenant isolation, durable media or deployment. |

## D1 — product thesis

### Existing

Existing PM1 made an explicit product pivot:

```text
PUBLIC_VENUE_SITE = UNIVERSAL
COMMUNITY_CAPABILITY = OPTIONAL
TRANSACTION_CAPABILITY = OPTIONAL_AND_SEPARATELY_PRIVILEGED
VALID_PUBLIC_VENUE_WITH_NO_HIVE = YES
```

This is coherent SaaS architecture and improves generic venue adoption. It is not an accidental absence: it is an explicit decision.

### Astra

Astra's product thesis is:

```text
BUSINESS = AUTHORS_CONTEXT
HIVE = SHARED_IDENTITY + SOCIAL_GRAPH + PUBLIC_CONTENT + ECONOMIC_PRIMITIVES
BUSINESS_OWNS_EXPERIENCE = YES
BUSINESS_OWNS_PATRON_IDENTITY = NO
```

A conventional business shell remains if Hive is removed, but the intended community product does not.

### Adjudication

Because this audit is against the founding HiVenues objective rather than generic venue-SaaS market breadth, Astra wins D1. Existing PM1's progressive-Hive model remains a legitimate product strategy but should be reconsidered during later synthesis rather than silently retained as axiomatic.

## D2 — Studio

### Independent convergence

Both implementations independently selected essentially the same deep authoring geometry:

```text
SEMANTIC_STRUCTURE / OUTLINE
        +
REAL_RENDERED_VENUE_CANVAS
        +
CONTEXTUAL_INSPECTOR
```

Both reject arbitrary DOM/CSS authoring and both treat the public renderer as the preview authority.

### Existing advantage

Existing adds:

- stable page/component/resource identity;
- explicit proposal state;
- Apply / Discard;
- Undo / Redo with exact inverse;
- expected-digest and stale-state rejection;
- resource-reference editing;
- shared-consumer consequences;
- explicit durable Save and exact reopen;
- no browser-provided source pointers/objects.

### Astra advantage

Astra adds a more productized operator shell:

- Design / Events / Menu & services / Community / Media as task-oriented workspaces;
- more compact semantic language;
- direct canvas selection;
- clearer separation of venue configuration from actions that would sign to Hive;
- visually stronger hierarchy and preview framing.

Neither side dominates all of D2.

## D3 — visual quality

Observed canonical-A references demonstrate real differentiation:

- Fourth Street: immersive real-photo hospitality;
- Harbor & Hearth: cream/editorial restaurant;
- Juniper: workshop/program identity;
- Northline: poster/live-music identity.

A's own PM4 history acknowledges that the Studio shell remained visually utilitarian and that a later idealized-vs-current convergence operation was still planned.

Observed B references demonstrate a higher current polish ceiling:

- Lowlight presents a convincing premium listening-bar identity with high-quality photographic hierarchy, editorial type and integrated community language;
- Forma materially changes typography, composition, palette, imagery and business vocabulary while using the same schema/renderer.

The B Studio also looks closer to commercial creative software than A's current canonical Studio.

## D4 — Hive architecture

### Convergence

Both agree on:

- portable Hive identity rather than a proprietary patron identity;
- public reads before requiring sign-in;
- explicit signer/review boundaries for writes;
- authority-sensitive operations;
- community/social state should not be silently duplicated as proprietary truth;
- transaction effects must be distinguishable from configuration edits.

### Divergence

A v2 makes Community a capability that may be absent. B treats Hive community/account identity as intrinsic to the HiVenue model.

A's mature v1/production surface proves much deeper real Hive behavior than B; B's stronger conceptual coupling does not erase that implementation asymmetry.

## D5 — ordinary-user translation

B's language systematically starts from human intent and reveals protocol semantics only at the consequence boundary. Examples:

```text
Share a moment -> comment/post
Add to the conversation -> reply
Support -> weighted vote
Join the room -> community subscription
Your pocket, everywhere -> wallet/activity
Review payment -> Active HBD transfer intent
Room to participate -> RC/voting capacity explanation
```

A has made major venue-first progress, but its historical/public product still exposes Community, Threads, Pay, Hive sign-in and other platform concepts more directly. Its PM1 architecture itself identifies this coupling as something to reduce.

## D6 — generalization

A has stronger proof of generality because one semantic engine already drives at least four materially different PM4 references and multiple page/resource families. Its design contract intentionally requires constrained variance across bar, workshop, premium restaurant and live-music archetypes.

B's Lowlight/Forma pair is a strong minimal proof that its design is not one hard-coded venue, but it does not yet match A's archetype and semantic-resource breadth.

## D7 — event/social model

B's event object carries stable:

```text
discussion.author
discussion.permlink
```

and community posts may carry `eventId`. Its event editor visibly states that Hive discussion identity remains stable while schedule/content are edited.

This is a stronger synthesis of physical event and portable social context than A currently demonstrates. A has robust shared event resources, derived event-detail pages and rich Hive community behavior, but they remain more parallel than intrinsically linked.

## D8 — identity/signing safety

B independently got important boundaries right:

- `comment`, `vote`, `custom_json`, `claim_reward_balance`, and `transfer` become explicit reviewed intents;
- Posting and Active are distinct;
- HBD is described as real money;
- SimulationSigner cannot broadcast or hold keys;
- a production signer seam must reconcile actual confirmation rather than relabel a simulation.

A goes substantially further in evidence and operation: real Keychain patron signing, server-key minimization, explicit zero patron private-key custody, narrowly bounded future machine Posting credential, production capability gates and exact deployment/recovery identities.

## D9 — business workflows

The comparison exposes a useful opposite strength.

A has a significantly more rigorous platform/domain model and shared resources. B has a smaller but more immediately coherent end-to-end operator product.

A's own canonical #199 record still keeps these gaps visible:

```text
TICKET_RESERVATION_ACTION_EDITING = REMAINING
TIMESTAMP_EDITING = REMAINING
GENERAL_NON_HERO_MEDIA = REMAINING
PER_COMPONENT_RECIPE_EDITING = REMAINING
FULL_FRESH_ARCHETYPE_JOURNEYS = REMAINING
```

B already exposes event times/actions and separate operator tabs for events, menus, community and media, but its provider integrations are simulations/links and its domain is far narrower.

## D10 — responsive/mobile

A provides stronger systematic evidence. Its renderer artifact tests reference sites at three canonical viewports, checks horizontal overflow, navigation geometry, primary touch target size and accessibility findings.

B provides stronger observed mobile product design in the supplied Lowlight capture: venue identity, content hierarchy and a compact bottom navigation are intentionally recomposed for the phone while reading the same released venue configuration.

## D11 — accessibility

A wins because accessibility is both architectural and machine-gated. B has credible accessibility-minded implementation, but its own frozen handoff explicitly records that no complete screen-reader/contrast/device audit was performed.

## D12 — state/release model

A's authoring transaction model is unusually rigorous and worth preserving:

```text
PROPOSE -> REAL_RENDERER_PREVIEW -> APPLY_OR_DISCARD
-> EXACT_UNDO_REDO
-> EXPLICIT_SAVE
-> FRESH_PROCESS_EXACT_REOPEN
```

B's product semantics are clearer to ordinary operators:

```text
DRAFT_AUTOSAVES_LOCALLY
RELEASED_SNAPSHOT_IS_SEPARATE
INVALID_DRAFT_CAN_RECOVER
INVALID_RELEASE_IS_REJECTED
CROSS_TAB_CONFLICT_FAILS_VISIBLE
```

The later synthesis should preserve A's integrity while considering B's draft/release vocabulary and mental model.

## D13 — engineering/reproducibility

B's freeze is valid and reproducible within its declared scope. This audit independently verified the bundle/tree/ZIP correspondence.

A nevertheless has far more adversarial and cross-platform evidence: canonical CI #757 succeeded across seven jobs, and the visual artifact itself packages numerous deterministic/browser suites. This is a maturity win, not evidence that A's product decisions are necessarily better.

## D14 — production readiness

A's repository records a real Fourth Street production deployment with explicit health/readiness, exact deployed source identity, last-good recovery identity, Keychain self-signing and durable payment/onboarding/moderation state.

B explicitly does not claim production readiness. Its live Hive read adapter reached fallback; no real authentication, transaction broadcast, reconciliation, durable hosting/media or production deployment exists.

## Matrix-level conclusion

The comparison does **not** support a single overall winner.

It supports a sharper statement:

```text
ASTRA_B = STRONGER_PRODUCT_THESIS + STRONGER_CURRENT_VISUAL/UX SYNTHESIS
EXISTING_A = STRONGER_PLATFORM_MODEL + STRONGER SAFETY/ENGINEERING + STRONGER PRODUCTION MATURITY
```

The most valuable result is that several architectural choices independently converged while the largest philosophical divergence—Hive optional versus Hive foundational—remained exposed rather than hidden by implementation history.
