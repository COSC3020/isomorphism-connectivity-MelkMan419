[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Graph $A$ has vertices $V_A = {1, 2, 3}$ and edges $E_A = {(1,2), (2,3)}$
Graph $B$ has vertices $V_B = {a, b, c}$ and edges $E_B = {(a,b), (b,c)}$
Now, we define a bijection $f: V_A \rightarrow V_B$ as follows:

$f(1) = a$
$f(2) = b$
$f(3) = c$
Under this bijection, the edges in graph $A$ and graph $B$ correspond as follows:

$(1,2) \in E_A$ maps to $(a,b) \in E_B$
$(2,3) \in E_A$ maps to $(b,c) \in E_B$
Since there exists a bijection $f$ from the vertices of graph $A$ to the vertices of graph $B$ such that the edges correspond, graphs $A$ and $B$ are isomorphic.

However, it is clear that neither graph $A$ nor graph $B$ is completely connected. They both have vertices that are not connected by edges. This counterexample prooves they fo not have to be completely connected 
