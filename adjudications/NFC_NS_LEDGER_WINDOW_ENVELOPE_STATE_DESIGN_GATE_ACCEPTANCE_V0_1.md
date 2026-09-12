# Acceptance — NFC NS Ledger Window Envelope State Design Gate v0.1

EXECUTION_COMMIT: ab27156b19b4618d65afd9e4c014195a58361c23

ACCEPTED_OUTCOME: A__SUPPORT_SUPREMUM_IS_MINIMAL_AUXILIARY_STATE

Independent review confirms that the nonnegative support supremum M_k is the smallest auxiliary state needed to control the successor-window discrepancy while leaving active transport-weighted averaging as the primary ledger-state map. It introduces no absolute ceiling, no weight floor, no endpoint assumption and no extra geometric semantics.

The remaining question is dynamical: whether the conditional visible-ledger recurrence and forward active-window structure imply decay or finite extinction of M_k strongly enough to make the discrepancy remainder summable/absorbable.

NEXT_OPERATION: NFC_NS_LEDGER_ENVELOPE_EVOLUTION_FEASIBILITY_GATE_V0_1

No mutation of frozen NFC, FCP or PGH.