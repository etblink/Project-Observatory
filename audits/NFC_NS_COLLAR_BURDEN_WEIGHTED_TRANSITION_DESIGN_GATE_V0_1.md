# NFC NS Collar Burden Weighted Transition Design Gate v0.1

PREREGISTRATION: de5b993fc46c5bf700087233fde13639945b2c36

## Outcome
A__WITNESS_PERSISTENCE_LIFT_DOMINATES_AS_FIRST_TARGET

## Finding
The weakest noncircular burden-weighted lift is not a free retention coefficient. It is an event/witness persistence accounting built on the witness-preserving nature of lawful Book-III transfer.

## Selected architecture — W2
For each stage n, seek a finite quotient-visible weighted multiset of certified interface-defect witnesses

W_n = {(w_i, q_i)}

with q_i >= 0 and

I_n = sum_i q_i.

A lawful transfer f_n induces, where defined, a partial witness map

p_n : W_n -> W_{n+1}

on certified burden witnesses. The accounting classes are then:

- RETAINED: old witnesses with lawful images under p_n;
- LOST: old witnesses with no retained target image or with separately certified discharge/removal;
- NEW: target witnesses not descended from any retained old witness;
- SPLIT/MERGED: permitted only with an explicit provenance map conserving or otherwise lawfully transforming certified burden weight.

The retained burden is determined by the certified images and their declared weight-transfer rule, not by a coefficient selected for desired contraction. The collar type transition tau_n -> tau_{n+1} constrains which witness transitions are admissible but does not itself determine the weights.

## Candidate adjudication

### W1 arbitrary retention coefficient
REJECTED AS PRIMITIVE. It is mathematically possible but scientifically unconstrained and can be tuned to manufacture contraction.

### W2 witness-level partial persistence map
SELECTED. It reuses the witness-preserving transfer concept already present in Book III and makes retention/loss/generation auditable before aggregation.

### W3 Markov/stochastic lift
REJECTED absent probability semantics. The collar transition graph is not a stochastic process by default.

### W4 Perron-Frobenius retention factor
REJECTED. Spectral properties of the type adjacency/transition operator do not by themselves equal retained defect burden.

### W5 adjacency only
INSUFFICIENT because it carries no burden magnitude.

### W6 no coherent lift
REJECTED; W2 is coherent as a target.

## Identity and composition tests
- Identity transfer: all witnesses are retained with unchanged burden unless an independently certified loss/generation operation occurs.
- Zero burden: empty/zero-weight witness state remains zero under pure retention.
- Composition: provenance maps must compose; a witness retained over two steps must have a composed certified lineage.
- Refinement/presentation: witness classes and weights must depend only on licensed quotient-visible structure.
- No double count: every target burden witness belongs to exactly one declared provenance class (retained lineage, new generation, or lawful merged/split lineage).

## Minimal missing theorem

T_NS-INTERFACE-WITNESS-DECOMP:
Prove that the Book-III interface burden I_n admits a finite additive decomposition into certified quotient-visible interface-defect witnesses with nonnegative weights, and that lawful transfer maps induce provenance-preserving partial maps on those witnesses with a certified weight-transfer rule.

This theorem would immediately define retained and lost prior burden and isolate genuinely new target burden before any contraction estimate.

## Relation to Book-I ledger
Book-I ledger additivity supports additive accounting along refinement histories, but current canon does not explicitly identify its primitive defect arithmetic with a unique interface-witness decomposition of I_n. That identification is part of T_NS-INTERFACE-WITNESS-DECOMP rather than assumed here.

## Relation to B_n
After a witness decomposition exists, B_n can be tested against the total weight of NEW boundary witnesses generated during the step. Equality, inequality, or only partial overlap remains to be adjudicated separately.

## Routing
NEXT_OPERATION = NFC_NS_INTERFACE_WITNESS_DECOMPOSITION_FEASIBILITY_GATE_V0_1

No mutation of frozen NFC, FCP, or PGH.