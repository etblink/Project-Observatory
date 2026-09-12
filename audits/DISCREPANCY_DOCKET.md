# Discrepancy Docket

Status: CANONICAL_STATE_REFRESH_V0_3_CANDIDATE

Discovery of a discrepancy does not authorize repair.

| Docket ID | Project | Sources in tension | Observation | Materiality | Resolution status |
|---|---|---|---|---|---|
| OBS-D001 | NFC | `main@b8587ce3409e34c0dd4e56c61ee585c07798b0e5` vs `archive/nfc-canonical-ed3047c2@ed3047c2cbc0abc34d2549dd27754e4d3d05af78` | Default `main` contains only the stripped publication surface while the archived canonical ref contains the frozen scientific corpus. Repository-default identity and scientific-canon identity therefore remain divergent. | HIGH — provenance/canonical-source selection | BOUNDED_BY_ARCHIVE_CANON; cause/history not adjudicated; no repair authorized; unchanged in v0.3 |
| OBS-D002 | PGH | `CURRENT_STATE.md@d8a16161...` vs `audits/PGH1_ADVERSARIAL_PHYSICAL_INTERFACE_DESIGN_GATE_0_1_0.md@d8a16161...` and merge `d8a16161...` | `CURRENT_STATE.md` retains older routing language while the latest canonical merge integrates the adversarial physical-interface design gate and freezes a next scientific sequence beginning with apparatus realization and target freeze. | MEDIUM — routing/navigation freshness | RECORDED_CURRENT_STATE_LAG; latest merge/audit controls the newer operation; no PGH repair authorized; unchanged in v0.3 |
| OBS-D003 | FCP / PGH | FCP `main@a41bc6101b63140ee2687e0cf67a47ab6be77215` controlling hold/corrective vs PGH `main@d8a16161f33d3bb8f97c15f095ca651c169f5896` latest physical-interface design gate | FCP's current main is chronologically later because of Reduced-NFC provenance strengthening, but its cross-program sequencing corrective still describes an earlier PGH trigger-reassessment stage. PGH independently advanced beyond that stage to the qualified physical-interface design. | LOW-MEDIUM — cross-program routing freshness | TEMPORAL_CONTENT_LAG; no contradiction established in FCP scientific/taxonomy result or evidence-triggered hold; no repair authorized |
| OBS-D004 | NFC | Frozen Book II `cor:ls2-universal-K07` `[U]` status/proof vs `def:structural-phases` and `thm:LAR-from-DW-PhA` | The attempted universal LS-2 discharge obtains LAR using Phase-A, while Phase-A is itself defined to require LS-2 certification. At the audited source-forcing target this is a circular dependency and cannot establish LS-2 from antecedent quotient/locality/stabilization structure alone. The independent U002 countermodel separately establishes nonforcing, so the circularity does not make the audit unadjudicable. | HIGH — theorem status/dependency integrity for finite-interface sufficiency | OBSERVATORY_IDENTIFIED; SOURCE_REPAIR_NOT_AUTHORIZED. U002 accepted at `b4bd176246b7e4154241c2965a92faaf5a70d709`; frozen NFC labels remain unchanged unless NFC separately adjudicates/repairs them. |

## V0.3 note

`OBS-D004` is docketed because it is an internal dependency/status tension in the frozen source discovered during an accepted Observatory audit. Docketing does **not** amend the source theorem, change its canonical label, or authorize a repair.

More generally, accepted Observatory findings remain external analytical findings unless and until a separately governed source-project operation adopts or adjudicates them.
