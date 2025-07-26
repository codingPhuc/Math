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

%% \draw (0,0) coordinate (A) node[anchor=north]{$1$}
        -- node[midway, below]{2}  % base 
        (4,0) coordinate (C) node[anchor=north]{$2$}
        -- node[midway, right]{5}  % hyp 
        (0,4) coordinate (B) node[anchor=south]{$3$}
        -- node[midway, above left] % adj 
        cycle; %%



\draw 
  (0,0) coordinate (A) node[anchor=north]{$A$}
    -- node[midway, below]{$2$} 
  (4,0) coordinate (C) node[anchor=north]{$C$}
    -- node[midway, right]{$5$} 
  (0,4) coordinate (B) node[anchor=south]{$B$}
    -- node[midway, above left]{$$} 
  cycle;
    % Add angle at point A (between sides AC and AB)

 
\end{tikzpicture}
\end{document}

```



$$
\sin (\circ)  =  \frac{app}{hyp}   = \frac{2}{5 }
$$
$$
 \cos(\circ)   =  \frac{adj}{hyp} = \frac{\sqrt{ 21 }}{5 }
$$
$$
 \tan(\circ)  =   \frac{opp}{adj} =  \frac{2}{\sqrt{ 21 }}
$$



$$
 \sec \circ   = \frac{1}{\cos \circ} =  \frac{1}{\frac{adj}{hyp}}   = \frac{hyp}{adj} =  \frac{5}{\sqrt{ 21 } }
$$
$$
 \csc \circ  =  \frac{1}{\sin \circ}   =  \frac{1}{\frac{opp}{hyp}}  =  \frac{hyp}{opp} =  \frac{5}{2  }
$$
$$
\cot \circ = \frac{1}{\tan \circ }  = \frac{1}{\frac{opp}{adj}}  = \frac{adj}{opp}  = \frac{\sqrt{ 21 }}{2} 
$$



A kite fly as an angle of  75 degree , with the kit string extended to the length of 100m. How high did the kite fly ? 

```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing, angles, quotes}
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis



\draw 
  (0,0) coordinate (A) node[anchor=north]{$A$}
    -- node[midway, below]{$2$} %  bases 
  (4,0) coordinate (C) node[anchor=north]{$C$}
    -- node[midway, right]{$5$} % hyp 
  (0,4) coordinate (B) node[anchor=south]{$B$}
    -- node[midway, above left]{$$} %adj
  cycle;
    % Add angle at point A (between sides AC and AB)

 
\end{tikzpicture}
\end{document}

```



$$
\sin (75\circ)  =  \frac{y}{100}   \implies  y =   96.59 m 
$$
Mnemonic for the equations is called  : SOHCAHTOA 


without using calculator find sin(45 ) adn cos 45  using right triangle with hyp being 1  

```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing, angles, quotes}
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis



\draw 
  (0,0) coordinate (A) node[anchor=north]{$A$}
    -- node[midway, below]{$a$} %  bases 
  (4,0) coordinate (C) node[anchor=north]{$C$}
    -- node[midway, right]{$a$} % hyp 
  (4,4) coordinate (B) node[anchor=south]{$B$}
    -- node[midway, above left]{$1$} %adj
  cycle;
    % Add angle at point A (between sides AC and AB)
    \pic["$50^\circ$", draw=orange, angle radius=1cm, angle eccentricity=1.2] {angle = B--C--A};
    \pic["$50^\circ$", draw=orange, angle radius=1cm, angle eccentricity=1.2] {angle = B--A--C} ;
    \pic["$45^\circ$", draw=orange, angle radius=1cm, angle eccentricity=1.2] {angle = A--B--C};

 
\end{tikzpicture}
\end{document}

```

