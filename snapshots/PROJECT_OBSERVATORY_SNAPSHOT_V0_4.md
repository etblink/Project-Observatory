# Project Observatory Snapshot V0.4 — Freeze Manifest

Status: `FROZEN`

## 1. Frozen identities

```text
SNAPSHOT_VERSION = V0.4
SNAPSHOT_BRANCH = snapshot/project-observatory-v0.4

CONTENT_COMMIT = 31e735f6bd9a8eaac8ca2e59dd2536448095c727
CONTENT_TREE = 3b653715f46b67d03f516c74a4f4e4bcef1f2ae7
CONTENT_PATH = snapshots/PROJECT_OBSERVATORY_SNAPSHOT_V0_4_CONTENT.md

OBS_U003_ACCEPTANCE = 15dde757783c7eaa4f2f18c6c9facb24fdf4a464
BRANCH_RETENTION_AUDIT_COMMIT = 702845fc92403a38a5dddc5e9cc52960ab3bfe66

PRIOR_SNAPSHOT_V0_3_FREEZE = 84d25c532114b92d6e547eb9ffebd25a87ebc3b3
PRIOR_SNAPSHOT_V0_3_CONTENT = 8624fef5c5139013deb68f37a301111288d58683
```

This manifest freezes the post-OBS-U003 portfolio refresh and branch-retention audit. It does not select or execute a new scientific/adversarial target.

## 2. Observed source heads at freeze

```text
NFC_PUBLICATION_MAIN = b8587ce3409e34c0dd4e56c61ee585c07798b0e5
NFC_SCIENTIFIC_CANON = archive/nfc-canonical-ed3047c2@ed3047c2cbc0abc34d2549dd27754e4d3d05af78
FCP_MAIN = a41bc6101b63140ee2687e0cf67a47ab6be77215
PGH_MAIN = d8a16161f33d3bb8f97c15f095ca651c169f5896
HIVenues_MAIN = 9351655112a25fd8a1d115d8c402534726b1e035
```

No observed source project moved during the v0.4 refresh.

## 3. Frozen Observatory conclusions

```text
OBS_U001 = RESOLVED_AT_AUDITED_SCOPE
OBS_U002 = RESOLVED_AT_AUDITED_SCOPE
OBS_U003 = RESOLVED_AT_AUDITED_SCOPE

OBS_U003_CONTROLLING_OUTCOME =
C__SOURCE_NONFORCING_ESTABLISHED_AT_AUDITED_SCOPE

SOURCE_WIDE_GLOBALIZATION_NO_GO = NO
VALID_SCOPED_GLOBALIZATION_OBSTRUCTION = YES
HISTORICAL_NO_UNIVERSAL_WAVEFUNCTION_RESTORED = NO
```

New reasoning/provenance constraints:

```text
OBS_DP015 = NO_SILENT_UNIVERSAL_GLOBALIZATION_NO_GO
OBS_DP016 = PRESERVE_ACCEPTANCE_REFS_UNTIL_ARCHIVAL_CONSOLIDATION
```

New discrepancy:

```text
OBS_D005 = PROJECT_OBSERVATORY_DEFAULT_MAIN_VS_DIVERGENT_ACCEPTED_HISTORY_REFS
```

## 4. Branch-retention freeze

The exact branch census was taken before creation of v0.4 refs:

```text
ORIGINAL_BRANCH_COUNT = 350
ORIGINAL_PRESERVE = 123
ORIGINAL_SAFE_DELETE = 227
```

Preserve from the original 350:

```text
all adjudication/*                                  117
audit/obs-u002-nfc-ls2-source-forcing                1
audit/obs-u003-globalization-obstruction              1
main                                                   1
snapshot/project-observatory-v0.2                      1
snapshot/project-observatory-v0.3                      1
research/nfc-ns-internal-control-premise-minimality-prereg-v0.1  1
TOTAL                                                123
```

Delete from the original 350, provided the preserve set remains:

```text
all research/* except the unfinished preregistration 208
16 enumerated legacy audit/nfc-* lifecycle refs       16
refresh/project-observatory-v0.2                       1
routing/observatory-v0.2-next-target-selection        1
selection/obs-u003-globalization-obstruction           1
TOTAL                                                227
```

The complete manual-deletion guidance is frozen in:

```text
maintenance/PROJECT_OBSERVATORY_BRANCH_RETENTION_AUDIT_V0_1.md
```

New refs created after the census and therefore outside the 350-ref checksum:

```text
refresh/project-observatory-v0.4
snapshot/project-observatory-v0.4
```

Both are preserve refs.

## 5. Information-gain reranking freeze

```text
HIGHEST_INTERNAL_ACTIONABLE = OBS-U009
HIGHEST_VALUE_EXTERNAL_EMPIRICAL = OBS-U004
ASTRA_INDEPENDENT_RESULT = OBS-U008__GATED
FCP_NEXT_TRIGGER = OBS-U005__EVIDENCE_GATED
HIVenues_ISSUE_199 = OBS-U006__QUARANTINED
HIVenues_VISUAL_PM4_EXIT = OBS-U007__SEQUENCED
NFC_NS_NEW_PREMISE_RESEARCH = OBS-U010__SOURCE_PROJECT_BOUNDARY
```

This is a gate-sensitive ordering. A newly opened external gate must be reconsidered before a later target-selection operation.

## 6. Freeze firewall

```text
PROJECT_OBSERVATORY_CORE_MISSION = ACTIVE
CANONICAL_STATE_REFRESH_V0_4 = COMPLETE
DEPENDENCY_REFRESH_V0_4 = COMPLETE
UNCERTAINTY_REFRESH_V0_4 = COMPLETE
BRANCH_RETENTION_AUDIT_V0_1 = COMPLETE
SNAPSHOT_V0_4 = FROZEN

NEW_TARGET_SELECTED = NO
NEW_AUDIT_PREREGISTERED = NO
NEW_AUDIT_EXECUTED = NO

NFC_REPOSITORY_MUTATED = NO
FCP_REPOSITORY_MUTATED = NO
PGH_REPOSITORY_MUTATED = NO
HIVenues_REPOSITORY_MUTATED = NO
PROJECT_OBSERVATORY_BRANCHES_DELETED = NO
```

Hard stop after freeze. Any next-target selection, accepted-history consolidation, default-branch rewrite, or actual branch deletion is a separate operation.
