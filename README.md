# Accounting for network noise in graph-guided Bayesian modeling of structured high-dimensional data (Biometrics, 2024)
Wenrui Li, Changgee Chang, Suprateek Kundu & Qi Long

## Abstract 

We propose a graph-guided Bayesian modeling framework to account for network noise in regression models involving structured high-dimensional predictors. Specifically, we use 2 sources of network information, including the noisy graph extracted from existing databases and the estimated graph from observed predictors in the dataset at hand, to inform the model for the true underlying network via a latent scale modeling framework. This model is coupled with the Bayesian regression model with structured high-dimensional predictors involving an adaptive structured shrinkage prior. We develop an efficient Markov chain Monte Carlo algorithm for posterior sampling.

## Code Description
- MCMC_noisy.cpp contains the main function for the model NoiseSH.     
- rcpp_pgdraw.cpp, rcpp_pgdraw.h and rcpp_pgdraw.o contain the collection of supporting functions for the MCMC_noisy.cpp.
- data.RData contains a sample of synthetic data.
- runMCMC.R contains the sample code for the model implementation and model selection. 

## Link
[Original paper](https://academic-oup-com.proxy.library.upenn.edu/biometrics/article/80/1/ujae012/7628584)
