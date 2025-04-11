---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Transformations.aspx
tags:
  - In_Progress
reference: https://www.youtube.com/watch?v=Tmdrjs9xufc&ab_channel=TheOrganicChemistryTutor
Current date: 2025-04-11
---

$f(x)+ 2$  vertical shift graph is gona move up 2 unit 
$f(x) -3$ vertical shift down 3 unti 

$f(x-4)$ horizon tal shift , this shift is 4 unit to the right 
$f(x+3)$ shift to the left 3 unit  

$-f(x)$  reflex over the x-axis 
$f(-x)$ reflex over the y-axis
$-f(-x)$ reflex over the origin 

2$f(x)$ vertical stretch 
$\frac{1}{2}f(x)$ shink vertically 
$f(2x)$ horizontal shink 
$f\left( \frac{1}{2}x \right)$ horizontal stretch 


$y =\sqrt{ x }$ 

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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:4, smooth] plot (\x, { sqrt(\x )  });
 
\end{tikzpicture}
\end{document}


``` 



$y = - \sqrt{ x }$ 

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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:4, smooth] plot (\x, {- sqrt(\x )  });
 
\end{tikzpicture}
\end{document}


``` 



$y = \sqrt{ -x }$ 

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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:-4, smooth] plot (\x, { sqrt(-\x )  });
 
\end{tikzpicture}
\end{document}


``` 




$y = -\sqrt{ -x }$ 

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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:-4, smooth] plot (\x, {- sqrt(-\x )  });
 
\end{tikzpicture}
\end{document}


``` 

$y=\mid  x \mid$




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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:-4, smooth] plot (\x, {-\x} );
	\draw[thick, blue, domain=0:4, smooth] plot (\x, {\x } );
   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```




$y= 2\mid x \mid$ 





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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:-4, smooth] plot (\x, {2*-\x} );
	\draw[thick, blue, domain=0:4, smooth] plot (\x, {2*\x } );
   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```
vertical stretch mean the y value increase 


$y=\frac{1}{2}\mid x \mid$





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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:-4, smooth] plot (\x, {0.5*-\x} );
	\draw[thick, blue, domain=0:4, smooth] plot (\x, {0.5*\x } );
   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```

vertical shrink when the y value decrease 


$y=\sqrt{ x }$




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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:4, smooth] plot (\x, {sqrt(\x)} );

   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```

$y=\sqrt{ 2x }$ 





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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:4, smooth] plot (\x, {sqrt(2*\x)} );

   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```
this is a horizontal shrink because the x value is less than what is needed for y to reach 2 

$y=\sqrt{ \frac{1}{2} }x$





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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:8, smooth] plot (\x, {sqrt(0.5*\x)} );

   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```
this is a horizontal stretch because the x value need to be increase in order to reach the same y value 


$y= x^3$ 

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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=-2:2, smooth] plot (\x, {pow(\x, 3)} );

   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```

$y=\mid  x \mid$

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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:-4, smooth] plot (\x, {-\x} );
	\draw[thick, blue, domain=0:4, smooth] plot (\x, {\x } );
   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%

\draw[dotted, red, domain=-6:-3, smooth] plot (\x, { -(\x  +3) -5 });
\draw[dotted, red, domain=-3:0, smooth] plot (\x, { (\x  +3) -5 });

\end{tikzpicture}
\end{document}


```


$$
 y  = (x- 2)^2 + 3
$$

so the origin will shift to the right by  2   and  up 3  
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
    \fill (2,0) circle (2pt) node[above right] {$(2,0)$};
	\fill (0,3) circle (2pt) node[above right] {$ (0,3) $};
	\fill (2,3) circle (2pt) node[above right] {$ (0,3) $};
    % Draw the parabola
   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\draw[dotted, red, domain=0:4, smooth] plot (\x, { (\x- 2)^2 + 3 });
\draw[thick, blue, domain=-2:2, smooth] plot (\x, { (\x)^2 });

\end{tikzpicture}
\end{document}


```
$$
 y =  3 - (x + 2)^2 \implies  y =  - (x + 2)^2  +3 
$$


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
    \fill (2,0) circle (2pt) node[above right] {$(2,0)$};
	\fill (0,3) circle (2pt) node[above right] {$ (0,3) $};
	\fill (2,3) circle (2pt) node[above right] {$ (0,3) $};
    % Draw the parabola
   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\draw[dotted, red, domain=0:4, smooth] plot (\x, { (\x- 2)^2 + 3 });
\draw[thick, blue, domain=-2:2, smooth] plot (\x, { (\x)^2 });

\end{tikzpicture}
\end{document}


```



## quick  trick to stretch the graph 
for the example  : 
$$
g(x) = 3  - (x+ 2)^2  
$$

which clearly shows:
we will start with the parent function  
$$
f(x) = -(x)^2  
$$
now let consider it transform function which is  
$$
g(x)  =  -(x+ 2)^2  + 3 
$$
which confirm that there is a horizontal shift to the left by 2 , and a vertical shift to the top 3 (x  -2 , y + 3)
to map the corresponding point of $f(x)$ to $g(x)$ we need to follow these step : 
1. plug in a point of $f(1)=-(1)^2=-1$ resulting in the point $(1,-1)$
2. to find the corresponding shift point we need  to find the x of the child graph combine with the c unit that result in the x of the parent graph $x_{c}+ u =x_{p} \text{ so } x+2=1\implies x=-1$   
$$
g(−1)=3−(−1+2)^2=3−1=2
$$
so point $g(-1) = 2$ is the shifted point of $f(1)=-1$



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
    \fill (1, -1 ) circle (2pt) node[above right] {$(1, -1 )$};
	\fill (-1,2)  circle (2pt) node[above right] {$ (-1,2) $};
    % Draw the parabola
   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\draw[dotted, red, domain=-3:0, smooth] plot (\x, { 3  - (\x+ 2)^2 });
\draw[thick, blue, domain=-2:2, smooth] plot (\x, { -(\x)^2});

\end{tikzpicture}
\end{document}


```



$$
y  = 4 - \sqrt{  3 - x }
$$
the parent function of this is $f(x)=-\sqrt{ x }$  
plug in 1 we will have $f(1)= -1$
find the shifted point of $g(x)=4-\sqrt{ 3-x }$ we need to find $3-x =-1\implies x=4$ 
$$
 g(x ) = 4 - \sqrt{  3 - 4 }  =  3 
$$


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
    \fill (1, -1 ) circle (2pt) node[above right] {$(1, -1 )$};
	\fill (-1,2)  circle (2pt) node[above right] {$ (-1,2) $};
    % Draw the parabola
   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\draw[dotted, red, domain=0:5, smooth] plot (\x, {-sqrt(\x) });
\draw[thick, blue, domain=-6:2.3, smooth] plot (\x, {4 - sqrt(3 - \x) });

\end{tikzpicture}
\end{document}


```


