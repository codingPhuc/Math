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
Sure, here is a table of cosine and sine values from 0 to 2pi at intermediate values, formatted for easy pasting into Obsidian. I've chosen common angles that divide the circle into 8 and 12 parts for good coverage.


| t (radians) | 0 | $\pi/6$ | $\pi/4$ | $\pi/3$ | $\pi/2$ | $2\pi/3$ | $3\pi/4$ | $5\pi/6$ | $\pi$ | $7\pi/6$ | $5\pi/4$ | $4\pi/3$ | $3\pi/2$ | $5\pi/3$ | $7\pi/4$ | $11\pi/6$ | $2\pi$ |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| cos t | 1 | $\sqrt{3}/2$ | $\sqrt{2}/2$ | $1/2$ | 0 | $-1/2$ | $-\sqrt{2}/2$ | $-\sqrt{3}/2$ | -1 | $-\sqrt{3}/2$ | $-\sqrt{2}/2$ | $-1/2$ | 0 | $1/2$ | $\sqrt{2}/2$ | $\sqrt{3}/2$ | 1 |
| sin t | 0 | $1/2$ | $\sqrt{2}/2$ | $\sqrt{3}/2$ | 1 | $\sqrt{3}/2$ | $\sqrt{2}/2$ | $1/2$ | 0 | $-1/2$ | $-\sqrt{2}/2$ | $-\sqrt{3}/2$ | -1 | $-\sqrt{3}/2$ | $-\sqrt{2}/2$ | $-1/2$ | 0 |

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
  \draw[thick, blue, domain=-6.28:6.28, smooth, samples=100]  node[midway, above] {cos} plot (\x, {cos(\x r)});
  \draw[thick, red, domain=-6.28:6.28, smooth, samples=100]  node[ above] {sin} plot (\x, {sin(\x r)});

 
\end{tikzpicture}
\end{document}


``` 
the graph of cos is similar to sin but shifted horizontally to the left by $\frac{\pi}{2}$  
$$
\begin{array} {l}
\cos ( x )  =  \sin \left( x  + \frac{\pi}{2} \right)   \\
\sin (x )   =  \cos \left(  x  - \frac{\pi}{2} \right)
\end{array}
$$
Midline : a horizontal line between the maximum and minimum 
amplitude : is the vertical distance between max point and mid point 
period: the horizontal length of the smallest unit 


attribute of graph cos t and sin t  : 
midline is  

