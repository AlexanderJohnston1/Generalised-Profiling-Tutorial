# Generalised Profiling Tutorial
This repository contains Jupyter Notebooks that illustrate the use of generalised profiling as a method of inference for systems of ordinary differential equations (ODEs). 

The folder "Generalised profiling" contains examples of using the method to conduct inference. Four ODE models are examined: the Lotka-Volterra model of predator-prey dynamics, a model of linear mass action, the Brusselator model of oscillatory chemical reactions, and a model of nonlinear mass action. These codes were written by Alexander Johnston.

The folder "Markov Chain Monte Carlo" contains codes used to analyse the same models using a Markov Chain Monte Carlo (MCMC) algorithm. These codes were written by Alexander Johnston.

The folder "Convergence demonstrations" shows the convergence properties of the generalised profiling method for each of the models. These codes were written by Alexander Johnston and James S. Bennett. 

The file "Confidence intervals" shows the code used to determine appropriate values of the generalised log-likelihood function to generate confidence sets at a specific confidence level. This code was written by Alexander Johnston.

All codes are written in Julia and were used to generate the figures and results in the paper "Solution-free parameter inference for differential equation models".
