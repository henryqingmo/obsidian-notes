### Idea
```c
void bubbleSort (Item items[], int lo, int hi)
{
	for (int i = hi; i > lo; i--)
	{
		bool swapped = false;
		for (int j = lo; j < i; j++)
		{
			if (gt(items[j], items[j + 1]))
			{
				swap(items, j, j + 1);
				swapped = true;
			}
		}
		if (!swapped) break;
	}
}
```
### Analysis
#### Best case
![[week02tue-elementary-sorts.pdf#page=37]]
#### Worst case
![[week02tue-elementary-sorts.pdf#page=38]]
#### Average case
![[week02tue-elementary-sorts.pdf#page=39]]
### Property
![[week02tue-elementary-sorts.pdf#page=40]]

#coding #algorithm #sorting_algorithm 




