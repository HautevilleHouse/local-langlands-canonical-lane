# EG1 Public Note (Projected Response Floor)

Mature wording: `projection / protected core`.

In-paper anchor: `paper/LOCAL_LANGLANDS_PREPRINT.md` (`LLG_G1`).

## Goal
Make the projected response floor explicit as the protected-core gate for `proving persistence of admissible local packets across Weil-Deligne parameters, inertial types, and inner-form packet data through a multi-lane local correspondence super-architecture`.

## Objects

- admissible class: the declared class `A` or routed admissible lattice in the main preprint.
- canonical/base object package: Let `u_tau` denote the admissible state package declared in the main preprint.
- projected core: the response sector controlled by `kappa_local`.
- carried remainder interface: downstream defect and coherence terms remain outside the protected core rather than being hidden in it.

## Closure Criterion

`LLG_G1` closes when `kappa_local` satisfies the response-floor requirement: projected local correspondence response has a strict positive floor.
This is the protected-core contribution to the strict margin `M_LLG`.

## Lemma Chain and Proof Payload

### Lemma EG1.1 (projection reduction)
On the declared admissible class, the response object may be read on the projected sector without changing the target gate.

Payload: verify that all quantities used by `kappa_local` are defined on the projected sector named in the main preprint.

### Lemma EG1.2 (protected-core floor)
If the projected response floor is positive on the admissible sector, then the core cannot collapse before the later transport and remainder gates are evaluated.

Payload: check the artifact key `kappa_local` and the corresponding extraction input/provenance record.

### Theorem EG1.3 (core gate closure)
If Lemmas EG1.1-EG1.2 hold and the runtime artifact accepts `kappa_local`, then `LLG_G1` supplies the projected/protected-core input to `M_LLG`.

## Current Instantiation

- gate: `LLG_G1`
- artifact key: `kappa_local`
- mature equivalent: `projection / protected core`
- audit surface: `artifacts/constants_registry.json`, `artifacts/constants_extracted.json`, and `repro/certificate_runtime.json`
