---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: "2025-07-26"
amount of time: 
learning score:
---
Periodic Property  : sin and cos are period $\pi$

$\cos( \circ  + 2\pi) =\cos \circ$ 
$$
\begin{array}{l} \\
\cos  (\circ + 360^\circ )  = \cos \circ  \\
\cos ( \circ -2\pi) =  \cos \circ   \\
\sin (\circ  + 2 \pi)  = \sin \circ  \\
\sin  ( \circ  +  360^\circ ) =  \sin \circ   \\
\sin ( \circ -2\pi) =  \sin  \circ   \\
\end{array}
$$
this is can be summarize as the equation :  $\cos||\sin(\circ +  2n)$

because $2n\pi$  mean that just n how many unit time the circle turn 
![[Pasted image 20250726124712.png]]
Example find  
$$
\begin{array}{l} \\
\cos 5\pi  =  \cos( \pi + 4\pi )  = \cos \pi  =  1   \\
\sin (-420) = \sin ( -360 -60 )  = \sin (-60)  = -\frac{\sqrt{ 3 }}{2}
\end{array}
$$
## even odd property 
$$
\begin{array}{l} \\
\cos  -\circ  =  \cos \circ \\
\sin  \circ   =  - \sin \circ 
\end{array}
$$


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=1pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm, scale = 2]
    % Draw x-axis 
    \draw[->] (-2,0) -- (2,0) node[right] {};
    \draw[->] (0,-2) -- (0,2) node[right] {}; 
     \draw[->] (0,0) -- (1,0.5) node[right] {(cos , sin)};  
     \draw[->] (1,0.5) -- (1,0.5) node[right] {(cos , sin)};  
      \draw[->] (0,0) -- (1,-0.5) node[right] {cos - , sin - };
    % Draw tick marks and labels
    \foreach \x in {-1,0,1} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-1,0,1} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    } 
\draw (0,0) circle (1cm);
 
\end{tikzpicture}
\end{document}

```
