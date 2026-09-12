# NFC NS Quotient Witness Mass Evolution Feasibility Gate — Preregistration v0.1

STATUS: PREREGISTERED
BASE_ACCEPTANCE: d27727d35bc6b2f03e2bb30e94b9eadd823683e0
SOURCE_PROJECT_MUTATION: FORBIDDEN

## Question
Given the accepted canonical boundary atomization and quotient-image status/loss construction, does the constructed active boundary witness mass M_n obey an exact finite one-step bookkeeping law under a complete lawful transfer step?

## Definitions to test
Let A_n be the deduplicated family of INTERFACE_ACTIVE weighted split distinctions at stage n, M_n=Mass(A_n).

Under lawful transfer f_n:
- L_n^q: within-lineage quotient-image coalescence loss;
- X_n^mig: retained distinguishability whose certified target image is outside the target interface/collar burden;
- C_n^merge: additional cross-lineage deduplication loss when distinct source lineages collapse to already-counted identical target distinctions;
- G_n^bdry: newly generated target boundary split mass, canonically identified with the step boundary-generation ledger B_n, after deduplication against transported target distinctions if the same distinction would otherwise be counted twice.

Candidate balance:
M_{n+1}=M_n-L_n^q-X_n^mig-C_n^merge+G_n^bdry.

An equivalent set-level definition may be preferred if it avoids signed bookkeeping artifacts:
A_{n+1}=Dedup((f_n[A_n] restricted to target boundary) union NewBoundaryAtoms_n),
M_{n+1}=Mass(A_{n+1}).

## Mandatory tests
- finite/nonnegative terms;
- exact no-double-counting;
- identity transfer/no generation gives M_{n+1}=M_n;
- pure quotient coalescence decreases mass exactly by L_n^q/C_n^merge;
- pure migration removes only interface mass, not global provenance;
- pure new boundary generation increases by its deduplicated mass;
- obstructed/undefined transfer blocks theorem rather than being called loss;
- no contraction coefficient;
- no use of I_n or active-load comparison in proving the M recurrence;
- no endpoint dependence.

## Outcomes
A__EXACT_FINITE_WITNESS_MASS_EVOLUTION_DERIVED
B__ONE_ADDITIONAL_DEDUP_OR_MIGRATION_BRIDGE_REQUIRED
C__ONLY_ONE_SIDED_MASS_BALANCE_DERIVABLE
D__NO_COHERENT_MASS_EVOLUTION
E__REPAIR_REQUIRED
F__UNDERDETERMINED

## Stop rule
This gate concerns the constructed M_n only. Do not promote the result to frozen I_n without the separately accepted two-sided active-load bridge.