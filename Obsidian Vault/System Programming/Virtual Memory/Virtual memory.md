### Idea
The stack grows downwards and the heap grows upwards. The heap is allocated from the space between stack and data.  

CPU stores the program counter which is a pointer to the memory of the execution code stored in text section. It fetches the code and executes them. 
![[Screen Shot 2024-08-07 at 11.51.08 am.png]]
Memory for each process splits up into pages which map to a frame in the Ram. 
![[Screen Shot 2024-08-07 at 3.35.20 pm.png]]
Translation look aside buffer stores the seen page and frame as key value pair like a hash table, to provide looks up.  
TLB miss if page not in TLB, then cpu look up the page table in main memory (SLOW). 
Page fault if the page is not in main memory, then swap may be performed.
![[Screen Shot 2024-08-07 at 3.37.55 pm.png]]
In a swap, the frame gets copied to be temporarily stored in the disk (SLOW). And copied back to the RAM it needs to be accessed.
![[Screen Shot 2024-08-07 at 3.44.42 pm.png]]
### Example
2D array access on array row by row is faster than col by col because of less TLB misses. 
![[Screen Shot 2024-08-07 at 3.47.25 pm.png]]

![[Screen Shot 2024-08-07 at 3.47.42 pm.png]]

#coding #assembly #memory



