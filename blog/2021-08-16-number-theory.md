---
slug: number-theory
title: Number Theory
tags: [number theory, outreach, events]
---

Based on some of the problems from Prof. Dragos Ghioca's
[problem set 1](https://personal.math.ubc.ca/~dghioca/courses/537/practice_set_1.pdf).

## Question 1
Let $a, b \in \mathbb{N}$. Show that if $\gcd(a,b) = \text{lcm}(a,b)$, then $a = b$.

### Question Explanation

$a, b$ here are natural numbers, i.e. the ones that are used to count things: $1, 2, \dotso$

Now, consider the set of all numbers that divide both $a$ and $b$.
The maximum of this set is defined to be $\gcd(a,b)$.
Formally: $\gcd(a,b) := \max \{ x : x | a\ \text{and}\ x | b \}$.

Similarly, consider the set of all numbers that are divisible by both $a$ and $b$.
The minimum of this set is defined to be $\text{lcm}(a,b)$.
Formally: $\text{lcm}(a,b) := \min \{ x : a | x\ \text{and}\ b | x \}$.

<details>
  <summary>Solution 1</summary>
  <p>
1. $a | \text{lcm}(a,b)$ and $b | \text{lcm}(a,b)$, thus $a \leq \text{lcm}(a,b)$ and $b \leq \text{lcm}(a,b)$ (by definition).
2. $\gcd(a,b) | a$ and $\gcd(a,b) | b$, thus $\gcd(a,b) \leq a$ and $\gcd(a,b) \leq b$ (by definition).
3. Combine both inequalities together:
 * $\gcd(a,b) \leq a \leq \text{lcm}(a,b)$
 * $\gcd(a,b) \leq b \leq \text{lcm}(a,b)$
4. We are given that $\gcd(a,b) = \text{lcm}(a,b)$, therefore inequalities are actually equalities:
 * $\gcd(a,b) = a = \text{lcm}(a,b)$
 * $\gcd(a,b) = b = \text{lcm}(a,b)$
5. Hence, $a = b$.
  </p>
</details> 
