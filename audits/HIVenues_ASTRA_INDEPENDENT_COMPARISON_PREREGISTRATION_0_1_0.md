# HiVenues ↔ Independent GPT-6 Astra Greenfield Comparison — Preregistration 0.1.0

## Purpose

This audit asks what can be learned from two independently developed realizations of the same founding HiVenues idea before either realization is allowed to influence the other.

The audit is read-only with respect to both source implementations. It may create comparison records only in Project Observatory. It may not merge, copy, port, refactor, or recommend implementation changes until the comparative adjudication is complete.

## Frozen inputs

### A — existing canonical HiVenues

```text
REPOSITORY = etblink/HiVenues
CANONICAL_REF = main
CANONICAL_COMMIT_AT_OPEN = 9351655112a25fd8a1d115d8c402534726b1e035
```

Canonical `main` is the controlling implementation input. An in-progress branch or PR may be inspected only to describe separately labeled `PIPELINE_DELTA` evidence if it is demonstrably the project's current active continuation. Pipeline evidence cannot silently replace canonical evidence or improve the canonical score.

### B — independent Astra greenfield result

```text
BRANCH = independent/greenfield
COMMIT = e7a03c1aa7e5b8a30e7e8a77b3d927f9e168daf2
TREE = 9810d4d44fae5bb43bfd28ce8a350306307aa22c
SOURCE_ZIP_SHA256 = 84e1ce7b68da0c58dbd7ab1ed40c1feb5efeaa4cea2172489c60e10b89632992
GIT_BUNDLE_SHA256 = f8fd2f434f22ec77bf34c8704e473d75173862556a2087d58985dc07ad3b2177
HANDOFF_SHA256 = aed2985e814a49ec5c6b73b66368164d979863f2247d309ef4c2aa667a403185
```

The Astra result is frozen and may not be modified during adjudication.

## Independence premise

The comparison treats Astra B as an independent product interpretation because its frozen handoff states that it did not inspect existing HiVenues source, screenshots, issues, architecture, or implementation decisions before freeze, and the preserved Git/source artifacts agree with the frozen identities. The comparison does not infer stronger independence than the available provenance supports.

## Core question

For each material design or implementation choice, which result is better supported under the founding HiVenues objective, and where did the two independent lines converge?

The purpose is not to declare a single overall winner. The purpose is to identify:

1. robust convergence that independently survived two design histories;
2. superior divergent ideas worth later synthesis;
3. tradeoffs where different choices serve different goals;
4. differences caused mainly by maturity/time rather than product insight;
5. gaps that neither implementation adequately solves.

## Verdict vocabulary

Each dimension receives one controlling disposition:

```text
EXISTING_WINS
ASTRA_WINS
COMPLEMENTARY
INSUFFICIENT_EVIDENCE
```

Optional secondary flags:

```text
INDEPENDENT_CONVERGENCE
MATURITY_ASYMMETRY
EVIDENCE_ASYMMETRY
PRODUCTION_GAP
SYNTHESIS_CANDIDATE
DO_NOT_PORT
```

No numerical aggregate score will be used. A weighted total could hide qualitatively important differences and would over-reward the much longer-lived implementation on maturity dimensions.

## Preregistered dimensions

D1. Product thesis and fidelity to the founding idea

D2. Studio information architecture and interaction model

D3. Generated-site visual quality and venue credibility

D4. Hive-native architecture and whether Hive is structurally essential

D5. Translation of Hive concepts for ordinary users

D6. Venue generalization / avoidance of a single-template product

D7. Events, community, and persistent social-object model

D8. Identity, signing, authority, transaction safety, and mutation clarity

D9. Media, menus, reservations, tickets, and ordinary business workflows

D10. Responsive/mobile experience

D11. Accessibility and non-pointer interaction

D12. State model, persistence, releases, undo/redo, and authoring safety

D13. Engineering/test/reproducibility quality

D14. Production readiness and operational completeness

## Cross-cutting questions

For every dimension, adjudication must also ask:

- Did both implementations independently converge on the same idea?
- Is the difference primarily conceptual or merely maturity/time?
- Does one implementation solve a problem the other has not recognized?
- Is there evidence from actual browser behavior/tests rather than prose alone?
- Would removing Hive leave the product substantially intact?
- Does the choice help a venue operator or patron without requiring blockchain expertise?
- Is the choice safe and honest at signing, financial, and irreversible boundaries?

## Evidence hierarchy

Prefer, in order:

1. executable source and tests;
2. actual browser screenshots / captured behavior;
3. frozen verification logs and exact provenance;
4. repository-native product/state documentation;
5. handoff prose;
6. inference.

Inference must be labeled as such.

## Fairness rules

- Do not penalize Astra merely for lacking years of accumulated implementation where its architectural seam is sound and the missing work is explicitly acknowledged.
- Do not reward Astra merely for novelty or visual freshness.
- Do not penalize existing HiVenues for iterative complexity if that complexity purchases real tested capability.
- Do not reward existing HiVenues merely because it has more files, issues, tests, or history.
- Compare product ideas separately from maturity.
- Claims about current existing HiVenues must be bound to commit/ref evidence.
- Claims about Astra must be bound to the frozen tree, bundle, ZIP, screenshots, or handoff.

## Visual adjudication

Visual comparison must distinguish:

```text
STUDIO_PRODUCT_QUALITY
GENERATED_VENUE_QUALITY
MOBILE_QUALITY
VENUE_DIVERSITY
VISUAL_SYSTEM_FLEXIBILITY
```

Screenshots are evidence of observed presentation, not proof of all interaction behavior.

## Synthesis firewall

Before the final adjudication is frozen:

```text
NO_CODE_COPY_BETWEEN_A_AND_B
NO_EXISTING_REFACTOR_BASED_ON_ASTRA
NO_ASTRA_MUTATION
NO_NEW_PRODUCT_REQUIREMENTS_DERIVED_FROM_COMPARISON
NO_WINNER_BY_AGGREGATE_SCORE
```

After adjudication, a separately authorized convergence operation may create a synthesis plan from findings marked `SYNTHESIS_CANDIDATE`.

## Required outputs

1. exact source-state binding;
2. dimension-by-dimension evidence matrix;
3. independent-convergence ledger;
4. divergence/adjudication record;
5. maturity-asymmetry ledger;
6. synthesis-candidate ledger, without implementation;
7. overall findings and recommended next experiment/user test;
8. exact comparison handoff.

## Stop condition

Stop after freezing the read-only adjudication and handoff. Do not modify either implementation as part of this audit.
