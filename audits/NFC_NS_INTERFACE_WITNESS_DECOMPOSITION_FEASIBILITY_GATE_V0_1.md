# NFC NS Interface Witness Decomposition Feasibility Gate v0.1

PREREGISTRATION: 0b076f4736df2eba9718fe47191d8b0cfa55b892
FROZEN_NFC: ed3047c2cbc0abc34d2549dd27754e4d3d05af78

## Outcome
B__NONCIRCULAR_WITNESS_DECOMPOSITION_SCHEMA_AVAILABLE__ONE_MINIMAL_BRIDGE_MISSING

## Evidence adjudication

### Book I
The primitive one-step defect number delta(C_n) is the number of descendant classes minus one. The defect ledger is additive along survivor chains, and the entropy proof interprets each defect event as one class-splitting event. This provides finite, nonnegative, quotient-level defect units and additive arithmetic.

However, Book I does not define a persistent interface-defect witness object, an active-vs-resolved status, or a map from a later interface stock to the historical class-splitting events that remain load-bearing.

### Book II
LS-2 provides a finite stabilized collar arena, a boundary law and collar-type transition structure. This is sufficient to localize a prospective interface witness at the quotient-visible collar level and prevents raw-token identity smuggling.

It does not define interface-burden mass or identify which defect events remain active at a later stage.

### Book III
I_n is defined as the total certified defect load arising from the collar structure of U_n. B_n is separately defined as the certified boundary-defect increment produced during U_n -> U_{n+1}. UCTI accounts for stepwise boundary defect through B_n and uses witness-preserving transfer maps for already-certified observable data.

No theorem identifies I_n with B_n, a cumulative sum of B_m, or the mass of a set of persistent boundary-defect witnesses. Such an identification would repeat the stock/increment error rejected by MIG-052.

## Minimal missing bridge
The smallest missing object is not a new transport coefficient. It is an active-witness attribution theorem:

T_NS-INTERFACE-WITNESS-ATTR:
For every stage n, there exists a finite quotient-visible multiset W_n of certified interface-defect witness classes with nonnegative ledger weights q_n(w), together with an active-status predicate, such that

I_n = sum_{w in W_n, active_n(w)} q_n(w),

and the attribution depends only on licensed collar/ledger data.

The theorem must specify how an underlying Book-I defect/class-splitting event becomes an interface-local witness and what it means for that burden to remain active at stage n. It may not infer activity from I_n itself.

Once T_NS-INTERFACE-WITNESS-ATTR holds, existing witness-preserving transfer maps provide the natural arena in which a later theorem can classify retained, lost, split/merged and newly generated witness burden. They do not by themselves prove the attribution theorem.

## Adversarial tests
- Exact additivity: CONDITIONAL PASS under T_NS-INTERFACE-WITNESS-ATTR; not proved by current canon.
- Quotient visibility: PASS in the proposed schema by using collar/witness classes rather than token identities.
- Stock/increment firewall: PASS; B_n remains a step increment and is not identified with I_n.
- Transfer provenance: STRUCTURALLY AVAILABLE after attribution through Book-III witness-preserving maps.
- Split/merge semantics: OPEN downstream; must be explicit.
- Loss semantics: OPEN downstream; disappearance from the current collar is not automatically annihilation.
- Contraction smuggling: PASS; no coefficient or monotonicity assumed.
- Endpoint fitting: PASS; decomposition is pre-endpoint bookkeeping.

## Scientific interpretation
The current canon contains enough structure to make an interface-witness decomposition mathematically coherent and tightly typed, but not enough to derive it. The gap is narrower than the prior common-state obligation: it is the missing attribution from scalar interface stock to active quotient-visible defect witnesses.

## Next operation
NFC_NS_INTERFACE_WITNESS_ATTRIBUTION_MINIMALITY_GATE_V0_1

No mutation of frozen NFC, FCP or PGH.