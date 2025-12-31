---
layout: post
title: Optimized Falcon 9 Ascent Trajectory
description: Final project for Advanced Numerical Methods course fall 2025
skills: 
- Python
- Trajectory optimization
main-image: /trajectory.png
---
___
In my senior fall, I took Advanced Numerical Methods for Data, Simulation, and Optimization. For the final project, I challenged myself to combine the course material with my growing fascination with Guidance, Navigation, and Control. This resulted in my attempt to optimize the trajectory of SpaceX's Falcon 9 rocket to low Earth orbit. LEO was chosen because the majority of satellites populate this orbit. 
<br>
The optimization was conducted in Python, utilizing physical equations like the Tsiolkovsky equation, exhaust velocity relation, and aerodynamic drag. After making the necessary assumptions, the Runge-Kutta method was employed, computing intermediate steps to estimate the slope of the solution. 
<br>
The resulting ascent profile was compared to a Brachistochrone curve. The Brachistochrone curve represents the fastest path between two points under gravity, making it a useful theoretical benchmark for optimal ascent trajectories. 

{% include image-gallery.html images="F9graph.png, rocketgraph.png" height="400" %} 

The resulting velocity was short of the necessary velocity to remain in LEO (7.8km/s) but followed a similar ascent to the Brachistochrone profile. I was unable to accommodate a stage separation successfully, but I hope to improve upon the optimization as a passion project moving forward.

<iframe width="640" height="360" src="https://docs.google.com/presentation/d/e/2PACX-1vTPWw4MnpcPdx7j1dGheG1igXoeds8F3oYFRkrnFFQ8pIONfq3QiGJ5NSi5Pq6iaViJvZt_TNKNI5Sd/pubembed?" sandbox="allow-same-origin allow-scripts allow-pointer-lock allow-forms allow-popups allow-popups-to-escape-sandbox"></iframe>
