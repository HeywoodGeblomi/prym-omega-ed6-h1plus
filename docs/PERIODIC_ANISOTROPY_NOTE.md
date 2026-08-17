# Periodic Anisotropy Note — ΩE_5(6)

## Claim (strict)
Affine multi-twists on the X(1,1) prototype surface in ΩE_5(6) repeatedly generate closed Teichmüller geodesics whose Kontsevich–Zorich monodromy on the geometric H_1^+ basis has **exact ratio 2:1**.

This is **not** a determination of the Masur–Veech / EKZ measure-average Lyapunov exponents.

`promote_ready = false`

## Literature baseline (attribution only)
- λ_1^+ + λ_2^+ = 6/7 — EKZ
- H^- = ±1/7 — Möller / EKZ
- Individuals unknown — Eskin–Matheus arXiv:1210.2157 §3.2 (rough numerics ≈0.58 / 0.26)

## Geometric evidence
- Prototype: X(1,1) (D=5) with Prym involution and cylinder cores.
- Generators: Prym-invariant multi-twists (horizontal + vertical).
- Exact 2:1 matrices on geometric H_1^+: 46
- Independent closed geodesics with exact ratio 2:1: **20**
- Example derivative: A = [[31,10],[65,21]] ∈ SL(2,ℝ)
- Example monodromy M_+ yields raw spectrum [1, 1/2, -1/2, -1] which scales to 4/7 + 2/7 under the known sum.

## Contrast
Random walk on the same multi-twist generators → nearly isotropic (~0.43 / 0.43).
Continuous Rauzy + heights integrators under elementary / multi-twist monodromy → parabolic / null (archived).

## Conjecture
The measure-average spectrum on H_1^+ is 4/7 and 2/7.

## Artefacts
See data/ directory and paper/computational_note_d6.md.
