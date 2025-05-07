---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-05-05
amount of time: 1h30 +
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
\log_{b}(x^r)  = r\log_{b}x   \\
\text{ if } \log_{b}x =  \log_{b}y  \text{ then } x =  y  
\end{array}
$$

We won't be doing anything with the final property  ,  it is only here for the sake of completeness  . We will be looking at the detail for property  in detail a couple of section 

The first two  properties can be a little confusing at first ,  since one have a product in the parentheses and the other have a quotient  .  We just need to  be careful with these properties  and make sure to use them correctly   


$$
\begin{array}{l} \\
\log_{b} (x +  y)  \neq  \log_{b}x  +  \log_{b}y   \\
\log_{b} (x  -  y)  \neq  \log_{b}x   -  \log_{b}y 
\end{array}
$$


Now for some example  on how to used these properties  
Note that the properties given are valid both for the common and natural logarithms  

##  simplify  each of the following logarithms 


$$
\begin{array}{l} \\
\log_{4}(x^3 y^5)     \\
=  \log_{4}x^3  +  \log_{4}y^5    \\
=  3\log_{4}x     +  5\log_{4}y    \\
    
\end{array}
$$


$$
\begin{array}{l} \\
\log \left( \frac{x^9y^5}{z^3} \right)     \\
=    \log x^9y^5  - \log  z^3  \\
= \log x^9  +  \log y^5        - \log z^3    \\
  =  9\log x  +  5\log y        - 3\log z  \\ 
\end{array}
$$



$$
\begin{array}{l} \\
\ln \sqrt{ xy }    \\
=  \frac{1}{2}\ln xy      \\
=  \frac{1}{2}\ln x    +  \frac{1}{2}\ln y      \\
\end{array}
$$



$$
\begin{array}{l} \\
\log_{3}\left( \frac{(x +  y )^2}{x^2  + y^2 } \right)  \\
\log_{3}(x  +  y )^2  -  \log_{3}(x^2  +  y^2)       \\
2 \log_{3}(x  +  y )     -    \log_{3}(x^2  +  y^2)   
\end{array}
$$



## Write each of the following as a single  logarithm  with  a coefficient of 1 



$$
\begin{array}{l} \\
7\log_{12}x   +  2\log_{12}y    \\
=  \log_{12}x^7  +  \log_{12}y^2    \\
= \log_{12}(x^7 +  y^2 ) 
\end{array}
$$



$$
\begin{array}{l} \\
3\log x   -  6 \log y   \\
\log x^3  -  \log y^6   \\
\log \left( \frac{x^3}{y^6} \right)
\end{array}
$$



$$
\begin{array}{l} \\
5\ln(x+y )  -  2\ln y  - 8\ln x   \\
\ln{\frac{(x +  y)^5}{y^2}}  - 8\ln x      \\
\ln{\frac{(x +  y)^5}{y^2x^8}}
\end{array}
$$



The change bases formula  
most calculator are able to evaluate  common  logarithm  and natural logarithms . However , what can we do if the logarithm  cannot be evaluate easily  
we can archive this by changing the base formula 

$$
\log_{a}x  = \frac{\log_{b}{x}}{\log_{b}a}
$$


where we can choose bb to be anything we want it to be. In order to use this to help us evaluate logarithms this is usually the common or natural logarithm. Here is the change of base formula using both the common logarithm and the natural logarithm.  

$$
\log_{a}x  = \frac{\log_{10}{x}}{\log_{10}a}
$$
$$
\ln_{a}x  = \frac{\ln{x}}{\ln{a}}
$$

$$
\log_{5}7  = \log_{5}7   =  \frac{\ln{7}}{\ln{5}}   =  
$$

First, notice that we can’t use the same method to do this evaluation that we did in the first set of examples. This would require us to look at the following exponential form,

5?=75?=7

and that’s just not something that anyone can answer off the top of their head. If the 7 had been a 5, or a 25, or a 125, _etc_. we could do this, but it’s not. Therefore, we have to use the change of base formula.

Now, we can use either one and we’ll get the same answer. So, let’s use both and verify that. We’ll start with the common logarithm form of the change of base.

log57=log7log5=0.8450980400140.698970004336=1.20906195512log57=log⁡7log⁡5=0.8450980400140.698970004336=1.20906195512

Now, let’s try the natural logarithm form of the change of base formula.

log57=ln7ln5=1.945910149061.60943791243=1.20906195512log57=ln⁡7ln⁡5=1.945910149061.60943791243=1.20906195512

So, we got the same answer despite the fact that the fractions involved different answers.




#  #Practice_Exercise   


## Write the expression in logarithmic form  

$$
7^5    =  16807      ;  \log_{5} 16807 =  7
$$
$$
16^{3/4}    =  8  ;  \log_{\frac{3}{4}} = 8  
$$

$$
\left( \frac{1}{3} \right) ^{-2}  =  9   ;  \log_{-2}9 =  \frac{1}{3}
$$

## Write the expression in exponential form  

$$
\log_{2}32    = 5  ;  2^5   = 32 
$$

$$
\log_{\frac{1}{5}} \frac{1}{625}  =  4      ;   \left( \frac{1}{5} \right)^4   =  \frac{1}{625}
$$

$$
\log_{9} \frac{1}{81}  =   -2   ;   9^{-2}  =  \frac{1}{81}
$$

## determine the exact value of each of the following without using a calculator 
$$
\log_{3}  81  =  4    ;  
$$

$$
\log_{5}  125  =  3     
$$
$$
\log_{2} \frac{1}{8}   =  -3
$$
$$
\log_{\frac{1}{4} }  16  =  -2
$$

$$
 \ln e^4  =  4
$$

$$
\log \frac{1}{100}  =  -2
$$

## write each of the following in terms of simpler logarithms 
$$
\begin{array}{l} \\
\log(3x^4  y^{-7})  \\
 =  \log 3x^4  +  \log y^{-7}   \\
  = 4\log 3x   -7\log y   \\
  =  4\log 3+    \log{x}   -7\log y 
\end{array}
$$ 


$$
\ln(x\sqrt{ y^2  +  z^2 })  =  \ln(x)  + \frac{1}{2}\ln  y^2  +  z^2
$$


$$
\begin{array}{l} \\
\log_{4} \frac{x-4}{y^2  \sqrt[5]{ z }}  \\
 =  \log_{4} (x-4)  -   \log_{4} (y^2  \sqrt[5]{ z })   \\
  =\log_{4} (x-4)  -   \log_{4} y^2  -   \log_{4}  \sqrt[5]{ z }      \\
  =  \log_{4} (x-4)  -   2\log_{4} y  - \frac{1}{5}  \log_{4} { z } 
\end{array}
$$ 
## combine each of the following into a single logarithm with a coefficient of one. 

$$
\begin{array}{l} \\
2 \log_{4}{x}  + 5\log_{4}{y}   -  \frac{1}{2}\log_{4}z \\
\log_{4}{x^2}   +  \log_{4}{y^5}   -   \log_{4}\sqrt{ z }  \\
\log_{4}{\frac{x^2y^5}{\sqrt{ z }}} 
\end{array}
$$



$$
\begin{array}{l} \\
3\ln(t +  5)  -  4 \ln t - 2\ln(s -1 )   \\
\ln(t +  5)^3  -   \ln t^4 - \ln(s -1 )^2  \\
 \ln \frac{(t +  5)^3}{t^4}    - \ln(s -1 )^2    \\
\ln \frac{(t +  5)^3}{t^4 (s -1  )^2}   
\end{array}
$$


$$
\begin{array}{l} \\
\frac{1}{3} \log a  -  6\log b  + 2   \\
 \log a^{1/3}  -  \log b^6  + \log 100   \\
 \log \frac{a^{1/3}\cdot 100}{b^6}  \\

\end{array}
$$

## use the change of base formula and a calculator to find the value of each of the following. 

$$
\log_{12}35   =  \frac{\log{35}}{\log{12}}   = \frac{3.55534806}{2.48490665}   = 1.43077731 
$$


$$
\log_{\frac{2}{3}}53  =  \frac{\log{53}}{\log{\frac{2}{3}}}   = \frac{1.72427587}{−0.17609126}   =−9.79194469
$$


##  sketch each of the given functions. 




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

#word_meaning  
	[quotient](https://www.cuemath.com/numbers/quotient/) 
	() : parentheses 
	[]: Square brackets 


