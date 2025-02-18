# Customer-Churn-Prediction for Subscription-Based Services

This project aimed to develop a predictive model for customer churn in a subscription-based service using historical customer data. The primary objective was to identify customers who are likely to churn (cancel their subscriptions) and enable the business to take proactive actions to retain them. The project involved a series of steps, from data preprocessing and feature engineering to model training, evaluation, and final insights.

# Dataset and Preprocessing:
The dataset used for this project consisted of various customer attributes, such as demographics, subscription details, usage patterns, and service interactions. The preprocessing steps included:

Handling missing values
Encoding categorical features
Scaling numerical features to ensure optimal model performance
Feature selection to remove irrelevant or redundant attributes

# Models Implemented:
The project employed multiple machine learning models to predict churn, including:

Logistic Regression: A simple yet powerful model that applies a linear decision boundary to classify churn and non-churn customers. It is often preferred for its interpretability and efficiency with binary classification tasks.

Decision Tree: A tree-based model that splits data into decision nodes based on feature values. This model is highly interpretable and can handle both categorical and continuous features.

Random Forest: An ensemble learning method that combines multiple decision trees to improve the model’s accuracy and robustness. Random Forest helps reduce overfitting and provides more generalized predictions by averaging the predictions of many individual trees.

# Evaluation Metrics:
The models were evaluated using various metrics, with a key focus on ROC AUC (Area Under the Receiver Operating Characteristic Curve) to assess the classification performance. The following results were achieved:

# Logistic Regression:
Accuracy: 100%
ROC AUC: 1.0
Precision: 1.0
Recall: 1.0
F1-Score: 1.0

# Decision Tree:
Accuracy: 100%
ROC AUC: 1.0
Precision: 1.0
Recall: 1.0
F1-Score: 1.0

# Random Forest:
Accuracy: 92.19%
ROC AUC: 1.0
Precision: 0.88
Recall: 1.0
F1-Score: 0.92
These results indicate that the models performed excellently, with the Logistic Regression and Decision Tree models achieving perfect classification scores. The Random Forest model, while slightly less accurate, still performed well with a high ROC AUC and good precision and recall.

# Churn Score vs. Churn Label:
The project also explored the possibility of using Churn Score instead of Churn Label as the target variable for training the models. While the Churn Label approach simplifies the model by classifying customers into binary categories (churn or not churn), the Churn Score provides a continuous probability value that represents the likelihood of a customer churning. The Churn Score offers a more nuanced understanding of churn risk for each customer, which can be beneficial for targeted retention strategies. However, it introduces challenges related to interpretability, complexity, and subjective decision-making thresholds for churn.

In practice, using Churn Label may be preferable for simpler models or scenarios where interpretability is crucial. However, in cases where businesses need more detailed insights into the probability of churn, Churn Score can be a valuable tool when used appropriately.

# Applications and Insights:
This project has several practical applications for subscription-based services:

Customer Retention: Identifying at-risk customers enables businesses to target retention strategies, such as personalized offers or outreach.
Resource Allocation: Companies can allocate resources more effectively by prioritizing high-risk customers for intervention.
Marketing and Upselling: Understanding churn risk allows businesses to create tailored marketing campaigns aimed at increasing customer engagement and reducing churn.

In conclusion, this project demonstrates the application of machine learning to predict customer churn and highlights the importance of model choice, feature engineering, and evaluation metrics in building an effective churn prediction model. The insights gained from this analysis can inform strategic decisions to improve customer retention, optimize marketing efforts, and drive long-term business growth.
