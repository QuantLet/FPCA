<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: FPCAloadings

Published in: Functional Principal Component Analysis for Derivatives of High-Dimensional Spatial Curves

Description: Employs a moving window to estimate an AR(1) model for the loadings and to estimate standard deviation of the VDAX, and plots the results.

Keywords: estimation, FPCA, call prices, derivative, density, state price density, risk neutral density, autoregressive, time series

See also: FPCAgpu, FPCAepan, FPCAmultiloc, FPCAsimulate_input, FPCAindividual, FPCAvariance, FPCAexpiration, FPCAcomponents, FPCAloadings

Author: Maria Grith

Submitted: Maria Grith

Input: 
- Results.mat          : Output of FPCAreal_data.m
- vdaxm.txt            : VDAX index time series (same date as the loadings)
- xData.txt            : date time series
- Is.txt               : index for the time series of loadings
- tickdatayear.txt     : tick years

Output: 
- b          : autoregressive coefficients
- s          : standard deviation of the error
- varcorr    : pairwise error correlation
- volv       : standard deviation of the VDAX index

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/FPCA/master/FPCAloadings/FPCA_Figure3.png" alt="Image" />
</div>

