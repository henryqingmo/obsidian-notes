### Idea
An AVL tree have all nodes height balanced. 

Steps in inserting to an AVL Tree. 
1. Inserting node
2. go up from the inserted node, update each node to update the height and check for imbalance. 
3. For the first node that have an imbalance, rotate depending on the following situations. 
4. LL: imbalance on the left branch, and the left left branch is heavier than left right branch
   in this situation, Perform a right rotation on the node. 
5. RR: imbalance on the right branch, and the right right branch is heavier than right left branch
   in this situation, Perform a left rotation on the node. 
   

LR: imbalance on the left branch, and the left right branch is heavier than left left branch
   in this situation, Perform a right  rotation on the left node, this will make  the node having a LL situation, hence we 
   
	follow by a left rotation on the node. 



### Formally

#coding #algorithm #binary_tree  



