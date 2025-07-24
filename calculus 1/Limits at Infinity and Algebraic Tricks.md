---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: "2025-07-24"
amount of time: 
learning score:
---
for  the two graph : 
$$
\lim_{ x \to \infty } \frac{5x^2 -4x}{2x^3  - 11x^2 + 12x}    
$$

$5x^2 -4x$ will result in the following :  
 
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
    \draw[thick, blue, domain=-1:4, smooth] plot (\x, {5(\x)^2 -4*\x});
 
\end{tikzpicture}
\end{document}


``` 


$\lim_{ x \to \infty }5x^2 -4x\xrightarrow{\text{}} \infty$


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
    \draw[thick, blue, domain=-1:4, smooth] plot (\x, {2*\x^3  - 11*(\x)^2 + 12*\x});
 
\end{tikzpicture}
\end{document}
``` 

$\lim_{ x \to \infty }2x^3  - 11x^2 + 12x\xrightarrow{\text{}} \infty$

polynomial of  a limit will result in : 
$$
\lim_{ x \to \infty } \frac{5x^2 -4x}{2x^3  - 11x^2 + 12x}     = \frac{\infty}{\infty}   \xrightarrow{\text{}} \text{ indeterminate form}
$$


##  step to solving indeterminate form 

factor out the highest power x in the numerator and the denominator:

$$
\begin{array}{l} \\
\lim_{ x \to 0 } \frac{5x^2 -4x}{2x^3  - 11x^2 + 12x}    \\
= \lim_{ x  \to 0 }  
\end{array}

$$