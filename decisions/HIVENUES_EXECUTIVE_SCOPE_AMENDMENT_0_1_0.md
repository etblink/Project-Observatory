# HiVenues — Executive Scope Amendment 0.1.0

## Status

```text
DECISION_CLASS = EXECUTIVE_SCOPE_AMENDMENT
DECISION_OWNER = USER / PROJECT EXECUTIVE
DECISION_DATE_LOCAL = 2026-09-12
PARENT_DECISION = decisions/HIVENUES_EXECUTIVE_PRODUCT_ADJUDICATION_0_1_0.md
IMPLEMENTATION_AUTHORIZATION = NO
SOURCE_PROJECT_MUTATION = NONE
ASTRA_RESULT_MUTATION = NONE
```

This amendment clarifies and broadens the immediately preceding executive product doctrine.

The prior record used **place**, **venue**, and **business** language too narrowly. The product is not limited to brick-and-mortar businesses.

The governing scope is broader:

> **HiVenues is a branded Hive-native social/business/community frontend platform for physical venues, creators, performers, public personalities, groups, and brands. The website/Studio exists to make that Hive-native community presence usable, beautiful, safe, and operator-manageable.**

This amendment does not reverse Decision B. It generalizes its subject.

---

## 1. Product scope

A first-class HiVenues deployment may represent, among other archetypes:

- bars, restaurants, clubs, stores, studios, workshops, galleries, theaters, and other physical venues;
- streamers and live creators;
- influencers and public personalities;
- comedians;
- bands, musicians, DJs, and other performers;
- podcasters and media creators;
- artists and creative collectives;
- clubs, communities, and membership groups;
- events, recurring shows, tours, and festivals;
- brands and organizations whose community identity is not tied to one physical location.

A physical address is therefore **not** a universal HiVenues requirement.

---

## 2. Generalized product definition

Replace the too-narrow formulation:

```text
PLACE_FIRST_EXPERIENCE
+
HIVE_FOUNDATIONAL_INFRASTRUCTURE
+
VENUE_NATIVE_TRANSLATION
=
HIVENUES
```

with:

```text
HOST_IDENTITY_FIRST_EXPERIENCE
+
HIVE_FOUNDATIONAL_INFRASTRUCTURE
+
DOMAIN_NATIVE_TRANSLATION
=
HIVENUES
```

where `HOST_IDENTITY` may be a physical place, creator, performer, group, brand, or event-oriented identity.

The governing product definition becomes:

> **HiVenues gives a host identity its own purpose-built Hive frontend. The host supplies the brand, context, vocabulary, content model, audience relationship, commercial or community goals, and visual experience. Hive supplies portable identity, community, publishing, social interaction, durable public content, rewards, and economic primitives. HiVenues translates those primitives into the language of that host domain rather than exposing a generic blockchain application.**

---

## 3. Terminology consequence

`Venue` remains a valid and historically central product archetype, but must not become a schema or UI assumption that excludes non-place hosts.

Future doctrine reconciliation should distinguish:

```text
PRODUCT_NAME = HIVENUES
VENUE = ONE HOST ARCHETYPE
HOST = GENERAL PRODUCT-SCOPE CONCEPT
```

The exact canonical schema term for `HOST` is **not** frozen by this amendment. A later source-project architecture operation may choose a better stable term if `host` is ambiguous.

Existing venue-specific production compatibility surfaces must not be renamed merely for conceptual purity.

---

## 4. Archetype implications

### Physical venue

Core semantic pressure may include:

- location, hours, menu/services, reservations, tickets, physical events, payments, visit guidance;
- persistent community around recurring real-world gatherings.

### Streamer / live creator

Core semantic pressure may include:

- live/next-stream state;
- stream schedule;
- episodes/clips/highlights;
- community discussion;
- supporter relationships;
- collaborations;
- Hive-native posts/rewards/support.

The product must not require an address, menu, or `Visit` information architecture.

### Influencer / creator / public personality

Core semantic pressure may include:

- identity/about;
- latest work/content;
- campaigns/projects;
- social/community interaction;
- memberships/support;
- collaborations and external channels.

### Comedian / performer

Core semantic pressure may include:

- tour/show dates;
- ticket actions;
- clips/specials;
- venue-specific event pages;
- durable discussion around shows;
- merchandise/support/community.

### Band / musician / DJ

Core semantic pressure may include:

- releases;
- music/media;
- tour/show dates;
- ticketing;
- fan community;
- posts/stories;
- support/merchandise/economic actions.

### Brand / organization / group

Core semantic pressure may include:

- products/services/projects;
- announcements;
- campaigns;
- community;
- events;
- support/member participation;
- organization-specific calls to action.

These archetypes are product pressures, not frozen page templates.

---

## 5. What remains universal

The broadened scope strengthens, rather than weakens, the following universal doctrines:

1. **Hive is foundational infrastructure.**
2. **The host identity is primary in the experience.**
3. **Hive primitives are translated into domain-native language.**
4. **Public/read-only consumption should not require sign-in.**
5. **Portable Hive identity remains the social identity.**
6. **Semantic authoring remains preferred over free-form arbitrary layout/code authority.**
7. **One responsive semantic source remains the target.**
8. **The real renderer remains preview authority.**
9. **Signing and value-moving consequences remain explicit and least-privileged.**
10. **Accessibility, provenance, reproducibility, and production safety remain release requirements.**

---

## 6. Required correction to the future implementation sequence

The previously selected next operation remains:

```text
HIVENUES_PRODUCT_DOCTRINE_RECONCILIATION_V0_1
```

but its scope must now also prevent a second form of product drift:

```text
DRIFT_A = GENERIC_NON_HIVE_WEBSITE_BUILDER
DRIFT_B = BRICK_AND_MORTAR_ONLY_PLATFORM
```

The reconciliation must therefore ensure that future source/domain architecture can support both:

```text
PHYSICAL_PLACE_HOSTS
AND
NON_PHYSICAL_CREATOR_PERFORMER_BRAND_HOSTS
```

without creating separate products or a collection of hard-coded archetype forks.

Before later implementation is considered complete, at least one non-physical reference archetype should become a first-class qualification target alongside the physical venue references.

Recommended pressure set for later design work:

```text
PHYSICAL_VENUE_REFERENCE
CREATOR_STREAMER_REFERENCE
PERFORMER_BAND_OR_COMEDIAN_REFERENCE
```

The exact reference identities and fixtures are deferred.

---

## 7. Event/social-object generalization

The adopted persistent social-object direction should also generalize beyond physical events.

Examples include:

- a bar's live-music night;
- a comedian's tour date;
- a band's show;
- a streamer's scheduled live stream;
- a creator's premiere or launch;
- a brand/community AMA;
- a recurring online gathering.

The common semantic is not simply `physical event`.

It is:

> **a time-bounded or recurring shared occurrence whose business/content facts may change while its accumulated Hive social identity can persist.**

This generalization must be considered before the event-social-object contract is frozen.

---

## 8. Final amended disposition

```text
HIVENUES_PRIMARY_IDENTITY = BRANDED_HIVE_NATIVE_FRONTEND_FOR_HOST_COMMUNITIES
SUPPORTED_HOST_CLASS = PHYSICAL_VENUE__CREATOR__PERFORMER__GROUP__BRAND__EVENT_ORIENTED_IDENTITY
BRICK_AND_MORTAR_REQUIREMENT = NO
PHYSICAL_ADDRESS_REQUIREMENT = NO
HIVE = FOUNDATIONAL_INFRASTRUCTURE
HOST_IDENTITY = EXPERIENCE_PRIMARY
DOMAIN_NATIVE_TRANSLATION = REQUIRED_DIRECTION
COMMUNITY = FOUNDATIONAL_PRODUCT_DIMENSION
PUBLIC_SIGN_IN_REQUIREMENT = NO
SEMANTIC_STUDIO = REAFFIRMED
FREEFORM_PAGE_BUILDER = REJECTED
NON_PHYSICAL_REFERENCE_ARCHETYPE = REQUIRED_FOR_FUTURE_QUALIFICATION
EVENT_SOCIAL_OBJECT_DIRECTION = GENERALIZE_BEFORE_FREEZE
EXISTING_TYPED_AUTHORING_ENGINE = PRESERVE
EXISTING_SECURITY_AND_PRODUCTION_DISCIPLINE = PRESERVE
NEXT_OPERATION = HIVENUES_PRODUCT_DOCTRINE_RECONCILIATION_V0_1
```

The governing aim is broader than making a physical venue Hive-native.

The governing aim is to let **a place, creator, performer, group, or brand become its own coherent Hive-native community experience without forcing its audience to think like blockchain users.**
