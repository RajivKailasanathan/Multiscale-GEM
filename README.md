# Multiscale-GEM
Code repository for the paper: 'Bridging Reactor-Scale Observations With Intracellular Fluxes: A Hybrid Framework For Constraint Based Flux Analysis Towards Process Monitoring'

### Hybrid process model for specific rate estimation predictively
DoH2_v3_scaled.py gives the extracted specific rates for high and low yielding batches in the dataset. Use the function at the end to get the estimated latent variables (specific exchanges) for required batch numbers
### Sampling the constrained genome scale model
Metabolic_Flux_Sampling_connectors stores the sampled data. Use the computed specific exchanges n the previous step
### Analysis
Sampling_Analyses Analyses the flux distributions between high and low yielding data.
