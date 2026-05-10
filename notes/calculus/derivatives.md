# Derivatives

**Domain:** Calculus  
**Tags:** `derivative`, `linear-operator`, `differentiation`

## Definition

Let $f : \mathbb{R} \to \mathbb{R}$ be defined near $a$.
The **derivative** of $f$ at $a$ is

$$
f'(a) = \lim_{h \to 0} \frac{f(a+h) - f(a)}{h},
$$

provided this limit exists (see [definition-of-limit](../concepts/definition-of-limit.md)).

## Key Properties

| Property | Statement |
|----------|-----------|
| Linearity | $(cf + g)' = cf' + g'$ |
| Product rule | $(fg)' = f'g + fg'$ |
| Chain rule | $(f \circ g)' = (f' \circ g) \cdot g'$ |

## Derivative as a Linear Operator

The derivative $D : C^1(\mathbb{R}) \to C^0(\mathbb{R})$, $D(f) = f'$, is a
**linear transformation** in the sense of
[linear-algebra/linear-transformations](../../linear-algebra/README.md):

$$
D(\alpha f + \beta g) = \alpha D(f) + \beta D(g).
$$

## References

- [@stewart2015] Ch. 2–3 — formal treatment with $\varepsilon$-$\delta$ proofs.
