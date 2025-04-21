### Idea
![[Pasted image 20250417131541.png]]
Initially label the distance to each vertices as infinity. 
#### Updating estimate
![[Pasted image 20250417131711.png]]
We then update our estimates, recording the previous vertex. 
#### Choosing the next vertex
![[Pasted image 20250417131854.png]]
Choose the vertex we **have not** explored with the shortest distance. 
We can use a [[Priority Queue]] here.

We then repeat this process.

If all the vertices have equal weights, this is a special case of [[BFS path finding]].
### Formally

#coding #algorithm 



