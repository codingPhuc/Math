

#  #definition 
A **relation**  is  a set of order pairs 

This seem  like an odd definition ,  but we  need it for the definition  of a function( which is the main  topic of this section) .However, before the definition of a function  let see what a relationship actually is  
think  back to [[Section 3.1 Graphing#Practice_Exercise]] . In the  example we constructed a set of order  pairs to sketch the  graph of $y =(x - 1)^2 - 4$ 
$$
(−2,5)(−1,0)(0,−3)(1,−4)(2,−3)(3,0)(4,5) 
$$ here are the relation  that will form from the set of order pairs 

$$
\begin{aligned}&\{(-2,5)\quad(-1,0)\quad(2,-3)\}\\&\{(-1,0)\quad(0,-3)\quad(2,-3)\quad(3,0)\quad(4,5)\}\\&\{(3,0)\quad(4,5)\}\\&\{(-2,5)\quad(-1,0)\quad(0,-3)\quad(1,-4)\quad(2,-3)\quad(3,0)\quad(4,5)\}\end{aligned}
$$

There are of course many  relation  we could form from the list of order pairs  above , we just want to list a few possible relations to give some example .Note as well that we could get  any order pairs  from the relation and add those into the equation as well 

Why do  we need to used  relation ?  Because some relation  are special and are used in all level of math 

## Definition of a function 
A **function**  is a value , in which each value  from the  first  set of the order pairs is  associated with   exactly one value from the set of second components of the ordered pairs 
example 1  the  following relation is  function 
$$
\{(−1,0)(0,−3)(2,−3)(3,0)(4,5)\}
$$ from the list of  order pairs above we have the following set of first component (the first number of the order pairs) and second component( the second value in the order pairs) 
$$
\text{1st component } : \{-1,0 , 2 ,3, 4\} \; \text{2nd component } : \{0,−3,0,5\} 
$$
notice how the second component have only 1 -3 in  two ordered pairs but we only listed one 
To  see why this is  a relation ,  select a  value from the first component , then plug the value in the order pairs  and list out all  it second components  . The list of  second  component will consist  of  exactly one value 

For example , let look at 2  in the first component . Find a pairs  in the relation that have 2 as the first component , then plug 2 in  . You will see that we will get -3  in the second components 

Note that -3 occur 2 time in the relation, that is perfectly fine  since 3 is a values in the second component . We only need there to be unique  value of the 1 components 

we look  only at one value from the first example . But , it will be the same regardless of other choices 

Example 2  The following relation is  not a function 
$$
\{(6,10)(−7,3)(0,4)(6,−4)\}
$$
Here is the list of second and first components  : 
$$
\text{1st component } : \{6,0,-7\} \; \text{2nd component } : \{10 ,  3 , 4 ,-4 \} 
$$
from the first component let's choose 6.  Now , when  plugging  6 into the relation we will see that 6  have 2 orders pairs (6,10) (6.-4) . The list of second component  associated with 6 is then : 10 , -4  resulting in this being an invalid function since there is 2 second components associated with 6 

even thought there are values like -7 and 0  that have a single pairs does not matter. The function will be invalid if there is  even 1 first component with more then 2 second component associated with it 

##  another definition of a function  
Now let give a working definition of a function to what we are working with. However with the four relations we gave prior to the definition of a function and the relation we used in example 1 we often get the relation from some equation 

it is important to  note that not all relations come form equations .  The relations from the second equation for example was just an order pairs that we wrote down ,  didn't come from any equation . This can also be true for relation that are functions   

However the function that we are using will all come from equation  , they are call the "working" definition of a function . Remember the term working meaning this is a specific type of function we are working with not the general definition like above

## "working definition" of a function 
A **function** , in which  values of x that can be plugged in to get a single value of y  out of the equation 

Before we move on , let examine the parse "that can be plugged into"  . This is  in fact correct since there are values of x that collide  with the constraint of an equation . For example , you cannot divided  by 0 and  you must not square the root of negative number  if you want to get a real number. 

for  the example going forward , we will not deal  with complex number and always going to assume that x and y are real number 
## Determine which of the following are functions and which are not functions 

$$
\begin{array}{l}
x   = -4  , y = 5x + 1  \implies y = 5 \cdot -4  + 1   =  -19  \\
x   = 0 , y = 5x + 1  \implies y = 5 \cdot 0  + 1   = 1   \\
x   = 1 , y = 5x + 1  \implies y = 5 \cdot 1  + 1   = 6 \\
 
\end{array}
$$
bases on the equation  , and number we plug in . We concluded that this is an equation since : 
1. when we plug in one value the value will be multiply by 5 and add by 1 
2. since the output of the equation will always be 1 value is satisfy the constrains of  a function that a plug in values x can yield a values y  
this is a function since you can  plug in  values of x to  get a value of  y 



$$
\begin{array}{l}
x   = -2  , y = x^2  + 1   \implies y =  (-2)^2  +  1    =  5  \\
x   = 0   , y = x^2  + 1   \implies y =  0^2  +1    =   1   \\
x   = 2   , y = x^2  + 1   \implies y =  2^2   + 1   =  5 \\
 
\end{array}
$$
bases on the equation  , and number we plug in . We concluded that this is an equation since : 
1. when we plug in one  x value will be raise to the  power of 2  and added by 1 
2. since the output of the equation will always be 1 value is satisfy the constrains of  a function that a plug in values x can yield a values y  
this is a function since you can  plug in  values of x to  get a value of  y ,  


$$
\begin{array}{l}
x   = -2  , y^2   =  x+ 1  \implies  y = \sqrt{ x+ 1 }   \implies y = \sqrt{ -2 + 1 } = \sqrt{ -1  }  \\
x   = 0   ,  y^2   =  x+ 1  \implies y   = \sqrt{ x+ 1 }     \implies  y = \sqrt{ 0+ 1 }   \\
x   = 2   ,  y^2   =  x+ 1  \implies  y  =  \sqrt{ x+ 1 }    \implies  y = \sqrt{ 2 + 1 } = \pm  \sqrt{ 3 } \\
 
\end{array}
$$ we concluded bases on this equation that  this is not a function since when plug in the value   -2 , it create a square root properties and there are no complex number  that are outputted from a function 
additionally  , there should not be two solution for y since that mean that there is a  value of x that can produce values of y contradicting the constraints of what make a function 



$$
\begin{array}{l}
x   = -2  , x^2 +   y^2   = 4  \\
  y^2   = 4  -   x^2  \\
 y =  \sqrt{ 4  -   (x)^2  }   \\
\implies  y =  \sqrt{ 4  -   (3)^2  }   =\sqrt{ -5 }   \\
x   = 0 , x^2 +   y^2   = 4  \\
  y^2   = 4  -   x^2  \\
 y =  \sqrt{ 4  -   x^2  }   \\
\implies y =  \sqrt{ 4  -   (0)^2  }     = \pm 4  \\
x   = 2  , x^2 +   y^2   = 4  \\
  y^2   = 4  -   x^2  \\
 y =  \sqrt{ 4  -   x^2  }   \\
\implies y =  \sqrt{ 4  -   (2)^2  }      = 0 \\
 
\end{array}
$$ we concluded bases on this equation that  this is not a function since when plug in the value   9, it create a square root properties and there are no complex number  that are outputted from a function 
additionally  , there should not be two solution for y since that mean that there is a  value of x that can produce values of y contradicting the constraints of what make a function 


We now need to move on to something call the **function  notation** .  Function notation will be use though out most of the equation in this chapter 
let start of  with the following quadratic equation : 
$$
 y   = x^2   - 5x  + 3  
$$

we can used the process similar to what we used in the pervious example to convince our self that this is a function . Since this is a function we denote it as the following 

$$
 f(x) =  x^2  - 5x  +  3 
$$
the notion of $f(x)$ is not  important since we can easily denote it as $g(x) \text{ or } h(x)$
the letter for the function name does not matter since the only thing we need is the $(x)$ part  , the letter in the parenthesis must match the variable used on the right side of the equation 
thing of $f(x)$ as  nothing more than a fancier way of writing  y  
- keep in mind that f by x  is not  a multiplication of  f by x , this is one of the error when people deal with function .  
- Next we need to talk about **evaluating functions** . Evaluating a function is nothing more than asking  what it values  is for a specific value of $x$ . An  example of this , is asking what the y for a value of x

##  Evaluating function 
evaluating is really simple . Let take a function we look at above  
$$
f(x) =  x^2  -5x + 3 
$$
and ask what its value  is for x = 4 . In term of function  notation we will "ask" this using the notation f(4) . So when there is sometime other than the variable inside the parenthesis we are asking what the return value of the function is for that particular input  . Here  is an  example of $f(4)$ 

$$
f(x) =  x^2  -5x + 3  \implies  f(4) =  4^2  -5\cdot 4 + 3 = -1   
$$
notice that the evaluate a function is done the same way in which we evaluate equations .  The additional step we need to do is plug in value for the x inside the parentheses 
$$
f(x) =  x^2  -5x + 3  \implies  f(-6) =  (-6)^2  -5\cdot -6  + 3 =  69 
$$

given 
$$
f(x )  = x^2  - 2x +  8 \cap g(x)  = \sqrt{ x +  6  }
$$
evaluate  each of the following : 
a) $f(3)$ and  $g(3 )$ 
$$
\begin{array}{l}
f(x )  = x^2  - 2x +  8   \\
f(3)  = 3^2  - 2 \cdot 3  +  8   \\
 f(3)  =   11 \\
\end{array}
$$


$$
\begin{array}{l}
g(x )  =  \sqrt{ x +  6  }   \\
g(3)  =  \sqrt{ 3 +  6  } \\
 g(3)  =  3 \\
\end{array}
$$



b)  $f(-10)$ and  $g(-10 )$    

$$
\begin{array}{l}
f(x )  = x^2  - 2x +  8   \\
f(3)  = (-10)^2  - 2 \cdot -10   +  8   \\
 f(3)  =   128 \\
\end{array}
$$



$$
\begin{array}{l}
g(x )  =  \sqrt{ x  +  6  }   \\
g(3)  =  \sqrt{  -4 } \\
\end{array}
$$
since  we only get real number with this we cannot  plug in 10  into the equation 



c ) $f(0)$  

$$
\begin{array}{l}
f(x )  = x^2  - 2x +  8   \\
f(0) = (0)^2  - 2 \cdot 0   +  8   \\
 f(3)  =  8
\end{array}
$$

d)  $f(t)$ 

$$
\begin{array}{l}
f(x )  = x^2  - 2x +  8   \\
f(t) = (t)^2  - 2 \cdot t   +  8   \\
\end{array}
$$
e )  $f(t +  1 ) and  f(x + 1 )$
$$
\begin{array}{l}
f(x )  = x^2  - 2x +  8   \\
f(t +  1) = (t +  1)^2  - 2  \cdot (t +  1) +  8  \\
f(t +  1) = t^2 + 2t + 1  -  2t   - 2   + 8   \\
f(t +  1) = t^2 + 7   \\
\end{array}
$$


$$
\begin{array}{l}
g(x )  =  \sqrt{ x +  6  }   \\
g(t +  1)  =  \sqrt{ t   + 7 } \\
\end{array}
$$

f)  $f(x^3)$ 
$$
\begin{array}{l}
f(x)  = x^2  - 2x +  8   \\
f(x^3) =  (x^3)^2  - 2\cdot x^3 +  8   \\
f(x^3) =  x^6 - 2x^3 +  8    \\
\end{array}
$$
f)  $g(x^2 -  5)$ 
$$
\begin{array}{l}
g(x )  =  \sqrt{ x +  6  }   \\
g(x^2 -  5) = \sqrt{ x^2 -  5 +  6  }  \\
g(x^2 -  5) = \sqrt{ x^2 + 1   }    \\
\end{array}
$$

while  we are  on the topic of function  evaluation we should now talk about **piecewise function** . Recall the mathematical definition of absolute value 

$$ 
\mid x \mid = 

\left\{
\begin{array}{l}
x  \text{ if } x\geq 0   \\
x  \text{ if } x \leq 0  
\end{array}
\right.
$$
this is  a function ,  if we replace the $\mid x \mid$ $f(x)$ we will get 
$$ 
f(x)= 

\left\{
\begin{array}{l}
x  \text{ if } x\geq 0   \\
x  \text{ if } -x \leq 0  
\end{array}
\right.
$$

This is a piece wise function . Think of a piece wise function as nothing more than  function that we broken into different pieces , the piece that  function return will be base on the value of x. If x is negative then we will used the  bottom piece and vice versa for positive 


$$
\left.g\left(t\right)=\left\{\begin{array}{ll}3t^2+4&\mathrm{if~}t\leq-4\\10&\mathrm{if~}-4<t\leq15\\1-6t&\mathrm{if~}t>15\end{array}\right.\right.
$$
1. g(−6)
since the input argument  satisfy the top  part    
so 
$$
\begin{array}{l}
g(t) =   3t^2 + 4 \\
g(-6)  = 3\cdot (-6)^2  + 4   \\
 g(-6)  = 112 
\end{array}
$$
2. g(−4)
since the input argument  satisfy the top  part    
so 
$$
\begin{array}{l}
g(t) =   3t^2 + 4 \\
g(−4)  = 3\cdot (−4)^2  + 4   \\
 g(-6)  = 52 
\end{array}
$$
3. g(1)
since the input argument  satisfy the middle  part    
so 
$$
\begin{array}{l}
g(t) =   3t^2 + 4 \\
g(1)  = 10
 
\end{array}
$$
4. g(15)
since the input argument  satisfy the middle  part    
so 
$$
\begin{array}{l}
g(t) =   3t^2 + 4 \\
g(15)  =10 
\end{array}
$$
5. g(21) 
since the input argument  satisfy the bottom   part    
so 
$$
\begin{array}{l}
g(t) =  1- 6t \\
g(15)  = 1- 6 \cdot  15 \\
 g(15)  = -89
\end{array}
$$ 


As a final topic  we cannot plug every   x into every function .We have talk briefly about this in the definition of a function section and another example when we were evaluating function . 

## domain  and range 

The domain of an equation is the set of all x that is plug into the equation and get back a real number for  y . The **range** of equation is the set of y that we get out of the equation 
determine the range of an equation/function can get really  difficult to do for many function so  we are not going to do that. We are must more interested in determining the domains of functions .From definition the domain is a set x that we can plug into a function to get back a real number. At this point , that mean that we need to avoid division by 0 and taking the square root of negative number 
6 Determine the domain of each of the following functions.
$$
\begin{array}{l}
 g(x) = \frac{x+ 3}{x^2  +  3x -  10 }   \\
x^2  + 3x  - 10 \neq 0    \\
(x + 5 )( x  - 2 )\neq 0  \\
\left\{    \\
\begin{array}{l}
x  =  -5  \\
x   =  2 \\
\end{array}
 \right. 
\end{array}
$$



$$
\begin{array}{l}
f(x)  = \sqrt{  5 - 3x  }   \\
5 - 3x  \geq 0   \\
x \leq  \frac{5}{3 }  \\
\end{array}
$$


$$
\begin{array}{l}
h(x)  = \frac{\sqrt{ 7x + 8  }}{x^2 +  4}     \\
x^2   +  4 \neq  0    \\
x^2   \neq  -  4     \\ 
x  \neq \sqrt{  -4 }  
\end{array}
$$ since  the result of the denominator is  an complex number there is no x that can cause the denominator to be  0 
$$
\begin{array}{l}
7x +  8  \geq  0 \\ 
x   \geq  -\frac{8}{7}  \\
\end{array}
$$
x need to be larger than  $-\frac{8}{7}$





$$
\begin{array}{l}
h(x)  = \frac{\sqrt{ 10x  - 5  }}{x^2  - 16 }     \\
x^2  - 16  \neq  0    \\
( x +  4) (x  - 4 )\neq 0     \\ 
\left\{    \\
\begin{array}{l}
x  =  -4  \\
x   = 4  \\
\end{array}
 \right.
\end{array}
$$ so we need to avoid number that can cause x to be 0 
$$
\begin{array}{l}
10x  - 5 \geq  0 \\ 
x   \geq  \frac{1}{2} \\
\end{array}
$$
so  the domain of x is $\left( \frac{1}{2}, 4  \right) \cap \left( 4 , + \infty \right)$



# #Practice_Exercise 

## determine if the given solution is a function 
$$
\{(2,4),(3,−7),(6,10)\} 
$$


$$
\text{1st component } : \{2, 3 , 6\} \; \text{2nd component } : \{4 ,  -7 , 10\} 
$$
the  given relationship is a function since all the number in the first  component will have single value from the second component 


$$
\{(−1,8),(4,−7),(−1,6),(0,0)\}
$$


$$
\text{1st component } : \{-1,4 , -1 , 0 \} \; \text{2nd component } : \{8 , -7 , 6  ,  0 \} 
$$
the  given relationship is a not function since the number -1 have 2  values in the second component 



##   determine if the given  equation is a function 
$$
\begin{array}{l}
x   = -3 , y = 14 -  \frac{1}{3} x   \implies y = 14 -  \frac{1}{3} \cdot -3    =  15 \\
x   = 0 , y = 14 -  \frac{1}{3} x   \implies y = 14  \\
x   = 2 , y = 14 -  \frac{1}{3} x  \implies y = 14 -  \frac{1}{3} \cdot 3    = 13 \\
 
\end{array}
$$
bases on the equation  , and number we plug in . We concluded that this is an equation since : 
1. when we plug in one value the value will be multiply by $-\frac{1}{3}$ and add by 14 
2. since the output of the equation will always be 1 value is satisfy the constrains of  a function that a plug in values x can yield a values y  
this is a function since you can  plug in  values of x to  get a value of  y  



$$
\begin{array}{l}
x   = -3 , y = \sqrt{ 3x^2  + 1  }  \implies y = \sqrt{ 3(-3)^2  + 1  }    =  \sqrt{ 10  } \\
x   = 0 , y =  \sqrt{ 3x^2  + 1  }   \implies y = \sqrt{ 3(0)^2  + 1  } = \pm 1     \\

\end{array}
$$
 we concluded bases on this equation that  this is not a function since when plug in the value   0 , it create a square root properties and there are no complex number  that are outputted from a function 
additionally  , there should not be two solution for y since that mean that there is a  value of x that can produce values of y contradicting the constraints of what make a function 



$$
\begin{array}{l}
x = 0  , y^4 - x^2  = 16 \\
  y^4   =   x^2 + 16   \\
 y =  \sqrt[4]{ x^2 + 16}   \\
\implies  y =   \sqrt[4]{ 2^2 + 16}  = \pm 2  \\

\end{array}
$$
 we concluded bases on this equation that  this is not a function since when plug in the value   0 , it create a square root properties and there are no complex number  that are outputted from a function 
additionally  , there should not be two solution for y since that mean that there is a  value of x that can produce values of y contradicting the constraints of what make a function 



given $f(x)=3−2x^2$ determine each of the following. 

1. f(0) 
$$
\begin{array}{l}
f(x )  = 3−2x^2  \\
f(0)  = 3−2\cdot0^2 \\
 f(3)  =   3 \\
\end{array}
$$
2.  f(2) 

$$
\begin{array}{l}
f(x )  = 3−2x^2  \\
f(2)  = 3−2\cdot2^2 \\
 f(3)  =   -5 \\
\end{array}
$$
1.  f(−4)

$$
\begin{array}{l}
f(x )  = 3−2x^2  \\
f(-4)  = 3−2\cdot(-4)^2 \\
 f(3)  =  -29 \\
\end{array}
$$
1.  f(3t)
$$
\begin{array}{l}
f(x )  = 3−2x^2  \\
f(3t)  = 3−2\cdot(3t)^2 \\
 f(3t)  = 3   - 18t^2 \\
\end{array}
$$
2.  f(x+2) 
$$
\begin{array}{l}
f(x )  = 3−2x^2  \\
f(x+  2 )  = 3−2\cdot(x+ 2 )^2 \\
 f(3t)  = 3  - 2 (x^2  +  4x + 4 )  \\
 f(3t)  = 3  -2x^2  +   8x - 8  \\
 f(3t)  =  -2x^2  +   8x  - 5 \\
\end{array}
$$



given $g(w)  = \frac{4}{ w + 1 }$  determine each of the following. 
1. g(−6)
$$
\begin{array}{l}
g(w)  = \frac{4}{ w + 1 }\\
g(-6)  = \frac{4}{ -6  + 1 } \\
g(-6)  = \frac{4}{ -5 } \\
\end{array}
$$
2.  g(−2)
$$
\begin{array}{l}
g(w)  = \frac{4}{ w + 1 }\\
g(-2)  = \frac{4}{ -2  + 1 } \\
g(-2)  = -4 \\
\end{array}
$$

3.  g(0)
$$
\begin{array}{l}
g(w)  = \frac{4}{ w + 1 }\\
g(-2)  = \frac{4}{ 0  + 1 } \\
g(-2)  =  4 \\
\end{array}
$$
4.  g(t−1)
$$
\begin{array}{l}
g(w)  = \frac{4}{ w + 1 }\\
g(t−1)  = \frac{4}{ t−1  + 1 } \\
g(t−1)  =   \frac{4}{ t } \\
\end{array}
$$
5.  g(4w+3) 
$$
\begin{array}{l}
g(w)  = \frac{4}{ w + 1 }\\
g(4w+3)  = \frac{4}{4w+3 + 1 } \\
g(4w+3)  =   \frac{4}{ 4w +  4 } \\
\end{array}
$$


given $h(t)  =t^2  + 6$  determine each of the following.   

1. h(0)
$$
\begin{array}{l}
h(t)  =t^2  + 6\\
h(0)  =0^2  + 6\\
h(0)  =  6 \\
\end{array}
$$
2.  h(−2)
$$
\begin{array}{l}
h(t)  =t^2  + 6 \\
h(-2)  =(-2)^2  + 6 \\
h(-2)  = 10\\ 
\end{array}
$$

3.  h(2)
$$
\begin{array}{l}
h(t)  =t^2  + 6 \\
h(2)  =(2)^2  + 6 \\
h(2)  = 10\\ 
\end{array}
$$
4.  h(√x)
$$
\begin{array}{l}
h(t)  =t^2  + 6 \\
h(\sqrt{ x })  =(\sqrt{ x })^2  + 6 \\
h(\sqrt{ x })  = x  +  6\\ 
\end{array}
$$
5.  h(3−t) 

$$
\begin{array}{l}
h(t)  =t^2  + 6 \\
h(3−t)  =(3−t)^2  + 6 \\
h(3−t)  = t^2  -  6t   +  15 \\
\end{array}
$$

$$
 \mathrm{Given~}h\left(z\right)=\left\{\begin{array}{ll}3z&\mathrm{if}z<2\\1+z^2&\mathrm{if}z\geq2\end{array}\right.
$$
1. h(0)
since the input argument  satisfy the top  part     
$$
\begin{array}{l}
h(z)  =  3z   \\
h(0)  =  3\cdot  0    =0 \\

\end{array}

$$
2.  h(2) 
since the input argument  satisfy the bottom part 
$$
\begin{array}{l}
h(z)  = 1+z^2   \\
h(2)  = 1 +   2^2    = 5\\

\end{array}

$$
2.  h(7) 

since the input argument  satisfy the bottom part 
$$
\begin{array}{l}
h(z)  = 1+z^2   \\
h(7)  = 1 +   7^2    = 15\\

\end{array}

$$

$$
\mathrm{Given~}f\left(x\right)=\left\{\begin{aligned}&6&&\mathrm{if}x\geq9\\&x+9&&\mathrm{if}2<x<9\\&x^2&&\mathrm{if}x\leq2\end{aligned}\right.
$$
 determine each of the following.  

1. f(−4) 
since the input argument  satisfy the bottom part  
$$
\begin{array}{l}
f(x) = x^2    \\
f(x)  =(-4)^2  = 16\\

\end{array}

$$
1.  f(2)
since the input argument  satisfy the bottom part  
$$
\begin{array}{l}
f(x) = x^2    \\
f(2)  =(2)^2  = 4\\

\end{array}

$$

2.  f(6)
since the input argument  satisfy the middle part  
$$
\begin{array}{l}
f(x) = x+  9   \\
f(2)  =6+  9   =15\\

\end{array}

$$
2.  f(9)
since the input argument  satisfy the top  part  
$$
\begin{array}{l}
f(x) = x+  9   \\
f(9)  =6\\

\end{array}

$$
2.  f(12)

since the input argument  satisfy the top  part  
$$
\begin{array}{l}
f(x) = x+  9   \\
f(9)  =6\\

\end{array}

$$

## compute the difference quotient for the given function. The difference quotient for the function f(x) is defined to be, 
$$
\frac{f(x  + h) - f(x)}{ h} 
$$
$$
f(x )  = 4 - 9x 
$$

$$
\begin{array}{l}
\frac{4 - 9(x + h )  - ( 4 - 9x ) }{ h}  \\
\frac{4  - 9x -  9h  - 4 +  9x  }{ h}  \\
-9 

\end{array}

$$ 




$$
f(x )  = 2x^2   -x  
$$


$$
\begin{array}{l}
\frac{2(x +  h )^2   -(x + h)   - (2x^2   -x)  }{ h}   \\
\frac{2(x^2  +  2xh  + h^2) - x- h  - 2x^2 + x }{ h}  \\
 \frac{2x^2 +  4xh  + 2h^2  - x- h  - 2x^2 + x }{ h}    \\
 \frac{   4xh  + 2h^2  - h   }{ h}    \\
 4x  + 2h  - 1

\end{array}

$$ 
## Determine the domain of the function 
$$
A(x)   =  6x  + 14
$$
Since the value of A(x) is not affected by  any value of x there is no domain 



$$
\begin{array}{l}
f(x)   =  \frac{1}{x^2  - 25}   \\
x^2 -  25  \neq  0  \\
(x +  5) (x- 5)   \neq  0   \\
\left\{\begin{array}{l}
x\neq -5   \\
x \neq  5 
\end{array}\right.
\end{array}

$$


$$


\begin{array}{l}
g(t)  = \frac{8t - 24}{ t^2   - 7t - 18}    \\
t^2   - 7t - 18  \neq  0  \\
(t -  9)(t +  2)  \neq  0   \\
\left\{\begin{array}{l}
x\neq 9   \\
x \neq  -3  
\end{array}\right.
\end{array}


$$




$$


\begin{array}{l}
g(W)  = \sqrt{  9w +  7 }  \\
9w  +  7 \geq 0  \\
 w  \geq  -\frac{7}{9}  \\

\end{array}


$$




$$


\begin{array}{l}
f(x) =  \frac{1}{\sqrt{  x^2  - 8x  + 15   }}\\
x^2  - 8x  + 15  > 0    \\
(x  -  3)( x- 5 )> 0    \\
\left\{\begin{array}{l} 
 x - 3   >  0   \cap x  -5 > 0  \\
x  -3  <  0  \cap x -5 < 0   \\

\end{array}\right.
\end{array}


$$

