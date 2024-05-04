$$
\begin{pmatrix}
x_{11} & x_{12} \\ 
x_{21} & x_{22}
\end{pmatrix}^{-1}=
\frac{1}{(x_{11}x_{22}-x_{12}x_{21})}
\begin{pmatrix}
x_{22} & -x_{12} \\ 
-x_{21} & x_{11}
\end{pmatrix}
$$

$$
\begin{pmatrix}
x_{11} & 0 \\ 
0 & x_{22}
\end{pmatrix}^{-1}=
\frac{1}{(x_{11}x_{22})}
\begin{pmatrix}
x_{22} & 0 \\ 
0 & x_{11}
\end{pmatrix}^{T}=
\begin{pmatrix}
\frac{1}{x_{11}} & 0 \\ 
0 & \frac{1}{x_{22}}
\end{pmatrix}
$$

$$
\begin{pmatrix}
x_{11} & 0 & 0 \\ 
0 & x_{22} & 0 \\ 
0 & 0 & x_{33}
\end{pmatrix}^{-1}=
\frac{1}{(x_{11}x_{22}x_{33})}
\begin{pmatrix}
x_{22}x_{33} & 0 & 0 \\ 
0 & x_{11}x_{33} & 0 \\ 
0 & 0 & x_{11}x_{22}
\end{pmatrix}=
\begin{pmatrix}
\frac{1}{x_{11}} & 0 & 0 \\ 
0 & \frac{1}{x_{22}} & 0 \\ 
0 & 0 & \frac{1}{x_{33}}
\end{pmatrix}
$$

$$
\begin{pmatrix}
x_{11} & x_{12} & x_{13} \\ 
0 & x_{22} & x_{23} \\ 
0 & 0 & x_{33}
\end{pmatrix}^{-1}=
\begin{pmatrix}
\frac{1}{x_{11}} & \frac{x_{12}}{x_{11}\cdot x_{22}} & \frac{x_{12}\cdot x_{23}}{x_{11}\cdot x_{22}\cdot x_{33}}-\frac{x_{13}}{x_{11}\cdot x_{22}\cdot x_{33}} \\ 
0 & \frac{1}{x_{22}} & \frac{x_{23}}{x_{22}\cdot x_{33}} \\ 
0 & 0 & \frac{1}{x_{33}}
\end{pmatrix}
$$
