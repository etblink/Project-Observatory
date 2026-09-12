# OBS-U009 — NFC Repository Provenance Divergence Audit Preregistration v0.1

Status: `PREREGISTERED`

Selection commit:

```text
68d74abca46552a72585fd161232a1ad3f4f0ca1
```

Audit branch:

```text
audit/obs-u009-nfc-provenance-divergence
```

## 1. Bound question

Can repository-native evidence reconstruct the provenance mechanism by which NFC's theorem-bearing corpus became separated from default `main`, distinguish Git-history discontinuity from scientific-content continuity, determine what can and cannot be established about the human reason for the split, and adjudicate whether the present repository needs additional provenance hardening to prevent canonical-source selection failure?

## 2. Frozen evidence surface

### Project Observatory baseline

```text
SNAPSHOT_V0_4 = 03d4753d7629b02447095db3d63f132f84550d20
OBS_D001 = NFC main vs frozen-canon identity divergence
```

### NFC default publication surface

```text
MAIN = b8587ce3409e34c0dd4e56c61ee585c07798b0e5
MAIN_PARENT = 0f23c285191ab20bf468868940f385068e7e8717
MAIN_MESSAGE = remove
MAIN_TREE = f5d2112d6346b659127d596f1f62a2c7069cdc60
```

### NFC frozen scientific canon

```text
CANON_REF = archive/nfc-canonical-ed3047c2
CANON_COMMIT = ed3047c2cbc0abc34d2549dd27754e4d3d05af78
CANON_TREE = 00ef55ff36d5e9663ca1ef2c9566e2bc1396f973
CANON_PARENT = dc72e0b07ce126d912b5f6ff85b0b5597dfaefeb
```

### Isolated archive root

```text
ARCHIVE_ROOT = d5d88c2e7672b36c9ef7231aa657d967e9feef6b
ARCHIVE_ROOT_TREE = 0b37fc5372d9de960bc5660671e12196c452223b
ARCHIVE_ROOT_PARENTS = 0
ARCHIVE_ROOT_MESSAGE = Baseline snapshot: isolated working copy of NFC corpus as received
ARCHIVE_ROOT_DATE = 2026-07-01T08:16:58Z
```

### Release pointer evidence

```text
DECLARED_RELEASE_TAG = v1.0-canon-rewrite
DECLARED_RELEASE_COMMIT = 716e6fae585251185ffd15775dd923132f16c88e
CURRENT_GIT_TAGS_OBSERVED = physics only
```

## 3. Definitions

`GIT_ANCESTRY_CONTINUITY` means the two audited refs have a shared Git ancestor.

`CONTENT_CONTINUITY` means one or more exact Git blob identities establish byte-for-byte continuity between the pre-strip main corpus and the isolated archive baseline. Representative continuity is not automatically complete-manifest continuity.

`PROVENANCE_MECHANISM` means a repository-evidenced account of the mechanical sequence: source state, re-root/import event, later development, and publication-surface deletion event.

`HUMAN_INTENT` means the reason or policy motivation for the split. Human intent is established only by explicit repository text, not inferred from chronology, branch names, or the word `remove`.

`HARDENING_SUFFICIENT` means the canonical scientific source is both durably anchored and discoverable enough that ordinary repository-default navigation is unlikely to select the wrong theorem-bearing source.

## 4. Required tests

1. Verify exact `main`, its parent, tree, message, and current root contents.
2. Verify exact canon ref, commit, tree, parent, and branch protection state.
3. Test Git ancestry between `main` and canon.
4. Locate the root of the canon lineage and verify whether it is parentless.
5. Establish representative content continuity using exact blob identities spanning at least spine and branch material.
6. Establish the length/direction of the archive lineage from root to frozen canon.
7. Inspect repository-native release/provenance documents for declared tags/commit pointers.
8. Compare declared release anchors with currently existing refs/tags.
9. Inspect default `main` documentation for accurate canonical-source routing.
10. Check whether other current NFC refs descend from the frozen canon, while distinguishing incidental reachability from explicit canonical anchoring.
11. Adjudicate whether current hardening is sufficient without implementing any repair.

## 5. Outcome burdens

### A — divergence fully explained and hardening sufficient

Requires:
- mechanical provenance sequence established;
- human intent explicitly evidenced or unnecessary to canonical-source determination;
- durable explicit canonical anchor exists;
- default navigation clearly routes readers to the theorem-bearing canon;
- no stale/broken release pointer materially weakens provenance.

### B — mechanism and intent established; hardening required

Requires explicit evidence for both mechanical mechanism and human policy intent, plus at least one material discoverability/durability defect.

### C — content continuity and mechanism established; human intent unresolved; hardening required

Requires:
- no common Git ancestry or equivalent discontinuity established;
- isolated re-root/import mechanism established;
- exact representative content continuity established;
- strip event mechanically established;
- human motivation not explicitly evidenced;
- at least one material hardening defect established.

### D — material provenance gap prevents reliable canon identification

Requires inability to identify a reliable theorem-bearing source or inability to establish meaningful content continuity between the relevant histories.

### E — source/access defect prevents adjudication

Use only if repository access or identity defects block the required tests.

## 6. Hardening defect criteria

Any of the following may establish a hardening need if verified:

- frozen canon depends only on mutable/unprotected branch refs with no matching immutable tag;
- release files point to a tag that no longer exists;
- default README materially misdescribes the current tree or fails to route theorem-source readers to the canon ref;
- default branch and scientific canon are disconnected histories without a repository-level crosswalk;
- canonical-source selection requires private memory or external Observatory knowledge rather than repository-native navigation.

The mere existence of a disconnected history is not itself a defect if routing and durable anchoring are explicit and sufficient.

## 7. Firewalls

- No NFC write, ref move, tag creation, branch protection change, or README edit.
- No scientific theorem/status adjudication.
- No inference of human intent from silence.
- No assertion of complete file-by-file identity from a representative sample.
- No claim that a descendant research branch is an immutable canonical anchor merely because it keeps a commit reachable.
- No repair recommendation may be treated as authorization.

## 8. Stop rule

Execute the evidence-only audit, record one A-E outcome, recommend only the minimum hardening justified by evidence, and stop before independent acceptance or any source-project mutation.
