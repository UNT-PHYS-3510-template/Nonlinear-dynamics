# Nonlinear Dynamics and Chaos
Assignment 1: (from Project 5.1 of the textbook) There is a period-3 stable window embedded in the chaotic region of the logistic map around ~0.96. Why does it not appear at smaller values of r? Explore this and related questions of the period-3 orbit.
* In the logistic_map.ipynb Jupyter notebook or in a separate Python file, plot the map function $f^3(x)$ for $r=0.959$, together with the straight line $y=x$. Find the intersections between the two curves. How many fixed points do you see? Which ones are stable?
* Repeat the above analysis for $r=0.95$. Are there any stable fixed points?
* Decrease $r$ from 0.959. At each $r$ generate a power spectrum of the map iterates after discarding transients. What is the lower limit of $r$ when no period-3 cycles exists? Compare your results with $(1+\sqrt{8})/4\approx 0.9571$

Assignment 2: Simulate a non-linear driven oscillator as a function of the intensity of the driving force. 
* In the driven_oscillator.ipynb notebook, implement a function for the righthandside of the differential equations of a pendulum subject to a linear drag and an oscillatory driving force.
* Following the examples in the book, simulate the driven oscillator for a $F_d=0.7$ and $1.1$, starting from slighlty different initial conditions. Plot the difference in angular velocity between two different initial conditions as a function of time (same as in Figure 5.13 of the textbook).
* For the chaotic motion at $F_d=1.1$, generate a Poincaré map, by sampling at regular time intervals (fractions of the period of the driving force).  
