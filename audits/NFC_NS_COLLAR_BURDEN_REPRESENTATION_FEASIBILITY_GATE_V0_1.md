# NFC NS Collar Burden Representation Feasibility Gate v0.1

PREREGISTRATION: 9fa3e2959f96956e17ca942c591798f553d4387a

## Outcome
B__POSITIVE_BURDEN_STATE_AVAILABLE__BURDEN_WEIGHTED_TRANSITION_LIFT_MISSING

## Finding
Frozen Books I-III supply enough structure for a minimal positive collar-burden state, but not for its nontrivial evolution.

At stage n, let tau_n be the realized stabilized collar type of the declared region U_n. Book III defines I_n as the nonnegative total certified defect load arising from that collar structure. Therefore the tagged positive measure

mu_n := I_n delta_{tau_n}

on the finite stabilized collar alphabet is a lawful minimal state representation at the realized stage, with total mass

||mu_n|| = I_n.

This construction introduces no new weighting across unrealized collar types and preserves the distinction between the scalar burden and its quotient-visible collar label.

## Representation levels

### L0 scalar I_n
FROZEN / AVAILABLE, but insufficient to carry collar-type state.

### L1 tagged scalar / Dirac burden state
AVAILABLE AS MINIMAL REPRESENTATION.

It packages the already-declared scalar burden with the realized stabilized collar type. It does not assert a new distribution of burden across multiple types.

### L2 burden function/measure across all collar types
NOT DERIVED GENERALLY.

Book-I defect-ledger additivity is additivity along survivor/refinement chains. It does not by itself assign each unit of interface burden to a unique collar-type coordinate across the entire alphabet. A richer per-type burden vector therefore requires an attribution/decomposition theorem if needed.

### L3 burden-weighted transition lift of T_partial
MISSING.

Book-II T_partial records the lawful transition relation among stabilized collar types. It does not specify how the burden magnitude I_n is retained, amplified, attenuated, or lost during a type transition. Thus applying T_partial to the support label of mu_n does not determine the mass of mu_{n+1}.

Conservative extensions with the same type transition but different burden-retention factors leave the existing frozen type-transition statements intact, establishing nonforcing of a unique burden-weighted lift.

### L4 full stock evolution
NOT AVAILABLE until L3 and generation/loss semantics are supplied.

## Key distinction
The state-space problem is smaller than previously feared: no new high-dimensional burden vector is required merely to represent the current interface stock. The actual missing theorem is quantitative transition semantics.

## Minimal missing bridge

T_NS-COLLAR-BURDEN-LIFT:
For each lawful stabilized collar transition tau -> tau', provide a quotient-visible positive burden transfer law that specifies the retained prior burden in the target collar state, with:
- identity-transition consistency;
- composition/refinement compatibility;
- nonnegative retained burden;
- explicit separation of retention/reclassification from newly generated burden and genuine loss;
- no normalization selected from downstream contraction needs;
- failure conditions.

A general version may be expressed as a positive kernel/operator on burden measures, but the one-realized-type case may reduce to a transition-dependent retention coefficient together with separately typed gain/loss terms.

## Relation to B_n
Book-III B_n remains a step increment. This gate does not identify B_n with retained mass, loss, or total next-stage burden. Its relation to the future generation term must be separately proved.

## Routing
NEXT_OPERATION = NFC_NS_COLLAR_BURDEN_WEIGHTED_TRANSITION_DESIGN_GATE_V0_1

No mutation of frozen NFC, FCP, or PGH.