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
$$
y = mx + b
$$
where m is the slope of the line  
b is the y-intercept of the line

$$
\text{ slope }  = \frac{rise}{sum} = \frac{y}{x}   = \frac{y_{2}-y_{1}}{x_{2}-x_{1}}
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
    \fill (1, 2) circle (2pt) node[above right] {$(1, 2) $};
    \fill[red] (5, -1) circle (2pt) node[above right] {$(5, -1)$};


    % Draw the parabola
\draw[thick, green, domain=0:6, smooth] 
  plot (\x, {-3/4*\x + 11/4}) 
 ;

\end{tikzpicture}
\end{document}
``` 

## find the equation of these lines 
```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}
  % Grid

    \draw[->] (-7,0) -- (7,0) node[right] {};
    \draw[->] (0,-7) -- (0,7) node[right] {};
  % Axes

  \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-7,-6,-5,-4,-3,-2,-1,1,2,3,4,5,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    }
  % Horizontal line at y=4
  \draw[blue, thick, ->] (-4,4) -- (4,4);
  \draw[blue, thick, <-] (-4,4) -- (-2.1,4);

  % Vertical dashed line at x = -2
  \draw[blue, thick, dashed, ->] (-2,-4) -- (-2,6);
  \draw[blue, thick, dashed, <-] (-2,-4) -- (-2,-3.9);
\end{tikzpicture}

\end{document}
```
horizontal line 
y = mx+ 6 
y = b  
m  = 0 
y = 3.5 
vertical line 
x = -2 



Find the equation of the line through the point (1,2) and (4,-3)
$$
m  = \frac{y_{2}-y_{1}}{x_{2}-x_{1}}   = \frac{-3-2}{-4-1}  = -\frac{5}{3}
$$

#todo 
Find the equation of the line through $(1,2)\cap(4,-3)$ 
method 1