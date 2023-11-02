# Assignment Feedback
In the unit 1 assement, number six is correct. I make an informal argument,
below. The rest of the answers marked off were incorrect, and I can help
explain them to him.

*I clearly have too much time on my hands, and my vacation
has led to extreme boredom.*

# Question
<style type="text/css">
    ol { list-style-type: upper-alpha; }
</style>
Ian counts twelve thousand, two hundred eight steps to hike a trail in
the park. 

What is the number written in expanded form?

> [a] $12+2+8$ \
> [b] $10,000 + 200 + 8$ \
> [c] $10,000 + 2,000 + 200 + 8$ \
> [d] $10,000 + 2,000 + 200 + 80$

# Informal Argument
Expanding using *Thm. 1.3*

$$12,208 = 10^4 \cdot 1 + 10^3 \cdot 2 + 10^2 \cdot 2 + 10^1 \cdot 0 + 10^0 \cdot 8$$

$$= 10,000 \cdot 1 + 1,000 \cdot 2 + 100 \cdot 2 + 10 \cdot 0 + 1 \cdot 8$$

$$= 10,000 + 2,000 + 200 + 0 + 8$$

$$= 10,000 + 2,000 + 200 + 8$$

$$= 12,208 $$

This was his answer.

**Q.E.D.**

## Background
To support this argument, we include some background.

There are some details glossed over for brevity. However, these are noted
and trivial to prove using elementary abstract algebra.

### Defn. 1.1 Natural numbers

Let $\mathbb{N}$ denote the set of natural numbers, constructed
through the Peano axioms. 

Some texts include $0$ in the natural numbers. 
For clarity, we denote the set of natural numbers with $0$ as 
$\mathbb{N}_0 = \{0\} \cup \mathbb{N}$.


### Defn. 1.2 Integers
We choose the common elementary school defintion. Note that, more formally,
this definition would require some mapping function. We choose to use an
informal defintion for simplicity.

We also choose to accept as an axiom that the set of integers with
operations $(+, \cdot, -)$ form a unital ring, yielding the commonly accepted
properties of said operations.

#### 1.2.1 Construction
In plain english, define the set of integers $\mathbb{Z}$ as the union 
of three sets:

- The set $\mathbb{N}$ from 1.1.
- The set $\{0\}$.
- The negation of $n \in \mathbb{N}$ denoted as $\mathbb{M}$. That is
$$-n \: \forall{n \in \mathbb{N}}$$

This yields

$$\mathbb{Z} = \mathbb{N} \cup \{0\} \cup \mathbb{M}$$ 

### Thm. 1.3
Without proof, we take as an axiom the following:

For all $z \in \mathbb{Z}$, there exist $a_i \in{\mathbb{N}_0}$
for $i \in{\mathbb{N}_0}$ such that

$$z = a_{0} \cdot 10^0 + a_{1} \cdot 10^1 + ...$$

$$= \sum_{i \in{\mathbb{N}_0}}a_i \cdot 10^i$$

This is using base ten, without loss of generality.
