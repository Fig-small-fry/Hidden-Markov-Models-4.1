# Hidden-Markov-Models

This repository contains tutorials for the inference of transition matrices and observation generating process of Markov chains, Markov Decision Processes (MDPs), and Partially Observable Markov Decision Processes (POMDPs), via Markov Chain Monte Carlo (MCMC) inference of Hidden Markov models (HMM). While other examples for the inference of transition and observation models for Markov chains are available, the tutorials here included extend this inference to the case of Markov chains conditioned on actions, namely MDPs and POMDPs.

The code used in the notebook `HMMs for deterioration process Truncated Normal Process.ipynb` is close to the code used for the POMDP inference in the paper   https://arxiv.org/abs/2212.07933. The differences are represented by the use of real world data, instead of the simulated data of the notebooks, and the slightly different HMM used, fully described in the paper (e.g., Student's t steps instead of the more general Gaussian steps of the notebook).

It is suggested to go over the notebooks in the order: `HMMs for Markov Chains.ipynb`, `HMMs for MDP and POMDP.ipynb`, and `HMMs for deterioration process Truncated Normal Process.ipynb`.
