# Definition of Limit

**Domain:** Calculus / Concepts  
**Tags:** `limit`, `epsilon-delta`, `continuity`, `foundational`

## Formal Definition ($\varepsilon$-$\delta$)

Let $f$ be a real-valued function defined on a punctured neighborhood of $a$.
We say the **limit** of $f$ as $x$ approaches $a$ is $L$, written

$$
\lim_{x \to a} f(x) = L,
$$

if for every $\varepsilon > 0$ there exists $\delta > 0$ such that

$$
0 < |x - a| < \delta \implies |f(x) - L| < \varepsilon.
$$

## Intuition

$\delta$ is how close $x$ must be to $a$; $\varepsilon$ is how close $f(x)$ must
be to $L$. The definition says: *no matter how small a tolerance $\varepsilon$ you
demand, I can find a neighborhood around $a$ where $f$ stays within that tolerance
of $L$.*

## Key Theorems

- **Uniqueness:** If $\lim_{x\to a} f(x) = L$ and $= M$, then $L = M$.
- **Limit Laws:** Limits distribute over $+$, $-$, $\times$, $\div$ (when denominator $\neq 0$).
- **Squeeze Theorem:** If $g(x) \leq f(x) \leq h(x)$ near $a$ and $\lim g = \lim h = L$, then $\lim f = L$.

## Cross-links

- [Derivatives](../calculus/derivatives.md) — the derivative is defined as a limit.
- Continuity: $f$ continuous at $a$ $\iff$ $\lim_{x \to a} f(x) = f(a)$.

## References

- [@apostol1967] Ch. 3 — rigorous $\varepsilon$-$\delta$ treatment.
- [@stewart2015] Ch. 2 — intuitive introduction with worked examples.
