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
 \tan(\circ)  =   \frac{opp}{adj} =  \frac{a}{b}
$$
why is does the equation of exit? 
because $\tan(\circ) =  \frac{\sin(\circ)}{\cos(\circ)}$  
$$
\frac{\sin(\circ)}{\cos(\circ)}  =  \frac{\left( \frac{opp}{hyp} \right)}{\frac{adj}{hyp} }   =   \frac{opp}{adj} =  \frac{a}{b}
$$

$$
 \sec \circ   = \frac{1}{\cos \circ} =  \frac{1}{\frac{adj}{hyp}}   = \frac{hyp}{adj} =  \frac{c}{b }
$$
$$
 \csc \circ  =  \frac{1}{\sin \circ}   =  \frac{1}{\frac{opp}{hyp}}  =  \frac{hyp}{opp} =  \frac{a}{c  }
$$
$$
\cot \circ = \frac{1}{\tan \circ }  = \frac{1}{\frac{opp}{adj}}  = \frac{adj}{opp}  = \frac{b}{a} 
$$
find the exact value of all six string function of angle $\circ$ in this right triangle  


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing, angles, quotes}
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis

\draw (0,0) coordinate (A) node[anchor=north]{$1$}
        -- node[midway, below]{2} 
        (4,0) coordinate (C) node[anchor=north]{$2$}
        -- node[midway, right]{5} 
        (0,4) coordinate (B) node[anchor=south]{$3$}
        -- node[midway, above left]
        cycle;

    % Add angle at point A (between sides AC and AB)

 
\end{tikzpicture}
\end{document}

```
