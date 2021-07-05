# introduction_to_statistical_inference
This is a half-day course aimed at providing a short introduction to statistical inference. In it, we cover:

- why do we need statistics?
- how regression models work and different approaches for fitting these models
- model diagnostics for linear regression
- estimating uncertainty in predictions using bootstrap sampling
- can statistics help to determine causation?

The lecture notes for this course are [here](./presentations/introduction_to_statistical_inference.pdf).

The problem sets for this course mirrors the lecture content and works through a regression analysis of wine data ([see here for an explanation of the dataset](https://www.kaggle.com/zynicide/wine-reviews)):

- [*regression*](./problem_sets/wine_regression.ipynb) invites participants to perform linear regressions on the wine data to determine the relationship between wine quality and price
- [*estimation methods*](./problem_sets/wine_estimation_methods.ipynb) is optional as the material is more mathematical; in this problem set, participants write their own methods for estimating parameters
- [*model assumption checking*](./problem_sets/wine_assumptions.ipynb) invites participants to probe whether the assumptions of the linear regression model are satisfied
- [*estimate uncertainty*](./problem_sets/wine_uncertainty.ipynb) asks users to determine estimate uncertainty using bootstrap sampling

The answers for this problem set (written in Python) are available [here](./problem_sets/answers/wine.ipynb).
