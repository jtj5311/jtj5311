---
layout: page
title: "Rigid Motion"
permalink: /rigidmotion/
---

# Visualization of Euler's Equations of Motion

This demo represents 100 simulated paths of Euler's equations of motion with
random initial conditions.

A simplified explanation: the way an object rotates in space can be determined
by knowing its angular momentum vector. Euler's equations of motion then
provide a differential equation that explains how the angular momentum vector
changes with respect to time, and by solving that equation, we can fully 
describe how an object rotates in space. This visualization was created 
by taking 100 random points on the sphere as initial angular momentum vectors
and then using Euler's equations of motion to determine how the angular
momentum vector would change over time. This gives the distinct elliptical
paths seen below. Note that the cones/arrows represent the direction the 
angular momentum vector is moving when the angular momentum vector is 
located at the base of the cone. Bright cones indicate where the angular
momentum is changing quickly and dark cones indicate that where the 
angular momentum is changing slowly.

{% include rigid1.html %}

In this second figure, I used the previous data to train a model to produce 
these paths. On the figure, I have drawn both the "true" path and the path
produced by model, and for each path, these are both drawn in the same color.
Visually, there is generally extremely good agreement between the true 
and predicted paths, but one extremely interesting place to look at is 
around some of the poles of the sphere.

Around these poles, my model received relatively little data to teach it how to 
generate solutions there, and the quality of the model breaks down there. In 
fact, one lavendar path especially close to the pole demonstrates a 
"bifurcation" where the true and predicted paths split off from each other 
and go in different directions. This is because the model was unable 
to correctly predict the path here, and the solution behavior near the poles 
is very sensitive to slight changes.

{% include rigid2.html %}