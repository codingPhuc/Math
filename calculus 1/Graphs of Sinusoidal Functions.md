---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: "2025-07-31"
amount of time: 
learning score:
---

graph the function $y=3\sin(2x)$  with the attribute  
- astray by  3  
- compress  horizontally by  1/2  



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw axes
    \draw[->] (-7,0) -- (7,0) node[right] {$x$};
    \draw[->] (0,-7) -- (0,7) node[above] {$y$};

    % Tick marks and labels
    \foreach \x in {-6,-5,...,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    \foreach \y in {-6,-5,...,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[left] {\y};
    }

    % Right branch
  \draw[thick, red, domain=-6.28:6.28, smooth, samples=100]  node[ above] {sin} plot (\x, {3* sin((2* \x) r)});



\end{tikzpicture}
\end{document}

```
if then the graph change by adding one like  
$$
3 \sin2x + 1  
$$
then the graph have an uptick by 1 unit 


|               | midline | amplitude | period |
| ------------- | ------- | --------- | ------ |
| $y=\sin(x)$   |         |           |        |
| $y=3 \sin 2x$ |         |           |        |
| $y = 3 \sin$  |         |           |        |
