# Project Observatory — NFC Provenance-Hardening Reconciliation v0.1

Status: `RECONCILED__NO_NEW_SCIENTIFIC_TARGET_SELECTED`

## 1. Basis

This maintenance record reconciles Project Observatory with the separately governed NFC provenance-hardening repair that followed accepted OBS-U009.

OBS-U009 accepted:

```text
ACCEPTANCE = 928f5d79c39b15657b9d4f36a096bcac1807dab8
OUTCOME = C__CONTENT_CONTINUITY_AND_MECHANISM_ESTABLISHED__HUMAN_INTENT_UNRESOLVED__HARDENING_REQUIRED
```

The accepted-history archive subsequently anchored that acceptance. This record does not reopen or reinterpret U009.

## 2. Repaired NFC publication identity

Current NFC publication/default branch:

```text
main = 5072d563b0a3dd4a7643be427cd47108216d8793
```

The default README now explicitly routes theorem-source readers to the frozen canon, and `PROVENANCE.md` records the disconnected-history/re-root provenance crosswalk.

## 3. Frozen scientific canon unchanged

```text
CANON_REF = archive/nfc-canonical-ed3047c2
CANON_TAG = nfc-canonical-ed3047c2
CANON_COMMIT = ed3047c2cbc0abc34d2549dd27754e4d3d05af78
CANON_TREE = 00ef55ff36d5e9663ca1ef2c9566e2bc1396f973
```

No theorem-bearing scientific content was changed by the provenance repair.

## 4. Release anchor restored

```text
v1.0-canon-rewrite
  -> 716e6fae585251185ffd15775dd923132f16c88e
```

The stale/missing tag identified by U009 is repaired.

## 5. H1-H4 closure

```text
H1 durable canonical anchor = COMPLETE_AT_ROUTING_SCOPE
H2 stale v1 release anchor = COMPLETE
H3 default-main source routing = COMPLETE
H4 repository-native provenance crosswalk = COMPLETE
```

Optional future tag/branch ruleset protection is administrative hardening, not a remaining source-selection defect at the present audited scope.

## 6. Observatory consequence

```text
OBS_U009 = RESOLVED_AT_AUDITED_SCOPE
OBS_D001 = DIVERGENCE_PERSISTS_BY_DESIGN__SOURCE_SELECTION_DEFECT_RESOLVED
NEW_SCIENTIFIC_TARGET_SELECTED = NO
NFC_CANON_MUTATED = NO
```

The repository-default/publication identity and theorem-bearing scientific-canon identity remain intentionally distinct. The prior risk was not the existence of two identities itself, but inadequate routing and durable anchoring. That risk is now repaired at the audited provenance/routing scope.

## 7. External-head revalidation

At reconciliation time:

```text
FCP main = a41bc6101b63140ee2687e0cf67a47ab6be77215
PGH main = d8a16161f33d3bb8f97c15f095ca651c169f5896
HiVenues main = 9351655112a25fd8a1d115d8c402534726b1e035
```

Those three default-branch identities are unchanged from Snapshot v0.4.

## 8. Portfolio routing consequence

With U009 resolved, Project Observatory has no presently eligible high-information internal target that outranks the externally gated work without crossing a project firewall:

- PGH D1 remains hardware/apparatus gated.
- FCP remains evidence-trigger gated.
- HiVenues independent Astra work remains gated until the isolated Astra handoff can run.
- HiVenues #199 / visual convergence remain quarantined behind that independence boundary.
- NFC U010 is source-project new-premise research, not a remaining frozen-source Observatory derivation.

Accordingly this reconciliation updates state only and does not silently select U010 or manufacture substitute work.