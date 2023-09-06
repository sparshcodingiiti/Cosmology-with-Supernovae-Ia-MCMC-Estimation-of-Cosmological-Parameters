# Cosmology with Supernovae Ia

This project focuses on estimating cosmological parameters from supernova Ia data using various statistical techniques. The repository contains three main files, each dedicated to a specific aspect of the analysis.

## MCMC Estimation of Cosmological Parameters


The `mcmc_estimation.py` file contains the code for performing Markov Chain Monte Carlo (MCMC) simulations to estimate cosmological parameters from supernova Ia data. Key features of this module include:

- Implementation of the flux-luminosity relation to calculate Luminosity Distance (DL) in the context of Big Bang cosmology.
- Utilization of a sophisticated fitting formula for DL to enhance computational efficiency and accuracy.
- Exploration of various proposal distribution sizes to analyze their impact on chain convergence and efficiency.
- Computation of average parameter values under the posterior distribution, providing insights into likely parameter values.

## Metropolis-Hastings (MH) MCMC


The `mh_mcmc.py` file focuses on Metropolis-Hastings (MH) MCMC, a variant of the MCMC algorithm. It explores the following:

- Implementation of MH MCMC for parameter estimation from supernova Ia data.
- Examination of the MH acceptance probability and its variations with different proposal distribution sizes.
- Assessment of the performance of MH MCMC in comparison to standard MCMC.

## Gelman-Rubin Statistic and Importance Sampling


The `gelman_rubin_importance_sampling.py` file introduces the Gelman-Rubin Statistic and Importance Sampling to the analysis:

- Calculation of the Gelman-Rubin Statistic to assess the convergence of MCMC chains and determine chain length requirements.
- Implementation of Importance Sampling to sample from a different distribution, demonstrating its application in parameter estimation.
- Visualization and analysis of results obtained using these statistical techniques.
