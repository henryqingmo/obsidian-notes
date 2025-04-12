$$
a_n-c_1a_{n-1}-c_2a_{n-2}-\cdots-c_ka_{n-k}=f(n) .
$$
The general solution to $a_n$ is the sum of the general solution to the homogeneous recurrence and a particular solution to the inhomogenous recurrence. 
$$
a_{n}= h_{n}+ p_n
$$
This is similar to linear algebra: finding the solutions of the plane that passes through the origin (homogeneous) and add it to a particular point on the shifted plane gives us all the solutions on the shifted plane. 

This is because when you sub $h_{n}+ p_n$ into the equation,  the part with $h_n$  will equal 0, leaving you with $p_n.$

Steps for finding a particular solution. 
1. Guess that $p_n$ will be something like the right hand side of the recurrence.
2. When we substitute $p_{n−1}$ into the left hand side, different kinds of terms may appear
which were not in $p_n$ itself. Add extra terms to $p_n$ to allow for these new terms.
3. Compare $p_n$ with the homogeneous solution $h_n$ . (So, it would have been best to calculate
$h_n$ before starting to think about $p_n$ . If $p_n$ has any terms in common with $h_n$ , multiply
$p_n$ by $n$. Repeat if necessary.

Explanation for step 2. 
We must make the $LHS$ same form as the $RHS$, therefore when we have extra terms on the $LHS$, we must introduce a new term to cancel it out. 

Explanation for step 3. 
If any part of the particular solution is included in the homogeneous solution, then that part would be 0 when subbed in, which makes the particular solution not work, for example we added extra terms to cancel out the constant, but the constant is part of the homogeneous solution, that makes the constant 0, so the particular solution will not work. Hence we have to multiply the particular solution by $n$. And try again.


Example 1. 
$$
\begin{align*}
a_{n} - 7a_{n-1} + 12a_{n-2} &= 30; \\
r^{2}+ 7r + 12 &= 0 \\
\end{align*}
$$
We get 
$$
h_{n} = A3^{n}+ B4^n
$$
Now we need to find a particular solution, Since right hand side is a constant, try $p_{n} = c$
Notice, $c$ is not included as a solution in $h_n$, and there is no term involves $n$ when subbing in $p_{n}= c$. 
We get 
$$
\begin{align*}
c - 7c + 12c &= 30 \\
6c &= 30 \\
c &= 5.
\end{align*}
$$
Hence 
$$
a_{n}=  A3^{n}+ B4^{n} + 5 
$$
Now we sub in initial condition to find $A$ and $B$.

Another example

$$
a_{n} - 6a_{n-1} + 9a_{n-2} = n3^n
$$
To find the homogeneous solution, we have
$$
\begin{align*}
r^{2}- 6r + 9 &= 0 \\
(r - 3)^{2}&= 0 \\
r &= 3, 3 
\end{align*}
$$

Hence the solution to homogeneous is 
$$
h_{n}= A3^{n}+ Bn3^n
$$
Now we find the  particular solution
By observation, we let $p_{n}= cn3^n$, then 
$$
p_{n-1} = c(n-1)3^{n - 1} = cn3^{n-1} - 3^{n-1} = \frac{cn^{3}}{3} - \frac{3^{n}}{3}
$$
Notice we got a constant on the $LHS$, and we have to compensate by adding a constant.
$$
\begin{align*}
p_{n} = cn3^{n} + d3^n \\
\end{align*}
$$
But now $cn3^{n}$ is a part of $h_n$, so we multiply by n
$$
p_{n}= cn^{2}3^{n}+ nd3^n
$$
But now $nd3^{n}$ is a part of $h_n$, so we multiply by n again
$$
p_{n}= cn^{3}3^{n}+ n^2d3^n
$$










