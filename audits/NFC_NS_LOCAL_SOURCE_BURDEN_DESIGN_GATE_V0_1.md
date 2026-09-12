# NFC NS Local Source Burden Design Gate v0.1

PREREGISTRATION: 0d9ed6a90778a6f46b66652d628daf1fef180e06

## Outcome
B__PROFILE_VALUED_LOCAL_BURDEN_IS_MINIMAL__SCALARIZATION_OPEN

## Finding
The weakest prospectively meaningful local source burden is the already-admitted multiscale force descriptor applied after lawful context restriction and retained componentwise:

B_F(alpha,U_j) := Q_{Res_{U_j}(alpha)}^{Pi,N,a}.

This object remains profile-valued over the declared source decomposition/scale indices. It distinguishes amplitude and scale distribution while preserving source provenance. No scalar aggregation is justified at this stage.

## Candidate adjudication
### B1 restricted multiscale profile
ACCEPTED as minimal. It is source-only, prospective, compatible with restriction, and can be defined representation-invariantly through the basis-free/reconstruction equivalence machinery already isolated upstream.

### B2 scalar norm
NOT YET JUSTIFIED. Different scale distributions can share the same scalar norm; frozen NFC supplies no theorem proving those sources equivalent for continuation purposes.

### B3 local work/energy injection
REJECTED as primary source burden. It depends on the evolving state u and is therefore a source-response diagnostic rather than source-only input data.

### B4 defect-like count
REJECTED. Exogenous source burden is not the endogenous defect ledger; copying that bookkeeping would erase the type distinction established by the forced-scope audit.

### B5 raw dictionary coefficients
REJECTED as canonical object. They are representation-relative; only their reconstruction-equivalence class has basis-independent meaning.

## Adversarial tests
- Same incidence/different amplitude: PASS; profile scales accordingly.
- Same scalar norm/different scale distribution: PASS; profiles remain distinct.
- Component cancellation: PASS by componentwise storage before optional aggregation.
- Dictionary invariance: PASS conditionally through reconstruction equivalence.
- Bounded solution energy: irrelevant to definition; does not force small source burden.
- Compact support: determines localization/provenance, not burden magnitude.

## Window ledger form
For a window W_k define the pre-transport source ledger

L_F(W_k) := { (alpha,j,B_F(alpha,U_j),provenance(alpha)) : j in W_k and Res_{U_j}(alpha) != 0 }.

This ledger is not yet transport-weighted and does not alter the endogenous defect ledger.

## Sharpened frontier
localized source components
 -> profile-valued burden B_F(alpha,U_j)
 -> pre-transport source ledger L_F(W_k)
 -> ? source transport law / weighting
 -> ? source-driven continuation inequality
 -> forced common-state bridge.

No source-project mutation and no forced-regularity claim.