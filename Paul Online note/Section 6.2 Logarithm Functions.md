---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: "2025-05-05"
amount of time: 
learning score:
---
In this section we are going to move on to logarithm functions . This can be a tricky function to graph right  away  


if  b is any number  $b>0$ and  $b\neq 0$  and $x>0$ then 
$$
y = \log_{b}x  \text{ is equivalent to } b^y  = x  
$$
we read this as "log bases b of x"  
In this definition  $y=\log_{b}x$ is called the logarithm  form and  $b^y = x$ is called the exponential form 

Note that the requirement  $x>0$ is really the result of the fact that we also require $b>0$ . This is due to the fact that raising a negative bases to a non integer exponent like ($(-x)^{1/2}$) will result in a complex number  . Therefore , there will be a restriction put in place to make sure that the number stay in $\in R$ 




#note
	The log part is just to notify that we are dealing with a logarithm . They are not number and they are not signifying multiplication  
	The B in the $y=\log_{b}x$ equation  above does not mean that it $\log(b^x)$ but instead b is the base that is exponent by  some number y  to get x 

$$
\log_{4}16   = 2  
$$
$$
\log_{2}16  =  4
$$

$$
\log_{6}216  =  6^3  
$$

$$
\log_{5}{\frac{1}{125}}  =  -3
$$

$$
\log_{\frac{1}{3}}81 = -4  
$$
$$
\log_{\frac{3}{2}}{\frac{27}{8}}   =  3  
$$

With these logarithm in mind , there is also different type of logarithm  that occur in a regular basic . Here are the definition using these two logarithms  . 

$$
\begin{array}{l}
\text{ common  logarithm } \log_{x} = \log_{10}  x  \\
\text{ natural logarithm } \ln_{x}  = \log_{e}x \\
\end{array}
$$

so the common logarithm  is simply log base 10 with remove the 10 notation from the log . Similarly ,  natural logarithm is  e which we saw in the pervious section [[6.2 Factoring Polynomials (a  =1)]]

$$
\log{1000} = 3
$$
$$
\log {\frac{1}{100}} = -2
$$
$$
\ln {\frac{1}{e}}  = -1
$$
$$
\ln {\sqrt{ e }}   = \frac{1}{2}
$$
$$ 
\log_{34}{34}  = 1 
$$
#fail 
$$
\log_{8}{1}  =   0 
$$




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
       \draw[thick, blue, domain=0.25:6] plot (\x, {log10(\x)});
   \draw[thick, red, domain=0.25:6] plot (\x, {ln(\x)});


\end{tikzpicture}
\end{document}

```


##  Properties of Logarithms 

1. $\log_{b}1 = 0$  . This is follow from the fact that $b^0=1$ 
2. $\log_{b}b=1$ this follow the fact that $b^1 = b$ 
3. $\log_{b}b^x=x$ this can be generalized out to $\log_{b}b^{f(x)}=f(x)$
4. $b^{\log_{b}x} =x$ this can be generalized out to $b^{\log_{b}f(x)}=f(x)$


the  properties  3 and 4  leads to a nice  relationship between  the logarithm and exponent function . Let first computer the following [[Section 3.6  Combining Functions]] 

$$
\begin{array}{l} \\
(f\circ  ) (x)  = f[g(x)]   = f(\log_{b}x)  = b^{\log_{b}x} =  x  \\
(g\circ f) ( x) =  g[f(x) ]  = g[b^x]   = \log_{b}b^x   =  x 
\end{array}
$$


recall from the [[Section 3.7  Inverse Functions]]   this mean that the exponent and logarithm are inverses of each other . 
$$
\begin{array}
\ln e^{f(X)} =  f(x)  \;  \log 10^{f(X)}  = f(x)     \\
e^{\ln f(x)  } =  f(X)  \;  10^{\log f(x)}   = f(x )
\end{array}
$$


Now let take  look at manipulate properties of the algorithm 


## more properties  of logarithms 
$$
\begin{array}{l}

\log_{b}  (xy )  =  \log_{b}x  +  \log_{b} y     \\
\log_{b}\left( \frac{x}{y} \right)   = \log_{b} x  - \log_{b}y  \\
\log_{b}(x^r)
\end{array}


$$
