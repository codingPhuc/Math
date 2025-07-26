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
\usetikzlibrary{decorations.pathreplacing, angles, quotes}
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis

\draw (0,0) coordinate (A) node[anchor=north]{$1$}
        -- node[midway, below]{B} 
        (4,0) coordinate (C) node[anchor=north]{$2$}
        -- node[midway, right]{C} 
        (0,4) coordinate (B) node[anchor=south]{$3$}
        -- node[midway, above left]{A} 
        cycle;

    % Add angle at point A (between sides AC and AB)
    \pic["$50^\circ$", draw=orange, angle radius=1cm, angle eccentricity=1.2] 
        {angle = B--C--A};

 
\end{tikzpicture}
\end{document}

```


we define the funciton  
$$
\sin (\circ)  =  \frac{app}{hyp}   = \frac{a}{c }
$$
$$
 \cos(\circ)   =  \frac{adj}{hyp} = \frac{b}{c }
$$
$$
 \tan(\circ)  =   \frac{opp}{hyp} =  \frac{a}{b}
$$
why is $\tan(\circ) =  \frac{\sin(\circ)}{\cos(\circ)}$  
$$
\frac{\sin(\circ)}{\cos(\circ)}  =  \frac{\left( \frac{opp}{hyp} \right)}{}
$$