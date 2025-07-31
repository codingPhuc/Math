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

$$
\cos(\circ)^2  + \sin (\circ)^2  = 1  
$$


example if $\sin(t) = -\frac{2}{7}$ and  t is angle that lies in quadrant III , find the $\cos(t)$ 

$$
\begin{array}{l} \\
\cos t^2   +  \sin t^2  = 1  \\ 
(\cos t)^2  +\left( -\frac{2}{7} \right)^2  =1   \\
(\cos t)^2  +  \frac{4}{49}   = 1   \\
(\cos t)^2    =  1  - \frac{4}{49}    =  \frac{45}{49} 
\end{array}
$$
cost  


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=1pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm, scale = 2]
    % Draw axes
    \draw[->] (-2,0) -- (2,0) node[right] {$x$};
    \draw[->] (0,-2) -- (0,2) node[above] {$y$}; 

    % Draw unit circle
    \draw (0,0) circle (1cm);

    % Draw angle in Quadrant III
    \draw[->, thick, blue] (0,0) -- (-0.9,-0.4) node[below left] {};
    
    % Draw triangle
    \draw[thick, red] (0,0) -- (-0.9,-0.4) -- (-0.9,0) -- cycle;

    % Label triangle sides
    \node at (-0.45, -0.2) [above left] {$7$}; % hypotenuse
    \node at (-0.9, -0.2) [below] {$-2$}; % opposite
    \node at (-0.45, 0) [below] {$-3\sqrt{5}$}; % adjacent (approx. -6.7)

    % Dotted angle arc
    \draw[dashed] (0.6,0) arc (0:-155:0.6cm);
    \node at (-0.2, -0.6) {$t$};
\end{tikzpicture}
\end{document}

```
