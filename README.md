# Scientific Calculator

A browser-based scientific calculator with symbolic derivatives, integrals, and Laplace transforms. No installation required — single HTML file, runs entirely in the browser.

**Live demo:** https://002-scientific-calculator.vercel.app

---

## Features

### Basic
- Arithmetic, percentages, parentheses
- Powers, roots, factorial
- Euler's number `e`, `π`

### Functions tab
- Trigonometry: sin, cos, tan, cot, sec, csc and their inverses
- Hyperbolic: sinh, cosh, tanh, coth and their inverses
- Logarithms: ln, log₁₀, log₂
- Rounding: floor, ceil, round
- Special: Γ(x), abs, sgn, gcd, lcm

### Symbols tab
- Constants: π, e, i, ∞, φ, τ
- All 24 Greek lowercase letters (α–ω)
- All 21 Greek uppercase letters (Α–Ω)
- Mathematical operators: ∂, ∇, ∫, ∬, ∮, ∑, ∏, ∈, ⊂, ∪, ≤, ≥, ≠, ≈

### Calculus tab
Powered by [nerdamer](https://nerdamer.com):
- Symbolic differentiation (any order)
- Indefinite and definite integration
- Variable selector, order selector, bound inputs

### Laplace tab
- Forward transform ℒ{f(t)} with pattern matching for ~20 common forms
- Inverse transform ℒ⁻¹{F(s)}
- Clickable reference table
- 11 key properties: linearity, shifting, convolution, initial/final value theorems

### Other
- RAD / DEG angle mode toggle
- Keyboard input support
- KaTeX math rendering throughout

---

## Usage

Open `index.html` directly in any modern browser — no build step, no dependencies to install.

```bash
git clone https://github.com/kevb2029-maker/002-Scientific-Calculator-Integrals-derivatives-laplace-transform.git
cd 002-Scientific-Calculator-Integrals-derivatives-laplace-transform
open index.html
```

### Calculus examples

| Input | Operation | Result |
|-------|-----------|--------|
| `x^3 + sin(x)` | d/dx | `3x² + cos(x)` |
| `x^2` | ∫ dx | `x³/3 + C` |
| `x^2`, bounds 0→1 | Definite ∫ | `1/3` |

### Laplace examples

| f(t) | ℒ{f(t)} |
|------|---------|
| `t^2` | `2/s³` |
| `sin(2*t)` | `2/(s²+4)` |
| `e^(3*t)` | `1/(s−3)` |
| `e^(a*t)*cos(b*t)` | `(s−a)/((s−a)²+b²)` |

---

## Tech stack

| Library | Purpose |
|---------|---------|
| [KaTeX 0.16.9](https://katex.org) | Math rendering |
| [nerdamer 1.1.13](https://nerdamer.com) | Symbolic algebra, calculus |

No frameworks, no bundler, no build step.

---

## License

MIT — see [LICENSE](LICENSE).
