# Project Observatory Branch Retention Audit V0.1

Status: `COMPLETE__MANUAL_DELETION_GUIDANCE_ONLY`

Audit basis: exact 350-branch inventory observed on 2026-09-12 before creation of the v0.4 refresh/snapshot refs.

This audit does **not** delete branches. It classifies the original 350 refs for safe manual cleanup while preserving accepted scientific/provenance history.

## 1. Controlling result

```text
ORIGINAL_BRANCH_COUNT = 350

PRESERVE_FROM_ORIGINAL_350 = 123
SAFE_TO_DELETE_FROM_ORIGINAL_350 = 227

CHECKSUM = 123 + 227 = 350
```

The controlling retention principle is:

> Preserve every accepted-history anchor and every unfinished operation. Delete lifecycle scaffolding only when the accepted endpoint ref retains the preregistration/execution ancestry.

A representative lifecycle was verified directly:

```text
research/...-prereg-v0.1
    -> research/...-v0.1
    -> adjudication/...-acceptance-v0.1
```

For `nfc-ns-common-state-completion-route-comparison`, the acceptance commit `162e9b856ad5aec11b5e965f74737bb03310d556` has execution `d11194423839668d87e555791fc2b77a17cae40a` as parent, and that execution has preregistration `2abe4f1542342bb1267deee64d0f550feba418d6` as parent.

The two audit lifecycle edge cases without a separate execution branch were also checked:

- `audit/nfc-physical-history-selection-prereg-v0.1` tip `89c799c2...` is the direct parent of acceptance `cde62683...`.
- `audit/nfc-scc-recursivity-selector-prereg-v0.1` tip `d687f962...` is the direct parent of acceptance `2e04c688...`.

By contrast, acceptance refs cannot be treated as redundant with the current snapshot/U003 lineage. A representative historical acceptance `f79271c5...` and U003 acceptance `15dde757...` are genuinely diverged, with merge base at Project Observatory `main@1a8cad05...`.

Therefore all `adjudication/*` refs are retained in this cleanup pass.

---

## 2. PRESERVE — 123 branches from the original 350

### 2.1 All accepted adjudication anchors — 117

```text
PRESERVE: adjudication/*
COUNT = 117
```

Do **not** delete any branch beginning with:

```text
adjudication/
```

Reason: these are accepted-operation endpoint refs, and the accepted histories are distributed across divergent lineages rather than all being ancestors of one current branch.

A later separately governed consolidation could merge/archive these histories and reduce this count, but that has not yet been done.

### 2.2 Current Observatory adversarial audit anchors — 2

Preserve exactly:

```text
audit/obs-u002-nfc-ls2-source-forcing
audit/obs-u003-globalization-obstruction
```

These are the dedicated accepted audit lineages for OBS-U002 and OBS-U003.

### 2.3 Default branch — 1

Preserve:

```text
main
```

`main` is provenance-divergent/stale relative to the newest snapshot line, but deleting or rewriting the default branch is outside this cleanup authorization.

### 2.4 Frozen snapshot refs already present in the original 350 — 2

Preserve:

```text
snapshot/project-observatory-v0.2
snapshot/project-observatory-v0.3
```

These are intentional frozen portfolio boundaries and useful audit landmarks.

### 2.5 One unfinished preregistered research operation — 1

Preserve:

```text
research/nfc-ns-internal-control-premise-minimality-prereg-v0.1
```

Tip at audit time:

```text
de1364024b201fd6c3674e4db4dc9048ad7d36a2
```

Commit message:

```text
Preregister NFC NS internal control premise minimality gate
```

No matching completed execution/acceptance ref exists in the 350-branch inventory. Deleting it would discard the only named ref for an unfinished preregistered operation. It may be deleted only after a separate decision explicitly abandons or supersedes that operation.

### Preserve checksum

```text
117 adjudication
+ 2 OBS audit anchors
+ 1 main
+ 2 frozen snapshots
+ 1 unfinished preregistration
= 123 PRESERVE
```

---

## 3. SAFE TO DELETE MANUALLY — 227 branches from the original 350

Deletion safety here assumes the 123 preserve refs above remain intact.

### 3.1 Completed research lifecycle refs — 208

Delete **every** branch under:

```text
research/
```

**except**:

```text
research/nfc-ns-internal-control-premise-minimality-prereg-v0.1
```

Census:

```text
TOTAL research/* = 209
UNFINISHED preserve exception = 1
SAFE_DELETE research/* = 208
```

The 208 deletable research refs consist of completed preregistration/execution scaffolding for operations whose accepted endpoints are retained under `adjudication/*`.

This includes both ordinary paired lifecycles (`*-prereg-v0.1` plus `*-v0.1`) and the small number of execution-only/special-named research refs whose accepted adjudication branch is present.

### 3.2 Legacy pre-OBS audit scaffolding — 16

The following sixteen refs are safe to delete because their accepted endpoint refs are retained under `adjudication/*`:

```text
audit/nfc-actualization-generator-authority-prereg-v0.1
audit/nfc-actualization-generator-authority-v0.1

audit/nfc-actualization-new-physics-design-space-prereg-v0.1
audit/nfc-actualization-new-physics-design-space-v0.1

audit/nfc-actualization-source-certificate-prereg-v0.1
audit/nfc-actualization-source-certificate-v0.1

audit/nfc-continuation-defect-projective-consistency-prereg-v0.1
audit/nfc-continuation-defect-projective-consistency-v0.1

audit/nfc-equal-child-authority-deterministic-counterpart-prereg-v0.1
audit/nfc-equal-child-authority-deterministic-counterpart-v0.1

audit/nfc-internal-observation-actualization-prereg-v0.1
audit/nfc-internal-observation-actualization-v0.1

audit/nfc-ns-force-representability-source-forcing-prereg-v0.1
audit/nfc-ns-force-representability-source-forcing-v0.1

audit/nfc-physical-history-selection-prereg-v0.1
audit/nfc-scc-recursivity-selector-prereg-v0.1
```

Do **not** apply this rule to `audit/obs-u002-*` or `audit/obs-u003-*`; those are preserve refs.

### 3.3 Superseded routing/refresh/selection refs — 3

Delete:

```text
refresh/project-observatory-v0.2
routing/observatory-v0.2-next-target-selection
selection/obs-u003-globalization-obstruction
```

Reasons:

- `refresh/project-observatory-v0.2` is superseded by the frozen v0.2/v0.3 snapshot lineage and the current v0.4 refresh.
- `routing/observatory-v0.2-next-target-selection` is an intermediate routing ref rather than an accepted-history anchor.
- `selection/obs-u003-globalization-obstruction` is retained in ancestry by the U003 preregistration/execution/acceptance audit lineage.

### Delete checksum

```text
208 completed research refs
+ 16 legacy audit scaffolding refs
+ 3 superseded routing/refresh/selection refs
= 227 SAFE_TO_DELETE
```

---

## 4. Manual deletion order

For lowest risk, delete in this order:

1. the 3 superseded routing/refresh/selection refs;
2. the 16 explicit legacy `audit/nfc-*` refs above;
3. `research/*-prereg-v0.1` branches except the one unfinished exception;
4. remaining completed `research/*` execution/special refs.

After cleanup of the **original 350-ref census**, exactly 123 of those original refs should remain.

The v0.4 refresh/snapshot operation creates additional new refs after this census. Those new v0.4 refs should be preserved and are not part of the `350 -> 123` checksum.

---

## 5. What not to infer

Branch deletion removes refs, not the meaning or acceptance status of artifacts retained in reachable commits. But Git history reachability matters: a commit reachable only through a deleted branch may eventually become difficult or impossible to recover.

That is why this audit is deliberately conservative about `adjudication/*`.

Do not delete:

- `adjudication/*`;
- `audit/obs-u002-nfc-ls2-source-forcing`;
- `audit/obs-u003-globalization-obstruction`;
- `main`;
- frozen snapshot refs;
- the unfinished internal-control preregistration;
- the new v0.4 refresh/snapshot refs created after the 350-branch census.

No scientific conclusion depends on keeping redundant prereg/execution branch **names** once their accepted endpoint ref retains the commit ancestry.

---

## 6. Future optimization

The repository can be reduced much further than 123 branches, but not safely by branch-name pruning alone.

The next provenance-hardening operation, if desired, should construct one or a small number of durable **accepted-history archive anchors** that make every accepted `adjudication/*` tip reachable from a consolidated archival ref (or another explicit durable mechanism). Only after verifying that coverage should the 117 adjudication branches be candidates for deletion.

That consolidation is intentionally not performed by this audit.
