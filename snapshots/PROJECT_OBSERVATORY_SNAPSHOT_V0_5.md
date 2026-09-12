# Project Observatory Snapshot V0.5 — Freeze Manifest

Status: `FROZEN`

## 1. Frozen identities

```text
SNAPSHOT_VERSION = V0.5
SNAPSHOT_BRANCH = snapshot/project-observatory-v0.5

CONTENT_COMMIT = 9766766efc5f6cfb2453c6cdb898ce0a232cfdc1
CONTENT_TREE = 3b8e01c9feb1b7f25549733a617a5098fa096445
CONTENT_PATH = snapshots/PROJECT_OBSERVATORY_SNAPSHOT_V0_5_CONTENT.md

PRIOR_SNAPSHOT_V0_4_FREEZE = 03d4753d7629b02447095db3d63f132f84550d20
PRIOR_SNAPSHOT_V0_4_TREE = 889cda59c10bd4e197a0c3aedb1bf1a0fba12b98

OBS_U009_ACCEPTANCE = 928f5d79c39b15657b9d4f36a096bcac1807dab8
ACCEPTED_HISTORY_ARCHIVE_CURRENT = archive/accepted-history-v0.1
NFC_PROVENANCE_RECONCILIATION = maintenance/PROJECT_OBSERVATORY_NFC_PROVENANCE_RECONCILIATION_V0_1.md
```

This manifest freezes the post-OBS-U009 / post-NFC-provenance-repair portfolio state. It does not select or execute a new scientific/adversarial target.

## 2. Observed source heads at freeze

```text
NFC_PUBLICATION_MAIN = 5072d563b0a3dd4a7643be427cd47108216d8793
NFC_SCIENTIFIC_CANON = archive/nfc-canonical-ed3047c2@ed3047c2cbc0abc34d2549dd27754e4d3d05af78
NFC_CANON_TREE = 00ef55ff36d5e9663ca1ef2c9566e2bc1396f973
NFC_CANON_TAG = nfc-canonical-ed3047c2
NFC_RELEASE_TAG = v1.0-canon-rewrite@716e6fae585251185ffd15775dd923132f16c88e

FCP_MAIN = a41bc6101b63140ee2687e0cf67a47ab6be77215
PGH_MAIN = d8a16161f33d3bb8f97c15f095ca651c169f5896
HIVenues_MAIN = 9351655112a25fd8a1d115d8c402534726b1e035
```

FCP, PGH, and HiVenues default heads remain unchanged from v0.4. NFC publication `main` moved only through separately governed provenance/routing maintenance; the frozen scientific canon did not move.

## 3. Frozen Observatory conclusions

```text
OBS_U001 = RESOLVED_AT_AUDITED_SCOPE
OBS_U002 = RESOLVED_AT_AUDITED_SCOPE
OBS_U003 = RESOLVED_AT_AUDITED_SCOPE
OBS_U009 = RESOLVED_AT_AUDITED_SCOPE

OBS_U009_CONTROLLING_OUTCOME =
C__CONTENT_CONTINUITY_AND_MECHANISM_ESTABLISHED__HUMAN_INTENT_UNRESOLVED__HARDENING_REQUIRED
```

The subsequently authorized NFC provenance repair completed the accepted routing package:

```text
H1_DURABLE_CANONICAL_ANCHOR = COMPLETE_AT_ROUTING_SCOPE
H2_V1_RELEASE_ANCHOR = COMPLETE
H3_DEFAULT_MAIN_ROUTING = COMPLETE
H4_REPOSITORY_NATIVE_PROVENANCE_CROSSWALK = COMPLETE
```

No theorem-bearing NFC source content or scientific status changed.

## 4. Discrepancy and dependency freeze

```text
OBS_D001 = RESOLVED_AT_PROVENANCE_ROUTING_SCOPE
OBS_D005 = RESOLVED_BY_ACCEPTED_HISTORY_ARCHIVE
OBS_D004 = OBSERVATORY_IDENTIFIED__SOURCE_REPAIR_NOT_AUTHORIZED

OBS_DP016 = ACCEPTED_HISTORY_ARCHIVE_RETENTION_RULE__SATISFIED_FOR_COMPLETED_CLEANUP
OBS_DP017 = NFC_CANONICAL_ROUTING_PACKAGE_CONTROLS_FUTURE_SOURCE_SELECTION
```

Publication `main` and scientific canon remain distinct by design. The former source-selection defect is resolved by explicit routing, exact tags, and provenance documentation rather than by collapsing the two histories.

## 5. Current information-gain routing

```text
PGH_D1_EMPIRICAL = OBS-U004__EXTERNALLY_GATED
FCP_NEXT_TRIGGER = OBS-U005__EVIDENCE_GATED
HIVenues_ISSUE_199 = OBS-U006__ASTRA_QUARANTINED
HIVenues_VISUAL_PM4_EXIT = OBS-U007__SEQUENCED_AND_QUARANTINED
ASTRA_INDEPENDENT_RESULT = OBS-U008__OPERATIONALLY_GATED
NFC_NS_NEW_PREMISE_RESEARCH = OBS-U010__SOURCE_PROJECT_BOUNDARY
```

At this freeze there is no high-value internally executable Observatory substitute target that respects all project firewalls and outranks the gated work.

Accordingly:

```text
HIGHEST_INTERNAL_ACTIONABLE_OBSERVATORY_TARGET = NONE_AT_CURRENT_GATE_STATE
NEW_TARGET_SELECTED = NO
U010_AUTO_SELECTED = NO
INTERNAL_MAKE_WORK_AUTHORIZED = NO
```

A changed external gate must trigger re-ranking before any later target-selection operation.

## 6. Freeze firewall

```text
PROJECT_OBSERVATORY_CORE_MISSION = ACTIVE
CANONICAL_STATE_REFRESH_V0_5 = COMPLETE
DEPENDENCY_REFRESH_V0_5 = COMPLETE
UNCERTAINTY_REFRESH_V0_5 = COMPLETE
NFC_PROVENANCE_RECONCILIATION = COMPLETE
SNAPSHOT_V0_5 = FROZEN

NEW_TARGET_SELECTED = NO
NEW_AUDIT_PREREGISTERED = NO
NEW_AUDIT_EXECUTED = NO

NFC_THEOREM_CONTENT_MUTATED_BY_OBSERVATORY = NO
FCP_REPOSITORY_MUTATED = NO
PGH_REPOSITORY_MUTATED = NO
HIVenues_REPOSITORY_MUTATED = NO
PROJECT_OBSERVATORY_DEFAULT_MAIN_REWRITTEN = NO
```

Hard stop after freeze. Any later NFC U010 research authorization, external-gate-triggered operation, default-branch rewrite, or new adversarial target selection is a separate operation.