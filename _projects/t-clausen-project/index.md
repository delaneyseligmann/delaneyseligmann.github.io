---
layout: post
title: Buckling Strength Enhancement with a Clausen Profile
description: Final project for Advanced Engineering Mechanics course spring 2024
skills: 
- 3D printing
- Wolfram Mathematica
- Instron testing
main-image: /clauseninstron.png
---
___
When tasked with an open-ended project for Advanced Engineering Mechanics, two other students and I drew inspiration from our professor's research. He published a paper investigating the mechanics and shape of the skeletal elements in the marine sponge Tethya Aurantia. The paper found that a tapered shape significantly enhances the spicules' ability to withstand buckling, presenting a unique strategy not commonly observed in man-made structures. The Strongyloxea (silica rods) most closely resemble a Clausen column.
<br>
<br>
Hence, the basis for our project: How does the critical buckling load of a Clausen column compare to that of a traditional cylindrical column? 
<br>
<br>
While my partners focused on CAD models for 3D printing, I worked with stress equations and evaluated the limitations of Lagrange's original determination of the cylinder as the strongest column. The Clausen column was determined to be 33% stronger than the cylindrical column.

{% include image-gallery.html images="clausencolumn.png, clauseninstron.png" height="400" %} 

To test this computation, we used 3D-printed columns and a 500N Instron. My partners led the testing endeavor while I processed the Instron data in MATLAB. We found the Clausen column was approximately 17% stronger than the cylindrical column but less rotation-resistant.
<br>
To finish our presentation, we performed a demo using buckets of sand and a 3D-printed setup to demonstrate the Clausen's superior buckling resistance, successfully proving our findings. 

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQxtZPiXG_SY-c0NNOenKvvZDMyFjUGrK-RwXsuH-Oo0Ff8UNR7dStumwvsNIK6mroH1CZNn9UaWFnC/pubembed?start=false&amp;loop=false&amp;delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true" sandbox="allow-same-origin allow-scripts allow-pointer-lock allow-forms allow-popups allow-popups-to-escape-sandbox"></iframe>
