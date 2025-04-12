$$
a_{n} - c_{1}a_{n-1} - c_2a_{n-2} - \ldots - c_ka_{n-k} = 0
$$
This is an homogeneous k-ordered recurrence , it requires k initial values to solve.
An inhomogeneous case is when then right hand side is not a constant. 

In inhomogeneous case we have the right hand side not equal to 0
$$
a_n-c_1a_{n-1}-c_2a_{n-2}-\cdots-c_ka_{n-k}=f(n) .
$$

Solving first order recurrence:

$$
\begin{align*}
a_{n} &= ra_{n - 1},\\
a_{0}&= A.
\end{align*}
$$
We can easily solve this by induction
$$
\begin{align*}
a_{n}&= Ar^n
\end{align*}
$$
Consider the second order recurrence
$$
a_n+pa_{n-1}+qa_{n-2}=0.
$$
Since the solution to first order is $a_{n}= r^n$, we can try it and sub in 
$$
\begin{align*}
r^n+pr^{n-1}+qr^{n-2}=0.
\end{align*}
$$
so either r = 0, which gives the uninteresting solution $a_n$ = 0, or
$$
\begin{align*}
r^2+pr+q=0.
\end{align*}
$$
And we obtain two solutions for r
$$
\begin{align*}
r &= \alpha,\; \beta
\end{align*}
$$
This means that 
$$
\begin{align*}
a_{n}&= \alpha^{n} \\
a_{n} &= \beta^{n}
\end{align*}
$$
are both solutions, which subsequently means  the general solution is 
$$
a_{n}= A\alpha^{n}+ B\beta^{n}
$$
proof. 
$$
\alpha^2+p\alpha+q=0\quad\mathrm{and}\quad\beta^2+p\beta+q=0 
$$
$$
\begin{aligned}
a_{n}+pa_{n-1}+qa_{n-2}& =(A\alpha^n+B\beta^n)+p(A\alpha^{n-1}+B\beta^{n-1})+q(A\alpha^{n-2}+B\beta^{n-2}) \\
&=A(\alpha^n+p\alpha^{n-1}+q\alpha^{n-2})+B(\beta^n+p\beta^{n-1}+q\beta^{n-2}) \\
&=A\alpha^{n-2}(\alpha^2+p\alpha+q)+B\beta^{n-2}(\beta^2+p\beta+q) \\
&=0 .
\end{aligned}

$$

However if $\alpha = \beta$ then
$$
A\alpha^{n } + B\alpha^{n} = C\alpha^n
$$
This contains only 1 constant, but we need another independent solution, so we can use the two initial values. 

So the general solution for this case is 
$$
\begin{align*}
a_{n}&= A\alpha^{n}+ Bn\alpha^{n}
\end{align*}
$$










