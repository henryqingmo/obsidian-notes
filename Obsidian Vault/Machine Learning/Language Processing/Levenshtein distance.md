### Idea
![[COMP3411 Week 8 - Language processing.pdf#page=52]]
![[COMP3411 Week 8 - Language processing.pdf#page=54]]
#### Formally
![[COMP3411 Week 8 - Language processing.pdf#page=55]]
We want to look at the minimum cost from three of the predecessor, D(i -1, j) + deletion, 
D(i, j-1) + insertion and D(i-1, j-1) + substitution.
When the column and row letters match, copy the diagonal, as we can safely ignore the new letter, by doing 0 operations on the previous substring of D(i-1, j-1) copying the diagonal. 
for eg. (hello $\rightarrow$ bghio) $\Leftrightarrow$ (hell $\rightarrow$ bghi), this will always be the minimum. 

```handwritten-ink
{
	"versionAtEmbed": "0.2.6",
	"filepath": "Assets/Pictures/Ink/Writing/2024.12.2 - 15.51pm.writing"
}
``` 
The first case for D(-1, -1), replacement is 0, hence by induction, the all holds.
![[COMP3411 Week 8 - Language processing.pdf#page=56]]
### Example
![[Exam 24T2 FCruz.pdf#page=15]]
#coding #algorithm #machine_learning #language_processing



