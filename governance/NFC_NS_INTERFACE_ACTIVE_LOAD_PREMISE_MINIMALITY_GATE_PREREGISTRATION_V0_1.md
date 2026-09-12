# NFC NS Interface Active Load Premise Minimality Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: eabf276cf343e19c28d8c5272c9136829867cf89
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
What is the weakest explicit bridge between the frozen Book-III interface burden I_n and the newly constructed active boundary quotient-mass M_n that is sufficient to provide a typed interface-stock evolution law without silently redefining I_n?

## Candidates
M1 exact unit identity: I_n=M_n.
M2 fixed normalization: I_n=kappa_I M_n with kappa_I>0.
M3 uniform two-sided equivalence: a_I M_n <= I_n <= b_I M_n with 0<a_I<=b_I<infinity on the declared regime.
M4 one-sided domination only.
M5 no bridge.

## Tests
- assumption strength;
- same-state type safety;
- ability to transfer an exact/inequality recurrence for M_n to a proved recurrence bound for I_n;
- preservation of a genuine loss channel;
- uniformity requirements must be explicit;
- no contraction assumed in the bridge itself;
- no fitted constants from endpoint outcomes;
- compatibility with the fact that I_n and M_n are both defect-load quantities but frozen canon did not identify their normalization.

## Outcomes
A__EXACT_UNIT_IDENTITY_IS_MINIMAL
B__UNIFORM_TWO_SIDED_EQUIVALENCE_IS_MINIMAL
C__ONE_SIDED_BRIDGE_SUFFICES
D__NO_NONCIRCULAR_BRIDGE_SUFFICES
E__REPAIR_REQUIRED
F__UNDERDETERMINED

## Stop rule
Do not choose constants to obtain contraction. This gate asks only what bridge is minimally sufficient to transport witness-mass evolution into the frozen I_n state.