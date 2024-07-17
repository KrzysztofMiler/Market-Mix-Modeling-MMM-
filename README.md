# Marketing-Mix-Modeling-using-PyMC-Marketing-and-Robyn
## Overview
Welcome to the Marketing Mix Modeling project using PyMC Marketing and Robyn! This project focuses on optimizing marketing expenditures by modeling their impact on sales using probabilistic programming and Bayesian inference.

## Purpose
The goal is to develop a robust model that quantifies the effects of marketing activities on sales and provides insights into the optimal allocation of marketing budgets across different channels. This project showcases the application of advanced statistical techniques in marketing analytics.

## Project Structure
### Data Used
As acquiring real marketing data can be challenging, synthetic data is generated for the purpose of this project.

### Model Implementation
The marketing mix model utilizes PyMC for Bayesian modeling and Robyn for Bayesian regression analysis. These tools enable the estimation of marketing channel effects and the prediction of sales based on marketing spend.

## Methodologies
### PyMC Marketing
Purpose: PyMC Marketing facilitates Bayesian inference and probabilistic programming for modeling marketing effectiveness.

Why it's used: PyMC Marketing provides a flexible framework to quantify uncertainty and optimize marketing strategies with lower computational intensity compared to Robyn.

![image](https://github.com/user-attachments/assets/dfb2d8de-fbb8-4538-b279-ffbb7abfb4fa)
Pictured optimal budget allocation according to PyMC markeing for a total bughet of 10 units.

### Robyn
Purpose: Robyn offers Bayesian regression capabilities, specifically tailored for marketing analytics and decision-making.

Why it's used: Robyn enables the estimation of regression models with Bayesian priors, providing accurate predictions and offering superior visualizations compared to PyMC.

![4_171_7_reallocated_best_roas](https://github.com/user-attachments/assets/6df1a7d8-7f17-4fe7-9343-80865f74ac48)
Pictured is the optimal budget allocation according to Robyn. Without increasing the resources spent, and based on last month's data, it is capable of raising the response rate by more than 50%, potentially reaching up to 60% with a more aggressive strategy.

## Benefits of This Solution
- **Optimized Budget Allocation**: Determines the most effective distribution of marketing budgets across different channels.
- **Quantitative Insights**: Provides quantitative measures of the impact of marketing activities on sales.
- **Uncertainty Estimation**: Accounts for uncertainties and variability in marketing data, leading to more reliable decision-making.
- **Scenario Analysis**: Allows for scenario testing to evaluate the potential outcomes of different marketing strategies.

![image](https://github.com/user-attachments/assets/5603eb37-7231-44c3-803c-faf82521f2e4)
Scenarios generated using PyMC Marketing show that reducing the budget from 10 units to 6 units, increasing from 8 units to 12 units, and further to 18 units results in minimal changes in user response. This suggests that in this scenario, the marketing budget could potentially be reduced by 40% while achieving comparable results.


## Key Features
- **Bayesian Marketing Mix Modeling**: Models the relationship between marketing expenditures and sales using Bayesian statistics.
- **Probabilistic Programming**: Uses PyMC Marketing for flexible Bayesian modeling.
- **Bayesian Regression**: Implements Robyn for Bayesian regression analysis tailored for marketing data.
- **Optimal Budget Allocation**: Enables efficient allocation of marketing funds to maximize ROI.

## Possible Future Directions
**Advanced Modeling Techniques**:  Explore advanced Bayesian models for handling complex marketing scenarios.
**Time Varing Parameters**: Incorporate variability in model parameters to better reflect real-world dynamics.
**Uplift Modeling**: Enhance models with causal inference to improve precision in marketing budget allocation.

## Contact
For inquiries, please contact krzy.miler@gmail.com.
