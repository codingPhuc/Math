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

we written as rational is written as ratio of 2 polynomial 
$$
f(x ) = \frac{P(x)}{Q(x) }  
$$

graph of the function $h(x) = \frac{3x^2 - 12}{x^2 + 3x  -10}$ 

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
    \fill (2, 2) circle (2pt) node[above right] {$(2, 2) $};
   

\draw[thick, blue, domain=-3:1.99, smooth] 
    plot (\x, {(3*(\x)^2 - 12)/((\x)^2 + 3*\x - 10)});

\draw[thick, blue, domain=2.01:10, smooth] 
    plot (\x, {(3*(\x)^2 - 12)/((\x)^2 + 3*\x - 10)});


\end{tikzpicture}
\end{document}
``` 

how is the graph of this function $h(x)$ different from the graph of polynomial 

what is the end behavior of the graph 
horizontal asymptote at y = 3  

what is the behavior of the graph of this function h(x) near  x = -5 
vertical asymptote  at x = -5 


what is going on at x = 2  ? hole at x = 2 