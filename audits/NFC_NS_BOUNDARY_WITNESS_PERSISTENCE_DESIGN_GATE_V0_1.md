# NFC NS Boundary Witness Persistence Design Gate v0.1

PREREGISTRATION: ca0c93859c2d3fcae18353dda5e56e488738c9fe
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Outcome
B__TYPED_LINEAGE_SCHEMA_AVAILABLE__GENUINE_RESOLUTION_SEMANTICS_MISSING

## Finding
The weakest noncircular persistence architecture is a quotient-visible witness-lineage system built from Book-III lawful transfer, together with target-context interface classification. Raw token identity is unnecessary and forbidden.

For a weighted boundary atom w generated at step n, let Lin(w) denote its lawful transport class under the composable Book-III transfer chain. At a later stage m, a representative/image may be classified relative to the target context as:

- INTERFACE_ACTIVE: a certified transported descendant remains represented in the target boundary subledger/collar burden;
- MIGRATED: a certified transported descendant exists but is no longer interface-local in the target context;
- RECLASSIFIED_OR_SPLIT_MERGED: lawful target representation differs while explicit provenance remains available;
- RESOLVED: burden has been genuinely removed by a separately certified loss rule;
- OBSTRUCTED: lawful persistence/classification cannot be established.

Only INTERFACE_ACTIVE burden contributes to the interface stock I_m. MIGRATED burden exits I_m but is not thereby globally annihilated. RESOLVED burden requires a genuine removal certificate. OBSTRUCTED is not counted as loss.

## Candidate adjudication
P1 raw witness identity — REJECTED by quotient/no-smuggling discipline.
P2 transport-class lineage plus collar restriction — PARTIAL SURVIVOR. It gives lineage and interface-vs-noninterface classification when the transferred witness is certified, but does not certify genuine resolution/removal.
P3 cumulative sum of all prior atoms — REJECTED; forbids lawful interface exit and guarantees artificial monotone accumulation.
P4 Markov persistence via T_partial — REJECTED; T_partial has transition structure, not licensed probability or burden-retention semantics.
P5 absence from next collar equals annihilation — REJECTED; absence can be migration/reclassification or obstruction.
P6 typed lineage with explicit statuses — ACCEPTED / MINIMAL GENERAL SCHEMA.
P7 no coherent mechanism — TOO PESSIMISTIC.

## Existing loss semantics and firewall
The frozen NS text records genuine H1/H2 removal channels on the Book-II visible ledger D=E+B. Those removals cannot be imported automatically into the interface-stock witness state: the same source explicitly states that transfer between ledger states requires a typed ledger-state map. Therefore a Book-II loss event may support RESOLVED only after an explicit witness-level attribution theorem connects that loss event to the boundary-witness lineage.

## Minimal missing bridge
T_NS-INTERFACE-WITNESS-STATUS:
For every active/generated boundary witness lineage and each lawful step, assign exactly one certified status transition among retained-interface, migrated, reclassified/split-merged, resolved, or obstructed, using quotient-visible transfer and ledger evidence. If RESOLVED is assigned, bind it to a genuine loss event on an already certified loss channel. Weight transformation under split/merge must be explicit and additive.

This theorem is prior to any contraction estimate. It supplies the semantics necessary to write an actual stock recurrence for I_n.

## Consequence
If T_NS-INTERFACE-WITNESS-STATUS is proved, define

I_n = total weight of INTERFACE_ACTIVE witness lineages at stage n.

Then the one-step stock identity has the form

I_{n+1} = I_n - L_n^interface + G_n^boundary + M_n^net,

where L_n^interface is certified interface exit/resolution burden, G_n^boundary is newly generated boundary atom burden (the already atomized B_n channel), and M_n^net records explicitly certified split/merge/reclassification weight changes. This identity is a target, not yet a theorem.

## Next operation
NFC_NS_INTERFACE_WITNESS_STATUS_FEASIBILITY_GATE_V0_1

No mutation of frozen NFC, FCP or PGH.