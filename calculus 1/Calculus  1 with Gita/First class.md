perform  function  F(x) with repeat to variable  x 
$$
\text{ input } \xrightarrow{\text{}} function  \xrightarrow{\text{}} ouput f(x)   
$$


# checking to know if the function is valid 
## graphing the function  
by  graphing the function you can visualize if the function have 2 output by drawing a straig
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


    \draw[thick, blue, domain=2:4, smooth] plot (\x, {(\x)^(3/2)-\x});
 
\end{tikzpicture}
\end{document}


``` 

