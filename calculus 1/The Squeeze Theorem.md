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
\draw[thick, blue, domain=0:3, smooth] 
  plot (\x, {2*\x + 2}) 
  node[pos=0.5, below] {y =  g(x)};

\end{tikzpicture}
\end{document}
``` 



suppose that we have 3 function  $$
f(x) , g( x) , h(x )
$$
limit only care about x value near a (not for x = a ) suppose 

## how  limit help solve wild behavior 


$$
\text{ Find }  \lim_{ x \to 0 }  \sin \left( \frac{1}{x} \right) 
$$


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width


\begin{tikzpicture}[x=10cm, y=3cm]
    \draw[->] (-0.2,0) -- (0.2,0) node[right] {};
    \draw[->] (0,-1.2) -- (0,1.2) node[above] {};

    % Ticks
    \foreach \x in {-0.2,-0.1,0.1,0.2} {
        \draw (\x,0.05) -- (\x,-0.05);
    }
    \foreach \y in {-1,1} {
        \draw (0.01,\y) -- (-0.01,\y) node[left] {\y};
    }

    % Plot sin(1/x)
    \draw[domain=0.01:1, smooth, variable=\x, thick, blue] plot ({\x},{\x^2*sin(1/\x r)});
    \draw[domain=0.01:1, smooth, variable=\x, thick, red] plot ({\x},{\x^2});
        \draw[domain=0.01:1, smooth, variable=\x, thick, green] plot ({\x},{-(\x)^2});

\end{tikzpicture}
  
\end{document}


```



it is tempting to used the product rule where 
$$
 \lim_{ x \to 0 }  \sin \left( \frac{1}{x} \right) \xrightarrow{\text{fail}} \text{ since limit does not exit }  
$$
## using Squeeze  Theorem 
$$
\begin{array}{l}  \\
-1 \leq \sin\left( \frac{1}{x} \right)   \leq   1   \\
-x^2 \leq x^2 \sin\left( \frac{1}{x} \right)  \leq x^2  \\
\end{array}
$$
$$
\lim_{ x \to 0 }    x^2 =  0 \cap  \lim_{ x \to 0 }  -x^2  = 0 \xrightarrow{\text{}} \lim_{ x \to \infty }  
$$


