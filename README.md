# numericalHeatPDE
Using the explicit finite difference method algorithm to numerical solve the 1-D heat equation

The algorithm used to solve this hyperbolic PDE utilized the explicit finite difference method. The first time derivative, second spatial derivative and the first spatial derivative were broken down into their i-th and k-th components at each iterative step. This PDE was similar to the standard heat equation except that it took into account the first spatial derivative with a constant, b. This meant that the first time derivative depended not only on the concavity value of the second spatial derivative but the slope of the first spatial derivative. This is evident in the output graph where in the areas of positive slope in the initial condition the first-time derivative step extends farther out and conversely in the areas of negative slope in the initial condition the first time derivative does not extend as far. 

Graphics do not display through GitHub, contact for full file.
