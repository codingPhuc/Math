---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: "2025-08-17"
amount of time: 
learning score:
---


## _look at a couple of exponential functions._  
sketch the graph of$f(x) =2^x$ and $g(x)=\left( \frac{1}{2} \right)^x$ 


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
 \node[blue] at (-3, 1) {$f(x) = 2^x$};
    \node[red] at (3, 1) {$f(x) = \left(\frac{1}{2}\right)^x = 2^{-x}$};
    % Draw the parabola
    \draw[thick, blue, domain=-2:2, smooth] plot (\x, {2^(\x)})  ;
    \draw[thick, red, domain=-2:4, smooth] plot (\x, {(1/2)^(\x)}) ;
\end{tikzpicture}
\end{document}


``` 

