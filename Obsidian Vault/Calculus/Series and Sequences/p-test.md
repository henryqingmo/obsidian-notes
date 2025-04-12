$$
\int_{1}^{\infty} \frac{1}{x^p}\; dx
$$
Convergent if  $p > 1$ and divergent if $p \leq 1$

Proof 

Case 1. if  $p \neq 1$
$$
\begin{aligned}
\int_1^Rx^{-p}dx& =\left[\frac{x^{1-p}}{1-p}\right]_1^R  \\
&\begin{aligned}&=\frac{R^{1-p}-1}{1-p}\end{aligned}
\end{aligned}
$$
$$
\to\begin{cases}\frac{1}{p-1}&\text{when }1-p<0\\\infty&\text{when }1-p>0\end{cases}
$$
When p = 1
$$
ln(\infty) = \infty
$$

### Comparison test
Suppose that $f$ and $g$ are integrable functions and that $0≤f(x)≤g(x)$ whenever $x>a$
$$
(i)If\int_a^\infty g(x)dx\textit{ converges then }\int_a^\infty f(x)dx\textit{ converges.}\\(ii)If\int_a^\infty f(x)dx\textit{ diverges then }\int_a^\infty g(x)dx\textit{ diverges.}
$$

Suppose that $f$ and $g$ are non-negative and bounded on $[a,∞)$.
$$
\lim_{x\to\infty}\frac{f(x)}{g(x)}=L
$$
$$
\begin{aligned}&and~0<L<\infty~then~either\\&\int_a^\infty f\left(x\right)dx&&and&&\int_a^\infty g(x)dx&&both&&converge\\or\\&\int_a^\infty f\left(x\right)dx&&and&&\int_a^\infty g(x)dx&&both&&diverge.\end{aligned}
$$
