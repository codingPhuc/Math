---
title: Adjunction
references: 
tags:
  - In_Progress
reference: 
Current date: "2025-04-23"
---
In this method we are going to get a rough sketch of a general polynomial. The only information that we are going to need a is a complete list of zero 
In this section we either be given a list of zero or they will be easy to find . In the next section we are going to go into method for determining  large portion of the list for most polynomial . We are graphing first instead of finding all the zero , we will do the other part latter on 

![[Pasted image 20250423084429.png]] 



Do not worry  about these polynomial we are giving these so that we can have the basic idea of the polynomial . 
First notice how all the hole are nice and smooth . There are no hole in the gap not break in the gap it is always nice an smooth 

Secondly  ,the hole  where the gap turn from increasing to decrease and vice versal are called turning point . For a graph with degree n it will have (n-1) turning point 

While this won't help must in graphing  , it will help in detecting error in our graph . For example if we have fourth degree polynomial with 5 turning point we will quickly spot the error 

Next we need to connect the relationship between the x intercept and the zero point of a polynomial . 
$$
P(x)  = 0 
$$
Also recall , that x = r is a zero of the polynomial , $P(x)$ , provided that $P(r) = 0$ . But that also mean that there is a solution x = r  that satisfy $P(x)$



In other word zero  of the polynomial also is the x intercept of the graph . Recall  , that the x intercept will either cross the graph or touch the x-axist without crossing the axis 

Notice as well that the x-intercept can either flatten out as they cross the x-axis or they can go through the x axis at that angle 


#fact 
	if  $x= r$ is a zero of the polynomial  $P(x)$ with a multiplicity of k then 
	1. if k  is an odd number then the x = r will cross the x axis 
	2. if k is and even number then the x =  r will only touch the x-axis and not actually cross it 
Furthermore  , if k > 1 then the graph will flatten out at $x=r$ 

Finally notice that we let x get large in both the positive and negative sense (ie . at either end of the graph ) it will increase or decrease without bound . This will happen with every polynomial and we will used the following test to determine the endpoints of the graphs 
## Leading Coefficient  Test 
Suppose the  $P(x)$ is polynomial  with degree n . So we know that the polynomial must look like 
$$
P(x)   = ax^n + \dots 
$$
We don't know if there are any other term in the polynomial , but  we do know that the first term will have to be one listed since it has degree n. We now have the following facts about the  graphs of  $P(x)$  at the ends of the graph 

1. if a> 0 and n  is even then the graph of $P(x)$ will increase a both end without bound .
  
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
    \draw[thick, blue, domain=-2:2, smooth] plot (\x, { (\x)^2  + 3  });
\end{tikzpicture}
\end{document}


``` 
2. if a>0 and n is odd then the graph of $P(x)$ will  increase without bound at the right end and decrease without bound at the left end . A good example of this is the graph $x^3$


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
    \draw[thick, blue, domain=-2:2, smooth] plot (\x, { (\x)^3});
\end{tikzpicture}
\end{document}


``` 


if $a<0$ and  n is even then the graph of$P(x)$ will decrease without bound at both endpoints . A good example of this is graphs of $x^2$
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
    \draw[thick, blue, domain=-2:2, smooth] plot (\x, { -(\x)^2    });
\end{tikzpicture}
\end{document}
``` 


4.  if a<  0  and n is an odd number then the graph of n will  increase without bound in the left and decrease without bound on the right 

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
    \draw[thick, blue, domain=-2:2, smooth] plot (\x, { -(\x)^3    });
\end{tikzpicture}
\end{document}
``` 

## process for graphing a polynomial 
1. Determine all the zeroes of the polynomial and their multiplicity . Use the fact above to determine the x-intercept that correspond  to each zero will cross the x-axis or just touch it or if the x intercept will flatten out or not 
2. Determine  the y-intercept $(0, P(0))$ 
3. Use the leading coefficient test to determine the behavior of the polynomial at the end of the graph 
4. 1. Plot a few more points. This is left intentionally vague. The more points that you plot the better the sketch. At the least you should plot at least one at either end of the graph and at least one point between each pair of zeroes. 



We should give a quick warning about this process , this process assume that all zero are real zero before operating 



Example 1 : 
1. Determine all the zeroes of the polynomial and their multiplicity . Use the fact above to determine the x-intercept that correspond  to each zero will cross the x-axis or just touch it or if the x intercept will flatten out or not 
Sketch the graphs of  $P(x) =5x^5-20x^4+5x^3 +50x^2-20x-40=5(x + 1)^2 (x- 2)^3$
we found out the zero point and the multiplicity of the equation in the previous example so we will just write them out again 
$$
 \begin{array}{l}  \\
x =  -1  \text{ multplicity of 2} \\
x = 2     \text{ multplicity of 3} 
\end{array}
$$

 if k  is an odd number then the x = r will cross the x axis  
we know that since the multiplicity of x = 2 is odd then x = 2  will cross the x axis 
 if k is and even number then the x =  r will only touch the x-axis and not actually cross it 
we know that since the multiplicity of x =  -1  is odd then x =  -1 will touch the x axis 
since both are larger then>1  we concluded that it would be flatten 
2. Determine  the y-intercept $(0, P(0))$ 
The y-intercept of the coefficient is (0 , -40 )
3. Use the leading coefficient test to determine the behavior of the polynomial at the end of the graph  
since the coefficient of the 5th term  is positive and the exponent is odd we can concluded that the graph will decrease without bound to  the left , and increase without bound to the right  
4.  Plot a few more points. This is left intentionally vague. The more points that you plot the better the sketch. At the least you should plot at least one at either end of the graph and at least one point between each pair of zeroes. 
$$
f(-2) =  5( -2 + 1)^2 (-2- 2)^3   =  -320 
$$ 

$$
f(3) =  5( 3 + 1)^2 (3- 2)^3   =  80   
$$


![[Pasted image 20250423112902.png]]  


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
    \draw[thick, blue, domain=0:6, smooth] plot (\x, {sqrt(\x)});
        \draw[dotted, red, domain=0:6, smooth] plot (\x, {sqrt(\x) -5});
 
 
\end{tikzpicture}
\end{document}


```





Example 1 : 
1. Determine all the zeroes of the polynomial and their multiplicity . Use the fact above to determine the x-intercept that correspond  to each zero will cross the x-axis or just touch it or if the x intercept will flatten out or not 
Sketch the graphs of  $P(x) =x^4   -x^3 - 6x^2=x^2(x - 3)(x + 2)$
we found out the zero point and the multiplicity of the equation in the previous example so we will just write them out again 
$$
 \begin{array}{l}  \\
x =  0   \text{ multplicity of 2} \\
x =  3  \text{ simple zero}   \\
x  =  -2     \text{ simple zero} 
\end{array}
$$

 if k  is an odd number then the x = r will cross the x axis   :  
we know that since the multiplicity of x = 3 is odd then x = 3   will cross the x axis  
we know that since the multiplicity of x = -2 is odd then x = -2   will cross the x axis 
 if k is and even number then the x =  r will only touch the x-axis and not actually cross it : 
we know that since the multiplicity of x =  0   is odd then x =  0 will touch the x axis 
since only  x =  0  are larger then>1  then x  =  0 will will be flat   , x = -2  and  x  =  3 on the other hand will not be flatten  

2. Determine  the y-intercept $(0, P(0))$ 
The y-intercept of the coefficient is (0 , 0)
3. Use the leading coefficient test to determine the behavior of the polynomial at the end of the graph  
since the coefficient of the 4th term  is positive and the exponent is even we can concluded that the graph will increase  without bound to  the left and   right  
4.  Plot a few more points. This is left intentionally vague. The more points that you plot the better the sketch. At the least you should plot at least one at either end of the graph and at least one point between each pair of zeroes. 
$$
f(-3) = (-3)^2(-3 - 3)(-3 + 2)   =  54  
$$ 

$$
f(4) = (4)^2(4- 3)(4+ 2)   =  96   
$$ 

$$
f(-1) = (-1)^2(-1- 3)(-1+ 2)   =  -4     
$$ 

$$
f(1) = (1)^2(1- 3)(1+ 2)   =  6     
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
    \fill (-3,3) circle (2pt) node[above right] {$(0,3) $};
\draw[thick, blue, domain=-2:3, smooth] plot (\x, {(\x)^2*(\x - 3)*(\x +2)});

    % Draw the parabola
\end{tikzpicture}
\end{document}


```






Example 1 : 
1. Determine all the zeroes of the polynomial and their multiplicity . Use the fact above to determine the x-intercept that correspond  to each zero will cross the x-axis or just touch it or if the x intercept will flatten out or not 
Sketch the graphs of  $P(x) =-x^5 +  4x^3 =-x^3(x  + 2)(x  - 2 )$
we found out the zero point and the multiplicity of the equation in the previous example so we will just write them out again 
$$
 \begin{array}{l}  \\
x =  0   \text{ multplicity of 3} \\
x =  -2  \text{ simple zero}   \\
x  =  2      \text{ simple zero} 
\end{array}
$$

 if k  is an odd number then the x = r will cross the x axis   :  
we know that since the multiplicity of x = 0  is odd then x =  0    will cross the x axis  
we know that since the multiplicity of x = -2 is odd then x = -2   will cross the x axis 
we know that since the multiplicity of x = 2 is odd then x = 2   will cross the x axis 
 if k is and even number then the x =  r will only touch the x-axis and not actually cross it : 

since only  x =  0  are larger then>1  then x  =  0 will will be flat   , x = -2  and  x  =  3 on the other hand will not be flatten  

2. Determine  the y-intercept $(0, P(0))$ 
The y-intercept of the coefficient is (0 , 0)
3. Use the leading coefficient test to determine the behavior of the polynomial at the end of the graph  
since the coefficient of the 5th term  is negative  and the exponent is odd we can concluded that the graph will increase  without bound from the left  and decrease without bound in the right 
4.  Plot a few more points. This is left intentionally vague. The more points that you plot the better the sketch. At the least you should plot at least one at either end of the graph and at least one point between each pair of zeroes. 
$$
f(-1) = -(-1)^3(-1  + 2)(-1  - 2 )  =   3  
$$
$$
f(1) = -1^3(1  + 2)(1  - 2 )  =    3  
$$
$$
f(3) = -3^3(3  + 2)(3  - 2 )  =  -135     
$$
$$
f(-3) = 3^3(-3  + 2)(-3  - 2 )  =  135     
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
    \fill (-3,2) circle (2pt) node[above right] {$(0,3) $};
\draw[thick, blue, domain=-2:2, smooth] plot (\x, {-(\x)^3*(\x  + 2)*(\x  - 2 )});

    % Draw the parabola
\end{tikzpicture}
\end{document}


```




# #Practice_Exercise   


##  Sketch the graph of each of the following polynomials. 

Example 1 : 
1. Determine all the zeroes of the polynomial and their multiplicity . Use the fact above to determine the x-intercept that correspond  to each zero will cross the x-axis or just touch it or if the x intercept will flatten out or not 
Sketch the graphs of  $G(x)   =  x^3  - 2x^2  - 24x   =x(x^2  -2x  -  24) =x(x+4)(x-6)$
we found out the zero point and the multiplicity of the equation in the previous example so we will just write them out again 
$$
 \begin{array}{l}  \\
x =  0   \text{ simple zero } \\
x =  -4   \text{ simple zero}   \\
x  =  6      \text{ simple zero} 
\end{array}
$$

 if k  is an odd number then the x = r will cross the x axis   :  
we know that since the multiplicity of x = 0  is odd then x =  0    will cross the x axis  
we know that since the multiplicity of x = -4 is odd then x = -4   will cross the x axis 
we know that since the multiplicity of x = 6 is odd then x = 6   will cross the x axis 
 if k is and even number then the x =  r will only touch the x-axis and not actually cross it : 

x   = 6  ,  x = -4  and  x  =  0  on the other hand will not be flatten  

2. Determine  the y-intercept $(0, P(0))$ 
The y-intercept of the coefficient is (0 , 0)
3. Use the leading coefficient test to determine the behavior of the polynomial at the end of the graph  
since the coefficient of the 3th term  is positive  and the exponent is odd we can concluded that the graph will decrease   without bound from the left  and increase  without bound in the right 
4.  Plot a few more points. This is left intentionally vague. The more points that you plot the better the sketch. At the least you should plot at least one at either end of the graph and at least one point between each pair of zeroes. 
$$
G(-2)   =  -2^3  - 2(-2)^2  - 24\cdot  -2   =   32  
$$
$$
G(-6)   =  -6^3  - 2(-6)^2  - 24\cdot -6    =    -144   
$$
$$
G(1)   =  1^3  - 2\cdot 1^2  - 24\cdot 1 =   -26      
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
    \fill (-3,2) circle (2pt) node[above right] {$(0,3) $};
\draw[thick, blue, domain=-1:6, smooth] plot (\x, {\x*(\x+4)*(\x-6)});

    % Draw the parabola
\end{tikzpicture}
\end{document}


```





Example 1 : 
1. Determine all the zeroes of the polynomial and their multiplicity . Use the fact above to determine the x-intercept that correspond  to each zero will cross the x-axis or just touch it or if the x intercept will flatten out or not 
Sketch the graphs of  $G(x)   =  -x^3  + 3x   - 2 = (x  -1)(-x^2 -x  )$
we found out the zero point and the multiplicity of the equation in the previous example so we will just write them out again 
$$
 \begin{array}{l}  \\
x =  0   \text{ simple zero } \\
x =  -4   \text{ simple zero}   \\
x  =  6      \text{ simple zero} 
\end{array}
$$

 if k  is an odd number then the x = r will cross the x axis   :  
we know that since the multiplicity of x = 0  is odd then x =  0    will cross the x axis  
we know that since the multiplicity of x = -4 is odd then x = -4   will cross the x axis 
we know that since the multiplicity of x = 6 is odd then x = 6   will cross the x axis 
 if k is and even number then the x =  r will only touch the x-axis and not actually cross it : 

x   = 6  ,  x = -4  and  x  =  0  on the other hand will not be flatten  

2. Determine  the y-intercept $(0, P(0))$ 
The y-intercept of the coefficient is (0 , 0)
3. Use the leading coefficient test to determine the behavior of the polynomial at the end of the graph  
since the coefficient of the 3th term  is positive  and the exponent is odd we can concluded that the graph will decrease   without bound from the left  and increase  without bound in the right 
4.  Plot a few more points. This is left intentionally vague. The more points that you plot the better the sketch. At the least you should plot at least one at either end of the graph and at least one point between each pair of zeroes. 
$$
G(-2)   =  -2^3  - 2(-2)^2  - 24\cdot  -2   =   32  
$$
$$
G(-6)   =  -6^3  - 2(-6)^2  - 24\cdot -6    =    -144   
$$
$$
G(1)   =  1^3  - 2\cdot 1^2  - 24\cdot 1 =   -26      
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
    \fill (-3,2) circle (2pt) node[above right] {$(0,3) $};
\draw[thick, blue, domain=-1:6, smooth] plot (\x, {\x*(\x+4)*(\x-6)});

    % Draw the parabola
\end{tikzpicture}
\end{document}


```


$$
$$