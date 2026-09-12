# OBS-U009 — NFC Repository Provenance Divergence Target Selection v0.1

Status: `TARGET_SELECTED`

Baseline:

```text
PROJECT_OBSERVATORY_SNAPSHOT = V0.4
SNAPSHOT_COMMIT = 03d4753d7629b02447095db3d63f132f84550d20
NFC_PUBLICATION_MAIN = b8587ce3409e34c0dd4e56c61ee585c07798b0e5
NFC_FROZEN_CANON_REF = archive/nfc-canonical-ed3047c2
NFC_FROZEN_CANON_COMMIT = ed3047c2cbc0abc34d2549dd27754e4d3d05af78
NFC_FROZEN_CANON_TREE = 00ef55ff36d5e9663ca1ef2c9566e2bc1396f973
```

## Selected uncertainty

```text
SELECTED_UNCERTAINTY_ID = OBS-U009
SELECTED_TARGET_CLASS = REPOSITORY_PROVENANCE_DIVERGENCE
SELECTED_TARGET_SHORT_NAME = NFC_MAIN_ARCHIVE_PROVENANCE_AND_HARDENING
```

## Exact question

Can repository-native evidence reconstruct the provenance mechanism by which NFC's theorem-bearing corpus became separated from default `main`, distinguish Git-history discontinuity from scientific-content continuity, determine what can and cannot be established about the human reason for the split, and adjudicate whether the present repository needs additional provenance hardening to prevent canonical-source selection failure?

## Preliminary evidence motivating selection

1. `main@b8587ce...` is a signed commit with parent `0f23c285...`, message `remove`, and a very large deletion-only diff.
2. current `main` contains only `README.md`, `CITATION.cff`, and `LICENSE`.
3. frozen canon is `archive/nfc-canonical-ed3047c2@ed3047c2...`.
4. GitHub reports no common ancestor between `main@b8587ce...` and `archive/...@ed3047c2...`.
5. the archive lineage has a parentless root `d5d88c2...` dated 2026-07-01 with message `Baseline snapshot: isolated working copy of NFC corpus as received`.
6. representative theorem-bearing blobs at `d5d88c2...` are byte-identical to the last pre-strip `main` state `0f23c285...`.
7. the archive branch is not protected; no tag currently points to `ed3047c2...`.
8. `main` README says the repository hosts the PDF and TeX source files even though the current `main` tree does not contain them.

These facts justify a bounded provenance audit. They do not authorize NFC mutation.

## Mandatory outcome space

```text
A__DIVERGENCE_FULLY_EXPLAINED_AND_CURRENT_HARDENING_SUFFICIENT
B__MECHANISM_AND_INTENT_ESTABLISHED__ADDITIONAL_HARDENING_REQUIRED
C__CONTENT_CONTINUITY_AND_MECHANISM_ESTABLISHED__HUMAN_INTENT_UNRESOLVED__HARDENING_REQUIRED
D__MATERIAL_PROVENANCE_GAP_PREVENTS_RELIABLE_CANON_IDENTIFICATION
E__SOURCE_OR_ACCESS_DEFECT_PREVENTS_ADJUDICATION
```

## Selection firewall

- Do not infer human motivation from the single commit message `remove`.
- Do not equate lack of common Git ancestry with lack of content continuity.
- Do not equate matching representative blobs with proof that every historical file was identical unless a complete manifest comparison is performed.
- Do not mutate NFC, move refs, create tags, rewrite `main`, or edit README during this audit.
- Do not change any theorem or scientific status.
- Do not treat a hardening recommendation as authorization to implement it.
- Distinguish commit reachability from canonical-source discoverability.
- Preserve OBS-D001's existing rule that the archive ref, not default `main`, is the theorem-bearing source for frozen-canon analysis.

## Next bounded step

Preregister and execute an evidence-only provenance audit on `audit/obs-u009-nfc-provenance-divergence`. Stop before any NFC repair/hardening action and before independent acceptance unless separately authorized.
