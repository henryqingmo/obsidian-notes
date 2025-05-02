### Idea
![[Topic 5 Lecture Notes (Gardiner).pdf#page=51]]


![[Topic 5 Lecture Notes (Gardiner).pdf#page=57]]
### Formally
A multigraph is planar if it doesn't contain a subgraph which is subdivision 
of $K_5$ or $K_{3,3}$ [[Kuratowski's theorem]]

By [[Handshaking lemma]] we have
$$
\sum\limits deg(f_{i)}= 2e
$$
Because the graph is simple, there is no loop or parallel edges.  
For each face, we need at least 3 edges. 
$$
\sum\limits deg(f_{i)} \geq 3f
$$
Hence we have
$$
3f \geq 2e
$$
by [[Discrete Math/Graph Theory/Euler's formula]] we have
$$
\begin{align}
v - e + f = 2 \\
f = 2 + e - v
\end{align}
$$
$$
\begin{align}
3(2 + e - v) &\geq 2e  \\
e &\geq 3v - 6

\end{align}
$$

Similarly for the second theorem, the cycle of each face must be at least length 4. 

#math #discrete #graph_theory  


