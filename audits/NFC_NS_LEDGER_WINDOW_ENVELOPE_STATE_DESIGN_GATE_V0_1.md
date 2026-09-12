# NFC NS Ledger Window Envelope State Design Gate v0.1

PREREGISTRATION: b1a481d6893b51641523df3fb9e073c34f56353a
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Outcome
A__SUPPORT_SUPREMUM_IS_MINIMAL_AUXILIARY_STATE

## Selected state
For the combined support used by the successor-window discrepancy, define

M_k := max { D_j : j in supp(mu_{k+1}) union supp(S mu_k) }.

Because the visible ledger D_j is nonnegative,

osc_k(D) = max D_j - min D_j <= M_k.

Therefore the already accepted discrepancy estimate sharpens to

|Delta_k^win(D)| <= TV(mu_{k+1},S mu_k) M_k.

M_k is dynamic state data, not an absolute ceiling and not a new physical constant.

## Candidate adjudication
E1 support supremum — ACCEPTED / MINIMAL. One nonnegative scalar controls the exact oscillation term and is well-defined on arbitrary finite supports without requiring monotonicity, contiguity or a weight floor.

E2 support range — mathematically exact but strictly more state than necessary for an upper bound; its separate min component complicates evolution and offers no current downstream benefit.

E3 total variation of ledger values — stronger than required and depends on an ordering/path through the support.

E4 endpoint pair — viable only after proving every relevant support is contiguous and the ledger is monotone across it. Those are downstream/conditional facts, so it is not the minimal unconditional auxiliary.

E5 period-block maximum — useful possible specialization but introduces the eventual period and does not improve the basic support-supremum object.

E6 no auxiliary state — insufficient after the weight-floor route failed.

## Firewall
The primary ledger-state map remains the componentwise active transport-weighted average A_k. M_k exists solely to control the window-measure mismatch remainder. No identification M_k=A_k(D), no absolute uniform bound on M_k, and no contraction claim is made here.

## Next operation
NFC_NS_LEDGER_ENVELOPE_EVOLUTION_FEASIBILITY_GATE_V0_1

That gate must determine whether the conditional Book-II visible-ledger recurrence, the temporal ordering of successive windows and the current H1/H2/renewal structure imply a closed bound of the form

M_{k+1} <= q_M M_k + r_k

with q_M<1 or a finite-extinction alternative, or whether an additional pointwise lower-loss comparison is missing.

No mutation of frozen NFC, FCP or PGH.