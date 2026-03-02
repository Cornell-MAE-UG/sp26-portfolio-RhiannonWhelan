---
layout: project
title: Nutcracker Design
description: design of a feasible nutcracker
technologies: [SolidWorks, Machining]
image: /assets/images/Nutcracker design.JPG
---


Problem Statement and Objective:
Design a simple lever nutcracker that can be used to crack open a macadamia nut. Calculate the necessary dimensions of the nutcracker. 

Constraints and Input Parameters:
Macadamia Nut Average Diameter: 25 mm
Average Human Grip Strength: 367.4 N (Fg)
Average Load to Crack a Macadamia Nut: 2177.364 N (Fl)

Approach to the Problem:

Assumptions:
1. Average human grip strength is the average of average male grip strenth (470.4 N) and average female grip strength (264.6 N), which is 367.4 N rounded to 370 N for simplicity
2. Rounded average load to crack a macadamia nut from 2177.364 N to 2200 N for simplicity
3. Assumed average macadamia nut diameter is 25mm
4. The distance from the joint to the middle of the nut for a standard nutcracker is about 50 mm, so assumed the same for my design (DisAD=50mm)
5. Assumed simple geometry

Calculations/Thought Process:
1. My goal was to find the handle length (DisAB) of the nutcracker
2. In order to do so, I needed to first find the horizontal distance from the joint to a point in between the ends of the two handles on the axis of symmetry (DisAE)
3. So, I took the moment about the joint (point A), and found an equation that related the horixontal distances AD and AE with the input and output forces (Fg= 370 N and Fl= 2200N). Equation: DisAD* Fl = DisAE* Fg
4. I then used that equation to calculate the Mechanical Advantage: MA = Fout/Fin = Fl/Fg= DisAE/DisAD=2200N/370N
= 5.95
5. Using this value of mechanical advantage and my assumed value for DisAD=50mm, I solved for DisAE. DisAE= 5.95 * DisAD. DisAE= 5.95 * 50mm = about 300 mm
6. Now that I had this distance, I knew I needed to find the vertical distance from the point in between the ends of the two handles on the axis of symmetry to the point on the end of the handle (DisBE). My strategy was to use this distance along with the already calculated DisAE in the pythagorean theorem to calculate DisAB. 
7. In order to find DisBE, I used the method of similar triangles. This method gave me the equation that the distance from the joint to the center of the nut (DisAD)/ distance from the center of the nut to where it touched the nutcracker (or in other words the radius of the nut) DisND = DisAE/ unknown distance DisBE. So, DisAD/DisND= DisAE/ DisBE---> 50mm/12.5mm = 300 mm/DisBE. Solving for DisBE foudn that DisBE= 75mm. 
8. Now that I had DisAE = 300mm and DisBE = 75mm, I was able to use the pythagorean theorem to find DisAB. I found that the handle length of my nutcracker (DisAB) = 309.23 mm

Usability of Nutcracker:

