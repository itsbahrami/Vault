## 1. Inline vs display

Inline — source: `The energy is $E = mc^2$ and that's that.`

Inline — preview: The energy is $E = mc^2$ and that's that.

Display — source:

```latex
$$
\int_0^\infty e^{-x^2}\,dx = \frac{\sqrt{\pi}}{2}
$$
```

Display — preview:

$$
\int_0^\infty e^{-x^2}\,dx = \frac{\sqrt{\pi}}{2}
$$

## 2. Building blocks

- `\frac{a}{b}` → $\frac{a}{b}$
- `\dfrac{a}{b}` → $\dfrac{a}{b}$
- `\displaystyle\frac{a}{b}` → $\displaystyle\frac{a}{b}$ (full-size inline)
- `\frac{1}{1+\frac{1}{x}}` → $\frac{1}{1+\frac{1}{x}}$ (nested)
- `\sqrt{x}` → $\sqrt{x}$
- `\sqrt[3]{x}` → $\sqrt[3]{x}$
- `\binom{n}{k}` → $\binom{n}{k}$
- `x^2` → $x^2$
- `x_{n+1}` → $x_{n+1}$
- `x_i^2` → $x_i^2$
- `a_{i,j}^{2n}` → $a_{i,j}^{2n}$
- `f'(x)` → $f'(x)$
- `f''(x)` → $f''(x)$
- `f^{\prime}(x)` → $f^{\prime}(x)$

## 3. Greek letters

**Lowercase**
- `\alpha` $\alpha$
- `\beta` $\beta$
- `\gamma` $\gamma$
- `\delta` $\delta$
- `\epsilon` $\epsilon$
- `\varepsilon` $\varepsilon$
- `\zeta` $\zeta$
- `\eta` $\eta$
- `\theta` $\theta$
- `\vartheta` $\vartheta$
- `\iota` $\iota$
- `\kappa` $\kappa$
- `\lambda` $\lambda$
- `\mu` $\mu$
- `\nu` $\nu$
- `\xi` $\xi$
- `\pi` $\pi$
- `\rho` $\rho$
- `\sigma` $\sigma$
- `\tau` $\tau$
- `\upsilon` $\upsilon$
- `\phi` $\phi$
- `\varphi` $\varphi$
- `\chi` $\chi$
- `\psi` $\psi$
- `\omega` $\omega$

**Uppercase**
- `\Gamma` $\Gamma$
- `\Delta` $\Delta$
- `\Theta` $\Theta$
- `\Lambda` $\Lambda$
- `\Xi` $\Xi$
- `\Pi` $\Pi$
- `\Sigma` $\Sigma$
- `\Upsilon` $\Upsilon$
- `\Phi` $\Phi$
- `\Psi` $\Psi$
- `\Omega` $\Omega$

## 4. Relations & arithmetic

- `\le` $\le$
- `\ge` $\ge$
- `\neq` $\neq$
- `\approx` $\approx$
- `\equiv` $\equiv$
- `\sim` $\sim$
- `\simeq` $\simeq$
- `\propto` $\propto$
- `\ll` $\ll$
- `\gg` $\gg$
- `\prec` $\prec$
- `\preceq` $\preceq$
- `\perp` $\perp$
- `\parallel` $\parallel$
- `\times` $\times$
- `\cdot` $\cdot$
- `\div` $\div$
- `\pm` $\pm$
- `\mp` $\mp$
- `\circ` $\circ$
- `\ast` $\ast$
- `\star` $\star$
- `\otimes` $\otimes$
- `\oplus` $\oplus$
- `\odot` $\odot$
- `\wedge` $\wedge$
- `\vee` $\vee$

## 5. Sets

- `\in` $\in$
- `\notin` $\notin$
- `\ni` $\ni$
- `\subset` $\subset$
- `\subseteq` $\subseteq$
- `\subsetneq` $\subsetneq$
- `\supset` $\supset$
- `\supseteq` $\supseteq$
- `\cup` $\cup$
- `\cap` $\cap$
- `\bigcup_{i=1}^{n}` $\bigcup_{i=1}^{n}$
- `\bigcap_{i}` $\bigcap_{i}$
- `\emptyset` $\emptyset$
- `\varnothing` $\varnothing$
- `\setminus` $\setminus$
- `\complement` $\complement$
- `\mathbb{N}` $\mathbb{N}$
- `\mathbb{Z}` $\mathbb{Z}$
- `\mathbb{Q}` $\mathbb{Q}$
- `\mathbb{R}` $\mathbb{R}$
- `\mathbb{C}` $\mathbb{C}$
- `\mathbb{F}_p` $\mathbb{F}_p$

## 6. Logic & arrows

- `\forall` $\forall$
- `\exists` $\exists$
- `\nexists` $\nexists$
- `\neg` $\neg$
- `\land` $\land$
- `\lor` $\lor$
- `\top` $\top$
- `\bot` $\bot$
- `\implies` $\implies$
- `\iff` $\iff$
- `\to` $\to$
- `\gets` $\gets$
- `\mapsto` $\mapsto$
- `\Rightarrow` $\Rightarrow$
- `\Leftarrow` $\Leftarrow$
- `\Leftrightarrow` $\Leftrightarrow$
- `\leftrightarrow` $\leftrightarrow$
- `\longrightarrow` $\longrightarrow$
- `\xrightarrow{f}` $\xrightarrow{f}$
- `\xrightarrow[n\to\infty]{}$ $\xrightarrow[n\to\infty]{}$

## 7. Big operators & functions

- `\sum_{i=1}^{n}` $\sum_{i=1}^{n}$
- `\prod_{k=1}^{n}` $\prod_{k=1}^{n}$
- `\coprod` $\coprod$
- `\int_a^b` $\int_a^b$
- `\iint_D` $\iint_D$
- `\iiint` $\iiint$
- `\oint_\gamma` $\oint_\gamma$
- `\lim_{x\to 0}` $\lim_{x\to 0}$
- `\limsup_n` $\limsup_n$
- `\liminf_n` $\liminf_n$
- `\max_{x\in A}` $\max_{x\in A}$
- Ready-made: `\sup \inf \min \arg \det \dim \ker \deg \gcd \ln \log \exp \sin \cos \tan \arcsin \sinh`
- Custom operator: `\operatorname{rank}(A)` $\operatorname{rank}(A)$ — use this, not `\text{rank}`, so spacing is right.

## 8. Miscellaneous

- `\infty` $\infty$
- `\partial` $\partial$
- `\nabla` $\nabla$
- `\hbar` $\hbar$
- `\ell` $\ell$
- `\aleph` $\aleph$
- `\Re` $\Re$
- `\Im` $\Im$
- `\angle` $\angle$
- `\square` $\square$
- `\triangle` $\triangle$
- `\therefore` $\therefore$
- `\because` $\because$
- `\cdots` $\cdots$
- `\ldots` $\ldots$
- `\dots` $\dots$
- `\vdots` $\vdots$
- `\ddots` $\ddots$
- `90^\circ` $90^\circ$
- `\prime` $\prime$
- `\dagger` $\dagger$

## 9. Accents & decorations

- `\vec{v}` $\vec{v}$
- `\overrightarrow{AB}` $\overrightarrow{AB}$
- `\hat{x}` $\hat{x}$
- `\bar{z}` $\bar{z}$
- `\overline{z}` $\overline{z}$
- `\tilde{f}` $\tilde{f}$
- `\dot{x}` $\dot{x}$
- `\ddot{x}` $\ddot{x}$
- `\check{a}` $\check{a}$
- `\breve{a}` $\breve{a}$
- `\acute{a}` $\acute{a}$
- `\grave{a}` $\grave{a}$
- `\underbrace{a+b}_{n}` $\underbrace{a+b}_{n}$
- `\overbrace{1+\cdots+1}^{n}` $\overbrace{1+\cdots+1}^{n}$
- `\overset{\text{def}}{=}` $\overset{\text{def}}{=}$
- `\underset{n\to\infty}{\to}` $\underset{n\to\infty}{\to}$
- ⚠️ `\cancel{x}` may **not** render — Obsidian doesn't load every MathJax extension. If it shows literally, drop it (LaTeX Suite's `C` snippet will also produce dead text).

## 10. Fonts

- `\mathrm{d}x` $\mathrm{d}x$
- `\mathbf{v}` $\mathbf{v}$
- `\mathit{abc}` $\mathit{abc}$
- `\mathsf{T}` $\mathsf{T}$
- `\mathtt{x}` $\mathtt{x}$
- `\mathcal{L}` $\mathcal{L}$
- `\mathfrak{g}` $\mathfrak{g}$
- `\mathbb{R}` $\mathbb{R}$
- `\boldsymbol{\alpha}` $\boldsymbol{\alpha}$
- Words inside math: `\text{for all } x` → $\text{for all } x$. Without `\text`, spaces vanish and letters go italic.

## 11. Spacing & sizing

- `\,` → $a\,b$ (thin)
- `\;` → $a\;b$ (medium)
- `\quad` $\quad$
- `\qquad` $\qquad$
- `\int f(x)\,dx` → $\int f(x)\,dx$ — the `\,` stops the $dx$ from crowding the integrand
- Auto-sizing brackets: `\left(\frac{a}{b}\right)` → $\left(\frac{a}{b}\right)$ vs `(\frac{a}{b})` → $(\frac{a}{b})$
- `\left[ x \right]` → $\left[ x \right]$
- `\left\{ x \right\}` → $\left\{ x \right\}$
- `\left| x \right|` → $\left| x \right|$
- `\left\langle x \right\rangle` → $\left\langle x \right\rangle$
- Evaluation bar: `\left. F(x) \right|_a^b` → $\left. F(x) \right|_a^b$
- `\vert` $\vert$
- `\lvert x \rvert` $\lvert x \rvert$
- `\mid` $\mid$ (for "such that" / divisibility)

## 12. Multi-line derivations

Source:

```latex
$$
\begin{aligned}
(a+b)^2 &= (a+b)(a+b) \\
        &= a^2 + ab + ba + b^2 \\
        &= a^2 + 2ab + b^2
\end{aligned}
$$
```

Preview:

$$
\begin{aligned}
(a+b)^2 &= (a+b)(a+b) \\
        &= a^2 + ab + ba + b^2 \\
        &= a^2 + 2ab + b^2
\end{aligned}
$$

`&` marks the alignment point, `\\` ends the line. Use **`aligned`** inside `$$` rather than `align` — it's the safer form in Obsidian. No automatic equation numbers, no `\label`/`\ref` cross-references.

## 13. Cases / piecewise

```latex
$$
f(x) =
\begin{cases}
x^2, & x \ge 0 \\
-x,  & x < 0
\end{cases}
$$
```

$$
f(x) =
\begin{cases}
x^2, & x \ge 0 \\
-x,  & x < 0
\end{cases}
$$

## 14. Matrices

Same syntax, different brackets:

- `pmatrix` → $\begin{pmatrix} a & b \\ c & d \end{pmatrix}$
- `bmatrix` → $\begin{bmatrix} a & b \\ c & d \end{bmatrix}$
- `vmatrix` (determinant) → $\begin{vmatrix} a & b \\ c & d \end{vmatrix}$
- `Bmatrix` → $\begin{Bmatrix} a & b \\ c & d \end{Bmatrix}$
- `matrix` (bare) → $\begin{matrix} a & b \\ c & d \end{matrix}$

```latex
$$
A = \begin{pmatrix} a & b \\ c & d \end{pmatrix},
\qquad
\det A = \begin{vmatrix} a & b \\ c & d \end{vmatrix} = ad - bc
$$
```

$$
A = \begin{pmatrix} a & b \\ c & d \end{pmatrix},
\qquad
\det A = \begin{vmatrix} a & b \\ c & d \end{vmatrix} = ad - bc
$$

Dots in general matrices:

```latex
$$
\begin{pmatrix}
a_{11} & \cdots & a_{1n} \\
\vdots & \ddots & \vdots \\
a_{m1} & \cdots & a_{mn}
\end{pmatrix}
$$
```

$$
\begin{pmatrix}
a_{11} & \cdots & a_{1n} \\
\vdots & \ddots & \vdots \\
a_{m1} & \cdots & a_{mn}
\end{pmatrix}
$$

## 15. Callouts for theorems — and the one caveat

Callouts are plain markdown, so the math inside them uses the same `$...$`. **Caveat:** in Live Preview, display math inside a callout frequently fails to render while editing. It's fine in Reading View; the plugin **Better Math in Callouts & Blockquotes** fixes Live Preview.

Source:

```markdown
> [!definition] Limit
> $\lim_{x \to a} f(x) = L$ means: for every $\varepsilon > 0$ there is $\delta > 0$ such that $0 < \lvert x-a \rvert < \delta \implies \lvert f(x)-L \rvert < \varepsilon$.

> [!theorem] Mean Value Theorem
> If $f$ is continuous on $[a,b]$ and differentiable on $(a,b)$, then there is $c \in (a,b)$ with
> $$f'(c) = \frac{f(b)-f(a)}{b-a}.$$

> [!note]- Proof idea (foldable)
> Apply Rolle's theorem to $g(x) = f(x) - \left[ f(a) + \frac{f(b)-f(a)}{b-a}(x-a) \right]$.
```

Preview (Reading View):

> [!definition] Limit
> $\lim_{x \to a} f(x) = L$ means: for every $\varepsilon > 0$ there is $\delta > 0$ such that $0 < \lvert x-a \rvert < \delta \implies \lvert f(x)-L \rvert < \varepsilon$.

> [!theorem] Mean Value Theorem
> If $f$ is continuous on $[a,b]$ and differentiable on $(a,b)$, then there is $c \in (a,b)$ with
> $$f'(c) = \frac{f(b)-f(a)}{b-a}.$$

> [!note]- Proof idea (foldable)
> Apply Rolle's theorem to $g(x) = f(x) - \left[ f(a) + \frac{f(b)-f(a)}{b-a}(x-a) \right]$.

## 16. LaTeX Suite snippets (typing speed)

Install the **LaTeX Suite** community plugin. Defaults worth memorising:

| Trigger         | Expands to                      | Notes                                   |
| :-------------- | :------------------------------ | :-------------------------------------- |
| `dm`            | `$$` then `$$`                  | display block, cursor in middle         |
| `xsr`           | `x^{2}`                         | power on `x`                            |
| `sr`            | `^{2}`                          | power on selection                      |
| `x/y` then Tab  | `\frac{x}{y}`                   | fraction                                |
| `//` then Tab   | `\frac{}{}`                     | cursor lands in numerator               |
| `par x y`       | `\frac{\partial x}{\partial y}` | partial derivative                      |
| `sq` then Tab   | `\sqrt{ }`                      | root                                    |
| `sin @t`        | `\sin \theta`                   | trig with Greek                         |
| `@a` … `@w`     | `\alpha` … `\omega`             | Greek by `@` + letter                   |
| `int` / `dint`  | `\int` / `\int_{}^{}`           | integrals                               |
| `sum` / `prod`  | `\sum_{}^{}`                    | sums, products                          |
| `mk` / `bm`     | `matrix` / `bmatrix` block      | matrix skeletons                        |
| `U` (selection) | `\underbrace{…}`                | visual snippet                          |
| `C` (selection) | `\cancel{…}`                    | visual snippet — may not render, see §9 |

Inside `matrix`, `aligned`, `cases`: **Tab** inserts `&`, **Enter** inserts `\\`.

Two settings worth flipping: turn on **Conceal** to see rendered math while typing (cursor inside reveals the source), and turn it off temporarily when a complex block looks wrong — conceal is the usual culprit, not your math.
