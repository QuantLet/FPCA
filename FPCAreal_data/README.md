<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: FPCAreal_data

Published in: 'Functional Principal Component Analysis for Derivatives of High-Dimensional Spatial Curves'

Description: 'Estimates state price densities (SPD) from a sample of discretely observed and noisy call price curves at different time to maturity and strike prices. Use FPCA decomposition of the dual covariance matrix and estimate functional components of the SPD and their corresponding loadings.'

Keywords: estimation, FPCA, call prices, derivative, density, state price density, risk neutral density

See also: FPCAgpu, FPCAepan, FPCAmultiloc, FPCAsimulate_input, FPCAindividual, FPCAvariance, FPCAexpiration, FPCAcomponents, FPCAloadings

Author: Maria Grith

Submitted: Maria Grith

Input: 

- ExpirationDates.txt: Expiration dates for the call prices

- dax_index.txt: DAX 30 index time series

- vdax.txt: VDAX index time series

- IRs.dat: EURIBOR interest rates multivariate time series

- C_2002.txt: Call prices 2002

Output: 

- hX2b: Low dimensional SPD curves (using L dimensions)

- V2b: Second derivative w.r.t. moneyness of the eigenfunctions

- loadsb: Loadings corresponding to the eigenfunction

- Meansmo2bb: Mean curve

- Db: Eigenvalues

- mx: Output Grid Monetary axis

- my: Output Grid Maturity axis

```
