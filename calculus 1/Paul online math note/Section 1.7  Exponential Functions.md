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

    % Draw the parabola
    \draw[thick, blue, domain=-2:4, smooth] plot (\x, {2^(\x)});
    \draw[thick, red, domain=-2:4, smooth] plot (\x, {(1/2)^(\x)});
\end{tikzpicture}
\end{document}


``` 




 solve for tan :
  $$
\begin{array}{l} \\
\frac{6t}{11} = 4.9098  +          2\pi n          \\
\frac{6t}{11}   =     1.7682    +          2\pi n       \\
\frac{6t}{11} = 9.0013  +  \frac{11\pi}{3}      \\
\frac{6t}{11} = 3.2415  +  \frac{11\pi}{3}           \\
\end{array}
$$





