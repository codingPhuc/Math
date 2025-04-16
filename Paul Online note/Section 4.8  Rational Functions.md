---
title: Adjunction
references: 
tags:
  - In_Progress
reference: 
Current date: 2025-04-16
---
In this final section we will discuss  graphing  rational function .  It's best to start of with a simple one that we can do without all the knowledge in this work 
Let's sketch the graph of $f(x) =\frac{1}{x}$ . First , since this is a rational function we have too be careful with a division by  0 problem . In this equation we need to avoid $x=0$ since that will give division by zero

Now , let plug in some value of x to see what we see 

| x       | f(x)   |
|---------|--------|
| -4      | -0.25  |
| -2      | -0.5   |
| -1      | -1     |
| -0.1    | -10    |
| -0.01   | -100   |
| 0.01    | 100    |
| 0.1     | 10     |
| 1       | 1      |
| 2       | 0.5    |
| 4       | 0.25   |

So , as x get large (both positive and negative) the function keep the sign of x and gets smaller and smaller . Likewise , as we approach $x=0$ the function again keep the same sign of x but start getting quick large 

```tikz
\documentclass{article}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}

\begin{document}

\begin{center}
\begin{tikzpicture}
  \begin{axis}[
    axis lines=middle,
    xlabel={$x$},
    ylabel={$y$},
    ymin=-10, ymax=10,
    xmin=-5, xmax=5,
    samples=200,
    domain=-5:-0.05, % First part of the function
    unbounded coords=jump,
    width=10cm,
    height=8cm,
    enlargelimits=true,
    axis line style={->},
    ticklabel style={font=\small},
    every axis y label/.style={at=(current axis.above origin), anchor=south},
    every axis x label/.style={at=(current axis.right of origin), anchor=west}
  ]
    \addplot[red, thick] {1/x};
    \addplot[red, thick, domain=0.05:5] {1/x}; % Second part of the function
  \end{axis}
\end{tikzpicture}
\end{center}

\end{document}

```