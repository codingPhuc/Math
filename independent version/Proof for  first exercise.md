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
have f  :$R\xrightarrow{\text{} }R$ but different from g(x) even if both g(x) and f(x) has  $X\in R$ and both equal to g(x), f(x) = $x^2+x-1$
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
let $X\subset R$, a real valued function X where $\forall x\in X$ and  $f,g:X\xrightarrow{\text{}}R$ 
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
however  this does not  mean that they are the same as Tao explain $f(x)=x^2$ is the same output  as of f(x) = 2x where $\forall x \in X$  for some x  but they are not the same function, and  f, g $X\xrightarrow{\text{}}R$ they are not the same composition  


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


$$
\left\{ \forall x \in  X : f(x )  = g(x) \cap \not \exists \in X : f(x)  \neq g(x)   \right\} 
$$






1.  is this the proof for the fractional exponent function ? 
2. Why is b positive ? fractional exponent q can be negative ? 
3. why does b need to be positive when q $\in \left\{ 0 , + , -  \right\}$ 
4. the last sentence just mean that there is one unify way of writing a fractional number  
5. what is it trying to do like why go though all this trouble  Definition 5.6.4 as the supremum of the set . Lemma 5.6.5  to  make sure that n >= 1  
6. **supremum (least upper bound)**  what is it about ? 
7. 

Definition 5.6.7 introduces **exponentiation for a positive real number $x$ raised to a rational exponent $q$**.

Here's a breakdown of the definition:
q  
a  is a all real number 
b is a all real number 
x > 
- **Positive Real Number ($x$):** The base of the exponentiation, denoted by $x$, must be a **positive real number** ($x > 0$). The process of constructing real numbers from rational numbers is detailed in Chapter 5, where real numbers are defined as formal limits of Cauchy sequences of rational numbers. Positive real numbers are also defined based on their Cauchy sequences being "positively bounded away from zero". 
	- detailed in Chapter 5, where real numbers are defined as formal limits of Cauchy sequences of rational numbers. Positive real numbers are also defined based on their Cauchy sequences being "positively bounded away from zero". 
		- what is a Cauchy sequences ? 
		-  Positive real numbers are also defined based on their Cauchy sequences being "positively bounded away from zero" what does this mean ? 
- **Rational Number ($q$):** The exponent, denoted by $q$, must be a **rational number**. Rational numbers are expressions of the form $a//b$ (or $a/b$), where $a$ and $b$ are integers and $b$ is non-zero.
	- why is rational number express this way ? 
- **Representing $q$ as $a/b$:** To define $x^q$, the rational exponent $q$ is first written as a fraction $a/b$, where $a$ is an integer and $b$ is a positive integer. The sources explain that every rational number $q$ can indeed be expressed in this form, regardless of whether $q$ is positive, negative, or zero.
- **The Formula ($x^q := (x^{1/b})^a$):** Once $q$ is written as $a/b$, $x^q$ is defined as **the $b$-th root of $x$, raised to the power of $a$**.
    - **$x^{1/b}$ (the $b$-th root of $x$):** This term refers to the $b$-th root of $x$, which is formally defined in Definition 5.6.4 as the supremum of the set ${y \in \mathbb{R} : y \geq 0 \text{ and } y^b \leq x}$. Lemma 5.6.5 confirms the existence of such $n$-th roots for non-negative real numbers.
    - **Meaning of "Root"**: The concept of an "$n$-th root" inherently implies that $n$ is a positive integer. We don't typically talk about a "0-th root" or a "$-2$-nd root" in this context; such notions would require different definitions or lead to mathematical inconsistencies (e.g., $y^0 = 1$ for $y \neq 0$, making $x^{1/0}$ problematic).
    - write out the definition of Definition 5.6.4  
    -  write out the definition of  Lemma 5.6.5   
	- [[supremum]]
    - **$(...)^a$ (raised to an integer power):** This involves exponentiation by an integer $a$. Definition 5.6.1 covers exponentiation by natural numbers ($x^0 = 1$, $x^{n+1} = x^n \times x$), and Definition 5.6.2 extends this to negative integers ($x^{-n} = 1/x^n$ for non-zero $x$).

**Well-Definedness and Consistency:**

- **Uniqueness of Representation:** A crucial point is that a rational number $q$ can be written as $a/b$ in multiple ways (e.g., $1/2 = 2/4 = 3/6$). Lemma 5.6.8 is dedicated to proving that **different expressions $a/b$ for the same rational $q$ will yield the same value for $x^q$**, thus ensuring that the definition is well-defined. 
	- used **well-defined**. This proof is provided in **Lemma 5.6.8**,  
	- This sentence actually means the **opposite**: it highlights that there is _not_ just one unique way to write a rational number $q$ as $a/b$
- **Consistency with Previous Definitions:** This new definition is noted to be **consistent with the earlier definitions of $x^{1/n}$ (nth root) and $x^n$ (integer exponentiation)**, meaning that if $q$ happens to be an integer or a simple reciprocal of an integer, the result from Definition 5.6.7 matches those earlier definitions.

This definition allows for positive real numbers to be raised to any rational power, building upon the foundational concepts of real numbers, rational numbers, integer exponentiation, and nth roots established earlier in the text. The theory of real exponentiation for exponents that are also real numbers (not just rational) is deferred to Section 6.7. 






raise x to a rational q 
b as the b  root a  power 
define what it is  then say what it is 
a beef  p