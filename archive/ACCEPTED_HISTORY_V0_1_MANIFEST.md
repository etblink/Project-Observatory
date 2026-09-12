# Project Observatory Accepted History Archive — Manifest v0.1

Status: `FROZEN__ARCHIVE_ANCHOR_ACTIVE`

## 1. Purpose

This archive branch is a provenance-only consolidation ref. It exists so accepted Project Observatory histories remain durably reachable without requiring one branch ref per accepted adjudication.

It does not alter any scientific result, source-project theorem, or acceptance status.

## 2. Archive branch

```text
ARCHIVE_BRANCH = archive/accepted-history-v0.1
SNAPSHOT_TREE = 889cda59c10bd4e197a0c3aedb1bf1a0fba12b98
SNAPSHOT_BASE = 03d4753d7629b02447095db3d63f132f84550d20
```

The archive uses synthetic Git commits with unchanged Snapshot-v0.4 tree content and multiple parents. Reachability, not content merging, is the sole purpose of those commits.

## 3. Original 117 adjudication-tip coverage

The adjudication refs existing before completion of the internal-control minimality gate were partitioned without duplication into six direct-parent groups:

```text
GENERIC_ACCEPTANCES = 25
GROUP_COMMIT = 8baf07bf942e88428d7fe615b7b1d5450440d73e

SPEC_ACCEPTANCES = 16
GROUP_COMMIT = 0deaa62be94248ae8f93161aa306fd2333ca0d21

NS_ACCEPTANCES_GROUP_1 = 19
GROUP_COMMIT = 9d29a83afe1b79bf2c62f3728352707525ad19af

NS_ACCEPTANCES_GROUP_2 = 19
GROUP_COMMIT = a87f3f2ce75ae8e2d23ac5019710a471f90342cd

NS_ACCEPTANCES_GROUP_3 = 19
GROUP_COMMIT = 7cf53936f381f4412571f37c813ce14875c346d8

NS_ACCEPTANCES_GROUP_4 = 19
GROUP_COMMIT = 2803f3973b92ce4ab9fc393114bf59f2bce2ad08
```

Coverage checksum:

```text
25 + 16 + 19 + 19 + 19 + 19 = 117
```

All 117 accepted tips are direct parents of exactly one group commit. Each group commit also directly parents Snapshot v0.4 so the archive remains tied to the frozen portfolio boundary.

## 4. First consolidation commit

The six group commits were consolidated by:

```text
ACCEPTED_HISTORY_ROOT = a95cb5c3cd1c202626942141d910c682457654f7
```

That commit also directly anchors the accepted Observatory audit tips:

```text
OBS_U002_ACCEPTANCE = b4bd176246b7e4154241c2965a92faaf5a70d709
OBS_U003_ACCEPTANCE = 15dde757783c7eaa4f2f18c6c9facb24fdf4a464
```

Thus the archive covers the 117 adjudication tips plus the separately named accepted U002/U003 audit lineages.

## 5. Newly completed internal-control minimality gate

The previously unfinished preregistration has now completed:

```text
PREREGISTRATION = de1364024b201fd6c3674e4db4dc9048ad7d36a2
EXECUTION = 83c785085152b7b6445b306668529025f09b0358
ACCEPTANCE = 83964fffad6aca5dcfe9495dcce6c871956c28fa
```

Its acceptance commit is directly parented into the archive by:

```text
ARCHIVE_EXTENSION = 73b4794465ead2934e90a94cc94ba58edc1f6993
```

The acceptance commit itself retains the execution and preregistration lineage.

Therefore current adjudication coverage is:

```text
PREVIOUS_ADJUDICATION_TIPS = 117
NEW_INTERNAL_CONTROL_ACCEPTANCE = 1
CURRENT_ADJUDICATION_TIPS_COVERED = 118
```

## 6. Reachability consequence

So long as `archive/accepted-history-v0.1` remains intact at or beyond `73b4794465ead2934e90a94cc94ba58edc1f6993`:

- all 118 current `adjudication/*` acceptance tips are ancestors of the archive branch;
- their execution/preregistration ancestors remain reachable through normal Git parentage;
- the accepted U002/U003 audit tips are ancestors of the archive branch;
- deleting the corresponding redundant branch refs does not delete the commits or accepted history.

This is a Git reachability statement only. It does not imply that deleting semantically useful refs is always desirable for navigation.

## 7. Scientific result added during consolidation

The completed internal-control minimality gate accepted:

```text
A__ABSOLUTE_INTERNAL_CEILING_IS_MINIMAL_FOR_VALUE_CONTROL__NOT_FOR_ABSORPTION
```

with prospective hypothesis:

```text
P_NS_INTERNAL_VALUE_CEILING:
there exists a prospectively fixed or independently derived finite M_E
such that 0 <= E_n <= M_E on the declared late-tail regime.
```

This supplies finite value control and hence finite oscillation control. It does not establish relative absorption or contraction.

The subsidiary oscillation-only result remains:

```text
IF_TARGET_IS_NARROWED_TO_OSCILLATION_ONLY:
B__DIRECT_OSCILLATION_PREMISE_IS_STRICTLY_WEAKER_AND_MINIMAL
```

## 8. Governance boundary

```text
SOURCE_PROJECT_MUTATED = NO
NFC_CANON_CHANGED = NO
FCP_MUTATED = NO
PGH_MUTATED = NO
ACCEPTED_RESULTS_REINTERPRETED = NO
```

The archive operation is maintenance/provenance work only. Any future branch deletion remains a separate manual action.

## 9. OBS-U009 provenance-divergence acceptance extension

The accepted OBS-U009 lineage is:

```text
TARGET_SELECTION = 68d74abca46552a72585fd161232a1ad3f4f0ca1
PREREGISTRATION = 773a8e9e6f30d6a5ca67c8a28ce2938aa6365928
EXECUTION = 24dc35bec216bf2db99aeaefb05a048868d6c969
ACCEPTANCE = 928f5d79c39b15657b9d4f36a096bcac1807dab8
```

Accepted outcome:

```text
C__CONTENT_CONTINUITY_AND_MECHANISM_ESTABLISHED__HUMAN_INTENT_UNRESOLVED__HARDENING_REQUIRED
```

The acceptance endpoint is directly parented into the archive by the provenance-only synthetic commit:

```text
OBS_U009_ARCHIVE_EXTENSION = eebbd228fab7d1a4be3b3fb5d17ea8460cf201d8
FIRST_PARENT = ba9b253f618461e2e5c918b2d117bc2c6cba26a0
SECOND_PARENT = 928f5d79c39b15657b9d4f36a096bcac1807dab8
```

The extension preserves the prior archive tree and changes no accepted result. The acceptance commit itself retains the U009 execution, preregistration, and selection lineage.

Accordingly, once this manifest update is committed and ancestry is independently verified, `audit/obs-u009-nfc-provenance-divergence` is no longer required for Git reachability and may be considered a manual branch-deletion candidate. This statement does not authorize deletion by the archive operation itself.
