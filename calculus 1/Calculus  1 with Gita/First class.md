---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-08-26
amount of time:
learning score:
---

[[Section 1.1  Functions]]
# #definition 


perform  function  F(x) with repeat to variable  x 
$$
\text{ input } \xrightarrow{\text{}} function  \xrightarrow{\text{}} ouput f(x)   
$$


## Function exercise 

F9  

## checking to know if the function is valid 
$f(x)^2 = x$
when  we  plug in the value let say  4  we can see that 1 input have 2 output causing the function to  not be valid 
$f(x)  = \sqrt{ 4 }  = \pm 2$
### Plugging in the function 
the first method is plugging in the function  

### graphing the function  
by  graphing the function you can visualize if the function have 2 output by drawing a vertical line from the x axis, if the line cross the function two time the function is not valid
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
    % Draw the parabol
\node[circle, draw, fill=black, inner sep=2pt, label=F(a)]  at  (2, 0.828) {};
\node[circle, draw, fill=black, inner sep=2pt, label=F(b)]  at  (4, 4) {};


    \draw[thick, blue, domain=0:4, smooth] plot (\x, {\x});
   \draw[thick, blue, domain=0:4, smooth] plot (1,\x );
 
\end{tikzpicture}
\end{document}


``` 
we can see  that the line only have 1 interception this mean that  it is a valid function 

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
    % Draw the parabol
\node[circle, draw, fill=black, inner sep=2pt, label=F(a)]  at  (2, 0.828) {};
\node[circle, draw, fill=black, inner sep=2pt, label=F(b)]  at  (4, 4) {};

\draw[thick, red, domain=-3:3, smooth] plot ( {(\x)^2} , \x);
   \draw[thick, blue, domain=-4:4, smooth] plot (4,\x );
 
\end{tikzpicture}
\end{document}


``` 
we can see that the line cross the function 2 time for a single x value, so we concluded that it is not a function  

For the function $f(x)=3x^{2}+2x-1$, evaluate
a. $f(-2)$ 
$$
\begin{array}

\end{array}
 f(-2)  =  3(-2)^2  + 2(-2)  - 1 

$$
b. $f(\sqrt{2})$
c. $f(a+h)$ 