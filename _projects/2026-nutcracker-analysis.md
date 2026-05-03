---
layout: project
title: Nutcracker Deflection Analysis
description: Class assignment for ENGRD 2020
technologies: [Goodnotes]
image: /assets/images/Nutcracker Final.png
---


As part of an earlier class assignment, I was tasked with designing a nutcracker, and eventually replacing the force applied by us with that of an linear actuator. Previously, we ignored beam bending and deflection as we had not learned of it yet. However, now that we have learned it, it is time to analyze my previous design.

This is how I solved the problem:

Find: I have to find the point of maximum deflection, and a mass-efficient cross section that resists bending

Given: For my assumptions I used the previously assumed details such as the nut laying at rest on length L2, while L1 was where the force supplied by the linear actuator was. Along with design assumptions, a force required to crack a nut of 490 lb. However, in order to analyze the beam bending, we have need more details, which is why I assumed the material used to create the nut cracker is structural steel.

Now that I made these assumptions, I began to diagram my nutcracker and drew a free body diagram which showed the lengths, members, and location of forces. I then decided to draw cross sections within my nut cracker to find the deflection equation. After finding the internal moment equations for both segments, I decided to double integrate to obtain the equations with the two constants of integration. I used the set boundary conditions such that the pivot and nut had zero deflection. This allowed me to obtain my deflection equation, and with it I saw that the maximum deflection occured at where the linear actuator supplied the force, which was at the end of the handle. I then solved for the minimum momnent of inertia to obtain a maximum deflection of two percent the total length. The required moment of inertia for the beam to bend only two percent was 0.0094 in^4, Then I designed a cross section fitting for the nutcracker that is not only stiff enough, but also mass-efficient. This resulted in my final design being a hollow square with the outer diameter of 1 inch and a inner square length of 0.75 inch which results in a moment of inertia of 0.0570 in^4, almost five times the required moment of inertia.
