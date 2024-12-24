# Phase_3_final_project
Telecom Churn Prediction Project
Overview
Customer churn is a critical issue in the telecom industry, leading to significant revenue loss and operational inefficiencies. This project aims to build a predictive model to identify customers at risk of churning, enabling targeted retention strategies. By leveraging data-driven insights, telecom providers can enhance customer satisfaction and reduce churn rates.

Business and Data Understanding
Business Context
Stakeholders:
The primary stakeholders are the management and customer support teams at Syria Tel. Their goal is to identify at-risk customers and implement strategies to retain them, such as offering discounts or improving service quality.

Business Problem:
Customer churn impacts the company's revenue and market competitiveness. Understanding and addressing the factors contributing to churn is crucial to retaining customers.

Dataset
The dataset contains customer information, including demographics, usage patterns, service details, and churn status.
Key attributes include:
Monthly Charges: Monthly fees paid by customers.
Contract Type: Whether the customer has a month-to-month, one-year, or two-year contract.
Customer Service Calls: Number of times a customer contacted support.
Churn Status: Target variable indicating whether a customer churned (1) or stayed (0).
Modeling
Objective: Develop a machine learning model to predict customer churn.
Approach:
Preprocessed the dataset, handling missing values and encoding categorical variables.
Experimented with multiple classification algorithms, including logistic regression, decision trees, and random forests.
Selected the best model based on performance metrics such as accuracy, precision, recall, and ROC AUC score.
Evaluation
Model Performance:

Accuracy: The final model achieved a high accuracy, effectively distinguishing churners from non-churners.
Precision and Recall: Balanced precision and recall ensure the model identifies churners without excessive false positives.
ROC AUC Score: A high score indicates the model's reliability in predicting churn.
Key Features:

Customer service calls and monthly charges were among the most significant predictors of churn.
Conclusion
Findings:
Customers with higher customer service interactions and month-to-month contracts are more likely to churn.
The model provides actionable predictions to prioritize retention efforts.
Recommendations:
Focus retention campaigns on customers flagged as likely to churn.
Address common complaints proactively by improving customer support quality.
Offer incentives for customers to transition from month-to-month to long-term contracts.
Next Steps:
Deploy the model to predict churn in real-time.
Retrain the model periodically with updated data to maintain its accuracy and relevance.
Expand the analysis by incorporating external factors such as competitor pricing and customer feedback.