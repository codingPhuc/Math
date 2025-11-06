Install these seven TI-Basic programs. They cover OpenStax 3.4–4.8. All are exam-safe (no jailbreak, no ASM).



# Compatable version 

Use these CE-safe picks for TI-84 Plus CE OS 5.4.0. All are TI-BASIC (no jailbreak). I grouped them to match OpenStax 3.4–4.8.

### Exact downloads

1. **Implicit/explicit dy/dx + tangent line**  x1 
    Purpose: Implicit dy/dx via −Fx/Fy, explicit dy/dx, tangent line at a point. CE-compatible BASIC. Download: ticalc “Derivatives—Implicit and Explicit.” ([Ticalc](https://www.ticalc.org/archives/files/fileinfo/409/40946.html?utm_source=chatgpt.com "Derivatives- Implicit and Explicit"))  
    Mirror with steps: CalculatorTI page. ([Calculatorti.com](https://www.calculatorti.com/ti-programs/ti-83-plus-ti-84-plus/calculus/derivatives-implicit-and-explicit-tangent-line-of-a-point/?srsltid=AfmBOorlQ3NaW0XnsZINiN6Lgwsht7cauxffGIpyRFn6cSSOybIKYk6V&utm_source=chatgpt.com "Derivatives - Implicit and Explicit - Tangent Line of a Point"))
        note : do not used the tangent line function  since using it will create a horizontal split screen making the calculator hard to operate to reset the screen : 
        1. go to mode 
        2. 
    
2. **Tangent line (fast) + Normal line**  x1
    Purpose: Equation of tangent; normal uses m⊥=−1/m. CE BASIC. Downloads: **Tangent_Line84 v1.10** and **Perpendicular_Line84 v1.01**. ([Ticalc](https://www.ticalc.org/pub/84pluscse/basic/math/?utm_source=chatgpt.com "TI-84 Plus C Silver Edition/CE BASIC Math Programs"))

3. **Mean Value Theorem helper**  x1 (problem have to reset after used )
    Purpose: Compute secant slope and solve f′(c)=secant on [a,b]. BASIC for 83+/84+ that runs on CE. Download: “AP Calculus Series: Mean Value.” ([Ticalc](https://www.ticalc.org/pub/83plus/basic/math/calculus/?utm_source=chatgpt.com "TI-83/84 Plus BASIC Math Programs (Calculus)"))
    
4. **L’Hôpital + derivative rules pack (ADERIV)**   x1
    Purpose: Quick derivative forms and L’Hôpital tool for 4.8. CE-compatible BASIC. Download: ticalc “Derivatives (ADERIV).” ([Ticalc](https://www.ticalc.org/archives/files/fileinfo/456/45646.html?utm_source=chatgpt.com "Derivatives"))


6. **Inflection points**  
    Options:  
    • **ALLSOLVE2** (CE BASIC): can find up to four inflection points. ([Ticalc](https://www.ticalc.org/archives/files/fileinfo/455/45552.html?utm_source=chatgpt.com "ALLSOLVE2")) 

```
	 Anders Tiberg den 3 September, 2013

                                                                   ALLSOLV2

 This program is a multi purpose equation solver which can find up to six real roots, and five extremes ( maxima/minima ). It can also find four terrace points or four inflection points. It can solve a wide variety of equations. For example: log(X^2)=.4, abs((X-3)(X+2))=4, cos(X^2)=.5, (X-300)(X-400)(X-500)(X-600)=0, cos(X)=X^2+3X, (X+1.1)(X+1.2)(X+1.3)=0, abs(X^3-1)=7, (X^3-7)^(1/3)=X-1. It uses the solve(-, and nDeriv(- commands. When you enter the equation you don't have to enter the =-sign, and the right side if it is 0. You simply enter just the left side then. On the other hand if the right side differs from nil, you can either enter the equation as it stands, or move the negation of the right side to the left side. Thus an equation like (X^3-7)^(1/3)=X-1, can also be entered as (X^3-7)^(1/3)-X+1.

 After you've entered the equation you are asked: "RSLT IN RAD. Y/N", which means wether you want the answer in radians or not. Enter Y or N depending of your choice. Then a menu opens up with five choices: 1, Real roots, 2, Find Max/Mins, 3, Inflection/Terrace Points, 4, Show Graph, 5, Exit. In the first three you are asked how many points on the function curve you search for. In the fourth, ( which you choose first if you're uncertain ), you get four options for: "ZOOM?", by which you decide what window you want. If you are uncertain, choose 6: ZStandard. You can always go back and choose another option. When you have seen the graph, you can estimate how many points of which kind you search for.

Upon execution of each of your choice you will be asked if you want the result in radians. It's a bit tedious, but it saved a lot of bytes. The exception is if you choose more points of a kind than there are. The program will then stop with an: "ERR: NO SIGN CHNG", or: "ERR: SINGULARTY". Just press [ 1 ] then to see the results. If you want to continue then, you have to start from the beginning. So let the program graph it for you first.

The program uses the solve(- function, so it can't find imaginary solutions, and neither can it solve for double roots. For example an equation like (X-2)(X-2)=0, gives an ERR: NO SIGN CHANGE. Also there may be trouble with even index radical equations as SQRT(X-5)=1, and rational equations in which a denominator may become 0 as 1/(X-5)=1.

 If you have an even radical equation like, Sqrt(X-5)=2, you can square the equation so you get rid of the root-sign: (X-5)=4, and then solve it. A rational equation like (X-5)/(X-1)=4, can be rewritten as, (X-5)=4(X-1).

                            Questions/input, write to: anders.tiberg@telia.com
 ```
 
• **Point of Inflection Finder** (83+/84+ BASIC; generally CE-compatible): scan a bound interval. ([Ticalc](https://www.ticalc.org/archives/files/fileinfo/357/35711.html?utm_source=chatgpt.com "Point of Inflection Finder"))
    

7. **Domain, Range, Derivatives, Integrals v1.1**  
    Purpose: quick domain/range for common trig/log/exp families (useful screening).  
    Download:
    

```
https://www.ticalc.org/archives/files/fileinfo/229/22962.html
```

([TICalc](https://www.ticalc.org/archives/files/fileinfo/229/22962.html?utm_source=chatgpt.com "Domain, Range, Derivatives, and Integrals v1.1"))
### Install (CE 5.4.0)

1. Install **TI-Connect CE** on your computer. ([Texas Instruments Education](https://education.ti.com/en/products/computer-software/ti-connect-ce-sw?utm_source=chatgpt.com "TI Connect™ CE Software Application | Texas Instruments"))
    
2. USB-connect calculator → open TI-Connect CE → **Send to Calculators…** → select each downloaded `.8xp` file → Send. ([Texas Instruments Education](https://education.ti.com/en/products/computer-software/ti-connect-ce-sw?utm_source=chatgpt.com "TI Connect™ CE Software Application | Texas Instruments"))
    
3. Run on calc: `PRGM` → select program → `ENTER` → `ENTER`.
    

### CE 5.4.0 compatibility notes

- TI-BASIC programs above run on CE 5.4.0. (Many 83+/84+ BASIC programs also run on CE; Cemetech explains CE BASIC compatibility.) ([Cemetech](https://www.cemetech.net/downloads/browse84pce/basic/education?utm_source=chatgpt.com "Archives: TI-84 Plus CE BASIC Educational Programs"))
    
- OS 5.4.0 still allows ASM, but TI removed ASM in 5.6+. You do not need ASM here. Avoid updating if you rely on legacy ASM. ([Reddit](https://www.reddit.com/r/TI_Calculators/comments/hqwzng/assembly_on_ti84_plus_ce_os_540/?utm_source=chatgpt.com "Assembly on TI-84 Plus CE OS 5.4.0? : r/TI_Calculators"))
    

### Troubleshooting your earlier split-screen error

If a program opens to a graph on top and an input pane below, you’re in a split mode and some programs will throw “check type/number of arguments.” Fix: `MODE` → set **FULL** (not **HORIZONTAL** or **GRAPH-TABLE**) → `2nd` `QUIT`, then rerun. ([Texas Instruments Education](https://education.ti.com/html/webhelp/EG_TI84PlusCE/EN/content/eg_gsguide/m_setting_modes/sm_full_horiz_graph.HTML?utm_source=chatgpt.com "FULL HORIZONTAL GRAPH-TABLE"))

---

### Definitions

- CE-compatible BASIC: TI-BASIC programs that run on the color CE models without jailbreak.
    
- Implicit differentiation: compute (dy/dx=-F_x/F_y) when (F(x,y)=0).
    
- Mean Value Theorem: there exists (c\in(a,b)) with (f'(c)=\frac{f(b)-f(a)}{b-a}).
    
- L’Hôpital’s Rule: for certain indeterminate forms, (\lim \frac{f}{g}=\lim \frac{f'}{g'}) if conditions hold.
    
- Split-screen modes: **Horizontal** or **Graph-Table** show two panes; **Full** uses the whole screen. ([Texas Instruments Education](https://education.ti.com/html/webhelp/EG_TI84PlusCE/EN/content/eg_gsguide/m_setting_modes/sm_full_horiz_graph.HTML?utm_source=chatgpt.com "FULL HORIZONTAL GRAPH-TABLE"))

# Non compatable version 
## Exact picks to download

1. **Derivatives — Implicit & Explicit + Tangent line**   x1 
    Purpose: dy/dx for explicit or implicit F(x,y)=0 and tangent line at a point.  
    Download:
    
explicit different
![[EXPLICIT.gif]]
implicit different 
![[IMPLICIT.gif]]
![[-Readme-.txt]]
```
https://www.calculatorti.com/ti-programs/ti-83-plus-ti-84-plus/calculus/derivatives-implicit-and-explicit-tangent-line-of-a-point/
```

Alt (same idea, shows work):

```
https://www.ticalc.org/archives/files/fileinfo/409/40946.html
```

reseting graph program  x1 


([Calculatorti.com](https://www.calculatorti.com/ti-programs/ti-83-plus-ti-84-plus/calculus/derivatives-implicit-and-explicit-tangent-line-of-a-point/?srsltid=AfmBOoqrH8TzqFak_IZXQ4GlTXEMzgiIEpAyHf9Z7lZ8PX9nch_eU1mw&utm_source=chatgpt.com "Derivatives - Implicit and Explicit - Tangent Line of a Point"))

2. **AP Calculus: f(x) of a Tangent**  problem(it overwrite the setting for graphing) x1
	1. you have to go to format screen and window screen to set the coordinate all back 
    Purpose: equation of the tangent line at x₀; use slope m for normal = −1/m.  
    Download:
![[Pasted image 20251105185839.png]]
![[Pasted image 20251105185847.png]]
![[apytngnt.txt]]
```
https://www.ticalc.org/archives/files/fileinfo/253/25313.html
```

([TICalc](https://www.ticalc.org/archives/files/fileinfo/253/25313.html?utm_source=chatgpt.com "AP Calculus Series: f(x) of a Tangent"))

3. **AP Calculus: Mean Value (MVT)**  
    Purpose: checks MVT and finds c with f′(c) = [f(b)−f(a)]/(b−a) on [a,b].  
    Download:
    

```
https://www.ticalc.org/archives/files/fileinfo/255/25536.html
```

([TICalc](https://ticalc.org/archives/files/fileinfo/255/25536.html?utm_source=chatgpt.com "AP Calculus Series: Mean Value"))

4. **Point of Inflection Finder**  
    Purpose: scans a bound interval for sign change in f′′ and reports inflection points.  
    Download:
    

```
https://www.ticalc.org/archives/files/fileinfo/357/35711.html
```

([TICalc](https://www.ticalc.org/archives/files/fileinfo/357/35711.html?utm_source=chatgpt.com "Point of Inflection Finder"))

5. **Limit Finder**  
    Purpose: numeric one-sided and two-sided limits near a point.  
    Download:
    

```
https://www.calculatorti.com/ti-programs/ti-83-plus-ti-84-plus/calculus/limit-finder/
```

([Calculatorti.com](https://www.calculatorti.com/ti-programs/ti-83-plus-ti-84-plus/calculus/limit-finder/?srsltid=AfmBOoqQPZiDcy6Qhds-pJ4KWvAV-DrkRz2YOKpFeQ9ZlTT_cGeTKwEM&utm_source=chatgpt.com "Limit Finder - TI 83 Plus and TI 84 Plus Programs"))

6. **Limit of a Function: Infinity**  
    Purpose: limits as x→±∞; horizontal asymptote checks.  
    Download:
    

```
https://www.calculatorti.com/ti-programs/ti-83-plus-ti-84-plus/calculus/limit-of-a-function-infinity/
```

Alt (finite-point limits):

```
https://www.ticalc.org/archives/files/fileinfo/249/24983.html
```

([Calculatorti.com](https://www.calculatorti.com/ti-programs/ti-83-plus-ti-84-plus/calculus/limit-of-a-function-infinity/?srsltid=AfmBOooKqfDDx_sghL_2jvbHek4P28KNGnDv_ji0pkkjUPHyE7YiSQBO&utm_source=chatgpt.com "Limit of a Function: Infinity"))


### Optional add (handy for 4.8)

• **Derivatives (ADERIV, includes L’Hôpital)** — CE-compatible helper formulas and L’Hôpital tool.  
Download:

```
https://www.ticalc.org/archives/files/fileinfo/456/45646.html
```

([TICalc](https://www.ticalc.org/archives/files/fileinfo/456/45646.html "Derivatives - ticalc.org"))

## How to install

1. Install **TI-Connect CE** on your computer.  
    Download:
    

```
https://education.ti.com/en/products/computer-software/ti-connect-ce-sw
```

Guide:

```
https://education.ti.com/en/customer-support/knowledge-base/sofware-apps/product-usage/11492
```

([Texas Instruments Education](https://education.ti.com/en/products/computer-software/ti-connect-ce-sw?utm_source=chatgpt.com "TI Connect™ CE Software Application | Texas Instruments"))  
2) Connect calculator via USB → open TI-Connect CE → **Send to Calculators…** → pick each `.8xp` you downloaded. Confirm they appear under `PRGM` on the TI-84. ([Texas Instruments Education](https://education.ti.com/en/customer-support/knowledge-base/sofware-apps/product-usage/11492?utm_source=chatgpt.com "Editing And Transferring Programs Using TI Connect™ and ..."))

## Notes

- These are TI-Basic, so they run on TI-84 Plus and CE without enabling blocked ASM/C. Keep your OS current. ([Texas Instruments Education](https://education.ti.com/en/software/update/84-ce-software-update?utm_source=chatgpt.com "TI-84 Plus CE | Product Updates | Texas Instruments"))
    
- For y-intercepts you usually do not need a program: evaluate at x=0 with `2nd`→`TRACE`→`Value`. Use the tangent program only when the problem asks for the full line. ([TICalc](https://www.ticalc.org/archives/files/fileinfo/253/25313.html?utm_source=chatgpt.com "AP Calculus Series: f(x) of a Tangent"))
    

Definitions

- TI-Basic program: User app you run from `PRGM`; allowed on standard TI-84 exam modes.
    
- Implicit differentiation: Differentiate F(x,y)=0 to obtain dy/dx.
    
- Mean Value Theorem (MVT): Guarantees c in (a,b) with f′(c)=secant slope.
    
- L’Hôpital’s Rule: Uses derivative ratio to evaluate certain indeterminate limits.
    
- One-sided limit: Limit from left or right only; used to test DNE at jumps.