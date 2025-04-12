### Idea
![[double_integral.png]]
Here is 1 way of partition, into squares with Area $\Delta A$, we choose the height evaluated at the mid-point of the grid(one way of partition). 
![[double_integral2.png]]
We use  $(x_{i,}y_i)$ to represent a specific point on each grid, which we use to evaluate the height.
![[double_integral_3.png]]
The [[Riemann integral]] have us partition the curve into rectangles length and width  $\Delta x$ and $\Delta y$, 
This is directly equivalent to double integral.
![[The Mathmagic Show - Visualize Double Sums Like a PRO! (The Drawing Trick Nobody Tells You) [P7JZynw-Ffs - 1108x623 - 1m56s].png]]
Double summation is similar to double for loop,  evaluate the inner sum with the first term of the outer sum, this is equivalent to going down each column here. 
or going across x and up y if we are looking from the top.
```python
for y in range(1, 2):
	for x in range(1, 3)
	print([x][y])
	# we have (1,1) (2, 1) (3, 1) (1, 2) so on 
```

#math #calculus #integration 



