---
layout: post
title: Thermodynamics Design Competition
description:  Final project for sophomore thermodynamics course spring 2023
skills: 
- Thermal systems development
- Design iteration
- Cost analysis
main-image: /interimthermo.png
---

---

To wrap up our sophomore year Thermodynamics course, a group of three other students and I were tasked with designing and evaluating a fossil-fuel-free utility network for a hypothetical new district being built in a large city. The mission was to design a process providing chilled and hot water to buildings, with an additional option to provide steam to an industrial park for process heating. We were given pressure, temperature, and volume rate requirements in addition to electricity and water prices. Professor Hurt also provided us with a proprietary refrigerant, "Hurt-o-Therm", and supplied us with its thermodynamic properties.
With a broad project scope, I proposed starting with our textbook's example of a vapor-compression refrigeration cycle, using Hurt-O-Therm as the refrigerant. The focus was primarily on creating the chilled water first, then designing the rest of the components for the hot water around that portion. To start, the economic component of the process was neglected, and the goal was to create a functional system that produced all required products in their entirety. As a group, we iterated through multiple designs, testing which one yielded the most favorable result. 
  Midway through the project, we submitted a proposal and received feedback from a TA. 

{% include image-gallery.html images="interimthermo.png" height="400" %} 

After receiving feedback from our first design, the main portion we sought to optimize was the two-stage transfer of heat to generate the optional saturated steam. The process of transferring heat twice is inefficient, so we decided to take the extra heat in the Hurt-O-Therm and split the stream. This split decreased the capital costs of the project while retaining the excess steam generated and optimizing the use of the Hurt-O-Therm in our design.

{% include image-gallery.html images="thermocycle.png" height="400" %} 

As a result of the alterations made to our final design, the area of the heat exchangers decreased, and thus capital cost went down from $11,243,774.60 to $10,437,692.60. Additionally, the amount of steam that was produced slightly increased and, in turn, increased the gross revenue by a small amount. Overall, the effect that this improvement had on our design was an increase in net present value to $422,191,963.57. Since both iterations of our design yielded an NPV term above zero, with no thermodynamic laws broken, they are both feasible and profitable designs for a fossil-fuel-free urban utility network in the long run. 
<br> 
This was a collaborative effort. Two group members focused on the economic side of the project, while another member and I contributed the majority of the thermodynamic calculations and diagram labeling.
<br>
>Together, our group of 4 designed the most efficient and profitable thermal system in the 88-person class. 
