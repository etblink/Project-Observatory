# Discrepancy Docket

Status: CANONICAL_STATE_RECONSTRUCTION_V0_2_READY_TO_FREEZE

Discovery of a discrepancy does not authorize repair in an observed repository. Resolution status below records only what the evidence now establishes; Project Observatory may repair its own routing/provenance records.

| Docket ID | Project | Sources in tension | Observation | Materiality | Resolution status |
|---|---|---|---|---|---|
| OBS-D001 | NFC | historical publication `main@b8587ce...` vs frozen archive canon `ed3047c2...` | V0.1 found that default main did not make theorem-source routing sufficiently explicit while the archive ref contained the frozen scientific corpus. NFC has since added `PROVENANCE.md`, explicit README routing, exact canon/release tags, and a closure record while leaving theorem content unchanged. | HIGH — provenance/canonical-source selection | `RESOLVED_AT_PROVENANCE_ROUTING_SCOPE` by NFC `main@5072d563...`; optional stronger administrative protection is not a remaining source-identification defect. |
| OBS-D002 | PGH | historical `CURRENT_STATE.md@d8a16161...` vs then-latest D1 design-gate merge | V0.1 recorded a navigation lag. Current `CURRENT_STATE.md@2923875b...` now names the D1 boundary, no-apparatus state, required next sequence, and readiness infrastructure. | MEDIUM — routing/navigation freshness | `RESOLVED` on PGH `main@2923875b...`. |
| OBS-D003 | FCP / PGH | FCP `main@a41bc610...` vs PGH `main@2923875b...` | PGH has advanced its non-empirical readiness layer beyond the PGH state named by FCP's earlier sequencing documents. FCP's only post-v0.1 change is NFC provenance strengthening and explicitly leaves the evidence-triggered hold unchanged. | LOW — cross-program routing freshness | `KNOWN_TEMPORAL_LAG__NO_SCIENTIFIC_CONTRADICTION`; no FCP repair is justified absent a qualifying evidence event. |
| OBS-D004 | Project Observatory | current historical `main@1a8cad05...` vs exact later Observatory commits referenced by NFC/FCP (`89c799c2...`, `cde62683...`, `d687f962...`, `2e04c688...`) | Four exact Project Observatory preregistration/acceptance artifacts existed by immutable commit SHA and were relied on by downstream NFC/FCP records, but were not reachable/discoverable from current Observatory `main`. | HIGH — Observatory provenance and audit discoverability | `RESOLVED_BY_V0_2_RECOVERY`: exact file contents were recovered from the original commits onto the v0.2 pass branch without changing their scientific meaning or original provenance identities. |
| OBS-D005 | HiVenues | v0.1 Observatory record `main@9351655... / FROZEN` vs current repository `main@bf9a0b4e... / Candidate C Phase 2A accepted` | The immutable v0.1 snapshot is substantially stale by design: the independent Fable/Astra comparison completed, Candidate C synthesis was chartered, Phase 2A was accepted/merged, and Phase 2B opened. | HIGH — current product routing, not historical snapshot integrity | `SUPERSEDED_BY_V0_2_RECONSTRUCTION`; v0.1 remains immutable historical evidence and is not rewritten. |

## Non-discrepancy notes

- HiVenues Phase 2B branch `candidate-c/phase2b-production-substrate` existed at observation and resolved to the exact Phase 2A canonical baseline `bf9a0b4e...`; no Phase 2B implementation delta or open PR was observable. That is a valid just-opened phase state, not by itself a defect.
- PGH synthetic D1 readiness fixtures and absence of physical response data are deliberately consistent; synthetic readiness must not be misclassified as empirical evidence.
- NFC publication-main provenance hardening and frozen-canon identity coexist intentionally after the repair; they are not competing scientific canons.
