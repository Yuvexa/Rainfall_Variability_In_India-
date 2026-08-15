# Rainfall Variability in India: A Statistical Analysis

Welcome to the Rainfall Variability in India project repository! 🌧️

This project presents a statistical analysis of rainfall variability and
extreme rainfall patterns across 36 meteorological regions of India.
Using 121 years of historical rainfall data, the project applies
probability distribution modelling and statistical goodness-of-fit
techniques to identify suitable distributions and estimate extreme
rainfall return levels.

# Project Overview

This project involves:

1. **Data Analysis:** Analyzing 121 years of historical rainfall data
   across 36 meteorological regions of India.

2. **Descriptive Analysis:** Examining regional rainfall characteristics
   using measures such as mean, median, standard deviation, coefficient
   of variation, and skewness.

3. **Probability Distribution Modelling:** Fitting nine probability
   distributions to the extreme rainfall data and estimating their
   parameters using Maximum Likelihood Estimation (MLE).

4. **Model Evaluation:** Comparing the fitted distributions using
   Kolmogorov-Smirnov (K-S), Anderson-Darling (A-D),
   Cramér-von Mises (CVM), and Bayesian Information Criterion (BIC).

5. **Model Selection:** Using a ranking-based approach to identify the
   most suitable probability distribution for each meteorological region.

6. **Return Period Analysis:** Estimating extreme rainfall levels for
   5, 10, 25, 50, 100, and 200-year return periods.

# Project Objectives

The main objectives of this project are:

- To analyze rainfall variability across different regions of India.
- To study the statistical characteristics of extreme rainfall.
- To fit different probability distributions to rainfall data.
- To identify the best-fitting probability distribution for each region.
- To estimate rainfall levels associated with different return periods.
- To provide insights useful for flood-risk assessment, water-resource
  planning, agriculture, and infrastructure planning.

# Dataset

The study uses **121 years of rainfall data from 1901 to 2022**
covering **36 meteorological regions of India**.

The analysis focuses on annual maximum rainfall recorded for the
meteorological regions.

# Statistical Methodology

## 1. Descriptive Analysis

The rainfall data was analyzed using:

- Mean
- Median
- Standard Deviation
- Minimum and Maximum
- Coefficient of Variation
- Coefficient of Skewness

These measures were used to understand the differences in rainfall
patterns and variability across regions.

## 2. Probability Distribution Modelling

Nine probability distributions were considered:

- Normal (N2)
- Lognormal (LN2)
- Pearson Type III (PIII3)
- Log-Pearson Type III (LPIII3)
- Pearson Type V (PV3)
- Gumbel (GUM2)
- Generalized Extreme Value (GEV3)
- Weibull (W2)
- Generalized Pareto (GP3)

Parameters of the distributions were estimated using
**Maximum Likelihood Estimation (MLE)**.

## 3. Goodness-of-Fit & Model Evaluation

The fitted distributions were evaluated using:

- Kolmogorov-Smirnov (K-S) Test
- Anderson-Darling (A-D) Test
- Cramér-von Mises (CVM) Test
- Bayesian Information Criterion (BIC)
- Quantile-Quantile (Q-Q) Plots

A ranking-based scoring approach was used to select the best-fitting
distribution for each region.

# Extreme Rainfall Prediction

The selected probability distributions were used to estimate rainfall
return levels for:

- 5-year
- 10-year
- 25-year
- 50-year
- 100-year
- 200-year

These return levels represent estimated extreme rainfall magnitudes
associated with different return periods.

# Key Findings

- Rainfall variability differs considerably across India's
  meteorological regions.
- Arunachal Pradesh recorded the highest precipitation, while
  West Rajasthan recorded the lowest.
- GEV3 was the most frequently selected best-fitting distribution,
  followed by PIII3, LN2, LPIII3 and GUM2.
- Return-period analysis provided region-specific estimates of
  extreme rainfall levels.

## Applications  

The findings of this project can be useful for:  

Flood-risk assessment  
Water-resource management  
Agricultural planning  
Infrastructure design  
Environmental management  
Extreme rainfall risk analysis 

### The results can support flood-risk assessment and planning related to agriculture, construction, water resources and environmental management.

## Important Note

This project was originally completed as an academic group project.
The repository contains the available project files and the final
project report. Some of the original source-code files are no longer
available, so the repository does not represent the complete original
codebase.

In Short:     
1. The dataset provided here is complete dataset.   
2. The code files provided here are just the available files.  

The included report documents the methodology, statistical modelling,
model selection, results, impact, conclusions and references of the project.
