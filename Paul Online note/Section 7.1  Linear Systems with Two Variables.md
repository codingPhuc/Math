---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/SystemsTwoVrble.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-05-12
amount of time: 
learning score:
---
A linear system with two variables is any system that can be written in the form of 
$$
\begin{array}{l}  
ax + by =  p    \\
cx  + dy  = q 
\end{array}
$$
where any constant can be zero with the exception that each equation must have at least one variable in it 
Also , the system is only linear  of the variables are only the first power ,are only numerator and there are no product of variable in any of the equation 
Here is an example of systems with numbers  

$$
\begin{array}{l}  
3x - y =  7  \\
2x + 3 y = 1  
\end{array}
$$


before solving the equation we must ask what the solution to a system of equation is . A solution to a system of equation is a value of x and a value of y that , when substituted into the equation ,satisfies both equation at the same times 

from the example above  $x = 2$ and $y = -1$ is a solution to the system. This is easy to check 

$$
\begin{array}{l} \\
3\cdot 2 + 1   =  7  \\
2\cdot 2  + 3 \cdot -1 = 1  
\end{array}
$$
So , sure enough a pairs of number is a solution to the system . Do not worry about how we got these values . This will be the very first system that we solve when we get into the example 

For reference , it is very important for the pairs of number to satisfy the equation. For instance , $x=1$ and $y=-4$ will satisfy the first equation , but not the second so it is not a solution to the system. Likewise,  x =-1 and y = 1 will satisfy the second equation but not the first and so can't be a solution to the system



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
    \draw[thick, blue, domain=-2:4, smooth] plot (\x, { 3*\x - 7  }); 
     \draw[thick, red, domain=-2:4, smooth] plot (\x, { (-2*\x -1 )/3  }); 
\end{tikzpicture}
\end{document}


``` 

the solution to the two system is where the two line will intersect . So , when solving linear system with two variable we are asking where to two lines will intersect 

We will be looking at two method for solving this equation 

The first method is called **method of substitution** . In this method we will solve one equation for one variable and substitute this into the other equation . This will give us one equation with one variable that we can solve.


## Solve each of the following systems. 

$$ 
\begin{array}{l} \\  
\left\{ \begin{array}{l}
3x - y  =  7  \\ 
 2x  + 3y  = 1  
\end{array} \right. \\ 
\left\{ \begin{array}{l}
y  =  3x   - 7 \\
 2x  + 3(3x   - 7)  = 1  
\end{array} \right. \\ 
\left\{ \begin{array}{l}
y  =  3x   - 7 \\
11x  - 21  = 1  
\end{array} \right.  \\
\left\{ \begin{array}{l}
y  =  3\cdot  2   - 7    = -1 \\
x  =2  
\end{array} \right. \\
\end{array}
$$

$$ 
\begin{array}{l} \\  
\left\{ \begin{array}{l}
5x +  4y  = 1       \\
3x  -  6y  = 2 
\end{array} \right. \\ 
\left\{ \begin{array}{l}
y =  \frac{1  -5x }{4}   \\
3x  - 3\left( \frac{1  -5x }{2} \right)  =2 
\end{array} \right. \\ 
\left\{ \begin{array}{l} 
y =  \frac{5x -1}{4}   \\
6x     -3  ( 1  -5x ) -3  +  15x  =4  
\end{array} \right.  \\
\left\{ \begin{array}{l}
y =  \frac{5\cdot \left( \frac{1}{3} \right) -1}{4}    = \frac{1}{6}\\
x=\frac{1}{3}
\end{array} \right. \\
\end{array}
$$




As with single equation we could always go back and checking this solution by plugging that it satisfy both the equation . Note as well that we really need to plug in both equations . 

let move on to the next method for solving the equation . As we saw in the pervious example method of s
substitution will force us to deal with fraction ,which adds to the likely hood of mistake . This second method will not have this problem . We that not the complete true .  IF fraction were to show up then it will show up in the final solution 

the second method is called method of elimination . Where we multiply both of the equations by a number so that one variables in each equation will have the same coefficient with opposite sign . Then we will add two equation together , the result will be a single equation that we will solve for one of the variables . Then substitute the value back into one of the original equation 
## solve each of the following system 

$$ 
\begin{array}{l} \\  
\left\{ \begin{array}{l}
2x + 4 y =  -10     \\
6x +  3 y =  6 
\end{array} \right. \\ 
\left\{ \begin{array}{l}
2x + 4 (2 -2x) =  -10\\  
2 -2x    = y 
\end{array} \right. \\ 
\left\{ \begin{array}{l} 
-6x  =  -18\\  
2 -2x    = y 
\end{array} \right.  \\
\left\{ \begin{array}{l}
y =  -4   \\
x  = 3 
\end{array} \right. \\
\end{array}
$$
![[Pasted image 20250512173208.png]]


$$
\begin{aligned}
&2x + 4y = -10 \\
&6x + 3y = 6 \\
\\
&\text{Multiply the first equation by } -3: \\
&-3(2x + 4y) = -3(-10) \Rightarrow -6x - 12y = 30 \\
&\text{Second equation remains the same: } 6x + 3y = 6 \\
\\
&\text{Add the equations:} \\
&(-6x - 12y) + (6x + 3y) = 30 + 6 \\
&-9y = 36 \\
&y = -4
\end{aligned}
$$


There is a third method that we'll  be looking at for solving system of two equation. But it is more used full for system of at least three equation so will look at it in later section 

Solve the following system of equations 


$$ 
\begin{array}{l} \\  
\left\{ \begin{array}{l}
x - y = 6  \\
-2x  +  2y  =1  
\end{array} \right. \\ 
\left\{ \begin{array}{l}
x = 6+ y     \\
   -12   -2y  + 2 y  = 1 
\end{array} \right. \\ 
\left\{ \begin{array}{l} 
x = 6+ y     \\
   -12  + 0 = 1  ?? 
\end{array} \right.  \\

\end{array}
$$

![[Pasted image 20250512173224.png]]
-12  cannot equal to 1 , so there must be and error in our  work  to see graph these two lines 



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
    \draw[thick, blue, domain=-2:4, smooth] plot (\x, { \x - 6  }); 
     \draw[thick, red, domain=-2:4, smooth] plot (\x, { (1+2*\x)/2  }); 
\end{tikzpicture}
\end{document}


``` 
it appears that these two lines are parallel (can you verify that with the slopes) and we know that parallel line with different y-intercepts( that's important) will never cross 
As saw in the opening discussion solution represent the point where two lines cross . If two line don't intersect we can't have a solution 

The system in the previous example is called **inconsistent** 

$$
\begin{array}{l} \\
\left\{ \begin{array}{l}
2x +  5 y  = -1   \\
-10x  - 25y =  5  
\end{array} \right. \\ 
\left\{ \begin{array}{l}
y =  \frac{-1  -2x}{5}  \\
-10x  - 25 (\frac{-1  -2x}{5}  )   =   5 
\end{array} \right.  \\
\left\{ \begin{array}{l}
y =  \frac{-1  -2x}{5}  \\
-10x +5 + 10x  =   5 
\end{array} \right. \\ 
\left\{ \begin{array}{l}
y =  \frac{-1  -2x}{5}  \\
5  =   5 
\end{array} \right.
\end{array}
$$
since the second equation  equal to it self 5, we concluded that there are a infinite number of solution to this equation  

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
    \draw[thick, blue, domain=-2:4, smooth] plot (\x, {( -1  -2*\x)/5 }); 
     \draw[thick, red, domain=-2:4, smooth] plot (\x, {(-10*\x   - 5)/25 }); 
\end{tikzpicture}
\end{document}


``` 
so there are infinite solution  number of possible t there must be an **infinite number of solutions** to this system and they are given by 
$$
\begin{array}{l} \\
x = t  \\
y =  -\frac{2}{5} t   - \frac{1}{5}
\end{array}
$$
System such as those in the pervious example are called dependent 
We're now seen all three possible solution for a system of equation .A system of equation  will either have one , none or infinite 



# #Practice_Exercise  


## use the Method of Substitution to find the solution to the given system or to determine if the system is inconsistent or dependent. 
$$
\begin{array}{l} \\
\left\{ \begin{array}{l}
x - 7y = -11   \\
5x + 2y =  -18  
\end{array} \right. \\ 
\left\{ \begin{array}{l}
y   =  \frac{x+ 11}{7} \\
5x  + 2(\frac{x+ 11}{7}) =  -18 
\end{array} \right.  \\
\left\{ \begin{array}{l}
y   =  \frac{x+ 11}{7} \\
35x  +   2x + 22  =  -126  
\end{array} \right. \\ 
\left\{ \begin{array}{l}
y =  \frac{-4+ 11}{7}  = 1 \\
x  = -4 
\end{array} \right.
\end{array}
$$



$$
\begin{array}{l} \\
\left\{ \begin{array}{l}
7x - 8y =  -12   \\
-4x + 2 y = 3 
\end{array} \right. \\ 
\left\{ \begin{array}{l}
7x - 8y =  -12   \\
y  =  \frac{3+ 4x}{2}
\end{array} \right.  \\
\left\{ \begin{array}{l}
7x    - 12  -16x=  -12   \\
y  =  \frac{3+ 4x}{2}
\end{array} \right. \\ 
\left\{ \begin{array}{l}
x = 0    \\
y  =  \frac{3}{2}
\end{array} \right.
\end{array}
$$



$$
\begin{array}{l} \\
\left\{ \begin{array}{l}
3x +  9y =  -6  \\
-4x - 12y  =  8 
\end{array} \right. \\ 
\left\{ \begin{array}{l}
x  =  -3y  -2   \\
  + 12y  +  8  - 12y  =  8 
\end{array} \right.  \\
\left\{ \begin{array}{l}
x  =    -3y  -2  \\
0  = 0   
\end{array} \right. \\ 

\end{array}
$$


the result is true for every value of y or x and so we know that the system is **dependent** and there will be an infinite number of solution to the system . We will write the "solution" to this system as following 
$$
\begin{array}{l} \\
x =  -3t  -2    \\
y =  t  \text{ t is any number}
\end{array}
$$

## use the Method of Elimination to find the solution to the given system or to determine if the system is inconsistent or dependent. 



$$
\begin{aligned}
&6x  - 5y  =  8 \\
& -12x  +   2y  = 0  \\
\\
&\text{Multiply the first equation by } 2: \\
&12x  - 10y  =  16 
&\text{Second equation remains the same: }  -12x   +   2y  = 0  \\
\\
&\text{Add the equations:} \\
&( 12x   -12x  ) + ( - 10y    +   2y  ) = 16 \\
&-8y = 16 \\
&y = -2  \\
&x =  \frac{1}{3} 
\end{aligned}
$$

$$
\begin{aligned}
&-2x +  10y  =  2 \\
& 5x  - 25y  = 3   \\
\\
&\text{Multiply the first equation by } 5: \\
&-10 x  + 50y  =  10   \\
&\text{Multiply the second  equation by  }  2 : \\
&10x - 50y = 15 
\\
&\text{Add the equations:} \\
&( -10 x  + 10x  ) + ( 50y   - 50y  ) = 25 \\
&0 = 25 \\
\end{aligned}
$$
since  $0\neq25$ we conclude that the equation is inconsistent and have no solution 


$$
\begin{aligned}
&2x  +  3y  = 20 \\
&7x + 2y  = 53    \\
\\
&\text{Multiply the first equation by } 2: \\
&4x  +  6y  = 40 \\
&\text{Multiply the second  equation by  }  -3: \\
&-14x  -  6y  = -159  
\\
&\text{Add the equations:} \\
&( -10 x  + 10x  ) + ( 50y   - 50y  ) = 25 \\
&0 = 25 \\
\end{aligned}
$$
since  $0\neq25$ we conclude that the equation is inconsistent and have no solution 



