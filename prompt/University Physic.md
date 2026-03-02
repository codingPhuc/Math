Patty — before you read, do these three things (one sentence each):

1. Restate the problem in your own words.
    
2. Show your current attempt (even if it’s a mess).
    
3. Say what you think the first subgoal is (identify the right formula? justify why acceleration isn’t zero?).
    

4. Scope and learning targets
    

We focus on one skill: recognizing that “constant speed in a circle” still implies nonzero acceleration, and that the magnitude is determined by the radial (centripetal) component. The target is to (i) distinguish speed vs velocity, (ii) interpret acceleration as “change of velocity,” (iii) use the uniform-circular-motion relation $a_{\perp}=\dfrac{v^2}{r}$, and (iv) check units to avoid nonsense. (Chapter_2_Zemansky.pdf PDF p.1; Chapter_3_Zemansky (1).pdf PDF pp.4–6; University Physics … Anna’s Arch.pdf PDF p.86; printed p.78)

1. Prerequisites (only what’s truly needed; cite)
    

You need only:

1. Vectors vs scalars; units for speed and acceleration (Chapter_1_Zemansky.pdf PDF p.6)
    
2. Speed vs velocity (speed has no direction; velocity does) (Chapter_2_Zemansky.pdf PDF p.1)
    
3. Acceleration as the time derivative of velocity (definition) (Chapter_3_Zemansky (1).pdf PDF p.4)
    
4. The uniform circular motion fact: constant speed + circular path (Chapter_3_Zemansky (1).pdf PDF p.6)
    
5. Where this sits in your course spine (Young & Freedman is the suggested text; chapters 1–16) (Syllabus - Physics 185 - Spring 2026 - Guerra (1).docx p.1)
    
6. Definitions, notation, and units (cite every definition)
    

Coordinate/geometry objects:

- Radius $r$: the (constant) distance from the circle’s center to the particle. In your problem, “radius 10 m” means $r=10,\text{m}$ and is a length. (Chapter_1_Zemansky.pdf PDF p.1)
    
- Speed $v$: a scalar measured in $\text{m/s}$. It is not the same thing as velocity (which includes direction). (Chapter_2_Zemansky.pdf PDF p.1; Chapter_1_Zemansky.pdf PDF p.6)
    

Kinematics objects:

- Velocity vector $\vec v$: a vector (magnitude + direction), units $\text{m/s}$. (Chapter_1_Zemansky.pdf PDF p.6)
    
- Acceleration vector $\vec a$: a vector, units $\text{m/s}^2$. Defined (instantaneously) as the derivative of velocity with respect to time. (Chapter_1_Zemansky.pdf PDF p.6; Chapter_3_Zemansky (1).pdf PDF p.4)
    

Circular-motion decomposition:

- Tangential component $a_{\parallel}$: comes from a change in the magnitude of $\vec v$; $a_{\parallel}=\dfrac{d|v|}{dt}$. (Chapter_3_Zemansky (1).pdf PDF p.4)
    
- Radial/centripetal component $a_{\perp}$: comes from a change in the direction of $\vec v$; for circular motion $a_{\perp}=\dfrac{v^2}{r}$ directed toward the center. (Chapter_3_Zemansky (1).pdf PDF p.5)
    
- Uniform circular motion: motion in a circle at constant speed. (Chapter_3_Zemansky (1).pdf PDF p.6)
    

3. Core ideas and interpretation (mostly conceptual; cite)
    

Idea 1: “Acceleration” means “velocity is changing,” not “speed is changing.”  
Acceleration is $\vec a=\dfrac{d\vec v}{dt}$ (Chapter_3_Zemansky (1).pdf PDF p.4) . Because $\vec v$ includes direction, $\vec v$ can change even if its magnitude $|\vec v|=v$ is constant. This is exactly why circular motion can have nonzero acceleration at constant speed. (University Physics … Anna’s Arch.pdf PDF p.86; printed p.78)

Idea 2: In uniform circular motion, the acceleration has no tangential part.  
If speed is constant, $a_{\parallel}=\dfrac{d|v|}{dt}=0$. (Chapter_3_Zemansky (1).pdf PDF p.4)

Idea 3: The acceleration is perpendicular to the velocity and points inward.  
For constant-speed circular motion, the acceleration is perpendicular (normal) to the path and “directed inward (never outward!) toward the center,” changing direction of $\vec v$ without changing its magnitude. (University Physics … Anna’s Arch.pdf PDF p.86; printed p.78)

Idea 4: Magnitude rule you actually use on homework  
The magnitude of the radial (centripetal) acceleration is  
$$  
a_{\perp}=\frac{v^2}{r}.  
$$  
(Chapter_3_Zemansky (1).pdf PDF p.5; University Physics … Anna’s Arch.pdf PDF p.100; printed p.92)

4. Derivations (rigorous; step-by-step; cite the rule/theorem used)
    

Derivation goal: justify why $a_{\perp}$ scales like $v^2/r$ in uniform circular motion.

Step 1 (definition): start from acceleration as a limit of average acceleration:  
$$  
\vec a=\lim_{\Delta t\to 0}\frac{\Delta \vec v}{\Delta t}.  
$$  
This is the content of $\vec a=d\vec v/dt$. (Chapter_3_Zemansky (1).pdf PDF p.4)

Step 2 (geometry of $\Delta \vec v$): over a short time $\Delta t$, the particle moves a short arc length $\Delta s$ along a circle of radius $R$ with (approximately) constant speed $v$. The velocity vectors at the start and end have equal magnitude $v$ but differ in direction; the change $\Delta \vec v$ forms a triangle similar to the triangle formed by the radii (similar-triangles argument). (University Physics … Anna’s Arch.pdf PDF p.86; printed p.78)

Step 3 (similar triangles ratio): similarity gives a proportionality of magnitudes:  
$$  
\frac{|\Delta \vec v|}{v}=\frac{\Delta s}{R}.  
$$  
This proportionality is exactly what the text states via the similar-triangle setup. (University Physics … Anna’s Arch.pdf PDF p.86; printed p.78)

Step 4 (divide by $\Delta t$ and take the limit): divide both sides by $\Delta t$:  
$$  
\frac{|\Delta \vec v|}{\Delta t}=\frac{v}{R}\frac{\Delta s}{\Delta t}.  
$$  
Now take $\Delta t\to 0$. By definition of instantaneous speed, $\lim_{\Delta t\to 0}\dfrac{\Delta s}{\Delta t}=v$. Substituting yields  
$$  
\lim_{\Delta t\to 0}\frac{|\Delta \vec v|}{\Delta t}=\frac{v}{R}\cdot v=\frac{v^2}{R}.  
$$  
This is the magnitude of the instantaneous acceleration, directed radially inward. (University Physics … Anna’s Arch.pdf PDF p.86; printed p.78; Chapter_3_Zemansky (1).pdf PDF p.5)

5. Worked examples for understanding (minimum 3; light numerics; conceptual emphasis; cite)
    

Example 1 (scaling): same speed, different radius  
Two particles have the same speed $v$ but radii $r_1$ and $r_2$. Using $a_{\perp}=v^2/r$, the ratio is  
$$  
\frac{a_1}{a_2}=\frac{v^2/r_1}{v^2/r_2}=\frac{r_2}{r_1}.  
$$  
So tighter circle (smaller $r$) means larger acceleration even if speed is unchanged. (Chapter_3_Zemansky (1).pdf PDF p.5)

Example 2 (period form, conceptual): expressing $a_{\perp}$ using the period $T$  
Uniform circular motion satisfies $T=\dfrac{2\pi r}{v}$, equivalently $v=\dfrac{2\pi r}{T}$. (Chapter_3_Zemansky (1).pdf PDF p.6)  
Substitute into $a_{\perp}=\dfrac{v^2}{r}$:  
$$  
a_{\perp}=\frac{1}{r}\left(\frac{2\pi r}{T}\right)^2=\frac{4\pi^2 r}{T^2}.  
$$  
Interpretation: for fixed $r$, shorter period (faster revolution) means larger acceleration; for fixed $T$, larger circle means larger acceleration. (University Physics … Anna’s Arch.pdf PDF p.100; printed p.92)

Example 3 (your exact homework setup, stop before the final arithmetic)  
Given: $r=10,\text{m}$, $v=20,\text{m/s}$, uniform circular motion (constant speed in a circle) (Chapter_3_Zemansky (1).pdf PDF pp.5–6)  
Therefore the acceleration magnitude is  
$$  
a=\frac{v^2}{r}.  
$$  
Your only remaining job is substitution and unit-check (see Section 6, failure mode “forgot units”). Do that substitution yourself and send me the number you get; I’ll tell you if it’s correct. (Chapter_1_Zemansky.pdf PDF p.6)

6. Common misconceptions and failure modes (minimum 6; each with “why wrong” + fix; cite)
    

7. Misconception: “Constant speed means zero acceleration.”  
    Why wrong: acceleration is $d\vec v/dt$, and $\vec v$ changes when direction changes, even if speed is constant. (Chapter_3_Zemansky (1).pdf PDF p.4; University Physics … Anna’s Arch.pdf PDF p.86; printed p.78)  
    Fix: Ask: is direction changing? If yes, $\vec a\neq \vec 0$.
    
8. Misconception: “Velocity and speed are interchangeable.”  
    Why wrong: speed is scalar; velocity is vector (includes direction). (Chapter_2_Zemansky.pdf PDF p.1; Chapter_1_Zemansky.pdf PDF p.6)  
    Fix: Treat $v$ as $|\vec v|$; only $\vec v$ has direction.
    
9. Misconception: “Centripetal acceleration points outward (centrifugal).”  
    Why wrong: for uniform circular motion, acceleration is inward “never outward!” (University Physics … Anna’s Arch.pdf PDF p.86; printed p.78)  
    Fix: Draw the circle: $\vec v$ tangent; $\vec a$ toward center.
    
10. Misconception: “Use $a=v/r$ (forgot the square).”  
    Why wrong: the established relation is $a_{\perp}=v^2/r$. (Chapter_3_Zemansky (1).pdf PDF p.5; University Physics … Anna’s Arch.pdf PDF p.100; printed p.92)  
    Fix: Dimensional check: $v/r$ has units $1/\text{s}$, not $\text{m/s}^2$.
    
11. Misconception: “There must be a tangential component because it’s ‘moving.’”  
    Why wrong: tangential acceleration is $a_{\parallel}=d|v|/dt$, and constant speed implies this is $0$. (Chapter_3_Zemansky (1).pdf PDF p.4)  
    Fix: Separate “change of magnitude” vs “change of direction.”
    
12. Misconception: “No time given, so you can’t find acceleration.”  
    Why wrong: in uniform circular motion, $a$ is determined locally by $v$ and $r$ (or by $r$ and $T$). (Chapter_3_Zemansky (1).pdf PDF pp.5–6; University Physics … Anna’s Arch.pdf PDF p.100; printed p.92)  
    Fix: Identify which formula matches the given data.
    
13. Misconception: “Units don’t matter in a short answer box.”  
    Why wrong: in SI, acceleration is in $\text{m/s}^2$; units are part of the physical quantity. (Chapter_1_Zemansky.pdf PDF p.6; Syllabus - Physics 185 - Spring 2026 - Guerra (1).docx p.1)  
    Fix: Always check $(\text{m/s})^2/\text{m}=\text{m/s}^2$.
    

14. Checkpoints (8–15 short questions)
    

15. In one sentence: why can acceleration be nonzero when speed is constant?
    
16. What is the definition of instantaneous acceleration in terms of velocity?
    
17. In uniform circular motion, which acceleration component is zero: tangential or radial? Why?
    
18. State the magnitude formula for centripetal acceleration.
    
19. Do a units check on $v^2/r$ in SI units.
    
20. If $v$ doubles and $r$ stays fixed, how does $a_{\perp}$ change?
    
21. If $r$ doubles and $v$ stays fixed, how does $a_{\perp}$ change?
    
22. What is the direction of $\vec a$ relative to $\vec v$ in uniform circular motion?
    
23. Express $v$ in terms of $r$ and period $T$.
    
24. Use 9) to express $a_{\perp}$ in terms of $r$ and $T$.
    

25. Answers to checkpoints
    

26. Because velocity includes direction; direction changes on a circle even when speed is constant. (University Physics … Anna’s Arch.pdf PDF p.86; printed p.78)
    
27. $\vec a=d\vec v/dt$. (Chapter_3_Zemansky (1).pdf PDF p.4)
    
28. Tangential is zero, because $a_{\parallel}=d|v|/dt$ and $|v|$ is constant. (Chapter_3_Zemansky (1).pdf PDF p.4)
    
29. $a_{\perp}=v^2/r$ (inward). (Chapter_3_Zemansky (1).pdf PDF p.5)
    
30. $(\text{m/s})^2/\text{m}=\text{m/s}^2$. (Chapter_1_Zemansky.pdf PDF p.6)
    
31. Quadruples. (From $a_{\perp}\propto v^2$.) (Chapter_3_Zemansky (1).pdf PDF p.5)
    
32. Halves. (From $a_{\perp}\propto 1/r$.) (Chapter_3_Zemansky (1).pdf PDF p.5)
    
33. Perpendicular to $\vec v$ and toward the center. (University Physics … Anna’s Arch.pdf PDF p.86; printed p.78)
    
34. $v=2\pi r/T$. (Chapter_3_Zemansky (1).pdf PDF p.6)
    
35. $a_{\perp}=4\pi^2 r/T^2$. (Derived in Section 5.) (University Physics … Anna’s Arch.pdf PDF p.100; printed p.92)
    

36. Practice set (10 problems: 3 easy, 4 medium, 3 hard; conceptual-first)
    

Easy

1. A particle moves in a circle at constant speed. Which is zero: $a_{\parallel}$ or $a_{\perp}$? Justify.
    
2. If $v$ triples and $r$ stays fixed, by what factor does $a_{\perp}$ change?
    
3. Units check: show $v^2/r$ has units of acceleration.
    

Medium  
4) A car rounds a curve of radius $r$ at speed $v$. Express the acceleration magnitude and direction in words.  
5) Express $a_{\perp}$ in terms of $r$ and $T$, and interpret what happens if $T$ is halved.  
6) Two circles have radii $r$ and $3r$. Same speed $v$. Compare accelerations.  
7) A particle’s speed is constant but its path is not a circle (some curved path). Which idea from circular motion still applies conceptually?

Hard  
8) Nonuniform circular motion: explain why $a_{\parallel}$ can be nonzero while $a_{\perp}$ still exists; identify what each “does” to motion.  
9) Explain (conceptually) why sharper curves require larger friction to avoid slipping at the same speed.  
10) You are given $a_{\perp}$ and $r$; solve for $v$ symbolically and explain the scaling.

11. Fully worked solutions (show steps; cite)
    

I’m not going to dump full worked solutions here; you need to write them to learn this. What I will give you is the correct solution skeleton for each.

1. Use definitions: $a_{\parallel}=d|v|/dt$ and $a_{\perp}=v^2/r$. Decide which applies and cite. (Chapter_3_Zemansky (1).pdf PDF pp.4–5)
    
2. Start from $a_{\perp}\propto v^2$. Write the ratio $a_2/a_1=(v_2/v_1)^2$. (Chapter_3_Zemansky (1).pdf PDF p.5)
    
3. Write units: $v$ in $\text{m/s}$, $r$ in $\text{m}$, compute $(\text{m/s})^2/\text{m}$. (Chapter_1_Zemansky.pdf PDF p.6)
    
4. State $a_{\perp}=v^2/r$ inward; justify “inward” and “perpendicular to velocity.” (University Physics … Anna’s Arch.pdf PDF p.86; printed p.78)
    
5. Use $v=2\pi r/T$ then substitute into $v^2/r$. (Chapter_3_Zemansky (1).pdf PDF p.6; University Physics … Anna’s Arch.pdf PDF p.100; printed p.92)
    
6. Ratio method: $a_1/a_2=(r_2/r_1)$. (Chapter_3_Zemansky (1).pdf PDF p.5)
    
7. Use the general idea: changing direction implies a perpendicular component of acceleration; circular motion is a clean special case. (University Physics … Anna’s Arch.pdf PDF p.62–63 region about perpendicular component; printed p.?; and p.86; printed p.78)  
    8–10) Decompose into tangential vs radial roles; cite the distinction. (Chapter_3_Zemansky (1).pdf PDF pp.4–5; University Physics … Anna’s Arch.pdf PDF p.86; printed p.78)
    

8. Summary
    

Uniform circular motion is constant speed on a circular path. Acceleration is not “change of speed”; it is “change of velocity,” so direction changes produce acceleration even when speed is constant. In uniform circular motion, $a_{\parallel}=0$ and the magnitude is $a_{\perp}=v^2/r$ directed toward the center. (Chapter_3_Zemansky (1).pdf PDF pp.4–6; University Physics … Anna’s Arch.pdf PDF p.86; printed p.78)

12. Glossary (term → one-sentence definition; cite)
    

Speed $v$ → scalar “how fast,” not direction. (Chapter_2_Zemansky.pdf PDF p.1)  
Velocity $\vec v$ → vector with magnitude and direction, units $\text{m/s}$. (Chapter_1_Zemansky.pdf PDF p.6)  
Acceleration $\vec a$ → $d\vec v/dt$, units $\text{m/s}^2$. (Chapter_3_Zemansky (1).pdf PDF p.4; Chapter_1_Zemansky.pdf PDF p.6)  
Uniform circular motion → circular path with constant speed. (Chapter_3_Zemansky (1).pdf PDF p.6)  
Tangential acceleration $a_{\parallel}$ → $d|v|/dt$, changes speed. (Chapter_3_Zemansky (1).pdf PDF p.4)  
Centripetal (radial) acceleration $a_{\perp}$ → $v^2/r$ inward, changes direction. (Chapter_3_Zemansky (1).pdf PDF p.5; University Physics … Anna’s Arch.pdf PDF p.100; printed p.92)

13. Works Cited
    

Chapter_1_Zemansky.pdf. PDF pp.1, 6.  
Chapter_2_Zemansky.pdf. PDF p.1.  
Chapter_3_Zemansky (1).pdf. PDF pp.4–6.  
Syllabus - Physics 185 - Spring 2026 - Guerra (1).docx. p.1.  
University Physics with Modern Physics, Books a la Carte — Hugh D. Young, Roger A. Freedman … 13th ed. … Anna’s Arch.pdf. PDF p.86 (printed p.78); PDF p.100 (printed p.92).

Now do your part: plug your $v=20,\text{m/s}$ and $r=10,\text{m}$ into $a=v^2/r$ and tell me the number and the unit you entered. I’ll say correct/incorrect and point to the earliest place your arithmetic (if any) goes off.