---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-08-23
amount of time:
learning score:
---


# #definition 

$$
\begin{array}{l} \\
\lim_{  x \to 2 } \frac{x^2 + 4x  - 12}{ x^2 - 2x  }   \\
\end{array}
$$


| x     | f(x)      |
| ----- | --------- |
| 1.9   | 4.157     |
| 1.99  | 4.01507   |
| 1.999 | 4.0015007 |
| 2.1   | 3.857     |
| 2.01  | 3.985     |
| 2.001 | 3.9985    |
we need to  note two thing :  
1. first the domain of the function does not accept x = 2  it will cause an undefine error if it does 
2. from the table we can see that the function is going to 4 as x approach 2  


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

   
      \draw[very thick, red, domain=2.1:4, smooth] plot(\x, {((\x)^2 + 4*\x - 12)/((\x)^2 - 2*\x)}); 
          \draw[very thick, red, domain=1:1.9, smooth] plot(\x, {((\x)^2 + 4*\x - 12)/((\x)^2 - 2*\x)});
\end{tikzpicture}
\end{document}


``` 


# todo 
- [ ]  what does this sentence mean ? _There are many functions out there in the world that we can make as close to_ _L_ _for specific values of_ _x_ _that are close to_ _a__, but there will be other values of_ _x_ _closer to_ _a_ _that give functions values that are nowhere near close to_ _L_ 
- [ ] what make  L and a different is L just a way of saying the limit of the function getting closer and closer to basically the function is getting close to a, so why do we need to both make it closer to a and L. Or does it mean that the limit should exit in a close range, a range that we define to get us the best result of x satisfying L condition like this : 
 f(x) no more than 0.001 away from L. This means that we want one of the following

$f(x)−L<0.001$ if f(x) is larger than 
\L−f(x)<0.001$ if f(x) is smaller than L
where L is a the limit or value that we want the function to be closest to a 
L is the domain we put on x, to get the range of f(x) that satisfy L 



