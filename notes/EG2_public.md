# EG2 Public Note (Capture and Restart)

Mature wording: `transport / local-to-global transfer`.

In-paper anchor: `paper/LOCAL_LANGLANDS_PREPRINT.md` (`LLG_G2`).

## Goal
Expand the compressed capture/restart language into the local-to-global transport gate for `proving persistence of admissible local packets across Weil-Deligne parameters, inertial types, and inner-form packet data through a multi-lane local correspondence super-architecture`.

## Objects

- transport carrier: the admissible evolution, deformation, or routed lattice declared in the preprint.
- capture floor: `sigma_matching`.
- restart law: the normalization/re-entry rule that keeps corrective steps inside the admissible class.
- carried losses: defect, restart, and normalization losses that must remain explicit.

## Closure Criterion

`LLG_G2` closes when `sigma_matching` survives admissible losses and restart corrections: local matching defect stays above capture floor across admissible local correspondence losses.
This is the transport contribution to `M_LLG`.

## Lemma Chain and Proof Payload

### Lemma EG2.1 (transport accounting)
Every transport step used by the lane is charged to the declared defect ledger instead of being absorbed into prose.

Payload: verify that the capture constant `sigma_matching` is present in the constants registry and extraction inputs.

### Lemma EG2.2 (restart preservation)
Restart or normalization preserves the declared admissible class and does not create an untracked remainder.

Payload: inspect the repro script and guard output for the gate tied to `sigma_matching`.

### Theorem EG2.3 (capture gate closure)
If transport accounting and restart preservation hold, then `LLG_G2` carries local control forward without breaking admissibility.

## Current Instantiation

- gate: `LLG_G2`
- artifact key: `sigma_matching`
- mature equivalent: `transport / local-to-global transfer`
- audit surface: `repro/run_repro.sh` and `repro/certificate_runtime.json`
