# Multi Parameter Simulation

This folder contains single parameter estimation code for four borrowing methods (CP, RMP, NOBO, FUBO) using both Bayesian and MLE estimation approaches.

## Methods:
- CP (Commensurate Prior)
- RMP (Robust Mixture Prior) 
- NOBO (No Borrowing)
- FUBO (Full Borrowing)

Each method is implemented with both Bayesian and MLE estimation techniques.

## Parameter Settings:
**These files run compatible scenarios by default.**

For different scenarios, change the parameter values:
- **Compatible**: β₀ₕ = β₁ₕ = β₀c = β₁c = 1  
- **Incompatible 1**: β₀ₕ = 5, β₁ₕ = β₀c = β₁c = 1 (only intercept incompatible)
- **Incompatible 2**: β₁ₕ = 5, β₀ₕ = β₀c = β₁c = 1 (only slope incompatible)  
- **Incompatible 3**: β₀ₕ = β₁ₕ = 5, β₀c = β₁c = 1 (both parameters incompatible)

No other code changes needed - just modify the parameter settings at the beginning of each file.
