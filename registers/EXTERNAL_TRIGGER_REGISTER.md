# External Trigger Register

Status: CANONICAL_STATE_RECONSTRUCTION_V0_2_READY_TO_FREEZE

This register records genuine external dependencies rather than substituting artificial work. Historical triggers are retained where they explain a state transition.

| Trigger ID | Project | External condition/event | Current state | Consequence when satisfied | Evidence/source |
|---|---|---|---|---|---|
| EXT-FCP-001 | FCP | Material new evidence independently satisfies FCP sequencing governance | `UNSATISFIED / OPEN_ENDED` | A separately preregistered FCP scientific operation may become eligible for selection | FCP sequencing corrective; `CURRENT_STATE.md@a41bc610...` |
| EXT-PGH-001 | PGH | A real conforming D1 apparatus is physically realized so exact switch/acquisition identity, three channels, wiring, custody, protocol metadata, and hashes can be bound prospectively | `UNSATISFIED` | Apparatus realization and target freeze may begin; negative-only analysis preregistration must still precede trials | PGH `CURRENT_STATE.md@2923875b...`; D1 readiness package |
| EXT-HV-001 | HIVenues | GPT-6 Astra usage capacity permits continuation of the isolated greenfield challenge | `RETIRED__NO_LONGER_LOAD_BEARING` | None; the relevant independent result is already frozen | Observatory v0.1 trigger history; HiVenues Issue #245 records GPT-6 Astra greenfield as frozen |
| EXT-HV-002 | HIVenues | Independent Fable/Astra greenfield results are completed/frozen before cross-pollination | `SATISFIED` | Candidate C synthesis may use the preserved independent discoveries | HiVenues Issue #245: both greenfields `FROZEN`, identities revealed after blind adjudication |
| EXT-HV-003 | HIVenues | A later separately qualified operation explicitly authorizes live-host migration or Hive/provider/payment/signing/deployment/DNS/VPS effects | `DEFERRED__NOT_CURRENT_PHASE` | Only then may the relevant external mutation be considered | HiVenues Issue #258 hard safety boundary |

## Current external-blocker summary

- **PGH** has the only concrete immediate physical blocker: no actual D1 apparatus is yet bound.
- **FCP** is evidence-gated rather than hardware-gated; no qualifying evidence event is currently established.
- **HiVenues Phase 2B** is not externally blocked. Production/external effects are explicitly out of scope, not prerequisites for the active phase.
- **NFC** has no external blocker for a future separately governed closed-source audit, but this pass does not select one.
