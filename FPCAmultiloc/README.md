<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: FPCAmultiloc

Published in: Functional Principal Component Analysis for Derivatives of High-Dimensional Spatial Curves

Description: Estimates second partial derivative of the curves using local polynomial regression.

Keywords: simulation, empirical, local polynomial surface estimator, derivative, nonparametric

See also: FPCAgpu, FPCASimulation, FPCAvariance, FPCAsimulate_input, FPCAindividual, FPCAepan

Author: Heiko Wagner

Submitted: Maria Grith

Input: 
- X1 : x1 coordinate
- X2 : x2 coordinate
- Y  : function value
- x1 : x1 output coordinate
- x2 : x2 output coordinate
- h1 : bandwidth in x1 direction
- h2 : bandwidth in x2 direction
- p  : degree of polynomial

Output: 
- fit0  : Smoothed curves
- fit1  : Smoothed 1. derivative
- fit2  : Smoothed 2. derivative
- fit3  : Smoothed 3. derivative
- W0    : nonderivative estimate
- W1    : first derivative estimate
- W2    : second derivative estimate
- W3    : third derivative estimate

```
