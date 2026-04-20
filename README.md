# Machine Learning & Dynamical Systems – Bachelor’s Thesis

This repository contains my bachelor’s thesis on data-driven modeling of nonlinear dynamical systems.

## Topic
- Neural Ordinary Differential Equations (Neural ODEs)
- Reservoir Computing (RC)
- Application: bistable Duffing system

## Focus
- Generalization beyond the observed phase space
- Recovery of basin-of-attraction structure from limited data
- Effect of noise and sampling interval on model performance

## Main findings
Both Neural ODEs and Reservoir Computing generalize well beyond the region of phase space represented in the training data, successfully recovering essential features of the global basin structure. In the Reservoir Computing setting, we additionally identify a non-monotonic dependence on sampling, showing that there exists an optimal time-step for robustness to noise. Denser sampling does not necessarily improve performance.

## Thesis
See `thesis.pdf`
