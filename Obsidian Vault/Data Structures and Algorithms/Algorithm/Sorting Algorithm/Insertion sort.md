### Idea
```c
void insertionSort(Item items[], int lo, int hi)
{
	for (int i = lo + 1; i <= hi; i++)
	{
		Item item = items[i];
		int j = i;
		for (; j > lo && lt(item, items[j - 1]; j--))
		{
			items[j] = items[j - 1];
		}
		items[j] = item;
	}
}
```
### Analysis

#### Best case
![[week02tue-elementary-sorts.pdf#page=53]]
#### Worst case
![[week02tue-elementary-sorts.pdf#page=54]]
#### Average case
![[week02tue-elementary-sorts.pdf#page=55]]
### Property
![[week02tue-elementary-sorts.pdf#page=56]]

#coding #algorithm #sorting_algorithm 



