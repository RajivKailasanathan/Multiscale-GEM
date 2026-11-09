# Multiscale-GEM
Code repository for the paper: 
From process variables to metabolic states: Hybrid constraint-based analysis for upstream bioprocesses,
Rajiv Kailasanathan, Abhishek Sivaram, Seyed Soheil Mansouri,
Computers & Chemical Engineering, Volume 214, 2026, 109828, ISSN 0098-1354, https://doi.org/10.1016/j.compchemeng.2026.109828.

### Hybrid process model for specific rate estimation predictively
DoH2_v3_scaled.py gives the extracted specific rates for high and low yielding batches in the dataset. Use the function at the end to get the estimated latent variables (specific exchanges) for required batch numbers
### Sampling the constrained genome scale model
Metabolic_Flux_Sampling_connectors stores the sampled data. Use the computed specific exchanges n the previous step
### Analysis
Sampling_Analyses Analyses the flux distributions between high and low yielding data.
