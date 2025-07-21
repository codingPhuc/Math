---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: "2025-07-21"
amount of time: 
learning score:
---
Example : for the function g(x) suppose that ,for x-value near 1  

$$
4\sqrt{ x  }  \leq g( x ) \leq 3x^2  - 4x  +  5
$$
```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-7,0) -- (7,0) node[right] {};
    \draw[->] (0,-7) -- (0,7) node[right] {};
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-7,-6,-5,-4,-3,-2,-1,1,2,3,4,5,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    }

    % Text annotations  
    \fill (1, 1) circle (2pt) node[above right] {$(1, 1) $};
    \fill[red] (1, 3) circle (2pt) node[above right] {$(1, 3)$};


    % Draw the parabola
    \draw[thick, blue, domain=0:3, smooth] plot (\x, {3*(\x)^2 -4*\x +5});
    \draw[thick, red, domain=0:3, smooth]  plot (\x, {4* sqrt(\x)});  
\draw[thick, blue, domain=0:3, smooth] node[midway, above] {Midpoint Label} plot (\x, {2*\x  + 2});
\end{tikzpicture}
\end{document}
``` 


