---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-07-26
amount of time: 
learning score:
---


$$

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
     \draw[->] (0,0) -- (1,0.5) node[right] {};
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
note up now   we have define sin , cos  , tan in terms of right triables for example , to find  sin 14 

```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing, angles, quotes}
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis



\draw 
  (0,0) coordinate (A) node[anchor=north]{$A$}
    -- node[midway, below]{$adj$} %  bases 
  (4,0) coordinate (C) node[anchor=north]{$C$}
    -- node[midway, right]{$opp$} % hyp 
  (4,4) coordinate (B) node[anchor=south]{$B$}
    -- node[midway, above left]{$hyp$} %adj
  cycle;
    % Add angle at point A (between sides AC and AB)

    \pic["$14^\circ$", draw=orange, angle radius=1cm, angle eccentricity=1.2] {angle = C--A--B} ;


 
\end{tikzpicture}
\end{document}

```
$$
 \sin  = \frac{opp}{hyp}
$$
what goes wrong if compute sin 120 using right tria