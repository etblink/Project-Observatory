# NFC SPEC-YM Gauge-Response Interaction Current Realization Gate — Preregistration v0.1

STATUS = PREREGISTERED

BASE_ACCEPTANCE_COMMIT = `cae84fde08737ea1131d62c49557c4f0a629fee6`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`

## Question

Can the frozen gauge-response SPEC regime, together with the frozen YM gauge/operator structure, instantiate a nontrivial subclass of admissible probes as physical interaction currents/operators `J_SPEC(P)` without importing measured branching ratios, external transition amplitudes, or an undeclared matter/source sector?

## Scope

This is a restricted realization gate. It may use only frozen SPEC and YM structure, plus spine imports explicitly declared by those branches. SM matter/current structure is excluded except as a negative control showing what YM alone lacks.

## Candidate subclasses

1. gauge-transformation probes;
2. connection/field perturbation probes;
3. curvature-response probes;
4. covariant-Laplacian perturbation probes;
5. source/current insertions into YM equations;
6. boundary/collar gauge interventions;
7. no nontrivial YM-only current subclass.

## Realization criteria

A candidate probe subclass passes only if:

- the probe is already lawful/quotient-visible at frozen SPEC/YM scope;
- a canonical map into the YM/SPEC operator arena can be written from frozen structure;
- the image is physically interaction-like rather than gauge redundancy or bookkeeping;
- no empirical transition strengths are used to define the map;
- the map has a declared zero-probe limit and composition/update rule;
- gauge covariance and branch-scope restrictions are explicit;
- the construction produces potential observable residue beyond support/reachability.

## Mandatory adverse tests

- gauge-redundancy test;
- source-free-YM test;
- perturbation-without-current test;
- operator-domain test;
- hidden matter-sector test;
- hidden coupling-normalization test;
- empirical circularity test.

## Outcome taxonomy

- `A__NONTRIVIAL_YM_ONLY_PROBE_CURRENT_SUBCLASS_DERIVED`
- `B__RESTRICTED_YM_PROBE_CURRENT_CANDIDATE_CONSTRUCTIBLE__NEW_PREMISE_REQUIRED`
- `C__YM_OPERATOR_PERTURBATION_STRUCTURE_EXISTS__PHYSICAL_CURRENT_NOT_DERIVED`
- `D__PURE_YM_GAUGE_RESPONSE_DOES_NOT_INSTANTIATE_PHYSICAL_PROBE_CURRENT`
- `E__UNDERDETERMINED`
- `F__REPAIR_REQUIRED`

## Routing

If C or D is earned, the next candidate lane should test whether the frozen/conditional SM matter sector supplies the missing source/current object without circularly importing empirical transition amplitudes. If A/B is earned, proceed instead to coupling/strength derivability within that restricted subclass.
