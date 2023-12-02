# Bayesian-inference
## Creating model for tumor growth prediction

fit_bayes.ipynb defines a model for predicting the growth of tumors in patients. The model is designed using the Turing.jl probabilistic programming framework.
It aims to estimate the parameters of the Gompertz model for tumor growth by fitting the model to patient data.

## Dependencies

- [Turing.jl](https://turing.ml/): Probabilistic programming framework for Julia.
- [DifferentialEquations.jl](https://diffeq.sciml.ai/stable/): Library for solving differential equations in Julia.
