# Project Observatory Snapshot v0.5 — Content

Status: `CONTENT_COMPLETE__AWAITING_FREEZE_MANIFEST`

## 1. Snapshot basis

Snapshot v0.5 advances Snapshot v0.4 only for accepted-history/provenance maintenance that occurred after v0.4:

```text
BASE_SNAPSHOT = 03d4753d7629b02447095db3d63f132f84550d20
BASE_TREE = 889cda59c10bd4e197a0c3aedb1bf1a0fba12b98
```

It incorporates:

1. accepted OBS-U009 provenance-divergence adjudication;
2. accepted-history archive consolidation and subsequent reachability cleanup;
3. separately governed NFC provenance hardening implementing accepted H1-H4 routing requirements;
4. exact revalidation of current default heads for NFC, FCP, PGH, and HiVenues;
5. register reconciliation only — no new scientific target selection.

## 2. Current observed project identities

```text
NFC publication main = 5072d563b0a3dd4a7643be427cd47108216d8793
NFC scientific canon ref = archive/nfc-canonical-ed3047c2
NFC canon tag = nfc-canonical-ed3047c2
NFC canon commit = ed3047c2cbc0abc34d2549dd27754e4d3d05af78
NFC canon tree = 00ef55ff36d5e9663ca1ef2c9566e2bc1396f973
NFC historical release tag v1.0-canon-rewrite = 716e6fae585251185ffd15775dd923132f16c88e

FCP main = a41bc6101b63140ee2687e0cf67a47ab6be77215
PGH main = d8a16161f33d3bb8f97c15f095ca651c169f5896
HiVenues main = 9351655112a25fd8a1d115d8c402534726b1e035
```

FCP, PGH, and HiVenues default heads are unchanged from v0.4. NFC publication `main` moved only through provenance/routing maintenance; the frozen scientific canon did not move.

## 3. OBS-U009 closure

Accepted Observatory lineage:

```text
SELECTION = 68d74abca46552a72585fd161232a1ad3f4f0ca1
PREREGISTRATION = 773a8e9e6f30d6a5ca67c8a28ce2938aa6365928
EXECUTION = 24dc35bec216bf2db99aeaefb05a048868d6c969
ACCEPTANCE = 928f5d79c39b15657b9d4f36a096bcac1807dab8
```

Accepted outcome:

```text
C__CONTENT_CONTINUITY_AND_MECHANISM_ESTABLISHED__HUMAN_INTENT_UNRESOLVED__HARDENING_REQUIRED
```

Separately governed NFC repair then completed:

```text
H1 durable canonical anchor = COMPLETE_AT_ROUTING_SCOPE
H2 historical v1 release anchor = COMPLETE
H3 default-main source routing = COMPLETE
H4 repository-native provenance crosswalk = COMPLETE
```

This repair does not alter theorem content or frozen scientific status.

## 4. Discrepancy closure

```text
OBS-D001 = RESOLVED_AT_PROVENANCE_ROUTING_SCOPE
```

Publication and scientific-canon identities remain distinct by design; the former source-selection defect is repaired through explicit routing, exact tags, and provenance documentation.

```text
OBS-D005 = RESOLVED_BY_ACCEPTED_HISTORY_ARCHIVE
```

`archive/accepted-history-v0.1` now carries the reachability burden formerly distributed across many independent acceptance/audit refs. Redundant branch cleanup therefore no longer threatens accepted-history reachability so long as the archive ref remains intact.

`OBS-D004` remains unresolved at source-project level and is not altered by provenance maintenance.

## 5. Active uncertainty posture

Active high-value uncertainties remain:

```text
OBS-U004 PGH D1 empirical test        -> externally hardware/apparatus gated
OBS-U005 FCP next evidence trigger     -> evidence gated
OBS-U006 HiVenues #199 completion      -> Astra independence quarantine
OBS-U007 HiVenues visual/#200 quality  -> sequenced after #199 + quarantine
OBS-U008 Astra greenfield comparison   -> operationally gated until isolated run
OBS-U010 NFC NS new-premise completion -> source-project research, not frozen-source Observatory derivation
```

There is no presently eligible high-information internal Observatory substitute target that respects all project firewalls and outranks the gated work.

## 6. Routing decision

```text
NEXT_OBSERVATORY_TARGET_SELECTED = NO
INTERNAL_MAKE_WORK_AUTHORIZED = NO
U010_AUTO_SELECTED = NO
```

The correct information-gain posture is to preserve readiness and re-rank when an external gate changes. Selecting NFC U010 would require a separately governed NFC new-premise research authorization rather than an Observatory continuation by default.

## 7. Scientific and governance firewall

```text
NFC_THEOREM_CONTENT_CHANGED_BY_OBSERVATORY = NO
FCP_SCIENCE_MUTATED = NO
PGH_SCIENCE_MUTATED = NO
HIVENUES_IMPLEMENTATION_MUTATED = NO
OBSERVATORY_DEFAULT_MAIN_REWRITTEN = NO
NEW_ADVERSARIAL_TARGET_OPENED = NO
```

This content freezes the post-U009/post-provenance-repair portfolio state only.