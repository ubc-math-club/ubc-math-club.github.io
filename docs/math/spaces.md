---
sidebar_position: 2
---

# Spaces

Generally, spaces are medium we embed things into.

We organize the spaces as follows, in order of more generality:

1. Vector spaces
2. Metric spaces
3. Topological spaces
4. ???

## Vector spaces

Vector spaces is where we do Euclidean geometry in.

## Metric spaces

Metric spaces generalize vector spaces by only keeping information about the metric.
In mathematical community, metric is a function $d(x,y)$ such that:

1. $d(x,y) > 0 ~ \forall x, y, ~ \textit{s.t.}~ x \neq y$ (positivity)
2. $d(x,y) = 0 \iff x = y$ (equality)
3. $d(x,y) \leq d(x,z) + d(z, y)$ (triangle inequality)

In some other places, people also mean other things by metric.
As such, some axioms might be ignored in such cases.
For example, Lorentz spacetime.


## Topological spaces

As we deal with metrics, we notice that we can study the structure of
metric spaces not directly with metric, but also with open sets induced
by this metric.

:::note

All metric spaces are topological spaces, but there are some topological
spaces that are not metric spaces.
More generally:

vector spaces $\subset$ metric spaces $\subset$ topological spaces

:::

Topological space is a set $X$ with topology $\Tau$ defined on it.

A topology $\Tau$ is a set of subsets of $X$.

We use the following axioms to define topologies:
1. Empty set and $X$ are in $\Tau$
2. Take two elements in topological space, their union is also in topological space. Union can be either *finite* or *infinte*.
3. Intersections of two elements in topological space is also in topological space. Intersection can only be *finite*.

:::note

We only can do finite intersections because infinite intersections of open sets allow getting closed sets.

:::
