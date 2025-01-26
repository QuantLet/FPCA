<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: FPCAindividual

Published in: Functional Principal Component Analysis for Derivatives of High-Dimensional Spatial Curves

Description: Estimates smooth second partial derivative for each curve using local polynomial regression using individual bandwidths.

Keywords: simulation, empirical, FPCA, surface, derivative, density

See also: FPCASimulation, FPCAepan, FPCAmultiloc, FPCAsimulate_input, FPCAgpu, FPCAvariance

Author: Heiko Wagner

Submitted: Maria Grith

Input: 
- L          : Number of Dimensions
- Fc         : Triscattered interpolated curves
- x1minc     : Min x1 value
- x2minc     : Min x2 value
- x1maxc     : Max x1 value
- x2maxc     : Max x2 value
- cgridx     : Joined Grid x1
- cgridy     : Joined Grid x2
- c5unil     : Moneyness Axis
- c2unil     : Maturity Axis
- c3unil     : Observations with error
- c3unilr    : Observations w/o error
- N          : Number of Days
- Tmon       : Observations  Monetary axis
- Tmat       : Observations Maturity axis

Output: 
- hX2r       : Smooth derivative estimate using LP
- mx         : Grid x1
- my         : Grid x2

```
