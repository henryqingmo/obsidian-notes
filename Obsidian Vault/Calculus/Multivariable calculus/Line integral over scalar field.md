### Idea
#### Line integral over scalar field
![[Screenshot 2024-12-24 at 9.55.02 am.png]]
Line integral of scalar field(all functions) are essentially the area of the curtain drawn from the curve to the function, where $dS$ denotes the change in arc length.

Alternatively thinking of summing up a density function along the length of the curve to get the total mass.

Line integral over scalar field cannot be thought of as an anti-derivative,  like [[Line integral over vector field]]
![[Pasted image 20250407210703.png]]
Note that changing the geometric curve does change the result as it changes the arc length, whereas changing the parameterisation of the same geometric curve does not.

Hence reversing the direction is merely changing the parameterisation of the same curve, so the integral remains unchanged.

#### Derivation 
![[Khan Academy - Introduction to the line integral Multivariable Calculus Khan Academy [_60sKaoRmhU - 1440x810 - 18m13s].png]]
We can then find $dS$ using Pythagoras theorem $\sqrt{dx^2 + dy^2}$, where $dx = x^{\prime}(t)dt$ and $y = y^{\prime}(t)dt$ using [[Total differential approximation]] notice it's exactly the norm of the vector $\vec{\gamma}^{\prime}(t)$ where $\vec{\gamma}(t) = x(t)\vec{i} + y(t)\vec{j}$
This has been derived in [[Arc length]]
![[Screenshot 2024-12-24 at 10.08.21 am.png]]

#math #calculus #multivariable_calculus



