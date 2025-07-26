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
\usetikzlibrary{decorations.pathreplacing,
angles,quotes}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis

my angle/.style = {draw, fill=teal!30,
                   angle radius=7mm, 
                   angle eccentricity=1.1, 
                   right, inner sep=1pt,
                   font=\footnotesize} 
                   ]
\draw   (0,0) coordinate[label=below:$A$] (a) --
        (4,0) coordinate[label=below:$C$] (c) --
        (4,4) coordinate[label=above:$B$] (b) -- cycle;
\pic[my angle, "$\alpha=\SI{45}{\degree}$"] {angle = c--a--b};

 
\end{tikzpicture}
\end{document}

```
