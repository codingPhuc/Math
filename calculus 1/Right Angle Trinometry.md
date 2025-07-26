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


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis

\draw (0,0) coordinate (A) node[anchor=north]{$A$}
        -- node[midway, below]{cm} 
        (4,0) coordinate (C) node[anchor=north]{$C$}
        -- node[midway, right]{cm} 
        (4,4) coordinate (B) node[anchor=south]{$B$}
        -- node[midway, above left]{cm} 
        cycle;

    % Add angle at point A (between sides AC and AB)
    \pic["$50^\circ$", draw=orange, angle radius=1cm, angle eccentricity=1.2] 
        {angle = B--A--C};

 
\end{tikzpicture}
\end{document}

```
