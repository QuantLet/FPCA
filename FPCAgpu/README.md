<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: FPCAgpu

Published in: Functional Principal Component Analysis for Derivatives of High-Dimensional Spatial Curves

Description: 'Computes low dimensional decomposition of derivatives for surfaces using automatic bandwidth selection.'

Keywords: simulation, empirical, FPCA, surface, derivative, density

See also: FPCASimulation, FPCAepan, FPCAmultiloc, FPCAsimulate_input, FPCAindividual, FPCAvariance

Author: Heiko Wagner

Submitted: Maria Grith

Input: 

- L: Number of Dimensions

- Fc: Triscattered interpolated curves

- x1minc: Min x1 value

- x2minc: Min x2 value

- x1maxc: Max x1 value

- x2maxc: Max x2 value

- cgridx: Joined Grid x1

- cgridy: Joined Grid x2

- c5unil: Moneyness Axis

- c2unil: Maturity Axis

- c3unil: Observations with error

- c3unilr: Observations wo. error

- N: Number of Days

- mx: Output Grid Monetary axis

- my: Output Grid Maturity axis

- method: Computation method (1=M0, 2=Md)

- comp: GPU or No GPU (experimental, GPU usually much slower)

- sigma: Estimated or ture sigma

- app: Application (1=Yes, 0=No) effects diagonal correction

Output: 

- hX2r: Low dimensional decomposition using L Dimensions

- V2a: Eigenvectors of second derivative

- loadsa: Corresponding loadings

- Meansmo2b: Mean curve

- Da: Eigenvalues

```
