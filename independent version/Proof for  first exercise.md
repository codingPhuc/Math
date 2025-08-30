---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/CalcI/CalcI.aspx
tags:
  - In_Progress
learning method: RAP (Read – Answer – Practice)
Current date: 2025-08-24
amount of time:
learning score:
---
**Strictly speaking, there is a distinction between a function f , and its value f(x) at a point x. f is a function; but f(x) is a number (which depends on some free variable x). This distinction is rather subtle and we will not stress it too much, but there are times when one has to distinguish between the two. For instance, if f : R → R is the function f(x) := x2, and g := f |[1,2] is the restriction of f to the interval [1, 2], then f and g both perform the operation of squaring, i.e., f(x) = x2**

**and g(x) = x2, but the two functions f and g are not considered the same function, f = g, because they have different domains. Despite this distinction, we shall often be careless, and say things like “consider the function x2 + 2x + 3” when really we should be saying “consider the function f : R → R defined by f(x) := x2 + 2x+ 3”. (This distinction makes more of a difference when we start doing things like differentiation.** **pages 218-219** 

Tao define  a f(x) to be different  from g(x) as they have different domains 
e.g 
define  f(x) where x $\in$ R :  
f is R $\xrightarrow{\text{}}$ R  but different from g(x) even if both g(x) and f(x) has X $\in$  R and both equal to g(x), $f(x) =x^2 +x -1$
have f  =$R\xrightarrow{\text{} }R$ but different from g(x) even if both g(x) and f(x) has  $X\in R$ and both equal to g(x), f(x) = $x^2+x-1$
have f = $R\xrightarrow{\text{}}R$, f(x) where x $\in$ R, $f(x)=x^2 + x -1$
and g  = $R\xrightarrow{\text{}}R$, g(x) where  $x\in R$, $g(x) =x^2+ x-1$ 
$g(x)\neq f(x)$ because of x of either function g(x) and f(x) have 
$\left\{ x : x \in R f(x) > 0 V g( x) >3 \right\}$ because of this they show they have different domains 



### Definition 9.2.1 — Arithmetic operations on functions  

Given two functions **f : X → ℝ** and **g : X → ℝ**, we define:  

- **Sum:**  
  $$
  (f + g)(x) = f(x) + g(x)
  $$  

- **Difference:**  
  $$
  (f - g)(x) = f(x) - g(x)
  $$  

- **Maximum:**  
  $$
  \max(f, g)(x) = \max(f(x), g(x))
  $$  

- **Minimum:**  
  $$
  \min(f, g)(x) = \min(f(x), g(x))
  $$  

- **Product:**  
  $$
  (fg)(x) = f(x)g(x)
  $$  
  (also written as $f \cdot g$)  

- **Quotient (when $g(x) \neq 0$ for all $x \in X$):**  
  $$
  \left(\frac{f}{g}\right)(x) = \frac{f(x)}{g(x)}
  $$  

- **Scalar multiplication (where $c \in \mathbb{R}$):**  
  $$
  (cf)(x) = c \cdot f(x)
  $$  



Tao uses  this basic point wise operation ton functions : i.e defining  what you do to f, g you do to their values x.
setup : 
let $X\subset R$, a real valued function X where $\forall x\in X$ and  $f,g,X\xrightarrow{\text{}}R$ 
$$
\begin{array}{l} \\
\text{ sum }  (f +g)X  =  f(x) + g(x)  \\
\text{ different}  (f - g ) (x)  = f(x)  - g(x)  \\
\text{ product} (f\cdot g)(x)   =  f(x) g(x)   \\
\text{ quitionent if } g(x) \neq 0 \forall x \in X , \left( \frac{f}{g} \right)(x)   = \frac{f(x)}{g(x)}  
\end{array}
$$
define $\subset$ as the constant where $C \in R$ scalar multiply $(c \cdot f)(x)  =cf(x)$ 
extremas : 
max (f,g)(x)   =  $max\left\{ f( x) , g(x) \right\}$  , 
min (f,g)(x)   =  $min\left\{ f( x) , g(x) \right\}$  , 
however  this does not  mean that they are the same as Tao explain $f(x)=x^2$ is the same output of f(x) = 2x where $\forall x \in X$ and  f, g $X\xrightarrow{\text{}}R$ they are not the same composition  


### Example 3.3.8  

- The functions  
  $$
  x \mapsto x^2 + 2x + 1
  $$  
  and  
  $$
  x \mapsto (x+1)^2
  $$  
  are equal on the domain $\mathbb{R}$.  

- The functions  
  $$
  x \mapsto x
  $$  
  and  
  $$
  x \mapsto |x|
  $$  
  are equal on the **positive real axis**, but are not equal on $\mathbb{R}$.  

Thus, the concept of **equality of functions** can depend on the choice of domain.  



two functions define as $f,g : X \xrightarrow{\text{}}Y$ are equal on domain $D\in R$  if $\forall x \in X,\forall y \in Y$ therefore $f(x)=g(x)$ as  both  $\forall x \text{ and } \forall y$ are equal to $X,Y\in R$ , and  $\forall x,\forall y\subset R$ 

define: 
$f:R\xrightarrow{\text{}} R: f(x)=x^2+2x-1$
and 
$g:R\xrightarrow{\text{}}R:g(x)=(x+ 1)^2$ 
therefore 
$f(x)=f(x)on R:D\in R$
however  iit depend on the domain that $f:R\xrightarrow{\text{ }}R$ , $f(x)=x$ and $g: R\xrightarrow{\text{}}R$ , $g(x)=\mid x \text{ are equal} \mid$  
our positive axis $[0,\infty]$ and where R >0  
because 
$$
\mid x \mid  =  \left\{ \begin{array}{l}x  \implies  x>0 \\
-x  \implies x  < 0 
\end{array} \right.
 
$$
therefore if R<0 is ture then f(x) != g(x)  but if R>0 then  f(x)  = g(x )  is true 



### Definition 3.3.7 — Equality of functions  

Two functions  
$$
f : X \to Y, \quad g : X \to Y
$$  
with the same domain and range are said to be **equal**, written as $f = g$, if and only if  
$$
f(x) = g(x) \quad \text{for all } x \in X.
$$  

(If $f(x)$ and $g(x)$ agree for some values of $x$, but not others, then we do **not** consider $f$ and $g$ to be equal.)  


# what is a codomain 

# what is equality definition ? 

# 