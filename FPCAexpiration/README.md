<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: FPCAexpiration

Published in: Functional Principal Component Analysis for Derivatives of High-Dimensional Spatial Curves

Description: Displays the effect of the expiration date on the level of estimated loadings corresponding to the second component.

Keywords: estimation, FPCA, call prices, derivative, density, state price density, risk neutral density, functional component, loadings

See also: FPCAgpu, FPCAepan, FPCAmultiloc, FPCAsimulate_input, FPCAindividual, FPCAvariance, FPCAexpiration, FPCAcomponents, FPCAloadings

Author: Maria Grith

Submitted: 17.12.2016

Input: 
- Results.mat          : Output of FPCAreal_data.m
- xData.txt            : date time series
- Is.txt               : index for the time series of loadings
- tickdatayear.txt     : tick years

Output: It plots the call price strings on two consecutive trading days, as well as the second estimated non-orthonormal functional component of the state price density (SPD) and the corresponding loadings

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/FPCA/master/FPCAexpiration/FPCA_Figure1.png" alt="Image" />
</div>

