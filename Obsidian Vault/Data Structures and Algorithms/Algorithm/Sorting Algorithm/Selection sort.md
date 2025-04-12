### Idea

```c
void selectionSort(Item items[], int lo, int hi)
{
	for (int i = 0; i < hi; i++)
	{
		int min = i;
		for (int j = i + 1; j < hi; j++)
		{
			if (lt(items[j], items[min]))
			{
				min = j;
			}
		}
		swap(items, i, min);
	}
}
```
### Analysis
![[week02tue-elementary-sorts.pdf#page=13]]
### Property
![[week02tue-elementary-sorts.pdf#page=15]]

#coding #algorithm #sorting_algorithm 



