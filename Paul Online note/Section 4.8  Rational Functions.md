---
title: Adjunction
references: 
tags:
  - In_Progress
reference: 
Current date: 2025-04-16
---
In this final section we will discuss  graphing  rational function .  It's best to start of with a simple one that we can do without all the knowledge in this work 
Let's sketch the graph of $f(x) =\frac{1}{x}$ . First , since this is a rational function we have too be careful with a division by  0 problem . In this equation we need to avoid $x=0$ since that will give division by zero

Now , let plug in some value of x to see what we see 

| x       | f(x)   |
|---------|--------|
| -4      | -0.25  |
| -2      | -0.5   |
| -1      | -1     |
| -0.1    | -10    |
| -0.01   | -100   |
| 0.01    | 100    |
| 0.1     | 10     |
| 1       | 1      |
| 2       | 0.5    |
| 4       | 0.25   |

So , as x get large (both positive and negative) the function keep the sign of x and gets smaller and smaller . Likewise , as we approach $x=0$ the function again keep the same sign of x but start getting quick large 

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
   \draw[red, thick, domain=0.3:3, samples=100] plot (\x, {1/\x});
  \draw[red, thick, domain=-3:-0.3, samples=100] plot (\x, {1/\x});

 
\end{tikzpicture}
\end{document}

```

1. the graph illustrated above is divided into 2 pieces 
2. the graph does not have any interception of any kind 
	recall that a graph will have y-interception at point $(0,f(0))$ . However ,  in this cases we need to avoid $x=0$ and so this  graph will never cross the y axis. It will lean toward it but never touch it 
3. next recall that we can get the x intercept by solving $f(x)=0$ . In rational function , this seem like a hard thing to deal with , but remember that we only need the numerator to be 0 not  the denominator . So try to avoid solution where the solution for $f(x)=0$ will cause the denominator to be 0
4. Finally we get to address that the graph gets very close to the x  and y-axis but never crosses . Since there isn't anything special about axis  it self we'll   use the fact that the x-axis is really the line given by $y=0$ and the y-axis is really the line given by $x=0$ 
5. In our graph as the value of x approaches x = 0 the graph start get very large on both side of the line given by x =0 . This line is called a **vertical asymptote** 
6. Also as x get very large , both  positive and negative the graph  approach the line given  by y  = 0 . This is called horizontal asymptote 
##  general definition for the two asymptotes 

1. The line x = a  is a **vertical asymptote** if the graph  increase or decrease without bound on one or both sides of the line as x move in closer and closer to x = a  
2. The line y = b  is a **horizontal asymptote** if the graph approaching  y =b  as x  increase or decreases without bound  . Note that it only need to approach y  by one side meaning that x is consider  **horizontal asymptote**  if  it increase  , decrease or both   


#word_meaning 
"**Increases or decreases without bound**" : means the graph shoots up toward **infinity** or down toward **negative infinity**. 
	like  $x \in {0.1,0.01,\dots}\implies f(X)\rightarrow \infty$
	 
Determining asymptotes  is actually a fairly simple process  . First , let start with a rational function 
$$
 f(x) = \frac{ax^n  + \dots} { bx^m + \dots}
$$
when  n is the largest exponent in the numerator and m is the largest exponent in the denominator  
we then have the following facts about asymptotes 
1. The graph will  have a vertical asymptote  at $x=a$ if the denominator is zero at $x=a$ and the numerator is not zero at $x=a$ 
2. if $x<m$ then the x-axis is the horizontal asymptote 
3. if $n=m$ then the line $y=\frac{a}{b}$ is the horizontal asymptote 
4. if n > m there will be no horizontal asymptotes 

## Process for graphing a rational function 

1. Find the intercepts , if there are any . Remember that the y-intercept is given by $(0,f(0))$ and we find the x-intercepts  by setting the numerator equal to zero and solving 
2. Find the vertical asymptotes by setting the denominator equal to zero and solving 
3. Find the horizontal asymptote , if it exists  , using the fact above 
4. The vertical asymptotes will divide the number line into region . In each region graph at least one point in each region .This point will tell us whether the graph will be above or below the horizontal asymptote and we should get several point to determine the shape of the graph 
5. sketch the graph 

$$
\begin{array}{l} \\
f(x) =  \frac{3x + 6}{x  -1}   \\

\end{array}

$$
1. Find the intercepts , if there are any . Remember that the y-intercept is given by $(0,f(0))$ and we find the x-intercepts  by setting the numerator equal to zero and solving  
the y-intercept  
$$
\begin{array}{l} \\
 \frac{3x + 6}{x  -1}    \\
f(0) = -6 
\end{array}
$$
we have a  y intercept of $(0,-6)$
the x-intercept  

$$
\begin{array}{l} \\
3\cdot x +  6  =  0  \\
x  = -2
\end{array}
$$
since $-3\neq 1$ we have the x intercept of $(-2,0)$
vertical  asymptotes 
$x  -1 =0  \implies x   =1$
this mean that there will be two region of x where $x< -1 \cap x>1$

Now the largest exponent in the graph is one so the horizontal asymptote at the line 

$$
y = \frac{3}{1}  = 3  
$$

Now we just need point  in each region of x . Since the y-intercept and x-intercept are already in the left region we won't need to get any point there . That  mean that we only need to get the point in the right region . We  just need to keep it simple for this point 

$$
f(2) =  \frac{3(2)+  6}{2-1} = \frac{12}{1 } = 12 
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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
   \draw[red, thick, domain=1.5:5, samples=100] plot (\x, {(3*\x + 6)/(\x-1)});
   \draw[red, thick, domain=-5:0, samples=100] plot (\x, {(3*\x + 6)/(\x-1)});
 
\end{tikzpicture}
\end{document}

```


$$
f(x )  =  \frac{9}{x^2  -  9}
$$


the y-intercept  
$$
\begin{array}{l} \\
 f(0) = \frac{9}{x^2  -  9}   \\
f(0)  = -1 
\end{array}
$$
we have a  y intercept of $(0,-1)$
the x-intercept  


since the numerator is a whole number we do not have the x-intercept 
vertical  asymptotes: 
 $$
 \begin{array}{l}
  x^2 - 9  = 0 \\ 
  \left\{ \begin{array}{l }  
x  =  3  \\
x  = - 3 
\end{array}
 \right.
\end{array}

$$

this mean that there will be three region in our graph  where $x< -3 \cap -3  <  x < 3 \cap x>3$

Now the largest exponent in the graph is one so the horizontal asymptote at the line is 
There is not  horizontal  asymptote because there is no x in the numerator 


Now we just need point  in each region of x . Since the y-intercept and x-intercept are already in the left region we won't need to get any point there . That  mean that we only need to get the point in the right region . We  just need to keep it simple for this point 

$$
f(-4 )  =  \frac{9}{(-4)^2  -  9}  = -\frac{9}{7}

$$
$(-9)$
$$
f(4)  =   \frac{9}{7}  
$$
$9$

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
   \draw[red, thick, domain=-8:-4, samples=100] plot (\x, { 9/((\x)^2 - 9) });
     \draw[red, thick, domain=-2.5:2.5, samples=100] plot (\x, { 9/((\x)^2 - 9) });
  \draw[red, thick, domain=4:8, samples=100] plot (\x, { 9/((\x)^2 - 9) });
\end{tikzpicture}
\end{document}

```






$$
f(x )  = \frac{x^2 -4}{x^2  - 4x }
$$

the y-intercept  
$$
\begin{array}{l} \\
f(0)  =  -\frac{4}{0}
\end{array}
$$
the graph doesn't have a y intercept since there is no value that can divide by 0 
vertical  asymptotes: 
 $$
 \begin{array}{l}
x^2  - 4x = 0  \\ 
  \left\{ \begin{array}{l }  
x  =  0  \\
x  =  4  
\end{array}
 \right.
\end{array}

$$


this mean that there will be two region in our graph  where $x< 0 \cap x>4$



the x-intercept  
$$
\begin{array}{l}
x^2 -4 = 0  \\
  \left\{ \begin{array}{l }  
x  =  2  \\
x  =  -2   
\end{array}
 \right.
\end{array}
$$

since the numerator does not equal to  0 for value 
Now the largest exponent in the graph is one so the horizontal asymptote at the line is 
There is not  horizontal  asymptote because there is no x in the numerator 


Now we just need point  in each region of x . Since the y-intercept and x-intercept are already in the left region we won't need to get any point there . That  mean that we only need to get the point in the right region . We  just need to keep it simple for this point 

$$
f(-4 )  =  \frac{9}{(-4)^2  -  9}  = -\frac{9}{7}

$$
$(-9)$
$$
f(4)  =   \frac{9}{}  
$$
$9$

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
   \draw[red, thick, domain=-8:-4, samples=100] plot (\x, { 9/((\x)^2 - 9) });
     \draw[red, thick, domain=-2.5:2.5, samples=100] plot (\x, { 9/((\x)^2 - 9) });
  \draw[red, thick, domain=4:8, samples=100] plot (\x, { 9/((\x)^2 - 9) });
\end{tikzpicture}
\end{document}

```