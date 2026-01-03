# Droplet Spreading Law Analysis (Python)

This project analyses experimental droplet spreading data to determine the relationship between contact line speed and contact angle.

Experimental radius–time data from multiple runs are processed to compute mean values and uncertainties, which are then propagated to derived physical quantities.

## What was done
- Combined multiple experimental runs to compute mean radius and standard deviation
- Propagated measurement uncertainty to droplet height and contact angle
- Computed contact line speed using numerical differentiation
- Fitted competing spreading laws (Cox–Voinov and de Gennes)
- Performed weighted regression and nonlinear curve fitting
- Compared models using residuals and chi-squared statistics

## Key result
Statistical analysis indicates that the de Gennes spreading law provides a better fit to the experimental data than the Cox–Voinov law.

## Technologies
Python, NumPy, SciPy, Matplotlib

## Relevance
This project demonstrates data analysis, uncertainty propagation, model fitting, and quantitative comparison of competing models, relevant to data analysis and scientific computing roles.
