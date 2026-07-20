# Telco Customer Churn Prediction

This project focuses on predicting customer churn in the telecommunications industry using a hybrid machine learning approach. By combining unsupervised learning for customer segmentation and supervised learning for prediction, we aim to help companies shift from reactive to proactive retention strategies.

## Project Overview
The telecommunications industry faces significant financial challenges due to high customer churn rates. This model identifies high-risk customers, enabling targeted intervention strategies.

## Methodology
The project follows a two-phase technical approach:
1. **Unsupervised Learning**: Implemented **K-Means Clustering** to segment customers into distinct behavioral groups based on tenure, service usage, and charges.
2. **Supervised Learning**: Deployed an **XGBoost Classifier** to predict churn, utilizing class weighting and threshold tuning to handle data imbalance effectively.

## Key Performance Metrics
Our optimized XGBoost model achieved a robust **78.61% accuracy**. The project effectively identifies primary churn drivers, specifically:
- Month-to-month contract types.
- Fiber Optic service issues.
- Behavioral patterns captured by the derived cluster features.

## Project Structure
- `main.ipynb`: The complete data cleaning, exploration, and model training pipeline.
- `final_churn_model_xgb.pkl`: The saved, production-ready XGBoost model.
- `WA_Fn-UseC_-Telco-Customer-Churn.csv`: The dataset used for model training.

## Future Work
- Integrating Natural Language Processing (NLP) to analyze customer complaint texts.
- Experimenting with Deep Learning architectures for more complex behavioral patterns.

## Contact
Developed by **Sobhan Davarzani**. Feel free to reach out if you have any questions regarding the methodology or findings!