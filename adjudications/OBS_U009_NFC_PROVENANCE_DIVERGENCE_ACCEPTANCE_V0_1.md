# OBS-U009 — NFC Repository Provenance Divergence Audit Acceptance v0.1

Status: `ACCEPTED__RESOLVED_AT_AUDITED_SCOPE`

```text
TARGET_SELECTION = 68d74abca46552a72585fd161232a1ad3f4f0ca1
PREREGISTRATION = 773a8e9e6f30d6a5ca67c8a28ce2938aa6365928
EXECUTION = 24dc35bec216bf2db99aeaefb05a048868d6c969
SOURCE_PROJECT_MUTATION = NO
```

## 1. Acceptance question

Did the execution faithfully adjudicate the preregistered NFC repository-provenance question, satisfy one and only one A-E outcome burden, respect the source-project firewall, and separate established repository mechanics from unresolved human intent?

## 2. Acceptance checks

### A1 — Exact lineage: PASS

The execution commit `24dc35bec216bf2db99aeaefb05a048868d6c969` is exactly parented to preregistration `773a8e9e6f30d6a5ca67c8a28ce2938aa6365928`, which is itself the preregistered continuation of target selection `68d74abca46552a72585fd161232a1ad3f4f0ca1`.

### A2 — Frozen identities respected: PASS

The execution uses the frozen identities declared by the preregistration:

```text
NFC main = b8587ce3409e34c0dd4e56c61ee585c07798b0e5
pre-strip main parent = 0f23c285191ab20bf468868940f385068e7e8717
frozen canon = ed3047c2cbc0abc34d2549dd27754e4d3d05af78
frozen canon tree = 00ef55ff36d5e9663ca1ef2c9566e2bc1396f973
archive root = d5d88c2e7672b36c9ef7231aa657d967e9feef6b
```

No moving source-project identity is substituted for these audited objects.

### A3 — Git-history discontinuity: PASS

The execution correctly records that GitHub comparison between current `main` and frozen canon returns no common ancestor. It does not misstate the archive as an ordinary descendant or fork of `main`.

### A4 — Re-root/import mechanism: PASS

The archive lineage has a parentless root `d5d88c2...` with repository-native message:

```text
Baseline snapshot: isolated working copy of NFC corpus as received
```

and the frozen canon is 74 commits ahead of that root. This is sufficient to establish the mechanical re-root/import structure of the archive lineage.

### A5 — Representative scientific-content continuity: PASS

The execution verifies exact Git blob equality between the isolated root and last pre-strip `main` for representative theorem-bearing material spanning spine and branch content:

```text
NFC_Book_I.tex  = 12c4fd2fbaf0f0aa34a20756810fe467afb85368
NFC_Book_II.tex = 97493131943f5462726a484461d3cceb930fb214
NFC_NS_Branch.tex = 81892c764f6f8b15eea2aa01a708037b229638c0
```

The execution correctly limits this to representative continuity and does not inflate it into an unperformed complete historical manifest proof.

### A6 — Strip event reconstruction: PASS

The execution correctly identifies `b8587ce...` as the signed direct child of `0f23c285...`, message `remove`, with zero additions and 53,368 deletions, leaving `README.md`, `CITATION.cff`, and `LICENSE` on current `main`.

That establishes the mechanical publication-surface stripping event without claiming a human policy motive.

### A7 — Human intent firewall: PASS

The execution expressly refuses to infer intent from chronology, the branch topology, the word `remove`, or the later publication-facing surface. It distinguishes:

```text
MECHANICAL_CAUSE = ESTABLISHED
CONTENT_CONTINUITY = ESTABLISHED_REPRESENTATIVELY
HUMAN_POLICY_INTENT = UNRESOLVED
```

This satisfies the preregistered human-intent standard and rules out outcome B.

### A8 — Hardening need: PASS

At least three independently sufficient hardening defects are established:

1. `archive/nfc-canonical-ed3047c2` is unprotected and no current tag points to `ed3047c2...`.
2. `release/RELEASE_POINTER.txt` declares immutable tag `v1.0-canon-rewrite` at `716e6fae...`, while the current repository tag namespace exposes only `physics`; the referenced commit remains reachable, so this is stale/broken anchoring rather than history loss.
3. default `main` contains only README/CITATION/LICENSE while README states that the repository hosts the PDF/TeX source corpus and does not route readers to the frozen theorem-bearing archive ref/commit/tree.

These facts independently defeat outcome A's `HARDENING_SUFFICIENT` burden.

The execution's additional observation that no concise repository-facing main-to-archive provenance crosswalk was found is reasonable, but this acceptance does not require exhaustive proof of nonexistence of every possible crosswalk file because defects 1-3 already establish the controlling hardening conclusion.

### A9 — Reliable canon remains identifiable: PASS

The frozen theorem-bearing source remains exactly identifiable as:

```text
archive/nfc-canonical-ed3047c2
commit ed3047c2cbc0abc34d2549dd27754e4d3d05af78
tree 00ef55ff36d5e9663ca1ef2c9566e2bc1396f973
```

and `ed3047c2...` remains ancestor-reachable from multiple post-freeze NFC audit/accepted refs. Therefore outcome D is too strong: provenance hardening is needed, but source identification is not currently impossible.

### A10 — Outcome exclusivity: PASS

```text
A = FAIL  hardening is not sufficient
B = FAIL  human policy intent is not explicitly established
C = PASS  all required burden elements are satisfied
D = FAIL  reliable theorem-bearing canon remains identifiable
E = FAIL  no source/access defect blocked adjudication
```

Exactly one preregistered outcome survives.

### A11 — Minimum-repair discipline: PASS

The execution recommends only provenance/navigation hardening:

- durable immutable/protected anchor for `ed3047c2...`;
- reconciliation of the stale/missing `v1.0-canon-rewrite` release anchor;
- accurate default-README routing to the theorem-bearing canon;
- a concise provenance crosswalk.

It correctly finds that changing the repository default branch back to the canon is not required by the evidence.

### A12 — Source-project firewall: PASS

No NFC theorem, source file, branch ref, tag, protection setting, README, or default branch was changed by the OBS-U009 execution. Recommendations are not treated as implementation authorization.

## 3. Accepted controlling result

```text
ACCEPTED_OUTCOME =
C__CONTENT_CONTINUITY_AND_MECHANISM_ESTABLISHED__HUMAN_INTENT_UNRESOLVED__HARDENING_REQUIRED
```

Accepted interpretation:

- NFC's publication `main` and frozen canon are disconnected Git histories.
- The archive history is mechanically explained as a parentless isolated-working-copy re-root/import followed by 74 commits to the frozen canon.
- Exact representative theorem-bearing blobs establish scientific-content continuity across the re-root boundary.
- The July-8 `remove` commit mechanically establishes the stripping of theorem-bearing files from `main`.
- Repository-native evidence does not establish why that stripping policy was chosen.
- The frozen canon is still reliably identifiable today.
- Current provenance/navigation hardening is insufficient and warrants a separately governed NFC repair operation.

## 4. Minimum accepted hardening requirement

A future NFC-side provenance repair, if separately authorized, should minimally achieve all of the following without changing scientific content:

```text
H1 durable canonical anchor for ed3047c2... / tree 00ef55ff...
H2 reconcile the stale declared v1.0-canon-rewrite release anchor
H3 make default main explicitly route theorem-source readers to the frozen canon
H4 record the re-root/import provenance boundary in repository-native documentation
```

This acceptance does not prescribe the exact Git mechanism (tag vs protected branch vs ruleset) so long as durability and discoverability are materially improved and exact identities remain explicit.

## 5. Closure state

```text
OBS_U009 = RESOLVED_AT_AUDITED_SCOPE
OBS_U009_ACCEPTED = YES
CONTROL_OUTCOME = C__CONTENT_CONTINUITY_AND_MECHANISM_ESTABLISHED__HUMAN_INTENT_UNRESOLVED__HARDENING_REQUIRED
GIT_ANCESTRY_CONTINUITY = NO
REPRESENTATIVE_CONTENT_CONTINUITY = YES
MECHANICAL_PROVENANCE_SEQUENCE = ESTABLISHED
HUMAN_POLICY_INTENT = UNRESOLVED
CANON_IDENTIFIABLE_NOW = YES
ADDITIONAL_PROVENANCE_HARDENING = REQUIRED
NFC_REPAIR_AUTHORIZED_BY_THIS_ACCEPTANCE = NO
NFC_SOURCE_MUTATED = NO
```

Hard stop before any NFC-side provenance repair, tag/ref/protection change, README edit, default-branch change, or scientific mutation.
