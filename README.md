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

let A = (V,E)(V = {a, b} with E = {a,b})

let B = (V,E)(V = {d, e} with E = {d,e})

if we compare the relationships of A and B, we can see that they are isomorphic bceause {a,b} $\to$ {d,e}

I will now add a new node to each graph and connect it to every single other node to make it complete

A = (V,E)(V = {a, b, c} with E = {{a,b},{a,c},{b,c}})

B = (V,E)(V = {d, e, f} with E = {{d,e},{d,f},{e,f}})

now we compare again:

{{a,b},{a,c},{b,c}} $\to$ {{d,e},{d,f},{e,f}}

as we can see, adding a node and making it fully connected added the same amount and comparable relations to both A and B

$\therefore$ if we keep adding nodes and connecting them to all other nodes, the graph will continue to be isomorphic no matter how many nodes they are because A and B will always have comparable relations to eachother.






















