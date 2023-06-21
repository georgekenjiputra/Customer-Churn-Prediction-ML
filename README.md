# Customer Churn Prediction using Machine Learning

![Image](https://miro.medium.com/v2/resize:fit:1024/1*YRq10sAcj2ScV2TirdSKBg.png)

## Introduction

By: [George Kenji Putra](https://www.linkedin.com/in/georgekenjiputra/)

Dataset: [Telecom Customer Churn]((https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics)

Deployment: For model deployment, please visit here: [Hugging Face](https://huggingface.co/spaces/agayabag/deploy_churn_prediction).

## Objective

The objective of the project is to predict customer churn, which refers to customers leaving a product or service. High churn rates can negatively impact businesses, resulting in lost revenue and customer dissatisfaction. The project aims to analyze factors such as age, gender, marital status, tenure, and total revenue to understand their relationship with churn. By identifying these patterns, the goal is to build a predictive model that accurately identifies customers at risk of leaving.

To achieve this objective, the project uses the evaluation metric recall, which minimizes false negatives. This ensures that the model accurately identifies customers who may churn, preventing missed retention opportunities and potential losses. By developing a better understanding of churn and creating an effective prediction model, businesses can proactively take measures to retain customers, enhance satisfaction, allocate resources efficiently, and mitigate financial impacts. The project provides actionable insights and recommendations to support informed decision-making and implement strategies to reduce churn, ultimately improving overall business performance.

## Conclusion

Churn refers to customers leaving a product or service, and a high churn rate can be problematic. In the plot, 72% of customers stay, while 28% churn, creating data imbalance. Gender doesn't significantly impact churn rates, indicating other factors play a stronger role. Age shows a correlation, with older customers, especially those over 60, more likely to churn. Marital status also influences churn, with married individuals showing higher retention rates. Tenure and total revenue exhibit correlations, as longer tenure and higher revenue contribute to lower churn rates. However, there are outliers where customers with higher revenue still churn, possibly due to other factors.

The evaluation metric used is recall, which measures the proportion of correctly identified positive instances. It helps minimize false negatives and avoid missed retention opportunities, customer dissatisfaction, wasted resources, lost revenue, and reputation damage. The SVC model fits well statistically, but its sensitivity to hyperparameters requires careful optimization to prevent suboptimal performance or overfitting. To improve future results, focus on thorough feature engineering, exploring different algorithms, utilizing methods for imbalanced datasets, and carefully tuning hyperparameters. These steps will enhance the churn prediction model for more accurate and reliable results.
