To help you document this project professionally on GitHub, here is a structured README.md template. It balances technical depth with business impact, making it attractive to both recruiters and fellow developers.

Credit Risk Analysis & Prescriptive Lending Strategy
## Project Overview
This project evaluates a dataset of 1,000 credit applicants to identify the primary drivers of loan default. By moving beyond simple descriptive statistics, this analysis identifies high-risk demographic clusters and proposes a set of prescriptive lending constraints to mitigate financial exposure.

The portfolio analyzed currently faces a 30% baseline default rate, with specific segments exceeding 50% probability of default.

## Key Insights
The "Car Loan Trap": Applicants living in free housing with "Little" checking account liquidity exhibit a default rate of 54.2%.

High-Exposure Segments: Homeowners with "Moderate" checking liquidity taking car loans represent the highest average financial loss at R7,931 per customer.

Risk Correlation: Longer loan durations (e.g., 72 months) show a strong positive correlation with increased default rates across all risk profiles.

## Proposed Strategic Constraints
Based on the data findings, the following business rules are recommended:

Liquidity Caps: Implement a hard credit limit of R3,500 for applicants in the "Little" checking account category.

Collateral Requirements: Require a 40% pledged amount (collateral) for segments where average exposure exceeds R7,500.

Duration Reform: Limit maximum loan terms for car purchases to 36 months for high-risk demographic profiles.

## Next Steps: Predictive Modeling
The current phase of this project focuses on Prescriptive Analytics. The next phase involves:

Model Development: Training Machine Learning classification algorithms (Random Forest, XGBoost) to predict individual default probabilities.

Automated Scoring: Building a pipeline to automate approval/rejection based on the identified risk thresholds.

Feature Engineering: Exploring interactive effects between housing status and loan purpose to refine model accuracy.

## Requirements
Python 3.x

Pandas

Matplotlib

Seaborn

Jupyter Notebook

### Note: This project is part of an ongoing initiative to apply data science to financial risk management.
