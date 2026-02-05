# Computational Statistic - GLM and Bayesian Inference
This project explores frequentist and Bayesian inference for Generalized Linear Models (GLMs),
with a focus on logistic and Poisson regression.

The goal is to compare Maximum Likelihood Estimation (MLE) and Bayesian inference when
closed-form solutions are not available, emphasizing algorithmic implementation and
uncertainty quantification.

## Methods
- Logistic and Poisson regression within the GLM framework
- Parameter estimation via Fisher Scoring / Newton–Raphson
- Bayesian inference using Metropolis–Hastings within Gibbs MCMC
- Comparison between frequentist and Bayesian estimates

## Implementation
All algorithms are implemented from scratch in Python.

The Bayesian approach relies on MCMC sampling from the posterior distribution, with
convergence and efficiency assessed through:
- Trace plots
- Autocorrelation functions (ACF)
- Acceptance rates

## Repository Structure
- `GLM_Bayesian_Inference.ipynb`: main notebook containing implementation, analysis, and results  
- `Data`: folder containing the datasets used in the project, along with a brief description of each dataset  
- `report.pdf`: full academic report with theoretical derivations and detailed discussion


