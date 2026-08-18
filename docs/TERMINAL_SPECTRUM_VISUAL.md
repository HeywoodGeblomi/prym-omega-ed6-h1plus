# Terminal Spectrum — Visual Aid

```mermaid
flowchart TD
    A["Existence ceiling\nW_D(2g−2) empty for g ≥ 5\nGutiérrez-Romo–Pardo et al."] --> B["Genus 4 is terminal"]
    B --> C["Ωℳ₄(6) minimal stratum"]
    C --> D["Even component\nGaps {1,2,4,7}\nExponents 1, 4/7, 2/7, 1/7\nYu–Zuo"]
    C --> E["Odd component\nGaps {1,2,3,7}\nExponents 1, 3/7, 2/7, 1/7\nYu–Zuo"]
    C --> F["Hyperelliptic\nGaps {1,3,5,7}\nExponents 1, 5/7, 3/7, 1/7"]
    G["Möller spin parity\nW_D(6) ⊂ even"] --> D
    D --> H["Terminal spectrum on every W_D(6)\nλ₁⁺ = 4/7 , λ₂⁺ = 2/7\non H₁⁺  (sum 6/7 by EKZ)\nH⁻ = ±1/7"]
    E -.->|never hosts Prym–Weierstrass| H

    style D fill:#e6f4ea,stroke:#137333
    style H fill:#e6f4ea,stroke:#137333
    style E fill:#fef7e0,stroke:#e37400
    style G fill:#e8f0fe,stroke:#1a73e8
    style A fill:#fce8e6,stroke:#c5221f
```

## One-line summary

Genus 4 is the last non-empty case of Weierstrass Prym eigenforms.  
All of them sit in the **even** component of $H(6)$.  
Yu–Zuo’s filtration then forces $\lambda_1^+=4/7$, $\lambda_2^+=2/7$ for every discriminant $D$.

## Attribution strip

| Piece | Source |
|-------|--------|
| Emptiness $g\ge 5$ | Gutiérrez-Romo–Pardo et al. |
| Even spin of $W_D(6)$ | Möller |
| Filtration / exponents | Yu–Zuo (arXiv:1203.6053) |
| Sum $6/7$, $H^-=\pm 1/7$ | EKZ / Möller |

This scaffold claims no discovery.
