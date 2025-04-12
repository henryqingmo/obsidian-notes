for the integral of $x^2$ on the interval $[0, 1]$

$$
\mathcal{P}_n = \{0, \frac{1}{n}, \frac{2}{n} ... \frac{n}{n}\}
$$
is called the partition of $[0, 1]$

Upper Rectangle for 1 rectangle =  $(\frac{k}{n} - \frac{k-1}{n}) \times f\left(\frac{k}{n}\right) = \frac{k^2}{n^3}$
Sum of Upper rectangle = $\frac{1}{n^3}\sum\limits k^2$

Lower Rectangle for 1 triangle $\frac{1}{n} \times f(\frac{k-1}{n}) = \frac{(k-1)^2}{n^3}$

Theorem 8.2.4. If f is bounded(attains maximum and minimum) and piece-wise continuous on [a, b] then f is integrable on [a, b].

First fundamental Theorem: 

Theorem 8.5.1 (The first fundamental theorem of calculus). If f is continuous function defined
on $[a, b]$ then the function $F : [a, b] \rightarrow \mathbb{R}$, defined by
$$
F(x) = \int_{a}^{b} f(t)\;dt,
$$
is continuous on $[a, b]$, differentiable on $(a, b)$ and has derivative $F^{\prime}$ given by
$F^{\prime}(x) = f(x)$.

The second fundamental theorem of calculus states that if $f(x)$ is continuous on an open interval containing $[a,b]$, and $F(x)$ is any antiderivative of $f(x)$ on that interval, then:
$$
\int_{a}^{b}f(t)\;dt = F(b) - F(a)
$$
If $f$ is periodic with period $T$ then 
$$
\int_{a}^{a + T} f(x)\;dx  = \int_{0}^{T} f(x)\;dx = \int_{-c}^{T - c}f(x)\;dx
$$
$$
\int_{a}^{\infty}f(x)\;dx = \lim_{R \to \infty} \int_{a}^{R}f(x) \;dx
$$
The integral is convergent if the limit approach a finite number $L$ 



