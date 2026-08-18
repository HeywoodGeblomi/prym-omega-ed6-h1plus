# prym-omega-ed6-h1plus

Structural note and computational scaffold for the individual Lyapunov exponents on the 4-dimensional block $H_1^+$ of Weierstrass Prym Teichmüller curves $\Omega E_D(6)$ (genus 4).

## Global spectrum (literature only)

| Quantity | Value | Source |
|----------|-------|--------|
| $\lambda_1^+ + \lambda_2^+$ | $6/7$ | Eskin–Kontsevich–Zorich |
| $H^-$ | $\pm 1/7$ | Möller / EKZ |
| $\lambda_1^+,\,\lambda_2^+$ | **$4/7,\,2/7$** | Yu–Zuo (filtration on the even component of $H(6)$) + Möller (spin parity: $W_D(6)\subset$ even) |
| Existence of $W_D(2g-2)$ | only for $g\le 4$ | Gutiérrez-Romo–Pardo et al. |

This repository does **not** claim discovery of these values. It records the terminal intersection of the cited theorems. See [paper/TERMINAL_SPECTRUM_NOTE.md](paper/TERMINAL_SPECTRUM_NOTE.md) and [docs/SPECTRUM_ATTRIBUTION.md](docs/SPECTRUM_ATTRIBUTION.md).

## Even / odd contrast (Yu–Zuo)

| Component of $\Omega\mathcal{M}_4(6)$ | Gap sequence | Exponents |
|--------------------------------------|--------------|-----------|
| **even** (hosts all $W_D(6)$) | $\{1,2,4,7\}$ | $1,\,4/7,\,2/7,\,1/7$ |
| odd | $\{1,2,3,7\}$ | $1,\,3/7,\,2/7,\,1/7$ |
| hyperelliptic | $\{1,3,5,7\}$ | $1,\,5/7,\,3/7,\,1/7$ |

## What this scaffold contributes

- Residual-0 real-multiplication projectors and plane-preserving tools
- Geometric multi-twist witnesses on the X(1,1) prototype exhibiting recurrent exact 2:1 anisotropy on closed Teichmüller geodesics (path-local / formal only)
- A short structural note assembling the literature resolution above

**Hard line:** `promote_ready = false` for any computational claim of the global individuals. Path-local numerical artefacts remain scoped as path-local.

## Layout

```
paper/terminal_spectrum_prym_g4.tex   # structural note (LaTeX)
paper/TERMINAL_SPECTRUM_NOTE.md       # same (Markdown)
paper/computational_note_d6.md        # earlier 2:1 periodic evidence (scoped)
docs/SPECTRUM_ATTRIBUTION.md          # attribution lock
docs/PERIODIC_ANISOTROPY_NOTE.md
data/                                 # matrices and surveys
NON_CLAIMS.md
```

## Citation guidance

- Cite the individual exponents $4/7$ and $2/7$ exclusively to Yu–Zuo + Möller.
- Cite residual-0 tools and geometric multi-twist witnesses as computational evidence only.
- Do **not** cite this repository as the source of the spectrum.

## License

MIT.
