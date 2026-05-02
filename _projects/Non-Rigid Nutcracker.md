---
layout: project
title: Non-Rigid Nutcracker
description: 
technologies: 
image: /assets/images/Hw 12 Nutcracker photo.jpg
---
a)
Assumptions:
- linear elastic material
- the pin is rigid
- the handles are uniform non-rigid beams
- normal force from nut (FN), actuator force (FA) and reaction force from pin (RA) are perpendicular
- deflection is small
- linear actuator acts like a roller (only vertical forces, acts at L)
- assume scenario like #5 in Appendix E
- assume stainless steel (cold rolled) material, E=193 GPa

Find where the max deflection occurs:
xm= sqrt((L^2-a^2)/3)
where a= distance to nut and L=total handle length
From HW 4 solutions: L= 11.59 cm, a= 4 cm, nut height= 2 cm, and linear actuator height = 13 cm
so, xm = 6.28 cm from the pin

b)

want to design the beam s.t max deflection < 0.02L:
from appendix E #5, max defl = (-P*a*(L^2-a^2)^3/2)/9sqrt3 *E*I*L

used FBD to find FN:
Rx=0
Ry+FN+FA=0 where FA= 169 lb
--> FN= -489.7 lb

Plugged values for FN, a, and L in max deflection formula
--> max def = 0.06207/EI

and max defl < 0.002318 m

so, 0.06207/EI < 0.002318 
--> I > 1.388 X 10^-10 m^4 where I = bh^3/12 for a rectangular cross section

for the design, want as much material away from the neutral axis (big h, small b)
tried b= 0.004 m
--> 0.004m *h^3/12 = 1.388 X 10^-10 --> h=0.00747m
round up to 0.008m=h

Final Design: 
Material: stainless steel (cold-rolled) with E=193 GPa
cross section: b=4mm, h=8mm






