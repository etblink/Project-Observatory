# NFC SPEC Probe Action Representation Feasibility Gate — Preregistration v0.1

STATUS = PREREGISTERED

BASE_ACCEPTANCE_COMMIT = `74260a436272c4b7641c86e55164629370ddcc8e`
FROZEN_NFC_COMMIT = `ed3047c2cbc0abc34d2549dd27754e4d3d05af78`
FROZEN_NFC_TREE = `00ef55ff36d5e9663ca1ef2c9566e2bc1396f973`

## Question

Before demanding a linear/operator representation, does frozen SPEC already induce a canonical quotient-visible **probe action object** for each admissible probe `P`?

The candidate need not be a deterministic endomorphism. Allowed forms include:

- a typed map between certified quotient-visible objects;
- a partial map;
- a relation/span/correspondence between parent and post-probe response classes;
- a functorial action on response signatures;
- another mathematically equivalent typed action object.

The burden is to identify the strongest form actually licensed by frozen source and SPEC, without importing transition weights or hidden state.

## Required distinctions

- response assignment vs state transition;
- deterministic map vs relation/correspondence;
- action object vs linearization/operatorization;
- accessibility vs transition strength;
- quotient-visible class vs raw token state.

## Mandatory evidence lanes

1. Book I admissible processes, observational quotient, structural invariance, anti-smuggling.
2. Book III transfer compatibility and composition.
3. SPEC admissible probe, probe episode, response object, spectroscopic equivalence, transition ledger, multistep ledger, generator compatibility, no-hidden-loss.
4. LING assembly/context action as a positive composition template.
5. RH operator-origin only as a later-stage control; it may not be used to smuggle weights into this gate.

## Candidate objects to test

### Candidate A — response map

For fixed `P`:

`A_P^resp : [X] -> [Resp(X;P)]_Spec`.

Test well-definedness under replacement of `X` by an observationally/spectroscopically equivalent representative.

### Candidate B — transition relation

For fixed `P`:

`R_P subset Q_parent x Q_post`

where `([X],[X']) in R_P` iff a lawful probe episode `X --P--> X'` is certified by the SPEC transition machinery.

Test quotient invariance and composition under lawful probe chains.

### Candidate C — deterministic transition map

`A_P^state : [X] -> [X']`.

This passes only if frozen SPEC proves uniqueness of the post-probe class for fixed parent class and fixed probe.

## Mandatory adversarial tests

- **Representative dependence:** raw representatives cannot affect the action.
- **Hidden determinism:** a relation may not be promoted to a function without uniqueness.
- **Outcome-weight smuggling:** multiplicity or accessibility cannot be converted into probability.
- **Composition:** sequential lawful probe episodes must induce compatible relational/typed composition at the same declared scope.
- **Probe identity:** two probes with the same observed response profile are not automatically the same action unless the source says so.
- **LING analogy check:** use LING only to test whether typed composition/congruence is architecturally lawful, not to import linguistic grammar into SPEC.
- **RH control:** no aggregation/linearization is permitted in this gate.

## Success criterion

A positive result must identify a unique or canonical-equivalence-class action object whose definition is fully recoverable from frozen SPEC and source data.

## Outcome taxonomy

- `A__CANONICAL_TYPED_PROBE_ACTION_DERIVED`
- `B__CANONICAL_RELATIONAL_ACTION_DERIVED__DETERMINISTIC_MAP_NOT_FORCED`
- `C__RESPONSE_MAP_ONLY__NO_STATE_ACTION`
- `D__NO_CANONICAL_PROBE_ACTION_OBJECT`
- `E__UNDERDETERMINED`
- `F__REPAIR_REQUIRED`

## Routing

If A or B is accepted, the next gate may test canonical linearization/operatorization of the action object. No physical transition-strength interpretation is authorized by this gate.
