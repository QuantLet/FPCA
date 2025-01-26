<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: FPCAsimulation

Published in: Functional Principal Component Analysis for Derivatives of

Description: Starts a simulation for varying number of curves and observations per curve for repeated samples, and performs a comparison of the methods.

Keywords: simulation, FPCA, surface, derivative, density

See also: FPCAgpu, FPCAepan, FPCAmultiloc, FPCAsimulate_input, FPCAindividual, FPCAvariance

Author: Heiko Wagner

Submitted: Maria Grith

Input: 
- reps : Repetitions +1
- Nn   : Vector of to simulate curves per trail
- Tt   : Vector of to simulate observations per curve

Output: 
- meanM : Matrix of Mean MSE with entries for each value of Nn and Tt
- varV  : Matrix of variances of MSE with entries for each value of Nn and Tt
- medM  : Matrix of medians of MSE with entries for each value of Nn and Tt
- iqrM  : Matrix of IQR of MSE with entries for each value of Nn and Tt

```
