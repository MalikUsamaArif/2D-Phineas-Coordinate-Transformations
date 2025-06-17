# 2D-Phineas-Coordinate-Transformations


**Implementation of Matrix Transformations in ℝ²**  
Python visualization of shear and compression operations on a 2D cartoon figure

## 🔢 Transformation Pipeline
```math
\text{Original} \xrightarrow{\text{Shear }(k=-3)} \xrightarrow{\text{Compression }(c=1/2)} \text{Transformed}



Shear Transformation (x-axis)
\begin{bmatrix}
x' \\ y'
\end{bmatrix} = 
\begin{bmatrix}
1 & -3 \\
0 & 1
\end{bmatrix}
\begin{bmatrix}
x \\ y
\end{bmatrix}

Compression Transformation (x-axis)

\begin{bmatrix}
x' \\ y'
\end{bmatrix} = 
\begin{bmatrix}
0.5 & 0 \\
0 & 1
\end{bmatrix}
\begin{bmatrix}
x \\ y
\end{bmatrix}
Composite Transformation
\begin{bmatrix}
x' \\ y'
\end{bmatrix} = 
\begin{bmatrix}
0.5 & 0 \\
0 & 1
\end{bmatrix}
\begin{bmatrix}
1 & -3 \\
0 & 1
\end{bmatrix}
\begin{bmatrix}
x \\ y
\end{bmatrix}
= 
\begin{bmatrix}
0.5 & -1.5 \\
0 & 1
\end{bmatrix}
\begin{bmatrix}
x \\ y
\end{bmatrix}
