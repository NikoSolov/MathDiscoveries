# Теорема о двух касательных параболы

В любой параболе абсцисса точки пересечения касательных, заданных в несовпадающих точках, равна полу сумме абсцисс от этих точек.

# Доказательство

$$
\begin{array}{l}
f(x)=ax^2+bx+c \to f'(x)=2ax+b\\
x_1, x_2 \text{ - точки касательных, } x_1\neq x_2 \\
\end{array}
$$

$$
\begin{array}{l}
t_{x_0}(x)=f'(x_0)(x-x_0)+f(x_0)=\\
=(2ax_0+b)(x-x_0)+ax_0^2+bx_0+c=\\
=2axx_0+bx-2ax_0^2\cancel{-bx_0}+ax_0^2\cancel{+bx_0}+c\\
=2axx_0+bx-ax_0^2+c
\end{array}
$$

$$
\begin{array}{l}
t_{x_1}(x)=2axx_1+bx-ax_1^2+c\\
t_{x_2}(x)=2axx_2+bx-ax_2^2+c
\end{array}
$$

$$
\begin{array}{l}
t_{x_1}(x_i)=t_{x_2}(x_i), x_i \text{ - абсцисса точки пересечения}\\
2ax_ix_1\cancel{+bx_i}-ax_1^2\cancel{+c}=
2ax_ix_2\cancel{+bx_i}-ax_2^2\cancel{+c}\\
2ax_ix_1-2ax_ix_2=ax_1^2-ax_2^2\\
x_i\cdot2\cancel{a}(x_1-x_2)=\cancel{a}(x_1^2-x_2^2)\\
x_i=\frac{(x_1+x_2)\cancel{(x_1-x_2)}}{2\cancel{(x_1-x_2)}}\\
\boxed{x_i=\frac{(x_1+x_2)}{2}}
\end{array}
$$

---

$$
\begin{array}{l}
\text{Треугольник: }\\
A=(x_1,F(x_1))=(x_1, ax_1^2+bx_1+c);\\
B=(x_2, F(x_2))=(x_2, ax_2^2+bx_2+c); \\
C=\left(\dfrac{x_1+x_2}{2},t(\dfrac{x_1+x_2}{2})\right)=
\left(\dfrac{x_1+x_2}{2},
a\cdot\dfrac{x_1^2+2x_1x_2+x_2^2}{4}+b\cdot\dfrac{x_1+x_2}{2}+c
\right)
\end{array}
$$
