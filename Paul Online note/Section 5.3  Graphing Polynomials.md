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
4.  if a<  0  and n is an odd number then the graph of n will  increase without 