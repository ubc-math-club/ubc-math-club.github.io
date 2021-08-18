---
sidebar_position: 3
---

# Metric Space Examples

See also: [Examples of metric spaces (Wikipedia)](https://en.wikipedia.org/wiki/Metric_space#Examples_of_metric_spaces)

1. $d(x,y) > 0 ~ \forall x, y, ~ \textit{s.t.}~ x \neq y$ (positivity)
2. $d(x,y) = 0 \iff x = y$ (equality)
3. $d(x,y) \leq d(x,z) + d(z, y)$ (triangle inequality)

## Normed Metric Spaces

Normed metric spaces are induced by some norm, i.e. $d(x,y) = \|x - y\|$, where
$\|.\|$ can be for example, Euclidian ($L_2$), Taxicab ($L_1$), Max ($L_\infty$), or some other norm.

These require norm as a dependency.
As such, need all the algebraic properties for addition/multiplication.

More specifically, normed metric is a metric that is also translation-invariant:
$d(x+z, y+z) = d(x,y)$.

### Discrete metric

$$
d(x,y) = 
\begin{cases} 
1 &\text{if}\ x\neq y , \\
0 &\text{if}\ x = y
\end{cases}
$$

## Metric Spaces not Induced by Norm

For example, consider a graph $G = (E,V)$. Define distance between two
vertices $x,y \in G$ to be the length of the minimal path between these
vertices. Aka Geodesic distance.
This metric is not translation invariant in general (check it!).
