### Idea
![[week01tue-recursion.pdf#page=20]]
![[week01tue-recursion.pdf#page=23]]
First consider base case (no recursion involved)
Then consider recursive case. 

### Example 
Check if a linked list is sorted
```c
bool listIsSorted(struct node *l) {
	//base case an empty list is sorted
	if (l == NULL) {
		return true;
	
	//base case a list with one item is sorted
	} else if (l->next == NULL) {
		return true;
	
	// base case if first item is greater than second item, list is not sorted
	} else if (l->value > l->next->value) {
		return false;
	
	//recursive case check whether rest of the list is sorted
	} else {
		return listIsSorted(l->next);
	}
}

```


#coding #algorithm 



