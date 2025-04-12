### Idea
#### Reverse a linked list using 3 pointers
```c
SinglyLinkedListNode* reverse(SinglyLinkedListNode* llist) 
{

	SinglyLinkedListNode *curr = llist;
	SinglyLinkedListNode *next = NULL;
	SinglyLinkedListNode *prev = NULL;
	
	while (curr != NULL)
	{
		next = curr->next;
		curr->next = prev;
		prev = curr;
		curr = next;
	}

	return prev;
}
```

### Formally

#coding #data_structure #linked_list



