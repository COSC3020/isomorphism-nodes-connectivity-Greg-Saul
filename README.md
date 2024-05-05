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

Because $G_1$ and $G_2$ are both completely connected and have the same number of nodes: $V_1$ and $V_2$. All that needs to be done is to map $V_1 \to V_2$ and then connect all vertices. This is done by mapping each node in $V_1$ to a unique node in $V_2$. At this point, each node and edge in $G_1$ has a relating one in $G_2$. This will create a bijection of $G_1$ to $G_2$ and we can compare all of the edges and their relations coming off of the nodes to prove that they are the isomorphic and fit the deifintion $f: V_1 \rightarrow V_2$ such that $(u,v)\in E_1$ iff $(f(u),f(v)) \in E_2$























