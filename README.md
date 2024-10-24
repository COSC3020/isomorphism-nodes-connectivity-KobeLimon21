# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

If two graphs G1 and G2 are of the same size n and are completely connnected, they have to be isomorphic. The definition of isomorphic says that there exists a bijection. Since they have the equivalent amount of nodes, each node in G1 is mapped to a unique node in G2 making it one to one. Being that they are completely connected, every node in G1 is connected to every other node which applies to G2 as well. When we map each node from G1 to a unique node in G2, every node in G2 is the image of some node in G1. This makes sure that no nodes are left out. This makes it onto, being that every node can be mapped to one another in the graphs. By the definition of isomorphic, these graphs must be isomorphic. 



Sources: 

TA Ali - helped explain the n-1 aspect

"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."
