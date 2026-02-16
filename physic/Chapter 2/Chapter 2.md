0. what this chapter is about (layer 1 preview)  
    how position changes in time, how velocity/acceleration encode that change, and what simplifies when acceleration is constant (especially free fall).
    

A) layer 1 — logic layer (big picture + structure)

1. chapter “map of maps”
    

keywords/phrases (chapter purpose + flow)

- position vector and displacement $\Delta \vec r$
    
- average vs instantaneous velocity $\vec v$
    
- acceleration $\vec a$ and “constant acceleration”
    
- calculus link: $\vec v = d\vec r/dt$, $\vec a = d\vec v/dt$
    
- graphs: $x(t)$, $v(t)$, $a(t)$ meaning (slope/area)
    
- kinematic equations for constant $\vec a$
    
- free fall: $\vec a = \pm g,\hat y$ (sign convention)
    
- components: $a_x = 0 \Rightarrow v_x$ constant
    
- sign conventions and coordinate choices
    
- what breaks when $\vec a$ is not constant
    

simple flow (what leads to what)

- define motion variables (position/displacement) → define rates (velocity, acceleration) → connect to calculus (derivatives) → integrate under constant acceleration → obtain kinematic equations → specialize to free fall and sign conventions → interpret with components/graphs.
    

2. section outline (navigation-first)
    

note: section titles are not verified from the pdf; labels below are [inferred] from the chapter’s kinematics content and your lecture transcript.

- ch2.[inferred] 2.1 position and displacement vectors: what changes
    
- ch2.[inferred] 2.2 average velocity vs instantaneous velocity: rate idea
    
- ch2.[inferred] 2.3 acceleration: change of velocity
    
- ch2.[inferred] 2.4 graphs: slope/area interpretations
    
- ch2.[inferred] 2.5 constant acceleration assumption: when allowed
    
- ch2.[inferred] 2.6 deriving kinematic equations by integration
    
- ch2.[inferred] 2.7 free fall near earth: $\vec a=\pm g,\hat y$
    
- ch2.[inferred] 2.8 1d vertical motion sign conventions
    
- ch2.[inferred] 2.9 components and “$a_x=0$ implies $v_x$ constant”
    
- ch2.[inferred] 2.10 limits of the equations: nonconstant acceleration
    

B) layer 2 — concepts layer (fine-grained cross-book anchors)

3. fine-grained concept inventory (40 items)
    

support sources available in your project folder (used below)

- Chapter_2_Zemansky.pdf (spine)
    
- Chapter_1_Zemansky.pdf
    
- vectors_overleaf.pdf
    
- University Physics with Modern Physics, Books a la Carte -- Hugh D_ Young, Roger A_ Freedman, A_ Lewis Ford, Francis -- 13th ed_ _ Hugh D_ Young, -- 9780321675460 -- c742c48faa77818c2cc56239c311b1e1 -- Anna’s Arch.pdf
    

for every item: spine anchors are ch2.[inferred] labels (since the pdf’s internal section numbering wasn’t verified). support anchors cite the most likely matching chapter/section by topic name; page numbers are unknown.

1. position vector $\vec r(t)$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.1
    
- support anchors: vectors_overleaf.pdf | vectors + position notation | confidence: medium; Chapter_1_Zemansky.pdf | vectors basics | confidence: medium; University Physics … 13e …pdf | “position, displacement, velocity” | confidence: medium
    
- why you’d open this: what $\vec r$ means and how it’s recorded
    
- prereqs: none
    
- confidence: medium
    

2. displacement $\Delta \vec r = \vec r_f - \vec r_i$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.1
    
- support anchors: Chapter_1_Zemansky.pdf | vector subtraction | confidence: medium; vectors_overleaf.pdf | displacement vs path | confidence: medium; University Physics … 13e …pdf | displacement definition | confidence: medium
    
- why you’d open this: “final minus initial” as change, vector meaning
    
- prereqs: position vector $\vec r(t)$
    
- confidence: medium
    

3. distance vs displacement distinction
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.1
    
- support anchors: University Physics … 13e …pdf | distance traveled vs displacement | confidence: medium; Chapter_1_Zemansky.pdf | scalar vs vector | confidence: medium
    
- why you’d open this: avoid mixing path length with vector change
    
- prereqs: displacement
    
- confidence: medium
    

4. average velocity $\vec v_{\text{avg}} = \Delta \vec r/\Delta t$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.2
    
- support anchors: University Physics … 13e …pdf | average velocity | confidence: medium; Chapter_1_Zemansky.pdf | unit consistency | confidence: medium
    
- why you’d open this: rate-of-change over an interval, vector form
    
- prereqs: displacement
    
- confidence: medium
    

5. instantaneous velocity $\vec v = d\vec r/dt$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.2
    
- support anchors: University Physics … 13e …pdf | instantaneous velocity via derivative | confidence: medium; Chapter_1_Zemansky.pdf | calculus notation in physics | confidence: low
    
- why you’d open this: derivative meaning; connects to slopes
    
- prereqs: average velocity
    
- confidence: medium
    

6. velocity as a function of time $\vec v(t)$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.2
    
- support anchors: University Physics … 13e …pdf | $v(t)$ notation in 1d motion | confidence: medium
    
- why you’d open this: resolve “$v = v_0 + at$ is really $v(t)$”
    
- prereqs: instantaneous velocity
    
- confidence: medium
    

7. average acceleration $\vec a_{\text{avg}} = \Delta \vec v/\Delta t$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.3
    
- support anchors: University Physics … 13e …pdf | average acceleration | confidence: medium
    
- why you’d open this: acceleration as change of velocity over time
    
- prereqs: velocity as a function of time
    
- confidence: medium
    

8. instantaneous acceleration $\vec a = d\vec v/dt = d^2\vec r/dt^2$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.3
    
- support anchors: University Physics … 13e …pdf | acceleration via derivative | confidence: medium
    
- why you’d open this: where $a$ comes from (not “magic formula”)
    
- prereqs: instantaneous velocity
    
- confidence: medium
    

9. constant acceleration assumption (“pull $a$ outside the integral”)
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.5
    
- support anchors: University Physics … 13e …pdf | constant-acceleration model | confidence: medium
    
- why you’d open this: the exact hypothesis that justifies kinematic equations
    
- prereqs: instantaneous acceleration
    
- confidence: medium
    

10. integrating $a$ to get $v$: $\int a,dt$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.6
    
- support anchors: University Physics … 13e …pdf | derivation of $v=v_0+at$ | confidence: medium
    
- why you’d open this: calculus derivation the instructor emphasizes
    
- prereqs: constant acceleration assumption
    
- confidence: medium
    

11. velocity update law (1d): $v = v_0 + at$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.6
    
- support anchors: University Physics … 13e …pdf | constant acceleration equation | confidence: medium
    
- why you’d open this: interpret symbols ($0$ means initial time, not zero velocity)
    
- prereqs: integrating $a$ to get $v$
    
- confidence: medium
    

12. integrating $v$ to get $r$: $\Delta \vec r = \int \vec v,dt$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.6
    
- support anchors: University Physics … 13e …pdf | derivation of $x=x_0+v_0 t+\frac12at^2$ | confidence: medium
    
- why you’d open this: why you must express $v$ in terms of $t$
    
- prereqs: velocity update law
    
- confidence: medium
    

13. displacement under constant $a$: $\Delta \vec r = \vec v_0 t + \frac12 \vec a t^2$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.6
    
- support anchors: University Physics … 13e …pdf | constant acceleration position equation | confidence: medium
    
- why you’d open this: the integrated result and its vector meaning
    
- prereqs: integrating $v$ to get $r$
    
- confidence: medium
    

14. “delta” notation: $\Delta(\cdot)$ means final minus initial
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.6
    
- support anchors: Chapter_1_Zemansky.pdf | unit conversion + difference notation | confidence: low; University Physics … 13e …pdf | $\Delta x$ conventions | confidence: medium
    
- why you’d open this: consistent meaning of $\Delta x$, $\Delta y$, $\Delta\vec r$
    
- prereqs: displacement
    
- confidence: medium
    

15. kinematic equation without time: $v^2 = v_0^2 + 2a\Delta x$ (1d)
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.6
    
- support anchors: University Physics … 13e …pdf | time-eliminated kinematics | confidence: medium
    
- why you’d open this: “equation 3 has no time” elimination idea
    
- prereqs: velocity update law; displacement under constant $a$
    
- confidence: medium
    

16. coordinate choice: origin location matters for $y_0, y$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.8
    
- support anchors: University Physics … 13e …pdf | coordinate system choice in kinematics | confidence: medium
    
- why you’d open this: avoid sign/height mistakes when origin shifts
    
- prereqs: delta notation
    
- confidence: medium
    

17. sign convention: choosing +y up vs +y down
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.8
    
- support anchors: University Physics … 13e …pdf | vertical motion sign conventions | confidence: medium
    
- why you’d open this: why $a_y = -g$ or $+g$ depending on axis
    
- prereqs: coordinate choice
    
- confidence: medium
    

18. free fall definition: “only gravity acts”
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.7
    
- support anchors: University Physics … 13e …pdf | free fall definition and assumptions | confidence: medium
    
- why you’d open this: when it’s valid to set $a=\pm g$
    
- prereqs: constant acceleration assumption
    
- confidence: medium
    

19. air resistance as “breaks free fall” condition
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.7
    
- support anchors: University Physics … 13e …pdf | drag/air resistance warnings (intro) | confidence: low
    
- why you’d open this: why “not too fast” matters in the model
    
- prereqs: free fall definition
    
- confidence: low
    

20. gravitational acceleration magnitude $g \approx 9.8\ \text{m/s}^2$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.7
    
- support anchors: University Physics … 13e …pdf | standard value of $g$ near Earth | confidence: medium
    
- why you’d open this: what $g$ represents (acceleration, not force)
    
- prereqs: free fall definition
    
- confidence: medium
    

21. distinction: gravity (force) vs $g$ (acceleration magnitude)
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.7
    
- support anchors: University Physics … 13e …pdf | force vs acceleration framing | confidence: medium
    
- why you’d open this: stop calling $g$ “gravity” in equations
    
- prereqs: gravitational acceleration magnitude
    
- confidence: medium
    

22. 1d free-fall kinematics with components: $v_y = v_{0y} \pm gt$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.8
    
- support anchors: University Physics … 13e …pdf | vertical motion formula set | confidence: medium
    
- why you’d open this: direct mapping from vector to component form
    
- prereqs: sign convention; velocity update law
    
- confidence: medium
    

23. 1d free-fall displacement: $\Delta y = v_{0y}t + \frac12(\pm g)t^2$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.8
    
- support anchors: University Physics … 13e …pdf | vertical displacement under gravity | confidence: medium
    
- why you’d open this: consistent handling of $\Delta y$ signs
    
- prereqs: sign convention; displacement under constant $a$
    
- confidence: medium
    

24. time symmetry (up and back to same level): $t_\text{down} = t_\text{up}$ (no drag)
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.8
    
- support anchors: University Physics … 13e …pdf | vertical motion symmetry discussion | confidence: low
    
- why you’d open this: why returning-to-same-height time doubles
    
- prereqs: free-fall kinematics with components
    
- confidence: low
    

25. “at the top, $v=0$ but $a\neq 0$”
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.8
    
- support anchors: University Physics … 13e …pdf | acceleration at highest point | confidence: medium
    
- why you’d open this: kill the common misconception immediately
    
- prereqs: instantaneous acceleration
    
- confidence: medium
    

26. 2d decomposition: $\vec v = v_x\hat i + v_y\hat j$, $\vec a = a_x\hat i + a_y\hat j$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.9
    
- support anchors: vectors_overleaf.pdf | component decomposition | confidence: high; Chapter_1_Zemansky.pdf | components and unit vectors | confidence: medium; University Physics … 13e …pdf | 2d motion components | confidence: medium
    
- why you’d open this: translate vector equations into solvable scalars
    
- prereqs: displacement; velocity; acceleration
    
- confidence: high
    

27. component independence principle (solve x and y separately)
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.9
    
- support anchors: University Physics … 13e …pdf | independence of perpendicular motions | confidence: medium
    
- why you’d open this: why $a_x$ doesn’t affect $y$ motion and vice versa
    
- prereqs: 2d decomposition
    
- confidence: medium
    

28. zero horizontal acceleration: $a_x=0$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.9
    
- support anchors: University Physics … 13e …pdf | projectile motion basics: $a_x=0$ | confidence: medium
    
- why you’d open this: identify when horizontal speed stays constant
    
- prereqs: component independence principle
    
- confidence: medium
    

29. consequence: $a_x=0 \Rightarrow v_x$ constant
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.9
    
- support anchors: University Physics … 13e …pdf | constant $v_x$ reasoning | confidence: medium
    
- why you’d open this: the exact interpretation the instructor drilled
    
- prereqs: zero horizontal acceleration
    
- confidence: medium
    

30. interpreting “constant” vs “zero”
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.9
    
- support anchors: Chapter_1_Zemansky.pdf | scalars/vectors and components | confidence: low; University Physics … 13e …pdf | component language | confidence: low
    
- why you’d open this: constant does not mean zero; zero is one constant
    
- prereqs: consequence: $v_x$ constant
    
- confidence: low
    

31. projectile motion launch components: $v_{0x}=v_0\cos\theta$, $v_{0y}=v_0\sin\theta$
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.9
    
- support anchors: vectors_overleaf.pdf | trig/component resolution | confidence: medium; University Physics … 13e …pdf | projectile decomposition | confidence: medium
    
- why you’d open this: connect “5 m/s at 37°” to components
    
- prereqs: 2d decomposition
    
- confidence: medium
    

32. tangent-to-trajectory velocity direction (qualitative)
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.9
    
- support anchors: University Physics … 13e …pdf | velocity tangent to path | confidence: low
    
- why you’d open this: why velocity arrow “turns” while $v_x$ stays fixed
    
- prereqs: component independence principle
    
- confidence: low
    

33. $x(t)$ graph slope as $v$ (qualitative mapping)
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.4
    
- support anchors: University Physics … 13e …pdf | graphs of motion (slope) | confidence: medium
    
- why you’d open this: interpret what graphs are telling you instantly
    
- prereqs: instantaneous velocity
    
- confidence: medium
    

34. $v(t)$ graph slope as $a$ (qualitative mapping)
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.4
    
- support anchors: University Physics … 13e …pdf | graphs of motion (slope/area) | confidence: medium
    
- why you’d open this: read acceleration from velocity graph
    
- prereqs: instantaneous acceleration
    
- confidence: medium
    

35. $v(t)$ area as displacement (constant-$a$ use)
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.4
    
- support anchors: University Physics … 13e …pdf | area under curve gives displacement | confidence: medium
    
- why you’d open this: alternative method when equations are messy
    
- prereqs: integrating $v$ to get $r$
    
- confidence: medium
    

36. “equations only valid if $a$ constant throughout interval”
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.10
    
- support anchors: University Physics … 13e …pdf | limitations of constant-accel model | confidence: low
    
- why you’d open this: know when to stop using the three kinematic equations
    
- prereqs: constant acceleration assumption
    
- confidence: low
    

37. instantaneous vs interval language: “at time $t$” vs “over $[0,t]$”
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.2–2.3
    
- support anchors: University Physics … 13e …pdf | notation $v(t)$, $a(t)$ | confidence: medium
    
- why you’d open this: fix the “0 means zero?” confusion in symbols
    
- prereqs: velocity as a function of time
    
- confidence: medium
    

38. “eliminate time” algebra move (derive eqn without $t$)
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.6
    
- support anchors: University Physics … 13e …pdf | deriving $v^2=v_0^2+2a\Delta x$ | confidence: medium
    
- why you’d open this: know what step is being done conceptually
    
- prereqs: time-eliminated kinematics
    
- confidence: medium
    

39. free fall in orbit: moon/astronauts “still falling”
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.7
    
- support anchors: University Physics … 13e …pdf | orbit as free fall (conceptual) | confidence: low
    
- why you’d open this: connect free fall definition beyond “dropping objects”
    
- prereqs: free fall definition
    
- confidence: low
    

40. apparent weightlessness vs weight (scale reading)
    

- spine anchor: Chapter_2_Zemansky.pdf | ch2.[inferred] 2.7 (bridge to forces)
    
- support anchors: University Physics … 13e …pdf | normal force, apparent weight, elevator/free fall | confidence: low
    
- why you’d open this: interpret “scale reads zero” without saying gravity vanished
    
- prereqs: free fall definition; gravity vs $g$ distinction
    
- confidence: low
    

4. crosswalk table (navigation density)
    

|concept|spine anchor|support #1|support #2|support #3|
|---|---|---|---|---|
|position vector $\vec r(t)$|zemansky ch2.[inf] 2.1|vectors_overleaf: position notation|ch1_zemansky: vectors|young/freedman: position/displacement|
|displacement $\Delta\vec r$|ch2.[inf] 2.1|ch1_zemansky: subtraction|vectors_overleaf: displacement|young/freedman: displacement|
|distance vs displacement|ch2.[inf] 2.1|young/freedman: distance vs displacement|ch1_zemansky: scalar vs vector|—|
|avg velocity|ch2.[inf] 2.2|young/freedman: avg velocity|ch1_zemansky: units|—|
|inst velocity|ch2.[inf] 2.2|young/freedman: derivative|—|—|
|$v(t)$ notation|ch2.[inf] 2.2|young/freedman: $v(t)$|—|—|
|avg acceleration|ch2.[inf] 2.3|young/freedman: avg accel|—|—|
|inst acceleration|ch2.[inf] 2.3|young/freedman: derivative|—|—|
|constant $a$ assumption|ch2.[inf] 2.5|young/freedman: model|—|—|
|integrate $a$→$v$|ch2.[inf] 2.6|young/freedman: derivation|—|—|
|$ v=v_0+at $|ch2.[inf] 2.6|young/freedman: equation|—|—|
|integrate $v$→$r$|ch2.[inf] 2.6|young/freedman: derivation|—|—|
|$\Delta r=v_0t+\frac12at^2$|ch2.[inf] 2.6|young/freedman: equation|—|—|
|$\Delta$ notation|ch2.[inf] 2.6|young/freedman: $\Delta x$|—|—|
|$ v^2=v_0^2+2a\Delta x $|ch2.[inf] 2.6|young/freedman: time-elim|—|—|
|origin choice|ch2.[inf] 2.8|young/freedman: coordinates|—|—|
|+y up vs down|ch2.[inf] 2.8|young/freedman: sign convention|—|—|
|free fall definition|ch2.[inf] 2.7|young/freedman: free fall|—|—|
|air resistance caveat|ch2.[inf] 2.7|young/freedman: drag warning|—|—|
|$g\approx9.8$|ch2.[inf] 2.7|young/freedman: $g$ value|—|—|
|gravity(force) vs $g$(accel)|ch2.[inf] 2.7|young/freedman: force vs accel|—|—|
|$ v_y=v_{0y}\pm gt $|ch2.[inf] 2.8|young/freedman: vertical motion|—|—|
|$\Delta y=v_{0y}t+\frac12(\pm g)t^2$|ch2.[inf] 2.8|young/freedman: vertical motion|—|—|
|time symmetry same height|ch2.[inf] 2.8|young/freedman: symmetry|—|—|
|top: $v=0$, $a\neq0$|ch2.[inf] 2.8|young/freedman: highest point|—|—|
|2d decomposition|ch2.[inf] 2.9|vectors_overleaf: components|ch1_zemansky: unit vectors|young/freedman: 2d motion|
|independence x/y|ch2.[inf] 2.9|young/freedman: independence|—|—|
|$a_x=0$|ch2.[inf] 2.9|young/freedman: projectile basics|—|—|
|$a_x=0\Rightarrow v_x$ const|ch2.[inf] 2.9|young/freedman: constant $v_x$|—|—|
|constant vs zero|ch2.[inf] 2.9|—|—|—|
|launch components trig|ch2.[inf] 2.9|vectors_overleaf: trig comps|young/freedman: decomposition|—|
|velocity tangent to path|ch2.[inf] 2.9|young/freedman: tangent velocity|—|—|
|$x(t)$ slope = $v$|ch2.[inf] 2.4|young/freedman: graphs|—|—|
|$v(t)$ slope = $a$|ch2.[inf] 2.4|young/freedman: graphs|—|—|
|area under $v(t)$|ch2.[inf] 2.4|young/freedman: area|—|—|
|limits of kinematic eqs|ch2.[inf] 2.10|young/freedman: limitations|—|—|
|instant vs interval language|ch2.[inf] 2.2–2.3|young/freedman: notation|—|—|
|time elimination move|ch2.[inf] 2.6|young/freedman: algebra|—|—|
|orbit as free fall|ch2.[inf] 2.7|young/freedman: orbit|—|—|
|apparent weightlessness|ch2.[inf] 2.7|young/freedman: normal force|—|—|

C) layer 3 — important details layer (notation + conditions that matter)

5. high-value details index (22 items)
    

each item links to a layer-2 concept and gives a spine anchor.

1. “$0$” in $v_0$ means “initial time,” not “zero velocity”
    

- linked concept: velocity update law (1d): $v=v_0+at$
    
- spine anchor: ch2.[inferred] 2.6
    

2. $v$ should be read as $v(t)$ when equations involve $t$
    

- linked concept: velocity as a function of time $\vec v(t)$
    
- spine anchor: ch2.[inferred] 2.2
    

3. constant acceleration hypothesis is global on the interval $[0,t]$
    

- linked concept: constant acceleration assumption
    
- spine anchor: ch2.[inferred] 2.5
    

4. “pull $a$ outside the integral” is illegal if $a=a(t)$
    

- linked concept: constant acceleration assumption
    
- spine anchor: ch2.[inferred] 2.6
    

5. $\Delta \vec r$ is always $\vec r_f-\vec r_i$ (vector subtraction)
    

- linked concept: displacement $\Delta\vec r$
    
- spine anchor: ch2.[inferred] 2.1
    

6. $\Delta y$ depends on where you set the origin, but it stays $y_f-y_i$
    

- linked concept: coordinate choice
    
- spine anchor: ch2.[inferred] 2.8
    

7. $g$ is a magnitude; $\vec a$ has direction set by axes
    

- linked concept: gravitational acceleration magnitude; sign convention
    
- spine anchor: ch2.[inferred] 2.7–2.8
    

8. if +y is up, then $a_y=-g$ for free fall
    

- linked concept: sign convention
    
- spine anchor: ch2.[inferred] 2.8
    

9. if +y is down, then $a_y=+g$ for free fall
    

- linked concept: sign convention
    
- spine anchor: ch2.[inferred] 2.8
    

10. at the highest point: $v_y=0$ but $a_y=\pm g$ still
    

- linked concept: “at the top, $v=0$ but $a\neq0$”
    
- spine anchor: ch2.[inferred] 2.8
    

11. “velocity” vs “speed”: sign/direction must be stated for velocity
    

- linked concept: free fall kinematics with components
    
- spine anchor: ch2.[inferred] 2.8
    

12. “constant” means unchanged; it can be nonzero or zero
    

- linked concept: interpreting “constant” vs “zero”
    
- spine anchor: ch2.[inferred] 2.9
    

13. $a_x=0$ implies $v_x$ constant, not necessarily $v_x=0$
    

- linked concept: consequence: $v_x$ constant
    
- spine anchor: ch2.[inferred] 2.9
    

14. when you say “free fall,” you are neglecting air friction by definition here
    

- linked concept: free fall definition; air resistance caveat
    
- spine anchor: ch2.[inferred] 2.7
    

15. “near earth surface” is a modeling condition for constant $g$
    

- linked concept: gravitational acceleration magnitude
    
- spine anchor: ch2.[inferred] 2.7
    

16. $\vec v = d\vec r/dt$ is vector: applies componentwise
    

- linked concept: instantaneous velocity; 2d decomposition
    
- spine anchor: ch2.[inferred] 2.2, 2.9
    

17. $\vec a = d\vec v/dt$ is vector: applies componentwise
    

- linked concept: instantaneous acceleration; 2d decomposition
    
- spine anchor: ch2.[inferred] 2.3, 2.9
    

18. “equation without time” comes from substituting $t=(v-v_0)/a$ (conceptually)
    

- linked concept: time-eliminated kinematics
    
- spine anchor: ch2.[inferred] 2.6
    

19. if the object is still in the air, acceleration remains $\pm g$ throughout
    

- linked concept: “equations only valid if $a$ constant throughout interval”
    
- spine anchor: ch2.[inferred] 2.10
    

20. the scale reads the contact force, not “gravity directly”
    

- linked concept: apparent weightlessness vs weight
    
- spine anchor: ch2.[inferred] 2.7 (bridge concept)
    

21. “only gravity acts” can still mean many gravities add; net is gravitational
    

- linked concept: free fall definition; orbit as free fall
    
- spine anchor: ch2.[inferred] 2.7
    

22. graphs: slope/area statements are about derivatives/integrals, not memorized tricks
    

- linked concept: $x(t)$ slope = $v$; $v(t)$ slope = $a$; area under $v(t)$
    
- spine anchor: ch2.[inferred] 2.4
    

D) layer 4 — arbitrary details layer (low priority unless needed)

6. low-yield index (short)
    

- numeric comparisons about atmosphere height vs earth radius (25–30 km vs 6380 km): skip unless required | spine anchor: ch2.[inf] 2.7
    
- side rant about terminology policing (“nobel prize winners say it too”): skip unless required | spine anchor: ch2.[inf] 2.7
    
- long electricity/current analogy to explain wording (“current doesn’t flow”): skip unless required | spine anchor: ch2.[inf] 2.7 (bridge)
    
- story/jokes about waiting for lunch / late friend: skip unless required | spine anchor: ch2.[inf] 2.6
    
- class-management chatter (“five minutes to see homework posted”): skip unless required | spine anchor: ch2.[inf] 2.10
    

7. two paths (navigation, not drills)
    

minimal path (ordered layer-2 concept names)

1. displacement $\Delta \vec r = \vec r_f - \vec r_i$
    
2. instantaneous velocity $\vec v = d\vec r/dt$
    
3. instantaneous acceleration $\vec a = d\vec v/dt$
    
4. constant acceleration assumption (“pull $a$ outside the integral”)
    
5. velocity update law (1d): $v = v_0 + at$
    
6. displacement under constant $a$: $\Delta \vec r = \vec v_0 t + \frac12 \vec a t^2$
    
7. sign convention: choosing +y up vs +y down
    
8. free fall definition: “only gravity acts”
    
9. 1d free-fall kinematics with components: $v_y = v_{0y} \pm gt$
    

mastery path (minimal + extras)

- add: time-eliminated kinematics $v^2 = v_0^2 + 2a\Delta x$ (1d)
    
- add: graphs: $x(t)$ slope = $v$, $v(t)$ slope = $a$, area under $v(t)$
    
- add: 2d decomposition and component independence
    
- add: $a_x=0 \Rightarrow v_x$ constant
    
- add: “at the top, $v=0$ but $a\neq 0$”
    
- add: orbit as free fall; apparent weightlessness vs weight
    

8. works cited (project library only)
    

- Chapter_2_Zemansky.pdf | location: chapter 2 (internal section titles not verified; anchors used are [inferred])
    
- Chapter_1_Zemansky.pdf | location: vectors/units preliminaries (exact section not verified)
    
- vectors_overleaf.pdf | location: vectors, components, unit vectors, trig resolution (exact section not verified)
    
- University Physics with Modern Physics, Books a la Carte -- Hugh D_ Young, Roger A_ Freedman, A_ Lewis Ford, Francis -- 13th ed_ _ Hugh D_ Young, -- 9780321675460 -- c742c48faa77818c2cc56239c311b1e1 -- Anna’s Arch.pdf | location: kinematics 1d/2d, free fall, graphs, apparent weight (exact chapter/section not verified)
    

if you want, paste any one screenshot of the Chapter_2_Zemansky table of contents page and i’ll replace every ch2.[inferred] anchor with the real section numbers without changing the concept list.