# NFC NS Interface Burden Evolution Law Design Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: 91d608cdaabd67b6ba5e0fbb10980cd2c8b26c04
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
What is the weakest typed evolution architecture for the Book-III interface burden I_n that respects its status as a level stock, uses existing finite collar/transition structure where lawful, records genuine boundary generation and loss separately, and avoids identifying I_n with the step increment B_n?

## Frozen inputs
- I_n = total certified defect load arising from the stabilized collar structure at stage n;
- B_n = certified boundary-defect increment generated during U_n -> U_{n+1};
- finite stabilized collar alphabet Sigma_partial;
- Book-II type transition operator T_partial on the collar alphabet;
- Book-III finite-balance/UCTI structure for the combined functional C_n = B_n^bulk - I_n;
- no current theorem separately evolves I_n.

## Candidate architectures
E1 Infer I_{n+1} by algebraically rearranging the UCTI for C_{n+1}.
E2 Set I_{n+1}=I_n+B_n.
E3 Positive collar-burden measure/state: represent I_n as total mass of a quotient-visible positive measure/vector mu_n over stabilized collar types, transport retained mass through a positive kernel induced by lawful collar transitions, and record new generation, migration, and genuine loss as separately typed terms.
E4 Raw collar-count evolution without burden weights/defect semantics.
E5 Arbitrary state recurrence chosen to recover downstream contraction.
E6 No coherent evolution architecture.

## Mandatory tests
1. stock/increment typing;
2. exact accounting of retained prior burden versus newly generated burden;
3. genuine loss channel is explicit and nonnegative;
4. migration/reclassification does not masquerade as generation/loss;
5. quotient/presentation invariance;
6. compatibility with T_partial only where the transition semantics actually apply;
7. additivity of total burden must be proved rather than presumed;
8. relation between generated boundary burden and Book-III B_n must be stated, not identified by name;
9. zero-change/identity-transfer case;
10. no downstream contraction assumptions baked into the evolution law.

## Outcomes
A COLLAR_BURDEN_MEASURE_EVOLUTION_DOMINATES_AS_FIRST_TARGET
B SMALL_NONDOMINATED_EVOLUTION_SET
C ONLY_ABSTRACT_STOCK_RECURRENCE_SURVIVES
D NO_NONCIRCULAR_INTERFACE_EVOLUTION_ARCHITECTURE
E REPAIR_REQUIRED
F UNDERDETERMINED

No frozen NFC mutation and no regularity claim.