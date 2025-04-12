$$
\begin{pmatrix}a_{11} \; a_{12} \\ a_{21} \; a{22}\end{pmatrix}^T
= \begin{pmatrix}a_{11} \; a_{21} \\ a_{12} \; {a_22}\end{pmatrix}
$$
Where row and column swapped
This can be represented as 
$$
[A^{T}]_{ij} = [A]_{ji} 
$$
Swapping the elements along the main diagonal axis.

#### A symmetrical matrix has the property
$$
A = A^{T} 
$$
This means that swapping elements along the main diagonal doesn't change the matrix, 
hence elements have to be the symmetric along the main diagonal.

### A skew symmetrical matrix has the property 
$$
-A = A^T
$$
This means that the main diagonal has to be all zero since after swap, 
the diagonal are the same. 
The element symmetric along the main diagonal has to be negative of each other. 
### proving symmetric 
$$
\begin{align*}
(AA^{T})^{T} &= AA^{T}\\
(A + A^{T})^{T}&= A^{T} + A
\end{align*}
$$
### Proving skew symmetric
$$
(A - A^{T})^{T} = A^{T} - A
$$



