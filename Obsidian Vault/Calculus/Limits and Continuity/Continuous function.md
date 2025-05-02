### Idea
![[Assets/Pictures/5. Continuous Functions - Handout 1.png]]
[[5. Continuous Functions - Handout.pdf#page=6&rect=21,59,773,576|5. Continuous Functions - Handout, p.6]]
[[Continuity]]
We start off proving the converse, firstly assuming that every open set $U$ has it's [[Image and pre-Image]] as an open set.  Notice that's it's a **pre-image**, so any $U$ lies outside the range would have pre-image of empty set.  which is already open and trivial for this proof(as we only look at the input space).

Now for any point $a$ in $\Omega$, we can find any open set that's gonna be a pre-image $f^{-1}(U)$ in which $U$ contains $f(a)$.
 
Since $a$ is an interior point of $f^{-1}(U)$, there would be ball centred at $a$ contained in the subset, which act as a neighbourhood. [[Point Set Topology]],
So $N \subseteq f^{-1}(U) \Rightarrow f(N) \subseteq U$ would mean that [[Continuity]] is satisfied.

![[Assets/Pictures/5. Continuous Functions - Handout 2.png]]
[[5. Continuous Functions - Handout.pdf#page=7&rect=17,1,784,587|5. Continuous Functions - Handout, p.7]]

The direct proof, we starts off with f is continuous. 
We first find an open set $U$ in the co-domain, and let $a \in f^{-1}(U)$.  Now we use the [[Continuity]], so there exist $B(a, \delta) \subseteq \Omega$ and $f(B(a, \delta)) \subseteq U$. Which means $B(a, \delta) \subseteq f^{-1}(U)$

So for every point in $f^{-1}(U)$, there is a ball contained entirely in $f^{-1}(U)$. Hence $f^{-1}(U)$ is open.

![[Assets/Pictures/5. Continuous Functions - Handout 3.png]]
[[5. Continuous Functions - Handout.pdf#page=8&rect=18,48,791,580|5. Continuous Functions - Handout, p.8]]

This is the theorem above but for closed. 

#### Path-connected
![[Assets/Pictures/5. Continuous Functions - Annotated.png]]
[[5. Continuous Functions - Annotated.pdf#page=25&rect=17,175,774,581|5. Continuous Functions - Annotated, p.25]]

![[Assets/Pictures/5. Continuous Functions - Annotated 1.png]]
[[5. Continuous Functions - Annotated.pdf#page=28&rect=54,60,747,440|5. Continuous Functions - Annotated, p.28]]

![[Assets/Pictures/5. Continuous Functions - Annotated 2.png]]
[[5. Continuous Functions - Annotated.pdf#page=29&rect=30,14,786,583|5. Continuous Functions - Annotated, p.29]]

![[Assets/Pictures/5. Continuous Functions - Annotated 5.png]]
[[5. Continuous Functions - Annotated.pdf#page=55&rect=24,25,781,596|5. Continuous Functions - Annotated, p.55]]
[[Bolzano-Weierstrass Theorem]]
[[Point Set Topology]]

#### Summary
![[Pasted image 20250502173650.png]]


#math #calculus #limit 



