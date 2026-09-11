# Project Observatory Snapshot V0.1

Status: FROZEN

## Frozen Observatory identity

The immutable content snapshot is the exact Observatory commit below. This manifest is intentionally committed **after** that content commit so it can bind the snapshot identity without a self-referential Git hash problem.

```text
SNAPSHOT_CONTENT_COMMIT = 09856095d8ff1f29f72676a768896b4f425edf17
SNAPSHOT_CONTENT_TREE = c3cd39ce3de7d11faf1680321e4f843cd1ddd94a
METHOD_FREEZE_COMMIT = 421a1237805d41365d02105d293711c72ea116b1
CANONICAL_RECONSTRUCTION_COMMIT = 332b2c5bc79fb70199c6be71f9eb977a97801db7
```

The manifest commit is a provenance pointer to `SNAPSHOT_CONTENT_COMMIT`; it is not a replacement snapshot with rewritten content.

## Observed repository identities

The snapshot binds the same exact observed identities used by the reconstructed project records and rechecked immediately before freeze:

| Project | Repository | Canonical ref | Canonical commit | Additional provenance identity |
|---|---|---|---|---|
| NFC | `etblink/Nested-Fibrational-Cosmology` | `archive/nfc-canonical-ed3047c2` | `ed3047c2cbc0abc34d2549dd27754e4d3d05af78` | default `main@b8587ce3409e34c0dd4e56c61ee585c07798b0e5` is retained only as discrepancy/public-surface context |
| FCP | `etblink/Foundational-Convergence-Program` | `main` | `e7dd1473e5ab89b4657d33e9b05fe90ae2ae7a65` | none |
| PGH | `etblink/Physical-Grammar-Hypothesis` | `main` | `d8a16161f33d3bb8f97c15f095ca651c169f5896` | none |
| HiVenues | `etblink/HiVenues` | `main` | `9351655112a25fd8a1d115d8c402534726b1e035` | none |

Project-record observation time remains `2026-09-11T21:05:00Z`. The exact heads above were rechecked unchanged immediately before snapshot freeze.

## Bound snapshot surfaces

The frozen content commit contains and binds:

- `projects/NFC.json`
- `projects/FCP.json`
- `projects/PGH.json`
- `projects/HIVenues.json`
- `registers/PROJECT_REGISTER.md`
- `registers/CLAIM_REGISTER.md`
- `registers/DEPENDENCY_REGISTER.md`
- `registers/UNCERTAINTY_REGISTER.md`
- `registers/EXTERNAL_TRIGGER_REGISTER.md`
- `audits/DISCREPANCY_DOCKET.md`
- the frozen schemas under `schema/`
- `governance/PROJECT_OBSERVATORY_CHARTER.md`

## Snapshot conclusions

1. Canonical state reconstruction is complete for the four initial observed projects at the exact identities above.
2. Material state claims are indexed without attempting to duplicate every project-internal theorem, issue, or ledger.
3. Load-bearing dependencies are separated from contextual relationships and explicit non-dependencies.
4. The qualitative uncertainty/information-gain register is complete at v0.1 and contains no combined score.
5. External blocks are recorded rather than replaced by synthetic work.
6. Three reconstruction discrepancies remain docketed; none authorizes observed-repository repair.
7. No observed repository was mutated by the Observatory operation.
8. No new NFC adversarial audit target was selected or executed as part of this snapshot.

## Post-snapshot firewall

The Charter sequence through snapshot freeze is now satisfied:

```text
CANONICAL_RECONSTRUCTION = COMPLETE
DEPENDENCY_RECONSTRUCTION = COMPLETE
UNCERTAINTY_REGISTER = COMPLETE
SNAPSHOT = FROZEN
NFC_ADVERSARIAL_TARGET_SELECTED = NO
NFC_ADVERSARIAL_AUDIT_EXECUTED = NO
```

A later operation may now **select** a candidate adversarial NFC target, but selection and execution remain separate acts. Any selected audit must be prospectively preregistered and must permit survival, weakening, underdetermination, repair requirement, or downstream reconsideration as legitimate outcomes.
