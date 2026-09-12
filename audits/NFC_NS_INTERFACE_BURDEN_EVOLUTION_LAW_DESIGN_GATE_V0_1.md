# NFC NS Interface Burden Evolution Law Design Gate v0.1

PREREGISTRATION: 8f47602d34216c425e1755129bfd28b9d9bcbef5

## Outcome
A__COLLAR_BURDEN_MEASURE_EVOLUTION_DOMINATES_AS_FIRST_TARGET

## Controlling type distinction
Book III defines I_n as a level stock: the total certified defect load arising from the collar structure at stage n. It defines B_n as a boundary-defect increment generated during the step U_n -> U_{n+1}. A lawful evolution theorem must therefore evolve a stock by accounting for retained/reclassified prior burden, genuine loss, and genuinely new burden. It may not set I_n=B_n or I_{n+1}=I_n+B_n without further proof.

## Selected architecture — E3
Represent the interface burden by a quotient-visible positive collar-burden measure/vector

mu_n in M_+(Sigma_partial)

on the finite stabilized collar alphabet, with

I_n = ||mu_n||_1

or the corresponding certified total-mass functional.

For one admissible enlargement, decompose the old burden stock into a retained submeasure r_n <= mu_n and a genuine loss measure l_n := mu_n-r_n. Let P_n be a positive reclassification/transport kernel on retained collar burden, derived from or constrained by the lawful collar-type transition relation. Let g_n be newly generated interface burden and m_n be any separately certified migration into the interface from a non-interface channel.

The candidate stock evolution is

mu_{n+1} = P_n r_n + g_n + m_n,

with

mu_n = r_n + l_n.

Equivalently, after a lawful extension of P_n to the full old measure, one may write a gain-loss form, but the retained/lost decomposition must remain explicit enough to prevent double counting.

Taking total mass gives a legitimate level-to-level burden accounting once all component measures are certified.

## Candidate adjudication

### E1 solve for I_{n+1} from UCTI
REJECTED. The UCTI is an inequality for the combined functional C_n=B_n^bulk-I_n and does not separately evolve bulk stability or interface stock. Algebraic rearrangement would manufacture information not contained in the inequality.

### E2 I_{n+1}=I_n+B_n
REJECTED. It assumes perfect retention, no removal, no reclassification effects, no migration, and equates every boundary increment with new stock.

### E3 positive collar-burden measure evolution
SELECTED. It matches the finite collar alphabet, allows the existing collar-type transition structure to constrain reclassification, and keeps generation/loss/migration typed separately.

### E4 collar counts only
INSUFFICIENT. Number of collar sites/types is not yet the certified defect load carried by those types.

### E5 arbitrary recurrence chosen for contraction
REJECTED as circular.

### E6 no architecture
REJECTED; E3 is coherent.

## Relationship to Book-II T_partial
The existing type transition operator establishes a lawful finite relation among stabilized collar types. It is strong evidence that reclassification can be represented on a finite type space. However current canon does not state that interface defect burden is a positive measure on that type space or that T_partial transports burden mass with a specified normalization. Those statements require a separate bridge.

## Relation to Book-III B_n
B_n is a certified boundary-defect increment during U_n -> U_{n+1}. It is a candidate input to the new-generation measure g_n, but the equality

||g_n|| = B_n

is NOT established here. A future theorem must determine whether B_n exhausts newly generated interface stock, whether some increment is immediately lost/transient, and whether interior-to-interface migration contributes separately.

## Minimal next bridge

T_NS-COLLAR-BURDEN-REP:
1. represent each stage's certified interface burden as a positive quotient-visible measure/vector on stabilized collar types whose total mass is I_n;
2. prove a lawful retained/lost decomposition across enlargement;
3. derive a positive reclassification kernel from the certified collar transition structure;
4. identify the source and semantics of genuinely new generation and any migration channel;
5. prove refinement/presentation invariance and exact no-double-count accounting.

## Why this is high information
If this representation fails, the present common-state architecture lacks the finite state variable needed for a genuine interface-burden evolution law. If it succeeds, an exact stock evolution becomes available before any contraction estimate, directly advancing common-state burdens A/B and constraining later ledger-state mapping.

## Routing
NEXT_OPERATION = NFC_NS_COLLAR_BURDEN_REPRESENTATION_FEASIBILITY_GATE_V0_1

No mutation of frozen NFC, FCP, or PGH.