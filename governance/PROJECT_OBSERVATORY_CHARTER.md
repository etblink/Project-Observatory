# Project Observatory Charter

Version: 0.1.0
Status: METHOD_FROZEN

## Purpose

Project Observatory is a read-only cross-project reconstruction layer. Its purpose is to record exact canonical state, claim/evidence relationships, dependencies, residual uncertainty, and external decision triggers without silently changing the projects it observes.

The initial observed set is:

- Nested Fibrational Cosmology (NFC)
- Foundational Convergence Program (FCP)
- PGH
- HiVenues

## Governing boundary

The Observatory is descriptive with respect to observed projects. It does not supersede, reinterpret, repair, or modify their canonical scientific, experimental, governance, or product state.

An Observatory finding is not automatically a finding of an observed project. Any proposed scientific correction, adversarial audit, repository repair, or product change must be opened under the governance of the affected project as a separately authorized operation.

## Read-only reconstruction rule

Canonical reconstruction must begin from public repository state and exact repository identities where available. During reconstruction:

1. do not mutate an observed repository;
2. do not repair inconsistencies while discovering them;
3. record discrepancies in the discrepancy docket;
4. distinguish canonical artifacts from local, candidate, superseded, historical, or unverified material;
5. bind material conclusions to exact repository, branch/ref, commit, and source path where possible;
6. do not use memory as a substitute for canonical verification when the repository can answer the question.

## Epistemic object

The core Observatory relation is:

`Claim -> Canonical source -> Status -> Evidence -> Challenges survived -> Dependencies -> Residual uncertainty -> What would change our mind`

Not every project is scientific. For product or operational projects, `claim` may instead represent a material state assertion, architectural decision, quality assertion, release gate, or blocker.

## Project states

Project-level state must use one of:

- ACTIVE
- BLOCKED_EXTERNAL
- WAITING_FOR_EVIDENCE
- FROZEN
- READY_FOR_NEXT_OPERATION
- SUPERSEDED
- DORMANT
- UNKNOWN

A project may carry a secondary note, but the primary state must not be invented to create apparent progress.

## Dependency classes

Dependencies must be classified as:

- HARD: downstream state cannot be validly advanced without the upstream condition or result;
- SOFT: upstream information may materially inform downstream interpretation or prioritization but is not logically required;
- CONTEXTUAL: useful context with no demonstrated load-bearing effect;
- NONE: an apparent relationship was checked and found non-load-bearing;
- UNKNOWN: relationship not yet adjudicated.

Dependencies must not be inferred merely because projects concern related subject matter.

## Uncertainty and information gain

The Observatory may rank unresolved questions for later target selection, but it must separate:

- uncertainty: how unresolved the proposition is on present evidence;
- downstream leverage: how many material conclusions depend on it;
- outcome divergence: how differently the program would proceed under plausible alternative outcomes;
- tractability: whether a bounded test or audit can resolve it.

No single combined numeric score is required in v0.1. Qualitative ranks must be justified in text.

The purpose of this register is target selection, not rhetorical scoring.

## Adversarial-audit firewall

No new adversarial NFC audit may be selected as part of canonical reconstruction itself.

The sequence is:

1. reconstruct canonical state;
2. build dependency relationships;
3. build uncertainty/information-gain register;
4. freeze an Observatory snapshot;
5. only then select a candidate adversarial target;
6. preregister the adversarial audit before executing it.

The audit must permit outcomes including survival, weakening, underdetermination, repair requirement, or downstream reconsideration. Passing is not defined as the success condition.

## External-trigger discipline

If progress genuinely depends on an external event, record the dependency rather than manufacturing substitute work. Examples include hardware arrival, awaited evidence, publication, experimental completion, or a deliberately deferred model run.

## HiVenues Astra quarantine

The independent GPT-6 Astra greenfield HiVenues challenge is intentionally isolated from the existing HiVenues implementation. Until that challenge is complete, the Observatory may record that the experiment exists and is deferred, but must not feed existing HiVenues implementation details into that independent challenge or use unfinished Astra work as canonical evidence about the existing project.

## Supersession discipline

Historical or superseded artifacts may remain important evidence. They must be labeled as historical/superseded and must not silently override a later canonical artifact.

If two apparently canonical artifacts conflict, record the conflict before choosing a resolution. The Observatory itself may identify which source appears controlling only when that follows from explicit project governance or exact repository history; otherwise status remains unresolved.

## Snapshot discipline

A frozen Observatory snapshot must bind:

- Observatory commit identity;
- observed repository/ref/commit identities used;
- project records;
- dependency register;
- uncertainty register;
- discrepancy docket;
- external triggers.

A later snapshot may supersede an earlier one, but must not rewrite its provenance.

## Initial operation boundary

`PROJECT_OBSERVATORY_V0_1` begins with method freeze only. No scientific adjudication, product modification, experiment execution, or observed-repository mutation is authorized by this charter.
