# Discrepancy Docket

Status: CANONICAL_STATE_RECONSTRUCTION_V0_1

Discovery of a discrepancy does not authorize repair.

| Docket ID | Project | Sources in tension | Observation | Materiality | Resolution status |
|---|---|---|---|---|---|
| OBS-D001 | NFC | `main@b8587ce3409e34c0dd4e56c61ee585c07798b0e5` vs `archive/nfc-canonical-ed3047c2@ed3047c2cbc0abc34d2549dd27754e4d3d05af78` | Default `main` contains only README/CITATION/LICENSE even though those metadata describe a repository hosting the PDF/TeX canon. The archived canonical ref contains the frozen scientific corpus. Repository-default identity and scientific-canon identity therefore diverge. | HIGH — provenance/canonical-source selection | BOUNDED_BY_ARCHIVE_CANON; cause/history not adjudicated; no repair authorized |
| OBS-D002 | PGH | `CURRENT_STATE.md@d8a16161...` vs `audits/PGH1_ADVERSARIAL_PHYSICAL_INTERFACE_DESIGN_GATE_0_1_0.md@d8a16161...` and merge `d8a16161...` | `CURRENT_STATE.md` still names PGH-OP-0115/0116 and `NEXT_RECOMMENDED_OPERATION = NONE`, while the latest canonical merge integrates the adversarial physical-interface design gate and freezes a next scientific sequence beginning with apparatus realization and target freeze. | MEDIUM — routing/navigation freshness | RECORDED_CURRENT_STATE_LAG; latest merge/audit controls the newer operation; no PGH repair authorized |
| OBS-D003 | FCP / PGH | FCP `main@e7dd1473...` vs later PGH `main@d8a16161...` | FCP's latest corrective properly preserves its evidence-triggered hold but describes PGH's next step as the read-only post-FCP trigger reassessment. PGH subsequently completed that phase and later merged the physical-interface design gate. | LOW-MEDIUM — cross-program routing freshness | TEMPORAL_LAG; no contradiction established in FCP scientific/taxonomy result; no repair authorized |
