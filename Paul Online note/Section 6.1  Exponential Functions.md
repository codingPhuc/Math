---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: "2025-05-01"
amount of time: 
learning score:
---
this chapter start of with the definition of a exponential functions 

if b is any number such that $b>0$ and $b\neq 1$ then exponential function is a function in the form , 
$$
f(x)  = b^x 
$$
where b is called the base and x can be any real number 
Notice that the x is now in the exponent and the base is a fixed number. This is the opposite from what we have seen in this point .To  this point the base is a variable x and the exponent is a fix number. However despite the different these function evaluate in the same way those that we are used to . 

There is some constrains that we need to mention , we need to avoid the constant b being 0 or 1  

$$
f(x)  =   0^x  =  0  \text{ and } f(x)  = 1^x  = 1  
$$
Due to this these are called exponent function and do not have the properties that normal exponents function have 
The next constraint is prohibiting function that have a negative value in the base,  due to the chances of receiving a complex number .For example, if the value is $b=-2$ it will be  
$$
f(x)  = ( -4)^x \implies f\left( \frac{1}{2} \right) = (-4)^{1/2 } = \sqrt{  -4 }
$$
we only want real number to arrive in exponent function 
Example 1 : Sketch the graph of $f(x) = 2^x$ and $g(x) =\left( \frac{1}{2} \right)^x$ on the same axis system 


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw axes
    \draw[->] (-7,0) -- (7,0) node[right] {$x$};
    \draw[->] (0,-7) -- (0,7) node[above] {$y$};

    % Tick marks and labels
    \foreach \x in {-6,-5,...,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    \foreach \y in {-6,-5,...,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[left] {\y};
    }

    % Parameters
    % Center: (h, k) = (0, 0)
    % a = 2, b = 3 → y = ±(3/2)*sqrt(x^2 - 4)
    % Horizontal hyperbola
 

    % Right branch
       \draw[dashed, red, domain=-3:3] plot (\x, {2^(\x) });
        \draw[dashed, red, domain=-3:3] plot (\x, {(1/2)^(\x) });

    % Asymptotes: y = ±(3/2)x
    % Center
    \filldraw[black] (0, 0) circle (2pt) node[below left] {$(0, 0)$};

\end{tikzpicture}
\end{document}

```


note that we can written $g(x)$ in the following way : 

 $$
g(x) = \left( \frac{1}{2} \right)^x  =  \frac{1}{2^x} = 2^{-x}
	$$1. The graph of f(x) will always contain the point $(0,1)$ . Or put another way ,$f(0)=1$ regardless of the value of b 
2. for every possible b we have $b^x >0$  . note that this imply that $b^x \neq 0$ 
3. if $0<b <1$ then the graph of $b^x$ will decrease as we move from left to right . Check out the graph of $\left( \frac{1}{2} \right)^x$ above for verification of this property 
4. if $b>1$ then the graph of $b^x$ will increase as we move from left to right . Check out the graph of $2^x$ above for verification 
5. if $b^x=b^y$ then  $x =y$
all of these properties except for the final function can be verify by the graph we just draw 
As the final topic we need to discuss a special exponent .

$$
f(x) = e^x 
$$
where $e =2.718281828$ note the different  between $f(x) =b^x\text{ and }f(x)=e^x$ . Given the above  b is any number that are given the restriction  above while e is a very specific number 

this special exponent is very important and arises naturally in many cases 
let get a quick graph of this function 
sketch the graph of $f(X)=e^x$ 


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw axes
    \draw[->] (-7,0) -- (7,0) node[right] {$x$};
    \draw[->] (0,-7) -- (0,7) node[above] {$y$};

    % Tick marks and labels
    \foreach \x in {-6,-5,...,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    \foreach \y in {-6,-5,...,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[left] {\y};
    }

    % Parameters
    % Center: (h, k) = (0, 0)
    % a = 2, b = 3 → y = ±(3/2)*sqrt(x^2 - 4)
    % Horizontal hyperbola
    % Right branch
        \draw[thick, red, domain=-3:2] plot (\x, {(2.718281828)^(\x) });

    % Asymptotes: y = ±(3/2)x
    % Center
    \filldraw[black] (0, 0) circle (2pt) node[below left] {$(0, 0)$};

\end{tikzpicture}
\end{document}

```

notice the graph increase since $e=2.718281828>1$

sketch the graph of $g(x)=5e^{1-x} -4$


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw axes
    \draw[->] (-7,0) -- (7,0) node[right] {$x$};
    \draw[->] (0,-7) -- (0,7) node[above] {$y$};

    % Tick marks and labels
    \foreach \x in {-6,-5,...,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    \foreach \y in {-6,-5,...,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[left] {\y};
    }

    % Parameters
    % Center: (h, k) = (0, 0)
    % a = 2, b = 3 → y = ±(3/2)*sqrt(x^2 - 4)
    % Horizontal hyperbola
    % Right branch
        \draw[thick, red, domain=-1:2] plot (\x, {5*(2.718281828)^(1-\x)  - 4 });

    % Asymptotes: y = ±(3/2)x
    % Center
    \filldraw[black] (0, 0) circle (2pt) node[below left] {$(0, 0)$};

\end{tikzpicture}
\end{document}

```
