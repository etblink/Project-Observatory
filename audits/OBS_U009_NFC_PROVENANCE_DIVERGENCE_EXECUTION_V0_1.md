# OBS-U009 — NFC Repository Provenance Divergence Audit Execution v0.1

Status: `EXECUTED__AWAITING_ACCEPTANCE`

```text
TARGET_SELECTION = 68d74abca46552a72585fd161232a1ad3f4f0ca1
PREREGISTRATION = 773a8e9e6f30d6a5ca67c8a28ce2938aa6365928
SOURCE_PROJECT_MUTATION = NO
```

## 1. Controlling outcome

```text
C__CONTENT_CONTINUITY_AND_MECHANISM_ESTABLISHED__HUMAN_INTENT_UNRESOLVED__HARDENING_REQUIRED
```

## 2. Exact repository identities

### Default publication main

```text
MAIN = b8587ce3409e34c0dd4e56c61ee585c07798b0e5
MAIN_TREE = f5d2112d6346b659127d596f1f62a2c7069cdc60
MAIN_PARENT = 0f23c285191ab20bf468868940f385068e7e8717
MAIN_MESSAGE = remove
MAIN_DATE = 2026-07-08T03:57:12Z
MAIN_SIGNATURE = VERIFIED
```

The `b8587ce...` commit reports zero additions and 53,368 deletions. The current `main` root contains exactly three files:

```text
README.md
CITATION.cff
LICENSE
```

The README nevertheless says the repository hosts the PDF and TeX source files for the current public materials and enumerates the canonical spine and derived branch books. Those files are not present on current `main`.

### Frozen scientific canon

```text
CANON_REF = archive/nfc-canonical-ed3047c2
CANON_COMMIT = ed3047c2cbc0abc34d2549dd27754e4d3d05af78
CANON_TREE = 00ef55ff36d5e9663ca1ef2c9566e2bc1396f973
CANON_PARENT = dc72e0b07ce126d912b5f6ff85b0b5597dfaefeb
CANON_MESSAGE = MIG-052 Corrective J: synchronize NS posture
CANON_REF_PROTECTED = NO
```

The archive root contains the theorem-bearing books, branch books, governance/scaffold material, metadata, release artifacts, and validation machinery.

## 3. Git ancestry result

GitHub comparison between `main@b8587ce...` and `archive/...@ed3047c2...` returns:

```text
NO_COMMON_ANCESTOR
```

Therefore the scientific-canon archive is not a descendant, ancestor, or ordinary branch fork of the current `main` history.

This does not imply lack of content continuity.

## 4. Archive re-root mechanism

The frozen canon lineage contains exactly 75 commits including its root. Its parentless root is:

```text
ARCHIVE_ROOT = d5d88c2e7672b36c9ef7231aa657d967e9feef6b
ARCHIVE_ROOT_TREE = 0b37fc5372d9de960bc5660671e12196c452223b
ARCHIVE_ROOT_PARENTS = 0
ARCHIVE_ROOT_DATE = 2026-07-01T08:16:58Z
ARCHIVE_ROOT_MESSAGE = Baseline snapshot: isolated working copy of NFC corpus as received
```

From this root to the frozen canon, GitHub reports:

```text
AHEAD_BY = 74
BEHIND_BY = 0
```

Thus the mechanical archive mechanism is a deliberate Git re-root/import of an isolated working-copy snapshot followed by 74 commits of canon/audit/migration work.

## 5. Representative exact content continuity

The following exact Git blob identities match between the isolated archive root `d5d88c2...` and the last pre-strip `main` commit `0f23c285...`:

```text
NFC_Book_I.tex
blob = 12c4fd2fbaf0f0aa34a20756810fe467afb85368

NFC_Book_II.tex
blob = 97493131943f5462726a484461d3cceb930fb214

NFC_NS_Branch.tex
blob = 81892c764f6f8b15eea2aa01a708037b229638c0
```

This spans two spine books and one major derived branch. It establishes byte-for-byte representative continuity between the pre-strip public-history corpus and the isolated archive baseline.

The audit does not claim complete file-by-file identity because a full historical manifest cross-comparison was not required for the target and was not performed.

## 6. Mechanical provenance sequence

Repository-native evidence supports the following sequence:

1. `main@0f23c285...` on 2026-06-23 contains the theorem-bearing corpus.
2. On 2026-07-01, an isolated working-copy snapshot of that corpus is committed as a new Git root `d5d88c2...`; representative theorem-bearing blobs exactly match `0f23c285...`.
3. The isolated lineage advances through 74 additional commits, eventually reaching frozen canon `ed3047c2...` on 2026-07-15.
4. Independently, default `main` advances directly from `0f23c285...` to `b8587ce...` on 2026-07-08 via a deletion-only commit titled `remove`, stripping the theorem-bearing files and leaving the publication metadata surface.
5. Because the isolated lineage began as a new root, Git history is disconnected even though representative scientific content is continuous.

This explains the topology/mechanism.

## 7. Human-intent result

The repository does not provide sufficient explicit evidence to establish the policy motivation for the July-8 stripping operation.

The commit message is only:

```text
remove
```

The present README/Zenodo/citation surface is consistent with a publication-facing intent, but that is an inference, not a repository-native declaration of why the theorem-bearing files were removed.

Therefore:

```text
MECHANICAL_CAUSE = ESTABLISHED
CONTENT_CONTINUITY = ESTABLISHED_REPRESENTATIVELY
HUMAN_POLICY_INTENT = UNRESOLVED
```

Outcome B is therefore unavailable.

## 8. Existing reachability protection

The frozen canon remains reachable not only through `archive/nfc-canonical-ed3047c2` but also as an ancestor of several current post-freeze branches, including:

```text
audit/physical-history-selection-source-forcing
  ed3047c2 -> +1 commit

audit/scc-recursivity-selector
  ed3047c2 -> +1 commit

accepted/post-freeze-actualization-findings-v0.1
  ed3047c2 -> +2 commits
```

This reduces immediate object-loss risk if one branch ref were accidentally deleted.

However, descendant research/audit refs are incidental reachability anchors. They do not substitute for an explicit canonical-source anchor or clear repository-default routing.

## 9. Hardening defects established

### H1 — canonical branch is mutable/unprotected

`archive/nfc-canonical-ed3047c2` is currently unprotected.

No current Git tag points to `ed3047c2...`.

### H2 — declared immutable release tag is absent

The canon contains:

```text
release/RELEASE_POINTER.txt
  tag: v1.0-canon-rewrite
  716e6fae585251185ffd15775dd923132f16c88e
```

and release notes call this tag/commit immutable.

The current repository tag namespace exposes only:

```text
physics -> aafc70a18b8324d051790083c702a9ef421babbf
```

The `716e6fae...` commit still exists and is an ancestor of `ed3047c2...` by 59 commits, so this is not history loss. It is a stale/broken repository-level release anchor.

### H3 — default README misroutes theorem-source readers

Current `main` contains only README/CITATION/LICENSE, yet README says the repository hosts the PDF and TeX source files and enumerates books/branches that are absent from that tree.

It does not identify `archive/nfc-canonical-ed3047c2`, `ed3047c2...`, or tree `00ef55ff...` as the frozen scientific source.

A reader following the default branch therefore cannot discover the controlling theorem source from the README itself.

### H4 — no repository-native main-to-archive provenance crosswalk

The archive root message proves it is an isolated working-copy snapshot, and representative blobs establish continuity, but there is no concise repository-facing crosswalk that records:

```text
pre-strip main 0f23c285...
    -> isolated content baseline d5d88c2...
    -> 74-commit canon lineage
    -> frozen canon ed3047c2...

pre-strip main 0f23c285...
    -> strip commit b8587ce...
    -> publication surface
```

Without Project Observatory knowledge or manual Git archaeology, the split is easy to misread as unrelated histories.

## 10. Minimum justified hardening package

This audit does not authorize implementation. The smallest source-project repair package justified by evidence is:

1. **Durable canonical anchor:** create an explicitly named immutable release tag (or equivalently protected ref/ruleset) for `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`; retain the exact tree `00ef55ff36d5e9663ca1ef2c9566e2bc1396f973` in the provenance record.
2. **Repair stale release pointer:** either restore the declared `v1.0-canon-rewrite` tag at `716e6fae...` or update the release metadata under separately governed provenance repair so the repository no longer claims an absent immutable tag.
3. **Default-branch routing banner:** change `main` README only under source-project authorization to state clearly that `main` is a publication/landing surface and that frozen theorem-bearing source is the named archive ref/commit/tree. Remove or qualify the false present-tense claim that the default tree hosts the TeX/PDF corpus.
4. **Provenance crosswalk:** add one short repository-native provenance document recording the re-root/import boundary and the exact identities above. A complete historical file manifest would strengthen this further but is not required to resolve source selection.

Changing the default branch back to the canon is not required by the evidence. Clear routing plus durable anchoring is sufficient.

## 11. Outcome adjudication

### A — rejected

Current hardening is not sufficient: archive ref is unprotected, declared immutable release tag is absent, and default README does not route to the theorem-bearing canon.

### B — rejected

Mechanical mechanism is established, but human policy intent for the strip is not explicitly evidenced.

### C — accepted

```text
C__CONTENT_CONTINUITY_AND_MECHANISM_ESTABLISHED__HUMAN_INTENT_UNRESOLVED__HARDENING_REQUIRED
```

The repository history is mechanically explained; representative scientific content continuity is exact; human motivation remains underdetermined; provenance/navigation hardening is materially warranted.

### D — rejected

Reliable canon identification is already possible: the archive ref, exact commit/tree, release/canon documents, and descendant refs preserve the theorem-bearing source.

### E — rejected

No source/access defect blocked adjudication.

## 12. Final execution state

```text
OBS_U009_EXECUTED = YES
CONTROLLING_OUTCOME = C__CONTENT_CONTINUITY_AND_MECHANISM_ESTABLISHED__HUMAN_INTENT_UNRESOLVED__HARDENING_REQUIRED
GIT_ANCESTRY_CONTINUITY = NO
REPRESENTATIVE_CONTENT_CONTINUITY = YES
MECHANICAL_PROVENANCE_SEQUENCE = ESTABLISHED
HUMAN_POLICY_INTENT = UNRESOLVED
ADDITIONAL_PROVENANCE_HARDENING = REQUIRED
CANON_SOURCE_IDENTIFIABLE_NOW = YES
NFC_SOURCE_MUTATED = NO
NFC_REFS_MOVED = NO
NFC_TAGS_CREATED = NO
NFC_README_EDITED = NO
```

Hard stop before independent acceptance or any NFC repair/hardening operation.
