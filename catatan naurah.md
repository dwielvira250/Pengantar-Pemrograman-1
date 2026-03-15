# Matrix Inversion Lemma
## Definisi Matrix Inversion Lemma
    Matrix Inversion Lemma adalah rumus yang digunakan untuk menghitung invers dari matriks yang berbentuk penjumlahan matriks tanpa harus menghitung invers besar secara langsung. 
## Rumus
$$
(A + BCD)^{-1} = A^{-1} - A^{-1}B(C^{-1}+DA^{-1}B)^{-1}DA^{-1}
$$
## Syarat Matrix Inversion Lemma 
    Agar rumus ini bisa digunakan: 
    Matriks A harus memiliki invers
    Matriks C harus memiliki invers 
    Dimensi matriks harus cocok untuk perkalian.
## Contoh Soal
$$
A =
\begin{bmatrix}
2 & 0 \\
0 & 2
\end{bmatrix}
$$

$$
B =
\begin{bmatrix}
1 \\
1
\end{bmatrix}
$$

$$
C =
\begin{bmatrix}
1
\end{bmatrix}
$$

$$
D =
\begin{bmatrix}
1 & 1
\end{bmatrix}
$$
