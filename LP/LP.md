# 线性规划(Linear Programming, LP)

## 1.线性规划模型的形式

一般形式：
$$
max(或min)z = c_1x_1 + c_2x_2 + ... + c_nx_n
\\
s.t.\begin{cases}
a_{11}x_1+a_{12}x_2+...+a_{1n}x_n \le(或=,\ge) b_1 \\
a_{21}x_1+a_{22}x_2+...+a_{2n}x_n \le(或=,\ge) b_2 \\
\qquad . \\
\qquad . \\
\qquad . \\
a_{m1}x_1+a_{m2}x_2+...+a_{mn}x_n \le(或=,\ge) b_m \\
x_1, x_2, ..., x_n \ge 0
\end{cases}
\\
$$
简写：
$$
max(或min)z = \sum_{j=1}^{n}{c_jx_j}
\\
s.t.\begin{cases}
\sum_{j=1}^{n}{a_{ij}x_j} \le(或=,\ge) b_i , \quad i=1,2,...m\\
x_j \ge 0, \quad j=1,2,...n
\end{cases}
\\
$$
