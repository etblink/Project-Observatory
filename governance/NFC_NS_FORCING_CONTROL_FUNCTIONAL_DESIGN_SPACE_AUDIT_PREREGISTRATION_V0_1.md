# NFC NS Forcing-Control Functional Design-Space Audit — Preregistration v0.1

STATUS = PREREGISTERED

BASE_ACCEPTANCE_COMMIT = `71fb2da441133abfcf556765bf4744d21417f9d9`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`
FCP_OPENAI_NS_SOURCE_INTAKE_MERGE = `d2c3014357ed1de66849f66c5a8cc08e0d453b4b`
FCP_OPENAI_NS_LOAD_BEARING_AUDIT_MERGE = `de51ef31b86993034e93be56a7b2cff468ffdb66`
FCP_OPENAI_NS_EXTERNAL_REVIEW_INTAKE_MERGE = `6770011acefcc36f57f1492c08ff58f6442ba6f1`

## Question

What is the smallest prospectively definable forcing-control functional, or small nondominated family of such functionals, that could be added to the accepted NFC-NS forced-scope extension schema without smuggling in outcome data, while correctly treating the OpenAI 2026 smooth compactly supported forced-blowup construction as an adversarial negative control?

This is a design-space audit, not a proof of forced regularity and not an NFC-canon mutation.

## Frozen control

The OpenAI/FCP construction is fixed before adjudication as follows:

- dimension 3;
- incompressible Navier–Stokes;
- every viscosity `nu > 0`;
- smooth compactly supported external force;
- initial velocity `u_0 = 0`;
- uniformly bounded kinetic energy / `L^2` norm;
- finite-time `L^infty` velocity blowup claimed at `t -> 1`;
- FCP targeted audits found no material load-bearing defect at their declared scope;
- no Clay/global-consensus/unforced-problem/NFC promotion is imported.

A candidate fails the adversarial-control gate if, under a naive or claimed sufficient forced-regularity criterion, it would classify this construction as safely subcritical while all other hypotheses are satisfied, unless the candidate prospectively identifies a concrete independent hypothesis that fails on this control.

## Candidate families

At minimum adjudicate:

F1. cumulative energy/work injection, e.g. an integral of pairing between force and velocity;
F2. force-only norm control independent of realized velocity, including time-space norms compatible with the branch continuum interface;
F3. scale-local / frequency-local forcing burden;
F4. source-ledger growth or renewal-count burden in the NFC discrete/window architecture;
F5. transport-weighted source burden aligned with the existing NS averaging/window machinery;
F6. source-to-dissipation ratio or reserve-margin functional;
F7. support/geometry-sensitive forcing burden;
F8. history-sensitive/common-state forcing descriptor;
F9. hybrid functional combining at least two nonredundant source features;
F10. no justified candidate at present.

## Mandatory criteria

For a candidate `N_F(F)` or `N_F(F; state)` to survive, it must:

1. be defined prospectively, before outcome frequencies/blowup status are consulted;
2. keep external forcing distinct from endogenous defect burden;
3. have a declared mathematical domain and comparison scope;
4. be compatible with the NFC-NS common-state and window architecture or clearly state the required extension;
5. avoid defining safety by the desired conclusion;
6. avoid post-hoc threshold choice on the OpenAI construction;
7. distinguish mere compact support/smoothness from quantitative source control;
8. have an explicit scaling/normalization policy;
9. state whether it is force-only, state-coupled, or history-coupled;
10. identify the precise theorem burden needed to connect the functional to continuation;
11. survive zero-initial-data reversal: `u_0=0` must not make the source burden vanish merely because the current unforced criterion is favorable;
12. survive bounded-energy reversal: bounded kinetic energy must not by itself imply source subcriticality;
13. preserve the accepted separation between common-state bridge and UWB;
14. not use the OpenAI construction to fit coefficients or choose the formula after the fact.

## Special anti-circularity tests

### A. Work-injection circularity
If a functional uses `u`, determine whether its value can only be known after solving the same dynamics whose regularity is under test. Such a functional may still be useful as an a posteriori criterion, but it does not qualify as an independent prospective source descriptor without an upstream bound.

### B. Norm monotonicity trap
Smooth compact support does not imply smallness in any relevant norm. A candidate may not infer subcriticality from smoothness/support alone.

### C. Scale concentration trap
A global norm that misses concentration into a dynamically dangerous scale must be marked incomplete unless a theorem proves that the omitted scale information is irrelevant.

### D. Window-renewal compatibility
If a candidate is mapped into the existing NFC window ledger, the map must be typed and must not identify source events with endogenous defect events by definition.

### E. Affine-contraction non-smuggling
A schematic forced recurrence such as `O_{k+m} <= q O_k + S_k` is not itself a theorem. Any `S_k` must be independently defined and linked to the physical forcing.

## Outcome taxonomy

A. `UNIQUE_MINIMAL_FORCING_CONTROL_FUNCTIONAL_IDENTIFIED`
B. `SMALL_NONDOMINATED_FUNCTIONAL_SET_IDENTIFIED`
C. `ONLY_A_POSTERIORI_OR_STATE_COUPLED_CRITERIA_SURVIVE`
D. `NO_NONCIRCULAR_FORCING_CONTROL_FUNCTIONAL_IDENTIFIED`
E. `OPENAI_CONTROL_REVEALS_INCOMPATIBILITY_WITH_PROPOSED_FORCED_EXTENSION`
F. `UNDERDETERMINED`
G. `REPAIR_REQUIRED`

## Routing discipline

No frozen NFC mutation.
No FCP scientific readjudication.
No claim that the OpenAI proof is globally accepted or Clay-recognized.
No inference from this audit to unforced Navier–Stokes unless separately proved.

If Outcome B is reached, select the lowest-assumption candidate for a separate source-derivability / OpenAI-control stress test. If only state-coupled functionals survive, explicitly distinguish prospective parameterization from a posteriori continuation criteria.