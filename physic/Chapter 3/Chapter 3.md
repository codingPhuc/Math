

Spine quick links:  
Scope you gave (course map): Chapter 3 with E 3, 9, 10, 16, 24, 25, 27, 29, 31, 33 and P 67.

Abbrev (for dense navigation):  
Z3 = Chapter_3_Zemansky (1).pdf; Z2 = Chapter_2_Zemansky.pdf; Z1 = Chapter_1_Zemansky.pdf; YF = University Physics (Young/Freedman) 13e.

0. One-line “what this chapter is about” (Layer 1 preview)  
    Vector kinematics in 2D/3D: define r, v, a; then specialize to projectile motion, circular motion, and relative velocity.
    

A) Layer 1 — Logic Layer (Big picture + structure)

1. Chapter “map of maps”  
    Keywords / phrases (purpose + flow)
    

- position vector r⃗, displacement Δr⃗
    
- average vs instantaneous velocity v⃗
    
- average vs instantaneous acceleration a⃗
    
- component form (x, y, z) and unit vectors î, ĵ, k̂
    
- constant-acceleration kinematics in 2D
    
- projectile motion (ax = 0, ay = ±g)
    
- circular motion: tangential a∥ and centripetal a⊥
    
- period T, uniform vs nonuniform circular motion
    
- relative velocity with double-subscript bookkeeping
    

Simple flow (what leads to what)  
r⃗(t) → Δr⃗/Δt (average v⃗) → limit (instantaneous v⃗) → Δv⃗/Δt (average a⃗) → limit (instantaneous a⃗) → 2D constant-a split → projectile model → circular motion split (a∥ + a⊥) → relative-velocity algebra rules.

2. Section outline (navigation-first)
    

- Z3 §3.1 Position and Velocity Vectors: define r⃗, v⃗, derivative idea
    
- Z3 §3.2 The Acceleration Vector: define a⃗ as dv⃗/dt
    
- Z3 §3.3 Projectile Motion: split x/y; ax = 0, ay = ±g
    
- Z3 §3.4 Motion in a Circle: a∥ from speed-change; a⊥ = v²/r
    
- Z3 §3.5 Relative Velocity: subscript rules; vAB = −vBA; chaining sums
    

B) Layer 2 — Concepts Layer (fine-grained cross-book anchors)

3. Fine-grained concept inventory (35 items; tuned to Z3 + your assigned set)
    

Format: Concept ID. name | Spine anchor | Support anchors | Why you’d open this | Prereqs

C01. position vector r⃗ definition | Z3 §3.1(A) p.1 | Z1 §1.7–1.9 pp.6–11; YF Ch4 “Position… vectors” | what r⃗ means; how components encode location | —  
C02. component form r⃗ = x î + y ĵ + z k̂ | Z3 §3.1(A) p.1 | Z1 §1.8–1.9; YF Ch4 summary | translate geometry ↔ algebra fast | C01, C05  
C03. displacement Δr⃗ points with motion | Z3 §3.1(B) p.2 | Z2 §2.1; Z1 §1.7 | connect “change in position” to vector direction | C01  
C04. average velocity vector v⃗ave = Δr⃗/Δt | Z3 §3.1(B) p.2 | Z2 §2.2; YF Ch4 summary | what average velocity means geometrically | C03  
C05. unit vectors î, ĵ, k̂ | Z3 uses î,ĵ,k̂ | Z1 §1.9 pp.10–11; YF Ch1 “Unit vectors” | notation sanity; prevents sign errors | —  
C06. instantaneous velocity v⃗ = dr⃗/dt | Z3 §3.1 p.3 | Z2 §2.3; YF Ch4 summary | why derivative shows up; “velocity at an instant” | C01  
C07. speed as |v⃗| vs velocity vector | Z3 §3.1 (context) | Z2 §2.3; YF Ch4 projectile pages | distinguish magnitude vs direction object | C06  
C08. average acceleration a⃗ave = Δv⃗/Δt | Z3 §3.2 p.4 | Z2 §2.5; YF Ch4 summary | what “velocity change per time” means | C06  
C09. instantaneous acceleration a⃗ = dv⃗/dt | Z3 §3.2 p.4 | Z2 §2.5; YF Ch4 summary | derivative meaning; direction of a⃗ | C08  
C10. “a⃗ points with Δv⃗” heuristic | Z3 §3.2 p.4 | Z2 §2.5 | quick direction check on sketches | C08  
C11. constant-acceleration vector kinematics (2D) | Z3 “Two-Dimensional Motion with Constant Acceleration” p.7–8 | Z2 §2.6; YF Ch4 summary | the template before projectiles/circles | C06–C09  
C12. split vectors into x/y components | Z3 p.8 | Z1 §1.8; Z2 §2.6 | the “do it twice” trick (x then y) | C02, C11  
C13. time is the coupling parameter | Z3 p.8 | YF projectile section | why you eliminate t to get trajectory | C11  
C14. free-fall acceleration “g downward” | Z3 §3.3 p.9 | Z2 §2.4; YF projectile section | sign conventions; “always downward” clause | —  
C15. projectile assumption ax = 0, ay = ±g | Z3 §3.3 p.9–10 | YF §4.9 | what the model assumes; what it ignores | C12, C14  
C16. projectile component equations (x-motion vs y-motion) | Z3 §3.3 p.10 | YF §4.9 | your “lookup block” for most E’s | C15  
C17. initial velocity decomposition v0x, v0y | implicit in Z3 component use | YF §4.9 eqs for v0 components | convert angle+speed → components cleanly | C12  
C18. trajectory is parabolic (ideal projectile) | not expanded in Z3; implied | YF derivation/statement | “why parabola” in one place | C15–C17  
C19. circular motion: acceleration split (a⃗ = a∥ + a⊥) | Z3 §3.4 p.4–6 | YF §4.10 | what changes speed vs what changes direction | C09  
C20. tangential acceleration a∥ = d|v|/dt | Z3 §3.4 p.5 | YF nonuniform circular | “speeding up/slowing down” component | C19  
C21. centripetal acceleration a⊥ = v²/r inward | Z3 §3.4 p.5 | YF §4.10 or Ch5 circular dynamics | the “must-know” circle formula + direction | C19  
C22. polar-unit-vector form a⃗ = (dv/dt) θ̂ − (v²/r) r̂ | Z3 §3.4 p.6 | YF nonuniform circular | compact vector form; good cross-check | C20–C21  
C23. uniform circular motion definition | Z3 §3.4 p.6 | YF §4.10 | “constant speed on circle” = special case | C21  
C24. period T and v = 2πr/T | Z3 §3.4 p.6 | YF summary | converting between v, r, and “one revolution” | C23  
C25. nonuniform circular motion: a∥ ≠ 0 | Z3 §3.4 p.6 (general) | YF nonuniform circular | keeps you from assuming “only inward” | C20–C21  
C26. direction-change implies acceleration even if speed constant | Z3 §3.4 opening | YF §4.10 opening | the conceptual punchline for circles | C09  
C27. relative velocity notation vAB | Z3 §3.5 p.10–11 | YF relative motion section (Ch4) | what subscripts literally mean | —  
C28. antisymmetry vAB = −vBA | Z3 §3.5 p.10–11 | Z3 explicitly states; YF vector logic | fast sign check | C27  
C29. chaining rule vBE + vAB + vEF = vAE | Z3 §3.5 p.10 | YF relative motion | how to build “velocity addition” safely | C27  
C30. “match last/first letters” bookkeeping | Z3 §3.5 rules (b)-(c) | — | prevents illegal sums like vAB + vCD | C29  
C31. projectile vs free fall: same y-motion | implicit in Z3 split | YF Fig 4.27 discussion | mental model: x and y decouple | C15–C16  
C32. choose origin at initial position | not emphasized in Z3 | YF projectile discussion | reduces constants; makes equations readable | C16  
C33. constant-velocity motion as “a = 0” | used in Z3 projectile x-motion | Z2 §2.4–2.6 | identifies what can be treated linear in t | C09  
C34. component-wise solving as invariant method | Z3 constant-a + projectile | Z2 §2.6; Z1 §1.8 | workflow: solve x(t), y(t), then eliminate t | C12–C13  
C35. “velocity tangent to trajectory” fact | not in Z3 | YF projectile statement | direction reasoning; slope vs v⃗ | C06

4. Crosswalk table (navigation density)
    

(anchors are minimal: section label + page in that source if shown)

|Concept|Spine anchor (Z3)|Support #1|Support #2|Support #3|
|---|---|---|---|---|
|C01 r⃗ definition|3.1(A) p.1|Z1 1.7–1.9 pp.6–11|YF Ch4 summary|—|
|C02 r⃗ components|3.1(A) p.1|Z1 1.8–1.9|YF Ch4 summary|—|
|C03 Δr⃗|3.1(B) p.2|Z2 2.1 p.1|Z1 1.7|—|
|C04 v⃗ave|3.1(B) p.2|Z2 2.2 p.1|YF Ch4 summary|—|
|C05 î ĵ k̂|(used throughout)|Z1 1.9 pp.10–11|YF Ch1 “Unit vectors”|—|
|C06 v⃗ = dr⃗/dt|3.1 p.3|Z2 2.3 p.2|YF Ch4 summary|—|
|C07 speed vs velocity|3.1 context|Z2 2.3|YF 4.9|—|
|C08 a⃗ave|3.2 p.4|Z2 2.5 p.3|YF Ch4 summary|—|
|C09 a⃗ = dv⃗/dt|3.2 p.4|Z2 2.5|YF Ch4 summary|—|
|C10 a⃗||Δv⃗|3.2 p.4|Z2 2.5|
|C11 2D constant-a|(p.7–8 block)|Z2 2.6 p.3|YF Ch4 summary|—|
|C12 split x/y|p.8|Z1 1.8|Z2 2.6|—|
|C13 time couples x,y|p.8|YF 4.9|—|—|
|C14 g downward|3.3 p.9|Z2 2.4|YF 4.9|—|
|C15 ax=0, ay=±g|3.3 p.9|YF 4.9|—|—|
|C16 projectile equations|3.3 p.10|YF 4.9|—|—|
|C17 v0 components|implicit|YF 4.9|Z1 1.8|—|
|C18 parabola|implied|YF 4.9 derivation|—|—|
|C19 a = a∥ + a⊥|3.4 p.4–6|YF 4.10|—|—|
|C20 a∥ = d|v|/dt|3.4 p.5|YF nonuniform|
|C21 a⊥ = v²/r|3.4 p.5|YF 4.10|—|—|
|C22 polar form|3.4 p.6|YF nonuniform|—|—|
|C23 uniform circular|3.4 p.6|YF 4.10|—|—|
|C24 period T, v=2πr/T|3.4 p.6|YF summary|—|—|
|C25 nonuniform circle|3.4 general|YF nonuniform|—|—|
|C26 direction-change ⇒ a≠0|3.4 opening|YF 4.10 opening|—|—|
|C27 vAB meaning|3.5 p.10–11|YF relative motion|—|—|
|C28 vAB = −vBA|3.5 p.10–11|—|—|—|
|C29 chaining sums|3.5 p.10|YF relative motion|—|—|
|C30 matching letters rule|3.5 rules|—|—|—|
|C31 same y-motion|implicit|YF Fig 4.27|—|—|
|C32 origin choice|—|YF projectile discussion|—|—|
|C33 constant v ↔ a=0|3.3 ax=0|Z2 2.6|—|—|
|C34 component workflow|3.3 + p.8|Z1 1.8|Z2 2.6|—|
|C35 v⃗ tangent|—|YF statement|—|—|

C) Layer 3 — Important Details Layer (notation + conditions that matter)

5. High-value details index (22 items)
    

D01. r⃗ is “origin → point P” (not “path length”) → links: C01–C03 | Spine: Z3 3.1(A).  
D02. Δr⃗ direction matches v⃗ave direction → links: C03–C04 | Spine: Z3 3.1(B).  
D03. instantaneous means limit Δt→0 (derivative) → links: C06, C09 | Spine: Z3 3.1, 3.2.  
D04. average vs instantaneous: keep subscripts “ave” straight → links: C04, C08 | Spine: Z3 3.1–3.2.  
D05. a⃗ direction follows Δv⃗, not v⃗ → links: C10 | Spine: Z3 3.2.  
D06. component equations are two independent copies (x and y) → links: C11–C13 | Spine: Z3 p.8.  
D07. time t is what connects x-motion and y-motion → links: C13, C34 | Spine: Z3 p.8.  
D08. projectile model: ax = 0 is the whole point of “horizontal constant v” → links: C15–C16 | Spine: Z3 3.3.  
D09. projectile model: ay = ±g; choose sign by axis convention → links: C14–C16 | Spine: Z3 3.3.  
D10. “g is always downward” (physical) vs “ay sign” (coordinates) → links: C14 | Support: YF summary.  
D11. circular motion: changing direction alone forces a⊥ even if speed constant → links: C26 | Spine: Z3 3.4.  
D12. a∥ changes speed; a⊥ changes direction → links: C19–C21 | Spine: Z3 3.4.  
D13. a⊥ = v²/r points toward center (not outward) → links: C21 | Spine: Z3 3.4.  
D14. uniform circular motion: “constant speed” (so a∥ = 0) → links: C23 | Spine: Z3 3.4.  
D15. period T: time for one revolution → links: C24 | Spine: Z3 3.4.  
D16. v = 2πr/T: don’t confuse with ω = 2π/T (if ω appears elsewhere) → links: C24 | Spine: Z3 3.4.  
D17. relative-velocity meaning: “velocity of first subscript relative to second” → links: C27 | Spine: Z3 3.5(a).  
D18. chaining rule: last letter must match next first letter → links: C30 | Spine: Z3 3.5(b).  
D19. endpoints rule: sum’s subscripts are (first first, last second) → links: C30 | Spine: Z3 3.5(c).  
D20. antisymmetry vAB = −vBA is mandatory (vector) → links: C28 | Spine: Z3 3.5(d).  
D21. common prerequisite: unit vectors + components (Z1 1.8–1.9) → links: C02, C05, C12 | Support: Z1.  
D22. common prerequisite: 1D constant-a kinematics (Z2 2.6) → links: C11, C14–C16 | Support: Z2.

D) Layer 4 — Arbitrary Details Layer (low priority unless needed)

6. Low-yield index (short)
    

L01. polar-unit-vector form with r̂, θ̂ (useful, but often extra) | mark: likely testable | Spine: Z3 3.4 (vector form).  
L02. full kinematic list “v² = v0² + 2 a·Δr” in vector form (nice identity; not always assigned) | mark: skip unless required | Spine: Z3 constant-a block.  
L03. extended projectile “trajectory derivation” (eliminate t explicitly) | mark: skip unless required | Support: YF parabola derivation.

7. Two paths (navigation, not drills)
    

Minimal path (smallest set to get the chapter’s main message)  
C01–C04, C06, C09, C11–C16, C19–C24, C27–C30. (definitions → 2D constant-a → projectiles → circles → relative velocity)

Mastery path (minimal path + completeness/robustness)  
Minimal path + C02, C05, C07–C10, C17–C18, C25–C26, C31–C35.

8. Works Cited (project-folder only)
    

- Chapter_3_Zemansky (1).pdf (Microsoft Word “Chapter 3 Zemansky”): §§3.1–3.5 (pp.1–11).
    
- Chapter_2_Zemansky.pdf: Ch.2 table of contents + §§2.1–2.6 (pp.1–3+).
    
- Chapter_1_Zemansky.pdf: §§1.7–1.9 (Vectors; components; unit vectors) (pp.6–11).
    
- University Physics with Modern Physics (Young, Freedman, et al.), 13th ed (PDF in folder): Ch.4 “Motion in Two or Three Dimensions” (projectile motion, circular motion) and related summaries.
    
- Syllabus - Physics 185 - Spring 2026 - Guerra (1).docx: Chapter 3 assignment list (E’s + P).
- 