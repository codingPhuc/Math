




Now we need to discuss  about graphing functions . if we recall from the pervious section we said that $f(x)$ is nothing more than a fancy way of writing y .This mean that we already know how to graph functions . We graph function in exactly the same way we graph equations . If we know ahead of time what the function is a graph of , we can used that information to help us graph , and if we do not know what the function is ahead of time then all we need to do is to plug in some x to compute the value of the funciton (which is really a y value) then plot the point 

$$
\begin{array}{l}
f(x) =   (x - 1)^3 + 1 
\end{array}
 
$$
in this graph we plug in the value of x to get  the value of y , then draw the graph  : 

| $x$ | $f(x)$ | $(x,y)$  |
| --- | ------ | -------- |
| -1  | -7     | (-1, -7) |
| 0   | 0      | (0,0 )   |
| 1   | 1      | (1,1)    |
| 2   | 2      | (2,2)    |
| 3   | 9      | (3,9)    |


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
    \fill (-1, -7) circle (2pt) node[above right] {$(3,0)$};
	\fill (0,0 ) circle (2pt) node[above right] {$(0,0 )$}; 
	\fill (1,1) circle (2pt) node[above right] {$(1,1)$};
	\fill (2,2) circle (2pt) node[above right] {$(2,2)$};
	\fill (3,9)   circle (2pt) node[above right] {$(3,9) $};
    % Draw the parabola
    \draw[thick, blue, domain=-1:2, smooth] plot (\x, {( \x - 1)^3+1});
\end{tikzpicture}
\end{document}


``` 

So  graphing function is pretty much the same as graphing equations 

There is one function we have seen  ,  that have not been  graphed like the first part of this chapter 

##  sketch the graph of the following piecewise function 
$$
\begin{aligned}\bullet\\\\g\left(x\right)=\left\{\begin{array}{ll}-x^{2}+4&\mathrm{if~}x<1\\2x-1&\mathrm{if~}x\geq1\end{array}\right.\end{aligned}
$$
okay when  graphing piecewise function  we are graphing serval function at one, except when we are going to graph them on specific interval .  In this cases we are going to be graphing the following two function : 
$$
\begin{array}{rcl}-x^2+4&\mathrm{~on~}&x<1\\2x-1&\mathrm{~on~}&x\geq1\end{array}
$$
We need to be careful with x =   1 since that will only be valid for the bottom function  . However we will deal with it when drawing the graph . For now , x =1  will be used in both function 

| $x$ | $-x^2  + 4$ | $(x,y)$   |
| --- | ----------- | --------- |
| -2  | 0           | (-2 ,  0) |
| -1  | 3           | (-1, 3 )  |
| 0   | 4           | (0,4)     |
| 1   | 3           | (1,3)     |



| $x$ | $2x - 1$ | $(x,y)$ |
| --- | -------- | ------- |
| 1   | 1        | (1,1)   |
| 2   | 3        | (2, 3)  |
| 3   | 5        | (3,5)   |
|     |          |         |

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
    \fill (1, 1) circle (2pt) node[above right] {$(1, 1) $};
    \fill[red] (1, 3) circle (2pt) node[above right] {$(1, 3)$};


    % Draw the parabola
    \draw[thick, blue, domain=-2:1, smooth] plot (\x, {-(\x)^2  + 4});
    \draw[thick, red, domain=1:3, smooth] plot (\x, {2*\x  - 1});
\end{tikzpicture}
\end{document}


``` 
here we specify with the red circle that the  graph does not reach the  top graph does not reach the x =1 point as oppose  to the bottom graph 

what does specific interval mean ? 
	an interval is a range of number between two point 

##  sketch the graph of the following piecewise function 

$$
\left.h\left(x\right)=\left\{\begin{array}{ll}x+3&\mathrm{if~}x<-2\\x^2&\mathrm{if~}-2\leq x<1\\-x+2&\mathrm{if~}x\geq1\end{array}\right.\right. 
$$
Here are three separate tables for each piece of the piecewise function:

### For $h(x) = x + 3$ when $x < -2$

| x   | $h(x)=x+3\;h(x) = x + 3$ | (x,y)(x, y |
| --- | ------------------------ | ---------- |
| -4  | -4 + 3 = -1              | (-4, -1)   |
| -3  | -3 + 3 = 0               | (-3, 0)    |
| -2  | -2 + 3   = 1             | (-2 ,  1)  |

---

### For $h(x) = x^2$ when $-2 \leq x < 1$

| xx  | $h(x)=x^2\;h(x) = x^2$ | (x,y)(x, y) |
| --- | ---------------------- | ----------- |
| -2  | $(-2)^2 = 4$           | (-2, 4)     |
| -1  | $(-1)^2 = 1$           | (-1, 1)     |
| 0   | $(0)^2 = 0$            | (0, 0)      |
| 1   | $1^2=0$                | (1, 1 )     |

---

### For $h(x) = -x + 2$ when $x≥1$

| xx  | $h(x)=−x+2\;h(x) = -x + 2$ | (x,y)(x, y) |
| --- | -------------------------- | ----------- |
| 1   | -1 + 2 = 1                 | (1, 1)      |
| 2   | -2 + 2 = 0                 | (2, 0)      |
| 3   | -3 + 2 = -1                | (3, -1)     |




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
    \fill[red] (-2 ,  1)  circle (2pt) node[above right] {$(-2 ,  1) $};
    \fill (-2 ,  4)  circle (2pt) node[above right] {$ (-2 ,  4) $};	
    \fill (1 ,  1)  circle (2pt) node[above right] {$(1 ,  1)$};	
    % Draw the parabola 
    
    \draw[thick, blue, domain=-4:-2, smooth] plot (\x,{\x + 3 });
    \draw[thick, blue, domain=-2:1, smooth] plot (\x,{(\x)^2});
    \draw[thick, blue, domain=1:3, smooth] plot (\x,{-\x + 2 });

\end{tikzpicture}
\end{document}


``` 


# #Practice_Exercise  

$$
f(x) =  x^2  - 2 
$$
 

| $x$ | $f(x) =  x^2  - 2$ | $(x,y)$   |
| --- | ------------------ | --------- |
| -2  | 2                  | (-2 , 2)  |
| -1  | -1                 | (-1 , -1) |
| 0   | -2                 | (0,-2)    |
| 1   | -1                 | (1, -1 )  |

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

    \draw[thick, blue, domain=-2:1, smooth] plot (\x,{(\x)^2 -2 });


\end{tikzpicture}
\end{document}


``` 





$$
f(x) = \sqrt{ x + 1  }
$$
 

| $x$ | $f(x) =  \sqrt{ x + 1  }$ | $(x,y)$           |
| --- | ------------------------- | ----------------- |
| -1  | 0                         | (-1 ,  0)         |
| 0   | 1                         | (0,  1)           |
| 1   | $\sqrt{ 2 }$              | (1, $\sqrt{ 2 }$) |
| 3   | 2                         | (3,2 )            |



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

    \draw[thick, blue, domain=-1:3, smooth] plot (\x,{sqrt(\x + 1) });


\end{tikzpicture}
\end{document}


``` 











$$
f(x) = 9
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

    \draw[thick, blue, domain=-1:3, smooth] plot (\x,{9});


\end{tikzpicture}
\end{document}


``` 







$$
.f\left(x\right)=\left\{\begin{aligned}&10-2x&&\mathrm{if}x<2\\&x^{2}+2&&\mathrm{if}x\geq2\end{aligned}\right.
$$
Here are three separate tables for each piece of the piecewise function:



| x   | $h(x)=10- 2x$ | (x,y)     |
| --- | ------------- | --------- |
| 0   | 10            | ( 0 , 10) |
| 1   | 8             | (1, 8)    |
| 2   | 6             | (2 , 6)   |

| x   | $h(x)=x^2  +2$ | (x,y)   |
| --- | -------------- | ------- |
| 2   | 6              | (2, 6)  |
| 3   | 11             | (3, 11) |

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
    \fill[red] (2 ,  6)  circle (2pt) node[above right] {$(2 ,  6) $};
	\fill(2 ,  6)  circle (2pt) node[above right] {$(2 ,  6) $};	
    % Draw the parabola 
    
    \draw[thick, blue, domain=0:2, smooth] plot (\x,{10  - 2*\x });
    \draw[thick, blue, domain=2:3, smooth] plot (\x,{(\x)^2+ 2 } );

\end{tikzpicture}
\end{document}


``` 

$$
 f\left(x\right)=\left\{\begin{array}{ll}5+x&\mathrm{if}x\geq1\\2&\mathrm{if}-2\leq x<1\\1-x^2&\mathrm{if}x<-2\end{array}\right.
$$



Here are separate tables for each piece of the piecewise function:

### For f(x)=5+xf(x) = 5 + x when x≥1x \geq 1

| xx  | f(x)=5+xf(x) = 5 + x | (x,y)(x, y) |
| --- | -------------------- | ----------- |
| 1   | 5 + 1 = 6            | (1, 6)      |
| 2   | 5 + 2 = 7            | (2, 7)      |
| 3   | 5 + 3 = 8            | (3, 8)      |

### For f(x)=2f(x) = 2 when −2≤x<1-2 \leq x < 1

|xx|f(x)=2f(x) = 2|(x,y)(x, y)|
|---|---|---|
|-2|2|(-2, 2)|
|-1|2|(-1, 2)|
|0|2|(0, 2)|

### For f(x)=1−x2f(x) = 1 - x^2 when x<−2x < -2

| xx  | f(x)=1−x2f(x) = 1 - x^2 | (x,y)(x, y) |
| --- | ----------------------- | ----------- |
| -3  | 1 - (-3)^2 = -8         | (-3, -8)    |
| -4  | 1 - (-4)^2 = -15        | (-4, -15)   |
|     |                         |             |

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
    \fill[red] (2 ,  6)  circle (2pt) node[above right] {$(2 ,  6) $};
	\fill(2 ,  6)  circle (2pt) node[above right] {$(2 ,  6) $};	
    % Draw the parabola 
    
    \draw[thick, blue, domain=1:3, smooth] plot (\x,{\x  + 5 });
    \draw[thick, blue, domain=-2:1, smooth] plot (\x,{2 } ); 
    \draw[thick, blue, domain=-4:-2, smooth] plot (\x,{1  - (\x)^2 } );

\end{tikzpicture}
\end{document}


``` 
# #todo 
