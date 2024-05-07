[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ppBU16qM)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## My Proof



A bijection occurs when every node in $G_1$ can be mapped to a comparable unique node in $G_2$. Because both graphs have the same number of nodes, there must be a function $f$ such that each unique node in $G_1$ can be mapped to a corresponding unique node in $G_2$.

Because $G_1$ is fully connected, there must be vertices $V_1{a}$ and $V_1{b}$ in which an edge connects them. Using this logic, there must be a function $f$ such that can map the afformentioned edge to the corresponding nodes in $G_2$. This is made possible because of the bijection of the nodes from $G_1$ to $G_2$ and the function that maps $G_1$ to $G_2$.

$\therefore$ the function works to map every node and edge from $G_1$ to $G_2$ while preserving its relations. We can conclude that every fully connected graph with the same number of nodes is isomorphic because of the mapping function that we can use to preserve the relations from $G_1$ that satisfy $f: V_1 \rightarrow V_2$ such that $(u,v) \in E_1$ iff $(f(u),f(v)) \in E_2$.





















