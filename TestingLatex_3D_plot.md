---
title: "test"
date: "2022-10-13"
tags:
  - LATEX
header-includes:
  - \usepackage{tikz}
  - \usepackage{pgfplots}
---

**This is LATEX 3D plot test in markdown.**

# vector column part #

$$
\begin{bmatrix}
           x_{1} \\
           x_{2} \\
           \vdots \\
           x_{m}
\end{bmatrix}
$$ 


# 3D plot part #

$$
\pgfplotsset{compat = newest}
\begin{tikzpicture}
\begin{axis}[view={20}{10}]
\addplot3 coordinates 
{
    (0,0,1)
    (0,0.5,0)
    (1,0,1)
    (1,1,1)
};
\end{axis}
\end{tikzpicture}
$$
