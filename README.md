# Critical Soil Test Values and Fertilizer Recommendations for Corn

This repository contains the code and example dataset for the soil phosphorus correlation and calibration methods described in:

**Critical Soil Test Values and Fertilizer Recommendations for Multiple Soil Phosphorus Tests in Corn**

Gustavo A. Roa, Dorivar A. Ruiz Diaz, Nathan O. Nelson, Ganga M. Hettiarachchi, and Christopher I. Vahl.

## Repository Contents

- **Quarto tutorial:** Code and methods for soil test correlation, Bayesian critical soil test value (CSTV) estimation, and phosphorus fertilizer calibration.
- **Example dataset:** Data to demonstrate the correlation and calibration workflow.

## Interactive Application

The methods are also available through an interactive web application for soil phosphorus test interpretation and fertilizer recommendations in corn.

**App:** [Kansas Corn Phosphorus Explorer](https://gustavo-roa.shinyapps.io/Corn_P_app/)

The application presents soil test interpretations and phosphorus fertilizer recommendations for practical use in Kansas.

## Methods

The workflow includes:
- Estimating CSTVs using Bayesian linear-plateau, quadratic-plateau, and Mitscherlich models.
- Applying Bayesian model averaging to account for uncertainty in CSTV estimation.
- Developing phosphorus fertilizer recommendation functions.

## Requirements

The tutorial uses R and RStudio. Required R packages and setup instructions are provided in the Quarto file.

## Citation

If you use this code or dataset, please cite the associated publication when available.

