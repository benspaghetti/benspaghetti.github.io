# Translation with Matrices

So I was bored in maths lesson and couldn't bother calculating inverse matrices. I thought, since we can do rotation, scaling, etc. with matrices, why is it that we can't do one of the most basic rigid motions of translation?

Turns out we can. We represent

\\[
\begin{bmatrix}
x \\
y \\
z
\end{bmatrix}
\\]

as 

\\[
\begin{bmatrix}
x \\
y \\
z \\
1
\end{bmatrix}
\\]
or we can replace $1$ by any non-zero number, but \\(1\\) is more convenient.

\\[
\begin{bmatrix}
1 & 0 & 0 & a\\
0 & 1 & 0 & b\\
0 & 0 & 1 & c\\
0 & 0 & 0 & 1
\end{bmatrix}
\begin{bmatrix}
x \\
y \\
z \\
1
\end{bmatrix}
=
\begin{bmatrix}
x + a\\
y + b\\
z + c\\
1
\end{bmatrix}
\\]

Might investigate the geometric interpretation of this 4th coordinate later.