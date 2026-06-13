# Spatiotemporal modeling of water demand in California

## Abstract

California faces growing water security challenges driven by climate variability, population growth, and urbanization, yet traditional statistical forecasting methods such as SARIMAX struggle to capture the complex, nonlinear relationships that shape regional water demand. This study compares SARIMAX with XGBoost, a modern gradient-boosting machine learning algorithm, using statewide data that integrate climate conditions, population, and land-use characteristics across California’s ten hydrologic regions. XGBoost achieved substantially higher accuracy, with an R² of 0.99 versus SARIMAX’s 0.87 and 41% and 9% lower MAE and RMSE, respectively. Scenario-based forecasts for 2026, including severe drought, wet year, climate change, and urban expansion conditions, were generated using recursive lagged predictions. Results indicate that severe drought could increase regional water demand by an average of 4%, with the most vulnerable regions nearing 7%. A multi-factor risk assessment combining drought sensitivity, urban intensity, population exposure, and watershed protection identified regions at highest risk under future climate stress. Overall, this work demonstrates that machine learning approaches provide more accurate, flexible, and policy-relevant tools for water-demand forecasting and climate adaptation planning than traditional statistical methods. 

## This Repository

This repository contains all code written for this project, including data exploration, model building and evaluation, and visualization creation.

### The full project website can be found at https://sites.google.com/view/ca-water-modeling/.
