# The Algebra Fundamentals

## Permutation

A permutation is a bijection from a set to itself.

Here are examples of bijections, and therefore, permutations on a set $\left\{ 1, 2, 3 \right\}$ as well.

$$
\alpha:
\begin{aligned}
  &1 \to 2\\
  &2 \to 1\\
  &3 \to 3\\
\end{aligned}
$$

$$
\beta:
\begin{aligned}
  &1 \to 2\\
  &2 \to 3\\
  &3 \to 1\\
\end{aligned}
$$

The operation between permutations is function composition.

For example, composition of mappings $\alpha$ and $\beta$ is:
$$
\alpha \circ \beta:
\begin{aligned}
  &1 \to 2 \to 1\\
  &2 \to 3 \to 3\\
  &3 \to 1 \to 2\\
\end{aligned}
$$
Notice the order, i.e., $\beta$ is applied first, $\alpha$ then, despite being written in the opposite order.

### Associativity

Let us show that the function composition is associative.
Let $f \circ g$ represent $\left[f \circ g \right] \left( x \right) = f \left( g \left( x \right) \right)$, then:
$$
\left\{ f \circ \left[ g \circ h \right] \right\} \left( x \right) =
f \left( \left[ g \circ h \right] \left( x \right) \right) =
f \left( g \left( h \left( x \right) \right) \right) =
\left[ f \circ g \right] \left( h \left( x \right) \right) =
\left\{\left[ f \circ g \right] \circ h \right\} \left( x \right)
$$

### Closed

Composition of bijections is a bijection, therefore it is a closed operation. Considering this, composition of permutations is a permutation, thus closed as well.

It's fairly easy to see why. Each permutation basically just shuffles the elements. So combining multiple shuffles produces another shuffle.

### Identity

For any set $\mathbb{A}$, the identity function on $\mathbb{A}$ is $\epsilon$ defined as $\epsilon: \mathbb{A} \to \mathbb{A}$, where $\epsilon \left( x \right) = x$.

Let $\epsilon$ be a permutation on $\mathbb{A}$, then:
$$
\begin{aligned}
    \epsilon \circ f &= f \circ \epsilon = f\\
    \left[ \epsilon \circ f \right] \left( x \right) &= \epsilon \left( f \left( x \right) \right) = f \left( x \right)\\
    \left[ f \circ \epsilon \right] \left( x \right) &= f \left( \epsilon \left( x \right) \right) = f \left( x \right)\\
\end{aligned}
$$