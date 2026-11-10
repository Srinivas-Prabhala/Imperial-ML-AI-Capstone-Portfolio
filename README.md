---
marp: true
---

## Imperial College – Machine Learning & Artificial Intelligence Capstone

### Bayesian Black-Box Optimisation (BBO) Project

**Author:** Srinivas Prabhala
**Programme:** Imperial College Professional Certificate in Machine Learning and Artificial Intelligence
**Year:** 2026

### 1. Project Overview

> This repository documents the Bayesian Black-Box Optimisation (BBO) capstone project undertaken as part of the Imperial College Professional Certificate in Machine Learning and Artificial Intelligence.

> The project investigates optimisation strategies for eight unknown objective functions using Gaussian Processes (GPs) and acquisition functions, including:

* Expected Improvement (EI)
* Probability of Improvement (PI)
* Upper Confidence Bound (UCB)

> The work documents the progression of experiments, optimisation decisions, weekly query submissions, cumulative observations and performance analysis.

### 2. Project Objectives

* Investigate Gaussian Process surrogate modelling for black-box optimisation.
* Implement and evaluate different acquisition functions.
* Explore the balance between exploration and exploitation.
* Develop function-specific optimisation strategies.
* Analyse cumulative experimental results and optimisation performance.
* Document the methodology and implementation transparently.

### 3. Project Documentation

> The following documents provide the supporting documentation for the capstone:

| Document                                                         | Description                                                                 |
| ---------------------------------------------------------------- | --------------------------------------------------------------------------- |
| [Query Submissions – Module 21.1](21.1_Query_Submissions.md)     | Record of submitted optimisation queries.                                   |
| [Strategy Reflection – Module 21.1](21.1_Strategy_Reflection.md) | Reflection on optimisation decisions and strategy.                          |
| [Dataset Datasheet – Module 21.2](21.2_Dataset_Datasheet.md)     | Dataset composition, collection methodology, limitations and intended uses. |
| [Model Card – Module 21.2](21.2_Model_Card.md)                   | Model overview, optimisation strategy, performance and limitations.         |

### 4. Technical Approach

> The project uses Gaussian Process modelling to estimate unknown objective functions and acquisition functions to select promising candidate query points.

> The optimisation strategy evolves through successive experiments, using observed results to inform subsequent query selection and adjustments to the balance between exploration and exploitation.

### 5. Reproducibility and Project Development

> The repository will progressively consolidate:

* Module-wise experimental notebooks.
* Cumulative datasets and weekly observations.
* Gaussian Process implementations.
* Individual acquisition-function implementations.
* Optimisation strategies and candidate-selection code.
* Comparative performance analysis and visualisations.

> The final consolidated implementation will be documented separately from the historical module-wise submissions.

### 6. Project Status

> This repository is being developed progressively as the capstone project advances towards its final submission.

> Historical submissions and supporting documentation are retained to provide traceability of the experimental process and technical decisions.
