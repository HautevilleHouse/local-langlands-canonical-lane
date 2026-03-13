# Reviewer Map

## Claim Scope

- Canonical-lane claim: inside the `manifold_constrained` local correspondence lattice, if the theorem chain in this repository holds and the guard certificate passes, the repository-level super-lane closure claim is satisfied.
- Standard target claim: admissible `L`-group morphisms in the declared local correspondence lattice produce the predicted automorphic endpoint packets with matching local/global observables.
- External-strengthening rule: any statement beyond the admissible class must retain the explicit remainder carried by the defect/coherence ledgers; see `notes/GEOMETRIC_GALOIS_BRIDGE.md`.

## Super-Lane Families

The manuscript treats the following as routed sub-lane families inside one coordinating super-repo:

1. inner forms and pure inner twists,
2. supercuspidal and tempered packet assembly,
3. endoscopic packet transfer and character identities,
4. Weil-Deligne and inertial compatibility packages,
5. local-global compatibility stitching for the declared local packets.

## Theorem Dependency Chain

1. `EG1`: coercive local correspondence response and active floor.
2. `EG2`: local matching capture across the local correspondence lattice.
3. `EG3`: compactness and no-collapse spacing for packet towers.
4. `EG4`: rigidity and endpoint local correspondence.
5. Identification bridge: strict coherence on the determining class.
6. Scalar closure: `LLG_G1, LLG_G2, LLG_G3, LLG_G4, LLG_G5, LLG_G6, LLG_GM` all `PASS`.

Primary files:

- `paper/LOCAL_LANGLANDS_PREPRINT.md`
- `notes/EG1_public.md`
- `notes/EG2_public.md`
- `notes/EG3_public.md`
- `notes/EG4_public.md`
- `notes/IDENTIFICATION_BRIDGE.md`
- `notes/GEOMETRIC_GALOIS_BRIDGE.md`

## Closure Gates

| Gate | Constant | Description |
|------|----------|-------------|
| `LLG_G1` | `kappa_local` | projected local correspondence response has a strict positive floor |
| `LLG_G2` | `sigma_matching` | local matching defect stays above capture floor across admissible local correspondence losses |
| `LLG_G3` | `kappa_compact` | normalized near-failure packet towers are precompact |
| `LLG_G4` | `rho_rigidity` | bad nonfunctorial countermodels are excluded |
| `LLG_G5` | `packet_local` | rigid limits local correspondence to predicted target packets |
| `LLG_G6` | `eps_coh` | strict coherence on the determining class |
| `LLG_GM` | derived | final strict margin |

## Falsification Conditions

- `repro/certificate_runtime.json` has any non-`PASS` gate.
- `lane.active_lane != "manifold_constrained"`.
- `all_pass != true`.
- Any manifest hash mismatch under `repro/repro_manifest.json`.
- A verified counterexample to any routed sub-lane local correspondence theorem used by the super-repo.
